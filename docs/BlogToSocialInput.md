# BlogToSocialInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | Pointer to **string** | Blog post URL to scrape. Required if &#x60;title&#x60; and &#x60;excerpt&#x60; are not provided. | [optional] 
**Title** | Pointer to **string** | Blog post title. Required if &#x60;url&#x60; is not provided. | [optional] 
**Excerpt** | Pointer to **string** | Blog post summary or excerpt. Required if &#x60;url&#x60; is not provided. | [optional] 
**ImageUrl** | Pointer to **NullableString** | Featured image URL for the blog post. When &#x60;create_post&#x60; is &#x60;true&#x60;, the image is imported into the workspace media library and attached to the draft post. If omitted in URL mode, the scraper attempts to extract the &#x60;og:image&#x60; meta tag.  | [optional] 
**Platforms** | Pointer to **[]string** | Target social media platforms. Only connected accounts matching these platforms are used. If omitted, all connected accounts in the workspace are targeted.  | [optional] 
**AccountIds** | Pointer to **[]int32** | Specific account IDs to generate captions for. Takes precedence over &#x60;platforms&#x60; when both are provided.  | [optional] 
**Tone** | Pointer to **NullableString** | Writing tone for all generated captions. | [optional] [default to "engaging"]
**ContentLength** | Pointer to **NullableString** | Desired length of the generated captions. | [optional] [default to "medium"]
**Hashtags** | Pointer to **NullableString** | Hashtag quantity: none (0), few (1-3), some (3-5), many (5+). | [optional] [default to "few"]
**Cta** | Pointer to **NullableString** | Call-to-action type appended to each caption. | [optional] [default to "none"]
**Language** | Pointer to **NullableString** | Output language as an ISO 639-1 code (e.g. &#x60;en&#x60;, &#x60;de&#x60;, &#x60;fr&#x60;). Use &#x60;auto&#x60; to match the blog post&#39;s language automatically.  | [optional] [default to "auto"]
**CustomInstructions** | Pointer to **NullableString** | Additional instructions appended to the AI prompt (e.g. \&quot;always mention our free tier\&quot;). | [optional] 
**CreatePost** | Pointer to **NullableBool** | When &#x60;true&#x60;, creates a draft post in the workspace with per-account caption versions. If an image is available, it is imported and attached to the post.  | [optional] [default to false]
**UseBrandVoice** | Pointer to **NullableBool** | Apply the workspace brand voice (see &#x60;GET brand-voice&#x60;) to the captions. An explicit &#x60;tone&#x60; is kept, but the brand voice wins on vocabulary, words to avoid and calls to action.  | [optional] [default to true]

## Methods

### NewBlogToSocialInput

`func NewBlogToSocialInput() *BlogToSocialInput`

NewBlogToSocialInput instantiates a new BlogToSocialInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBlogToSocialInputWithDefaults

`func NewBlogToSocialInputWithDefaults() *BlogToSocialInput`

NewBlogToSocialInputWithDefaults instantiates a new BlogToSocialInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *BlogToSocialInput) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *BlogToSocialInput) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *BlogToSocialInput) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *BlogToSocialInput) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetTitle

`func (o *BlogToSocialInput) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *BlogToSocialInput) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *BlogToSocialInput) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *BlogToSocialInput) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetExcerpt

`func (o *BlogToSocialInput) GetExcerpt() string`

GetExcerpt returns the Excerpt field if non-nil, zero value otherwise.

### GetExcerptOk

`func (o *BlogToSocialInput) GetExcerptOk() (*string, bool)`

GetExcerptOk returns a tuple with the Excerpt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcerpt

`func (o *BlogToSocialInput) SetExcerpt(v string)`

SetExcerpt sets Excerpt field to given value.

### HasExcerpt

`func (o *BlogToSocialInput) HasExcerpt() bool`

HasExcerpt returns a boolean if a field has been set.

### GetImageUrl

`func (o *BlogToSocialInput) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *BlogToSocialInput) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *BlogToSocialInput) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *BlogToSocialInput) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### SetImageUrlNil

`func (o *BlogToSocialInput) SetImageUrlNil(b bool)`

 SetImageUrlNil sets the value for ImageUrl to be an explicit nil

### UnsetImageUrl
`func (o *BlogToSocialInput) UnsetImageUrl()`

UnsetImageUrl ensures that no value is present for ImageUrl, not even an explicit nil
### GetPlatforms

`func (o *BlogToSocialInput) GetPlatforms() []string`

GetPlatforms returns the Platforms field if non-nil, zero value otherwise.

