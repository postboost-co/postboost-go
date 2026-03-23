# InitiateChunkedUploadRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Filename** | **string** |  | 
**MimeType** | **string** |  | 
**TotalSize** | **int32** | Total file size in bytes. | 

## Methods

### NewInitiateChunkedUploadRequest

`func NewInitiateChunkedUploadRequest(filename string, mimeType string, totalSize int32, ) *InitiateChunkedUploadRequest`

NewInitiateChunkedUploadRequest instantiates a new InitiateChunkedUploadRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInitiateChunkedUploadRequestWithDefaults

`func NewInitiateChunkedUploadRequestWithDefaults() *InitiateChunkedUploadRequest`

NewInitiateChunkedUploadRequestWithDefaults instantiates a new InitiateChunkedUploadRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFilename

`func (o *InitiateChunkedUploadRequest) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *InitiateChunkedUploadRequest) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *InitiateChunkedUploadRequest) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetMimeType

`func (o *InitiateChunkedUploadRequest) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *InitiateChunkedUploadRequest) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *InitiateChunkedUploadRequest) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.


### GetTotalSize

`func (o *InitiateChunkedUploadRequest) GetTotalSize() int32`

GetTotalSize returns the TotalSize field if non-nil, zero value otherwise.

### GetTotalSizeOk

`func (o *InitiateChunkedUploadRequest) GetTotalSizeOk() (*int32, bool)`

GetTotalSizeOk returns a tuple with the TotalSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalSize

`func (o *InitiateChunkedUploadRequest) SetTotalSize(v int32)`

SetTotalSize sets TotalSize field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


