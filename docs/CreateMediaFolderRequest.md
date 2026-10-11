# CreateMediaFolderRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Folder name; must be unique among its siblings (case-insensitive). | 
**Parent** | Pointer to **string** | UUID of the parent folder, or null for the top level. Folders nest to a limited depth. | [optional] 

## Methods

### NewCreateMediaFolderRequest

`func NewCreateMediaFolderRequest(name string, ) *CreateMediaFolderRequest`

NewCreateMediaFolderRequest instantiates a new CreateMediaFolderRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateMediaFolderRequestWithDefaults

`func NewCreateMediaFolderRequestWithDefaults() *CreateMediaFolderRequest`

NewCreateMediaFolderRequestWithDefaults instantiates a new CreateMediaFolderRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *CreateMediaFolderRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateMediaFolderRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateMediaFolderRequest) SetName(v string)`

SetName sets Name field to given value.


### GetParent

`func (o *CreateMediaFolderRequest) GetParent() string`

GetParent returns the Parent field if non-nil, zero value otherwise.

### GetParentOk

`func (o *CreateMediaFolderRequest) GetParentOk() (*string, bool)`

GetParentOk returns a tuple with the Parent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParent

`func (o *CreateMediaFolderRequest) SetParent(v string)`

SetParent sets Parent field to given value.

### HasParent

`func (o *CreateMediaFolderRequest) HasParent() bool`

HasParent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


