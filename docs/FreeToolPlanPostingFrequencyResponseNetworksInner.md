# FreeToolPlanPostingFrequencyResponseNetworksInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Network** | Pointer to **string** |  | [optional] 
**Label** | Pointer to **string** |  | [optional] 
**RecommendedPerWeek** | Pointer to [**FreeToolPlanPostingFrequencyResponseNetworksInnerRecommendedPerWeek**](FreeToolPlanPostingFrequencyResponseNetworksInnerRecommendedPerWeek.md) |  | [optional] 
**RecommendedLabel** | Pointer to **string** | The range as text, e.g. \&quot;3-5 per week\&quot; or \&quot;1+ per week\&quot;. | [optional] 
**AllocatedPerWeek** | Pointer to **int32** | Your posts for this network: capacity split in proportion to the range midpoints (the minimum for an open-ended range). | [optional] 
**Fit** | Pointer to **string** | Where the allocation sits against the recommended range. | [optional] 
**SourceType** | Pointer to **string** | measured &#x3D; a study of real posts; vendor &#x3D; a software vendor&#39;s guidance; platform &#x3D; the network&#39;s own guidance. | [optional] 
**Sources** | Pointer to [**[]FreeToolPlanPostingFrequencyResponseNetworksInnerSourcesInner**](FreeToolPlanPostingFrequencyResponseNetworksInnerSourcesInner.md) |  | [optional] 

## Methods

### NewFreeToolPlanPostingFrequencyResponseNetworksInner

`func NewFreeToolPlanPostingFrequencyResponseNetworksInner() *FreeToolPlanPostingFrequencyResponseNetworksInner`

NewFreeToolPlanPostingFrequencyResponseNetworksInner instantiates a new FreeToolPlanPostingFrequencyResponseNetworksInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolPlanPostingFrequencyResponseNetworksInnerWithDefaults

`func NewFreeToolPlanPostingFrequencyResponseNetworksInnerWithDefaults() *FreeToolPlanPostingFrequencyResponseNetworksInner`

NewFreeToolPlanPostingFrequencyResponseNetworksInnerWithDefaults instantiates a new FreeToolPlanPostingFrequencyResponseNetworksInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNetwork

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetLabel

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetRecommendedPerWeek

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) GetRecommendedPerWeek() FreeToolPlanPostingFrequencyResponseNetworksInnerRecommendedPerWeek`

GetRecommendedPerWeek returns the RecommendedPerWeek field if non-nil, zero value otherwise.

### GetRecommendedPerWeekOk

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) GetRecommendedPerWeekOk() (*FreeToolPlanPostingFrequencyResponseNetworksInnerRecommendedPerWeek, bool)`

GetRecommendedPerWeekOk returns a tuple with the RecommendedPerWeek field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendedPerWeek

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) SetRecommendedPerWeek(v FreeToolPlanPostingFrequencyResponseNetworksInnerRecommendedPerWeek)`

SetRecommendedPerWeek sets RecommendedPerWeek field to given value.

### HasRecommendedPerWeek

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) HasRecommendedPerWeek() bool`

HasRecommendedPerWeek returns a boolean if a field has been set.

### GetRecommendedLabel

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) GetRecommendedLabel() string`

GetRecommendedLabel returns the RecommendedLabel field if non-nil, zero value otherwise.

### GetRecommendedLabelOk

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) GetRecommendedLabelOk() (*string, bool)`

GetRecommendedLabelOk returns a tuple with the RecommendedLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendedLabel

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) SetRecommendedLabel(v string)`

SetRecommendedLabel sets RecommendedLabel field to given value.

### HasRecommendedLabel

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) HasRecommendedLabel() bool`

HasRecommendedLabel returns a boolean if a field has been set.

### GetAllocatedPerWeek

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) GetAllocatedPerWeek() int32`

GetAllocatedPerWeek returns the AllocatedPerWeek field if non-nil, zero value otherwise.

### GetAllocatedPerWeekOk

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) GetAllocatedPerWeekOk() (*int32, bool)`

GetAllocatedPerWeekOk returns a tuple with the AllocatedPerWeek field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllocatedPerWeek

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) SetAllocatedPerWeek(v int32)`

SetAllocatedPerWeek sets AllocatedPerWeek field to given value.

### HasAllocatedPerWeek

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) HasAllocatedPerWeek() bool`

HasAllocatedPerWeek returns a boolean if a field has been set.

### GetFit

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) GetFit() string`

GetFit returns the Fit field if non-nil, zero value otherwise.

### GetFitOk

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) GetFitOk() (*string, bool)`

GetFitOk returns a tuple with the Fit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFit

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) SetFit(v string)`

SetFit sets Fit field to given value.

### HasFit

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) HasFit() bool`

HasFit returns a boolean if a field has been set.

### GetSourceType

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) GetSourceType() string`

GetSourceType returns the SourceType field if non-nil, zero value otherwise.

### GetSourceTypeOk

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) GetSourceTypeOk() (*string, bool)`

GetSourceTypeOk returns a tuple with the SourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceType

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) SetSourceType(v string)`

SetSourceType sets SourceType field to given value.

### HasSourceType

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) HasSourceType() bool`

HasSourceType returns a boolean if a field has been set.

### GetSources

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) GetSources() []FreeToolPlanPostingFrequencyResponseNetworksInnerSourcesInner`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) GetSourcesOk() (*[]FreeToolPlanPostingFrequencyResponseNetworksInnerSourcesInner, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) SetSources(v []FreeToolPlanPostingFrequencyResponseNetworksInnerSourcesInner)`

SetSources sets Sources field to given value.

### HasSources

`func (o *FreeToolPlanPostingFrequencyResponseNetworksInner) HasSources() bool`

HasSources returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


