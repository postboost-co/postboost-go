# FreeToolGetVideoSpecsResponseSpecsInnerLimits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MinSeconds** | Pointer to **NullableFloat32** | Shortest length. Null when the source states no figure. | [optional] 
**MaxSeconds** | Pointer to **NullableFloat32** | Longest length. Null when the source states no figure. | [optional] 
**WarnOverSeconds** | Pointer to **NullableFloat32** | Longer videos need a check (account type, reach), see &#x60;length&#x60;. Null when the source states no figure. | [optional] 
**MinRatio** | Pointer to **NullableFloat32** | Narrowest width / height. Null when the source states no figure. | [optional] 
**MaxRatio** | Pointer to **NullableFloat32** | Widest width / height. Null when the source states no figure. | [optional] 
**RecommendedRatio** | Pointer to **NullableString** | Recommended ratio, e.g. &#x60;9:16&#x60;. | [optional] 
**MaxMb** | Pointer to **NullableFloat32** | Largest file in MB. Null when the source states no figure. | [optional] 

## Methods

### NewFreeToolGetVideoSpecsResponseSpecsInnerLimits

`func NewFreeToolGetVideoSpecsResponseSpecsInnerLimits() *FreeToolGetVideoSpecsResponseSpecsInnerLimits`

NewFreeToolGetVideoSpecsResponseSpecsInnerLimits instantiates a new FreeToolGetVideoSpecsResponseSpecsInnerLimits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGetVideoSpecsResponseSpecsInnerLimitsWithDefaults

`func NewFreeToolGetVideoSpecsResponseSpecsInnerLimitsWithDefaults() *FreeToolGetVideoSpecsResponseSpecsInnerLimits`

NewFreeToolGetVideoSpecsResponseSpecsInnerLimitsWithDefaults instantiates a new FreeToolGetVideoSpecsResponseSpecsInnerLimits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMinSeconds

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) GetMinSeconds() float32`

GetMinSeconds returns the MinSeconds field if non-nil, zero value otherwise.

### GetMinSecondsOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) GetMinSecondsOk() (*float32, bool)`

GetMinSecondsOk returns a tuple with the MinSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinSeconds

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) SetMinSeconds(v float32)`

SetMinSeconds sets MinSeconds field to given value.

### HasMinSeconds

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) HasMinSeconds() bool`

HasMinSeconds returns a boolean if a field has been set.

### SetMinSecondsNil

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) SetMinSecondsNil(b bool)`

 SetMinSecondsNil sets the value for MinSeconds to be an explicit nil

### UnsetMinSeconds
`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) UnsetMinSeconds()`

UnsetMinSeconds ensures that no value is present for MinSeconds, not even an explicit nil
### GetMaxSeconds

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) GetMaxSeconds() float32`

GetMaxSeconds returns the MaxSeconds field if non-nil, zero value otherwise.

### GetMaxSecondsOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) GetMaxSecondsOk() (*float32, bool)`

GetMaxSecondsOk returns a tuple with the MaxSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxSeconds

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) SetMaxSeconds(v float32)`

SetMaxSeconds sets MaxSeconds field to given value.

### HasMaxSeconds

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) HasMaxSeconds() bool`

HasMaxSeconds returns a boolean if a field has been set.

### SetMaxSecondsNil

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) SetMaxSecondsNil(b bool)`

 SetMaxSecondsNil sets the value for MaxSeconds to be an explicit nil

### UnsetMaxSeconds
`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) UnsetMaxSeconds()`

UnsetMaxSeconds ensures that no value is present for MaxSeconds, not even an explicit nil
### GetWarnOverSeconds

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) GetWarnOverSeconds() float32`

GetWarnOverSeconds returns the WarnOverSeconds field if non-nil, zero value otherwise.

### GetWarnOverSecondsOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) GetWarnOverSecondsOk() (*float32, bool)`

