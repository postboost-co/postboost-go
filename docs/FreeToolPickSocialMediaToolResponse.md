# FreeToolPickSocialMediaToolResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Needs** | Pointer to **[]string** | The needs matched, deduplicated, in a fixed order. | [optional] 
**Results** | Pointer to [**[]FreeToolPickSocialMediaToolResponseResultsInner**](FreeToolPickSocialMediaToolResponseResultsInner.md) | Every tool compared, PostBoost included: by score (highest first), then name. | [optional] 
**CheckedAt** | Pointer to **string** | Date of the comparison data snapshot. | [optional] 
**CheckedLabel** | Pointer to **string** | The snapshot month, as shown on the page. | [optional] 

## Methods

### NewFreeToolPickSocialMediaToolResponse

`func NewFreeToolPickSocialMediaToolResponse() *FreeToolPickSocialMediaToolResponse`

NewFreeToolPickSocialMediaToolResponse instantiates a new FreeToolPickSocialMediaToolResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolPickSocialMediaToolResponseWithDefaults

`func NewFreeToolPickSocialMediaToolResponseWithDefaults() *FreeToolPickSocialMediaToolResponse`

NewFreeToolPickSocialMediaToolResponseWithDefaults instantiates a new FreeToolPickSocialMediaToolResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNeeds

`func (o *FreeToolPickSocialMediaToolResponse) GetNeeds() []string`

GetNeeds returns the Needs field if non-nil, zero value otherwise.

### GetNeedsOk

`func (o *FreeToolPickSocialMediaToolResponse) GetNeedsOk() (*[]string, bool)`

GetNeedsOk returns a tuple with the Needs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeeds

`func (o *FreeToolPickSocialMediaToolResponse) SetNeeds(v []string)`

SetNeeds sets Needs field to given value.

### HasNeeds

`func (o *FreeToolPickSocialMediaToolResponse) HasNeeds() bool`

HasNeeds returns a boolean if a field has been set.

### GetResults

`func (o *FreeToolPickSocialMediaToolResponse) GetResults() []FreeToolPickSocialMediaToolResponseResultsInner`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *FreeToolPickSocialMediaToolResponse) GetResultsOk() (*[]FreeToolPickSocialMediaToolResponseResultsInner, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *FreeToolPickSocialMediaToolResponse) SetResults(v []FreeToolPickSocialMediaToolResponseResultsInner)`

SetResults sets Results field to given value.

### HasResults

`func (o *FreeToolPickSocialMediaToolResponse) HasResults() bool`

HasResults returns a boolean if a field has been set.

### GetCheckedAt

`func (o *FreeToolPickSocialMediaToolResponse) GetCheckedAt() string`

GetCheckedAt returns the CheckedAt field if non-nil, zero value otherwise.

### GetCheckedAtOk

`func (o *FreeToolPickSocialMediaToolResponse) GetCheckedAtOk() (*string, bool)`

GetCheckedAtOk returns a tuple with the CheckedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckedAt

`func (o *FreeToolPickSocialMediaToolResponse) SetCheckedAt(v string)`

SetCheckedAt sets CheckedAt field to given value.

### HasCheckedAt

`func (o *FreeToolPickSocialMediaToolResponse) HasCheckedAt() bool`

HasCheckedAt returns a boolean if a field has been set.

### GetCheckedLabel

`func (o *FreeToolPickSocialMediaToolResponse) GetCheckedLabel() string`

GetCheckedLabel returns the CheckedLabel field if non-nil, zero value otherwise.

### GetCheckedLabelOk

`func (o *FreeToolPickSocialMediaToolResponse) GetCheckedLabelOk() (*string, bool)`

GetCheckedLabelOk returns a tuple with the CheckedLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckedLabel

`func (o *FreeToolPickSocialMediaToolResponse) SetCheckedLabel(v string)`

SetCheckedLabel sets CheckedLabel field to given value.

### HasCheckedLabel

`func (o *FreeToolPickSocialMediaToolResponse) HasCheckedLabel() bool`

HasCheckedLabel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


