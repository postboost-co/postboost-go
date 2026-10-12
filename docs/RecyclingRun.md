# RecyclingRun

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Status** | **string** |  | 
**Reason** | **NullableString** | Why the run skipped or failed; on &#x60;created&#x60;, a note such as &#x60;x_skipped_identical_text&#x60;. | 
**SourcePostUuid** | **NullableString** |  | 
**CreatedPostUuid** | **NullableString** |  | 
**CreatedAt** | **NullableTime** |  | 

## Methods

### NewRecyclingRun

`func NewRecyclingRun(id int32, status string, reason NullableString, sourcePostUuid NullableString, createdPostUuid NullableString, createdAt NullableTime, ) *RecyclingRun`

NewRecyclingRun instantiates a new RecyclingRun object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecyclingRunWithDefaults

`func NewRecyclingRunWithDefaults() *RecyclingRun`

NewRecyclingRunWithDefaults instantiates a new RecyclingRun object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RecyclingRun) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RecyclingRun) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RecyclingRun) SetId(v int32)`

SetId sets Id field to given value.


### GetStatus

`func (o *RecyclingRun) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RecyclingRun) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RecyclingRun) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetReason

`func (o *RecyclingRun) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *RecyclingRun) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *RecyclingRun) SetReason(v string)`

SetReason sets Reason field to given value.


### SetReasonNil

`func (o *RecyclingRun) SetReasonNil(b bool)`

 SetReasonNil sets the value for Reason to be an explicit nil

### UnsetReason
`func (o *RecyclingRun) UnsetReason()`

UnsetReason ensures that no value is present for Reason, not even an explicit nil
### GetSourcePostUuid

`func (o *RecyclingRun) GetSourcePostUuid() string`

GetSourcePostUuid returns the SourcePostUuid field if non-nil, zero value otherwise.

### GetSourcePostUuidOk

`func (o *RecyclingRun) GetSourcePostUuidOk() (*string, bool)`

GetSourcePostUuidOk returns a tuple with the SourcePostUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourcePostUuid

`func (o *RecyclingRun) SetSourcePostUuid(v string)`

SetSourcePostUuid sets SourcePostUuid field to given value.


### SetSourcePostUuidNil

`func (o *RecyclingRun) SetSourcePostUuidNil(b bool)`

 SetSourcePostUuidNil sets the value for SourcePostUuid to be an explicit nil

### UnsetSourcePostUuid
`func (o *RecyclingRun) UnsetSourcePostUuid()`

UnsetSourcePostUuid ensures that no value is present for SourcePostUuid, not even an explicit nil
### GetCreatedPostUuid

`func (o *RecyclingRun) GetCreatedPostUuid() string`

GetCreatedPostUuid returns the CreatedPostUuid field if non-nil, zero value otherwise.

### GetCreatedPostUuidOk

`func (o *RecyclingRun) GetCreatedPostUuidOk() (*string, bool)`

GetCreatedPostUuidOk returns a tuple with the CreatedPostUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedPostUuid

`func (o *RecyclingRun) SetCreatedPostUuid(v string)`

SetCreatedPostUuid sets CreatedPostUuid field to given value.


### SetCreatedPostUuidNil

`func (o *RecyclingRun) SetCreatedPostUuidNil(b bool)`

 SetCreatedPostUuidNil sets the value for CreatedPostUuid to be an explicit nil

### UnsetCreatedPostUuid
`func (o *RecyclingRun) UnsetCreatedPostUuid()`

UnsetCreatedPostUuid ensures that no value is present for CreatedPostUuid, not even an explicit nil
### GetCreatedAt

`func (o *RecyclingRun) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RecyclingRun) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RecyclingRun) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### SetCreatedAtNil

`func (o *RecyclingRun) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *RecyclingRun) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


