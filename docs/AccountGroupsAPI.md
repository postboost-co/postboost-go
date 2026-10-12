# \AccountGroupsAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateAccountGroup**](AccountGroupsAPI.md#CreateAccountGroup) | **Post** /{workspaceUuid}/account-groups | Create an account group
[**DeleteAccountGroup**](AccountGroupsAPI.md#DeleteAccountGroup) | **Delete** /{workspaceUuid}/account-groups/{accountGroupUuid} | Delete an account group
[**GetAccountGroup**](AccountGroupsAPI.md#GetAccountGroup) | **Get** /{workspaceUuid}/account-groups/{accountGroupUuid} | Get an account group
[**ListAccountGroups**](AccountGroupsAPI.md#ListAccountGroups) | **Get** /{workspaceUuid}/account-groups | List account groups
[**UpdateAccountGroup**](AccountGroupsAPI.md#UpdateAccountGroup) | **Put** /{workspaceUuid}/account-groups/{accountGroupUuid} | Update an account group



## CreateAccountGroup

> CreateAccountGroup201Response CreateAccountGroup(ctx, workspaceUuid).AccountGroupInput(accountGroupInput).Execute()

Create an account group



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
	accountGroupInput := *openapiclient.NewAccountGroupInput("Name_example") // AccountGroupInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountGroupsAPI.CreateAccountGroup(context.Background(), workspaceUuid).AccountGroupInput(accountGroupInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountGroupsAPI.CreateAccountGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateAccountGroup`: CreateAccountGroup201Response
	fmt.Fprintf(os.Stdout, "Response from `AccountGroupsAPI.CreateAccountGroup`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateAccountGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **accountGroupInput** | [**AccountGroupInput**](AccountGroupInput.md) |  | 

### Return type

[**CreateAccountGroup201Response**](CreateAccountGroup201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteAccountGroup

> DeleteAccountGroup(ctx, workspaceUuid, accountGroupUuid).Execute()

Delete an account group



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
	accountGroupUuid := "accountGroupUuid_example" // string | The account group `uuid`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.AccountGroupsAPI.DeleteAccountGroup(context.Background(), workspaceUuid, accountGroupUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountGroupsAPI.DeleteAccountGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**accountGroupUuid** | **string** | The account group &#x60;uuid&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteAccountGroupRequest struct via the builder pattern


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


## GetAccountGroup

> CreateAccountGroup201Response GetAccountGroup(ctx, workspaceUuid, accountGroupUuid).Execute()

Get an account group



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
	accountGroupUuid := "accountGroupUuid_example" // string | The account group `uuid`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountGroupsAPI.GetAccountGroup(context.Background(), workspaceUuid, accountGroupUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountGroupsAPI.GetAccountGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAccountGroup`: CreateAccountGroup201Response
	fmt.Fprintf(os.Stdout, "Response from `AccountGroupsAPI.GetAccountGroup`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**accountGroupUuid** | **string** | The account group &#x60;uuid&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAccountGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CreateAccountGroup201Response**](CreateAccountGroup201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListAccountGroups

> ListAccountGroups200Response ListAccountGroups(ctx, workspaceUuid).Page(page).PerPage(perPage).Execute()

List account groups



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
	resp, r, err := apiClient.AccountGroupsAPI.ListAccountGroups(context.Background(), workspaceUuid).Page(page).PerPage(perPage).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountGroupsAPI.ListAccountGroups``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListAccountGroups`: ListAccountGroups200Response
	fmt.Fprintf(os.Stdout, "Response from `AccountGroupsAPI.ListAccountGroups`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListAccountGroupsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** | Page number (1-based). | [default to 1]
 **perPage** | **int32** | Items per page, 1-100. | [default to 100]

### Return type

[**ListAccountGroups200Response**](ListAccountGroups200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateAccountGroup

> CreateAccountGroup201Response UpdateAccountGroup(ctx, workspaceUuid, accountGroupUuid).AccountGroupInput(accountGroupInput).Execute()

Update an account group



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
	accountGroupUuid := "accountGroupUuid_example" // string | The account group `uuid`.
	accountGroupInput := *openapiclient.NewAccountGroupInput("Name_example") // AccountGroupInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AccountGroupsAPI.UpdateAccountGroup(context.Background(), workspaceUuid, accountGroupUuid).AccountGroupInput(accountGroupInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AccountGroupsAPI.UpdateAccountGroup``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateAccountGroup`: CreateAccountGroup201Response
	fmt.Fprintf(os.Stdout, "Response from `AccountGroupsAPI.UpdateAccountGroup`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**accountGroupUuid** | **string** | The account group &#x60;uuid&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateAccountGroupRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **accountGroupInput** | [**AccountGroupInput**](AccountGroupInput.md) |  | 

### Return type

[**CreateAccountGroup201Response**](CreateAccountGroup201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

