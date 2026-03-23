# \MediaAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AbortChunkedUpload**](MediaAPI.md#AbortChunkedUpload) | **Delete** /{workspaceUuid}/media/chunked/{uploadUuid} | Abort chunked upload
[**CompleteChunkedUpload**](MediaAPI.md#CompleteChunkedUpload) | **Post** /{workspaceUuid}/media/chunked/{uploadUuid}/complete | Complete chunked upload
[**DeleteMediaBulk**](MediaAPI.md#DeleteMediaBulk) | **Delete** /{workspaceUuid}/media | Delete media (bulk)
[**GetMedia**](MediaAPI.md#GetMedia) | **Get** /{workspaceUuid}/media/{mediaUuid} | Get media
[**GetRemoteUploadStatus**](MediaAPI.md#GetRemoteUploadStatus) | **Get** /{workspaceUuid}/media/remote/{downloadId}/status | Get remote upload status
[**InitiateChunkedUpload**](MediaAPI.md#InitiateChunkedUpload) | **Post** /{workspaceUuid}/media/chunked/initiate | Initiate chunked upload
[**InitiateRemoteUpload**](MediaAPI.md#InitiateRemoteUpload) | **Post** /{workspaceUuid}/media/remote/initiate | Initiate remote upload
[**ListMedia**](MediaAPI.md#ListMedia) | **Get** /{workspaceUuid}/media | List media
[**UpdateMedia**](MediaAPI.md#UpdateMedia) | **Put** /{workspaceUuid}/media/{mediaUuid} | Update media
[**UploadChunk**](MediaAPI.md#UploadChunk) | **Post** /{workspaceUuid}/media/chunked/{uploadUuid}/upload | Upload a chunk
[**UploadMedia**](MediaAPI.md#UploadMedia) | **Post** /{workspaceUuid}/media | Upload media (binary)



## AbortChunkedUpload

> AbortChunkedUpload(ctx, workspaceUuid, uploadUuid).Execute()

Abort chunked upload



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
	uploadUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	r, err := apiClient.MediaAPI.AbortChunkedUpload(context.Background(), workspaceUuid, uploadUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MediaAPI.AbortChunkedUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**uploadUuid** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiAbortChunkedUploadRequest struct via the builder pattern


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


## CompleteChunkedUpload

> Media CompleteChunkedUpload(ctx, workspaceUuid, uploadUuid).Execute()

Complete chunked upload



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
	uploadUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.CompleteChunkedUpload(context.Background(), workspaceUuid, uploadUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MediaAPI.CompleteChunkedUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompleteChunkedUpload`: Media
	fmt.Fprintf(os.Stdout, "Response from `MediaAPI.CompleteChunkedUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**uploadUuid** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCompleteChunkedUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**Media**](Media.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteMediaBulk

> map[string]interface{} DeleteMediaBulk(ctx, workspaceUuid).DeleteMediaBulkRequest(deleteMediaBulkRequest).Execute()

Delete media (bulk)



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
	deleteMediaBulkRequest := *openapiclient.NewDeleteMediaBulkRequest([]int32{int32(123)}) // DeleteMediaBulkRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.DeleteMediaBulk(context.Background(), workspaceUuid).DeleteMediaBulkRequest(deleteMediaBulkRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MediaAPI.DeleteMediaBulk``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteMediaBulk`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `MediaAPI.DeleteMediaBulk`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteMediaBulkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **deleteMediaBulkRequest** | [**DeleteMediaBulkRequest**](DeleteMediaBulkRequest.md) |  | 

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


## GetMedia

> Media GetMedia(ctx, workspaceUuid, mediaUuid).Execute()

Get media



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
	mediaUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the media asset.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.GetMedia(context.Background(), workspaceUuid, mediaUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MediaAPI.GetMedia``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetMedia`: Media
	fmt.Fprintf(os.Stdout, "Response from `MediaAPI.GetMedia`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**mediaUuid** | **string** | UUID of the media asset. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetMediaRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**Media**](Media.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetRemoteUploadStatus

> GetRemoteUploadStatus200Response GetRemoteUploadStatus(ctx, workspaceUuid, downloadId).Execute()

Get remote upload status



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
	downloadId := "downloadId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.GetRemoteUploadStatus(context.Background(), workspaceUuid, downloadId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MediaAPI.GetRemoteUploadStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetRemoteUploadStatus`: GetRemoteUploadStatus200Response
	fmt.Fprintf(os.Stdout, "Response from `MediaAPI.GetRemoteUploadStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**downloadId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetRemoteUploadStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

[**GetRemoteUploadStatus200Response**](GetRemoteUploadStatus200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InitiateChunkedUpload

> InitiateChunkedUpload201Response InitiateChunkedUpload(ctx, workspaceUuid).InitiateChunkedUploadRequest(initiateChunkedUploadRequest).Execute()

Initiate chunked upload



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
	initiateChunkedUploadRequest := *openapiclient.NewInitiateChunkedUploadRequest("Filename_example", "video/mp4", int32(123)) // InitiateChunkedUploadRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.InitiateChunkedUpload(context.Background(), workspaceUuid).InitiateChunkedUploadRequest(initiateChunkedUploadRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MediaAPI.InitiateChunkedUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InitiateChunkedUpload`: InitiateChunkedUpload201Response
	fmt.Fprintf(os.Stdout, "Response from `MediaAPI.InitiateChunkedUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInitiateChunkedUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **initiateChunkedUploadRequest** | [**InitiateChunkedUploadRequest**](InitiateChunkedUploadRequest.md) |  | 

### Return type

[**InitiateChunkedUpload201Response**](InitiateChunkedUpload201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## InitiateRemoteUpload

> InitiateRemoteUpload201Response InitiateRemoteUpload(ctx, workspaceUuid).InitiateRemoteUploadRequest(initiateRemoteUploadRequest).Execute()

Initiate remote upload



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
	initiateRemoteUploadRequest := *openapiclient.NewInitiateRemoteUploadRequest("Url_example") // InitiateRemoteUploadRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.InitiateRemoteUpload(context.Background(), workspaceUuid).InitiateRemoteUploadRequest(initiateRemoteUploadRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MediaAPI.InitiateRemoteUpload``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `InitiateRemoteUpload`: InitiateRemoteUpload201Response
	fmt.Fprintf(os.Stdout, "Response from `MediaAPI.InitiateRemoteUpload`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiInitiateRemoteUploadRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **initiateRemoteUploadRequest** | [**InitiateRemoteUploadRequest**](InitiateRemoteUploadRequest.md) |  | 

### Return type

[**InitiateRemoteUpload201Response**](InitiateRemoteUpload201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListMedia

> ListMedia200Response ListMedia(ctx, workspaceUuid).Page(page).Execute()

List media



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
	page := int32(56) // int32 | Page number (20 items per page). (optional) (default to 1)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.ListMedia(context.Background(), workspaceUuid).Page(page).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MediaAPI.ListMedia``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListMedia`: ListMedia200Response
	fmt.Fprintf(os.Stdout, "Response from `MediaAPI.ListMedia`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListMediaRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **page** | **int32** | Page number (20 items per page). | [default to 1]

### Return type

[**ListMedia200Response**](ListMedia200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateMedia

> map[string]interface{} UpdateMedia(ctx, workspaceUuid, mediaUuid).UpdateMediaRequest(updateMediaRequest).Execute()

Update media



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
	mediaUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the media asset.
	updateMediaRequest := *openapiclient.NewUpdateMediaRequest("AltText_example") // UpdateMediaRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.UpdateMedia(context.Background(), workspaceUuid, mediaUuid).UpdateMediaRequest(updateMediaRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MediaAPI.UpdateMedia``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateMedia`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `MediaAPI.UpdateMedia`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**mediaUuid** | **string** | UUID of the media asset. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateMediaRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **updateMediaRequest** | [**UpdateMediaRequest**](UpdateMediaRequest.md) |  | 

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


## UploadChunk

> UploadChunk201Response UploadChunk(ctx, workspaceUuid, uploadUuid).Chunk(chunk).ChunkIndex(chunkIndex).Execute()

Upload a chunk



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
	uploadUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | 
	chunk := os.NewFile(1234, "some_file") // *os.File | 
	chunkIndex := int32(56) // int32 | Zero-based index of this chunk.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.UploadChunk(context.Background(), workspaceUuid, uploadUuid).Chunk(chunk).ChunkIndex(chunkIndex).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MediaAPI.UploadChunk``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadChunk`: UploadChunk201Response
	fmt.Fprintf(os.Stdout, "Response from `MediaAPI.UploadChunk`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**uploadUuid** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUploadChunkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **chunk** | ***os.File** |  | 
 **chunkIndex** | **int32** | Zero-based index of this chunk. | 

### Return type

[**UploadChunk201Response**](UploadChunk201Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadMedia

> Media UploadMedia(ctx, workspaceUuid).File(file).AltText(altText).Execute()

Upload media (binary)



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
	file := os.NewFile(1234, "some_file") // *os.File | The file to upload.
	altText := "altText_example" // string | Alternative text for accessibility. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.UploadMedia(context.Background(), workspaceUuid).File(file).AltText(altText).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MediaAPI.UploadMedia``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadMedia`: Media
	fmt.Fprintf(os.Stdout, "Response from `MediaAPI.UploadMedia`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUploadMediaRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **file** | ***os.File** | The file to upload. | 
 **altText** | **string** | Alternative text for accessibility. | 

### Return type

[**Media**](Media.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

