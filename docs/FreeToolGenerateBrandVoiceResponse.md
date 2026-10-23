# FreeToolGenerateBrandVoiceResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Voice** | Pointer to [**FreeToolGenerateBrandVoiceResponseVoice**](FreeToolGenerateBrandVoiceResponseVoice.md) |  | [optional] 
**Evidence** | Pointer to **map[string][]string** | Per trait key, up to 2 quotes from your posts that show it; only quotes found in your posts are kept, so a list can be empty. | [optional] 
**SystemPrompt** | Pointer to **string** | The system prompt PostBoost&#39;s AI uses for this voice; paste it into ChatGPT, Claude or your agent. | [optional] 
**Markdown** | Pointer to **string** | The voice as a Markdown guide with its quotes, ending with the system prompt. | [optional] 
**CreditsSpent** | Pointer to **int32** | AI credits this call took from the workspace: 1, or 0 for a cached result. | [optional] 
**Cached** | Pointer to **bool** | True when the same request was answered before (free). | [optional] 

## Methods

### NewFreeToolGenerateBrandVoiceResponse

`func NewFreeToolGenerateBrandVoiceResponse() *FreeToolGenerateBrandVoiceResponse`

NewFreeToolGenerateBrandVoiceResponse instantiates a new FreeToolGenerateBrandVoiceResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateBrandVoiceResponseWithDefaults

`func NewFreeToolGenerateBrandVoiceResponseWithDefaults() *FreeToolGenerateBrandVoiceResponse`

NewFreeToolGenerateBrandVoiceResponseWithDefaults instantiates a new FreeToolGenerateBrandVoiceResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVoice

`func (o *FreeToolGenerateBrandVoiceResponse) GetVoice() FreeToolGenerateBrandVoiceResponseVoice`

GetVoice returns the Voice field if non-nil, zero value otherwise.

### GetVoiceOk

`func (o *FreeToolGenerateBrandVoiceResponse) GetVoiceOk() (*FreeToolGenerateBrandVoiceResponseVoice, bool)`

GetVoiceOk returns a tuple with the Voice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoice

`func (o *FreeToolGenerateBrandVoiceResponse) SetVoice(v FreeToolGenerateBrandVoiceResponseVoice)`

SetVoice sets Voice field to given value.

### HasVoice

`func (o *FreeToolGenerateBrandVoiceResponse) HasVoice() bool`

HasVoice returns a boolean if a field has been set.

### GetEvidence

`func (o *FreeToolGenerateBrandVoiceResponse) GetEvidence() map[string][]string`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *FreeToolGenerateBrandVoiceResponse) GetEvidenceOk() (*map[string][]string, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *FreeToolGenerateBrandVoiceResponse) SetEvidence(v map[string][]string)`

SetEvidence sets Evidence field to given value.

### HasEvidence

`func (o *FreeToolGenerateBrandVoiceResponse) HasEvidence() bool`

HasEvidence returns a boolean if a field has been set.

### GetSystemPrompt

`func (o *FreeToolGenerateBrandVoiceResponse) GetSystemPrompt() string`

GetSystemPrompt returns the SystemPrompt field if non-nil, zero value otherwise.

### GetSystemPromptOk

`func (o *FreeToolGenerateBrandVoiceResponse) GetSystemPromptOk() (*string, bool)`

GetSystemPromptOk returns a tuple with the SystemPrompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemPrompt

`func (o *FreeToolGenerateBrandVoiceResponse) SetSystemPrompt(v string)`

SetSystemPrompt sets SystemPrompt field to given value.

### HasSystemPrompt

`func (o *FreeToolGenerateBrandVoiceResponse) HasSystemPrompt() bool`

HasSystemPrompt returns a boolean if a field has been set.

### GetMarkdown

`func (o *FreeToolGenerateBrandVoiceResponse) GetMarkdown() string`

GetMarkdown returns the Markdown field if non-nil, zero value otherwise.

### GetMarkdownOk

`func (o *FreeToolGenerateBrandVoiceResponse) GetMarkdownOk() (*string, bool)`

GetMarkdownOk returns a tuple with the Markdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarkdown

`func (o *FreeToolGenerateBrandVoiceResponse) SetMarkdown(v string)`

SetMarkdown sets Markdown field to given value.

### HasMarkdown

`func (o *FreeToolGenerateBrandVoiceResponse) HasMarkdown() bool`

HasMarkdown returns a boolean if a field has been set.

### GetCreditsSpent

`func (o *FreeToolGenerateBrandVoiceResponse) GetCreditsSpent() int32`

GetCreditsSpent returns the CreditsSpent field if non-nil, zero value otherwise.

### GetCreditsSpentOk

`func (o *FreeToolGenerateBrandVoiceResponse) GetCreditsSpentOk() (*int32, bool)`

GetCreditsSpentOk returns a tuple with the CreditsSpent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsSpent

`func (o *FreeToolGenerateBrandVoiceResponse) SetCreditsSpent(v int32)`

SetCreditsSpent sets CreditsSpent field to given value.

### HasCreditsSpent

`func (o *FreeToolGenerateBrandVoiceResponse) HasCreditsSpent() bool`

HasCreditsSpent returns a boolean if a field has been set.

### GetCached

`func (o *FreeToolGenerateBrandVoiceResponse) GetCached() bool`

GetCached returns the Cached field if non-nil, zero value otherwise.

### GetCachedOk

`func (o *FreeToolGenerateBrandVoiceResponse) GetCachedOk() (*bool, bool)`

GetCachedOk returns a tuple with the Cached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCached

`func (o *FreeToolGenerateBrandVoiceResponse) SetCached(v bool)`

SetCached sets Cached field to given value.

### HasCached

`func (o *FreeToolGenerateBrandVoiceResponse) HasCached() bool`

HasCached returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


