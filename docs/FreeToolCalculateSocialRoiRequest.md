# FreeToolCalculateSocialRoiRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Revenue** | **float32** | Revenue attributed to social media in the period, in USD. | 
**Costs** | Pointer to [**FreeToolCalculateSocialRoiRequestCosts**](FreeToolCalculateSocialRoiRequestCosts.md) |  | [optional] 
**Period** | Pointer to **string** | Optional label for the period, e.g. \&quot;Q3 2026\&quot;. | [optional] 

## Methods

### NewFreeToolCalculateSocialRoiRequest

`func NewFreeToolCalculateSocialRoiRequest(revenue float32, ) *FreeToolCalculateSocialRoiRequest`

NewFreeToolCalculateSocialRoiRequest instantiates a new FreeToolCalculateSocialRoiRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCalculateSocialRoiRequestWithDefaults

`func NewFreeToolCalculateSocialRoiRequestWithDefaults() *FreeToolCalculateSocialRoiRequest`

NewFreeToolCalculateSocialRoiRequestWithDefaults instantiates a new FreeToolCalculateSocialRoiRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRevenue

`func (o *FreeToolCalculateSocialRoiRequest) GetRevenue() float32`

GetRevenue returns the Revenue field if non-nil, zero value otherwise.

### GetRevenueOk

`func (o *FreeToolCalculateSocialRoiRequest) GetRevenueOk() (*float32, bool)`

GetRevenueOk returns a tuple with the Revenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevenue

`func (o *FreeToolCalculateSocialRoiRequest) SetRevenue(v float32)`

SetRevenue sets Revenue field to given value.


### GetCosts

`func (o *FreeToolCalculateSocialRoiRequest) GetCosts() FreeToolCalculateSocialRoiRequestCosts`

GetCosts returns the Costs field if non-nil, zero value otherwise.

### GetCostsOk

`func (o *FreeToolCalculateSocialRoiRequest) GetCostsOk() (*FreeToolCalculateSocialRoiRequestCosts, bool)`

GetCostsOk returns a tuple with the Costs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCosts

`func (o *FreeToolCalculateSocialRoiRequest) SetCosts(v FreeToolCalculateSocialRoiRequestCosts)`

SetCosts sets Costs field to given value.

### HasCosts

`func (o *FreeToolCalculateSocialRoiRequest) HasCosts() bool`

HasCosts returns a boolean if a field has been set.

### GetPeriod

`func (o *FreeToolCalculateSocialRoiRequest) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *FreeToolCalculateSocialRoiRequest) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *FreeToolCalculateSocialRoiRequest) SetPeriod(v string)`

SetPeriod sets Period field to given value.

### HasPeriod

`func (o *FreeToolCalculateSocialRoiRequest) HasPeriod() bool`

HasPeriod returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


