# PostingScheduleInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | **int32** | 0 for the workspace schedule, or an account &#x60;id&#x60;. | 
**Timezone** | **string** |  | 
**AutoTune** | Pointer to **bool** |  | [optional] 
**Times** | [**[]PostingScheduleDay**](PostingScheduleDay.md) |  | 

## Methods

### NewPostingScheduleInput

`func NewPostingScheduleInput(accountId int32, timezone string, times []PostingScheduleDay, ) *PostingScheduleInput`

NewPostingScheduleInput instantiates a new PostingScheduleInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostingScheduleInputWithDefaults

`func NewPostingScheduleInputWithDefaults() *PostingScheduleInput`

NewPostingScheduleInputWithDefaults instantiates a new PostingScheduleInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *PostingScheduleInput) GetAccountId() int32`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *PostingScheduleInput) GetAccountIdOk() (*int32, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *PostingScheduleInput) SetAccountId(v int32)`

SetAccountId sets AccountId field to given value.


### GetTimezone

`func (o *PostingScheduleInput) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *PostingScheduleInput) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *PostingScheduleInput) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.


### GetAutoTune

`func (o *PostingScheduleInput) GetAutoTune() bool`

GetAutoTune returns the AutoTune field if non-nil, zero value otherwise.

### GetAutoTuneOk

`func (o *PostingScheduleInput) GetAutoTuneOk() (*bool, bool)`

GetAutoTuneOk returns a tuple with the AutoTune field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoTune

`func (o *PostingScheduleInput) SetAutoTune(v bool)`

SetAutoTune sets AutoTune field to given value.

### HasAutoTune

`func (o *PostingScheduleInput) HasAutoTune() bool`

HasAutoTune returns a boolean if a field has been set.

### GetTimes

`func (o *PostingScheduleInput) GetTimes() []PostingScheduleDay`

GetTimes returns the Times field if non-nil, zero value otherwise.

### GetTimesOk

`func (o *PostingScheduleInput) GetTimesOk() (*[]PostingScheduleDay, bool)`

GetTimesOk returns a tuple with the Times field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimes

`func (o *PostingScheduleInput) SetTimes(v []PostingScheduleDay)`

SetTimes sets Times field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


