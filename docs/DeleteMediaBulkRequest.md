# DeleteMediaBulkRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Items** | [**[]DeleteMediaBulkRequestItemsInner**](DeleteMediaBulkRequestItemsInner.md) | Array of media IDs or UUIDs to delete. | 

## Methods

### NewDeleteMediaBulkRequest

`func NewDeleteMediaBulkRequest(items []DeleteMediaBulkRequestItemsInner, ) *DeleteMediaBulkRequest`

NewDeleteMediaBulkRequest instantiates a new DeleteMediaBulkRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDeleteMediaBulkRequestWithDefaults

`func NewDeleteMediaBulkRequestWithDefaults() *DeleteMediaBulkRequest`

NewDeleteMediaBulkRequestWithDefaults instantiates a new DeleteMediaBulkRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetItems

`func (o *DeleteMediaBulkRequest) GetItems() []DeleteMediaBulkRequestItemsInner`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *DeleteMediaBulkRequest) GetItemsOk() (*[]DeleteMediaBulkRequestItemsInner, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *DeleteMediaBulkRequest) SetItems(v []DeleteMediaBulkRequestItemsInner)`

SetItems sets Items field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


