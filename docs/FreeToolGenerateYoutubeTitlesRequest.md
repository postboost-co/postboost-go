# FreeToolGenerateYoutubeTitlesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** | What the video is about. | 
**Style** | Pointer to **string** | how-to (\&quot;How to ...\&quot;), listicle (\&quot;7 ways to ...\&quot;), question, story (first person) or news. | [optional] [default to "how-to"]
**Workspace** | Pointer to **string** | UUID of the workspace whose AI credits pay for the call. Default: your active workspace (a scoped API key: its own workspace). | [optional] 
**Transcript** | Pointer to **string** | Optional: your video&#39;s captions (.srt, .vtt or the Show transcript text) as context; timestamps are removed and the first 6,000 characters are used. | [optional] 

## Methods

### NewFreeToolGenerateYoutubeTitlesRequest

`func NewFreeToolGenerateYoutubeTitlesRequest(text string, ) *FreeToolGenerateYoutubeTitlesRequest`

NewFreeToolGenerateYoutubeTitlesRequest instantiates a new FreeToolGenerateYoutubeTitlesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateYoutubeTitlesRequestWithDefaults

`func NewFreeToolGenerateYoutubeTitlesRequestWithDefaults() *FreeToolGenerateYoutubeTitlesRequest`

NewFreeToolGenerateYoutubeTitlesRequestWithDefaults instantiates a new FreeToolGenerateYoutubeTitlesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolGenerateYoutubeTitlesRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolGenerateYoutubeTitlesRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolGenerateYoutubeTitlesRequest) SetText(v string)`

SetText sets Text field to given value.


### GetStyle

`func (o *FreeToolGenerateYoutubeTitlesRequest) GetStyle() string`

GetStyle returns the Style field if non-nil, zero value otherwise.

### GetStyleOk

`func (o *FreeToolGenerateYoutubeTitlesRequest) GetStyleOk() (*string, bool)`

GetStyleOk returns a tuple with the Style field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStyle

`func (o *FreeToolGenerateYoutubeTitlesRequest) SetStyle(v string)`

SetStyle sets Style field to given value.

### HasStyle

`func (o *FreeToolGenerateYoutubeTitlesRequest) HasStyle() bool`

HasStyle returns a boolean if a field has been set.

### GetWorkspace

`func (o *FreeToolGenerateYoutubeTitlesRequest) GetWorkspace() string`

GetWorkspace returns the Workspace field if non-nil, zero value otherwise.

### GetWorkspaceOk

`func (o *FreeToolGenerateYoutubeTitlesRequest) GetWorkspaceOk() (*string, bool)`

GetWorkspaceOk returns a tuple with the Workspace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspace

`func (o *FreeToolGenerateYoutubeTitlesRequest) SetWorkspace(v string)`

SetWorkspace sets Workspace field to given value.

### HasWorkspace

`func (o *FreeToolGenerateYoutubeTitlesRequest) HasWorkspace() bool`

HasWorkspace returns a boolean if a field has been set.

### GetTranscript

`func (o *FreeToolGenerateYoutubeTitlesRequest) GetTranscript() string`

GetTranscript returns the Transcript field if non-nil, zero value otherwise.

### GetTranscriptOk

`func (o *FreeToolGenerateYoutubeTitlesRequest) GetTranscriptOk() (*string, bool)`

GetTranscriptOk returns a tuple with the Transcript field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTranscript

`func (o *FreeToolGenerateYoutubeTitlesRequest) SetTranscript(v string)`

SetTranscript sets Transcript field to given value.

### HasTranscript

`func (o *FreeToolGenerateYoutubeTitlesRequest) HasTranscript() bool`

HasTranscript returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


