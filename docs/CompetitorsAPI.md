# \CompetitorsAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddCompetitor**](CompetitorsAPI.md#AddCompetitor) | **Post** /{workspaceUuid}/competitors | Track a competitor
[**DeleteCompetitor**](CompetitorsAPI.md#DeleteCompetitor) | **Delete** /{workspaceUuid}/competitors/{competitorId} | Stop tracking a competitor
[**GetCompetitor**](CompetitorsAPI.md#GetCompetitor) | **Get** /{workspaceUuid}/competitors/{competitorId} | Get a competitor
[**ListCompetitors**](CompetitorsAPI.md#ListCompetitors) | **Get** /{workspaceUuid}/competitors | List competitors



## AddCompetitor

> AddCompetitor202Response AddCompetitor(ctx, workspaceUuid).CompetitorInput(competitorInput).Execute()

Track a competitor



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
	competitorInput := *openapiclient.NewCompetitorInput(int32(123), "natgeo") // CompetitorInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CompetitorsAPI.AddCompetitor(context.Background(), workspaceUuid).CompetitorInput(competitorInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CompetitorsAPI.AddCompetitor``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddCompetitor`: AddCompetitor202Response
	fmt.Fprintf(os.Stdout, "Response from `CompetitorsAPI.AddCompetitor`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddCompetitorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **competitorInput** | [**CompetitorInput**](CompetitorInput.md) |  | 

### Return type

[**AddCompetitor202Response**](AddCompetitor202Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteCompetitor

> DeleteCompetitor(ctx, workspaceUuid, competitorId).Execute()

Stop tracking a competitor



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
	competitorId := int32(56) // int32 | The competitor `id`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.CompetitorsAPI.DeleteCompetitor(context.Background(), workspaceUuid, competitorId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CompetitorsAPI.DeleteCompetitor``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**competitorId** | **int32** | The competitor &#x60;id&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteCompetitorRequest struct via the builder pattern


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


## GetCompetitor

> GetCompetitor200Response GetCompetitor(ctx, workspaceUuid, competitorId).Execute()

Get a competitor



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
	competitorId := int32(56) // int32 | The competitor `id`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CompetitorsAPI.GetCompetitor(context.Background(), workspaceUuid, competitorId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CompetitorsAPI.GetCompetitor``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetCompetitor`: GetCompetitor200Response
	fmt.Fprintf(os.Stdout, "Response from `CompetitorsAPI.GetCompetitor`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**competitorId** | **int32** | The competitor &#x60;id&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetCompetitorRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**GetCompetitor200Response**](GetCompetitor200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListCompetitors

> ListCompetitors200Response ListCompetitors(ctx, workspaceUuid).AccountId(accountId).Execute()

List competitors



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
	accountId := int32(56) // int32 | Only competitors tracked from this Instagram account `id`. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.CompetitorsAPI.ListCompetitors(context.Background(), workspaceUuid).AccountId(accountId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `CompetitorsAPI.ListCompetitors``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListCompetitors`: ListCompetitors200Response
	fmt.Fprintf(os.Stdout, "Response from `CompetitorsAPI.ListCompetitors`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListCompetitorsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **accountId** | **int32** | Only competitors tracked from this Instagram account &#x60;id&#x60;. | 

### Return type

[**ListCompetitors200Response**](ListCompetitors200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

