# DeleteResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Deleted** | **bool** |  | 
**DeletedFromApp** | **bool** |  | 
**ToTrash** | **bool** |  | 

## Methods

### NewDeleteResult

`func NewDeleteResult(deleted bool, deletedFromApp bool, toTrash bool, ) *DeleteResult`

NewDeleteResult instantiates a new DeleteResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeleteResultWithDefaults

`func NewDeleteResultWithDefaults() *DeleteResult`

NewDeleteResultWithDefaults instantiates a new DeleteResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDeleted

`func (o *DeleteResult) GetDeleted() bool`

GetDeleted returns the Deleted field if non-nil, zero value otherwise.

### GetDeletedOk

`func (o *DeleteResult) GetDeletedOk() (*bool, bool)`

GetDeletedOk returns a tuple with the Deleted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleted

`func (o *DeleteResult) SetDeleted(v bool)`

SetDeleted sets Deleted field to given value.


### GetDeletedFromApp

`func (o *DeleteResult) GetDeletedFromApp() bool`

GetDeletedFromApp returns the DeletedFromApp field if non-nil, zero value otherwise.

### GetDeletedFromAppOk

`func (o *DeleteResult) GetDeletedFromAppOk() (*bool, bool)`

GetDeletedFromAppOk returns a tuple with the DeletedFromApp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedFromApp

`func (o *DeleteResult) SetDeletedFromApp(v bool)`

SetDeletedFromApp sets DeletedFromApp field to given value.


### GetToTrash

`func (o *DeleteResult) GetToTrash() bool`

GetToTrash returns the ToTrash field if non-nil, zero value otherwise.

### GetToTrashOk

`func (o *DeleteResult) GetToTrashOk() (*bool, bool)`

GetToTrashOk returns a tuple with the ToTrash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToTrash

`func (o *DeleteResult) SetToTrash(v bool)`

SetToTrash sets ToTrash field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


