# PublicWorkspace

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Uuid** | **string** |  | 
**Name** | **string** |  | 
**Pivot** | Pointer to [**PublicWorkspacePivot**](PublicWorkspacePivot.md) |  | [optional] 

## Methods

### NewPublicWorkspace

`func NewPublicWorkspace(id int32, uuid string, name string, ) *PublicWorkspace`

NewPublicWorkspace instantiates a new PublicWorkspace object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublicWorkspaceWithDefaults

`func NewPublicWorkspaceWithDefaults() *PublicWorkspace`

NewPublicWorkspaceWithDefaults instantiates a new PublicWorkspace object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *PublicWorkspace) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *PublicWorkspace) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *PublicWorkspace) SetId(v int32)`

SetId sets Id field to given value.


### GetUuid

`func (o *PublicWorkspace) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *PublicWorkspace) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *PublicWorkspace) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *PublicWorkspace) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *PublicWorkspace) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *PublicWorkspace) SetName(v string)`

SetName sets Name field to given value.


### GetPivot

`func (o *PublicWorkspace) GetPivot() PublicWorkspacePivot`

GetPivot returns the Pivot field if non-nil, zero value otherwise.

### GetPivotOk

`func (o *PublicWorkspace) GetPivotOk() (*PublicWorkspacePivot, bool)`

GetPivotOk returns a tuple with the Pivot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPivot

`func (o *PublicWorkspace) SetPivot(v PublicWorkspacePivot)`

SetPivot sets Pivot field to given value.

### HasPivot

`func (o *PublicWorkspace) HasPivot() bool`

HasPivot returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


