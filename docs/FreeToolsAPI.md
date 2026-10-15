# \FreeToolsAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**BuildUtmUrl**](FreeToolsAPI.md#BuildUtmUrl) | **Post** /tools/utm-builder | Build a UTM-tagged campaign URL
[**CalculateEngagementRate**](FreeToolsAPI.md#CalculateEngagementRate) | **Post** /tools/engagement-rate-calculator | Calculate an engagement rate
[**CheckPost**](FreeToolsAPI.md#CheckPost) | **Post** /tools/social-media-post-checker | Check a post against each network&#39;s publishing rules
[**CleanText**](FreeToolsAPI.md#CleanText) | **Post** /tools/ai-text-cleaner | Clean AI-written text: dashes, quotes, invisible characters, markdown
[**CountCharacters**](FreeToolsAPI.md#CountCharacters) | **Post** /tools/social-media-character-counter | Count characters as each network counts them
[**FormatLinkedInPost**](FreeToolsAPI.md#FormatLinkedInPost) | **Post** /tools/linkedin-post-formatter | Format a LinkedIn post with bold, italic and lists
[**GenerateFancyText**](FreeToolsAPI.md#GenerateFancyText) | **Post** /tools/fancy-text-generator | Convert text to fancy Unicode styles
[**ListFreeTools**](FreeToolsAPI.md#ListFreeTools) | **Get** /tools | List the free tools
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

