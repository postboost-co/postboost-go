# ImageGenerateInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Caption** | Pointer to **string** | Social media caption. Triggers standard mode. Takes priority over prompt. | [optional] 
**Platform** | Pointer to **string** | Required when caption is provided. | [optional] 
**Template** | Pointer to **string** |  | [optional] 
**Style** | Pointer to **string** |  | [optional] 
**BrandVoice** | Pointer to **string** |  | [optional] 
**CustomInstructions** | Pointer to **string** |  | [optional] 
**Prompt** | Pointer to **string** | Developer escape hatch. Bypasses internal prompt builder. Ignored if caption is present. | [optional] 
**AspectRatio** | Pointer to **string** |  | [optional] [default to "1:1"]
**Count** | Pointer to **int32** |  | [optional] [default to 1]
**Quality** | Pointer to **string** |  | [optional] [default to "standard"]

## Methods

### NewImageGenerateInput

`func NewImageGenerateInput() *ImageGenerateInput`

NewImageGenerateInput instantiates a new ImageGenerateInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageGenerateInputWithDefaults

`func NewImageGenerateInputWithDefaults() *ImageGenerateInput`

NewImageGenerateInputWithDefaults instantiates a new ImageGenerateInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCaption

`func (o *ImageGenerateInput) GetCaption() string`

GetCaption returns the Caption field if non-nil, zero value otherwise.

### GetCaptionOk

`func (o *ImageGenerateInput) GetCaptionOk() (*string, bool)`

GetCaptionOk returns a tuple with the Caption field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCaption

`func (o *ImageGenerateInput) SetCaption(v string)`

SetCaption sets Caption field to given value.

### HasCaption

`func (o *ImageGenerateInput) HasCaption() bool`

HasCaption returns a boolean if a field has been set.

### GetPlatform

`func (o *ImageGenerateInput) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *ImageGenerateInput) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *ImageGenerateInput) SetPlatform(v string)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *ImageGenerateInput) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### GetTemplate

`func (o *ImageGenerateInput) GetTemplate() string`

GetTemplate returns the Template field if non-nil, zero value otherwise.

### GetTemplateOk

`func (o *ImageGenerateInput) GetTemplateOk() (*string, bool)`

GetTemplateOk returns a tuple with the Template field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplate

`func (o *ImageGenerateInput) SetTemplate(v string)`

SetTemplate sets Template field to given value.

### HasTemplate

`func (o *ImageGenerateInput) HasTemplate() bool`

HasTemplate returns a boolean if a field has been set.

### GetStyle

`func (o *ImageGenerateInput) GetStyle() string`

GetStyle returns the Style field if non-nil, zero value otherwise.

### GetStyleOk

`func (o *ImageGenerateInput) GetStyleOk() (*string, bool)`

GetStyleOk returns a tuple with the Style field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStyle

`func (o *ImageGenerateInput) SetStyle(v string)`

SetStyle sets Style field to given value.

### HasStyle

`func (o *ImageGenerateInput) HasStyle() bool`

HasStyle returns a boolean if a field has been set.

### GetBrandVoice

`func (o *ImageGenerateInput) GetBrandVoice() string`

GetBrandVoice returns the BrandVoice field if non-nil, zero value otherwise.

### GetBrandVoiceOk

`func (o *ImageGenerateInput) GetBrandVoiceOk() (*string, bool)`

GetBrandVoiceOk returns a tuple with the BrandVoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandVoice

`func (o *ImageGenerateInput) SetBrandVoice(v string)`

SetBrandVoice sets BrandVoice field to given value.

### HasBrandVoice

`func (o *ImageGenerateInput) HasBrandVoice() bool`

HasBrandVoice returns a boolean if a field has been set.

### GetCustomInstructions

`func (o *ImageGenerateInput) GetCustomInstructions() string`

GetCustomInstructions returns the CustomInstructions field if non-nil, zero value otherwise.

### GetCustomInstructionsOk

`func (o *ImageGenerateInput) GetCustomInstructionsOk() (*string, bool)`

GetCustomInstructionsOk returns a tuple with the CustomInstructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomInstructions

`func (o *ImageGenerateInput) SetCustomInstructions(v string)`

SetCustomInstructions sets CustomInstructions field to given value.

### HasCustomInstructions

`func (o *ImageGenerateInput) HasCustomInstructions() bool`

HasCustomInstructions returns a boolean if a field has been set.

### GetPrompt

`func (o *ImageGenerateInput) GetPrompt() string`

GetPrompt returns the Prompt field if non-nil, zero value otherwise.

### GetPromptOk

`func (o *ImageGenerateInput) GetPromptOk() (*string, bool)`

GetPromptOk returns a tuple with the Prompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompt

`func (o *ImageGenerateInput) SetPrompt(v string)`

SetPrompt sets Prompt field to given value.

### HasPrompt

`func (o *ImageGenerateInput) HasPrompt() bool`

HasPrompt returns a boolean if a field has been set.

### GetAspectRatio

`func (o *ImageGenerateInput) GetAspectRatio() string`

GetAspectRatio returns the AspectRatio field if non-nil, zero value otherwise.

### GetAspectRatioOk

`func (o *ImageGenerateInput) GetAspectRatioOk() (*string, bool)`

GetAspectRatioOk returns a tuple with the AspectRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAspectRatio

`func (o *ImageGenerateInput) SetAspectRatio(v string)`

SetAspectRatio sets AspectRatio field to given value.

### HasAspectRatio

`func (o *ImageGenerateInput) HasAspectRatio() bool`

HasAspectRatio returns a boolean if a field has been set.

### GetCount

`func (o *ImageGenerateInput) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *ImageGenerateInput) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *ImageGenerateInput) SetCount(v int32)`

SetCount sets Count field to given value.

### HasCount

`func (o *ImageGenerateInput) HasCount() bool`

HasCount returns a boolean if a field has been set.

### GetQuality

`func (o *ImageGenerateInput) GetQuality() string`

GetQuality returns the Quality field if non-nil, zero value otherwise.

### GetQualityOk

`func (o *ImageGenerateInput) GetQualityOk() (*string, bool)`

GetQualityOk returns a tuple with the Quality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuality

`func (o *ImageGenerateInput) SetQuality(v string)`

SetQuality sets Quality field to given value.

### HasQuality

`func (o *ImageGenerateInput) HasQuality() bool`

HasQuality returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


