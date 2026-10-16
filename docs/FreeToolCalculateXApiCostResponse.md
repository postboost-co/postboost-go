# FreeToolCalculateXApiCostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**LineItems** | Pointer to [**[]FreeToolCalculateXApiCostResponseLineItemsInner**](FreeToolCalculateXApiCostResponseLineItemsInner.md) | One row per billed resource: count × unit price. | [optional] 
**TotalUsd** | Pointer to **float32** | Sum of every line item. | [optional] 
**LinkPremiumUsd** | Pointer to **float32** | What the link posts cost on top of the plain post price. | [optional] 
**Notes** | Pointer to **[]string** |  | [optional] 
**PricesLastVerified** | Pointer to **string** | When the prices were last checked against the source. | [optional] 
**Source** | Pointer to **string** |  | [optional] 

## Methods

### NewFreeToolCalculateXApiCostResponse

`func NewFreeToolCalculateXApiCostResponse() *FreeToolCalculateXApiCostResponse`

NewFreeToolCalculateXApiCostResponse instantiates a new FreeToolCalculateXApiCostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCalculateXApiCostResponseWithDefaults

`func NewFreeToolCalculateXApiCostResponseWithDefaults() *FreeToolCalculateXApiCostResponse`

NewFreeToolCalculateXApiCostResponseWithDefaults instantiates a new FreeToolCalculateXApiCostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLineItems

`func (o *FreeToolCalculateXApiCostResponse) GetLineItems() []FreeToolCalculateXApiCostResponseLineItemsInner`

GetLineItems returns the LineItems field if non-nil, zero value otherwise.

### GetLineItemsOk

`func (o *FreeToolCalculateXApiCostResponse) GetLineItemsOk() (*[]FreeToolCalculateXApiCostResponseLineItemsInner, bool)`

GetLineItemsOk returns a tuple with the LineItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLineItems

`func (o *FreeToolCalculateXApiCostResponse) SetLineItems(v []FreeToolCalculateXApiCostResponseLineItemsInner)`

SetLineItems sets LineItems field to given value.

### HasLineItems

`func (o *FreeToolCalculateXApiCostResponse) HasLineItems() bool`

HasLineItems returns a boolean if a field has been set.

### GetTotalUsd

`func (o *FreeToolCalculateXApiCostResponse) GetTotalUsd() float32`

GetTotalUsd returns the TotalUsd field if non-nil, zero value otherwise.

### GetTotalUsdOk

`func (o *FreeToolCalculateXApiCostResponse) GetTotalUsdOk() (*float32, bool)`

GetTotalUsdOk returns a tuple with the TotalUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalUsd

`func (o *FreeToolCalculateXApiCostResponse) SetTotalUsd(v float32)`

SetTotalUsd sets TotalUsd field to given value.

### HasTotalUsd

`func (o *FreeToolCalculateXApiCostResponse) HasTotalUsd() bool`

HasTotalUsd returns a boolean if a field has been set.

### GetLinkPremiumUsd

`func (o *FreeToolCalculateXApiCostResponse) GetLinkPremiumUsd() float32`

GetLinkPremiumUsd returns the LinkPremiumUsd field if non-nil, zero value otherwise.

### GetLinkPremiumUsdOk

`func (o *FreeToolCalculateXApiCostResponse) GetLinkPremiumUsdOk() (*float32, bool)`

GetLinkPremiumUsdOk returns a tuple with the LinkPremiumUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkPremiumUsd

`func (o *FreeToolCalculateXApiCostResponse) SetLinkPremiumUsd(v float32)`

SetLinkPremiumUsd sets LinkPremiumUsd field to given value.

### HasLinkPremiumUsd

`func (o *FreeToolCalculateXApiCostResponse) HasLinkPremiumUsd() bool`

HasLinkPremiumUsd returns a boolean if a field has been set.

### GetNotes

`func (o *FreeToolCalculateXApiCostResponse) GetNotes() []string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *FreeToolCalculateXApiCostResponse) GetNotesOk() (*[]string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *FreeToolCalculateXApiCostResponse) SetNotes(v []string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *FreeToolCalculateXApiCostResponse) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### GetPricesLastVerified

`func (o *FreeToolCalculateXApiCostResponse) GetPricesLastVerified() string`

GetPricesLastVerified returns the PricesLastVerified field if non-nil, zero value otherwise.

### GetPricesLastVerifiedOk

`func (o *FreeToolCalculateXApiCostResponse) GetPricesLastVerifiedOk() (*string, bool)`

GetPricesLastVerifiedOk returns a tuple with the PricesLastVerified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricesLastVerified

`func (o *FreeToolCalculateXApiCostResponse) SetPricesLastVerified(v string)`

SetPricesLastVerified sets PricesLastVerified field to given value.

### HasPricesLastVerified

`func (o *FreeToolCalculateXApiCostResponse) HasPricesLastVerified() bool`

HasPricesLastVerified returns a boolean if a field has been set.

### GetSource

`func (o *FreeToolCalculateXApiCostResponse) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *FreeToolCalculateXApiCostResponse) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *FreeToolCalculateXApiCostResponse) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *FreeToolCalculateXApiCostResponse) HasSource() bool`

HasSource returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