### GetPlatformsOk

`func (o *BlogToSocialInput) GetPlatformsOk() (*[]string, bool)`

GetPlatformsOk returns a tuple with the Platforms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatforms

`func (o *BlogToSocialInput) SetPlatforms(v []string)`

SetPlatforms sets Platforms field to given value.

### HasPlatforms

`func (o *BlogToSocialInput) HasPlatforms() bool`

HasPlatforms returns a boolean if a field has been set.

### SetPlatformsNil

`func (o *BlogToSocialInput) SetPlatformsNil(b bool)`

 SetPlatformsNil sets the value for Platforms to be an explicit nil

### UnsetPlatforms
`func (o *BlogToSocialInput) UnsetPlatforms()`

UnsetPlatforms ensures that no value is present for Platforms, not even an explicit nil
### GetAccountIds

`func (o *BlogToSocialInput) GetAccountIds() []int32`

GetAccountIds returns the AccountIds field if non-nil, zero value otherwise.

### GetAccountIdsOk

`func (o *BlogToSocialInput) GetAccountIdsOk() (*[]int32, bool)`

GetAccountIdsOk returns a tuple with the AccountIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountIds

`func (o *BlogToSocialInput) SetAccountIds(v []int32)`

SetAccountIds sets AccountIds field to given value.

### HasAccountIds

`func (o *BlogToSocialInput) HasAccountIds() bool`

HasAccountIds returns a boolean if a field has been set.

### SetAccountIdsNil

`func (o *BlogToSocialInput) SetAccountIdsNil(b bool)`

 SetAccountIdsNil sets the value for AccountIds to be an explicit nil

### UnsetAccountIds
`func (o *BlogToSocialInput) UnsetAccountIds()`

UnsetAccountIds ensures that no value is present for AccountIds, not even an explicit nil
### GetTone

`func (o *BlogToSocialInput) GetTone() string`

GetTone returns the Tone field if non-nil, zero value otherwise.

### GetToneOk

`func (o *BlogToSocialInput) GetToneOk() (*string, bool)`

GetToneOk returns a tuple with the Tone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTone

`func (o *BlogToSocialInput) SetTone(v string)`

SetTone sets Tone field to given value.

### HasTone

`func (o *BlogToSocialInput) HasTone() bool`

HasTone returns a boolean if a field has been set.

### SetToneNil

`func (o *BlogToSocialInput) SetToneNil(b bool)`

 SetToneNil sets the value for Tone to be an explicit nil

### UnsetTone
`func (o *BlogToSocialInput) UnsetTone()`

UnsetTone ensures that no value is present for Tone, not even an explicit nil
### GetContentLength

`func (o *BlogToSocialInput) GetContentLength() string`

GetContentLength returns the ContentLength field if non-nil, zero value otherwise.

### GetContentLengthOk

`func (o *BlogToSocialInput) GetContentLengthOk() (*string, bool)`

GetContentLengthOk returns a tuple with the ContentLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentLength

`func (o *BlogToSocialInput) SetContentLength(v string)`

SetContentLength sets ContentLength field to given value.

### HasContentLength

`func (o *BlogToSocialInput) HasContentLength() bool`

HasContentLength returns a boolean if a field has been set.

### SetContentLengthNil

`func (o *BlogToSocialInput) SetContentLengthNil(b bool)`

 SetContentLengthNil sets the value for ContentLength to be an explicit nil

### UnsetContentLength
`func (o *BlogToSocialInput) UnsetContentLength()`

UnsetContentLength ensures that no value is present for ContentLength, not even an explicit nil
### GetHashtags

`func (o *BlogToSocialInput) GetHashtags() string`

GetHashtags returns the Hashtags field if non-nil, zero value otherwise.

### GetHashtagsOk

`func (o *BlogToSocialInput) GetHashtagsOk() (*string, bool)`

GetHashtagsOk returns a tuple with the Hashtags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHashtags

`func (o *BlogToSocialInput) SetHashtags(v string)`

SetHashtags sets Hashtags field to given value.

### HasHashtags

`func (o *BlogToSocialInput) HasHashtags() bool`

HasHashtags returns a boolean if a field has been set.

### SetHashtagsNil

`func (o *BlogToSocialInput) SetHashtagsNil(b bool)`

 SetHashtagsNil sets the value for Hashtags to be an explicit nil

### UnsetHashtags
`func (o *BlogToSocialInput) UnsetHashtags()`

UnsetHashtags ensures that no value is present for Hashtags, not even an explicit nil
### GetCta

