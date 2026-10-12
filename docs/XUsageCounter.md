# XUsageCounter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Used** | **int32** |  | 
**Limit** | **NullableInt32** | Monthly allowance; null &#x3D; unlimited. | 

## Methods

### NewXUsageCounter

`func NewXUsageCounter(used int32, limit NullableInt32, ) *XUsageCounter`

NewXUsageCounter instantiates a new XUsageCounter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewXUsageCounterWithDefaults

`func NewXUsageCounterWithDefaults() *XUsageCounter`

NewXUsageCounterWithDefaults instantiates a new XUsageCounter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsed

`func (o *XUsageCounter) GetUsed() int32`

GetUsed returns the Used field if non-nil, zero value otherwise.

### GetUsedOk

`func (o *XUsageCounter) GetUsedOk() (*int32, bool)`

GetUsedOk returns a tuple with the Used field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsed

`func (o *XUsageCounter) SetUsed(v int32)`

SetUsed sets Used field to given value.


### GetLimit

`func (o *XUsageCounter) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *XUsageCounter) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *XUsageCounter) SetLimit(v int32)`

SetLimit sets Limit field to given value.


### SetLimitNil

`func (o *XUsageCounter) SetLimitNil(b bool)`

 SetLimitNil sets the value for Limit to be an explicit nil

### UnsetLimit
`func (o *XUsageCounter) UnsetLimit()`

UnsetLimit ensures that no value is present for Limit, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


