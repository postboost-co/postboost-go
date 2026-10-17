# FreeToolCalculateInfluencerRateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tier** | Pointer to **string** |  | [optional] 
**TierLabel** | Pointer to **string** |  | [optional] 
**Deliverable** | Pointer to **string** |  | [optional] 
**GuideLow** | Pointer to **int32** | USD, low end of the vendor price-guide range after the adjustments. | [optional] 
**GuideHigh** | Pointer to **NullableInt32** | USD, high end; null when the guide is open-ended (e.g. 10,000+). | [optional] 
**GuideSource** | Pointer to [**FreeToolCalculateInfluencerRateResponseGuideSource**](FreeToolCalculateInfluencerRateResponseGuideSource.md) |  | [optional] 
**MarketplaceMedian** | Pointer to **int32** | USD, the measured median paid deliverable for this tier, all networks, before adjustments. | [optional] 
**MarketplaceNote** | Pointer to **string** |  | [optional] 
**MarketplaceSource** | Pointer to [**FreeToolCalculateInfluencerRateResponseGuideSource**](FreeToolCalculateInfluencerRateResponseGuideSource.md) |  | [optional] 
**CpmEstimate** | Pointer to **NullableInt32** | USD, avg_views / 1,000 × cpm_usd (half up); null without both. | [optional] 
**Multipliers** | Pointer to [**[]FreeToolCalculateInfluencerRateResponseMultipliersInner**](FreeToolCalculateInfluencerRateResponseMultipliersInner.md) | Every adjustment applied, as a percent of the base price. | [optional] 
**Method** | Pointer to **string** |  | [optional] 
**Warnings** | Pointer to **[]string** |  | [optional] 
**Currency** | Pointer to **string** |  | [optional] 
**LastVerified** | Pointer to **string** |  | [optional] 

## Methods

### NewFreeToolCalculateInfluencerRateResponse

`func NewFreeToolCalculateInfluencerRateResponse() *FreeToolCalculateInfluencerRateResponse`

NewFreeToolCalculateInfluencerRateResponse instantiates a new FreeToolCalculateInfluencerRateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCalculateInfluencerRateResponseWithDefaults

`func NewFreeToolCalculateInfluencerRateResponseWithDefaults() *FreeToolCalculateInfluencerRateResponse`

NewFreeToolCalculateInfluencerRateResponseWithDefaults instantiates a new FreeToolCalculateInfluencerRateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTier

`func (o *FreeToolCalculateInfluencerRateResponse) GetTier() string`

GetTier returns the Tier field if non-nil, zero value otherwise.

### GetTierOk

`func (o *FreeToolCalculateInfluencerRateResponse) GetTierOk() (*string, bool)`

GetTierOk returns a tuple with the Tier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTier

`func (o *FreeToolCalculateInfluencerRateResponse) SetTier(v string)`

SetTier sets Tier field to given value.

### HasTier

`func (o *FreeToolCalculateInfluencerRateResponse) HasTier() bool`

HasTier returns a boolean if a field has been set.

### GetTierLabel

`func (o *FreeToolCalculateInfluencerRateResponse) GetTierLabel() string`

GetTierLabel returns the TierLabel field if non-nil, zero value otherwise.

### GetTierLabelOk

`func (o *FreeToolCalculateInfluencerRateResponse) GetTierLabelOk() (*string, bool)`

GetTierLabelOk returns a tuple with the TierLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTierLabel

`func (o *FreeToolCalculateInfluencerRateResponse) SetTierLabel(v string)`

SetTierLabel sets TierLabel field to given value.

### HasTierLabel

`func (o *FreeToolCalculateInfluencerRateResponse) HasTierLabel() bool`

HasTierLabel returns a boolean if a field has been set.

### GetDeliverable

`func (o *FreeToolCalculateInfluencerRateResponse) GetDeliverable() string`

GetDeliverable returns the Deliverable field if non-nil, zero value otherwise.

### GetDeliverableOk

`func (o *FreeToolCalculateInfluencerRateResponse) GetDeliverableOk() (*string, bool)`

GetDeliverableOk returns a tuple with the Deliverable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliverable

`func (o *FreeToolCalculateInfluencerRateResponse) SetDeliverable(v string)`

SetDeliverable sets Deliverable field to given value.

### HasDeliverable

`func (o *FreeToolCalculateInfluencerRateResponse) HasDeliverable() bool`

HasDeliverable returns a boolean if a field has been set.

### GetGuideLow

`func (o *FreeToolCalculateInfluencerRateResponse) GetGuideLow() int32`

