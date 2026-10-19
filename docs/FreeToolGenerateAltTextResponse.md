# FreeToolGenerateAltTextResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AltText** | Pointer to **string** | The alt text, within the chosen length. | [optional] 
**ShortAltText** | Pointer to **string** | A shorter alternative. | [optional] 
**CreditsSpent** | Pointer to **int32** | AI credits this call took from the workspace: 1, or 0 for a cached result. | [optional] 
**Cached** | Pointer to **bool** | True when the same request was answered before (free). | [optional] 

## Methods

### NewFreeToolGenerateAltTextResponse

`func NewFreeToolGenerateAltTextResponse() *FreeToolGenerateAltTextResponse`

NewFreeToolGenerateAltTextResponse instantiates a new FreeToolGenerateAltTextResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateAltTextResponseWithDefaults

`func NewFreeToolGenerateAltTextResponseWithDefaults() *FreeToolGenerateAltTextResponse`

NewFreeToolGenerateAltTextResponseWithDefaults instantiates a new FreeToolGenerateAltTextResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAltText

`func (o *FreeToolGenerateAltTextResponse) GetAltText() string`

GetAltText returns the AltText field if non-nil, zero value otherwise.

### GetAltTextOk

`func (o *FreeToolGenerateAltTextResponse) GetAltTextOk() (*string, bool)`

GetAltTextOk returns a tuple with the AltText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAltText

`func (o *FreeToolGenerateAltTextResponse) SetAltText(v string)`

SetAltText sets AltText field to given value.

### HasAltText

`func (o *FreeToolGenerateAltTextResponse) HasAltText() bool`

HasAltText returns a boolean if a field has been set.

### GetShortAltText

`func (o *FreeToolGenerateAltTextResponse) GetShortAltText() string`

GetShortAltText returns the ShortAltText field if non-nil, zero value otherwise.

### GetShortAltTextOk

`func (o *FreeToolGenerateAltTextResponse) GetShortAltTextOk() (*string, bool)`

GetShortAltTextOk returns a tuple with the ShortAltText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortAltText

`func (o *FreeToolGenerateAltTextResponse) SetShortAltText(v string)`

SetShortAltText sets ShortAltText field to given value.

### HasShortAltText

`func (o *FreeToolGenerateAltTextResponse) HasShortAltText() bool`

HasShortAltText returns a boolean if a field has been set.

### GetCreditsSpent

`func (o *FreeToolGenerateAltTextResponse) GetCreditsSpent() int32`

GetCreditsSpent returns the CreditsSpent field if non-nil, zero value otherwise.

### GetCreditsSpentOk

`func (o *FreeToolGenerateAltTextResponse) GetCreditsSpentOk() (*int32, bool)`

GetCreditsSpentOk returns a tuple with the CreditsSpent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsSpent

`func (o *FreeToolGenerateAltTextResponse) SetCreditsSpent(v int32)`

SetCreditsSpent sets CreditsSpent field to given value.

### HasCreditsSpent

`func (o *FreeToolGenerateAltTextResponse) HasCreditsSpent() bool`

HasCreditsSpent returns a boolean if a field has been set.

### GetCached

`func (o *FreeToolGenerateAltTextResponse) GetCached() bool`

GetCached returns the Cached field if non-nil, zero value otherwise.

### GetCachedOk

`func (o *FreeToolGenerateAltTextResponse) GetCachedOk() (*bool, bool)`

GetCachedOk returns a tuple with the Cached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCached

`func (o *FreeToolGenerateAltTextResponse) SetCached(v bool)`

SetCached sets Cached field to given value.

### HasCached

`func (o *FreeToolGenerateAltTextResponse) HasCached() bool`

HasCached returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