`func (o *BlogToSocialInput) GetCta() string`

GetCta returns the Cta field if non-nil, zero value otherwise.

### GetCtaOk

`func (o *BlogToSocialInput) GetCtaOk() (*string, bool)`

GetCtaOk returns a tuple with the Cta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCta

`func (o *BlogToSocialInput) SetCta(v string)`

SetCta sets Cta field to given value.

### HasCta

`func (o *BlogToSocialInput) HasCta() bool`

HasCta returns a boolean if a field has been set.

### SetCtaNil

`func (o *BlogToSocialInput) SetCtaNil(b bool)`

 SetCtaNil sets the value for Cta to be an explicit nil

### UnsetCta
`func (o *BlogToSocialInput) UnsetCta()`

UnsetCta ensures that no value is present for Cta, not even an explicit nil
### GetLanguage

`func (o *BlogToSocialInput) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *BlogToSocialInput) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *BlogToSocialInput) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *BlogToSocialInput) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### SetLanguageNil

`func (o *BlogToSocialInput) SetLanguageNil(b bool)`

 SetLanguageNil sets the value for Language to be an explicit nil

### UnsetLanguage
`func (o *BlogToSocialInput) UnsetLanguage()`

UnsetLanguage ensures that no value is present for Language, not even an explicit nil
### GetCustomInstructions

`func (o *BlogToSocialInput) GetCustomInstructions() string`

GetCustomInstructions returns the CustomInstructions field if non-nil, zero value otherwise.

### GetCustomInstructionsOk

`func (o *BlogToSocialInput) GetCustomInstructionsOk() (*string, bool)`

GetCustomInstructionsOk returns a tuple with the CustomInstructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomInstructions

`func (o *BlogToSocialInput) SetCustomInstructions(v string)`

SetCustomInstructions sets CustomInstructions field to given value.

### HasCustomInstructions

`func (o *BlogToSocialInput) HasCustomInstructions() bool`

HasCustomInstructions returns a boolean if a field has been set.

### SetCustomInstructionsNil

`func (o *BlogToSocialInput) SetCustomInstructionsNil(b bool)`

 SetCustomInstructionsNil sets the value for CustomInstructions to be an explicit nil

### UnsetCustomInstructions
`func (o *BlogToSocialInput) UnsetCustomInstructions()`

UnsetCustomInstructions ensures that no value is present for CustomInstructions, not even an explicit nil
### GetCreatePost

`func (o *BlogToSocialInput) GetCreatePost() bool`

GetCreatePost returns the CreatePost field if non-nil, zero value otherwise.

### GetCreatePostOk

`func (o *BlogToSocialInput) GetCreatePostOk() (*bool, bool)`

GetCreatePostOk returns a tuple with the CreatePost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatePost

`func (o *BlogToSocialInput) SetCreatePost(v bool)`

SetCreatePost sets CreatePost field to given value.

### HasCreatePost

`func (o *BlogToSocialInput) HasCreatePost() bool`

HasCreatePost returns a boolean if a field has been set.

### SetCreatePostNil

`func (o *BlogToSocialInput) SetCreatePostNil(b bool)`

 SetCreatePostNil sets the value for CreatePost to be an explicit nil

### UnsetCreatePost
`func (o *BlogToSocialInput) UnsetCreatePost()`

UnsetCreatePost ensures that no value is present for CreatePost, not even an explicit nil
### GetUseBrandVoice

`func (o *BlogToSocialInput) GetUseBrandVoice() bool`

GetUseBrandVoice returns the UseBrandVoice field if non-nil, zero value otherwise.

### GetUseBrandVoiceOk

`func (o *BlogToSocialInput) GetUseBrandVoiceOk() (*bool, bool)`

GetUseBrandVoiceOk returns a tuple with the UseBrandVoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseBrandVoice

`func (o *BlogToSocialInput) SetUseBrandVoice(v bool)`

SetUseBrandVoice sets UseBrandVoice field to given value.

### HasUseBrandVoice

`func (o *BlogToSocialInput) HasUseBrandVoice() bool`

HasUseBrandVoice returns a boolean if a field has been set.

### SetUseBrandVoiceNil

`func (o *BlogToSocialInput) SetUseBrandVoiceNil(b bool)`

 SetUseBrandVoiceNil sets the value for UseBrandVoice to be an explicit nil

### UnsetUseBrandVoice
`func (o *BlogToSocialInput) UnsetUseBrandVoice()`

UnsetUseBrandVoice ensures that no value is present for UseBrandVoice, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


