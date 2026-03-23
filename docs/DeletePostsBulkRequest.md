# DeletePostsBulkRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Posts** | **[]string** | Array of post UUIDs to delete. | 
**Trash** | Pointer to **bool** | Move to trash instead of permanent delete. | [optional] [default to false]
**DeleteMode** | Pointer to [**DeleteMode**](DeleteMode.md) |  | [optional] [default to APP_ONLY]

## Methods

### NewDeletePostsBulkRequest

`func NewDeletePostsBulkRequest(posts []string, ) *DeletePostsBulkRequest`

NewDeletePostsBulkRequest instantiates a new DeletePostsBulkRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeletePostsBulkRequestWithDefaults

`func NewDeletePostsBulkRequestWithDefaults() *DeletePostsBulkRequest`

NewDeletePostsBulkRequestWithDefaults instantiates a new DeletePostsBulkRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPosts

`func (o *DeletePostsBulkRequest) GetPosts() []string`

GetPosts returns the Posts field if non-nil, zero value otherwise.

### GetPostsOk

`func (o *DeletePostsBulkRequest) GetPostsOk() (*[]string, bool)`

GetPostsOk returns a tuple with the Posts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosts

`func (o *DeletePostsBulkRequest) SetPosts(v []string)`

SetPosts sets Posts field to given value.


### GetTrash

`func (o *DeletePostsBulkRequest) GetTrash() bool`

GetTrash returns the Trash field if non-nil, zero value otherwise.

### GetTrashOk

`func (o *DeletePostsBulkRequest) GetTrashOk() (*bool, bool)`

GetTrashOk returns a tuple with the Trash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrash

`func (o *DeletePostsBulkRequest) SetTrash(v bool)`

SetTrash sets Trash field to given value.

### HasTrash

`func (o *DeletePostsBulkRequest) HasTrash() bool`

HasTrash returns a boolean if a field has been set.

### GetDeleteMode

`func (o *DeletePostsBulkRequest) GetDeleteMode() DeleteMode`

GetDeleteMode returns the DeleteMode field if non-nil, zero value otherwise.

### GetDeleteModeOk

`func (o *DeletePostsBulkRequest) GetDeleteModeOk() (*DeleteMode, bool)`

GetDeleteModeOk returns a tuple with the DeleteMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeleteMode

`func (o *DeletePostsBulkRequest) SetDeleteMode(v DeleteMode)`

SetDeleteMode sets DeleteMode field to given value.

### HasDeleteMode

`func (o *DeletePostsBulkRequest) HasDeleteMode() bool`

HasDeleteMode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


