# FreeToolGenerateBioRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** | What you or your brand do, and for whom. | 
**Tone** | Pointer to **string** |  | [optional] [default to "friendly"]
**Emoji** | Pointer to **bool** | Use one or two fitting emoji. | [optional] [default to true]
**Cta** | Pointer to **bool** | End with a short call to action, such as the link in bio. | [optional] [default to true]
**Network** | Pointer to **string** | The network the bio is written for (Instagram for now). | [optional] [default to "instagram"]
**Workspace** | Pointer to **string** | UUID of the workspace whose AI credits pay for the call. Default: your active workspace (a scoped API key: its own workspace). | [optional] 

## Methods

### NewFreeToolGenerateBioRequest

`func NewFreeToolGenerateBioRequest(text string, ) *FreeToolGenerateBioRequest`

NewFreeToolGenerateBioRequest instantiates a new FreeToolGenerateBioRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateBioRequestWithDefaults

`func NewFreeToolGenerateBioRequestWithDefaults() *FreeToolGenerateBioRequest`

NewFreeToolGenerateBioRequestWithDefaults instantiates a new FreeToolGenerateBioRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolGenerateBioRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolGenerateBioRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolGenerateBioRequest) SetText(v string)`

SetText sets Text field to given value.


### GetTone

`func (o *FreeToolGenerateBioRequest) GetTone() string`

GetTone returns the Tone field if non-nil, zero value otherwise.

### GetToneOk

`func (o *FreeToolGenerateBioRequest) GetToneOk() (*string, bool)`

GetToneOk returns a tuple with the Tone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTone

`func (o *FreeToolGenerateBioRequest) SetTone(v string)`

SetTone sets Tone field to given value.

### HasTone

`func (o *FreeToolGenerateBioRequest) HasTone() bool`

HasTone returns a boolean if a field has been set.

### GetEmoji

`func (o *FreeToolGenerateBioRequest) GetEmoji() bool`

GetEmoji returns the Emoji field if non-nil, zero value otherwise.

### GetEmojiOk

`func (o *FreeToolGenerateBioRequest) GetEmojiOk() (*bool, bool)`

GetEmojiOk returns a tuple with the Emoji field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmoji

`func (o *FreeToolGenerateBioRequest) SetEmoji(v bool)`

SetEmoji sets Emoji field to given value.

### HasEmoji

`func (o *FreeToolGenerateBioRequest) HasEmoji() bool`

HasEmoji returns a boolean if a field has been set.

### GetCta

`func (o *FreeToolGenerateBioRequest) GetCta() bool`

GetCta returns the Cta field if non-nil, zero value otherwise.

### GetCtaOk

`func (o *FreeToolGenerateBioRequest) GetCtaOk() (*bool, bool)`

GetCtaOk returns a tuple with the Cta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCta

`func (o *FreeToolGenerateBioRequest) SetCta(v bool)`

SetCta sets Cta field to given value.

### HasCta

`func (o *FreeToolGenerateBioRequest) HasCta() bool`

HasCta returns a boolean if a field has been set.

### GetNetwork

`func (o *FreeToolGenerateBioRequest) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *FreeToolGenerateBioRequest) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *FreeToolGenerateBioRequest) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *FreeToolGenerateBioRequest) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetWorkspace

`func (o *FreeToolGenerateBioRequest) GetWorkspace() string`

GetWorkspace returns the Workspace field if non-nil, zero value otherwise.

### GetWorkspaceOk

`func (o *FreeToolGenerateBioRequest) GetWorkspaceOk() (*string, bool)`

GetWorkspaceOk returns a tuple with the Workspace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspace

`func (o *FreeToolGenerateBioRequest) SetWorkspace(v string)`

SetWorkspace sets Workspace field to given value.

### HasWorkspace

`func (o *FreeToolGenerateBioRequest) HasWorkspace() bool`

HasWorkspace returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


