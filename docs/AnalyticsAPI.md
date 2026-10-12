# \AnalyticsAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateReportExport**](AnalyticsAPI.md#CreateReportExport) | **Post** /{workspaceUuid}/reports/exports | Create a report export
[**DownloadReportExport**](AnalyticsAPI.md#DownloadReportExport) | **Get** /{workspaceUuid}/reports/exports/{exportUuid}/download | Download a report file
[**GetAccountAnalytics**](AnalyticsAPI.md#GetAccountAnalytics) | **Get** /{workspaceUuid}/analytics/accounts/{accountUuid} | Get account analytics
[**GetAnalyticsSummary**](AnalyticsAPI.md#GetAnalyticsSummary) | **Get** /{workspaceUuid}/analytics | Get analytics summary
[**GetBestPostingTimes**](AnalyticsAPI.md#GetBestPostingTimes) | **Get** /{workspaceUuid}/analytics/best-times | Get best posting times
[**GetPostAnalytics_0**](AnalyticsAPI.md#GetPostAnalytics_0) | **Get** /{workspaceUuid}/posts/{postUuid}/analytics | Get post analytics
[**GetPostingTimes**](AnalyticsAPI.md#GetPostingTimes) | **Get** /{workspaceUuid}/analytics/posting-times | Get posting times heatmap
[**GetReportBranding**](AnalyticsAPI.md#GetReportBranding) | **Get** /{workspaceUuid}/report-branding | Get the report branding
[**GetReportExport**](AnalyticsAPI.md#GetReportExport) | **Get** /{workspaceUuid}/reports/exports/{exportUuid} | Get a report export
[**ListReportExports**](AnalyticsAPI.md#ListReportExports) | **Get** /{workspaceUuid}/reports/exports | List report exports
[**UpdateReportBranding**](AnalyticsAPI.md#UpdateReportBranding) | **Put** /{workspaceUuid}/report-branding | Update the report branding
[**UploadReportBrandingLogo**](AnalyticsAPI.md#UploadReportBrandingLogo) | **Post** /{workspaceUuid}/report-branding/logo | Upload the report logo



## CreateReportExport

> CreateReportExport201Response CreateReportExport(ctx, workspaceUuid).ReportExportInput(reportExportInput).Execute()

Create a report export



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
	reportExportInput := *openapiclient.NewReportExportInput("Format_example") // ReportExportInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnalyticsAPI.CreateReportExport(context.Background(), workspaceUuid).ReportExportInput(reportExportInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.CreateReportExport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateReportExport`: CreateReportExport201Response
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.CreateReportExport`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateReportExportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **reportExportInput** | [**ReportExportInput**](ReportExportInput.md) |  | 

### Return type

[**CreateReportExport201Response**](CreateReportExport201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DownloadReportExport

> *os.File DownloadReportExport(ctx, workspaceUuid, exportUuid).Execute()

Download a report file



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
	exportUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the report export.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnalyticsAPI.DownloadReportExport(context.Background(), workspaceUuid, exportUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.DownloadReportExport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DownloadReportExport`: *os.File
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.DownloadReportExport`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**exportUuid** | **string** | UUID of the report export. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDownloadReportExportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[***os.File**](*os.File.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/pdf, text/csv, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAccountAnalytics

> AccountAnalytics GetAccountAnalytics(ctx, workspaceUuid, accountUuid).Period(period).DateFrom(dateFrom).DateTo(dateTo).Type_(type_).Page(page).PerPage(perPage).SortBy(sortBy).SortDir(sortDir).Execute()

Get account analytics



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
	accountUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the social media account.
	period := "period_example" // string | Preset reporting period. Ignored when `date_from` and `date_to` are given. (optional) (default to "this_month")
	dateFrom := time.Now() // string | Start of a custom range (Y-m-d). Required with `date_to`; the range may span at most 366 days. (optional)
	dateTo := time.Now() // string | End of a custom range (Y-m-d). Required with `date_from`; must not be before it. (optional)
	type_ := "type__example" // string | Analytics tab. Defaults to the account's default tab. (optional)
	page := int32(56) // int32 | Page for list-style tabs (for example per-post metrics). (optional) (default to 1)
	perPage := int32(56) // int32 |  (optional)
	sortBy := "sortBy_example" // string |  (optional)
	sortDir := "sortDir_example" // string |  (optional) (default to "desc")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnalyticsAPI.GetAccountAnalytics(context.Background(), workspaceUuid, accountUuid).Period(period).DateFrom(dateFrom).DateTo(dateTo).Type_(type_).Page(page).PerPage(perPage).SortBy(sortBy).SortDir(sortDir).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.GetAccountAnalytics``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAccountAnalytics`: AccountAnalytics
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.GetAccountAnalytics`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**accountUuid** | **string** | UUID of the social media account. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAccountAnalyticsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **period** | **string** | Preset reporting period. Ignored when &#x60;date_from&#x60; and &#x60;date_to&#x60; are given. | [default to &quot;this_month&quot;]
 **dateFrom** | **string** | Start of a custom range (Y-m-d). Required with &#x60;date_to&#x60;; the range may span at most 366 days. | 
 **dateTo** | **string** | End of a custom range (Y-m-d). Required with &#x60;date_from&#x60;; must not be before it. | 
 **type_** | **string** | Analytics tab. Defaults to the account&#39;s default tab. | 
 **page** | **int32** | Page for list-style tabs (for example per-post metrics). | [default to 1]
 **perPage** | **int32** |  | 
 **sortBy** | **string** |  | 
 **sortDir** | **string** |  | [default to &quot;desc&quot;]

### Return type

[**AccountAnalytics**](AccountAnalytics.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetAnalyticsSummary

> AnalyticsSummary GetAnalyticsSummary(ctx, workspaceUuid).Period(period).DateFrom(dateFrom).DateTo(dateTo).Execute()

Get analytics summary



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
	period := "period_example" // string | Preset reporting period. Ignored when `date_from` and `date_to` are given. (optional) (default to "this_month")
	dateFrom := time.Now() // string | Start of a custom range (Y-m-d). Required with `date_to`; the range may span at most 366 days. (optional)
	dateTo := time.Now() // string | End of a custom range (Y-m-d). Required with `date_from`; must not be before it. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnalyticsAPI.GetAnalyticsSummary(context.Background(), workspaceUuid).Period(period).DateFrom(dateFrom).DateTo(dateTo).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.GetAnalyticsSummary``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetAnalyticsSummary`: AnalyticsSummary
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.GetAnalyticsSummary`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetAnalyticsSummaryRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **period** | **string** | Preset reporting period. Ignored when &#x60;date_from&#x60; and &#x60;date_to&#x60; are given. | [default to &quot;this_month&quot;]
 **dateFrom** | **string** | Start of a custom range (Y-m-d). Required with &#x60;date_to&#x60;; the range may span at most 366 days. | 
 **dateTo** | **string** | End of a custom range (Y-m-d). Required with &#x60;date_from&#x60;; must not be before it. | 

### Return type

[**AnalyticsSummary**](AnalyticsSummary.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetBestPostingTimes

> BestPostingTimes GetBestPostingTimes(ctx, workspaceUuid).Accounts(accounts).From(from).Timezone(timezone).Execute()

Get best posting times



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
	accounts := []string{"Inner_example"} // []string | Account UUIDs. Defaults to every account in the workspace. (optional)
	from := time.Now() // string | Earliest date to recommend (Y-m-d). Defaults to now. (optional)
	timezone := "timezone_example" // string | Timezone for `from` and the returned times. Defaults to the workspace timezone. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnalyticsAPI.GetBestPostingTimes(context.Background(), workspaceUuid).Accounts(accounts).From(from).Timezone(timezone).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.GetBestPostingTimes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetBestPostingTimes`: BestPostingTimes
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.GetBestPostingTimes`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetBestPostingTimesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **accounts** | **[]string** | Account UUIDs. Defaults to every account in the workspace. | 
 **from** | **string** | Earliest date to recommend (Y-m-d). Defaults to now. | 
 **timezone** | **string** | Timezone for &#x60;from&#x60; and the returned times. Defaults to the workspace timezone. | 

### Return type

[**BestPostingTimes**](BestPostingTimes.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetPostAnalytics_0

> PostAnalytics GetPostAnalytics_0(ctx, workspaceUuid, postUuid).Execute()

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
	resp, r, err := apiClient.AnalyticsAPI.GetPostAnalytics_0(context.Background(), workspaceUuid, postUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.GetPostAnalytics_0``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPostAnalytics_0`: PostAnalytics
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.GetPostAnalytics_0`: %v\n", resp)
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


## GetPostingTimes

> PostingTimes GetPostingTimes(ctx, workspaceUuid).Accounts(accounts).Timezone(timezone).Execute()

Get posting times heatmap



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
	accounts := []string{"Inner_example"} // []string | Account UUIDs. Defaults to every account in the workspace. (optional)
	timezone := "Europe/Istanbul" // string | Timezone the grid is expressed in. Defaults to the workspace timezone. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnalyticsAPI.GetPostingTimes(context.Background(), workspaceUuid).Accounts(accounts).Timezone(timezone).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.GetPostingTimes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetPostingTimes`: PostingTimes
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.GetPostingTimes`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetPostingTimesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **accounts** | **[]string** | Account UUIDs. Defaults to every account in the workspace. | 
 **timezone** | **string** | Timezone the grid is expressed in. Defaults to the workspace timezone. | 

### Return type

[**PostingTimes**](PostingTimes.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetReportBranding

> GetReportBranding200Response GetReportBranding(ctx, workspaceUuid).Execute()

Get the report branding



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
	resp, r, err := apiClient.AnalyticsAPI.GetReportBranding(context.Background(), workspaceUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.GetReportBranding``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetReportBranding`: GetReportBranding200Response
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.GetReportBranding`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetReportBrandingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**GetReportBranding200Response**](GetReportBranding200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetReportExport

> CreateReportExport201Response GetReportExport(ctx, workspaceUuid, exportUuid).Execute()

Get a report export

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
	exportUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the report export.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnalyticsAPI.GetReportExport(context.Background(), workspaceUuid, exportUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.GetReportExport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetReportExport`: CreateReportExport201Response
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.GetReportExport`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**exportUuid** | **string** | UUID of the report export. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetReportExportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**CreateReportExport201Response**](CreateReportExport201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListReportExports

> ListReportExports200Response ListReportExports(ctx, workspaceUuid).Execute()

List report exports



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
	resp, r, err := apiClient.AnalyticsAPI.ListReportExports(context.Background(), workspaceUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.ListReportExports``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListReportExports`: ListReportExports200Response
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.ListReportExports`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListReportExportsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListReportExports200Response**](ListReportExports200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateReportBranding

> GetReportBranding200Response UpdateReportBranding(ctx, workspaceUuid).ReportBrandingInput(reportBrandingInput).Execute()

Update the report branding



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
	reportBrandingInput := *openapiclient.NewReportBrandingInput() // ReportBrandingInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnalyticsAPI.UpdateReportBranding(context.Background(), workspaceUuid).ReportBrandingInput(reportBrandingInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.UpdateReportBranding``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateReportBranding`: GetReportBranding200Response
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.UpdateReportBranding`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateReportBrandingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **reportBrandingInput** | [**ReportBrandingInput**](ReportBrandingInput.md) |  | 

### Return type

[**GetReportBranding200Response**](GetReportBranding200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadReportBrandingLogo

> GetReportBranding200Response UploadReportBrandingLogo(ctx, workspaceUuid).Logo(logo).Execute()

Upload the report logo



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
	logo := os.NewFile(1234, "some_file") // *os.File | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.AnalyticsAPI.UploadReportBrandingLogo(context.Background(), workspaceUuid).Logo(logo).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `AnalyticsAPI.UploadReportBrandingLogo``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadReportBrandingLogo`: GetReportBranding200Response
	fmt.Fprintf(os.Stdout, "Response from `AnalyticsAPI.UploadReportBrandingLogo`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUploadReportBrandingLogoRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **logo** | ***os.File** |  | 

### Return type

[**GetReportBranding200Response**](GetReportBranding200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

