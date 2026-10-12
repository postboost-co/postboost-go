# AIUsageText

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Used** | **NullableInt32** | &#x60;null&#x60; when the workspace has no text credit limit. | 
**Limit** | **NullableInt32** |  | 
**Remaining** | **NullableInt32** |  | 
**CycleStartedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewAIUsageText

`func NewAIUsageText(used NullableInt32, limit NullableInt32, remaining NullableInt32, ) *AIUsageText`

NewAIUsageText instantiates a new AIUsageText object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAIUsageTextWithDefaults

`func NewAIUsageTextWithDefaults() *AIUsageText`

NewAIUsageTextWithDefaults instantiates a new AIUsageText object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsed

`func (o *AIUsageText) GetUsed() int32`

GetUsed returns the Used field if non-nil, zero value otherwise.

### GetUsedOk

`func (o *AIUsageText) GetUsedOk() (*int32, bool)`

GetUsedOk returns a tuple with the Used field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsed

`func (o *AIUsageText) SetUsed(v int32)`

SetUsed sets Used field to given value.


### SetUsedNil

`func (o *AIUsageText) SetUsedNil(b bool)`

 SetUsedNil sets the value for Used to be an explicit nil

### UnsetUsed
`func (o *AIUsageText) UnsetUsed()`

UnsetUsed ensures that no value is present for Used, not even an explicit nil
### GetLimit

`func (o *AIUsageText) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *AIUsageText) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *AIUsageText) SetLimit(v int32)`

SetLimit sets Limit field to given value.


### SetLimitNil

`func (o *AIUsageText) SetLimitNil(b bool)`

 SetLimitNil sets the value for Limit to be an explicit nil

### UnsetLimit
`func (o *AIUsageText) UnsetLimit()`

UnsetLimit ensures that no value is present for Limit, not even an explicit nil
### GetRemaining

`func (o *AIUsageText) GetRemaining() int32`

GetRemaining returns the Remaining field if non-nil, zero value otherwise.

### GetRemainingOk

`func (o *AIUsageText) GetRemainingOk() (*int32, bool)`

GetRemainingOk returns a tuple with the Remaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemaining

`func (o *AIUsageText) SetRemaining(v int32)`

SetRemaining sets Remaining field to given value.


### SetRemainingNil

`func (o *AIUsageText) SetRemainingNil(b bool)`

 SetRemainingNil sets the value for Remaining to be an explicit nil

### UnsetRemaining
`func (o *AIUsageText) UnsetRemaining()`

UnsetRemaining ensures that no value is present for Remaining, not even an explicit nil
### GetCycleStartedAt

`func (o *AIUsageText) GetCycleStartedAt() time.Time`

GetCycleStartedAt returns the CycleStartedAt field if non-nil, zero value otherwise.

### GetCycleStartedAtOk

`func (o *AIUsageText) GetCycleStartedAtOk() (*time.Time, bool)`

GetCycleStartedAtOk returns a tuple with the CycleStartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycleStartedAt

`func (o *AIUsageText) SetCycleStartedAt(v time.Time)`

SetCycleStartedAt sets CycleStartedAt field to given value.

### HasCycleStartedAt

`func (o *AIUsageText) HasCycleStartedAt() bool`

HasCycleStartedAt returns a boolean if a field has been set.

### SetCycleStartedAtNil

`func (o *AIUsageText) SetCycleStartedAtNil(b bool)`

 SetCycleStartedAtNil sets the value for CycleStartedAt to be an explicit nil

### UnsetCycleStartedAt
`func (o *AIUsageText) UnsetCycleStartedAt()`

UnsetCycleStartedAt ensures that no value is present for CycleStartedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


