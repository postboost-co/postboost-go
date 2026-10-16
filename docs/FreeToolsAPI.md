# \FreeToolsAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BuildUtmUrl**](FreeToolsAPI.md#BuildUtmUrl) | **Post** /tools/utm-builder | Build a UTM-tagged campaign URL
[**CalculateAspectRatio**](FreeToolsAPI.md#CalculateAspectRatio) | **Post** /tools/aspect-ratio-calculator | Calculate an aspect ratio, or the missing side of an image at a given ratio
[**CalculateCrop**](FreeToolsAPI.md#CalculateCrop) | **Post** /tools/social-media-image-sizes/crop | Calculate the crop box that fits an image to a social media size
[**CalculateEngagementRate**](FreeToolsAPI.md#CalculateEngagementRate) | **Post** /tools/engagement-rate-calculator | Calculate an engagement rate
[**CheckLinkPreview**](FreeToolsAPI.md#CheckLinkPreview) | **Post** /tools/link-preview-checker | Check how a link previews on X, LinkedIn, Facebook and chat apps (Open Graph and Twitter card tags)
[**CheckPost**](FreeToolsAPI.md#CheckPost) | **Post** /tools/social-media-post-checker | Check a post against each network&#39;s publishing rules
[**CheckYoutubeThumbnail**](FreeToolsAPI.md#CheckYoutubeThumbnail) | **Post** /tools/youtube-thumbnail-size-checker | Check a YouTube thumbnail&#39;s ratio, width, file size and format against YouTube&#39;s requirements
[**CleanText**](FreeToolsAPI.md#CleanText) | **Post** /tools/ai-text-cleaner | Clean AI-written text: dashes, quotes, invisible characters, markdown
[**CountCharacters**](FreeToolsAPI.md#CountCharacters) | **Post** /tools/social-media-character-counter | Count characters as each network counts them
[**FormatInstagramCaption**](FreeToolsAPI.md#FormatInstagramCaption) | **Post** /tools/instagram-line-break-generator | Keep blank lines in an Instagram caption with spacer lines, and count it
[**FormatLinkedInPost**](FreeToolsAPI.md#FormatLinkedInPost) | **Post** /tools/linkedin-post-formatter | Format a LinkedIn post with bold, italic and lists
[**GenerateCaption**](FreeToolsAPI.md#GenerateCaption) | **Post** /tools/instagram-caption-generator | Write three post captions for a topic with AI (needs a token, spends AI credits)
[**GenerateFancyText**](FreeToolsAPI.md#GenerateFancyText) | **Post** /tools/fancy-text-generator | Convert text to fancy Unicode styles
[**GenerateHashtags**](FreeToolsAPI.md#GenerateHashtags) | **Post** /tools/instagram-hashtag-generator | Generate hashtags for a post topic with AI (needs a token, spends AI credits)
[**GenerateHooks**](FreeToolsAPI.md#GenerateHooks) | **Post** /tools/hook-generator | Generate hooks (opening lines) for a social media post with AI (needs a token, spends AI credits)
[**GenerateQrCode**](FreeToolsAPI.md#GenerateQrCode) | **Post** /tools/qr-code-generator | Generate a QR code (SVG) for a link or text, with optional UTM tags
[**GenerateSocialPostsFromBlog**](FreeToolsAPI.md#GenerateSocialPostsFromBlog) | **Post** /tools/blog-to-social-media | Turn a blog post (URL or text) into one social post per network with AI (needs a token, spends AI credits)
[**GetBestTimesToPost**](FreeToolsAPI.md#GetBestTimesToPost) | **Get** /tools/best-time-to-post | Get the best times to post per network from published studies, with sources
[**GetHookTemplates**](FreeToolsAPI.md#GetHookTemplates) | **Get** /tools/hook-generator/library | Get free hook templates for social media posts, filtered by style and network
[**GetImageSizes**](FreeToolsAPI.md#GetImageSizes) | **Get** /tools/social-media-image-sizes | Get social media image sizes per network, each with its source
[**GetVideoSpecs**](FreeToolsAPI.md#GetVideoSpecs) | **Get** /tools/social-media-video-specs | Get social media video ratios, resolutions, lengths and file size limits per network, with sources
[**ListFreeTools**](FreeToolsAPI.md#ListFreeTools) | **Get** /tools | List the free tools
[**PreviewPost**](FreeToolsAPI.md#PreviewPost) | **Post** /tools/social-media-post-preview | Preview where a post folds and when its image is cropped on Instagram, X, LinkedIn and Facebook
[**SplitThread**](FreeToolsAPI.md#SplitThread) | **Post** /tools/x-thread-maker | Split long text into a thread



## BuildUtmUrl

> FreeToolBuildUtmUrlResponse BuildUtmUrl(ctx).FreeToolBuildUtmUrlRequest(freeToolBuildUtmUrlRequest).Execute()

Build a UTM-tagged campaign URL



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
	freeToolBuildUtmUrlRequest := *openapiclient.NewFreeToolBuildUtmUrlRequest("Url_example") // FreeToolBuildUtmUrlRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.BuildUtmUrl(context.Background()).FreeToolBuildUtmUrlRequest(freeToolBuildUtmUrlRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.BuildUtmUrl``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `BuildUtmUrl`: FreeToolBuildUtmUrlResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.BuildUtmUrl`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiBuildUtmUrlRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolBuildUtmUrlRequest** | [**FreeToolBuildUtmUrlRequest**](FreeToolBuildUtmUrlRequest.md) |  | 

### Return type

[**FreeToolBuildUtmUrlResponse**](FreeToolBuildUtmUrlResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CalculateAspectRatio

> FreeToolCalculateAspectRatioResponse CalculateAspectRatio(ctx).FreeToolCalculateAspectRatioRequest(freeToolCalculateAspectRatioRequest).Execute()

Calculate an aspect ratio, or the missing side of an image at a given ratio



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
	freeToolCalculateAspectRatioRequest := *openapiclient.NewFreeToolCalculateAspectRatioRequest() // FreeToolCalculateAspectRatioRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.CalculateAspectRatio(context.Background()).FreeToolCalculateAspectRatioRequest(freeToolCalculateAspectRatioRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.CalculateAspectRatio``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CalculateAspectRatio`: FreeToolCalculateAspectRatioResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.CalculateAspectRatio`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCalculateAspectRatioRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolCalculateAspectRatioRequest** | [**FreeToolCalculateAspectRatioRequest**](FreeToolCalculateAspectRatioRequest.md) |  | 

### Return type

[**FreeToolCalculateAspectRatioResponse**](FreeToolCalculateAspectRatioResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CalculateCrop

> FreeToolCalculateCropResponse CalculateCrop(ctx).FreeToolCalculateCropRequest(freeToolCalculateCropRequest).Execute()

Calculate the crop box that fits an image to a social media size



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
	freeToolCalculateCropRequest := *openapiclient.NewFreeToolCalculateCropRequest(int32(123), int32(123)) // FreeToolCalculateCropRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.CalculateCrop(context.Background()).FreeToolCalculateCropRequest(freeToolCalculateCropRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.CalculateCrop``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CalculateCrop`: FreeToolCalculateCropResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.CalculateCrop`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCalculateCropRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolCalculateCropRequest** | [**FreeToolCalculateCropRequest**](FreeToolCalculateCropRequest.md) |  | 

### Return type

[**FreeToolCalculateCropResponse**](FreeToolCalculateCropResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CalculateEngagementRate

> FreeToolCalculateEngagementRateResponse CalculateEngagementRate(ctx).FreeToolCalculateEngagementRateRequest(freeToolCalculateEngagementRateRequest).Execute()

Calculate an engagement rate



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
	freeToolCalculateEngagementRateRequest := *openapiclient.NewFreeToolCalculateEngagementRateRequest(int32(123)) // FreeToolCalculateEngagementRateRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.CalculateEngagementRate(context.Background()).FreeToolCalculateEngagementRateRequest(freeToolCalculateEngagementRateRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.CalculateEngagementRate``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CalculateEngagementRate`: FreeToolCalculateEngagementRateResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.CalculateEngagementRate`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCalculateEngagementRateRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolCalculateEngagementRateRequest** | [**FreeToolCalculateEngagementRateRequest**](FreeToolCalculateEngagementRateRequest.md) |  | 

### Return type

[**FreeToolCalculateEngagementRateResponse**](FreeToolCalculateEngagementRateResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CheckLinkPreview

> FreeToolCheckLinkPreviewResponse CheckLinkPreview(ctx).FreeToolCheckLinkPreviewRequest(freeToolCheckLinkPreviewRequest).Execute()

Check how a link previews on X, LinkedIn, Facebook and chat apps (Open Graph and Twitter card tags)



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
	freeToolCheckLinkPreviewRequest := *openapiclient.NewFreeToolCheckLinkPreviewRequest("Url_example") // FreeToolCheckLinkPreviewRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.CheckLinkPreview(context.Background()).FreeToolCheckLinkPreviewRequest(freeToolCheckLinkPreviewRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.CheckLinkPreview``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckLinkPreview`: FreeToolCheckLinkPreviewResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.CheckLinkPreview`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCheckLinkPreviewRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolCheckLinkPreviewRequest** | [**FreeToolCheckLinkPreviewRequest**](FreeToolCheckLinkPreviewRequest.md) |  | 

### Return type

[**FreeToolCheckLinkPreviewResponse**](FreeToolCheckLinkPreviewResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CheckPost

> FreeToolCheckPostResponse CheckPost(ctx).FreeToolCheckPostRequest(freeToolCheckPostRequest).Execute()

Check a post against each network's publishing rules



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
	freeToolCheckPostRequest := *openapiclient.NewFreeToolCheckPostRequest([]string{"Networks_example"}) // FreeToolCheckPostRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.CheckPost(context.Background()).FreeToolCheckPostRequest(freeToolCheckPostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.CheckPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckPost`: FreeToolCheckPostResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.CheckPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCheckPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolCheckPostRequest** | [**FreeToolCheckPostRequest**](FreeToolCheckPostRequest.md) |  | 

### Return type

[**FreeToolCheckPostResponse**](FreeToolCheckPostResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CheckYoutubeThumbnail

> FreeToolCheckYoutubeThumbnailResponse CheckYoutubeThumbnail(ctx).FreeToolCheckYoutubeThumbnailRequest(freeToolCheckYoutubeThumbnailRequest).Execute()

Check a YouTube thumbnail's ratio, width, file size and format against YouTube's requirements



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
	freeToolCheckYoutubeThumbnailRequest := *openapiclient.NewFreeToolCheckYoutubeThumbnailRequest(int32(123), int32(123), int32(123), "Format_example") // FreeToolCheckYoutubeThumbnailRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.CheckYoutubeThumbnail(context.Background()).FreeToolCheckYoutubeThumbnailRequest(freeToolCheckYoutubeThumbnailRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.CheckYoutubeThumbnail``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CheckYoutubeThumbnail`: FreeToolCheckYoutubeThumbnailResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.CheckYoutubeThumbnail`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCheckYoutubeThumbnailRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolCheckYoutubeThumbnailRequest** | [**FreeToolCheckYoutubeThumbnailRequest**](FreeToolCheckYoutubeThumbnailRequest.md) |  | 

### Return type

[**FreeToolCheckYoutubeThumbnailResponse**](FreeToolCheckYoutubeThumbnailResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CleanText

> FreeToolCleanTextResponse CleanText(ctx).FreeToolCleanTextRequest(freeToolCleanTextRequest).Execute()

Clean AI-written text: dashes, quotes, invisible characters, markdown



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
	freeToolCleanTextRequest := *openapiclient.NewFreeToolCleanTextRequest("Text_example") // FreeToolCleanTextRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.CleanText(context.Background()).FreeToolCleanTextRequest(freeToolCleanTextRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.CleanText``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CleanText`: FreeToolCleanTextResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.CleanText`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCleanTextRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolCleanTextRequest** | [**FreeToolCleanTextRequest**](FreeToolCleanTextRequest.md) |  | 

### Return type

[**FreeToolCleanTextResponse**](FreeToolCleanTextResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CountCharacters

> FreeToolCountCharactersResponse CountCharacters(ctx).FreeToolCountCharactersRequest(freeToolCountCharactersRequest).Execute()

Count characters as each network counts them



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
	freeToolCountCharactersRequest := *openapiclient.NewFreeToolCountCharactersRequest() // FreeToolCountCharactersRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.CountCharacters(context.Background()).FreeToolCountCharactersRequest(freeToolCountCharactersRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.CountCharacters``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CountCharacters`: FreeToolCountCharactersResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.CountCharacters`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCountCharactersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolCountCharactersRequest** | [**FreeToolCountCharactersRequest**](FreeToolCountCharactersRequest.md) |  | 

### Return type

[**FreeToolCountCharactersResponse**](FreeToolCountCharactersResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FormatInstagramCaption

> FreeToolFormatInstagramCaptionResponse FormatInstagramCaption(ctx).FreeToolFormatInstagramCaptionRequest(freeToolFormatInstagramCaptionRequest).Execute()

Keep blank lines in an Instagram caption with spacer lines, and count it



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
	freeToolFormatInstagramCaptionRequest := *openapiclient.NewFreeToolFormatInstagramCaptionRequest("Text_example") // FreeToolFormatInstagramCaptionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.FormatInstagramCaption(context.Background()).FreeToolFormatInstagramCaptionRequest(freeToolFormatInstagramCaptionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.FormatInstagramCaption``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FormatInstagramCaption`: FreeToolFormatInstagramCaptionResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.FormatInstagramCaption`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFormatInstagramCaptionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolFormatInstagramCaptionRequest** | [**FreeToolFormatInstagramCaptionRequest**](FreeToolFormatInstagramCaptionRequest.md) |  | 

### Return type

[**FreeToolFormatInstagramCaptionResponse**](FreeToolFormatInstagramCaptionResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## FormatLinkedInPost

> FreeToolFormatLinkedInPostResponse FormatLinkedInPost(ctx).FreeToolFormatLinkedInPostRequest(freeToolFormatLinkedInPostRequest).Execute()

Format a LinkedIn post with bold, italic and lists



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
	freeToolFormatLinkedInPostRequest := *openapiclient.NewFreeToolFormatLinkedInPostRequest("Text_example") // FreeToolFormatLinkedInPostRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.FormatLinkedInPost(context.Background()).FreeToolFormatLinkedInPostRequest(freeToolFormatLinkedInPostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.FormatLinkedInPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `FormatLinkedInPost`: FreeToolFormatLinkedInPostResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.FormatLinkedInPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFormatLinkedInPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolFormatLinkedInPostRequest** | [**FreeToolFormatLinkedInPostRequest**](FreeToolFormatLinkedInPostRequest.md) |  | 

### Return type

[**FreeToolFormatLinkedInPostResponse**](FreeToolFormatLinkedInPostResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateCaption

> FreeToolGenerateCaptionResponse GenerateCaption(ctx).FreeToolGenerateCaptionRequest(freeToolGenerateCaptionRequest).Execute()

Write three post captions for a topic with AI (needs a token, spends AI credits)



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
	freeToolGenerateCaptionRequest := *openapiclient.NewFreeToolGenerateCaptionRequest("Text_example") // FreeToolGenerateCaptionRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.GenerateCaption(context.Background()).FreeToolGenerateCaptionRequest(freeToolGenerateCaptionRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.GenerateCaption``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateCaption`: FreeToolGenerateCaptionResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.GenerateCaption`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateCaptionRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolGenerateCaptionRequest** | [**FreeToolGenerateCaptionRequest**](FreeToolGenerateCaptionRequest.md) |  | 

### Return type

[**FreeToolGenerateCaptionResponse**](FreeToolGenerateCaptionResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateFancyText

> FreeToolGenerateFancyTextResponse GenerateFancyText(ctx).FreeToolGenerateFancyTextRequest(freeToolGenerateFancyTextRequest).Execute()

Convert text to fancy Unicode styles



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
	freeToolGenerateFancyTextRequest := *openapiclient.NewFreeToolGenerateFancyTextRequest("Text_example") // FreeToolGenerateFancyTextRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.GenerateFancyText(context.Background()).FreeToolGenerateFancyTextRequest(freeToolGenerateFancyTextRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.GenerateFancyText``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateFancyText`: FreeToolGenerateFancyTextResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.GenerateFancyText`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateFancyTextRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolGenerateFancyTextRequest** | [**FreeToolGenerateFancyTextRequest**](FreeToolGenerateFancyTextRequest.md) |  | 

### Return type

[**FreeToolGenerateFancyTextResponse**](FreeToolGenerateFancyTextResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateHashtags

> FreeToolGenerateHashtagsResponse GenerateHashtags(ctx).FreeToolGenerateHashtagsRequest(freeToolGenerateHashtagsRequest).Execute()

Generate hashtags for a post topic with AI (needs a token, spends AI credits)



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
	freeToolGenerateHashtagsRequest := *openapiclient.NewFreeToolGenerateHashtagsRequest("Topic_example") // FreeToolGenerateHashtagsRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.GenerateHashtags(context.Background()).FreeToolGenerateHashtagsRequest(freeToolGenerateHashtagsRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.GenerateHashtags``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateHashtags`: FreeToolGenerateHashtagsResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.GenerateHashtags`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateHashtagsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolGenerateHashtagsRequest** | [**FreeToolGenerateHashtagsRequest**](FreeToolGenerateHashtagsRequest.md) |  | 

### Return type

[**FreeToolGenerateHashtagsResponse**](FreeToolGenerateHashtagsResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateHooks

> FreeToolGenerateHooksResponse GenerateHooks(ctx).FreeToolGenerateHooksRequest(freeToolGenerateHooksRequest).Execute()

Generate hooks (opening lines) for a social media post with AI (needs a token, spends AI credits)



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
	freeToolGenerateHooksRequest := *openapiclient.NewFreeToolGenerateHooksRequest("Topic_example") // FreeToolGenerateHooksRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.GenerateHooks(context.Background()).FreeToolGenerateHooksRequest(freeToolGenerateHooksRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.GenerateHooks``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateHooks`: FreeToolGenerateHooksResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.GenerateHooks`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateHooksRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolGenerateHooksRequest** | [**FreeToolGenerateHooksRequest**](FreeToolGenerateHooksRequest.md) |  | 

### Return type

[**FreeToolGenerateHooksResponse**](FreeToolGenerateHooksResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateQrCode

> FreeToolGenerateQrCodeResponse GenerateQrCode(ctx).FreeToolGenerateQrCodeRequest(freeToolGenerateQrCodeRequest).Execute()

Generate a QR code (SVG) for a link or text, with optional UTM tags



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
	freeToolGenerateQrCodeRequest := *openapiclient.NewFreeToolGenerateQrCodeRequest("Data_example") // FreeToolGenerateQrCodeRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.GenerateQrCode(context.Background()).FreeToolGenerateQrCodeRequest(freeToolGenerateQrCodeRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.GenerateQrCode``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateQrCode`: FreeToolGenerateQrCodeResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.GenerateQrCode`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateQrCodeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolGenerateQrCodeRequest** | [**FreeToolGenerateQrCodeRequest**](FreeToolGenerateQrCodeRequest.md) |  | 

### Return type

[**FreeToolGenerateQrCodeResponse**](FreeToolGenerateQrCodeResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GenerateSocialPostsFromBlog

> FreeToolGenerateSocialPostsFromBlogResponse GenerateSocialPostsFromBlog(ctx).FreeToolGenerateSocialPostsFromBlogRequest(freeToolGenerateSocialPostsFromBlogRequest).Execute()

Turn a blog post (URL or text) into one social post per network with AI (needs a token, spends AI credits)



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
	freeToolGenerateSocialPostsFromBlogRequest := *openapiclient.NewFreeToolGenerateSocialPostsFromBlogRequest([]string{"Platforms_example"}) // FreeToolGenerateSocialPostsFromBlogRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.GenerateSocialPostsFromBlog(context.Background()).FreeToolGenerateSocialPostsFromBlogRequest(freeToolGenerateSocialPostsFromBlogRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.GenerateSocialPostsFromBlog``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GenerateSocialPostsFromBlog`: FreeToolGenerateSocialPostsFromBlogResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.GenerateSocialPostsFromBlog`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGenerateSocialPostsFromBlogRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolGenerateSocialPostsFromBlogRequest** | [**FreeToolGenerateSocialPostsFromBlogRequest**](FreeToolGenerateSocialPostsFromBlogRequest.md) |  | 

### Return type

[**FreeToolGenerateSocialPostsFromBlogResponse**](FreeToolGenerateSocialPostsFromBlogResponse.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetBestTimesToPost

> FreeToolGetBestTimesToPostResponse GetBestTimesToPost(ctx).Network(network).Execute()

Get the best times to post per network from published studies, with sources



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
	network := "network_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.GetBestTimesToPost(context.Background()).Network(network).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.GetBestTimesToPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBestTimesToPost`: FreeToolGetBestTimesToPostResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.GetBestTimesToPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetBestTimesToPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **network** | **string** |  | 

### Return type

[**FreeToolGetBestTimesToPostResponse**](FreeToolGetBestTimesToPostResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetHookTemplates

> FreeToolGetHookTemplatesResponse GetHookTemplates(ctx).Topic(topic).Category(category).Network(network).Search(search).Execute()

Get free hook templates for social media posts, filtered by style and network



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
	topic := "topic_example" // string |  (optional)
	category := "category_example" // string |  (optional)
	network := "network_example" // string |  (optional)
	search := "search_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.GetHookTemplates(context.Background()).Topic(topic).Category(category).Network(network).Search(search).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.GetHookTemplates``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetHookTemplates`: FreeToolGetHookTemplatesResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.GetHookTemplates`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetHookTemplatesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **topic** | **string** |  | 
 **category** | **string** |  | 
 **network** | **string** |  | 
 **search** | **string** |  | 

### Return type

[**FreeToolGetHookTemplatesResponse**](FreeToolGetHookTemplatesResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetImageSizes

> FreeToolGetImageSizesResponse GetImageSizes(ctx).Network(network).Execute()

Get social media image sizes per network, each with its source



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
	network := "network_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.GetImageSizes(context.Background()).Network(network).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.GetImageSizes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetImageSizes`: FreeToolGetImageSizesResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.GetImageSizes`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetImageSizesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **network** | **string** |  | 

### Return type

[**FreeToolGetImageSizesResponse**](FreeToolGetImageSizesResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetVideoSpecs

> FreeToolGetVideoSpecsResponse GetVideoSpecs(ctx).Network(network).Execute()

Get social media video ratios, resolutions, lengths and file size limits per network, with sources



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
	network := "network_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.GetVideoSpecs(context.Background()).Network(network).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.GetVideoSpecs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVideoSpecs`: FreeToolGetVideoSpecsResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.GetVideoSpecs`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetVideoSpecsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **network** | **string** |  | 

### Return type

[**FreeToolGetVideoSpecsResponse**](FreeToolGetVideoSpecsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListFreeTools

> FreeToolList ListFreeTools(ctx).Execute()

List the free tools



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.ListFreeTools(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.ListFreeTools``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListFreeTools`: FreeToolList
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.ListFreeTools`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiListFreeToolsRequest struct via the builder pattern


### Return type

[**FreeToolList**](FreeToolList.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PreviewPost

> FreeToolPreviewPostResponse PreviewPost(ctx).FreeToolPreviewPostRequest(freeToolPreviewPostRequest).Execute()

Preview where a post folds and when its image is cropped on Instagram, X, LinkedIn and Facebook



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
	freeToolPreviewPostRequest := *openapiclient.NewFreeToolPreviewPostRequest("Text_example") // FreeToolPreviewPostRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.PreviewPost(context.Background()).FreeToolPreviewPostRequest(freeToolPreviewPostRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.PreviewPost``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PreviewPost`: FreeToolPreviewPostResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.PreviewPost`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPreviewPostRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolPreviewPostRequest** | [**FreeToolPreviewPostRequest**](FreeToolPreviewPostRequest.md) |  | 

### Return type

[**FreeToolPreviewPostResponse**](FreeToolPreviewPostResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## SplitThread

> FreeToolSplitThreadResponse SplitThread(ctx).FreeToolSplitThreadRequest(freeToolSplitThreadRequest).Execute()

Split long text into a thread



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
	freeToolSplitThreadRequest := *openapiclient.NewFreeToolSplitThreadRequest() // FreeToolSplitThreadRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.FreeToolsAPI.SplitThread(context.Background()).FreeToolSplitThreadRequest(freeToolSplitThreadRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `FreeToolsAPI.SplitThread``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `SplitThread`: FreeToolSplitThreadResponse
	fmt.Fprintf(os.Stdout, "Response from `FreeToolsAPI.SplitThread`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiSplitThreadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **freeToolSplitThreadRequest** | [**FreeToolSplitThreadRequest**](FreeToolSplitThreadRequest.md) |  | 

### Return type

[**FreeToolSplitThreadResponse**](FreeToolSplitThreadResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

