# InitiateRemoteUpload201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Uuid** | **string** |  | 
**Name** | **string** |  | 
**MimeType** | **string** |  | 
**Type** | **string** |  | 
**Url** | **string** |  | 
**ThumbUrl** | Pointer to **string** |  | [optional] 
**IsVideo** | **bool** |  | 
**IsProcessing** | Pointer to **bool** | True while an uploaded video is still being converted. | [optional] 
**Width** | Pointer to **int32** | Width in pixels, when stored. | [optional] 
**Height** | Pointer to **int32** | Height in pixels, when stored. | [optional] 
**DurationMs** | Pointer to **int32** | Video duration in milliseconds; null for images or videos not read yet. | [optional] 
**Size** | Pointer to **int32** | File size in bytes. | [optional] 
**AltText** | Pointer to **string** |  | [optional] 
**Folder** | Pointer to [**MediaFolderRef**](MediaFolderRef.md) |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**DownloadId** | Pointer to **string** |  | [optional] 

## Methods

### NewInitiateRemoteUpload201Response

`func NewInitiateRemoteUpload201Response(id int32, uuid string, name string, mimeType string, type_ string, url string, isVideo bool, createdAt time.Time, ) *InitiateRemoteUpload201Response`

NewInitiateRemoteUpload201Response instantiates a new InitiateRemoteUpload201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInitiateRemoteUpload201ResponseWithDefaults

`func NewInitiateRemoteUpload201ResponseWithDefaults() *InitiateRemoteUpload201Response`

NewInitiateRemoteUpload201ResponseWithDefaults instantiates a new InitiateRemoteUpload201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InitiateRemoteUpload201Response) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InitiateRemoteUpload201Response) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InitiateRemoteUpload201Response) SetId(v int32)`

SetId sets Id field to given value.


### GetUuid

`func (o *InitiateRemoteUpload201Response) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *InitiateRemoteUpload201Response) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *InitiateRemoteUpload201Response) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *InitiateRemoteUpload201Response) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *InitiateRemoteUpload201Response) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *InitiateRemoteUpload201Response) SetName(v string)`

SetName sets Name field to given value.


### GetMimeType

`func (o *InitiateRemoteUpload201Response) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *InitiateRemoteUpload201Response) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *InitiateRemoteUpload201Response) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.


### GetType

`func (o *InitiateRemoteUpload201Response) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *InitiateRemoteUpload201Response) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *InitiateRemoteUpload201Response) SetType(v string)`

SetType sets Type field to given value.


### GetUrl

