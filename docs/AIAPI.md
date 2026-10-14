# \AIAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BlogToSocial**](AIAPI.md#BlogToSocial) | **Post** /{workspaceUuid}/ai/blog-to-social | Generate social media captions from a blog post
[**DeleteBrandVoice**](AIAPI.md#DeleteBrandVoice) | **Delete** /{workspaceUuid}/brand-voice | Delete the brand voice
[**GetAIUsage**](AIAPI.md#GetAIUsage) | **Get** /{workspaceUuid}/usage/ai | AI credit usage
[**GetBrandVoice**](AIAPI.md#GetBrandVoice) | **Get** /{workspaceUuid}/brand-voice | Get the brand voice
[**GetRepurposeRun**](AIAPI.md#GetRepurposeRun) | **Get** /{workspaceUuid}/ai/repurpose/runs/{runId} | Get a repurpose run
[**ImageAltText**](AIAPI.md#ImageAltText) | **Post** /{workspaceUuid}/ai/image-alt-text | Generate alt text for a media image using AI
[**ImageEdit**](AIAPI.md#ImageEdit) | **Post** /{workspaceUuid}/ai/image-edit | Edit an existing media image using AI
[**ImageGenerate**](AIAPI.md#ImageGenerate) | **Post** /{workspaceUuid}/ai/image-generate | Generate social media images from a caption
[**ImagePrompt**](AIAPI.md#ImagePrompt) | **Post** /{workspaceUuid}/ai/image-prompt | Build an optimized image prompt from a social media caption
[**ImageVariations**](AIAPI.md#ImageVariations) | **Post** /{workspaceUuid}/ai/image-variations | Generate variations of an existing media image
[**LearnBrandVoice**](AIAPI.md#LearnBrandVoice) | **Post** /{workspaceUuid}/brand-voice/learn | Learn a brand voice from past posts
[**RepurposeContent**](AIAPI.md#RepurposeContent) | **Post** /{workspaceUuid}/ai/repurpose | Repurpose long-form content into a draft post set with a carousel
[**UpdateBrandVoice**](AIAPI.md#UpdateBrandVoice) | **Put** /{workspaceUuid}/brand-voice | Create or update the brand voice



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


## DeleteBrandVoice

> map[string]interface{} DeleteBrandVoice(ctx, workspaceUuid).Execute()

Delete the brand voice



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
	resp, r, err := apiClient.AIAPI.DeleteBrandVoice(context.Background(), workspaceUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAPI.DeleteBrandVoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteBrandVoice`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `AIAPI.DeleteBrandVoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteBrandVoiceRequest struct via the builder pattern


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


## GetAIUsage

> AIUsage GetAIUsage(ctx, workspaceUuid).Execute()

AI credit usage



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
	resp, r, err := apiClient.AIAPI.GetAIUsage(context.Background(), workspaceUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAPI.GetAIUsage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAIUsage`: AIUsage
	fmt.Fprintf(os.Stdout, "Response from `AIAPI.GetAIUsage`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAIUsageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**AIUsage**](AIUsage.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetBrandVoice

> GetBrandVoice200Response GetBrandVoice(ctx, workspaceUuid).Execute()

Get the brand voice



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
	resp, r, err := apiClient.AIAPI.GetBrandVoice(context.Background(), workspaceUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAPI.GetBrandVoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBrandVoice`: GetBrandVoice200Response
	fmt.Fprintf(os.Stdout, "Response from `AIAPI.GetBrandVoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetBrandVoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetBrandVoice200Response**](GetBrandVoice200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRepurposeRun

> GetRepurposeRun200Response GetRepurposeRun(ctx, workspaceUuid, runId).Execute()

Get a repurpose run



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
	runId := int32(56) // int32 | The `run_id` from `repurposeContent`.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AIAPI.GetRepurposeRun(context.Background(), workspaceUuid, runId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAPI.GetRepurposeRun``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRepurposeRun`: GetRepurposeRun200Response
	fmt.Fprintf(os.Stdout, "Response from `AIAPI.GetRepurposeRun`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**runId** | **int32** | The &#x60;run_id&#x60; from &#x60;repurposeContent&#x60;. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetRepurposeRunRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**GetRepurposeRun200Response**](GetRepurposeRun200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
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


## LearnBrandVoice

> LearnBrandVoiceResponse LearnBrandVoice(ctx, workspaceUuid).LearnBrandVoiceInput(learnBrandVoiceInput).Execute()

Learn a brand voice from past posts



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
	learnBrandVoiceInput := *openapiclient.NewLearnBrandVoiceInput() // LearnBrandVoiceInput |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AIAPI.LearnBrandVoice(context.Background(), workspaceUuid).LearnBrandVoiceInput(learnBrandVoiceInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAPI.LearnBrandVoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `LearnBrandVoice`: LearnBrandVoiceResponse
	fmt.Fprintf(os.Stdout, "Response from `AIAPI.LearnBrandVoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiLearnBrandVoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **learnBrandVoiceInput** | [**LearnBrandVoiceInput**](LearnBrandVoiceInput.md) |  | 

### Return type

[**LearnBrandVoiceResponse**](LearnBrandVoiceResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RepurposeContent

> RepurposeContent200Response RepurposeContent(ctx, workspaceUuid).RepurposeInput(repurposeInput).IdempotencyKey(idempotencyKey).Execute()

Repurpose long-form content into a draft post set with a carousel



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
	repurposeInput := *openapiclient.NewRepurposeInput("SourceType_example") // RepurposeInput | 
	idempotencyKey := "idempotencyKey_example" // string | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with `Idempotent-Replayed: true` and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AIAPI.RepurposeContent(context.Background(), workspaceUuid).RepurposeInput(repurposeInput).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAPI.RepurposeContent``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RepurposeContent`: RepurposeContent200Response
	fmt.Fprintf(os.Stdout, "Response from `AIAPI.RepurposeContent`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiRepurposeContentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **repurposeInput** | [**RepurposeInput**](RepurposeInput.md) |  | 
 **idempotencyKey** | **string** | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with &#x60;Idempotent-Replayed: true&#x60; and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  | 

### Return type

[**RepurposeContent200Response**](RepurposeContent200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateBrandVoice

> GetBrandVoice200Response UpdateBrandVoice(ctx, workspaceUuid).BrandVoiceInput(brandVoiceInput).Execute()

Create or update the brand voice



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
	brandVoiceInput := *openapiclient.NewBrandVoiceInput() // BrandVoiceInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AIAPI.UpdateBrandVoice(context.Background(), workspaceUuid).BrandVoiceInput(brandVoiceInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AIAPI.UpdateBrandVoice``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateBrandVoice`: GetBrandVoice200Response
	fmt.Fprintf(os.Stdout, "Response from `AIAPI.UpdateBrandVoice`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateBrandVoiceRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **brandVoiceInput** | [**BrandVoiceInput**](BrandVoiceInput.md) |  | 

### Return type

[**GetBrandVoice200Response**](GetBrandVoice200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

