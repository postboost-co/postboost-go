# RepurposeInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SourceType** | **string** |  | 
**Url** | Pointer to **string** | Article URL (&#x60;url&#x60;) or YouTube video URL (&#x60;youtube&#x60;). For &#x60;text&#x60;, an optional link to mention. | [optional] 
**PdfUrl** | Pointer to **string** | Public URL of a PDF (&#x60;pdf&#x60;), at most 20 MB. | [optional] 
**Title** | Pointer to **string** | Required for &#x60;text&#x60;. For &#x60;youtube&#x60;, overrides the video title. | [optional] 
**Text** | Pointer to **string** | Required for &#x60;text&#x60;. Long sources are cut to about 12,000 characters. | [optional] 
**Transcript** | Pointer to **string** | Video transcript for &#x60;youtube&#x60;. | [optional] 
**Platforms** | Pointer to **[]string** | Limit to connected accounts of these networks. Ignored when &#x60;account_ids&#x60; is set. | [optional] 
**AccountIds** | Pointer to **[]int32** | Target accounts. Default is every connected account. | [optional] 
**Tone** | Pointer to **string** |  | [optional] [default to "engaging"]
**ContentLength** | Pointer to **string** |  | [optional] [default to "medium"]
**Hashtags** | Pointer to **string** |  | [optional] [default to "few"]
**Cta** | Pointer to **string** |  | [optional] [default to "none"]
**Language** | Pointer to **string** |  | [optional] [default to "auto"]
**CustomInstructions** | Pointer to **string** |  | [optional] 
**Carousel** | Pointer to **bool** | Render carousel slides (one extra AI credit for the outline). | [optional] [default to true]
**SlideCount** | Pointer to **int32** | Total slides including the hook and call-to-action slides. | [optional] [default to 7]
**Theme** | Pointer to [**RepurposeInputTheme**](RepurposeInputTheme.md) |  | [optional] 
**CreatePost** | Pointer to **bool** | Create the draft post. &#x60;false&#x60; returns captions and slides only. | [optional] [default to true]
**UseBrandVoice** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewRepurposeInput

`func NewRepurposeInput(sourceType string, ) *RepurposeInput`

NewRepurposeInput instantiates a new RepurposeInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRepurposeInputWithDefaults

`func NewRepurposeInputWithDefaults() *RepurposeInput`

NewRepurposeInputWithDefaults instantiates a new RepurposeInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSourceType

`func (o *RepurposeInput) GetSourceType() string`

GetSourceType returns the SourceType field if non-nil, zero value otherwise.

### GetSourceTypeOk

`func (o *RepurposeInput) GetSourceTypeOk() (*string, bool)`

GetSourceTypeOk returns a tuple with the SourceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceType

`func (o *RepurposeInput) SetSourceType(v string)`

SetSourceType sets SourceType field to given value.


### GetUrl

`func (o *RepurposeInput) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *RepurposeInput) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *RepurposeInput) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *RepurposeInput) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetPdfUrl

`func (o *RepurposeInput) GetPdfUrl() string`

GetPdfUrl returns the PdfUrl field if non-nil, zero value otherwise.

### GetPdfUrlOk

`func (o *RepurposeInput) GetPdfUrlOk() (*string, bool)`

GetPdfUrlOk returns a tuple with the PdfUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPdfUrl

`func (o *RepurposeInput) SetPdfUrl(v string)`

SetPdfUrl sets PdfUrl field to given value.

### HasPdfUrl

`func (o *RepurposeInput) HasPdfUrl() bool`

HasPdfUrl returns a boolean if a field has been set.

### GetTitle

`func (o *RepurposeInput) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *RepurposeInput) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *RepurposeInput) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *RepurposeInput) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetText

`func (o *RepurposeInput) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *RepurposeInput) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *RepurposeInput) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *RepurposeInput) HasText() bool`

HasText returns a boolean if a field has been set.

