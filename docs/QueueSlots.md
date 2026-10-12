# QueueSlots

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Slots** | **[]map[string]interface{}** | Upcoming posting times and scheduled posts, in order. | 
**NextCursor** | **NullableString** | Pass as &#x60;after&#x60; for the next page; null at the end. | 

## Methods

### NewQueueSlots

`func NewQueueSlots(slots []map[string]interface{}, nextCursor NullableString, ) *QueueSlots`

NewQueueSlots instantiates a new QueueSlots object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueueSlotsWithDefaults

`func NewQueueSlotsWithDefaults() *QueueSlots`

NewQueueSlotsWithDefaults instantiates a new QueueSlots object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSlots

`func (o *QueueSlots) GetSlots() []map[string]interface{}`

GetSlots returns the Slots field if non-nil, zero value otherwise.

### GetSlotsOk

`func (o *QueueSlots) GetSlotsOk() (*[]map[string]interface{}, bool)`

GetSlotsOk returns a tuple with the Slots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlots

`func (o *QueueSlots) SetSlots(v []map[string]interface{})`

SetSlots sets Slots field to given value.


### GetNextCursor

`func (o *QueueSlots) GetNextCursor() string`

GetNextCursor returns the NextCursor field if non-nil, zero value otherwise.

### GetNextCursorOk

`func (o *QueueSlots) GetNextCursorOk() (*string, bool)`

GetNextCursorOk returns a tuple with the NextCursor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextCursor

`func (o *QueueSlots) SetNextCursor(v string)`

SetNextCursor sets NextCursor field to given value.


### SetNextCursorNil

`func (o *QueueSlots) SetNextCursorNil(b bool)`

 SetNextCursorNil sets the value for NextCursor to be an explicit nil

### UnsetNextCursor
`func (o *QueueSlots) UnsetNextCursor()`

UnsetNextCursor ensures that no value is present for NextCursor, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