`func (o *InitiateRemoteUpload201Response) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *InitiateRemoteUpload201Response) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *InitiateRemoteUpload201Response) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetThumbUrl

`func (o *InitiateRemoteUpload201Response) GetThumbUrl() string`

GetThumbUrl returns the ThumbUrl field if non-nil, zero value otherwise.

### GetThumbUrlOk

`func (o *InitiateRemoteUpload201Response) GetThumbUrlOk() (*string, bool)`

GetThumbUrlOk returns a tuple with the ThumbUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbUrl

`func (o *InitiateRemoteUpload201Response) SetThumbUrl(v string)`

SetThumbUrl sets ThumbUrl field to given value.

### HasThumbUrl

`func (o *InitiateRemoteUpload201Response) HasThumbUrl() bool`

HasThumbUrl returns a boolean if a field has been set.

### GetIsVideo

`func (o *InitiateRemoteUpload201Response) GetIsVideo() bool`

GetIsVideo returns the IsVideo field if non-nil, zero value otherwise.

### GetIsVideoOk

`func (o *InitiateRemoteUpload201Response) GetIsVideoOk() (*bool, bool)`

GetIsVideoOk returns a tuple with the IsVideo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsVideo

`func (o *InitiateRemoteUpload201Response) SetIsVideo(v bool)`

SetIsVideo sets IsVideo field to given value.


### GetIsProcessing

`func (o *InitiateRemoteUpload201Response) GetIsProcessing() bool`

GetIsProcessing returns the IsProcessing field if non-nil, zero value otherwise.

### GetIsProcessingOk

`func (o *InitiateRemoteUpload201Response) GetIsProcessingOk() (*bool, bool)`

GetIsProcessingOk returns a tuple with the IsProcessing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsProcessing

`func (o *InitiateRemoteUpload201Response) SetIsProcessing(v bool)`

SetIsProcessing sets IsProcessing field to given value.

### HasIsProcessing

`func (o *InitiateRemoteUpload201Response) HasIsProcessing() bool`

HasIsProcessing returns a boolean if a field has been set.

### GetWidth

`func (o *InitiateRemoteUpload201Response) GetWidth() int32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *InitiateRemoteUpload201Response) GetWidthOk() (*int32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *InitiateRemoteUpload201Response) SetWidth(v int32)`

SetWidth sets Width field to given value.

### HasWidth

`func (o *InitiateRemoteUpload201Response) HasWidth() bool`

HasWidth returns a boolean if a field has been set.

### GetHeight

`func (o *InitiateRemoteUpload201Response) GetHeight() int32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *InitiateRemoteUpload201Response) GetHeightOk() (*int32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *InitiateRemoteUpload201Response) SetHeight(v int32)`

SetHeight sets Height field to given value.

### HasHeight

`func (o *InitiateRemoteUpload201Response) HasHeight() bool`

HasHeight returns a boolean if a field has been set.

### GetDurationMs

`func (o *InitiateRemoteUpload201Response) GetDurationMs() int32`

GetDurationMs returns the DurationMs field if non-nil, zero value otherwise.

### GetDurationMsOk

`func (o *InitiateRemoteUpload201Response) GetDurationMsOk() (*int32, bool)`

GetDurationMsOk returns a tuple with the DurationMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationMs

`func (o *InitiateRemoteUpload201Response) SetDurationMs(v int32)`

SetDurationMs sets DurationMs field to given value.

### HasDurationMs

`func (o *InitiateRemoteUpload201Response) HasDurationMs() bool`

HasDurationMs returns a boolean if a field has been set.

### GetSize

`func (o *InitiateRemoteUpload201Response) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *InitiateRemoteUpload201Response) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *InitiateRemoteUpload201Response) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *InitiateRemoteUpload201Response) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetAltText

`func (o *InitiateRemoteUpload201Response) GetAltText() string`

GetAltText returns the AltText field if non-nil, zero value otherwise.

### GetAltTextOk

`func (o *InitiateRemoteUpload201Response) GetAltTextOk() (*string, bool)`

GetAltTextOk returns a tuple with the AltText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAltText

`func (o *InitiateRemoteUpload201Response) SetAltText(v string)`

SetAltText sets AltText field to given value.

### HasAltText

`func (o *InitiateRemoteUpload201Response) HasAltText() bool`

HasAltText returns a boolean if a field has been set.

### GetFolder

`func (o *InitiateRemoteUpload201Response) GetFolder() MediaFolderRef`

GetFolder returns the Folder field if non-nil, zero value otherwise.

### GetFolderOk

`func (o *InitiateRemoteUpload201Response) GetFolderOk() (*MediaFolderRef, bool)`

GetFolderOk returns a tuple with the Folder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFolder

`func (o *InitiateRemoteUpload201Response) SetFolder(v MediaFolderRef)`

SetFolder sets Folder field to given value.

### HasFolder

`func (o *InitiateRemoteUpload201Response) HasFolder() bool`

HasFolder returns a boolean if a field has been set.

### GetCreatedAt

`func (o *InitiateRemoteUpload201Response) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *InitiateRemoteUpload201Response) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *InitiateRemoteUpload201Response) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDownloadId

`func (o *InitiateRemoteUpload201Response) GetDownloadId() string`

GetDownloadId returns the DownloadId field if non-nil, zero value otherwise.

### GetDownloadIdOk

`func (o *InitiateRemoteUpload201Response) GetDownloadIdOk() (*string, bool)`

GetDownloadIdOk returns a tuple with the DownloadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownloadId

`func (o *InitiateRemoteUpload201Response) SetDownloadId(v string)`

SetDownloadId sets DownloadId field to given value.

### HasDownloadId

`func (o *InitiateRemoteUpload201Response) HasDownloadId() bool`

HasDownloadId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


