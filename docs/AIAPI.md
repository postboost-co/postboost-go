# \AIAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BlogToSocial**](AIAPI.md#BlogToSocial) | **Post** /{workspaceUuid}/ai/blog-to-social | Generate social media captions from a blog post



## BlogToSocial

> BlogToSocial200Response BlogToSocial(ctx, workspaceUuid).BlogToSocialInput(blogToSocialInput).Execute()

Generate social media captions from a blog post



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
	blogToSocialInput := *openapiclient.NewBlogToSocialInput() // BlogToSocialInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AIAPI.BlogToSocial(context.Background(), workspaceUuid).BlogToSocialInput(blogToSocialInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAPI.BlogToSocial``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BlogToSocial`: BlogToSocial200Response
	fmt.Fprintf(os.Stdout, "Response from `AIAPI.BlogToSocial`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiBlogToSocialRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **blogToSocialInput** | [**BlogToSocialInput**](BlogToSocialInput.md) |  | 

### Return type

[**BlogToSocial200Response**](BlogToSocial200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

