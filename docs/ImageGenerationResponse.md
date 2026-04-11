# ImageGenerationResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Images** | [**[]GeneratedImageItem**](GeneratedImageItem.md) |  | 
**PromptUsed** | **string** |  | 
**RevisedPrompt** | Pointer to **string** |  | [optional] 
**AspectRatio** | **string** |  | 
**Quality** | **string** |  | 
**CreditsUsed** | **int32** |  | 
**CreditsRemaining** | Pointer to **int32** |  | [optional] 

## Methods

### NewImageGenerationResponse

`func NewImageGenerationResponse(images []GeneratedImageItem, promptUsed string, aspectRatio string, quality string, creditsUsed int32, ) *ImageGenerationResponse`

NewImageGenerationResponse instantiates a new ImageGenerationResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageGenerationResponseWithDefaults

`func NewImageGenerationResponseWithDefaults() *ImageGenerationResponse`

NewImageGenerationResponseWithDefaults instantiates a new ImageGenerationResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImages

`func (o *ImageGenerationResponse) GetImages() []GeneratedImageItem`

GetImages returns the Images field if non-nil, zero value otherwise.

### GetImagesOk

`func (o *ImageGenerationResponse) GetImagesOk() (*[]GeneratedImageItem, bool)`

GetImagesOk returns a tuple with the Images field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImages

`func (o *ImageGenerationResponse) SetImages(v []GeneratedImageItem)`

SetImages sets Images field to given value.


### GetPromptUsed

`func (o *ImageGenerationResponse) GetPromptUsed() string`

GetPromptUsed returns the PromptUsed field if non-nil, zero value otherwise.

### GetPromptUsedOk

`func (o *ImageGenerationResponse) GetPromptUsedOk() (*string, bool)`

GetPromptUsedOk returns a tuple with the PromptUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPromptUsed

`func (o *ImageGenerationResponse) SetPromptUsed(v string)`

SetPromptUsed sets PromptUsed field to given value.


### GetRevisedPrompt

`func (o *ImageGenerationResponse) GetRevisedPrompt() string`

GetRevisedPrompt returns the RevisedPrompt field if non-nil, zero value otherwise.

### GetRevisedPromptOk

`func (o *ImageGenerationResponse) GetRevisedPromptOk() (*string, bool)`

GetRevisedPromptOk returns a tuple with the RevisedPrompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRevisedPrompt

`func (o *ImageGenerationResponse) SetRevisedPrompt(v string)`

SetRevisedPrompt sets RevisedPrompt field to given value.

### HasRevisedPrompt

`func (o *ImageGenerationResponse) HasRevisedPrompt() bool`

HasRevisedPrompt returns a boolean if a field has been set.

### GetAspectRatio

`func (o *ImageGenerationResponse) GetAspectRatio() string`

GetAspectRatio returns the AspectRatio field if non-nil, zero value otherwise.

### GetAspectRatioOk

`func (o *ImageGenerationResponse) GetAspectRatioOk() (*string, bool)`

GetAspectRatioOk returns a tuple with the AspectRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAspectRatio

`func (o *ImageGenerationResponse) SetAspectRatio(v string)`

SetAspectRatio sets AspectRatio field to given value.


### GetQuality

`func (o *ImageGenerationResponse) GetQuality() string`

GetQuality returns the Quality field if non-nil, zero value otherwise.

### GetQualityOk

`func (o *ImageGenerationResponse) GetQualityOk() (*string, bool)`

GetQualityOk returns a tuple with the Quality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuality

`func (o *ImageGenerationResponse) SetQuality(v string)`

SetQuality sets Quality field to given value.


### GetCreditsUsed

`func (o *ImageGenerationResponse) GetCreditsUsed() int32`

GetCreditsUsed returns the CreditsUsed field if non-nil, zero value otherwise.

### GetCreditsUsedOk

`func (o *ImageGenerationResponse) GetCreditsUsedOk() (*int32, bool)`

GetCreditsUsedOk returns a tuple with the CreditsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsUsed

`func (o *ImageGenerationResponse) SetCreditsUsed(v int32)`

SetCreditsUsed sets CreditsUsed field to given value.


### GetCreditsRemaining

`func (o *ImageGenerationResponse) GetCreditsRemaining() int32`

GetCreditsRemaining returns the CreditsRemaining field if non-nil, zero value otherwise.

### GetCreditsRemainingOk

`func (o *ImageGenerationResponse) GetCreditsRemainingOk() (*int32, bool)`

GetCreditsRemainingOk returns a tuple with the CreditsRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsRemaining

`func (o *ImageGenerationResponse) SetCreditsRemaining(v int32)`

SetCreditsRemaining sets CreditsRemaining field to given value.

### HasCreditsRemaining

`func (o *ImageGenerationResponse) HasCreditsRemaining() bool`

HasCreditsRemaining returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


