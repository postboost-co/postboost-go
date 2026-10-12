# \HashtagGroupsAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateHashtagGroup**](HashtagGroupsAPI.md#CreateHashtagGroup) | **Post** /{workspaceUuid}/hashtag-groups | Create a hashtag group
[**DeleteHashtagGroup**](HashtagGroupsAPI.md#DeleteHashtagGroup) | **Delete** /{workspaceUuid}/hashtag-groups/{hashtagGroupId} | Delete a hashtag group
[**GetHashtagGroup**](HashtagGroupsAPI.md#GetHashtagGroup) | **Get** /{workspaceUuid}/hashtag-groups/{hashtagGroupId} | Get a hashtag group
[**ListHashtagGroups**](HashtagGroupsAPI.md#ListHashtagGroups) | **Get** /{workspaceUuid}/hashtag-groups | List hashtag groups
[**UpdateHashtagGroup**](HashtagGroupsAPI.md#UpdateHashtagGroup) | **Put** /{workspaceUuid}/hashtag-groups/{hashtagGroupId} | Update a hashtag group



## CreateHashtagGroup

> CreateHashtagGroup201Response CreateHashtagGroup(ctx, workspaceUuid).HashtagGroupInput(hashtagGroupInput).Execute()

Create a hashtag group



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/postboost-co/postboost-go"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the workspace.
	hashtagGroupInput := *openapiclient.NewHashtagGroupInput("Name_example", "Content_example") // HashtagGroupInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HashtagGroupsAPI.CreateHashtagGroup(context.Background(), workspaceUuid).HashtagGroupInput(hashtagGroupInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HashtagGroupsAPI.CreateHashtagGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateHashtagGroup`: CreateHashtagGroup201Response
	fmt.Fprintf(os.Stdout, "Response from `HashtagGroupsAPI.CreateHashtagGroup`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateHashtagGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **hashtagGroupInput** | [**HashtagGroupInput**](HashtagGroupInput.md) |  | 

### Return type

[**CreateHashtagGroup201Response**](CreateHashtagGroup201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteHashtagGroup

> DeleteHashtagGroup(ctx, workspaceUuid, hashtagGroupId).Execute()

Delete a hashtag group



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/postboost-co/postboost-go"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the workspace.
	hashtagGroupId := "hashtagGroupId_example" // string | The hashtag group `id`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.HashtagGroupsAPI.DeleteHashtagGroup(context.Background(), workspaceUuid, hashtagGroupId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HashtagGroupsAPI.DeleteHashtagGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**hashtagGroupId** | **string** | The hashtag group &#x60;id&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteHashtagGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

 (empty response body)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetHashtagGroup

> CreateHashtagGroup201Response GetHashtagGroup(ctx, workspaceUuid, hashtagGroupId).Execute()

Get a hashtag group



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/postboost-co/postboost-go"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the workspace.
	hashtagGroupId := "hashtagGroupId_example" // string | The hashtag group `id`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HashtagGroupsAPI.GetHashtagGroup(context.Background(), workspaceUuid, hashtagGroupId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HashtagGroupsAPI.GetHashtagGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetHashtagGroup`: CreateHashtagGroup201Response
	fmt.Fprintf(os.Stdout, "Response from `HashtagGroupsAPI.GetHashtagGroup`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**hashtagGroupId** | **string** | The hashtag group &#x60;id&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetHashtagGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CreateHashtagGroup201Response**](CreateHashtagGroup201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListHashtagGroups

> ListHashtagGroups200Response ListHashtagGroups(ctx, workspaceUuid).Page(page).PerPage(perPage).Execute()

List hashtag groups



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/postboost-co/postboost-go"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the workspace.
	page := int32(56) // int32 | Page number (1-based). (optional) (default to 1)
	perPage := int32(56) // int32 | Items per page, 1-100. (optional) (default to 100)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HashtagGroupsAPI.ListHashtagGroups(context.Background(), workspaceUuid).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HashtagGroupsAPI.ListHashtagGroups``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListHashtagGroups`: ListHashtagGroups200Response
	fmt.Fprintf(os.Stdout, "Response from `HashtagGroupsAPI.ListHashtagGroups`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListHashtagGroupsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** | Page number (1-based). | [default to 1]
 **perPage** | **int32** | Items per page, 1-100. | [default to 100]

### Return type

[**ListHashtagGroups200Response**](ListHashtagGroups200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateHashtagGroup

> CreateHashtagGroup201Response UpdateHashtagGroup(ctx, workspaceUuid, hashtagGroupId).HashtagGroupInput(hashtagGroupInput).Execute()

Update a hashtag group



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/postboost-co/postboost-go"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the workspace.
	hashtagGroupId := "hashtagGroupId_example" // string | The hashtag group `id`.
	hashtagGroupInput := *openapiclient.NewHashtagGroupInput("Name_example", "Content_example") // HashtagGroupInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.HashtagGroupsAPI.UpdateHashtagGroup(context.Background(), workspaceUuid, hashtagGroupId).HashtagGroupInput(hashtagGroupInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `HashtagGroupsAPI.UpdateHashtagGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateHashtagGroup`: CreateHashtagGroup201Response
	fmt.Fprintf(os.Stdout, "Response from `HashtagGroupsAPI.UpdateHashtagGroup`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**hashtagGroupId** | **string** | The hashtag group &#x60;id&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateHashtagGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **hashtagGroupInput** | [**HashtagGroupInput**](HashtagGroupInput.md) |  | 

### Return type

[**CreateHashtagGroup201Response**](CreateHashtagGroup201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

