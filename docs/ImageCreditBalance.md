# ImageCreditBalance

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Enabled** | **bool** | &#x60;false&#x60; when images are charged to text credits instead (the pool is switched off). | 
**Used** | **int32** |  | 
**Limit** | **NullableInt32** | Image credits this month; &#x60;null&#x60; &#x3D; no limit. | 
**Remaining** | **NullableInt32** |  | 
**PeriodStart** | **time.Time** |  | 
**PeriodEnd** | **time.Time** |  | 

## Methods

### NewImageCreditBalance

`func NewImageCreditBalance(enabled bool, used int32, limit NullableInt32, remaining NullableInt32, periodStart time.Time, periodEnd time.Time, ) *ImageCreditBalance`

NewImageCreditBalance instantiates a new ImageCreditBalance object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageCreditBalanceWithDefaults

`func NewImageCreditBalanceWithDefaults() *ImageCreditBalance`

NewImageCreditBalanceWithDefaults instantiates a new ImageCreditBalance object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEnabled

`func (o *ImageCreditBalance) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *ImageCreditBalance) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *ImageCreditBalance) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetUsed

`func (o *ImageCreditBalance) GetUsed() int32`

GetUsed returns the Used field if non-nil, zero value otherwise.

### GetUsedOk

`func (o *ImageCreditBalance) GetUsedOk() (*int32, bool)`

GetUsedOk returns a tuple with the Used field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsed

`func (o *ImageCreditBalance) SetUsed(v int32)`

SetUsed sets Used field to given value.


### GetLimit

`func (o *ImageCreditBalance) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *ImageCreditBalance) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *ImageCreditBalance) SetLimit(v int32)`

SetLimit sets Limit field to given value.


### SetLimitNil

`func (o *ImageCreditBalance) SetLimitNil(b bool)`

 SetLimitNil sets the value for Limit to be an explicit nil

### UnsetLimit
`func (o *ImageCreditBalance) UnsetLimit()`

UnsetLimit ensures that no value is present for Limit, not even an explicit nil
### GetRemaining

`func (o *ImageCreditBalance) GetRemaining() int32`

GetRemaining returns the Remaining field if non-nil, zero value otherwise.

### GetRemainingOk

`func (o *ImageCreditBalance) GetRemainingOk() (*int32, bool)`

GetRemainingOk returns a tuple with the Remaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemaining

`func (o *ImageCreditBalance) SetRemaining(v int32)`

SetRemaining sets Remaining field to given value.


### SetRemainingNil

`func (o *ImageCreditBalance) SetRemainingNil(b bool)`

 SetRemainingNil sets the value for Remaining to be an explicit nil

### UnsetRemaining
`func (o *ImageCreditBalance) UnsetRemaining()`

UnsetRemaining ensures that no value is present for Remaining, not even an explicit nil
### GetPeriodStart

`func (o *ImageCreditBalance) GetPeriodStart() time.Time`

GetPeriodStart returns the PeriodStart field if non-nil, zero value otherwise.

### GetPeriodStartOk

`func (o *ImageCreditBalance) GetPeriodStartOk() (*time.Time, bool)`

GetPeriodStartOk returns a tuple with the PeriodStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodStart

`func (o *ImageCreditBalance) SetPeriodStart(v time.Time)`

SetPeriodStart sets PeriodStart field to given value.


### GetPeriodEnd

`func (o *ImageCreditBalance) GetPeriodEnd() time.Time`

GetPeriodEnd returns the PeriodEnd field if non-nil, zero value otherwise.

### GetPeriodEndOk

`func (o *ImageCreditBalance) GetPeriodEndOk() (*time.Time, bool)`

GetPeriodEndOk returns a tuple with the PeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodEnd

`func (o *ImageCreditBalance) SetPeriodEnd(v time.Time)`

SetPeriodEnd sets PeriodEnd field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


