# FreeToolGenerateSocialPostsFromBlogResponsePostsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Platform** | Pointer to **string** |  | [optional] 
**Text** | Pointer to **string** | The post, cut at a sentence end when the model ran over the limit. | [optional] 
**Hashtags** | Pointer to **[]string** | Hashtags in the text, with #. | [optional] 
**Characters** | Pointer to **int32** | Length as the network counts it (X weighs links as 23, YouTube counts bytes). | [optional] 
**Limit** | Pointer to **int32** | The network&#39;s text limit. | [optional] 

## Methods

### NewFreeToolGenerateSocialPostsFromBlogResponsePostsInner

`func NewFreeToolGenerateSocialPostsFromBlogResponsePostsInner() *FreeToolGenerateSocialPostsFromBlogResponsePostsInner`

NewFreeToolGenerateSocialPostsFromBlogResponsePostsInner instantiates a new FreeToolGenerateSocialPostsFromBlogResponsePostsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateSocialPostsFromBlogResponsePostsInnerWithDefaults

`func NewFreeToolGenerateSocialPostsFromBlogResponsePostsInnerWithDefaults() *FreeToolGenerateSocialPostsFromBlogResponsePostsInner`

NewFreeToolGenerateSocialPostsFromBlogResponsePostsInnerWithDefaults instantiates a new FreeToolGenerateSocialPostsFromBlogResponsePostsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlatform

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) SetPlatform(v string)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### GetText

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) HasText() bool`

HasText returns a boolean if a field has been set.

### GetHashtags

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) GetHashtags() []string`

GetHashtags returns the Hashtags field if non-nil, zero value otherwise.

### GetHashtagsOk

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) GetHashtagsOk() (*[]string, bool)`

GetHashtagsOk returns a tuple with the Hashtags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHashtags

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) SetHashtags(v []string)`

SetHashtags sets Hashtags field to given value.

### HasHashtags

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) HasHashtags() bool`

HasHashtags returns a boolean if a field has been set.

### GetCharacters

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) GetCharacters() int32`

GetCharacters returns the Characters field if non-nil, zero value otherwise.

### GetCharactersOk

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) GetCharactersOk() (*int32, bool)`

GetCharactersOk returns a tuple with the Characters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharacters

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) SetCharacters(v int32)`

SetCharacters sets Characters field to given value.

### HasCharacters

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) HasCharacters() bool`

HasCharacters returns a boolean if a field has been set.

### GetLimit

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *FreeToolGenerateSocialPostsFromBlogResponsePostsInner) HasLimit() bool`

HasLimit returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