GetGuideLow returns the GuideLow field if non-nil, zero value otherwise.

### GetGuideLowOk

`func (o *FreeToolCalculateInfluencerRateResponse) GetGuideLowOk() (*int32, bool)`

GetGuideLowOk returns a tuple with the GuideLow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuideLow

`func (o *FreeToolCalculateInfluencerRateResponse) SetGuideLow(v int32)`

SetGuideLow sets GuideLow field to given value.

### HasGuideLow

`func (o *FreeToolCalculateInfluencerRateResponse) HasGuideLow() bool`

HasGuideLow returns a boolean if a field has been set.

### GetGuideHigh

`func (o *FreeToolCalculateInfluencerRateResponse) GetGuideHigh() int32`

GetGuideHigh returns the GuideHigh field if non-nil, zero value otherwise.

### GetGuideHighOk

`func (o *FreeToolCalculateInfluencerRateResponse) GetGuideHighOk() (*int32, bool)`

GetGuideHighOk returns a tuple with the GuideHigh field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuideHigh

`func (o *FreeToolCalculateInfluencerRateResponse) SetGuideHigh(v int32)`

SetGuideHigh sets GuideHigh field to given value.

### HasGuideHigh

`func (o *FreeToolCalculateInfluencerRateResponse) HasGuideHigh() bool`

HasGuideHigh returns a boolean if a field has been set.

### SetGuideHighNil

`func (o *FreeToolCalculateInfluencerRateResponse) SetGuideHighNil(b bool)`

 SetGuideHighNil sets the value for GuideHigh to be an explicit nil

### UnsetGuideHigh
`func (o *FreeToolCalculateInfluencerRateResponse) UnsetGuideHigh()`

UnsetGuideHigh ensures that no value is present for GuideHigh, not even an explicit nil
### GetGuideSource

`func (o *FreeToolCalculateInfluencerRateResponse) GetGuideSource() FreeToolCalculateInfluencerRateResponseGuideSource`

GetGuideSource returns the GuideSource field if non-nil, zero value otherwise.

### GetGuideSourceOk

`func (o *FreeToolCalculateInfluencerRateResponse) GetGuideSourceOk() (*FreeToolCalculateInfluencerRateResponseGuideSource, bool)`

GetGuideSourceOk returns a tuple with the GuideSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuideSource

`func (o *FreeToolCalculateInfluencerRateResponse) SetGuideSource(v FreeToolCalculateInfluencerRateResponseGuideSource)`

SetGuideSource sets GuideSource field to given value.

### HasGuideSource

`func (o *FreeToolCalculateInfluencerRateResponse) HasGuideSource() bool`

HasGuideSource returns a boolean if a field has been set.

### GetMarketplaceMedian

`func (o *FreeToolCalculateInfluencerRateResponse) GetMarketplaceMedian() int32`

GetMarketplaceMedian returns the MarketplaceMedian field if non-nil, zero value otherwise.

### GetMarketplaceMedianOk

`func (o *FreeToolCalculateInfluencerRateResponse) GetMarketplaceMedianOk() (*int32, bool)`

GetMarketplaceMedianOk returns a tuple with the MarketplaceMedian field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarketplaceMedian

`func (o *FreeToolCalculateInfluencerRateResponse) SetMarketplaceMedian(v int32)`

SetMarketplaceMedian sets MarketplaceMedian field to given value.

### HasMarketplaceMedian

`func (o *FreeToolCalculateInfluencerRateResponse) HasMarketplaceMedian() bool`

HasMarketplaceMedian returns a boolean if a field has been set.

### GetMarketplaceNote

`func (o *FreeToolCalculateInfluencerRateResponse) GetMarketplaceNote() string`

GetMarketplaceNote returns the MarketplaceNote field if non-nil, zero value otherwise.

### GetMarketplaceNoteOk

`func (o *FreeToolCalculateInfluencerRateResponse) GetMarketplaceNoteOk() (*string, bool)`

GetMarketplaceNoteOk returns a tuple with the MarketplaceNote field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarketplaceNote

`func (o *FreeToolCalculateInfluencerRateResponse) SetMarketplaceNote(v string)`

SetMarketplaceNote sets MarketplaceNote field to given value.

### HasMarketplaceNote

`func (o *FreeToolCalculateInfluencerRateResponse) HasMarketplaceNote() bool`

HasMarketplaceNote returns a boolean if a field has been set.

### GetMarketplaceSource

`func (o *FreeToolCalculateInfluencerRateResponse) GetMarketplaceSource() FreeToolCalculateInfluencerRateResponseGuideSource`

