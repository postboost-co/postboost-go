# RecommendedPostingTimes

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HasData** | **bool** |  | 
**Timezone** | Pointer to **string** |  | [optional] 
**SlotsPerDay** | **int32** |  | 
**Samples** | **int32** | Number of past posts the recommendation is based on. | 
**Times** | **[]map[string]interface{}** | Recommended times per weekday. | 

## Methods

### NewRecommendedPostingTimes

`func NewRecommendedPostingTimes(hasData bool, slotsPerDay int32, samples int32, times []map[string]interface{}, ) *RecommendedPostingTimes`

NewRecommendedPostingTimes instantiates a new RecommendedPostingTimes object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecommendedPostingTimesWithDefaults

`func NewRecommendedPostingTimesWithDefaults() *RecommendedPostingTimes`

NewRecommendedPostingTimesWithDefaults instantiates a new RecommendedPostingTimes object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHasData

`func (o *RecommendedPostingTimes) GetHasData() bool`

GetHasData returns the HasData field if non-nil, zero value otherwise.

### GetHasDataOk

`func (o *RecommendedPostingTimes) GetHasDataOk() (*bool, bool)`

GetHasDataOk returns a tuple with the HasData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasData

`func (o *RecommendedPostingTimes) SetHasData(v bool)`

SetHasData sets HasData field to given value.


### GetTimezone

`func (o *RecommendedPostingTimes) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *RecommendedPostingTimes) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *RecommendedPostingTimes) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *RecommendedPostingTimes) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.

### GetSlotsPerDay

`func (o *RecommendedPostingTimes) GetSlotsPerDay() int32`

GetSlotsPerDay returns the SlotsPerDay field if non-nil, zero value otherwise.

### GetSlotsPerDayOk

`func (o *RecommendedPostingTimes) GetSlotsPerDayOk() (*int32, bool)`

GetSlotsPerDayOk returns a tuple with the SlotsPerDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlotsPerDay

`func (o *RecommendedPostingTimes) SetSlotsPerDay(v int32)`

SetSlotsPerDay sets SlotsPerDay field to given value.


### GetSamples

`func (o *RecommendedPostingTimes) GetSamples() int32`

GetSamples returns the Samples field if non-nil, zero value otherwise.

### GetSamplesOk

`func (o *RecommendedPostingTimes) GetSamplesOk() (*int32, bool)`

GetSamplesOk returns a tuple with the Samples field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSamples

`func (o *RecommendedPostingTimes) SetSamples(v int32)`

SetSamples sets Samples field to given value.


### GetTimes

`func (o *RecommendedPostingTimes) GetTimes() []map[string]interface{}`

GetTimes returns the Times field if non-nil, zero value otherwise.

### GetTimesOk

`func (o *RecommendedPostingTimes) GetTimesOk() (*[]map[string]interface{}, bool)`

GetTimesOk returns a tuple with the Times field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimes

`func (o *RecommendedPostingTimes) SetTimes(v []map[string]interface{})`

SetTimes sets Times field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


