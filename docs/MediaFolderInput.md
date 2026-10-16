# MediaFolderInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Folder name; must be unique among its siblings (case-insensitive). | [optional] 
**Parent** | Pointer to **NullableString** | UUID of the parent folder, or null for the top level. Folders nest to a limited depth. | [optional] 

## Methods

### NewMediaFolderInput

`func NewMediaFolderInput() *MediaFolderInput`

NewMediaFolderInput instantiates a new MediaFolderInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMediaFolderInputWithDefaults

`func NewMediaFolderInputWithDefaults() *MediaFolderInput`

NewMediaFolderInputWithDefaults instantiates a new MediaFolderInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *MediaFolderInput) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *MediaFolderInput) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *MediaFolderInput) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *MediaFolderInput) HasName() bool`

HasName returns a boolean if a field has been set.

### GetParent

`func (o *MediaFolderInput) GetParent() string`

GetParent returns the Parent field if non-nil, zero value otherwise.

### GetParentOk

`func (o *MediaFolderInput) GetParentOk() (*string, bool)`

GetParentOk returns a tuple with the Parent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParent

`func (o *MediaFolderInput) SetParent(v string)`

SetParent sets Parent field to given value.

### HasParent

`func (o *MediaFolderInput) HasParent() bool`

HasParent returns a boolean if a field has been set.

### SetParentNil

`func (o *MediaFolderInput) SetParentNil(b bool)`

 SetParentNil sets the value for Parent to be an explicit nil

### UnsetParent
`func (o *MediaFolderInput) UnsetParent()`

UnsetParent ensures that no value is present for Parent, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


