# PostInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Versions** | [**[]PostVersion**](PostVersion.md) | At least one version with &#x60;is_original: true&#x60; is required. | 
**Accounts** | Pointer to **[]int32** | Account IDs to publish to. | [optional] 
**Tags** | Pointer to **[]int32** | Tag IDs to attach. | [optional] 
**Date** | Pointer to **string** |  | [optional] 
**Time** | Pointer to **string** |  | [optional] 
**Timezone** | Pointer to **string** |  | [optional] 
**Schedule** | Pointer to **bool** | Schedule the post for the given date/time. | [optional] 
**ScheduleNow** | Pointer to **bool** | Publish immediately. | [optional] 
**Queue** | Pointer to **bool** | Add to the smart publishing queue. | [optional] 

## Methods

### NewPostInput

`func NewPostInput(versions []PostVersion, ) *PostInput`

NewPostInput instantiates a new PostInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostInputWithDefaults

`func NewPostInputWithDefaults() *PostInput`

NewPostInputWithDefaults instantiates a new PostInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVersions

`func (o *PostInput) GetVersions() []PostVersion`

GetVersions returns the Versions field if non-nil, zero value otherwise.

### GetVersionsOk

`func (o *PostInput) GetVersionsOk() (*[]PostVersion, bool)`

GetVersionsOk returns a tuple with the Versions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersions

`func (o *PostInput) SetVersions(v []PostVersion)`

SetVersions sets Versions field to given value.


### GetAccounts

`func (o *PostInput) GetAccounts() []int32`

GetAccounts returns the Accounts field if non-nil, zero value otherwise.

### GetAccountsOk

`func (o *PostInput) GetAccountsOk() (*[]int32, bool)`

GetAccountsOk returns a tuple with the Accounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccounts

`func (o *PostInput) SetAccounts(v []int32)`

SetAccounts sets Accounts field to given value.

### HasAccounts

`func (o *PostInput) HasAccounts() bool`

HasAccounts returns a boolean if a field has been set.

### GetTags

`func (o *PostInput) GetTags() []int32`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *PostInput) GetTagsOk() (*[]int32, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *PostInput) SetTags(v []int32)`

SetTags sets Tags field to given value.

### HasTags

`func (o *PostInput) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetDate

`func (o *PostInput) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *PostInput) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *PostInput) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *PostInput) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetTime

`func (o *PostInput) GetTime() string`

GetTime returns the Time field if non-nil, zero value otherwise.

### GetTimeOk

`func (o *PostInput) GetTimeOk() (*string, bool)`

GetTimeOk returns a tuple with the Time field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTime

`func (o *PostInput) SetTime(v string)`

SetTime sets Time field to given value.

### HasTime

`func (o *PostInput) HasTime() bool`

HasTime returns a boolean if a field has been set.

### GetTimezone

`func (o *PostInput) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *PostInput) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *PostInput) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *PostInput) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetSchedule

`func (o *PostInput) GetSchedule() bool`

GetSchedule returns the Schedule field if non-nil, zero value otherwise.

### GetScheduleOk

`func (o *PostInput) GetScheduleOk() (*bool, bool)`

GetScheduleOk returns a tuple with the Schedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedule

`func (o *PostInput) SetSchedule(v bool)`

SetSchedule sets Schedule field to given value.

### HasSchedule

`func (o *PostInput) HasSchedule() bool`

HasSchedule returns a boolean if a field has been set.

### GetScheduleNow

`func (o *PostInput) GetScheduleNow() bool`

GetScheduleNow returns the ScheduleNow field if non-nil, zero value otherwise.

### GetScheduleNowOk

`func (o *PostInput) GetScheduleNowOk() (*bool, bool)`

GetScheduleNowOk returns a tuple with the ScheduleNow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduleNow

`func (o *PostInput) SetScheduleNow(v bool)`

SetScheduleNow sets ScheduleNow field to given value.

### HasScheduleNow

`func (o *PostInput) HasScheduleNow() bool`

HasScheduleNow returns a boolean if a field has been set.

### GetQueue

`func (o *PostInput) GetQueue() bool`

GetQueue returns the Queue field if non-nil, zero value otherwise.

### GetQueueOk

`func (o *PostInput) GetQueueOk() (*bool, bool)`

GetQueueOk returns a tuple with the Queue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQueue

`func (o *PostInput) SetQueue(v bool)`

SetQueue sets Queue field to given value.

### HasQueue

`func (o *PostInput) HasQueue() bool`

HasQueue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


