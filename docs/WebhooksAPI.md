# \WebhooksAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateWebhookSubscription**](WebhooksAPI.md#CreateWebhookSubscription) | **Post** /{workspaceUuid}/webhooks/subscriptions | Subscribe a webhook
[**DeleteWebhookSubscription**](WebhooksAPI.md#DeleteWebhookSubscription) | **Delete** /{workspaceUuid}/webhooks/subscriptions/{subscriptionUuid} | Unsubscribe a webhook
[**ListWebhookSubscriptions**](WebhooksAPI.md#ListWebhookSubscriptions) | **Get** /{workspaceUuid}/webhooks/subscriptions | List webhook subscriptions



## CreateWebhookSubscription

> CreateWebhookSubscription201Response CreateWebhookSubscription(ctx, workspaceUuid).WebhookSubscriptionInput(webhookSubscriptionInput).Execute()

Subscribe a webhook



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
	webhookSubscriptionInput := *openapiclient.NewWebhookSubscriptionInput("CallbackUrl_example", []openapiclient.WebhookEventName{openapiclient.WebhookEventName("post.scheduled")}) // WebhookSubscriptionInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksAPI.CreateWebhookSubscription(context.Background(), workspaceUuid).WebhookSubscriptionInput(webhookSubscriptionInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.CreateWebhookSubscription``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateWebhookSubscription`: CreateWebhookSubscription201Response
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.CreateWebhookSubscription`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateWebhookSubscriptionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **webhookSubscriptionInput** | [**WebhookSubscriptionInput**](WebhookSubscriptionInput.md) |  | 

### Return type

[**CreateWebhookSubscription201Response**](CreateWebhookSubscription201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteWebhookSubscription

> map[string]interface{} DeleteWebhookSubscription(ctx, workspaceUuid, subscriptionUuid).Execute()

Unsubscribe a webhook



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
	subscriptionUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the webhook subscription.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WebhooksAPI.DeleteWebhookSubscription(context.Background(), workspaceUuid, subscriptionUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.DeleteWebhookSubscription``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteWebhookSubscription`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.DeleteWebhookSubscription`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**subscriptionUuid** | **string** | UUID of the webhook subscription. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteWebhookSubscriptionRequest struct via the builder pattern


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


## ListWebhookSubscriptions

> ListWebhookSubscriptions200Response ListWebhookSubscriptions(ctx, workspaceUuid).Execute()

List webhook subscriptions



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
	resp, r, err := apiClient.WebhooksAPI.ListWebhookSubscriptions(context.Background(), workspaceUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WebhooksAPI.ListWebhookSubscriptions``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListWebhookSubscriptions`: ListWebhookSubscriptions200Response
	fmt.Fprintf(os.Stdout, "Response from `WebhooksAPI.ListWebhookSubscriptions`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListWebhookSubscriptionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListWebhookSubscriptions200Response**](ListWebhookSubscriptions200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

