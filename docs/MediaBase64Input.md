# MediaBase64Input

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Content** | **string** | The file as base64. A &#x60;data:&lt;mime&gt;;base64,&#x60; prefix is accepted. At most 20 MB once decoded. | 
**Filename** | **string** | File name with extension, for example &#x60;cover.png&#x60;. No folders. | 
**AltText** | Pointer to **NullableString** | Alternative text for accessibility. | [optional] 
**Folder** | Pointer to **NullableString** | UUID of the media folder to file the upload in. Omit or null for the library root. | [optional] 

## Methods

### NewMediaBase64Input

`func NewMediaBase64Input(content string, filename string, ) *MediaBase64Input`

NewMediaBase64Input instantiates a new MediaBase64Input object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMediaBase64InputWithDefaults

`func NewMediaBase64InputWithDefaults() *MediaBase64Input`

NewMediaBase64InputWithDefaults instantiates a new MediaBase64Input object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetContent

`func (o *MediaBase64Input) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *MediaBase64Input) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *MediaBase64Input) SetContent(v string)`

SetContent sets Content field to given value.


### GetFilename

`func (o *MediaBase64Input) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *MediaBase64Input) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *MediaBase64Input) SetFilename(v string)`

SetFilename sets Filename field to given value.


### GetAltText

`func (o *MediaBase64Input) GetAltText() string`

GetAltText returns the AltText field if non-nil, zero value otherwise.

### GetAltTextOk

`func (o *MediaBase64Input) GetAltTextOk() (*string, bool)`

GetAltTextOk returns a tuple with the AltText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAltText

`func (o *MediaBase64Input) SetAltText(v string)`

SetAltText sets AltText field to given value.

### HasAltText

`func (o *MediaBase64Input) HasAltText() bool`

HasAltText returns a boolean if a field has been set.

### SetAltTextNil

`func (o *MediaBase64Input) SetAltTextNil(b bool)`

 SetAltTextNil sets the value for AltText to be an explicit nil

### UnsetAltText
`func (o *MediaBase64Input) UnsetAltText()`

UnsetAltText ensures that no value is present for AltText, not even an explicit nil
### GetFolder

`func (o *MediaBase64Input) GetFolder() string`

GetFolder returns the Folder field if non-nil, zero value otherwise.

### GetFolderOk

`func (o *MediaBase64Input) GetFolderOk() (*string, bool)`

GetFolderOk returns a tuple with the Folder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFolder

`func (o *MediaBase64Input) SetFolder(v string)`

SetFolder sets Folder field to given value.

### HasFolder

`func (o *MediaBase64Input) HasFolder() bool`

HasFolder returns a boolean if a field has been set.

### SetFolderNil

`func (o *MediaBase64Input) SetFolderNil(b bool)`

 SetFolderNil sets the value for Folder to be an explicit nil

### UnsetFolder
`func (o *MediaBase64Input) UnsetFolder()`

UnsetFolder ensures that no value is present for Folder, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


