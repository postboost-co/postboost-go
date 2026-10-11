# UpdateMediaRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**AltText** | Pointer to **string** | Alternative text for accessibility. | [optional] 
**Folder** | Pointer to **string** | UUID of the media folder to move the item to, or null for the library root. | [optional] 

## Methods

### NewUpdateMediaRequest

`func NewUpdateMediaRequest() *UpdateMediaRequest`

NewUpdateMediaRequest instantiates a new UpdateMediaRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUpdateMediaRequestWithDefaults

`func NewUpdateMediaRequestWithDefaults() *UpdateMediaRequest`

NewUpdateMediaRequestWithDefaults instantiates a new UpdateMediaRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UpdateMediaRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UpdateMediaRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UpdateMediaRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *UpdateMediaRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetAltText

`func (o *UpdateMediaRequest) GetAltText() string`

GetAltText returns the AltText field if non-nil, zero value otherwise.

### GetAltTextOk

`func (o *UpdateMediaRequest) GetAltTextOk() (*string, bool)`

GetAltTextOk returns a tuple with the AltText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAltText

`func (o *UpdateMediaRequest) SetAltText(v string)`

SetAltText sets AltText field to given value.

### HasAltText

`func (o *UpdateMediaRequest) HasAltText() bool`

HasAltText returns a boolean if a field has been set.

### GetFolder

`func (o *UpdateMediaRequest) GetFolder() string`

GetFolder returns the Folder field if non-nil, zero value otherwise.

### GetFolderOk

`func (o *UpdateMediaRequest) GetFolderOk() (*string, bool)`

GetFolderOk returns a tuple with the Folder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFolder

`func (o *UpdateMediaRequest) SetFolder(v string)`

SetFolder sets Folder field to given value.

### HasFolder

`func (o *UpdateMediaRequest) HasFolder() bool`

HasFolder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


