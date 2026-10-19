# FreeToolGenerateYoutubeDescriptionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Descriptions** | Pointer to **[]string** | Two or three different descriptions, each under 5,000 UTF-8 bytes (YouTube&#39;s limit) and without &#x60;&lt;&#x60; or &#x60;&gt;&#x60;. Links are &#x60;[link]&#x60; placeholders. | [optional] 
**CreditsSpent** | Pointer to **int32** | AI credits this call took from the workspace: 1, or 0 for a cached result. | [optional] 
**Cached** | Pointer to **bool** | True when the same request was answered before (free). | [optional] 

## Methods

### NewFreeToolGenerateYoutubeDescriptionResponse

`func NewFreeToolGenerateYoutubeDescriptionResponse() *FreeToolGenerateYoutubeDescriptionResponse`

NewFreeToolGenerateYoutubeDescriptionResponse instantiates a new FreeToolGenerateYoutubeDescriptionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateYoutubeDescriptionResponseWithDefaults

`func NewFreeToolGenerateYoutubeDescriptionResponseWithDefaults() *FreeToolGenerateYoutubeDescriptionResponse`

NewFreeToolGenerateYoutubeDescriptionResponseWithDefaults instantiates a new FreeToolGenerateYoutubeDescriptionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescriptions

`func (o *FreeToolGenerateYoutubeDescriptionResponse) GetDescriptions() []string`

GetDescriptions returns the Descriptions field if non-nil, zero value otherwise.

### GetDescriptionsOk

`func (o *FreeToolGenerateYoutubeDescriptionResponse) GetDescriptionsOk() (*[]string, bool)`

GetDescriptionsOk returns a tuple with the Descriptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescriptions

`func (o *FreeToolGenerateYoutubeDescriptionResponse) SetDescriptions(v []string)`

SetDescriptions sets Descriptions field to given value.

### HasDescriptions

`func (o *FreeToolGenerateYoutubeDescriptionResponse) HasDescriptions() bool`

HasDescriptions returns a boolean if a field has been set.

### GetCreditsSpent

`func (o *FreeToolGenerateYoutubeDescriptionResponse) GetCreditsSpent() int32`

GetCreditsSpent returns the CreditsSpent field if non-nil, zero value otherwise.

### GetCreditsSpentOk

`func (o *FreeToolGenerateYoutubeDescriptionResponse) GetCreditsSpentOk() (*int32, bool)`

GetCreditsSpentOk returns a tuple with the CreditsSpent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsSpent

`func (o *FreeToolGenerateYoutubeDescriptionResponse) SetCreditsSpent(v int32)`

SetCreditsSpent sets CreditsSpent field to given value.

### HasCreditsSpent

`func (o *FreeToolGenerateYoutubeDescriptionResponse) HasCreditsSpent() bool`

HasCreditsSpent returns a boolean if a field has been set.

### GetCached

`func (o *FreeToolGenerateYoutubeDescriptionResponse) GetCached() bool`

GetCached returns the Cached field if non-nil, zero value otherwise.

### GetCachedOk

`func (o *FreeToolGenerateYoutubeDescriptionResponse) GetCachedOk() (*bool, bool)`

GetCachedOk returns a tuple with the Cached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCached

`func (o *FreeToolGenerateYoutubeDescriptionResponse) SetCached(v bool)`

SetCached sets Cached field to given value.

### HasCached

`func (o *FreeToolGenerateYoutubeDescriptionResponse) HasCached() bool`

HasCached returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


