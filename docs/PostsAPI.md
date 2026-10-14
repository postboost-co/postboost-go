# \PostsAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddPostToQueue**](PostsAPI.md#AddPostToQueue) | **Post** /{workspaceUuid}/posts/add-to-queue/{postUuid} | Add post to queue
[**ApprovePost**](PostsAPI.md#ApprovePost) | **Post** /{workspaceUuid}/posts/approve/{postUuid} | Approve post
[**CreatePost**](PostsAPI.md#CreatePost) | **Post** /{workspaceUuid}/posts | Create post
[**CreateRecyclingRule**](PostsAPI.md#CreateRecyclingRule) | **Post** /{workspaceUuid}/recycling-rules | Create a recycling rule
[**CreateRssFeed**](PostsAPI.md#CreateRssFeed) | **Post** /{workspaceUuid}/rss-feeds | Add an RSS feed
[**DeletePost**](PostsAPI.md#DeletePost) | **Delete** /{workspaceUuid}/posts/{postUuid} | Delete post
[**DeletePostsBulk**](PostsAPI.md#DeletePostsBulk) | **Delete** /{workspaceUuid}/posts | Delete posts (bulk)
[**DeleteRecyclingRule**](PostsAPI.md#DeleteRecyclingRule) | **Delete** /{workspaceUuid}/recycling-rules/{ruleUuid} | Delete a recycling rule
[**DeleteRssFeed**](PostsAPI.md#DeleteRssFeed) | **Delete** /{workspaceUuid}/rss-feeds/{feedUuid} | Delete an RSS feed
[**GetPost**](PostsAPI.md#GetPost) | **Get** /{workspaceUuid}/posts/{postUuid} | Get post
[**GetPostAnalytics**](PostsAPI.md#GetPostAnalytics) | **Get** /{workspaceUuid}/posts/{postUuid}/analytics | Get post analytics
[**GetRecyclingRule**](PostsAPI.md#GetRecyclingRule) | **Get** /{workspaceUuid}/recycling-rules/{ruleUuid} | Get a recycling rule
[**GetRssFeed**](PostsAPI.md#GetRssFeed) | **Get** /{workspaceUuid}/rss-feeds/{feedUuid} | Get an RSS feed
[**ListPosts**](PostsAPI.md#ListPosts) | **Get** /{workspaceUuid}/posts | List posts
[**ListRecyclingRules**](PostsAPI.md#ListRecyclingRules) | **Get** /{workspaceUuid}/recycling-rules | List recycling rules
[**ListRecyclingRuns**](PostsAPI.md#ListRecyclingRuns) | **Get** /{workspaceUuid}/recycling-rules/{ruleUuid}/runs | List a recycling rule&#39;s runs
[**ListRssFeeds**](PostsAPI.md#ListRssFeeds) | **Get** /{workspaceUuid}/rss-feeds | List RSS feeds
[**PollRssFeed**](PostsAPI.md#PollRssFeed) | **Post** /{workspaceUuid}/rss-feeds/{feedUuid}/poll | Check an RSS feed now
[**RecyclePost**](PostsAPI.md#RecyclePost) | **Post** /{workspaceUuid}/posts/{postUuid}/recycle | Recycle a post on an interval
[**RetryPostAccount**](PostsAPI.md#RetryPostAccount) | **Post** /{workspaceUuid}/posts/retry/{postUuid}/{accountUuid} | Retry publishing to one account
[**SchedulePost**](PostsAPI.md#SchedulePost) | **Post** /{workspaceUuid}/posts/schedule/{postUuid} | Schedule post
[**UpdatePost**](PostsAPI.md#UpdatePost) | **Put** /{workspaceUuid}/posts/{postUuid} | Update post
[**UpdateRecyclingRule**](PostsAPI.md#UpdateRecyclingRule) | **Put** /{workspaceUuid}/recycling-rules/{ruleUuid} | Update, pause or resume a recycling rule
[**UpdateRssFeed**](PostsAPI.md#UpdateRssFeed) | **Put** /{workspaceUuid}/rss-feeds/{feedUuid} | Update, pause or resume an RSS feed
[**ValidatePost**](PostsAPI.md#ValidatePost) | **Post** /{workspaceUuid}/posts/validate | Validate post (dry run)



## AddPostToQueue

> ScheduleResult AddPostToQueue(ctx, workspaceUuid, postUuid).IdempotencyKey(idempotencyKey).AddPostToQueueRequest(addPostToQueueRequest).Execute()

Add post to queue



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
	postUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the post.
	idempotencyKey := "idempotencyKey_example" // string | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with `Idempotent-Replayed: true` and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  (optional)
	addPostToQueueRequest := *openapiclient.NewAddPostToQueueRequest() // AddPostToQueueRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.AddPostToQueue(context.Background(), workspaceUuid, postUuid).IdempotencyKey(idempotencyKey).AddPostToQueueRequest(addPostToQueueRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.AddPostToQueue``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `AddPostToQueue`: ScheduleResult
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.AddPostToQueue`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**postUuid** | **string** | UUID of the post. | 

### Other Parameters

Other parameters are passed through a pointer to a apiAddPostToQueueRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **idempotencyKey** | **string** | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with &#x60;Idempotent-Replayed: true&#x60; and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  | 
 **addPostToQueueRequest** | [**AddPostToQueueRequest**](AddPostToQueueRequest.md) |  | 

### Return type

[**ScheduleResult**](ScheduleResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApprovePost

> ScheduleResult ApprovePost(ctx, workspaceUuid, postUuid).IdempotencyKey(idempotencyKey).ApprovePostRequest(approvePostRequest).Execute()

Approve post



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
	postUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the post.
	idempotencyKey := "idempotencyKey_example" // string | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with `Idempotent-Replayed: true` and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  (optional)
	approvePostRequest := *openapiclient.NewApprovePostRequest() // ApprovePostRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.ApprovePost(context.Background(), workspaceUuid, postUuid).IdempotencyKey(idempotencyKey).ApprovePostRequest(approvePostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.ApprovePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ApprovePost`: ScheduleResult
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.ApprovePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**postUuid** | **string** | UUID of the post. | 

### Other Parameters

Other parameters are passed through a pointer to a apiApprovePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **idempotencyKey** | **string** | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with &#x60;Idempotent-Replayed: true&#x60; and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  | 
 **approvePostRequest** | [**ApprovePostRequest**](ApprovePostRequest.md) |  | 

### Return type

[**ScheduleResult**](ScheduleResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreatePost

> CreatePost201Response CreatePost(ctx, workspaceUuid).PostInput(postInput).IdempotencyKey(idempotencyKey).Execute()

Create post



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
	postInput := *openapiclient.NewPostInput([]openapiclient.PostVersion{*openapiclient.NewPostVersion(int32(123), false, []openapiclient.PostContent{*openapiclient.NewPostContent()})}) // PostInput | 
	idempotencyKey := "idempotencyKey_example" // string | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with `Idempotent-Replayed: true` and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.CreatePost(context.Background(), workspaceUuid).PostInput(postInput).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.CreatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePost`: CreatePost201Response
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.CreatePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **postInput** | [**PostInput**](PostInput.md) |  | 
 **idempotencyKey** | **string** | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with &#x60;Idempotent-Replayed: true&#x60; and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  | 

### Return type

[**CreatePost201Response**](CreatePost201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateRecyclingRule

> CreateRecyclingRule201Response CreateRecyclingRule(ctx, workspaceUuid).RecyclingRuleInput(recyclingRuleInput).Execute()

Create a recycling rule



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
	recyclingRuleInput := *openapiclient.NewRecyclingRuleInput(int32(123)) // RecyclingRuleInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.CreateRecyclingRule(context.Background(), workspaceUuid).RecyclingRuleInput(recyclingRuleInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.CreateRecyclingRule``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateRecyclingRule`: CreateRecyclingRule201Response
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.CreateRecyclingRule`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateRecyclingRuleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **recyclingRuleInput** | [**RecyclingRuleInput**](RecyclingRuleInput.md) |  | 

### Return type

[**CreateRecyclingRule201Response**](CreateRecyclingRule201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateRssFeed

> CreateRssFeed201Response CreateRssFeed(ctx, workspaceUuid).RssFeedInput(rssFeedInput).Execute()

Add an RSS feed



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
	rssFeedInput := *openapiclient.NewRssFeedInput("Url_example", []int32{int32(123)}) // RssFeedInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.CreateRssFeed(context.Background(), workspaceUuid).RssFeedInput(rssFeedInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.CreateRssFeed``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateRssFeed`: CreateRssFeed201Response
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.CreateRssFeed`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateRssFeedRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **rssFeedInput** | [**RssFeedInput**](RssFeedInput.md) |  | 

### Return type

[**CreateRssFeed201Response**](CreateRssFeed201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeletePost

> DeleteResult DeletePost(ctx, workspaceUuid, postUuid).DeletePostRequest(deletePostRequest).Execute()

Delete post



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
	postUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the post.
	deletePostRequest := *openapiclient.NewDeletePostRequest() // DeletePostRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.DeletePost(context.Background(), workspaceUuid, postUuid).DeletePostRequest(deletePostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.DeletePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeletePost`: DeleteResult
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.DeletePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**postUuid** | **string** | UUID of the post. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeletePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **deletePostRequest** | [**DeletePostRequest**](DeletePostRequest.md) |  | 

### Return type

[**DeleteResult**](DeleteResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeletePostsBulk

> DeleteResult DeletePostsBulk(ctx, workspaceUuid).DeletePostsBulkRequest(deletePostsBulkRequest).Execute()

Delete posts (bulk)



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
	deletePostsBulkRequest := *openapiclient.NewDeletePostsBulkRequest([]string{"Posts_example"}) // DeletePostsBulkRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.DeletePostsBulk(context.Background(), workspaceUuid).DeletePostsBulkRequest(deletePostsBulkRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.DeletePostsBulk``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeletePostsBulk`: DeleteResult
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.DeletePostsBulk`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeletePostsBulkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **deletePostsBulkRequest** | [**DeletePostsBulkRequest**](DeletePostsBulkRequest.md) |  | 

### Return type

[**DeleteResult**](DeleteResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteRecyclingRule

> map[string]interface{} DeleteRecyclingRule(ctx, workspaceUuid, ruleUuid).Execute()

Delete a recycling rule



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
	ruleUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the recycling rule.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.DeleteRecyclingRule(context.Background(), workspaceUuid, ruleUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.DeleteRecyclingRule``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteRecyclingRule`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.DeleteRecyclingRule`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**ruleUuid** | **string** | UUID of the recycling rule. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteRecyclingRuleRequest struct via the builder pattern


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


## DeleteRssFeed

> map[string]interface{} DeleteRssFeed(ctx, workspaceUuid, feedUuid).Execute()

Delete an RSS feed



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
	feedUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the RSS feed.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.DeleteRssFeed(context.Background(), workspaceUuid, feedUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.DeleteRssFeed``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteRssFeed`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.DeleteRssFeed`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**feedUuid** | **string** | UUID of the RSS feed. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteRssFeedRequest struct via the builder pattern


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


## GetPost

> Post GetPost(ctx, workspaceUuid, postUuid).Execute()

Get post



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
	postUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the post.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.GetPost(context.Background(), workspaceUuid, postUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.GetPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPost`: Post
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.GetPost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**postUuid** | **string** | UUID of the post. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**Post**](Post.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPostAnalytics

> PostAnalytics GetPostAnalytics(ctx, workspaceUuid, postUuid).Execute()

Get post analytics



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
	postUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the post.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.GetPostAnalytics(context.Background(), workspaceUuid, postUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.GetPostAnalytics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPostAnalytics`: PostAnalytics
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.GetPostAnalytics`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**postUuid** | **string** | UUID of the post. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPostAnalyticsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**PostAnalytics**](PostAnalytics.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRecyclingRule

> CreateRecyclingRule201Response GetRecyclingRule(ctx, workspaceUuid, ruleUuid).Execute()

Get a recycling rule

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
	ruleUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the recycling rule.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.GetRecyclingRule(context.Background(), workspaceUuid, ruleUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.GetRecyclingRule``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRecyclingRule`: CreateRecyclingRule201Response
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.GetRecyclingRule`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**ruleUuid** | **string** | UUID of the recycling rule. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetRecyclingRuleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CreateRecyclingRule201Response**](CreateRecyclingRule201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRssFeed

> CreateRssFeed201Response GetRssFeed(ctx, workspaceUuid, feedUuid).Execute()

Get an RSS feed

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
	feedUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the RSS feed.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.GetRssFeed(context.Background(), workspaceUuid, feedUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.GetRssFeed``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRssFeed`: CreateRssFeed201Response
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.GetRssFeed`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**feedUuid** | **string** | UUID of the RSS feed. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetRssFeedRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CreateRssFeed201Response**](CreateRssFeed201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListPosts

> ListPosts200Response ListPosts(ctx, workspaceUuid).Page(page).Execute()

List posts



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
	page := int32(56) // int32 |  (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.ListPosts(context.Background(), workspaceUuid).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.ListPosts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListPosts`: ListPosts200Response
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.ListPosts`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListPostsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** |  | [default to 1]

### Return type

[**ListPosts200Response**](ListPosts200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListRecyclingRules

> ListRecyclingRules200Response ListRecyclingRules(ctx, workspaceUuid).Execute()

List recycling rules



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
	resp, r, err := apiClient.PostsAPI.ListRecyclingRules(context.Background(), workspaceUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.ListRecyclingRules``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListRecyclingRules`: ListRecyclingRules200Response
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.ListRecyclingRules`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListRecyclingRulesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListRecyclingRules200Response**](ListRecyclingRules200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListRecyclingRuns

> ListRecyclingRuns200Response ListRecyclingRuns(ctx, workspaceUuid, ruleUuid).Execute()

List a recycling rule's runs



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
	ruleUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the recycling rule.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.ListRecyclingRuns(context.Background(), workspaceUuid, ruleUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.ListRecyclingRuns``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListRecyclingRuns`: ListRecyclingRuns200Response
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.ListRecyclingRuns`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**ruleUuid** | **string** | UUID of the recycling rule. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListRecyclingRunsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**ListRecyclingRuns200Response**](ListRecyclingRuns200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListRssFeeds

> ListRssFeeds200Response ListRssFeeds(ctx, workspaceUuid).Execute()

List RSS feeds



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
	resp, r, err := apiClient.PostsAPI.ListRssFeeds(context.Background(), workspaceUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.ListRssFeeds``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListRssFeeds`: ListRssFeeds200Response
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.ListRssFeeds`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListRssFeedsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListRssFeeds200Response**](ListRssFeeds200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PollRssFeed

> PollRssFeed200Response PollRssFeed(ctx, workspaceUuid, feedUuid).Execute()

Check an RSS feed now



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
	feedUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the RSS feed.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.PollRssFeed(context.Background(), workspaceUuid, feedUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.PollRssFeed``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PollRssFeed`: PollRssFeed200Response
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.PollRssFeed`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**feedUuid** | **string** | UUID of the RSS feed. | 

### Other Parameters

Other parameters are passed through a pointer to a apiPollRssFeedRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**PollRssFeed200Response**](PollRssFeed200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RecyclePost

> CreateRecyclingRule201Response RecyclePost(ctx, workspaceUuid, postUuid).RecyclingRuleSettings(recyclingRuleSettings).Execute()

Recycle a post on an interval



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
	postUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the post.
	recyclingRuleSettings := *openapiclient.NewRecyclingRuleSettings(int32(123)) // RecyclingRuleSettings | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.RecyclePost(context.Background(), workspaceUuid, postUuid).RecyclingRuleSettings(recyclingRuleSettings).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.RecyclePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RecyclePost`: CreateRecyclingRule201Response
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.RecyclePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**postUuid** | **string** | UUID of the post. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRecyclePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **recyclingRuleSettings** | [**RecyclingRuleSettings**](RecyclingRuleSettings.md) |  | 

### Return type

[**CreateRecyclingRule201Response**](CreateRecyclingRule201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RetryPostAccount

> RetryPostAccountResult RetryPostAccount(ctx, workspaceUuid, postUuid, accountUuid).IdempotencyKey(idempotencyKey).Execute()

Retry publishing to one account



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
	postUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the post.
	accountUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the social media account.
	idempotencyKey := "idempotencyKey_example" // string | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with `Idempotent-Replayed: true` and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.RetryPostAccount(context.Background(), workspaceUuid, postUuid, accountUuid).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.RetryPostAccount``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetryPostAccount`: RetryPostAccountResult
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.RetryPostAccount`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**postUuid** | **string** | UUID of the post. | 
**accountUuid** | **string** | UUID of the social media account. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRetryPostAccountRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



 **idempotencyKey** | **string** | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with &#x60;Idempotent-Replayed: true&#x60; and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  | 

### Return type

[**RetryPostAccountResult**](RetryPostAccountResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SchedulePost

> ScheduleResult SchedulePost(ctx, workspaceUuid, postUuid).SchedulePostRequest(schedulePostRequest).IdempotencyKey(idempotencyKey).Execute()

Schedule post



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
	postUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the post.
	schedulePostRequest := *openapiclient.NewSchedulePostRequest(false) // SchedulePostRequest | 
	idempotencyKey := "idempotencyKey_example" // string | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with `Idempotent-Replayed: true` and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.SchedulePost(context.Background(), workspaceUuid, postUuid).SchedulePostRequest(schedulePostRequest).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.SchedulePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SchedulePost`: ScheduleResult
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.SchedulePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**postUuid** | **string** | UUID of the post. | 

### Other Parameters

Other parameters are passed through a pointer to a apiSchedulePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **schedulePostRequest** | [**SchedulePostRequest**](SchedulePostRequest.md) |  | 
 **idempotencyKey** | **string** | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with &#x60;Idempotent-Replayed: true&#x60; and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  | 

### Return type

[**ScheduleResult**](ScheduleResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdatePost

> UpdatePost200Response UpdatePost(ctx, workspaceUuid, postUuid).PostInput(postInput).Execute()

Update post



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
	postUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the post.
	postInput := *openapiclient.NewPostInput([]openapiclient.PostVersion{*openapiclient.NewPostVersion(int32(123), false, []openapiclient.PostContent{*openapiclient.NewPostContent()})}) // PostInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.UpdatePost(context.Background(), workspaceUuid, postUuid).PostInput(postInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.UpdatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdatePost`: UpdatePost200Response
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.UpdatePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**postUuid** | **string** | UUID of the post. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **postInput** | [**PostInput**](PostInput.md) |  | 

### Return type

[**UpdatePost200Response**](UpdatePost200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateRecyclingRule

> CreateRecyclingRule201Response UpdateRecyclingRule(ctx, workspaceUuid, ruleUuid).RecyclingRuleUpdate(recyclingRuleUpdate).Execute()

Update, pause or resume a recycling rule



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
	ruleUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the recycling rule.
	recyclingRuleUpdate := *openapiclient.NewRecyclingRuleUpdate() // RecyclingRuleUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.UpdateRecyclingRule(context.Background(), workspaceUuid, ruleUuid).RecyclingRuleUpdate(recyclingRuleUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.UpdateRecyclingRule``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateRecyclingRule`: CreateRecyclingRule201Response
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.UpdateRecyclingRule`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**ruleUuid** | **string** | UUID of the recycling rule. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateRecyclingRuleRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **recyclingRuleUpdate** | [**RecyclingRuleUpdate**](RecyclingRuleUpdate.md) |  | 

### Return type

[**CreateRecyclingRule201Response**](CreateRecyclingRule201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateRssFeed

> CreateRssFeed201Response UpdateRssFeed(ctx, workspaceUuid, feedUuid).RssFeedUpdate(rssFeedUpdate).Execute()

Update, pause or resume an RSS feed



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
	feedUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the RSS feed.
	rssFeedUpdate := *openapiclient.NewRssFeedUpdate() // RssFeedUpdate | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.UpdateRssFeed(context.Background(), workspaceUuid, feedUuid).RssFeedUpdate(rssFeedUpdate).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.UpdateRssFeed``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateRssFeed`: CreateRssFeed201Response
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.UpdateRssFeed`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**feedUuid** | **string** | UUID of the RSS feed. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateRssFeedRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **rssFeedUpdate** | [**RssFeedUpdate**](RssFeedUpdate.md) |  | 

### Return type

[**CreateRssFeed201Response**](CreateRssFeed201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ValidatePost

> PreflightResult ValidatePost(ctx, workspaceUuid).PostInput(postInput).Execute()

Validate post (dry run)



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
	postInput := *openapiclient.NewPostInput([]openapiclient.PostVersion{*openapiclient.NewPostVersion(int32(123), false, []openapiclient.PostContent{*openapiclient.NewPostContent()})}) // PostInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.ValidatePost(context.Background(), workspaceUuid).PostInput(postInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.ValidatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ValidatePost`: PreflightResult
	fmt.Fprintf(os.Stdout, "Response from `PostsAPI.ValidatePost`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiValidatePostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **postInput** | [**PostInput**](PostInput.md) |  | 

### Return type

[**PreflightResult**](PreflightResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

