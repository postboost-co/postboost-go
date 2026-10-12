# \InboxAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ApproveInboxReplyDraft**](InboxAPI.md#ApproveInboxReplyDraft) | **Post** /{workspaceUuid}/inbox/drafts/{draftId}/approve | Approve and send a reply draft
[**CreateInboxReplyDraft**](InboxAPI.md#CreateInboxReplyDraft) | **Post** /{workspaceUuid}/inbox/conversations/{conversationId}/drafts | Draft a reply
[**DeleteInboxReplyDraft**](InboxAPI.md#DeleteInboxReplyDraft) | **Delete** /{workspaceUuid}/inbox/drafts/{draftId} | Withdraw a reply draft
[**GetInboxConversation**](InboxAPI.md#GetInboxConversation) | **Get** /{workspaceUuid}/inbox/conversations/{conversationId} | Get an inbox conversation
[**GetInboxReplyDraft**](InboxAPI.md#GetInboxReplyDraft) | **Get** /{workspaceUuid}/inbox/drafts/{draftId} | Get a reply draft
[**ListInboxConversations**](InboxAPI.md#ListInboxConversations) | **Get** /{workspaceUuid}/inbox/conversations | List inbox conversations
[**ListInboxReplyDrafts**](InboxAPI.md#ListInboxReplyDrafts) | **Get** /{workspaceUuid}/inbox/drafts | List reply drafts
[**RejectInboxReplyDraft**](InboxAPI.md#RejectInboxReplyDraft) | **Post** /{workspaceUuid}/inbox/drafts/{draftId}/reject | Reject a reply draft
[**UpdateInboxConversation**](InboxAPI.md#UpdateInboxConversation) | **Patch** /{workspaceUuid}/inbox/conversations/{conversationId} | Update an inbox conversation
[**UpdateInboxReplyDraft**](InboxAPI.md#UpdateInboxReplyDraft) | **Put** /{workspaceUuid}/inbox/drafts/{draftId} | Edit a reply draft



## ApproveInboxReplyDraft

> CreateInboxReplyDraft201Response ApproveInboxReplyDraft(ctx, workspaceUuid, draftId).InboxReplyDraftApprove(inboxReplyDraftApprove).Execute()

Approve and send a reply draft



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
	draftId := "draftId_example" // string | The draft `id`.
	inboxReplyDraftApprove := *openapiclient.NewInboxReplyDraftApprove() // InboxReplyDraftApprove |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InboxAPI.ApproveInboxReplyDraft(context.Background(), workspaceUuid, draftId).InboxReplyDraftApprove(inboxReplyDraftApprove).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InboxAPI.ApproveInboxReplyDraft``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApproveInboxReplyDraft`: CreateInboxReplyDraft201Response
	fmt.Fprintf(os.Stdout, "Response from `InboxAPI.ApproveInboxReplyDraft`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**draftId** | **string** | The draft &#x60;id&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiApproveInboxReplyDraftRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **inboxReplyDraftApprove** | [**InboxReplyDraftApprove**](InboxReplyDraftApprove.md) |  | 

### Return type

[**CreateInboxReplyDraft201Response**](CreateInboxReplyDraft201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateInboxReplyDraft

> CreateInboxReplyDraft201Response CreateInboxReplyDraft(ctx, workspaceUuid, conversationId).InboxReplyDraftInput(inboxReplyDraftInput).Execute()

Draft a reply



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
	conversationId := "conversationId_example" // string | The conversation `id`.
	inboxReplyDraftInput := *openapiclient.NewInboxReplyDraftInput("Body_example") // InboxReplyDraftInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InboxAPI.CreateInboxReplyDraft(context.Background(), workspaceUuid, conversationId).InboxReplyDraftInput(inboxReplyDraftInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InboxAPI.CreateInboxReplyDraft``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateInboxReplyDraft`: CreateInboxReplyDraft201Response
	fmt.Fprintf(os.Stdout, "Response from `InboxAPI.CreateInboxReplyDraft`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**conversationId** | **string** | The conversation &#x60;id&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateInboxReplyDraftRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **inboxReplyDraftInput** | [**InboxReplyDraftInput**](InboxReplyDraftInput.md) |  | 

### Return type

[**CreateInboxReplyDraft201Response**](CreateInboxReplyDraft201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteInboxReplyDraft

> DeleteInboxReplyDraft(ctx, workspaceUuid, draftId).Execute()

Withdraw a reply draft



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
	draftId := "draftId_example" // string | The draft `id`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.InboxAPI.DeleteInboxReplyDraft(context.Background(), workspaceUuid, draftId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InboxAPI.DeleteInboxReplyDraft``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**draftId** | **string** | The draft &#x60;id&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteInboxReplyDraftRequest struct via the builder pattern


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


## GetInboxConversation

> GetInboxConversation200Response GetInboxConversation(ctx, workspaceUuid, conversationId).Execute()

Get an inbox conversation



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
	conversationId := "conversationId_example" // string | The conversation `id`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InboxAPI.GetInboxConversation(context.Background(), workspaceUuid, conversationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InboxAPI.GetInboxConversation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetInboxConversation`: GetInboxConversation200Response
	fmt.Fprintf(os.Stdout, "Response from `InboxAPI.GetInboxConversation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**conversationId** | **string** | The conversation &#x60;id&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetInboxConversationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**GetInboxConversation200Response**](GetInboxConversation200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetInboxReplyDraft

> CreateInboxReplyDraft201Response GetInboxReplyDraft(ctx, workspaceUuid, draftId).Execute()

Get a reply draft



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
	draftId := "draftId_example" // string | The draft `id`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InboxAPI.GetInboxReplyDraft(context.Background(), workspaceUuid, draftId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InboxAPI.GetInboxReplyDraft``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetInboxReplyDraft`: CreateInboxReplyDraft201Response
	fmt.Fprintf(os.Stdout, "Response from `InboxAPI.GetInboxReplyDraft`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**draftId** | **string** | The draft &#x60;id&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetInboxReplyDraftRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CreateInboxReplyDraft201Response**](CreateInboxReplyDraft201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListInboxConversations

> ListInboxConversations200Response ListInboxConversations(ctx, workspaceUuid).Status(status).AccountId(accountId).Provider(provider).Unread(unread).Sentiment(sentiment).AiLabel(aiLabel).Since(since).Page(page).Execute()

List inbox conversations



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
	status := "status_example" // string | Conversation status. (optional)
	accountId := int32(56) // int32 | Account `id`. (optional)
	provider := "provider_example" // string | Network, for example `bluesky`. (optional)
	unread := true // bool | Only unread (`true`) or read (`false`) conversations. (optional)
	sentiment := "sentiment_example" // string | AI sentiment. (optional)
	aiLabel := "aiLabel_example" // string | AI label. (optional)
	since := time.Now() // time.Time | Only conversations with activity at or after this time. (optional)
	page := int32(56) // int32 | Page number. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InboxAPI.ListInboxConversations(context.Background(), workspaceUuid).Status(status).AccountId(accountId).Provider(provider).Unread(unread).Sentiment(sentiment).AiLabel(aiLabel).Since(since).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InboxAPI.ListInboxConversations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListInboxConversations`: ListInboxConversations200Response
	fmt.Fprintf(os.Stdout, "Response from `InboxAPI.ListInboxConversations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListInboxConversationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **status** | **string** | Conversation status. | 
 **accountId** | **int32** | Account &#x60;id&#x60;. | 
 **provider** | **string** | Network, for example &#x60;bluesky&#x60;. | 
 **unread** | **bool** | Only unread (&#x60;true&#x60;) or read (&#x60;false&#x60;) conversations. | 
 **sentiment** | **string** | AI sentiment. | 
 **aiLabel** | **string** | AI label. | 
 **since** | **time.Time** | Only conversations with activity at or after this time. | 
 **page** | **int32** | Page number. | [default to 1]

### Return type

[**ListInboxConversations200Response**](ListInboxConversations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListInboxReplyDrafts

> ListInboxReplyDrafts200Response ListInboxReplyDrafts(ctx, workspaceUuid).Status(status).ConversationId(conversationId).Page(page).Execute()

List reply drafts



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
	status := "status_example" // string | Draft status. (optional)
	conversationId := "conversationId_example" // string | Only drafts for this conversation `id`. (optional)
	page := int32(56) // int32 | Page number. (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InboxAPI.ListInboxReplyDrafts(context.Background(), workspaceUuid).Status(status).ConversationId(conversationId).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InboxAPI.ListInboxReplyDrafts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListInboxReplyDrafts`: ListInboxReplyDrafts200Response
	fmt.Fprintf(os.Stdout, "Response from `InboxAPI.ListInboxReplyDrafts`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListInboxReplyDraftsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **status** | **string** | Draft status. | 
 **conversationId** | **string** | Only drafts for this conversation &#x60;id&#x60;. | 
 **page** | **int32** | Page number. | [default to 1]

### Return type

[**ListInboxReplyDrafts200Response**](ListInboxReplyDrafts200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RejectInboxReplyDraft

> CreateInboxReplyDraft201Response RejectInboxReplyDraft(ctx, workspaceUuid, draftId).Execute()

Reject a reply draft



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
	draftId := "draftId_example" // string | The draft `id`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InboxAPI.RejectInboxReplyDraft(context.Background(), workspaceUuid, draftId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InboxAPI.RejectInboxReplyDraft``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RejectInboxReplyDraft`: CreateInboxReplyDraft201Response
	fmt.Fprintf(os.Stdout, "Response from `InboxAPI.RejectInboxReplyDraft`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**draftId** | **string** | The draft &#x60;id&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRejectInboxReplyDraftRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CreateInboxReplyDraft201Response**](CreateInboxReplyDraft201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateInboxConversation

> GetInboxConversation200Response UpdateInboxConversation(ctx, workspaceUuid, conversationId).InboxConversationUpdate(inboxConversationUpdate).Execute()

Update an inbox conversation



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
	conversationId := "conversationId_example" // string | The conversation `id`.
	inboxConversationUpdate := *openapiclient.NewInboxConversationUpdate() // InboxConversationUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InboxAPI.UpdateInboxConversation(context.Background(), workspaceUuid, conversationId).InboxConversationUpdate(inboxConversationUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InboxAPI.UpdateInboxConversation``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateInboxConversation`: GetInboxConversation200Response
	fmt.Fprintf(os.Stdout, "Response from `InboxAPI.UpdateInboxConversation`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**conversationId** | **string** | The conversation &#x60;id&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateInboxConversationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **inboxConversationUpdate** | [**InboxConversationUpdate**](InboxConversationUpdate.md) |  | 

### Return type

[**GetInboxConversation200Response**](GetInboxConversation200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateInboxReplyDraft

> CreateInboxReplyDraft201Response UpdateInboxReplyDraft(ctx, workspaceUuid, draftId).InboxReplyDraftEdit(inboxReplyDraftEdit).Execute()

Edit a reply draft



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
	draftId := "draftId_example" // string | The draft `id`.
	inboxReplyDraftEdit := *openapiclient.NewInboxReplyDraftEdit("Body_example") // InboxReplyDraftEdit | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.InboxAPI.UpdateInboxReplyDraft(context.Background(), workspaceUuid, draftId).InboxReplyDraftEdit(inboxReplyDraftEdit).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `InboxAPI.UpdateInboxReplyDraft``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateInboxReplyDraft`: CreateInboxReplyDraft201Response
	fmt.Fprintf(os.Stdout, "Response from `InboxAPI.UpdateInboxReplyDraft`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**draftId** | **string** | The draft &#x60;id&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateInboxReplyDraftRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **inboxReplyDraftEdit** | [**InboxReplyDraftEdit**](InboxReplyDraftEdit.md) |  | 

### Return type

[**CreateInboxReplyDraft201Response**](CreateInboxReplyDraft201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

