# SchedulePostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PostNow** | **bool** |  | 
**Date** | Pointer to **string** | New date for the post (Y-m-d). Use together with &#x60;time&#x60;. | [optional] 
**Time** | Pointer to **string** | New time for the post (H:i). | [optional] 
**Timezone** | Pointer to **string** | Timezone &#x60;date&#x60;, &#x60;time&#x60; and &#x60;accounts_schedule&#x60; are read in. Defaults to the workspace timezone. | [optional] 
**AccountsSchedule** | Pointer to [**[]AccountSchedule**](AccountSchedule.md) | Per-account departure times. When omitted, accounts keep their offsets from the post time. | [optional] 

## Methods

### NewSchedulePostRequest

`func NewSchedulePostRequest(postNow bool, ) *SchedulePostRequest`

NewSchedulePostRequest instantiates a new SchedulePostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSchedulePostRequestWithDefaults

`func NewSchedulePostRequestWithDefaults() *SchedulePostRequest`

NewSchedulePostRequestWithDefaults instantiates a new SchedulePostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPostNow

`func (o *SchedulePostRequest) GetPostNow() bool`

GetPostNow returns the PostNow field if non-nil, zero value otherwise.

### GetPostNowOk

`func (o *SchedulePostRequest) GetPostNowOk() (*bool, bool)`

GetPostNowOk returns a tuple with the PostNow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostNow

`func (o *SchedulePostRequest) SetPostNow(v bool)`

SetPostNow sets PostNow field to given value.


### GetDate

`func (o *SchedulePostRequest) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *SchedulePostRequest) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *SchedulePostRequest) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *SchedulePostRequest) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetTime

`func (o *SchedulePostRequest) GetTime() string`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *SchedulePostRequest) GetTimeOk() (*string, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *SchedulePostRequest) SetTime(v string)`

SetTime sets Time field to given value.

### HasTime

`func (o *SchedulePostRequest) HasTime() bool`

HasTime returns a boolean if a field has been set.

### GetTimezone

`func (o *SchedulePostRequest) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *SchedulePostRequest) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *SchedulePostRequest) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *SchedulePostRequest) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetAccountsSchedule

`func (o *SchedulePostRequest) GetAccountsSchedule() []AccountSchedule`

GetAccountsSchedule returns the AccountsSchedule field if non-nil, zero value otherwise.

### GetAccountsScheduleOk

`func (o *SchedulePostRequest) GetAccountsScheduleOk() (*[]AccountSchedule, bool)`

GetAccountsScheduleOk returns a tuple with the AccountsSchedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountsSchedule

`func (o *SchedulePostRequest) SetAccountsSchedule(v []AccountSchedule)`

SetAccountsSchedule sets AccountsSchedule field to given value.

### HasAccountsSchedule

`func (o *SchedulePostRequest) HasAccountsSchedule() bool`

HasAccountsSchedule returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


