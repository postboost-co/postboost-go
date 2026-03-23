# \WorkspacesAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddUserToWorkspace**](WorkspacesAPI.md#AddUserToWorkspace) | **Post** /panel/workspaces/{workspaceUuid}/users | Add user to workspace
[**CreateWorkspace**](WorkspacesAPI.md#CreateWorkspace) | **Post** /panel/workspaces | Create workspace
[**DeleteWorkspace**](WorkspacesAPI.md#DeleteWorkspace) | **Delete** /panel/workspaces/{workspaceUuid} | Delete workspace
[**DeleteWorkspacesBulk**](WorkspacesAPI.md#DeleteWorkspacesBulk) | **Delete** /panel/workspaces | Delete workspaces (bulk)
[**GetWorkspace**](WorkspacesAPI.md#GetWorkspace) | **Get** /panel/workspaces/{workspaceUuid} | Get workspace
[**ListWorkspaces**](WorkspacesAPI.md#ListWorkspaces) | **Get** /panel/workspaces | List workspaces
[**RemoveUserFromWorkspace**](WorkspacesAPI.md#RemoveUserFromWorkspace) | **Delete** /panel/workspaces/{workspaceUuid}/users | Remove user from workspace
[**UpdateWorkspace**](WorkspacesAPI.md#UpdateWorkspace) | **Put** /panel/workspaces/{workspaceUuid} | Update workspace
[**UpdateWorkspaceUser**](WorkspacesAPI.md#UpdateWorkspaceUser) | **Put** /panel/workspaces/{workspaceUuid}/users | Update user role in workspace



## AddUserToWorkspace

> map[string]interface{} AddUserToWorkspace(ctx, workspaceUuid).WorkspaceUserInput(workspaceUserInput).Execute()

Add user to workspace



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
	workspaceUserInput := *openapiclient.NewWorkspaceUserInput(int32(123), "Role_example", false, false) // WorkspaceUserInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.AddUserToWorkspace(context.Background(), workspaceUuid).WorkspaceUserInput(workspaceUserInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.AddUserToWorkspace``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddUserToWorkspace`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.AddUserToWorkspace`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddUserToWorkspaceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **workspaceUserInput** | [**WorkspaceUserInput**](WorkspaceUserInput.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateWorkspace

> Workspace CreateWorkspace(ctx).WorkspaceInput(workspaceInput).Execute()

Create workspace



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
	workspaceInput := *openapiclient.NewWorkspaceInput("Name_example", "#1d4ed8", "AccessStatus_example") // WorkspaceInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.CreateWorkspace(context.Background()).WorkspaceInput(workspaceInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.CreateWorkspace``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateWorkspace`: Workspace
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.CreateWorkspace`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateWorkspaceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **workspaceInput** | [**WorkspaceInput**](WorkspaceInput.md) |  | 

### Return type

[**Workspace**](Workspace.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteWorkspace

> map[string]interface{} DeleteWorkspace(ctx, workspaceUuid).Execute()

Delete workspace



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.DeleteWorkspace(context.Background(), workspaceUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.DeleteWorkspace``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteWorkspace`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.DeleteWorkspace`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteWorkspaceRequest struct via the builder pattern


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


## DeleteWorkspacesBulk

> map[string]interface{} DeleteWorkspacesBulk(ctx).DeleteWorkspacesBulkRequest(deleteWorkspacesBulkRequest).Execute()

Delete workspaces (bulk)



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
	deleteWorkspacesBulkRequest := *openapiclient.NewDeleteWorkspacesBulkRequest([]string{"Workspaces_example"}) // DeleteWorkspacesBulkRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.DeleteWorkspacesBulk(context.Background()).DeleteWorkspacesBulkRequest(deleteWorkspacesBulkRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.DeleteWorkspacesBulk``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteWorkspacesBulk`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.DeleteWorkspacesBulk`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDeleteWorkspacesBulkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **deleteWorkspacesBulkRequest** | [**DeleteWorkspacesBulkRequest**](DeleteWorkspacesBulkRequest.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetWorkspace

> Workspace GetWorkspace(ctx, workspaceUuid).Execute()

Get workspace



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.GetWorkspace(context.Background(), workspaceUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.GetWorkspace``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetWorkspace`: Workspace
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.GetWorkspace`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetWorkspaceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Workspace**](Workspace.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListWorkspaces

> ListWorkspaces200Response ListWorkspaces(ctx).Keyword(keyword).SubscriptionStatus(subscriptionStatus).AccessStatus(accessStatus).Page(page).Execute()

List workspaces



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
	keyword := "keyword_example" // string |  (optional)
	subscriptionStatus := "subscriptionStatus_example" // string |  (optional)
	accessStatus := "accessStatus_example" // string |  (optional)
	page := int32(56) // int32 | Page number (15 items per page). (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.ListWorkspaces(context.Background()).Keyword(keyword).SubscriptionStatus(subscriptionStatus).AccessStatus(accessStatus).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.ListWorkspaces``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWorkspaces`: ListWorkspaces200Response
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.ListWorkspaces`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListWorkspacesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **keyword** | **string** |  | 
 **subscriptionStatus** | **string** |  | 
 **accessStatus** | **string** |  | 
 **page** | **int32** | Page number (15 items per page). | [default to 1]

### Return type

[**ListWorkspaces200Response**](ListWorkspaces200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RemoveUserFromWorkspace

> map[string]interface{} RemoveUserFromWorkspace(ctx, workspaceUuid).RemoveUserFromWorkspaceRequest(removeUserFromWorkspaceRequest).Execute()

Remove user from workspace



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
	removeUserFromWorkspaceRequest := *openapiclient.NewRemoveUserFromWorkspaceRequest(int32(123)) // RemoveUserFromWorkspaceRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.RemoveUserFromWorkspace(context.Background(), workspaceUuid).RemoveUserFromWorkspaceRequest(removeUserFromWorkspaceRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.RemoveUserFromWorkspace``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RemoveUserFromWorkspace`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.RemoveUserFromWorkspace`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRemoveUserFromWorkspaceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **removeUserFromWorkspaceRequest** | [**RemoveUserFromWorkspaceRequest**](RemoveUserFromWorkspaceRequest.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateWorkspace

> map[string]interface{} UpdateWorkspace(ctx, workspaceUuid).WorkspaceInput(workspaceInput).Execute()

Update workspace



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
	workspaceInput := *openapiclient.NewWorkspaceInput("Name_example", "#1d4ed8", "AccessStatus_example") // WorkspaceInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.UpdateWorkspace(context.Background(), workspaceUuid).WorkspaceInput(workspaceInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.UpdateWorkspace``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateWorkspace`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.UpdateWorkspace`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateWorkspaceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **workspaceInput** | [**WorkspaceInput**](WorkspaceInput.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateWorkspaceUser

> map[string]interface{} UpdateWorkspaceUser(ctx, workspaceUuid).WorkspaceUserInput(workspaceUserInput).Execute()

Update user role in workspace



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
	workspaceUserInput := *openapiclient.NewWorkspaceUserInput(int32(123), "Role_example", false, false) // WorkspaceUserInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WorkspacesAPI.UpdateWorkspaceUser(context.Background(), workspaceUuid).WorkspaceUserInput(workspaceUserInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WorkspacesAPI.UpdateWorkspaceUser``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateWorkspaceUser`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `WorkspacesAPI.UpdateWorkspaceUser`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateWorkspaceUserRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **workspaceUserInput** | [**WorkspaceUserInput**](WorkspaceUserInput.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

