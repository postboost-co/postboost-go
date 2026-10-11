# PostingTimes

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HasData** | **bool** |  | 
**Timezone** | **string** |  | 
**OffsetHours** | **int32** |  | 
**Accounts** | **int32** | Accounts that contributed scores. | 
**Samples** | **int32** |  | 
**Days** | [**[]PostingTimesDaysInner**](PostingTimesDaysInner.md) | One entry per weekday (&#x60;day&#x60; 0 &#x3D; Sunday). | 
**DayIntervals** | [**[][]PostingTimesDayIntervalsInnerInner**]([]PostingTimesDayIntervalsInnerInner.md) | Per weekday, 2-hour intervals. | 
**Best** | [**[]PostingTimesBestInner**](PostingTimesBestInner.md) | Up to three recommended slots, at most one per weekday. | 

## Methods

### NewPostingTimes

`func NewPostingTimes(hasData bool, timezone string, offsetHours int32, accounts int32, samples int32, days []PostingTimesDaysInner, dayIntervals [][]PostingTimesDayIntervalsInnerInner, best []PostingTimesBestInner, ) *PostingTimes`

NewPostingTimes instantiates a new PostingTimes object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostingTimesWithDefaults

`func NewPostingTimesWithDefaults() *PostingTimes`

NewPostingTimesWithDefaults instantiates a new PostingTimes object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHasData

`func (o *PostingTimes) GetHasData() bool`

GetHasData returns the HasData field if non-nil, zero value otherwise.

### GetHasDataOk

`func (o *PostingTimes) GetHasDataOk() (*bool, bool)`

GetHasDataOk returns a tuple with the HasData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasData

`func (o *PostingTimes) SetHasData(v bool)`

SetHasData sets HasData field to given value.


### GetTimezone

`func (o *PostingTimes) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *PostingTimes) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *PostingTimes) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.


### GetOffsetHours

`func (o *PostingTimes) GetOffsetHours() int32`

GetOffsetHours returns the OffsetHours field if non-nil, zero value otherwise.

### GetOffsetHoursOk

`func (o *PostingTimes) GetOffsetHoursOk() (*int32, bool)`

GetOffsetHoursOk returns a tuple with the OffsetHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffsetHours

`func (o *PostingTimes) SetOffsetHours(v int32)`

SetOffsetHours sets OffsetHours field to given value.


### GetAccounts

`func (o *PostingTimes) GetAccounts() int32`

GetAccounts returns the Accounts field if non-nil, zero value otherwise.

### GetAccountsOk

`func (o *PostingTimes) GetAccountsOk() (*int32, bool)`

GetAccountsOk returns a tuple with the Accounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccounts

`func (o *PostingTimes) SetAccounts(v int32)`

SetAccounts sets Accounts field to given value.


### GetSamples

`func (o *PostingTimes) GetSamples() int32`

GetSamples returns the Samples field if non-nil, zero value otherwise.

### GetSamplesOk

`func (o *PostingTimes) GetSamplesOk() (*int32, bool)`

GetSamplesOk returns a tuple with the Samples field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSamples

`func (o *PostingTimes) SetSamples(v int32)`

SetSamples sets Samples field to given value.


### GetDays

`func (o *PostingTimes) GetDays() []PostingTimesDaysInner`

GetDays returns the Days field if non-nil, zero value otherwise.

### GetDaysOk

`func (o *PostingTimes) GetDaysOk() (*[]PostingTimesDaysInner, bool)`

GetDaysOk returns a tuple with the Days field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDays

`func (o *PostingTimes) SetDays(v []PostingTimesDaysInner)`

SetDays sets Days field to given value.


### GetDayIntervals

`func (o *PostingTimes) GetDayIntervals() [][]PostingTimesDayIntervalsInnerInner`

GetDayIntervals returns the DayIntervals field if non-nil, zero value otherwise.

### GetDayIntervalsOk

`func (o *PostingTimes) GetDayIntervalsOk() (*[][]PostingTimesDayIntervalsInnerInner, bool)`

GetDayIntervalsOk returns a tuple with the DayIntervals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDayIntervals

`func (o *PostingTimes) SetDayIntervals(v [][]PostingTimesDayIntervalsInnerInner)`

SetDayIntervals sets DayIntervals field to given value.


### GetBest

`func (o *PostingTimes) GetBest() []PostingTimesBestInner`

GetBest returns the Best field if non-nil, zero value otherwise.

### GetBestOk

`func (o *PostingTimes) GetBestOk() (*[]PostingTimesBestInner, bool)`

GetBestOk returns a tuple with the Best field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBest

`func (o *PostingTimes) SetBest(v []PostingTimesBestInner)`

SetBest sets Best field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


