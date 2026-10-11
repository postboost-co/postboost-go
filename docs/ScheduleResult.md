# ScheduleResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**ScheduledAt** | Pointer to **time.Time** |  | [optional] 
**NeedsApproval** | Pointer to **bool** | True when the post now waits for approval instead of being scheduled (not returned by approve). | [optional] 

## Methods

### NewScheduleResult

`func NewScheduleResult(success bool, ) *ScheduleResult`

NewScheduleResult instantiates a new ScheduleResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewScheduleResultWithDefaults

`func NewScheduleResultWithDefaults() *ScheduleResult`

NewScheduleResultWithDefaults instantiates a new ScheduleResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *ScheduleResult) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ScheduleResult) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ScheduleResult) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetScheduledAt

`func (o *ScheduleResult) GetScheduledAt() time.Time`

GetScheduledAt returns the ScheduledAt field if non-nil, zero value otherwise.

### GetScheduledAtOk

`func (o *ScheduleResult) GetScheduledAtOk() (*time.Time, bool)`

GetScheduledAtOk returns a tuple with the ScheduledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledAt

`func (o *ScheduleResult) SetScheduledAt(v time.Time)`

SetScheduledAt sets ScheduledAt field to given value.

### HasScheduledAt

`func (o *ScheduleResult) HasScheduledAt() bool`

HasScheduledAt returns a boolean if a field has been set.

### GetNeedsApproval

`func (o *ScheduleResult) GetNeedsApproval() bool`

GetNeedsApproval returns the NeedsApproval field if non-nil, zero value otherwise.

### GetNeedsApprovalOk

`func (o *ScheduleResult) GetNeedsApprovalOk() (*bool, bool)`

GetNeedsApprovalOk returns a tuple with the NeedsApproval field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeedsApproval

`func (o *ScheduleResult) SetNeedsApproval(v bool)`

SetNeedsApproval sets NeedsApproval field to given value.

### HasNeedsApproval

`func (o *ScheduleResult) HasNeedsApproval() bool`

HasNeedsApproval returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


