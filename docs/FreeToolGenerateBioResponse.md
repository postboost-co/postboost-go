# FreeToolGenerateBioResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Bios** | Pointer to **[]string** | Three to five different bios, each at most 150 characters as the character counter counts them (most emoji count as 2). | [optional] 
**CreditsSpent** | Pointer to **int32** | AI credits this call took from the workspace: 1, or 0 for a cached result. | [optional] 
**Cached** | Pointer to **bool** | True when the same request was answered before (free). | [optional] 

## Methods

### NewFreeToolGenerateBioResponse

`func NewFreeToolGenerateBioResponse() *FreeToolGenerateBioResponse`

NewFreeToolGenerateBioResponse instantiates a new FreeToolGenerateBioResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateBioResponseWithDefaults

`func NewFreeToolGenerateBioResponseWithDefaults() *FreeToolGenerateBioResponse`

NewFreeToolGenerateBioResponseWithDefaults instantiates a new FreeToolGenerateBioResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBios

`func (o *FreeToolGenerateBioResponse) GetBios() []string`

GetBios returns the Bios field if non-nil, zero value otherwise.

### GetBiosOk

`func (o *FreeToolGenerateBioResponse) GetBiosOk() (*[]string, bool)`

GetBiosOk returns a tuple with the Bios field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBios

`func (o *FreeToolGenerateBioResponse) SetBios(v []string)`

SetBios sets Bios field to given value.

### HasBios

`func (o *FreeToolGenerateBioResponse) HasBios() bool`

HasBios returns a boolean if a field has been set.

### GetCreditsSpent

`func (o *FreeToolGenerateBioResponse) GetCreditsSpent() int32`

GetCreditsSpent returns the CreditsSpent field if non-nil, zero value otherwise.

### GetCreditsSpentOk

`func (o *FreeToolGenerateBioResponse) GetCreditsSpentOk() (*int32, bool)`

GetCreditsSpentOk returns a tuple with the CreditsSpent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsSpent

`func (o *FreeToolGenerateBioResponse) SetCreditsSpent(v int32)`

SetCreditsSpent sets CreditsSpent field to given value.

### HasCreditsSpent

`func (o *FreeToolGenerateBioResponse) HasCreditsSpent() bool`

HasCreditsSpent returns a boolean if a field has been set.

### GetCached

`func (o *FreeToolGenerateBioResponse) GetCached() bool`

GetCached returns the Cached field if non-nil, zero value otherwise.

### GetCachedOk

`func (o *FreeToolGenerateBioResponse) GetCachedOk() (*bool, bool)`

GetCachedOk returns a tuple with the Cached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCached

`func (o *FreeToolGenerateBioResponse) SetCached(v bool)`

SetCached sets Cached field to given value.

### HasCached

`func (o *FreeToolGenerateBioResponse) HasCached() bool`

HasCached returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


