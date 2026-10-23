# FreeToolGenerateSocialPostsFromVideoRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** | The captions of your video: an .srt, .vtt or .sbv file&#39;s text, or the text of YouTube&#39;s \&quot;Show transcript\&quot; panel. Timestamps, cue numbers and sound tags like [Music] are removed; 100 to 24,000 characters must remain. | 
**VideoUrl** | Pointer to **string** | The video&#39;s YouTube link (watch, youtu.be, Shorts or live). Each output links it once, the X thread in its last post; without it the posts have no link. | [optional] 
**Title** | Pointer to **string** | The video&#39;s title, as context for the posts. | [optional] 
**Outputs** | Pointer to **[]string** | What to write, 1 to 4 different keys. | [optional] [default to [x_thread, linkedin, instagram]]
**Tone** | Pointer to **string** |  | [optional] [default to "friendly"]
**Workspace** | Pointer to **string** | UUID of the workspace whose AI credits pay for the call. Default: your active workspace (a scoped API key: its own workspace). | [optional] 

## Methods

### NewFreeToolGenerateSocialPostsFromVideoRequest

`func NewFreeToolGenerateSocialPostsFromVideoRequest(text string, ) *FreeToolGenerateSocialPostsFromVideoRequest`

NewFreeToolGenerateSocialPostsFromVideoRequest instantiates a new FreeToolGenerateSocialPostsFromVideoRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateSocialPostsFromVideoRequestWithDefaults

`func NewFreeToolGenerateSocialPostsFromVideoRequestWithDefaults() *FreeToolGenerateSocialPostsFromVideoRequest`

NewFreeToolGenerateSocialPostsFromVideoRequestWithDefaults instantiates a new FreeToolGenerateSocialPostsFromVideoRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) SetText(v string)`

SetText sets Text field to given value.


### GetVideoUrl

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) GetVideoUrl() string`

GetVideoUrl returns the VideoUrl field if non-nil, zero value otherwise.

### GetVideoUrlOk

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) GetVideoUrlOk() (*string, bool)`

GetVideoUrlOk returns a tuple with the VideoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoUrl

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) SetVideoUrl(v string)`

SetVideoUrl sets VideoUrl field to given value.

### HasVideoUrl

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) HasVideoUrl() bool`

HasVideoUrl returns a boolean if a field has been set.

### GetTitle

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetOutputs

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) GetOutputs() []string`

GetOutputs returns the Outputs field if non-nil, zero value otherwise.

### GetOutputsOk

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) GetOutputsOk() (*[]string, bool)`

GetOutputsOk returns a tuple with the Outputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputs

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) SetOutputs(v []string)`

SetOutputs sets Outputs field to given value.

### HasOutputs

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) HasOutputs() bool`

HasOutputs returns a boolean if a field has been set.

### GetTone

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) GetTone() string`

GetTone returns the Tone field if non-nil, zero value otherwise.

### GetToneOk

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) GetToneOk() (*string, bool)`

GetToneOk returns a tuple with the Tone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTone

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) SetTone(v string)`

SetTone sets Tone field to given value.

### HasTone

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) HasTone() bool`

HasTone returns a boolean if a field has been set.

### GetWorkspace

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) GetWorkspace() string`

GetWorkspace returns the Workspace field if non-nil, zero value otherwise.

### GetWorkspaceOk

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) GetWorkspaceOk() (*string, bool)`

GetWorkspaceOk returns a tuple with the Workspace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspace

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) SetWorkspace(v string)`

SetWorkspace sets Workspace field to given value.

### HasWorkspace

`func (o *FreeToolGenerateSocialPostsFromVideoRequest) HasWorkspace() bool`

HasWorkspace returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


