# \ActivityAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ListApiActivity**](ActivityAPI.md#ListApiActivity) | **Get** /{workspaceUuid}/activity | List API activity



## ListApiActivity

> ListApiActivity200Response ListApiActivity(ctx, workspaceUuid).Outcome(outcome).Client(client).Since(since).Page(page).Execute()

List API activity



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/postboost-co/postboost-go"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the workspace.
	outcome := openapiclient.ApiActivityOutcome("created") // ApiActivityOutcome |  (optional)
	client := "client_example" // string | Client label prefix, for example `mcp`. (optional)
	since := time.Now() // time.Time | Only entries at or after this time (UTC). (optional)
	page := int32(56) // int32 |  (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ActivityAPI.ListApiActivity(context.Background(), workspaceUuid).Outcome(outcome).Client(client).Since(since).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ActivityAPI.ListApiActivity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListApiActivity`: ListApiActivity200Response
	fmt.Fprintf(os.Stdout, "Response from `ActivityAPI.ListApiActivity`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListApiActivityRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **outcome** | [**ApiActivityOutcome**](ApiActivityOutcome.md) |  | 
 **client** | **string** | Client label prefix, for example &#x60;mcp&#x60;. | 
 **since** | **time.Time** | Only entries at or after this time (UTC). | 
 **page** | **int32** |  | [default to 1]

### Return type

[**ListApiActivity200Response**](ListApiActivity200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

