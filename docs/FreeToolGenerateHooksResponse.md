# FreeToolGenerateHooksResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Hooks** | Pointer to [**[]FreeToolGenerateHooksResponseHooksInner**](FreeToolGenerateHooksResponseHooksInner.md) | &#x60;count&#x60; hooks in several styles. | [optional] 
**Notice** | Pointer to **string** | Only while AI is switched off: the hooks are templates from the free library (getHookTemplates) with the topic filled in, free of charge. | [optional] 
**CreditsSpent** | Pointer to **int32** | AI credits this call took from the workspace: 1, or 0 for a cached result. | [optional] 
**Cached** | Pointer to **bool** | True when the same request was answered before (free). | [optional] 

## Methods

### NewFreeToolGenerateHooksResponse

`func NewFreeToolGenerateHooksResponse() *FreeToolGenerateHooksResponse`

NewFreeToolGenerateHooksResponse instantiates a new FreeToolGenerateHooksResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateHooksResponseWithDefaults

`func NewFreeToolGenerateHooksResponseWithDefaults() *FreeToolGenerateHooksResponse`

NewFreeToolGenerateHooksResponseWithDefaults instantiates a new FreeToolGenerateHooksResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHooks

`func (o *FreeToolGenerateHooksResponse) GetHooks() []FreeToolGenerateHooksResponseHooksInner`

GetHooks returns the Hooks field if non-nil, zero value otherwise.

### GetHooksOk

`func (o *FreeToolGenerateHooksResponse) GetHooksOk() (*[]FreeToolGenerateHooksResponseHooksInner, bool)`

GetHooksOk returns a tuple with the Hooks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHooks

`func (o *FreeToolGenerateHooksResponse) SetHooks(v []FreeToolGenerateHooksResponseHooksInner)`

SetHooks sets Hooks field to given value.

### HasHooks

`func (o *FreeToolGenerateHooksResponse) HasHooks() bool`

HasHooks returns a boolean if a field has been set.

### GetNotice

`func (o *FreeToolGenerateHooksResponse) GetNotice() string`

GetNotice returns the Notice field if non-nil, zero value otherwise.

### GetNoticeOk

`func (o *FreeToolGenerateHooksResponse) GetNoticeOk() (*string, bool)`

GetNoticeOk returns a tuple with the Notice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotice

`func (o *FreeToolGenerateHooksResponse) SetNotice(v string)`

SetNotice sets Notice field to given value.

### HasNotice

`func (o *FreeToolGenerateHooksResponse) HasNotice() bool`

HasNotice returns a boolean if a field has been set.

### GetCreditsSpent

`func (o *FreeToolGenerateHooksResponse) GetCreditsSpent() int32`

GetCreditsSpent returns the CreditsSpent field if non-nil, zero value otherwise.

### GetCreditsSpentOk

`func (o *FreeToolGenerateHooksResponse) GetCreditsSpentOk() (*int32, bool)`

GetCreditsSpentOk returns a tuple with the CreditsSpent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsSpent

`func (o *FreeToolGenerateHooksResponse) SetCreditsSpent(v int32)`

SetCreditsSpent sets CreditsSpent field to given value.

### HasCreditsSpent

`func (o *FreeToolGenerateHooksResponse) HasCreditsSpent() bool`

HasCreditsSpent returns a boolean if a field has been set.

### GetCached

`func (o *FreeToolGenerateHooksResponse) GetCached() bool`

GetCached returns the Cached field if non-nil, zero value otherwise.

### GetCachedOk

`func (o *FreeToolGenerateHooksResponse) GetCachedOk() (*bool, bool)`

GetCachedOk returns a tuple with the Cached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCached

`func (o *FreeToolGenerateHooksResponse) SetCached(v bool)`

SetCached sets Cached field to given value.

### HasCached

`func (o *FreeToolGenerateHooksResponse) HasCached() bool`

HasCached returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


