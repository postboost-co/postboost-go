# FreeToolGenerateSocialPostsFromBlogRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | Pointer to **string** | Public http(s) address of the blog post. Give &#x60;url&#x60; or &#x60;text&#x60;. | [optional] 
**Text** | Pointer to **string** | The blog post itself, instead of &#x60;url&#x60;. | [optional] 
**Platforms** | **[]string** | Networks to write for, at most 4 per call (one AI credit each). | 
**Tone** | Pointer to **string** |  | [optional] [default to "casual"]
**Length** | Pointer to **string** |  | [optional] [default to "short"]
**Hashtags** | Pointer to **string** | How many hashtags to include. | [optional] [default to "no"]
**Cta** | Pointer to **string** | Call to action to end with. | [optional] [default to "no"]
**Workspace** | Pointer to **string** | UUID of the workspace whose AI credits pay for the call. Default: your active workspace (a scoped API key: its own workspace). | [optional] 

## Methods

### NewFreeToolGenerateSocialPostsFromBlogRequest

`func NewFreeToolGenerateSocialPostsFromBlogRequest(platforms []string, ) *FreeToolGenerateSocialPostsFromBlogRequest`

NewFreeToolGenerateSocialPostsFromBlogRequest instantiates a new FreeToolGenerateSocialPostsFromBlogRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateSocialPostsFromBlogRequestWithDefaults

`func NewFreeToolGenerateSocialPostsFromBlogRequestWithDefaults() *FreeToolGenerateSocialPostsFromBlogRequest`

NewFreeToolGenerateSocialPostsFromBlogRequestWithDefaults instantiates a new FreeToolGenerateSocialPostsFromBlogRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetText

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) HasText() bool`

HasText returns a boolean if a field has been set.

### GetPlatforms

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) GetPlatforms() []string`

GetPlatforms returns the Platforms field if non-nil, zero value otherwise.

### GetPlatformsOk

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) GetPlatformsOk() (*[]string, bool)`

GetPlatformsOk returns a tuple with the Platforms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatforms

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) SetPlatforms(v []string)`

SetPlatforms sets Platforms field to given value.


### GetTone

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) GetTone() string`

GetTone returns the Tone field if non-nil, zero value otherwise.

### GetToneOk

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) GetToneOk() (*string, bool)`

GetToneOk returns a tuple with the Tone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTone

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) SetTone(v string)`

SetTone sets Tone field to given value.

### HasTone

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) HasTone() bool`

HasTone returns a boolean if a field has been set.

### GetLength

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) GetLength() string`

GetLength returns the Length field if non-nil, zero value otherwise.

### GetLengthOk

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) GetLengthOk() (*string, bool)`

GetLengthOk returns a tuple with the Length field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLength

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) SetLength(v string)`

SetLength sets Length field to given value.

### HasLength

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) HasLength() bool`

HasLength returns a boolean if a field has been set.

### GetHashtags

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) GetHashtags() string`

GetHashtags returns the Hashtags field if non-nil, zero value otherwise.

### GetHashtagsOk

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) GetHashtagsOk() (*string, bool)`

GetHashtagsOk returns a tuple with the Hashtags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHashtags

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) SetHashtags(v string)`

SetHashtags sets Hashtags field to given value.

### HasHashtags

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) HasHashtags() bool`

HasHashtags returns a boolean if a field has been set.

### GetCta

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) GetCta() string`

GetCta returns the Cta field if non-nil, zero value otherwise.

### GetCtaOk

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) GetCtaOk() (*string, bool)`

GetCtaOk returns a tuple with the Cta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCta

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) SetCta(v string)`

SetCta sets Cta field to given value.

### HasCta

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) HasCta() bool`

HasCta returns a boolean if a field has been set.

### GetWorkspace

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) GetWorkspace() string`

GetWorkspace returns the Workspace field if non-nil, zero value otherwise.

### GetWorkspaceOk

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) GetWorkspaceOk() (*string, bool)`

GetWorkspaceOk returns a tuple with the Workspace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspace

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) SetWorkspace(v string)`

SetWorkspace sets Workspace field to given value.

### HasWorkspace

`func (o *FreeToolGenerateSocialPostsFromBlogRequest) HasWorkspace() bool`

HasWorkspace returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


