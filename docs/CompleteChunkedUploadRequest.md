# CompleteChunkedUploadRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AltText** | Pointer to **string** |  | [optional] 
**Folder** | Pointer to **string** | UUID of the media folder to file the item in. Omit or null for the library root. | [optional] 

## Methods

### NewCompleteChunkedUploadRequest

`func NewCompleteChunkedUploadRequest() *CompleteChunkedUploadRequest`

NewCompleteChunkedUploadRequest instantiates a new CompleteChunkedUploadRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompleteChunkedUploadRequestWithDefaults

`func NewCompleteChunkedUploadRequestWithDefaults() *CompleteChunkedUploadRequest`

NewCompleteChunkedUploadRequestWithDefaults instantiates a new CompleteChunkedUploadRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAltText

`func (o *CompleteChunkedUploadRequest) GetAltText() string`

GetAltText returns the AltText field if non-nil, zero value otherwise.

### GetAltTextOk

`func (o *CompleteChunkedUploadRequest) GetAltTextOk() (*string, bool)`

GetAltTextOk returns a tuple with the AltText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAltText

`func (o *CompleteChunkedUploadRequest) SetAltText(v string)`

SetAltText sets AltText field to given value.

### HasAltText

`func (o *CompleteChunkedUploadRequest) HasAltText() bool`

HasAltText returns a boolean if a field has been set.

### GetFolder

`func (o *CompleteChunkedUploadRequest) GetFolder() string`

GetFolder returns the Folder field if non-nil, zero value otherwise.

### GetFolderOk

`func (o *CompleteChunkedUploadRequest) GetFolderOk() (*string, bool)`

GetFolderOk returns a tuple with the Folder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFolder

`func (o *CompleteChunkedUploadRequest) SetFolder(v string)`

SetFolder sets Folder field to given value.

### HasFolder

`func (o *CompleteChunkedUploadRequest) HasFolder() bool`

HasFolder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