GetWarnOverSecondsOk returns a tuple with the WarnOverSeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnOverSeconds

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) SetWarnOverSeconds(v float32)`

SetWarnOverSeconds sets WarnOverSeconds field to given value.

### HasWarnOverSeconds

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) HasWarnOverSeconds() bool`

HasWarnOverSeconds returns a boolean if a field has been set.

### SetWarnOverSecondsNil

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) SetWarnOverSecondsNil(b bool)`

 SetWarnOverSecondsNil sets the value for WarnOverSeconds to be an explicit nil

### UnsetWarnOverSeconds
`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) UnsetWarnOverSeconds()`

UnsetWarnOverSeconds ensures that no value is present for WarnOverSeconds, not even an explicit nil
### GetMinRatio

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) GetMinRatio() float32`

GetMinRatio returns the MinRatio field if non-nil, zero value otherwise.

### GetMinRatioOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) GetMinRatioOk() (*float32, bool)`

GetMinRatioOk returns a tuple with the MinRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinRatio

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) SetMinRatio(v float32)`

SetMinRatio sets MinRatio field to given value.

### HasMinRatio

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) HasMinRatio() bool`

HasMinRatio returns a boolean if a field has been set.

### SetMinRatioNil

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) SetMinRatioNil(b bool)`

 SetMinRatioNil sets the value for MinRatio to be an explicit nil

### UnsetMinRatio
`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) UnsetMinRatio()`

UnsetMinRatio ensures that no value is present for MinRatio, not even an explicit nil
### GetMaxRatio

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) GetMaxRatio() float32`

GetMaxRatio returns the MaxRatio field if non-nil, zero value otherwise.

### GetMaxRatioOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) GetMaxRatioOk() (*float32, bool)`

GetMaxRatioOk returns a tuple with the MaxRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRatio

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) SetMaxRatio(v float32)`

SetMaxRatio sets MaxRatio field to given value.

### HasMaxRatio

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) HasMaxRatio() bool`

HasMaxRatio returns a boolean if a field has been set.

### SetMaxRatioNil

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) SetMaxRatioNil(b bool)`

 SetMaxRatioNil sets the value for MaxRatio to be an explicit nil

### UnsetMaxRatio
`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) UnsetMaxRatio()`

UnsetMaxRatio ensures that no value is present for MaxRatio, not even an explicit nil
### GetRecommendedRatio

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) GetRecommendedRatio() string`

GetRecommendedRatio returns the RecommendedRatio field if non-nil, zero value otherwise.

### GetRecommendedRatioOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) GetRecommendedRatioOk() (*string, bool)`

GetRecommendedRatioOk returns a tuple with the RecommendedRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendedRatio

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) SetRecommendedRatio(v string)`

SetRecommendedRatio sets RecommendedRatio field to given value.

### HasRecommendedRatio

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) HasRecommendedRatio() bool`

HasRecommendedRatio returns a boolean if a field has been set.

### SetRecommendedRatioNil

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) SetRecommendedRatioNil(b bool)`

 SetRecommendedRatioNil sets the value for RecommendedRatio to be an explicit nil

### UnsetRecommendedRatio
`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) UnsetRecommendedRatio()`

UnsetRecommendedRatio ensures that no value is present for RecommendedRatio, not even an explicit nil
### GetMaxMb

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) GetMaxMb() float32`

GetMaxMb returns the MaxMb field if non-nil, zero value otherwise.

### GetMaxMbOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) GetMaxMbOk() (*float32, bool)`

GetMaxMbOk returns a tuple with the MaxMb field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxMb

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) SetMaxMb(v float32)`

SetMaxMb sets MaxMb field to given value.

### HasMaxMb

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) HasMaxMb() bool`

HasMaxMb returns a boolean if a field has been set.

### SetMaxMbNil

`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) SetMaxMbNil(b bool)`

 SetMaxMbNil sets the value for MaxMb to be an explicit nil

### UnsetMaxMb
`func (o *FreeToolGetVideoSpecsResponseSpecsInnerLimits) UnsetMaxMb()`

UnsetMaxMb ensures that no value is present for MaxMb, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


