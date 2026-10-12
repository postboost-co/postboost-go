# \PostingScheduleAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetPostingSchedule**](PostingScheduleAPI.md#GetPostingSchedule) | **Get** /{workspaceUuid}/posting-schedule | Get the posting schedule
[**GetRecommendedPostingTimes**](PostingScheduleAPI.md#GetRecommendedPostingTimes) | **Get** /{workspaceUuid}/posting-schedule/recommended | Get recommended posting times
[**ListQueueSlots**](PostingScheduleAPI.md#ListQueueSlots) | **Get** /{workspaceUuid}/queue/slots | List upcoming queue slots
[**ResetAccountPostingSchedule**](PostingScheduleAPI.md#ResetAccountPostingSchedule) | **Delete** /{workspaceUuid}/posting-schedule/{accountId} | Reset an account schedule
[**UpdatePostingSchedule**](PostingScheduleAPI.md#UpdatePostingSchedule) | **Put** /{workspaceUuid}/posting-schedule | Set the posting schedule



## GetPostingSchedule

> GetPostingSchedule200Response GetPostingSchedule(ctx, workspaceUuid).AccountId(accountId).Execute()

Get the posting schedule



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
	accountId := int32(56) // int32 | `0` (default) for the workspace schedule, or an account `id`. (optional) (default to 0)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostingScheduleAPI.GetPostingSchedule(context.Background(), workspaceUuid).AccountId(accountId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostingScheduleAPI.GetPostingSchedule``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPostingSchedule`: GetPostingSchedule200Response
	fmt.Fprintf(os.Stdout, "Response from `PostingScheduleAPI.GetPostingSchedule`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPostingScheduleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **accountId** | **int32** | &#x60;0&#x60; (default) for the workspace schedule, or an account &#x60;id&#x60;. | [default to 0]

### Return type

[**GetPostingSchedule200Response**](GetPostingSchedule200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRecommendedPostingTimes

> RecommendedPostingTimes GetRecommendedPostingTimes(ctx, workspaceUuid).AccountId(accountId).SlotsPerDay(slotsPerDay).Execute()

Get recommended posting times



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
	accountId := int32(56) // int32 | `0` (default) for the workspace schedule, or an account `id`. (optional) (default to 0)
	slotsPerDay := int32(56) // int32 | Times to suggest per day (1 to 6). (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostingScheduleAPI.GetRecommendedPostingTimes(context.Background(), workspaceUuid).AccountId(accountId).SlotsPerDay(slotsPerDay).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostingScheduleAPI.GetRecommendedPostingTimes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRecommendedPostingTimes`: RecommendedPostingTimes
	fmt.Fprintf(os.Stdout, "Response from `PostingScheduleAPI.GetRecommendedPostingTimes`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetRecommendedPostingTimesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **accountId** | **int32** | &#x60;0&#x60; (default) for the workspace schedule, or an account &#x60;id&#x60;. | [default to 0]
 **slotsPerDay** | **int32** | Times to suggest per day (1 to 6). | 

### Return type

[**RecommendedPostingTimes**](RecommendedPostingTimes.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListQueueSlots

> QueueSlots ListQueueSlots(ctx, workspaceUuid).AccountId(accountId).After(after).Execute()

List upcoming queue slots



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
	accountId := int32(56) // int32 | `0` (default) for the workspace schedule, or an account `id`. (optional) (default to 0)
	after := "after_example" // string | Start after this time (`Y-m-d H:i:s`, UTC), from `next_cursor`. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostingScheduleAPI.ListQueueSlots(context.Background(), workspaceUuid).AccountId(accountId).After(after).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostingScheduleAPI.ListQueueSlots``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListQueueSlots`: QueueSlots
	fmt.Fprintf(os.Stdout, "Response from `PostingScheduleAPI.ListQueueSlots`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListQueueSlotsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **accountId** | **int32** | &#x60;0&#x60; (default) for the workspace schedule, or an account &#x60;id&#x60;. | [default to 0]
 **after** | **string** | Start after this time (&#x60;Y-m-d H:i:s&#x60;, UTC), from &#x60;next_cursor&#x60;. | 

### Return type

[**QueueSlots**](QueueSlots.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ResetAccountPostingSchedule

> GetPostingSchedule200Response ResetAccountPostingSchedule(ctx, workspaceUuid, accountId).Execute()

Reset an account schedule



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
	accountId := int32(56) // int32 | The account `id`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostingScheduleAPI.ResetAccountPostingSchedule(context.Background(), workspaceUuid, accountId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostingScheduleAPI.ResetAccountPostingSchedule``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ResetAccountPostingSchedule`: GetPostingSchedule200Response
	fmt.Fprintf(os.Stdout, "Response from `PostingScheduleAPI.ResetAccountPostingSchedule`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**accountId** | **int32** | The account &#x60;id&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiResetAccountPostingScheduleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**GetPostingSchedule200Response**](GetPostingSchedule200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePostingSchedule

> GetPostingSchedule200Response UpdatePostingSchedule(ctx, workspaceUuid).PostingScheduleInput(postingScheduleInput).Execute()

Set the posting schedule



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
	postingScheduleInput := *openapiclient.NewPostingScheduleInput(int32(123), "Europe/Amsterdam", []openapiclient.PostingScheduleDay{*openapiclient.NewPostingScheduleDay(int32(123), false, []openapiclient.PostingScheduleDayTimesInner{*openapiclient.NewPostingScheduleDayTimesInner("09:00")})}) // PostingScheduleInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostingScheduleAPI.UpdatePostingSchedule(context.Background(), workspaceUuid).PostingScheduleInput(postingScheduleInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostingScheduleAPI.UpdatePostingSchedule``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePostingSchedule`: GetPostingSchedule200Response
	fmt.Fprintf(os.Stdout, "Response from `PostingScheduleAPI.UpdatePostingSchedule`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePostingScheduleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **postingScheduleInput** | [**PostingScheduleInput**](PostingScheduleInput.md) |  | 

### Return type

[**GetPostingSchedule200Response**](GetPostingSchedule200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