GetMarketplaceSource returns the MarketplaceSource field if non-nil, zero value otherwise.

### GetMarketplaceSourceOk

`func (o *FreeToolCalculateInfluencerRateResponse) GetMarketplaceSourceOk() (*FreeToolCalculateInfluencerRateResponseGuideSource, bool)`

GetMarketplaceSourceOk returns a tuple with the MarketplaceSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarketplaceSource

`func (o *FreeToolCalculateInfluencerRateResponse) SetMarketplaceSource(v FreeToolCalculateInfluencerRateResponseGuideSource)`

SetMarketplaceSource sets MarketplaceSource field to given value.

### HasMarketplaceSource

`func (o *FreeToolCalculateInfluencerRateResponse) HasMarketplaceSource() bool`

HasMarketplaceSource returns a boolean if a field has been set.

### GetCpmEstimate

`func (o *FreeToolCalculateInfluencerRateResponse) GetCpmEstimate() int32`

GetCpmEstimate returns the CpmEstimate field if non-nil, zero value otherwise.

### GetCpmEstimateOk

`func (o *FreeToolCalculateInfluencerRateResponse) GetCpmEstimateOk() (*int32, bool)`

GetCpmEstimateOk returns a tuple with the CpmEstimate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpmEstimate

`func (o *FreeToolCalculateInfluencerRateResponse) SetCpmEstimate(v int32)`

SetCpmEstimate sets CpmEstimate field to given value.

### HasCpmEstimate

`func (o *FreeToolCalculateInfluencerRateResponse) HasCpmEstimate() bool`

HasCpmEstimate returns a boolean if a field has been set.

### SetCpmEstimateNil

`func (o *FreeToolCalculateInfluencerRateResponse) SetCpmEstimateNil(b bool)`

 SetCpmEstimateNil sets the value for CpmEstimate to be an explicit nil

### UnsetCpmEstimate
`func (o *FreeToolCalculateInfluencerRateResponse) UnsetCpmEstimate()`

UnsetCpmEstimate ensures that no value is present for CpmEstimate, not even an explicit nil
### GetMultipliers

`func (o *FreeToolCalculateInfluencerRateResponse) GetMultipliers() []FreeToolCalculateInfluencerRateResponseMultipliersInner`

GetMultipliers returns the Multipliers field if non-nil, zero value otherwise.

### GetMultipliersOk

`func (o *FreeToolCalculateInfluencerRateResponse) GetMultipliersOk() (*[]FreeToolCalculateInfluencerRateResponseMultipliersInner, bool)`

GetMultipliersOk returns a tuple with the Multipliers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMultipliers

`func (o *FreeToolCalculateInfluencerRateResponse) SetMultipliers(v []FreeToolCalculateInfluencerRateResponseMultipliersInner)`

SetMultipliers sets Multipliers field to given value.

### HasMultipliers

`func (o *FreeToolCalculateInfluencerRateResponse) HasMultipliers() bool`

HasMultipliers returns a boolean if a field has been set.

### GetMethod

`func (o *FreeToolCalculateInfluencerRateResponse) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *FreeToolCalculateInfluencerRateResponse) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *FreeToolCalculateInfluencerRateResponse) SetMethod(v string)`

SetMethod sets Method field to given value.

### HasMethod

`func (o *FreeToolCalculateInfluencerRateResponse) HasMethod() bool`

HasMethod returns a boolean if a field has been set.

### GetWarnings

`func (o *FreeToolCalculateInfluencerRateResponse) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *FreeToolCalculateInfluencerRateResponse) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *FreeToolCalculateInfluencerRateResponse) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *FreeToolCalculateInfluencerRateResponse) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.

### GetCurrency

`func (o *FreeToolCalculateInfluencerRateResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *FreeToolCalculateInfluencerRateResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *FreeToolCalculateInfluencerRateResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *FreeToolCalculateInfluencerRateResponse) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetLastVerified

`func (o *FreeToolCalculateInfluencerRateResponse) GetLastVerified() string`

GetLastVerified returns the LastVerified field if non-nil, zero value otherwise.

### GetLastVerifiedOk

`func (o *FreeToolCalculateInfluencerRateResponse) GetLastVerifiedOk() (*string, bool)`

GetLastVerifiedOk returns a tuple with the LastVerified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastVerified

`func (o *FreeToolCalculateInfluencerRateResponse) SetLastVerified(v string)`

SetLastVerified sets LastVerified field to given value.

### HasLastVerified

`func (o *FreeToolCalculateInfluencerRateResponse) HasLastVerified() bool`

HasLastVerified returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