### GetTranscript

`func (o *RepurposeInput) GetTranscript() string`

GetTranscript returns the Transcript field if non-nil, zero value otherwise.

### GetTranscriptOk

`func (o *RepurposeInput) GetTranscriptOk() (*string, bool)`

GetTranscriptOk returns a tuple with the Transcript field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTranscript

`func (o *RepurposeInput) SetTranscript(v string)`

SetTranscript sets Transcript field to given value.

### HasTranscript

`func (o *RepurposeInput) HasTranscript() bool`

HasTranscript returns a boolean if a field has been set.

### GetPlatforms

`func (o *RepurposeInput) GetPlatforms() []string`

GetPlatforms returns the Platforms field if non-nil, zero value otherwise.

### GetPlatformsOk

`func (o *RepurposeInput) GetPlatformsOk() (*[]string, bool)`

GetPlatformsOk returns a tuple with the Platforms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatforms

`func (o *RepurposeInput) SetPlatforms(v []string)`

SetPlatforms sets Platforms field to given value.

### HasPlatforms

`func (o *RepurposeInput) HasPlatforms() bool`

HasPlatforms returns a boolean if a field has been set.

### GetAccountIds

`func (o *RepurposeInput) GetAccountIds() []int32`

GetAccountIds returns the AccountIds field if non-nil, zero value otherwise.

### GetAccountIdsOk

`func (o *RepurposeInput) GetAccountIdsOk() (*[]int32, bool)`

GetAccountIdsOk returns a tuple with the AccountIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountIds

`func (o *RepurposeInput) SetAccountIds(v []int32)`

SetAccountIds sets AccountIds field to given value.

### HasAccountIds

`func (o *RepurposeInput) HasAccountIds() bool`

HasAccountIds returns a boolean if a field has been set.

### GetTone

`func (o *RepurposeInput) GetTone() string`

GetTone returns the Tone field if non-nil, zero value otherwise.

### GetToneOk

`func (o *RepurposeInput) GetToneOk() (*string, bool)`

GetToneOk returns a tuple with the Tone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTone

`func (o *RepurposeInput) SetTone(v string)`

SetTone sets Tone field to given value.

### HasTone

`func (o *RepurposeInput) HasTone() bool`

HasTone returns a boolean if a field has been set.

### GetContentLength

`func (o *RepurposeInput) GetContentLength() string`

GetContentLength returns the ContentLength field if non-nil, zero value otherwise.

### GetContentLengthOk

`func (o *RepurposeInput) GetContentLengthOk() (*string, bool)`

GetContentLengthOk returns a tuple with the ContentLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentLength

`func (o *RepurposeInput) SetContentLength(v string)`

SetContentLength sets ContentLength field to given value.

### HasContentLength

`func (o *RepurposeInput) HasContentLength() bool`

HasContentLength returns a boolean if a field has been set.

### GetHashtags

`func (o *RepurposeInput) GetHashtags() string`

GetHashtags returns the Hashtags field if non-nil, zero value otherwise.

### GetHashtagsOk

`func (o *RepurposeInput) GetHashtagsOk() (*string, bool)`

GetHashtagsOk returns a tuple with the Hashtags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHashtags

`func (o *RepurposeInput) SetHashtags(v string)`

SetHashtags sets Hashtags field to given value.

### HasHashtags

`func (o *RepurposeInput) HasHashtags() bool`

HasHashtags returns a boolean if a field has been set.

### GetCta

`func (o *RepurposeInput) GetCta() string`

GetCta returns the Cta field if non-nil, zero value otherwise.

### GetCtaOk

`func (o *RepurposeInput) GetCtaOk() (*string, bool)`

GetCtaOk returns a tuple with the Cta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCta

`func (o *RepurposeInput) SetCta(v string)`

SetCta sets Cta field to given value.

### HasCta

`func (o *RepurposeInput) HasCta() bool`

