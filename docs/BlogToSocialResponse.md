# BlogToSocialResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BlogTitle** | Pointer to **string** | The blog post title (scraped or provided directly). | [optional] 
**BlogExcerpt** | Pointer to **string** | A short excerpt from the blog post content. | [optional] 
**Captions** | Pointer to [**[]BlogToSocialCaption**](BlogToSocialCaption.md) | Generated captions, one per target account. | [optional] 
**PostUuid** | Pointer to **string** | UUID of the created draft post. Only present when &#x60;create_post&#x60; was &#x60;true&#x60;. | [optional] 
**Media** | Pointer to [**BlogToSocialMedia**](BlogToSocialMedia.md) |  | [optional] 
**CreditsUsed** | Pointer to **int32** | Number of AI credits consumed by this request (one per successful caption). | [optional] 
**CreditsRemaining** | Pointer to **int32** | Remaining AI credits for the current billing period. &#x60;null&#x60; for unlimited plans. | [optional] 

## Methods

### NewBlogToSocialResponse

`func NewBlogToSocialResponse() *BlogToSocialResponse`

NewBlogToSocialResponse instantiates a new BlogToSocialResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBlogToSocialResponseWithDefaults

`func NewBlogToSocialResponseWithDefaults() *BlogToSocialResponse`

NewBlogToSocialResponseWithDefaults instantiates a new BlogToSocialResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBlogTitle

`func (o *BlogToSocialResponse) GetBlogTitle() string`

GetBlogTitle returns the BlogTitle field if non-nil, zero value otherwise.

### GetBlogTitleOk

`func (o *BlogToSocialResponse) GetBlogTitleOk() (*string, bool)`

GetBlogTitleOk returns a tuple with the BlogTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlogTitle

`func (o *BlogToSocialResponse) SetBlogTitle(v string)`

SetBlogTitle sets BlogTitle field to given value.

### HasBlogTitle

`func (o *BlogToSocialResponse) HasBlogTitle() bool`

HasBlogTitle returns a boolean if a field has been set.

### GetBlogExcerpt

`func (o *BlogToSocialResponse) GetBlogExcerpt() string`

GetBlogExcerpt returns the BlogExcerpt field if non-nil, zero value otherwise.

### GetBlogExcerptOk

`func (o *BlogToSocialResponse) GetBlogExcerptOk() (*string, bool)`

GetBlogExcerptOk returns a tuple with the BlogExcerpt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBlogExcerpt

`func (o *BlogToSocialResponse) SetBlogExcerpt(v string)`

SetBlogExcerpt sets BlogExcerpt field to given value.

### HasBlogExcerpt

`func (o *BlogToSocialResponse) HasBlogExcerpt() bool`

HasBlogExcerpt returns a boolean if a field has been set.

### GetCaptions

`func (o *BlogToSocialResponse) GetCaptions() []BlogToSocialCaption`

GetCaptions returns the Captions field if non-nil, zero value otherwise.

### GetCaptionsOk

`func (o *BlogToSocialResponse) GetCaptionsOk() (*[]BlogToSocialCaption, bool)`

GetCaptionsOk returns a tuple with the Captions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCaptions

`func (o *BlogToSocialResponse) SetCaptions(v []BlogToSocialCaption)`

SetCaptions sets Captions field to given value.

### HasCaptions

`func (o *BlogToSocialResponse) HasCaptions() bool`

HasCaptions returns a boolean if a field has been set.

### GetPostUuid

`func (o *BlogToSocialResponse) GetPostUuid() string`

GetPostUuid returns the PostUuid field if non-nil, zero value otherwise.

### GetPostUuidOk

`func (o *BlogToSocialResponse) GetPostUuidOk() (*string, bool)`

GetPostUuidOk returns a tuple with the PostUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostUuid

`func (o *BlogToSocialResponse) SetPostUuid(v string)`

SetPostUuid sets PostUuid field to given value.

### HasPostUuid

`func (o *BlogToSocialResponse) HasPostUuid() bool`

HasPostUuid returns a boolean if a field has been set.

### GetMedia

`func (o *BlogToSocialResponse) GetMedia() BlogToSocialMedia`

GetMedia returns the Media field if non-nil, zero value otherwise.

### GetMediaOk

`func (o *BlogToSocialResponse) GetMediaOk() (*BlogToSocialMedia, bool)`

GetMediaOk returns a tuple with the Media field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMedia

`func (o *BlogToSocialResponse) SetMedia(v BlogToSocialMedia)`

SetMedia sets Media field to given value.

### HasMedia

`func (o *BlogToSocialResponse) HasMedia() bool`

HasMedia returns a boolean if a field has been set.

### GetCreditsUsed

`func (o *BlogToSocialResponse) GetCreditsUsed() int32`

GetCreditsUsed returns the CreditsUsed field if non-nil, zero value otherwise.

### GetCreditsUsedOk

`func (o *BlogToSocialResponse) GetCreditsUsedOk() (*int32, bool)`

GetCreditsUsedOk returns a tuple with the CreditsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsUsed

`func (o *BlogToSocialResponse) SetCreditsUsed(v int32)`

SetCreditsUsed sets CreditsUsed field to given value.

### HasCreditsUsed

`func (o *BlogToSocialResponse) HasCreditsUsed() bool`

HasCreditsUsed returns a boolean if a field has been set.

### GetCreditsRemaining

`func (o *BlogToSocialResponse) GetCreditsRemaining() int32`

GetCreditsRemaining returns the CreditsRemaining field if non-nil, zero value otherwise.

### GetCreditsRemainingOk

`func (o *BlogToSocialResponse) GetCreditsRemainingOk() (*int32, bool)`

GetCreditsRemainingOk returns a tuple with the CreditsRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsRemaining

`func (o *BlogToSocialResponse) SetCreditsRemaining(v int32)`

SetCreditsRemaining sets CreditsRemaining field to given value.

### HasCreditsRemaining

`func (o *BlogToSocialResponse) HasCreditsRemaining() bool`

HasCreditsRemaining returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


