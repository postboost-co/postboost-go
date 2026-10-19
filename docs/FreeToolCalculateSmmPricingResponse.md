# FreeToolCalculateSmmPricingResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Currency** | Pointer to **string** |  | [optional] 
**PricingModel** | Pointer to **string** |  | [optional] 
**PostsPerMonth** | Pointer to **float32** | Networks × posts per week × 52 ÷ 12, 1 decimal. | [optional] 
**HoursPerMonth** | Pointer to **float32** | Estimated working hours a month, 1 decimal. | [optional] 
**HourlyRate** | Pointer to **float32** |  | [optional] 
**MonthlyRetainer** | Pointer to **float32** | Hours a month × hourly rate, whole currency units. | [optional] 
**PerPost** | Pointer to **NullableFloat32** | Monthly retainer ÷ posts a month, 2 decimals; null with no posts. | [optional] 
**Range** | Pointer to [**FreeToolCalculateSmmPricingResponseRange**](FreeToolCalculateSmmPricingResponseRange.md) |  | [optional] 
**LineItems** | Pointer to [**[]FreeToolCalculateSmmPricingResponseLineItemsInner**](FreeToolCalculateSmmPricingResponseLineItemsInner.md) | Every task with hours above 0. | [optional] 
**Assumptions** | Pointer to **[]string** |  | [optional] 

## Methods

### NewFreeToolCalculateSmmPricingResponse

`func NewFreeToolCalculateSmmPricingResponse() *FreeToolCalculateSmmPricingResponse`

NewFreeToolCalculateSmmPricingResponse instantiates a new FreeToolCalculateSmmPricingResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCalculateSmmPricingResponseWithDefaults

`func NewFreeToolCalculateSmmPricingResponseWithDefaults() *FreeToolCalculateSmmPricingResponse`

NewFreeToolCalculateSmmPricingResponseWithDefaults instantiates a new FreeToolCalculateSmmPricingResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCurrency

`func (o *FreeToolCalculateSmmPricingResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *FreeToolCalculateSmmPricingResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *FreeToolCalculateSmmPricingResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *FreeToolCalculateSmmPricingResponse) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetPricingModel

`func (o *FreeToolCalculateSmmPricingResponse) GetPricingModel() string`

GetPricingModel returns the PricingModel field if non-nil, zero value otherwise.

### GetPricingModelOk

`func (o *FreeToolCalculateSmmPricingResponse) GetPricingModelOk() (*string, bool)`

GetPricingModelOk returns a tuple with the PricingModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingModel

`func (o *FreeToolCalculateSmmPricingResponse) SetPricingModel(v string)`

SetPricingModel sets PricingModel field to given value.

### HasPricingModel

`func (o *FreeToolCalculateSmmPricingResponse) HasPricingModel() bool`

HasPricingModel returns a boolean if a field has been set.

### GetPostsPerMonth

`func (o *FreeToolCalculateSmmPricingResponse) GetPostsPerMonth() float32`

GetPostsPerMonth returns the PostsPerMonth field if non-nil, zero value otherwise.

### GetPostsPerMonthOk

`func (o *FreeToolCalculateSmmPricingResponse) GetPostsPerMonthOk() (*float32, bool)`

GetPostsPerMonthOk returns a tuple with the PostsPerMonth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostsPerMonth

`func (o *FreeToolCalculateSmmPricingResponse) SetPostsPerMonth(v float32)`

SetPostsPerMonth sets PostsPerMonth field to given value.

### HasPostsPerMonth

`func (o *FreeToolCalculateSmmPricingResponse) HasPostsPerMonth() bool`

HasPostsPerMonth returns a boolean if a field has been set.

### GetHoursPerMonth

`func (o *FreeToolCalculateSmmPricingResponse) GetHoursPerMonth() float32`

GetHoursPerMonth returns the HoursPerMonth field if non-nil, zero value otherwise.

### GetHoursPerMonthOk

`func (o *FreeToolCalculateSmmPricingResponse) GetHoursPerMonthOk() (*float32, bool)`

GetHoursPerMonthOk returns a tuple with the HoursPerMonth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHoursPerMonth

`func (o *FreeToolCalculateSmmPricingResponse) SetHoursPerMonth(v float32)`

SetHoursPerMonth sets HoursPerMonth field to given value.

### HasHoursPerMonth

`func (o *FreeToolCalculateSmmPricingResponse) HasHoursPerMonth() bool`

HasHoursPerMonth returns a boolean if a field has been set.

### GetHourlyRate

`func (o *FreeToolCalculateSmmPricingResponse) GetHourlyRate() float32`

GetHourlyRate returns the HourlyRate field if non-nil, zero value otherwise.

### GetHourlyRateOk

`func (o *FreeToolCalculateSmmPricingResponse) GetHourlyRateOk() (*float32, bool)`

GetHourlyRateOk returns a tuple with the HourlyRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHourlyRate

`func (o *FreeToolCalculateSmmPricingResponse) SetHourlyRate(v float32)`

SetHourlyRate sets HourlyRate field to given value.

### HasHourlyRate

`func (o *FreeToolCalculateSmmPricingResponse) HasHourlyRate() bool`

HasHourlyRate returns a boolean if a field has been set.

### GetMonthlyRetainer

`func (o *FreeToolCalculateSmmPricingResponse) GetMonthlyRetainer() float32`

GetMonthlyRetainer returns the MonthlyRetainer field if non-nil, zero value otherwise.

### GetMonthlyRetainerOk

`func (o *FreeToolCalculateSmmPricingResponse) GetMonthlyRetainerOk() (*float32, bool)`

GetMonthlyRetainerOk returns a tuple with the MonthlyRetainer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlyRetainer

`func (o *FreeToolCalculateSmmPricingResponse) SetMonthlyRetainer(v float32)`

SetMonthlyRetainer sets MonthlyRetainer field to given value.

### HasMonthlyRetainer

`func (o *FreeToolCalculateSmmPricingResponse) HasMonthlyRetainer() bool`

HasMonthlyRetainer returns a boolean if a field has been set.

### GetPerPost

`func (o *FreeToolCalculateSmmPricingResponse) GetPerPost() float32`

GetPerPost returns the PerPost field if non-nil, zero value otherwise.

### GetPerPostOk

`func (o *FreeToolCalculateSmmPricingResponse) GetPerPostOk() (*float32, bool)`

GetPerPostOk returns a tuple with the PerPost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerPost

`func (o *FreeToolCalculateSmmPricingResponse) SetPerPost(v float32)`

SetPerPost sets PerPost field to given value.

### HasPerPost

`func (o *FreeToolCalculateSmmPricingResponse) HasPerPost() bool`

HasPerPost returns a boolean if a field has been set.

### SetPerPostNil

`func (o *FreeToolCalculateSmmPricingResponse) SetPerPostNil(b bool)`

 SetPerPostNil sets the value for PerPost to be an explicit nil

### UnsetPerPost
`func (o *FreeToolCalculateSmmPricingResponse) UnsetPerPost()`

UnsetPerPost ensures that no value is present for PerPost, not even an explicit nil
### GetRange

`func (o *FreeToolCalculateSmmPricingResponse) GetRange() FreeToolCalculateSmmPricingResponseRange`

GetRange returns the Range field if non-nil, zero value otherwise.

### GetRangeOk

`func (o *FreeToolCalculateSmmPricingResponse) GetRangeOk() (*FreeToolCalculateSmmPricingResponseRange, bool)`

GetRangeOk returns a tuple with the Range field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRange

`func (o *FreeToolCalculateSmmPricingResponse) SetRange(v FreeToolCalculateSmmPricingResponseRange)`

SetRange sets Range field to given value.

### HasRange

`func (o *FreeToolCalculateSmmPricingResponse) HasRange() bool`

HasRange returns a boolean if a field has been set.

### GetLineItems

`func (o *FreeToolCalculateSmmPricingResponse) GetLineItems() []FreeToolCalculateSmmPricingResponseLineItemsInner`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *FreeToolCalculateSmmPricingResponse) GetLineItemsOk() (*[]FreeToolCalculateSmmPricingResponseLineItemsInner, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *FreeToolCalculateSmmPricingResponse) SetLineItems(v []FreeToolCalculateSmmPricingResponseLineItemsInner)`

SetLineItems sets LineItems field to given value.

### HasLineItems

`func (o *FreeToolCalculateSmmPricingResponse) HasLineItems() bool`

HasLineItems returns a boolean if a field has been set.

### GetAssumptions

`func (o *FreeToolCalculateSmmPricingResponse) GetAssumptions() []string`

GetAssumptions returns the Assumptions field if non-nil, zero value otherwise.

### GetAssumptionsOk

`func (o *FreeToolCalculateSmmPricingResponse) GetAssumptionsOk() (*[]string, bool)`

GetAssumptionsOk returns a tuple with the Assumptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssumptions

`func (o *FreeToolCalculateSmmPricingResponse) SetAssumptions(v []string)`

SetAssumptions sets Assumptions field to given value.

### HasAssumptions

`func (o *FreeToolCalculateSmmPricingResponse) HasAssumptions() bool`

HasAssumptions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


