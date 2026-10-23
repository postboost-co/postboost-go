# FreeToolGenerateYoutubeDescriptionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** | What the video is about: a summary or the main points. | 
**Keywords** | Pointer to **string** | Optional search keywords to use naturally, comma separated. | [optional] 
**Chapters** | Pointer to **bool** | Add a chapters block after the first paragraph. | [optional] [default to false]
**ChapterLines** | Pointer to **[]string** | Your chapters as &#x60;m:ss Title&#x60; lines, the first at 0:00. Used verbatim when &#x60;chapters&#x60; is true; without them the block has fill-in placeholders. Timestamps are never generated. | [optional] 
**Cta** | Pointer to **string** | The closing call to action: subscribe, link (a [link] placeholder) or none. | [optional] [default to "subscribe"]
**Workspace** | Pointer to **string** | UUID of the workspace whose AI credits pay for the call. Default: your active workspace (a scoped API key: its own workspace). | [optional] 
**Transcript** | Pointer to **string** | Optional: your video&#39;s captions (.srt, .vtt or the Show transcript text) as context; timestamps are removed and the first 6,000 characters are used. | [optional] 

## Methods

### NewFreeToolGenerateYoutubeDescriptionRequest

`func NewFreeToolGenerateYoutubeDescriptionRequest(text string, ) *FreeToolGenerateYoutubeDescriptionRequest`

NewFreeToolGenerateYoutubeDescriptionRequest instantiates a new FreeToolGenerateYoutubeDescriptionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateYoutubeDescriptionRequestWithDefaults

`func NewFreeToolGenerateYoutubeDescriptionRequestWithDefaults() *FreeToolGenerateYoutubeDescriptionRequest`

NewFreeToolGenerateYoutubeDescriptionRequestWithDefaults instantiates a new FreeToolGenerateYoutubeDescriptionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolGenerateYoutubeDescriptionRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolGenerateYoutubeDescriptionRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolGenerateYoutubeDescriptionRequest) SetText(v string)`

SetText sets Text field to given value.


### GetKeywords

`func (o *FreeToolGenerateYoutubeDescriptionRequest) GetKeywords() string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *FreeToolGenerateYoutubeDescriptionRequest) GetKeywordsOk() (*string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *FreeToolGenerateYoutubeDescriptionRequest) SetKeywords(v string)`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *FreeToolGenerateYoutubeDescriptionRequest) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### GetChapters

`func (o *FreeToolGenerateYoutubeDescriptionRequest) GetChapters() bool`

GetChapters returns the Chapters field if non-nil, zero value otherwise.

### GetChaptersOk

`func (o *FreeToolGenerateYoutubeDescriptionRequest) GetChaptersOk() (*bool, bool)`

GetChaptersOk returns a tuple with the Chapters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChapters

`func (o *FreeToolGenerateYoutubeDescriptionRequest) SetChapters(v bool)`

SetChapters sets Chapters field to given value.

### HasChapters

`func (o *FreeToolGenerateYoutubeDescriptionRequest) HasChapters() bool`

HasChapters returns a boolean if a field has been set.

### GetChapterLines

`func (o *FreeToolGenerateYoutubeDescriptionRequest) GetChapterLines() []string`

GetChapterLines returns the ChapterLines field if non-nil, zero value otherwise.

### GetChapterLinesOk

`func (o *FreeToolGenerateYoutubeDescriptionRequest) GetChapterLinesOk() (*[]string, bool)`

GetChapterLinesOk returns a tuple with the ChapterLines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChapterLines

`func (o *FreeToolGenerateYoutubeDescriptionRequest) SetChapterLines(v []string)`

SetChapterLines sets ChapterLines field to given value.

### HasChapterLines

`func (o *FreeToolGenerateYoutubeDescriptionRequest) HasChapterLines() bool`

HasChapterLines returns a boolean if a field has been set.

### GetCta

`func (o *FreeToolGenerateYoutubeDescriptionRequest) GetCta() string`

GetCta returns the Cta field if non-nil, zero value otherwise.

### GetCtaOk

`func (o *FreeToolGenerateYoutubeDescriptionRequest) GetCtaOk() (*string, bool)`

GetCtaOk returns a tuple with the Cta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCta

`func (o *FreeToolGenerateYoutubeDescriptionRequest) SetCta(v string)`

SetCta sets Cta field to given value.

### HasCta

`func (o *FreeToolGenerateYoutubeDescriptionRequest) HasCta() bool`

HasCta returns a boolean if a field has been set.

### GetWorkspace

`func (o *FreeToolGenerateYoutubeDescriptionRequest) GetWorkspace() string`

GetWorkspace returns the Workspace field if non-nil, zero value otherwise.

### GetWorkspaceOk

`func (o *FreeToolGenerateYoutubeDescriptionRequest) GetWorkspaceOk() (*string, bool)`

GetWorkspaceOk returns a tuple with the Workspace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspace

`func (o *FreeToolGenerateYoutubeDescriptionRequest) SetWorkspace(v string)`

SetWorkspace sets Workspace field to given value.

### HasWorkspace

`func (o *FreeToolGenerateYoutubeDescriptionRequest) HasWorkspace() bool`

HasWorkspace returns a boolean if a field has been set.

### GetTranscript

`func (o *FreeToolGenerateYoutubeDescriptionRequest) GetTranscript() string`

GetTranscript returns the Transcript field if non-nil, zero value otherwise.

### GetTranscriptOk

`func (o *FreeToolGenerateYoutubeDescriptionRequest) GetTranscriptOk() (*string, bool)`

GetTranscriptOk returns a tuple with the Transcript field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTranscript

`func (o *FreeToolGenerateYoutubeDescriptionRequest) SetTranscript(v string)`

SetTranscript sets Transcript field to given value.

### HasTranscript

`func (o *FreeToolGenerateYoutubeDescriptionRequest) HasTranscript() bool`

HasTranscript returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


