# \PostsAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AddPostToQueue**](PostsAPI.md#AddPostToQueue) | **Post** /{workspaceUuid}/posts/add-to-queue/{postUuid} | Add post to queue
[**ApprovePost**](PostsAPI.md#ApprovePost) | **Post** /{workspaceUuid}/posts/approve/{postUuid} | Approve post
[**CreatePost**](PostsAPI.md#CreatePost) | **Post** /{workspaceUuid}/posts | Create post
[**DeletePost**](PostsAPI.md#DeletePost) | **Delete** /{workspaceUuid}/posts/{postUuid} | Delete post
[**DeletePostsBulk**](PostsAPI.md#DeletePostsBulk) | **Delete** /{workspaceUuid}/posts | Delete posts (bulk)
[**GetPost**](PostsAPI.md#GetPost) | **Get** /{workspaceUuid}/posts/{postUuid} | Get post
[**ListPosts**](PostsAPI.md#ListPosts) | **Get** /{workspaceUuid}/posts | List posts
[**SchedulePost**](PostsAPI.md#SchedulePost) | **Post** /{workspaceUuid}/posts/schedule/{postUuid} | Schedule post
[**UpdatePost**](PostsAPI.md#UpdatePost) | **Put** /{workspaceUuid}/posts/{postUuid} | Update post



## AddPostToQueue

> ScheduleResult AddPostToQueue(ctx, workspaceUuid, postUuid).Execute()

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.AddPostToQueue(context.Background(), workspaceUuid, postUuid).Execute()
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



### Return type

[**ScheduleResult**](ScheduleResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ApprovePost

> ScheduleResult ApprovePost(ctx, workspaceUuid, postUuid).Execute()

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.ApprovePost(context.Background(), workspaceUuid, postUuid).Execute()
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



### Return type

[**ScheduleResult**](ScheduleResult.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreatePost

> Post CreatePost(ctx, workspaceUuid).PostInput(postInput).Execute()

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.CreatePost(context.Background(), workspaceUuid).PostInput(postInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `PostsAPI.CreatePost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreatePost`: Post
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

### Return type

[**Post**](Post.md)

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


## SchedulePost

> ScheduleResult SchedulePost(ctx, workspaceUuid, postUuid).SchedulePostRequest(schedulePostRequest).Execute()

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.PostsAPI.SchedulePost(context.Background(), workspaceUuid, postUuid).SchedulePostRequest(schedulePostRequest).Execute()
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

> map[string]interface{} UpdatePost(ctx, workspaceUuid, postUuid).PostInput(postInput).Execute()

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
	// response from `UpdatePost`: map[string]interface{}
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

**map[string]interface{}**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

