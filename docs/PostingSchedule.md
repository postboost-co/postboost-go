# PostingSchedule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | **int32** | The account asked for; 0 for the workspace schedule. | 
**SourceAccountId** | **int32** | Whose schedule applies; 0 when the workspace schedule applies. | 
**Inherited** | **bool** | True when the account follows the workspace schedule. | 
**Timezone** | **NullableString** |  | 
**AutoTune** | **bool** | Adjust times automatically from engagement data. | 
**Times** | [**[]PostingScheduleDay**](PostingScheduleDay.md) |  | 

## Methods

### NewPostingSchedule

`func NewPostingSchedule(accountId int32, sourceAccountId int32, inherited bool, timezone NullableString, autoTune bool, times []PostingScheduleDay, ) *PostingSchedule`

NewPostingSchedule instantiates a new PostingSchedule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostingScheduleWithDefaults

`func NewPostingScheduleWithDefaults() *PostingSchedule`

NewPostingScheduleWithDefaults instantiates a new PostingSchedule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *PostingSchedule) GetAccountId() int32`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *PostingSchedule) GetAccountIdOk() (*int32, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *PostingSchedule) SetAccountId(v int32)`

SetAccountId sets AccountId field to given value.


### GetSourceAccountId

`func (o *PostingSchedule) GetSourceAccountId() int32`

GetSourceAccountId returns the SourceAccountId field if non-nil, zero value otherwise.

### GetSourceAccountIdOk

`func (o *PostingSchedule) GetSourceAccountIdOk() (*int32, bool)`

GetSourceAccountIdOk returns a tuple with the SourceAccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceAccountId

`func (o *PostingSchedule) SetSourceAccountId(v int32)`

SetSourceAccountId sets SourceAccountId field to given value.


### GetInherited

`func (o *PostingSchedule) GetInherited() bool`

GetInherited returns the Inherited field if non-nil, zero value otherwise.

### GetInheritedOk

`func (o *PostingSchedule) GetInheritedOk() (*bool, bool)`

GetInheritedOk returns a tuple with the Inherited field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInherited

`func (o *PostingSchedule) SetInherited(v bool)`

SetInherited sets Inherited field to given value.


### GetTimezone

`func (o *PostingSchedule) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *PostingSchedule) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *PostingSchedule) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.


### SetTimezoneNil

`func (o *PostingSchedule) SetTimezoneNil(b bool)`

 SetTimezoneNil sets the value for Timezone to be an explicit nil

### UnsetTimezone
`func (o *PostingSchedule) UnsetTimezone()`

UnsetTimezone ensures that no value is present for Timezone, not even an explicit nil
### GetAutoTune

`func (o *PostingSchedule) GetAutoTune() bool`

GetAutoTune returns the AutoTune field if non-nil, zero value otherwise.

### GetAutoTuneOk

`func (o *PostingSchedule) GetAutoTuneOk() (*bool, bool)`

GetAutoTuneOk returns a tuple with the AutoTune field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoTune

`func (o *PostingSchedule) SetAutoTune(v bool)`

SetAutoTune sets AutoTune field to given value.


### GetTimes

`func (o *PostingSchedule) GetTimes() []PostingScheduleDay`

GetTimes returns the Times field if non-nil, zero value otherwise.

### GetTimesOk

`func (o *PostingSchedule) GetTimesOk() (*[]PostingScheduleDay, bool)`

GetTimesOk returns a tuple with the Times field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimes

`func (o *PostingSchedule) SetTimes(v []PostingScheduleDay)`

SetTimes sets Times field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


