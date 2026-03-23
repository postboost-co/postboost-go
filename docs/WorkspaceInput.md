# WorkspaceInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**HexColor** | **string** |  | 
**OwnerId** | Pointer to **int32** |  | [optional] 
**AccessStatus** | **string** |  | 

## Methods

### NewWorkspaceInput

`func NewWorkspaceInput(name string, hexColor string, accessStatus string, ) *WorkspaceInput`

NewWorkspaceInput instantiates a new WorkspaceInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkspaceInputWithDefaults

`func NewWorkspaceInputWithDefaults() *WorkspaceInput`

NewWorkspaceInputWithDefaults instantiates a new WorkspaceInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *WorkspaceInput) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WorkspaceInput) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WorkspaceInput) SetName(v string)`

SetName sets Name field to given value.


### GetHexColor

`func (o *WorkspaceInput) GetHexColor() string`

GetHexColor returns the HexColor field if non-nil, zero value otherwise.

### GetHexColorOk

`func (o *WorkspaceInput) GetHexColorOk() (*string, bool)`

GetHexColorOk returns a tuple with the HexColor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHexColor

`func (o *WorkspaceInput) SetHexColor(v string)`

SetHexColor sets HexColor field to given value.


### GetOwnerId

`func (o *WorkspaceInput) GetOwnerId() int32`

GetOwnerId returns the OwnerId field if non-nil, zero value otherwise.

### GetOwnerIdOk

`func (o *WorkspaceInput) GetOwnerIdOk() (*int32, bool)`

GetOwnerIdOk returns a tuple with the OwnerId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerId

`func (o *WorkspaceInput) SetOwnerId(v int32)`

SetOwnerId sets OwnerId field to given value.

### HasOwnerId

`func (o *WorkspaceInput) HasOwnerId() bool`

HasOwnerId returns a boolean if a field has been set.

### GetAccessStatus

`func (o *WorkspaceInput) GetAccessStatus() string`

GetAccessStatus returns the AccessStatus field if non-nil, zero value otherwise.

### GetAccessStatusOk

`func (o *WorkspaceInput) GetAccessStatusOk() (*string, bool)`

GetAccessStatusOk returns a tuple with the AccessStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessStatus

`func (o *WorkspaceInput) SetAccessStatus(v string)`

SetAccessStatus sets AccessStatus field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


