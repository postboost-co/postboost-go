# FreeToolGenerateCaptionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** | What the post is about. | 
**Tone** | Pointer to **string** |  | [optional] [default to "friendly"]
**Length** | Pointer to **string** | short: 10-20 words, medium: 25-40, long: 45-60. | [optional] [default to "medium"]
**Emoji** | Pointer to **bool** | Use a few fitting emoji. | [optional] [default to true]
**Hashtags** | Pointer to **bool** | End each caption with 3-5 relevant hashtags. | [optional] [default to false]
**Network** | Pointer to **string** | The network the text is written for. | [optional] [default to "instagram"]
**Workspace** | Pointer to **string** | UUID of the workspace whose AI credits pay for the call. Default: your active workspace (a scoped API key: its own workspace). | [optional] 
**Format** | Pointer to **string** | caption: short captions (default). post: long-form posts of 300-600, 600-1,300 or 1,300-2,000 characters by &#x60;length&#x60;, with at most 3 hashtags; network linkedin only. | [optional] [default to "caption"]

## Methods

### NewFreeToolGenerateCaptionRequest

`func NewFreeToolGenerateCaptionRequest(text string, ) *FreeToolGenerateCaptionRequest`

NewFreeToolGenerateCaptionRequest instantiates a new FreeToolGenerateCaptionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateCaptionRequestWithDefaults

`func NewFreeToolGenerateCaptionRequestWithDefaults() *FreeToolGenerateCaptionRequest`

NewFreeToolGenerateCaptionRequestWithDefaults instantiates a new FreeToolGenerateCaptionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolGenerateCaptionRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolGenerateCaptionRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolGenerateCaptionRequest) SetText(v string)`

SetText sets Text field to given value.


### GetTone

`func (o *FreeToolGenerateCaptionRequest) GetTone() string`

GetTone returns the Tone field if non-nil, zero value otherwise.

### GetToneOk

`func (o *FreeToolGenerateCaptionRequest) GetToneOk() (*string, bool)`

GetToneOk returns a tuple with the Tone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTone

`func (o *FreeToolGenerateCaptionRequest) SetTone(v string)`

SetTone sets Tone field to given value.

### HasTone

`func (o *FreeToolGenerateCaptionRequest) HasTone() bool`

HasTone returns a boolean if a field has been set.

### GetLength

`func (o *FreeToolGenerateCaptionRequest) GetLength() string`

GetLength returns the Length field if non-nil, zero value otherwise.

### GetLengthOk

`func (o *FreeToolGenerateCaptionRequest) GetLengthOk() (*string, bool)`

GetLengthOk returns a tuple with the Length field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLength

`func (o *FreeToolGenerateCaptionRequest) SetLength(v string)`

SetLength sets Length field to given value.

### HasLength

`func (o *FreeToolGenerateCaptionRequest) HasLength() bool`

HasLength returns a boolean if a field has been set.

### GetEmoji

`func (o *FreeToolGenerateCaptionRequest) GetEmoji() bool`

GetEmoji returns the Emoji field if non-nil, zero value otherwise.

### GetEmojiOk

`func (o *FreeToolGenerateCaptionRequest) GetEmojiOk() (*bool, bool)`

GetEmojiOk returns a tuple with the Emoji field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmoji

`func (o *FreeToolGenerateCaptionRequest) SetEmoji(v bool)`

SetEmoji sets Emoji field to given value.

### HasEmoji

`func (o *FreeToolGenerateCaptionRequest) HasEmoji() bool`

HasEmoji returns a boolean if a field has been set.

### GetHashtags

`func (o *FreeToolGenerateCaptionRequest) GetHashtags() bool`

GetHashtags returns the Hashtags field if non-nil, zero value otherwise.

### GetHashtagsOk

`func (o *FreeToolGenerateCaptionRequest) GetHashtagsOk() (*bool, bool)`

GetHashtagsOk returns a tuple with the Hashtags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHashtags

`func (o *FreeToolGenerateCaptionRequest) SetHashtags(v bool)`

SetHashtags sets Hashtags field to given value.

### HasHashtags

`func (o *FreeToolGenerateCaptionRequest) HasHashtags() bool`

HasHashtags returns a boolean if a field has been set.

### GetNetwork

`func (o *FreeToolGenerateCaptionRequest) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *FreeToolGenerateCaptionRequest) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *FreeToolGenerateCaptionRequest) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *FreeToolGenerateCaptionRequest) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetWorkspace

`func (o *FreeToolGenerateCaptionRequest) GetWorkspace() string`

GetWorkspace returns the Workspace field if non-nil, zero value otherwise.

### GetWorkspaceOk

`func (o *FreeToolGenerateCaptionRequest) GetWorkspaceOk() (*string, bool)`

GetWorkspaceOk returns a tuple with the Workspace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspace

`func (o *FreeToolGenerateCaptionRequest) SetWorkspace(v string)`

SetWorkspace sets Workspace field to given value.

### HasWorkspace

`func (o *FreeToolGenerateCaptionRequest) HasWorkspace() bool`

HasWorkspace returns a boolean if a field has been set.

### GetFormat

`func (o *FreeToolGenerateCaptionRequest) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *FreeToolGenerateCaptionRequest) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *FreeToolGenerateCaptionRequest) SetFormat(v string)`

SetFormat sets Format field to given value.

### HasFormat

`func (o *FreeToolGenerateCaptionRequest) HasFormat() bool`

HasFormat returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


