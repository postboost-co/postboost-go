# BlogToSocialInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | Pointer to **string** | Blog post URL to scrape. Required if &#x60;title&#x60; and &#x60;excerpt&#x60; are not provided. | [optional] 
**Title** | Pointer to **string** | Blog post title. Required if &#x60;url&#x60; is not provided. | [optional] 
**Excerpt** | Pointer to **string** | Blog post summary or excerpt. Required if &#x60;url&#x60; is not provided. | [optional] 
**ImageUrl** | Pointer to **string** | Featured image URL for the blog post. When &#x60;create_post&#x60; is &#x60;true&#x60;, the image is imported into the workspace media library and attached to the draft post. If omitted in URL mode, the scraper attempts to extract the &#x60;og:image&#x60; meta tag.  | [optional] 
**Platforms** | Pointer to **[]string** | Target social media platforms. Only connected accounts matching these platforms are used. If omitted, all connected accounts in the workspace are targeted.  | [optional] 
**AccountIds** | Pointer to **[]int32** | Specific account IDs to generate captions for. Takes precedence over &#x60;platforms&#x60; when both are provided.  | [optional] 
**Tone** | Pointer to **string** | Writing tone for all generated captions. | [optional] [default to "engaging"]
**ContentLength** | Pointer to **string** | Desired length of the generated captions. | [optional] [default to "medium"]
**Hashtags** | Pointer to **string** | Hashtag quantity: none (0), few (1-3), some (3-5), many (5+). | [optional] [default to "few"]
**Cta** | Pointer to **string** | Call-to-action type appended to each caption. | [optional] [default to "none"]
**Language** | Pointer to **string** | Output language as an ISO 639-1 code (e.g. &#x60;en&#x60;, &#x60;de&#x60;, &#x60;fr&#x60;). Use &#x60;auto&#x60; to match the blog post&#39;s language automatically.  | [optional] [default to "auto"]
**CustomInstructions** | Pointer to **string** | Additional instructions appended to the AI prompt (e.g. \&quot;always mention our free tier\&quot;). | [optional] 
**CreatePost** | Pointer to **bool** | When &#x60;true&#x60;, creates a draft post in the workspace with per-account caption versions. If an image is available, it is imported and attached to the post.  | [optional] [default to false]

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


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


