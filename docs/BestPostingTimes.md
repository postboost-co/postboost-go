# BestPostingTimes

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Timezone** | **string** |  | 
**Times** | [**[]BestPostingTimesTimesInner**](BestPostingTimesTimesInner.md) | The next recommended time per account. Accounts without enough history are left out. | 

## Methods

### NewBestPostingTimes

`func NewBestPostingTimes(timezone string, times []BestPostingTimesTimesInner, ) *BestPostingTimes`

NewBestPostingTimes instantiates a new BestPostingTimes object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBestPostingTimesWithDefaults

`func NewBestPostingTimesWithDefaults() *BestPostingTimes`

NewBestPostingTimesWithDefaults instantiates a new BestPostingTimes object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTimezone

`func (o *BestPostingTimes) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *BestPostingTimes) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *BestPostingTimes) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.


### GetTimes

`func (o *BestPostingTimes) GetTimes() []BestPostingTimesTimesInner`

GetTimes returns the Times field if non-nil, zero value otherwise.

### GetTimesOk

`func (o *BestPostingTimes) GetTimesOk() (*[]BestPostingTimesTimesInner, bool)`

GetTimesOk returns a tuple with the Times field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimes

`func (o *BestPostingTimes) SetTimes(v []BestPostingTimesTimesInner)`

SetTimes sets Times field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


