# \AIAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BlogToSocial**](AIAPI.md#BlogToSocial) | **Post** /{workspaceUuid}/ai/blog-to-social | Generate social media captions from a blog post
[**ImageAltText**](AIAPI.md#ImageAltText) | **Post** /{workspaceUuid}/ai/image-alt-text | Generate alt text for a media image using AI
[**ImageEdit**](AIAPI.md#ImageEdit) | **Post** /{workspaceUuid}/ai/image-edit | Edit an existing media image using AI
[**ImageGenerate**](AIAPI.md#ImageGenerate) | **Post** /{workspaceUuid}/ai/image-generate | Generate social media images from a caption
[**ImagePrompt**](AIAPI.md#ImagePrompt) | **Post** /{workspaceUuid}/ai/image-prompt | Build an optimized image prompt from a social media caption
[**ImageVariations**](AIAPI.md#ImageVariations) | **Post** /{workspaceUuid}/ai/image-variations | Generate variations of an existing media image



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


## ImageAltText

> ImageAltText200Response ImageAltText(ctx, workspaceUuid).ImageAltTextInput(imageAltTextInput).Execute()

Generate alt text for a media image using AI



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
	imageAltTextInput := *openapiclient.NewImageAltTextInput("MediaUuid_example") // ImageAltTextInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AIAPI.ImageAltText(context.Background(), workspaceUuid).ImageAltTextInput(imageAltTextInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAPI.ImageAltText``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ImageAltText`: ImageAltText200Response
	fmt.Fprintf(os.Stdout, "Response from `AIAPI.ImageAltText`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiImageAltTextRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **imageAltTextInput** | [**ImageAltTextInput**](ImageAltTextInput.md) |  | 

### Return type

[**ImageAltText200Response**](ImageAltText200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ImageEdit

> ImageGenerate200Response ImageEdit(ctx, workspaceUuid).ImageEditInput(imageEditInput).Execute()

Edit an existing media image using AI



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
	imageEditInput := *openapiclient.NewImageEditInput("MediaUuid_example", "Make the background a white studio backdrop") // ImageEditInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AIAPI.ImageEdit(context.Background(), workspaceUuid).ImageEditInput(imageEditInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAPI.ImageEdit``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ImageEdit`: ImageGenerate200Response
	fmt.Fprintf(os.Stdout, "Response from `AIAPI.ImageEdit`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiImageEditRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **imageEditInput** | [**ImageEditInput**](ImageEditInput.md) |  | 

### Return type

[**ImageGenerate200Response**](ImageGenerate200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ImageGenerate

> ImageGenerate200Response ImageGenerate(ctx, workspaceUuid).ImageGenerateInput(imageGenerateInput).Execute()

Generate social media images from a caption



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
	imageGenerateInput := *openapiclient.NewImageGenerateInput() // ImageGenerateInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AIAPI.ImageGenerate(context.Background(), workspaceUuid).ImageGenerateInput(imageGenerateInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAPI.ImageGenerate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ImageGenerate`: ImageGenerate200Response
	fmt.Fprintf(os.Stdout, "Response from `AIAPI.ImageGenerate`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiImageGenerateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **imageGenerateInput** | [**ImageGenerateInput**](ImageGenerateInput.md) |  | 

### Return type

[**ImageGenerate200Response**](ImageGenerate200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ImagePrompt

> ImagePrompt200Response ImagePrompt(ctx, workspaceUuid).ImagePromptInput(imagePromptInput).Execute()

Build an optimized image prompt from a social media caption



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
	imagePromptInput := *openapiclient.NewImagePromptInput("Our summer sale starts today, 30% off everything!", "instagram") // ImagePromptInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AIAPI.ImagePrompt(context.Background(), workspaceUuid).ImagePromptInput(imagePromptInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAPI.ImagePrompt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ImagePrompt`: ImagePrompt200Response
	fmt.Fprintf(os.Stdout, "Response from `AIAPI.ImagePrompt`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiImagePromptRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **imagePromptInput** | [**ImagePromptInput**](ImagePromptInput.md) |  | 

### Return type

[**ImagePrompt200Response**](ImagePrompt200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ImageVariations

> ImageVariations200Response ImageVariations(ctx, workspaceUuid).ImageVariationsInput(imageVariationsInput).Execute()

Generate variations of an existing media image



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
	imageVariationsInput := *openapiclient.NewImageVariationsInput("MediaUuid_example") // ImageVariationsInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AIAPI.ImageVariations(context.Background(), workspaceUuid).ImageVariationsInput(imageVariationsInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAPI.ImageVariations``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ImageVariations`: ImageVariations200Response
	fmt.Fprintf(os.Stdout, "Response from `AIAPI.ImageVariations`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiImageVariationsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **imageVariationsInput** | [**ImageVariationsInput**](ImageVariationsInput.md) |  | 

### Return type

[**ImageVariations200Response**](ImageVariations200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

