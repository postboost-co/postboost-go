# BlogToSocialCaption

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | Pointer to **int32** | ID of the social account this caption was generated for. | [optional] 
**Provider** | Pointer to **string** | Social media platform identifier. | [optional] 
**Content** | Pointer to **string** | The generated caption text. &#x60;null&#x60; if generation failed for this account. | [optional] 
**CharacterCount** | Pointer to **int32** | Character count of the generated content. &#x60;null&#x60; if generation failed. | [optional] 
**CharacterLimit** | Pointer to **int32** | Maximum allowed character count for this platform. | [optional] 
**Error** | Pointer to **string** | Error message if caption generation failed for this account. &#x60;null&#x60; on success. | [optional] 

## Methods

### NewBlogToSocialCaption

`func NewBlogToSocialCaption() *BlogToSocialCaption`

NewBlogToSocialCaption instantiates a new BlogToSocialCaption object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBlogToSocialCaptionWithDefaults

`func NewBlogToSocialCaptionWithDefaults() *BlogToSocialCaption`

NewBlogToSocialCaptionWithDefaults instantiates a new BlogToSocialCaption object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *BlogToSocialCaption) GetAccountId() int32`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *BlogToSocialCaption) GetAccountIdOk() (*int32, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *BlogToSocialCaption) SetAccountId(v int32)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *BlogToSocialCaption) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetProvider

`func (o *BlogToSocialCaption) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *BlogToSocialCaption) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *BlogToSocialCaption) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *BlogToSocialCaption) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### GetContent

`func (o *BlogToSocialCaption) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *BlogToSocialCaption) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *BlogToSocialCaption) SetContent(v string)`

SetContent sets Content field to given value.

### HasContent

`func (o *BlogToSocialCaption) HasContent() bool`

HasContent returns a boolean if a field has been set.

### GetCharacterCount

`func (o *BlogToSocialCaption) GetCharacterCount() int32`

GetCharacterCount returns the CharacterCount field if non-nil, zero value otherwise.

### GetCharacterCountOk

`func (o *BlogToSocialCaption) GetCharacterCountOk() (*int32, bool)`

GetCharacterCountOk returns a tuple with the CharacterCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharacterCount

`func (o *BlogToSocialCaption) SetCharacterCount(v int32)`

SetCharacterCount sets CharacterCount field to given value.

### HasCharacterCount

`func (o *BlogToSocialCaption) HasCharacterCount() bool`

HasCharacterCount returns a boolean if a field has been set.

### GetCharacterLimit

`func (o *BlogToSocialCaption) GetCharacterLimit() int32`

GetCharacterLimit returns the CharacterLimit field if non-nil, zero value otherwise.

### GetCharacterLimitOk

`func (o *BlogToSocialCaption) GetCharacterLimitOk() (*int32, bool)`

GetCharacterLimitOk returns a tuple with the CharacterLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCharacterLimit

`func (o *BlogToSocialCaption) SetCharacterLimit(v int32)`

SetCharacterLimit sets CharacterLimit field to given value.

### HasCharacterLimit

`func (o *BlogToSocialCaption) HasCharacterLimit() bool`

HasCharacterLimit returns a boolean if a field has been set.

### GetError

`func (o *BlogToSocialCaption) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *BlogToSocialCaption) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *BlogToSocialCaption) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *BlogToSocialCaption) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


