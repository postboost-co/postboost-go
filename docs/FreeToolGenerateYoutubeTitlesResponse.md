# FreeToolGenerateYoutubeTitlesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Titles** | Pointer to **[]string** | Three to five different titles, each at most 100 characters, with the main keyword early, no &#x60;&lt;&#x60; or &#x60;&gt;&#x60; and not in capitals. | [optional] 
**CreditsSpent** | Pointer to **int32** | AI credits this call took from the workspace: 1, or 0 for a cached result. | [optional] 
**Cached** | Pointer to **bool** | True when the same request was answered before (free). | [optional] 

## Methods

### NewFreeToolGenerateYoutubeTitlesResponse

`func NewFreeToolGenerateYoutubeTitlesResponse() *FreeToolGenerateYoutubeTitlesResponse`

NewFreeToolGenerateYoutubeTitlesResponse instantiates a new FreeToolGenerateYoutubeTitlesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateYoutubeTitlesResponseWithDefaults

`func NewFreeToolGenerateYoutubeTitlesResponseWithDefaults() *FreeToolGenerateYoutubeTitlesResponse`

NewFreeToolGenerateYoutubeTitlesResponseWithDefaults instantiates a new FreeToolGenerateYoutubeTitlesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitles

`func (o *FreeToolGenerateYoutubeTitlesResponse) GetTitles() []string`

GetTitles returns the Titles field if non-nil, zero value otherwise.

### GetTitlesOk

`func (o *FreeToolGenerateYoutubeTitlesResponse) GetTitlesOk() (*[]string, bool)`

GetTitlesOk returns a tuple with the Titles field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitles

`func (o *FreeToolGenerateYoutubeTitlesResponse) SetTitles(v []string)`

SetTitles sets Titles field to given value.

### HasTitles

`func (o *FreeToolGenerateYoutubeTitlesResponse) HasTitles() bool`

HasTitles returns a boolean if a field has been set.

### GetCreditsSpent

`func (o *FreeToolGenerateYoutubeTitlesResponse) GetCreditsSpent() int32`

GetCreditsSpent returns the CreditsSpent field if non-nil, zero value otherwise.

### GetCreditsSpentOk

`func (o *FreeToolGenerateYoutubeTitlesResponse) GetCreditsSpentOk() (*int32, bool)`

GetCreditsSpentOk returns a tuple with the CreditsSpent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsSpent

`func (o *FreeToolGenerateYoutubeTitlesResponse) SetCreditsSpent(v int32)`

SetCreditsSpent sets CreditsSpent field to given value.

### HasCreditsSpent

`func (o *FreeToolGenerateYoutubeTitlesResponse) HasCreditsSpent() bool`

HasCreditsSpent returns a boolean if a field has been set.

### GetCached

`func (o *FreeToolGenerateYoutubeTitlesResponse) GetCached() bool`

GetCached returns the Cached field if non-nil, zero value otherwise.

### GetCachedOk

`func (o *FreeToolGenerateYoutubeTitlesResponse) GetCachedOk() (*bool, bool)`

GetCachedOk returns a tuple with the Cached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCached

`func (o *FreeToolGenerateYoutubeTitlesResponse) SetCached(v bool)`

SetCached sets Cached field to given value.

### HasCached

`func (o *FreeToolGenerateYoutubeTitlesResponse) HasCached() bool`

HasCached returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


