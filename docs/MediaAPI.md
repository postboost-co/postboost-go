# \MediaAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**AbortChunkedUpload**](MediaAPI.md#AbortChunkedUpload) | **Delete** /{workspaceUuid}/media/chunked/{uploadUuid} | Abort chunked upload
[**CompleteChunkedUpload**](MediaAPI.md#CompleteChunkedUpload) | **Post** /{workspaceUuid}/media/chunked/{uploadUuid}/complete | Complete chunked upload
[**CreateMediaFolder**](MediaAPI.md#CreateMediaFolder) | **Post** /{workspaceUuid}/media/folders | Create media folder
[**DeleteMediaBulk**](MediaAPI.md#DeleteMediaBulk) | **Delete** /{workspaceUuid}/media | Delete media (bulk)
[**DeleteMediaFolder**](MediaAPI.md#DeleteMediaFolder) | **Delete** /{workspaceUuid}/media/folders/{folderUuid} | Delete media folder
[**GetMedia**](MediaAPI.md#GetMedia) | **Get** /{workspaceUuid}/media/{mediaUuid} | Get media
[**GetRemoteUploadStatus**](MediaAPI.md#GetRemoteUploadStatus) | **Get** /{workspaceUuid}/media/remote/{downloadId}/status | Get remote upload status
[**InitiateChunkedUpload**](MediaAPI.md#InitiateChunkedUpload) | **Post** /{workspaceUuid}/media/chunked/initiate | Initiate chunked upload
[**InitiateRemoteUpload**](MediaAPI.md#InitiateRemoteUpload) | **Post** /{workspaceUuid}/media/remote/initiate | Initiate remote upload
[**ListMedia**](MediaAPI.md#ListMedia) | **Get** /{workspaceUuid}/media | List media
[**ListMediaFolders**](MediaAPI.md#ListMediaFolders) | **Get** /{workspaceUuid}/media/folders | List media folders
[**UpdateMedia**](MediaAPI.md#UpdateMedia) | **Put** /{workspaceUuid}/media/{mediaUuid} | Update media
[**UpdateMediaFolder**](MediaAPI.md#UpdateMediaFolder) | **Put** /{workspaceUuid}/media/folders/{folderUuid} | Update media folder
[**UploadChunk**](MediaAPI.md#UploadChunk) | **Post** /{workspaceUuid}/media/chunked/{uploadUuid}/upload | Upload a chunk
[**UploadMedia**](MediaAPI.md#UploadMedia) | **Post** /{workspaceUuid}/media | Upload media (binary)
[**UploadMediaBase64**](MediaAPI.md#UploadMediaBase64) | **Post** /{workspaceUuid}/media/base64 | Upload media (base64 JSON)



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

> Media CompleteChunkedUpload(ctx, workspaceUuid, uploadUuid).CompleteChunkedUploadRequest(completeChunkedUploadRequest).Execute()

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
	completeChunkedUploadRequest := *openapiclient.NewCompleteChunkedUploadRequest() // CompleteChunkedUploadRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.CompleteChunkedUpload(context.Background(), workspaceUuid, uploadUuid).CompleteChunkedUploadRequest(completeChunkedUploadRequest).Execute()
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


 **completeChunkedUploadRequest** | [**CompleteChunkedUploadRequest**](CompleteChunkedUploadRequest.md) |  | 

### Return type

[**Media**](Media.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CreateMediaFolder

> MediaFolder CreateMediaFolder(ctx, workspaceUuid).CreateMediaFolderRequest(createMediaFolderRequest).IdempotencyKey(idempotencyKey).Execute()

Create media folder



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
	createMediaFolderRequest := *openapiclient.NewCreateMediaFolderRequest("Name_example") // CreateMediaFolderRequest | 
	idempotencyKey := "idempotencyKey_example" // string | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with `Idempotent-Replayed: true` and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.CreateMediaFolder(context.Background(), workspaceUuid).CreateMediaFolderRequest(createMediaFolderRequest).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MediaAPI.CreateMediaFolder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateMediaFolder`: MediaFolder
	fmt.Fprintf(os.Stdout, "Response from `MediaAPI.CreateMediaFolder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateMediaFolderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createMediaFolderRequest** | [**CreateMediaFolderRequest**](CreateMediaFolderRequest.md) |  | 
 **idempotencyKey** | **string** | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with &#x60;Idempotent-Replayed: true&#x60; and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  | 

### Return type

[**MediaFolder**](MediaFolder.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
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
	deleteMediaBulkRequest := *openapiclient.NewDeleteMediaBulkRequest([]openapiclient.DeleteMediaBulkRequestItemsInner{openapiclient.deleteMediaBulk_request_items_inner{Int32: new(int32)}}) // DeleteMediaBulkRequest | 

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


## DeleteMediaFolder

> map[string]interface{} DeleteMediaFolder(ctx, workspaceUuid, folderUuid).DeleteMediaFolderRequest(deleteMediaFolderRequest).Execute()

Delete media folder



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
	folderUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the media folder.
	deleteMediaFolderRequest := *openapiclient.NewDeleteMediaFolderRequest() // DeleteMediaFolderRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.DeleteMediaFolder(context.Background(), workspaceUuid, folderUuid).DeleteMediaFolderRequest(deleteMediaFolderRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MediaAPI.DeleteMediaFolder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteMediaFolder`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `MediaAPI.DeleteMediaFolder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**folderUuid** | **string** | UUID of the media folder. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteMediaFolderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **deleteMediaFolderRequest** | [**DeleteMediaFolderRequest**](DeleteMediaFolderRequest.md) |  | 

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

> InitiateChunkedUpload201Response InitiateChunkedUpload(ctx, workspaceUuid).InitiateChunkedUploadRequest(initiateChunkedUploadRequest).IdempotencyKey(idempotencyKey).Execute()

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
	idempotencyKey := "idempotencyKey_example" // string | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with `Idempotent-Replayed: true` and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.InitiateChunkedUpload(context.Background(), workspaceUuid).InitiateChunkedUploadRequest(initiateChunkedUploadRequest).IdempotencyKey(idempotencyKey).Execute()
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
 **idempotencyKey** | **string** | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with &#x60;Idempotent-Replayed: true&#x60; and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  | 

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

> InitiateRemoteUpload201Response InitiateRemoteUpload(ctx, workspaceUuid).InitiateRemoteUploadRequest(initiateRemoteUploadRequest).IdempotencyKey(idempotencyKey).Execute()

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
	idempotencyKey := "idempotencyKey_example" // string | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with `Idempotent-Replayed: true` and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.InitiateRemoteUpload(context.Background(), workspaceUuid).InitiateRemoteUploadRequest(initiateRemoteUploadRequest).IdempotencyKey(idempotencyKey).Execute()
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
 **idempotencyKey** | **string** | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with &#x60;Idempotent-Replayed: true&#x60; and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  | 

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

> ListMedia200Response ListMedia(ctx, workspaceUuid).Page(page).Limit(limit).Folder(folder).MimeTypes(mimeTypes).Type_(type_).Keyword(keyword).Usage(usage).Favorite(favorite).Sort(sort).Execute()

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
	page := int32(56) // int32 | Page number. (optional) (default to 1)
	limit := int32(56) // int32 | Items per page. Values below 1 fall back to 50; values above 100 are capped at 100. (optional) (default to 50)
	folder := "folder_example" // string | Media folder UUID, or `root` for items not filed in any folder. (optional)
	mimeTypes := []string{"Inner_example"} // []string | Only these MIME types (for example `image/png`). (optional)
	type_ := "type__example" // string | Only this media type. (optional)
	keyword := "keyword_example" // string | Search media by name. (optional)
	usage := "usage_example" // string | Filter by how the media is used in posts. (optional)
	favorite := true // bool | When `true`, only media the caller marked as favorite. (optional)
	sort := "sort_example" // string |  (optional) (default to "newest")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.ListMedia(context.Background(), workspaceUuid).Page(page).Limit(limit).Folder(folder).MimeTypes(mimeTypes).Type_(type_).Keyword(keyword).Usage(usage).Favorite(favorite).Sort(sort).Execute()
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

 **page** | **int32** | Page number. | [default to 1]
 **limit** | **int32** | Items per page. Values below 1 fall back to 50; values above 100 are capped at 100. | [default to 50]
 **folder** | **string** | Media folder UUID, or &#x60;root&#x60; for items not filed in any folder. | 
 **mimeTypes** | **[]string** | Only these MIME types (for example &#x60;image/png&#x60;). | 
 **type_** | **string** | Only this media type. | 
 **keyword** | **string** | Search media by name. | 
 **usage** | **string** | Filter by how the media is used in posts. | 
 **favorite** | **bool** | When &#x60;true&#x60;, only media the caller marked as favorite. | 
 **sort** | **string** |  | [default to &quot;newest&quot;]

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


## ListMediaFolders

> ListMediaFolders200Response ListMediaFolders(ctx, workspaceUuid).Execute()

List media folders



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
	resp, r, err := apiClient.MediaAPI.ListMediaFolders(context.Background(), workspaceUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MediaAPI.ListMediaFolders``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListMediaFolders`: ListMediaFolders200Response
	fmt.Fprintf(os.Stdout, "Response from `MediaAPI.ListMediaFolders`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiListMediaFoldersRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListMediaFolders200Response**](ListMediaFolders200Response.md)

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
	updateMediaRequest := *openapiclient.NewUpdateMediaRequest() // UpdateMediaRequest | 

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


## UpdateMediaFolder

> MediaFolder UpdateMediaFolder(ctx, workspaceUuid, folderUuid).MediaFolderInput(mediaFolderInput).Execute()

Update media folder



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
	folderUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the media folder.
	mediaFolderInput := *openapiclient.NewMediaFolderInput() // MediaFolderInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.UpdateMediaFolder(context.Background(), workspaceUuid, folderUuid).MediaFolderInput(mediaFolderInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MediaAPI.UpdateMediaFolder``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateMediaFolder`: MediaFolder
	fmt.Fprintf(os.Stdout, "Response from `MediaAPI.UpdateMediaFolder`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 
**folderUuid** | **string** | UUID of the media folder. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateMediaFolderRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **mediaFolderInput** | [**MediaFolderInput**](MediaFolderInput.md) |  | 

### Return type

[**MediaFolder**](MediaFolder.md)

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

> Media UploadMedia(ctx, workspaceUuid).File(file).IdempotencyKey(idempotencyKey).AltText(altText).Folder(folder).Execute()

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
	idempotencyKey := "idempotencyKey_example" // string | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with `Idempotent-Replayed: true` and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  (optional)
	altText := "altText_example" // string | Alternative text for accessibility. (optional)
	folder := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the media folder to file the upload in. Omit or null for the library root. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.UploadMedia(context.Background(), workspaceUuid).File(file).IdempotencyKey(idempotencyKey).AltText(altText).Folder(folder).Execute()
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
 **idempotencyKey** | **string** | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with &#x60;Idempotent-Replayed: true&#x60; and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  | 
 **altText** | **string** | Alternative text for accessibility. | 
 **folder** | **string** | UUID of the media folder to file the upload in. Omit or null for the library root. | 

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


## UploadMediaBase64

> Media UploadMediaBase64(ctx, workspaceUuid).MediaBase64Input(mediaBase64Input).IdempotencyKey(idempotencyKey).Execute()

Upload media (base64 JSON)



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
	mediaBase64Input := *openapiclient.NewMediaBase64Input("Content_example", "cover.png") // MediaBase64Input | 
	idempotencyKey := "idempotencyKey_example" // string | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with `Idempotent-Replayed: true` and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.MediaAPI.UploadMediaBase64(context.Background(), workspaceUuid).MediaBase64Input(mediaBase64Input).IdempotencyKey(idempotencyKey).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `MediaAPI.UploadMediaBase64``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadMediaBase64`: Media
	fmt.Fprintf(os.Stdout, "Response from `MediaAPI.UploadMediaBase64`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**workspaceUuid** | **string** | UUID of the workspace. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUploadMediaBase64Request struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **mediaBase64Input** | [**MediaBase64Input**](MediaBase64Input.md) |  | 
 **idempotencyKey** | **string** | Unique key (for example a UUID) that makes the request safe to retry. A repeat with the same key and body within 24 hours returns the stored response with &#x60;Idempotent-Replayed: true&#x60; and has no further effect. Keys are scoped to your user, the workspace, the method and the path.  | 

### Return type

[**Media**](Media.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

