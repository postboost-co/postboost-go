# FreeToolCalculateSocialRoiResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Period** | Pointer to **NullableString** |  | [optional] 
**Revenue** | Pointer to **float32** |  | [optional] 
**TotalCost** | Pointer to **float32** | Sum of every cost, labor &#x3D; hours × hourly rate. 2 decimals. | [optional] 
**NetReturn** | Pointer to **float32** | Revenue minus total cost. 2 decimals. | [optional] 
**RoiPercent** | Pointer to **NullableFloat32** | (revenue − total cost) ÷ total cost × 100, 1 decimal; null when the total cost is 0. | [optional] 
**CostBreakdown** | Pointer to [**[]FreeToolCalculateSocialRoiResponseCostBreakdownInner**](FreeToolCalculateSocialRoiResponseCostBreakdownInner.md) | Every cost above 0, with its share of the total cost (percent, 1 decimal). | [optional] 
**Warnings** | Pointer to **[]string** |  | [optional] 
**Formula** | Pointer to **string** |  | [optional] 

## Methods

### NewFreeToolCalculateSocialRoiResponse

`func NewFreeToolCalculateSocialRoiResponse() *FreeToolCalculateSocialRoiResponse`

NewFreeToolCalculateSocialRoiResponse instantiates a new FreeToolCalculateSocialRoiResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCalculateSocialRoiResponseWithDefaults

`func NewFreeToolCalculateSocialRoiResponseWithDefaults() *FreeToolCalculateSocialRoiResponse`

NewFreeToolCalculateSocialRoiResponseWithDefaults instantiates a new FreeToolCalculateSocialRoiResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPeriod

`func (o *FreeToolCalculateSocialRoiResponse) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *FreeToolCalculateSocialRoiResponse) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *FreeToolCalculateSocialRoiResponse) SetPeriod(v string)`

SetPeriod sets Period field to given value.

### HasPeriod

`func (o *FreeToolCalculateSocialRoiResponse) HasPeriod() bool`

HasPeriod returns a boolean if a field has been set.

### SetPeriodNil

`func (o *FreeToolCalculateSocialRoiResponse) SetPeriodNil(b bool)`

 SetPeriodNil sets the value for Period to be an explicit nil

### UnsetPeriod
`func (o *FreeToolCalculateSocialRoiResponse) UnsetPeriod()`

UnsetPeriod ensures that no value is present for Period, not even an explicit nil
### GetRevenue

`func (o *FreeToolCalculateSocialRoiResponse) GetRevenue() float32`

GetRevenue returns the Revenue field if non-nil, zero value otherwise.

### GetRevenueOk

`func (o *FreeToolCalculateSocialRoiResponse) GetRevenueOk() (*float32, bool)`

GetRevenueOk returns a tuple with the Revenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevenue

`func (o *FreeToolCalculateSocialRoiResponse) SetRevenue(v float32)`

SetRevenue sets Revenue field to given value.

### HasRevenue

`func (o *FreeToolCalculateSocialRoiResponse) HasRevenue() bool`

HasRevenue returns a boolean if a field has been set.

### GetTotalCost

`func (o *FreeToolCalculateSocialRoiResponse) GetTotalCost() float32`

GetTotalCost returns the TotalCost field if non-nil, zero value otherwise.

### GetTotalCostOk

`func (o *FreeToolCalculateSocialRoiResponse) GetTotalCostOk() (*float32, bool)`

GetTotalCostOk returns a tuple with the TotalCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCost

`func (o *FreeToolCalculateSocialRoiResponse) SetTotalCost(v float32)`

SetTotalCost sets TotalCost field to given value.

### HasTotalCost

`func (o *FreeToolCalculateSocialRoiResponse) HasTotalCost() bool`

HasTotalCost returns a boolean if a field has been set.

### GetNetReturn

`func (o *FreeToolCalculateSocialRoiResponse) GetNetReturn() float32`

GetNetReturn returns the NetReturn field if non-nil, zero value otherwise.

### GetNetReturnOk

`func (o *FreeToolCalculateSocialRoiResponse) GetNetReturnOk() (*float32, bool)`

GetNetReturnOk returns a tuple with the NetReturn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetReturn

`func (o *FreeToolCalculateSocialRoiResponse) SetNetReturn(v float32)`

SetNetReturn sets NetReturn field to given value.

### HasNetReturn

`func (o *FreeToolCalculateSocialRoiResponse) HasNetReturn() bool`

HasNetReturn returns a boolean if a field has been set.

### GetRoiPercent

`func (o *FreeToolCalculateSocialRoiResponse) GetRoiPercent() float32`

GetRoiPercent returns the RoiPercent field if non-nil, zero value otherwise.

### GetRoiPercentOk

`func (o *FreeToolCalculateSocialRoiResponse) GetRoiPercentOk() (*float32, bool)`

GetRoiPercentOk returns a tuple with the RoiPercent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoiPercent

`func (o *FreeToolCalculateSocialRoiResponse) SetRoiPercent(v float32)`

SetRoiPercent sets RoiPercent field to given value.

### HasRoiPercent

`func (o *FreeToolCalculateSocialRoiResponse) HasRoiPercent() bool`

HasRoiPercent returns a boolean if a field has been set.

### SetRoiPercentNil

`func (o *FreeToolCalculateSocialRoiResponse) SetRoiPercentNil(b bool)`

 SetRoiPercentNil sets the value for RoiPercent to be an explicit nil

### UnsetRoiPercent
`func (o *FreeToolCalculateSocialRoiResponse) UnsetRoiPercent()`

UnsetRoiPercent ensures that no value is present for RoiPercent, not even an explicit nil
### GetCostBreakdown

`func (o *FreeToolCalculateSocialRoiResponse) GetCostBreakdown() []FreeToolCalculateSocialRoiResponseCostBreakdownInner`

GetCostBreakdown returns the CostBreakdown field if non-nil, zero value otherwise.

### GetCostBreakdownOk

`func (o *FreeToolCalculateSocialRoiResponse) GetCostBreakdownOk() (*[]FreeToolCalculateSocialRoiResponseCostBreakdownInner, bool)`

GetCostBreakdownOk returns a tuple with the CostBreakdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCostBreakdown

`func (o *FreeToolCalculateSocialRoiResponse) SetCostBreakdown(v []FreeToolCalculateSocialRoiResponseCostBreakdownInner)`

SetCostBreakdown sets CostBreakdown field to given value.

### HasCostBreakdown

`func (o *FreeToolCalculateSocialRoiResponse) HasCostBreakdown() bool`

HasCostBreakdown returns a boolean if a field has been set.

### GetWarnings

`func (o *FreeToolCalculateSocialRoiResponse) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *FreeToolCalculateSocialRoiResponse) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *FreeToolCalculateSocialRoiResponse) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *FreeToolCalculateSocialRoiResponse) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.

### GetFormula

`func (o *FreeToolCalculateSocialRoiResponse) GetFormula() string`

GetFormula returns the Formula field if non-nil, zero value otherwise.

### GetFormulaOk

`func (o *FreeToolCalculateSocialRoiResponse) GetFormulaOk() (*string, bool)`

GetFormulaOk returns a tuple with the Formula field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormula

`func (o *FreeToolCalculateSocialRoiResponse) SetFormula(v string)`

SetFormula sets Formula field to given value.

### HasFormula

`func (o *FreeToolCalculateSocialRoiResponse) HasFormula() bool`

HasFormula returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


