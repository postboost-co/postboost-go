# FreeToolGenerateCaptionResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Captions** | Pointer to **[]string** | Three different captions, each within the network&#39;s text limit (at most 2,200 characters). | [optional] 
**CreditsSpent** | Pointer to **int32** | AI credits this call took from the workspace: 1, or 0 for a cached result. | [optional] 
**Cached** | Pointer to **bool** | True when the same request was answered before (free). | [optional] 

## Methods

### NewFreeToolGenerateCaptionResponse

`func NewFreeToolGenerateCaptionResponse() *FreeToolGenerateCaptionResponse`

NewFreeToolGenerateCaptionResponse instantiates a new FreeToolGenerateCaptionResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateCaptionResponseWithDefaults

`func NewFreeToolGenerateCaptionResponseWithDefaults() *FreeToolGenerateCaptionResponse`

NewFreeToolGenerateCaptionResponseWithDefaults instantiates a new FreeToolGenerateCaptionResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCaptions

`func (o *FreeToolGenerateCaptionResponse) GetCaptions() []string`

GetCaptions returns the Captions field if non-nil, zero value otherwise.

### GetCaptionsOk

`func (o *FreeToolGenerateCaptionResponse) GetCaptionsOk() (*[]string, bool)`

GetCaptionsOk returns a tuple with the Captions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCaptions

`func (o *FreeToolGenerateCaptionResponse) SetCaptions(v []string)`

SetCaptions sets Captions field to given value.

### HasCaptions

`func (o *FreeToolGenerateCaptionResponse) HasCaptions() bool`

HasCaptions returns a boolean if a field has been set.

### GetCreditsSpent

`func (o *FreeToolGenerateCaptionResponse) GetCreditsSpent() int32`

GetCreditsSpent returns the CreditsSpent field if non-nil, zero value otherwise.

### GetCreditsSpentOk

`func (o *FreeToolGenerateCaptionResponse) GetCreditsSpentOk() (*int32, bool)`

GetCreditsSpentOk returns a tuple with the CreditsSpent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsSpent

`func (o *FreeToolGenerateCaptionResponse) SetCreditsSpent(v int32)`

SetCreditsSpent sets CreditsSpent field to given value.

### HasCreditsSpent

`func (o *FreeToolGenerateCaptionResponse) HasCreditsSpent() bool`

HasCreditsSpent returns a boolean if a field has been set.

### GetCached

`func (o *FreeToolGenerateCaptionResponse) GetCached() bool`

GetCached returns the Cached field if non-nil, zero value otherwise.

### GetCachedOk

`func (o *FreeToolGenerateCaptionResponse) GetCachedOk() (*bool, bool)`

GetCachedOk returns a tuple with the Cached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCached

`func (o *FreeToolGenerateCaptionResponse) SetCached(v bool)`

SetCached sets Cached field to given value.

### HasCached

`func (o *FreeToolGenerateCaptionResponse) HasCached() bool`

HasCached returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


