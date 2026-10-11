# Media

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
**Folder** | Pointer to [**NullableMediaFolderRef**](MediaFolderRef.md) |  | [optional] 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewMedia

`func NewMedia(id int32, uuid string, name string, mimeType string, type_ string, url string, isVideo bool, createdAt time.Time, ) *Media`

NewMedia instantiates a new Media object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMediaWithDefaults

`func NewMediaWithDefaults() *Media`

NewMediaWithDefaults instantiates a new Media object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Media) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Media) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Media) SetId(v int32)`

SetId sets Id field to given value.


### GetUuid

`func (o *Media) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *Media) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *Media) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *Media) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Media) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Media) SetName(v string)`

SetName sets Name field to given value.


### GetMimeType

`func (o *Media) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *Media) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *Media) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.


### GetType

`func (o *Media) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Media) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Media) SetType(v string)`

SetType sets Type field to given value.


### GetUrl

`func (o *Media) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *Media) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *Media) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetThumbUrl

`func (o *Media) GetThumbUrl() string`

GetThumbUrl returns the ThumbUrl field if non-nil, zero value otherwise.

### GetThumbUrlOk

`func (o *Media) GetThumbUrlOk() (*string, bool)`

GetThumbUrlOk returns a tuple with the ThumbUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbUrl

`func (o *Media) SetThumbUrl(v string)`

SetThumbUrl sets ThumbUrl field to given value.

### HasThumbUrl

`func (o *Media) HasThumbUrl() bool`

HasThumbUrl returns a boolean if a field has been set.

### GetIsVideo

`func (o *Media) GetIsVideo() bool`

GetIsVideo returns the IsVideo field if non-nil, zero value otherwise.

### GetIsVideoOk

`func (o *Media) GetIsVideoOk() (*bool, bool)`

GetIsVideoOk returns a tuple with the IsVideo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsVideo

`func (o *Media) SetIsVideo(v bool)`

SetIsVideo sets IsVideo field to given value.


### GetIsProcessing

`func (o *Media) GetIsProcessing() bool`

GetIsProcessing returns the IsProcessing field if non-nil, zero value otherwise.

### GetIsProcessingOk

`func (o *Media) GetIsProcessingOk() (*bool, bool)`

GetIsProcessingOk returns a tuple with the IsProcessing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsProcessing

`func (o *Media) SetIsProcessing(v bool)`

SetIsProcessing sets IsProcessing field to given value.

### HasIsProcessing

`func (o *Media) HasIsProcessing() bool`

HasIsProcessing returns a boolean if a field has been set.

### GetWidth

`func (o *Media) GetWidth() int32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *Media) GetWidthOk() (*int32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *Media) SetWidth(v int32)`

SetWidth sets Width field to given value.

### HasWidth

`func (o *Media) HasWidth() bool`

HasWidth returns a boolean if a field has been set.

### GetHeight

`func (o *Media) GetHeight() int32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *Media) GetHeightOk() (*int32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *Media) SetHeight(v int32)`

SetHeight sets Height field to given value.

### HasHeight

`func (o *Media) HasHeight() bool`

HasHeight returns a boolean if a field has been set.

### GetDurationMs

`func (o *Media) GetDurationMs() int32`

GetDurationMs returns the DurationMs field if non-nil, zero value otherwise.

### GetDurationMsOk

`func (o *Media) GetDurationMsOk() (*int32, bool)`

GetDurationMsOk returns a tuple with the DurationMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationMs

`func (o *Media) SetDurationMs(v int32)`

SetDurationMs sets DurationMs field to given value.

### HasDurationMs

`func (o *Media) HasDurationMs() bool`

HasDurationMs returns a boolean if a field has been set.

### GetSize

`func (o *Media) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *Media) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *Media) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *Media) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetAltText

`func (o *Media) GetAltText() string`

GetAltText returns the AltText field if non-nil, zero value otherwise.

### GetAltTextOk

`func (o *Media) GetAltTextOk() (*string, bool)`

GetAltTextOk returns a tuple with the AltText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAltText

`func (o *Media) SetAltText(v string)`

SetAltText sets AltText field to given value.

### HasAltText

`func (o *Media) HasAltText() bool`

HasAltText returns a boolean if a field has been set.

### GetFolder

`func (o *Media) GetFolder() MediaFolderRef`

GetFolder returns the Folder field if non-nil, zero value otherwise.

### GetFolderOk

`func (o *Media) GetFolderOk() (*MediaFolderRef, bool)`

GetFolderOk returns a tuple with the Folder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFolder

`func (o *Media) SetFolder(v MediaFolderRef)`

SetFolder sets Folder field to given value.

### HasFolder

`func (o *Media) HasFolder() bool`

HasFolder returns a boolean if a field has been set.

### SetFolderNil

`func (o *Media) SetFolderNil(b bool)`

 SetFolderNil sets the value for Folder to be an explicit nil

### UnsetFolder
`func (o *Media) UnsetFolder()`

UnsetFolder ensures that no value is present for Folder, not even an explicit nil
### GetCreatedAt

`func (o *Media) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Media) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Media) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


