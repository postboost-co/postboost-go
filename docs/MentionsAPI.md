# \MentionsAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateMention**](MentionsAPI.md#CreateMention) | **Post** /{workspaceUuid}/mentions | Create mention
[**DeleteMention**](MentionsAPI.md#DeleteMention) | **Delete** /{workspaceUuid}/mentions/{mentionId} | Delete mention
[**GetMention**](MentionsAPI.md#GetMention) | **Get** /{workspaceUuid}/mentions/{mentionId} | Get mention
[**ListMentions**](MentionsAPI.md#ListMentions) | **Get** /{workspaceUuid}/mentions | List mentions
[**UpdateMention**](MentionsAPI.md#UpdateMention) | **Put** /{workspaceUuid}/mentions/{mentionId} | Update mention



## CreateMention

> CreateMention201Response CreateMention(ctx, workspaceUuid).MentionInput(mentionInput).Execute()

Create mention



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
	mentionInput := *openapiclient.NewMentionInput("Name_example") // MentionInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MentionsAPI.CreateMention(context.Background(), workspaceUuid).MentionInput(mentionInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MentionsAPI.CreateMention``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateMention`: CreateMention201Response
	fmt.Fprintf(os.Stdout, "Response from `MentionsAPI.CreateMention`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateMentionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **mentionInput** | [**MentionInput**](MentionInput.md) |  | 

### Return type

[**CreateMention201Response**](CreateMention201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteMention

> map[string]interface{} DeleteMention(ctx, workspaceUuid, mentionId).Execute()

Delete mention



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
	mentionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The mention's `id` (a UUID).

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MentionsAPI.DeleteMention(context.Background(), workspaceUuid, mentionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MentionsAPI.DeleteMention``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteMention`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `MentionsAPI.DeleteMention`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**mentionId** | **string** | The mention&#39;s &#x60;id&#x60; (a UUID). | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteMentionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

**map[string]interface{}**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetMention

> CreateMention201Response GetMention(ctx, workspaceUuid, mentionId).Execute()

Get mention



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
	mentionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The mention's `id` (a UUID).

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MentionsAPI.GetMention(context.Background(), workspaceUuid, mentionId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MentionsAPI.GetMention``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMention`: CreateMention201Response
	fmt.Fprintf(os.Stdout, "Response from `MentionsAPI.GetMention`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**mentionId** | **string** | The mention&#39;s &#x60;id&#x60; (a UUID). | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetMentionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CreateMention201Response**](CreateMention201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListMentions

> ListMentions200Response ListMentions(ctx, workspaceUuid).Q(q).PerPage(perPage).Page(page).Execute()

List mentions



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
	q := "q_example" // string | Search keyword. (optional)
	perPage := int32(56) // int32 |  (optional) (default to 25)
	page := int32(56) // int32 |  (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MentionsAPI.ListMentions(context.Background(), workspaceUuid).Q(q).PerPage(perPage).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MentionsAPI.ListMentions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListMentions`: ListMentions200Response
	fmt.Fprintf(os.Stdout, "Response from `MentionsAPI.ListMentions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListMentionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **q** | **string** | Search keyword. | 
 **perPage** | **int32** |  | [default to 25]
 **page** | **int32** |  | [default to 1]

### Return type

[**ListMentions200Response**](ListMentions200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateMention

> CreateMention201Response UpdateMention(ctx, workspaceUuid, mentionId).MentionInput(mentionInput).Execute()

Update mention



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
	mentionId := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | The mention's `id` (a UUID).
	mentionInput := *openapiclient.NewMentionInput("Name_example") // MentionInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MentionsAPI.UpdateMention(context.Background(), workspaceUuid, mentionId).MentionInput(mentionInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MentionsAPI.UpdateMention``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateMention`: CreateMention201Response
	fmt.Fprintf(os.Stdout, "Response from `MentionsAPI.UpdateMention`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**mentionId** | **string** | The mention&#39;s &#x60;id&#x60; (a UUID). | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateMentionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **mentionInput** | [**MentionInput**](MentionInput.md) |  | 

### Return type

[**CreateMention201Response**](CreateMention201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

