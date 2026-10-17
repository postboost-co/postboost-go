# FreeToolCalculateInfluencerRateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Network** | **string** | LinkedIn is not offered: no primary source for its rates. | 
**Followers** | **int32** | Followers (subscribers on YouTube). Sets the tier. | 
**Deliverable** | Pointer to **string** | Instagram: post (default), reel, carousel. TikTok: video. X and Facebook: post. YouTube: integration (default), dedicated, short. | [optional] 
**AvgViews** | Pointer to **int32** | Expected views of the deliverable. Required on YouTube, which is priced per 1,000 views; with cpm_usd it gives your own CPM estimate on any network. | [optional] 
**CpmUsd** | Pointer to **int32** | Your own price per 1,000 views, in whole USD, for the CPM estimate. | [optional] 
**UsageRightsMonths** | Pointer to **int32** | Months the brand may reuse the content. | [optional] [default to 0]
**Exclusivity** | Pointer to **bool** | The creator agrees not to work with competitors for the campaign. | [optional] [default to false]

## Methods

### NewFreeToolCalculateInfluencerRateRequest

`func NewFreeToolCalculateInfluencerRateRequest(network string, followers int32, ) *FreeToolCalculateInfluencerRateRequest`

NewFreeToolCalculateInfluencerRateRequest instantiates a new FreeToolCalculateInfluencerRateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCalculateInfluencerRateRequestWithDefaults

`func NewFreeToolCalculateInfluencerRateRequestWithDefaults() *FreeToolCalculateInfluencerRateRequest`

NewFreeToolCalculateInfluencerRateRequestWithDefaults instantiates a new FreeToolCalculateInfluencerRateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNetwork

`func (o *FreeToolCalculateInfluencerRateRequest) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *FreeToolCalculateInfluencerRateRequest) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *FreeToolCalculateInfluencerRateRequest) SetNetwork(v string)`

SetNetwork sets Network field to given value.


### GetFollowers

`func (o *FreeToolCalculateInfluencerRateRequest) GetFollowers() int32`

GetFollowers returns the Followers field if non-nil, zero value otherwise.

### GetFollowersOk

`func (o *FreeToolCalculateInfluencerRateRequest) GetFollowersOk() (*int32, bool)`

GetFollowersOk returns a tuple with the Followers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFollowers

`func (o *FreeToolCalculateInfluencerRateRequest) SetFollowers(v int32)`

SetFollowers sets Followers field to given value.


### GetDeliverable

`func (o *FreeToolCalculateInfluencerRateRequest) GetDeliverable() string`

GetDeliverable returns the Deliverable field if non-nil, zero value otherwise.

### GetDeliverableOk

`func (o *FreeToolCalculateInfluencerRateRequest) GetDeliverableOk() (*string, bool)`

GetDeliverableOk returns a tuple with the Deliverable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliverable

`func (o *FreeToolCalculateInfluencerRateRequest) SetDeliverable(v string)`

SetDeliverable sets Deliverable field to given value.

### HasDeliverable

`func (o *FreeToolCalculateInfluencerRateRequest) HasDeliverable() bool`

HasDeliverable returns a boolean if a field has been set.

### GetAvgViews

`func (o *FreeToolCalculateInfluencerRateRequest) GetAvgViews() int32`

GetAvgViews returns the AvgViews field if non-nil, zero value otherwise.

### GetAvgViewsOk

`func (o *FreeToolCalculateInfluencerRateRequest) GetAvgViewsOk() (*int32, bool)`

GetAvgViewsOk returns a tuple with the AvgViews field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgViews

`func (o *FreeToolCalculateInfluencerRateRequest) SetAvgViews(v int32)`

SetAvgViews sets AvgViews field to given value.

### HasAvgViews

`func (o *FreeToolCalculateInfluencerRateRequest) HasAvgViews() bool`

HasAvgViews returns a boolean if a field has been set.

### GetCpmUsd

`func (o *FreeToolCalculateInfluencerRateRequest) GetCpmUsd() int32`

GetCpmUsd returns the CpmUsd field if non-nil, zero value otherwise.

### GetCpmUsdOk

`func (o *FreeToolCalculateInfluencerRateRequest) GetCpmUsdOk() (*int32, bool)`

GetCpmUsdOk returns a tuple with the CpmUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCpmUsd

`func (o *FreeToolCalculateInfluencerRateRequest) SetCpmUsd(v int32)`

SetCpmUsd sets CpmUsd field to given value.

### HasCpmUsd

`func (o *FreeToolCalculateInfluencerRateRequest) HasCpmUsd() bool`

HasCpmUsd returns a boolean if a field has been set.

### GetUsageRightsMonths

`func (o *FreeToolCalculateInfluencerRateRequest) GetUsageRightsMonths() int32`

GetUsageRightsMonths returns the UsageRightsMonths field if non-nil, zero value otherwise.

### GetUsageRightsMonthsOk

`func (o *FreeToolCalculateInfluencerRateRequest) GetUsageRightsMonthsOk() (*int32, bool)`

GetUsageRightsMonthsOk returns a tuple with the UsageRightsMonths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageRightsMonths

`func (o *FreeToolCalculateInfluencerRateRequest) SetUsageRightsMonths(v int32)`

SetUsageRightsMonths sets UsageRightsMonths field to given value.

### HasUsageRightsMonths

`func (o *FreeToolCalculateInfluencerRateRequest) HasUsageRightsMonths() bool`

HasUsageRightsMonths returns a boolean if a field has been set.

### GetExclusivity

`func (o *FreeToolCalculateInfluencerRateRequest) GetExclusivity() bool`

GetExclusivity returns the Exclusivity field if non-nil, zero value otherwise.

### GetExclusivityOk

`func (o *FreeToolCalculateInfluencerRateRequest) GetExclusivityOk() (*bool, bool)`

GetExclusivityOk returns a tuple with the Exclusivity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExclusivity

`func (o *FreeToolCalculateInfluencerRateRequest) SetExclusivity(v bool)`

SetExclusivity sets Exclusivity field to given value.

### HasExclusivity

`func (o *FreeToolCalculateInfluencerRateRequest) HasExclusivity() bool`

HasExclusivity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


