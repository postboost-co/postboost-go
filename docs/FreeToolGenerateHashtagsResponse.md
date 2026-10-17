# FreeToolGenerateHashtagsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Hashtags** | Pointer to **[]string** | 5 to 10 hashtags (3 to 6 with network tiktok), best first. | [optional] 
**CreditsSpent** | Pointer to **int32** | AI credits this call took from the workspace: 1, or 0 for a cached result. | [optional] 
**Cached** | Pointer to **bool** | True when the same request was answered before (free). | [optional] 

## Methods

### NewFreeToolGenerateHashtagsResponse

`func NewFreeToolGenerateHashtagsResponse() *FreeToolGenerateHashtagsResponse`

NewFreeToolGenerateHashtagsResponse instantiates a new FreeToolGenerateHashtagsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateHashtagsResponseWithDefaults

`func NewFreeToolGenerateHashtagsResponseWithDefaults() *FreeToolGenerateHashtagsResponse`

NewFreeToolGenerateHashtagsResponseWithDefaults instantiates a new FreeToolGenerateHashtagsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHashtags

`func (o *FreeToolGenerateHashtagsResponse) GetHashtags() []string`

GetHashtags returns the Hashtags field if non-nil, zero value otherwise.

### GetHashtagsOk

`func (o *FreeToolGenerateHashtagsResponse) GetHashtagsOk() (*[]string, bool)`

GetHashtagsOk returns a tuple with the Hashtags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHashtags

`func (o *FreeToolGenerateHashtagsResponse) SetHashtags(v []string)`

SetHashtags sets Hashtags field to given value.

### HasHashtags

`func (o *FreeToolGenerateHashtagsResponse) HasHashtags() bool`

HasHashtags returns a boolean if a field has been set.

### GetCreditsSpent

`func (o *FreeToolGenerateHashtagsResponse) GetCreditsSpent() int32`

GetCreditsSpent returns the CreditsSpent field if non-nil, zero value otherwise.

### GetCreditsSpentOk

`func (o *FreeToolGenerateHashtagsResponse) GetCreditsSpentOk() (*int32, bool)`

GetCreditsSpentOk returns a tuple with the CreditsSpent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsSpent

`func (o *FreeToolGenerateHashtagsResponse) SetCreditsSpent(v int32)`

SetCreditsSpent sets CreditsSpent field to given value.

### HasCreditsSpent

`func (o *FreeToolGenerateHashtagsResponse) HasCreditsSpent() bool`

HasCreditsSpent returns a boolean if a field has been set.

### GetCached

`func (o *FreeToolGenerateHashtagsResponse) GetCached() bool`

GetCached returns the Cached field if non-nil, zero value otherwise.

### GetCachedOk

`func (o *FreeToolGenerateHashtagsResponse) GetCachedOk() (*bool, bool)`

GetCachedOk returns a tuple with the Cached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCached

`func (o *FreeToolGenerateHashtagsResponse) SetCached(v bool)`

SetCached sets Cached field to given value.

### HasCached

`func (o *FreeToolGenerateHashtagsResponse) HasCached() bool`

HasCached returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