HasCta returns a boolean if a field has been set.

### GetLanguage

`func (o *RepurposeInput) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *RepurposeInput) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *RepurposeInput) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *RepurposeInput) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetCustomInstructions

`func (o *RepurposeInput) GetCustomInstructions() string`

GetCustomInstructions returns the CustomInstructions field if non-nil, zero value otherwise.

### GetCustomInstructionsOk

`func (o *RepurposeInput) GetCustomInstructionsOk() (*string, bool)`

GetCustomInstructionsOk returns a tuple with the CustomInstructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomInstructions

`func (o *RepurposeInput) SetCustomInstructions(v string)`

SetCustomInstructions sets CustomInstructions field to given value.

### HasCustomInstructions

`func (o *RepurposeInput) HasCustomInstructions() bool`

HasCustomInstructions returns a boolean if a field has been set.

### GetCarousel

`func (o *RepurposeInput) GetCarousel() bool`

GetCarousel returns the Carousel field if non-nil, zero value otherwise.

### GetCarouselOk

`func (o *RepurposeInput) GetCarouselOk() (*bool, bool)`

GetCarouselOk returns a tuple with the Carousel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCarousel

`func (o *RepurposeInput) SetCarousel(v bool)`

SetCarousel sets Carousel field to given value.

### HasCarousel

`func (o *RepurposeInput) HasCarousel() bool`

HasCarousel returns a boolean if a field has been set.

### GetSlideCount

`func (o *RepurposeInput) GetSlideCount() int32`

GetSlideCount returns the SlideCount field if non-nil, zero value otherwise.

### GetSlideCountOk

`func (o *RepurposeInput) GetSlideCountOk() (*int32, bool)`

GetSlideCountOk returns a tuple with the SlideCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlideCount

`func (o *RepurposeInput) SetSlideCount(v int32)`

SetSlideCount sets SlideCount field to given value.

### HasSlideCount

`func (o *RepurposeInput) HasSlideCount() bool`

HasSlideCount returns a boolean if a field has been set.

### GetTheme

`func (o *RepurposeInput) GetTheme() RepurposeInputTheme`

GetTheme returns the Theme field if non-nil, zero value otherwise.

### GetThemeOk

`func (o *RepurposeInput) GetThemeOk() (*RepurposeInputTheme, bool)`

GetThemeOk returns a tuple with the Theme field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTheme

`func (o *RepurposeInput) SetTheme(v RepurposeInputTheme)`

SetTheme sets Theme field to given value.

### HasTheme

`func (o *RepurposeInput) HasTheme() bool`

HasTheme returns a boolean if a field has been set.

### GetCreatePost

`func (o *RepurposeInput) GetCreatePost() bool`

GetCreatePost returns the CreatePost field if non-nil, zero value otherwise.

### GetCreatePostOk

`func (o *RepurposeInput) GetCreatePostOk() (*bool, bool)`

GetCreatePostOk returns a tuple with the CreatePost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatePost

`func (o *RepurposeInput) SetCreatePost(v bool)`

SetCreatePost sets CreatePost field to given value.

### HasCreatePost

`func (o *RepurposeInput) HasCreatePost() bool`

HasCreatePost returns a boolean if a field has been set.

### GetUseBrandVoice

`func (o *RepurposeInput) GetUseBrandVoice() bool`

GetUseBrandVoice returns the UseBrandVoice field if non-nil, zero value otherwise.

### GetUseBrandVoiceOk

`func (o *RepurposeInput) GetUseBrandVoiceOk() (*bool, bool)`

GetUseBrandVoiceOk returns a tuple with the UseBrandVoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseBrandVoice

`func (o *RepurposeInput) SetUseBrandVoice(v bool)`

SetUseBrandVoice sets UseBrandVoice field to given value.

### HasUseBrandVoice

`func (o *RepurposeInput) HasUseBrandVoice() bool`

HasUseBrandVoice returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


