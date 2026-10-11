# AccountSchedule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | **int32** | ID of one of the post&#39;s accounts. Entries for accounts the post does not carry are ignored. | 
**Date** | **string** |  | 
**Time** | **string** | H:i, read in the request &#x60;timezone&#x60;. Must not be in the past. | 

## Methods

### NewAccountSchedule

`func NewAccountSchedule(accountId int32, date string, time string, ) *AccountSchedule`

NewAccountSchedule instantiates a new AccountSchedule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountScheduleWithDefaults

`func NewAccountScheduleWithDefaults() *AccountSchedule`

NewAccountScheduleWithDefaults instantiates a new AccountSchedule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *AccountSchedule) GetAccountId() int32`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *AccountSchedule) GetAccountIdOk() (*int32, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *AccountSchedule) SetAccountId(v int32)`

SetAccountId sets AccountId field to given value.


### GetDate

`func (o *AccountSchedule) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *AccountSchedule) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *AccountSchedule) SetDate(v string)`

SetDate sets Date field to given value.


### GetTime

`func (o *AccountSchedule) GetTime() string`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *AccountSchedule) GetTimeOk() (*string, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *AccountSchedule) SetTime(v string)`

SetTime sets Time field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


