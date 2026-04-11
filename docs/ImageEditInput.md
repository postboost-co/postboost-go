# ImageEditInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MediaUuid** | **string** | UUID of the source media item to edit | 
**Prompt** | **string** | Describe what to change in the image | 
**MaskUuid** | Pointer to **string** | UUID of a mask image. Transparent areas will be edited. | [optional] 
**AspectRatio** | Pointer to **string** |  | [optional] [default to "1:1"]
**Count** | Pointer to **int32** |  | [optional] [default to 1]
**Quality** | Pointer to **string** |  | [optional] [default to "standard"]

## Methods

### NewImageEditInput

`func NewImageEditInput(mediaUuid string, prompt string, ) *ImageEditInput`

NewImageEditInput instantiates a new ImageEditInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageEditInputWithDefaults

`func NewImageEditInputWithDefaults() *ImageEditInput`

NewImageEditInputWithDefaults instantiates a new ImageEditInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMediaUuid

`func (o *ImageEditInput) GetMediaUuid() string`

GetMediaUuid returns the MediaUuid field if non-nil, zero value otherwise.

### GetMediaUuidOk

`func (o *ImageEditInput) GetMediaUuidOk() (*string, bool)`

GetMediaUuidOk returns a tuple with the MediaUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMediaUuid

`func (o *ImageEditInput) SetMediaUuid(v string)`

SetMediaUuid sets MediaUuid field to given value.


### GetPrompt

`func (o *ImageEditInput) GetPrompt() string`

GetPrompt returns the Prompt field if non-nil, zero value otherwise.

### GetPromptOk

`func (o *ImageEditInput) GetPromptOk() (*string, bool)`

GetPromptOk returns a tuple with the Prompt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrompt

`func (o *ImageEditInput) SetPrompt(v string)`

SetPrompt sets Prompt field to given value.


### GetMaskUuid

`func (o *ImageEditInput) GetMaskUuid() string`

GetMaskUuid returns the MaskUuid field if non-nil, zero value otherwise.

### GetMaskUuidOk

`func (o *ImageEditInput) GetMaskUuidOk() (*string, bool)`

GetMaskUuidOk returns a tuple with the MaskUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaskUuid

`func (o *ImageEditInput) SetMaskUuid(v string)`

SetMaskUuid sets MaskUuid field to given value.

### HasMaskUuid

`func (o *ImageEditInput) HasMaskUuid() bool`

HasMaskUuid returns a boolean if a field has been set.

### GetAspectRatio

`func (o *ImageEditInput) GetAspectRatio() string`

GetAspectRatio returns the AspectRatio field if non-nil, zero value otherwise.

### GetAspectRatioOk

`func (o *ImageEditInput) GetAspectRatioOk() (*string, bool)`

GetAspectRatioOk returns a tuple with the AspectRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAspectRatio

`func (o *ImageEditInput) SetAspectRatio(v string)`

SetAspectRatio sets AspectRatio field to given value.

### HasAspectRatio

`func (o *ImageEditInput) HasAspectRatio() bool`

HasAspectRatio returns a boolean if a field has been set.

### GetCount

`func (o *ImageEditInput) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *ImageEditInput) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *ImageEditInput) SetCount(v int32)`

SetCount sets Count field to given value.

### HasCount

`func (o *ImageEditInput) HasCount() bool`

HasCount returns a boolean if a field has been set.

### GetQuality

`func (o *ImageEditInput) GetQuality() string`

GetQuality returns the Quality field if non-nil, zero value otherwise.

### GetQualityOk

`func (o *ImageEditInput) GetQualityOk() (*string, bool)`

GetQualityOk returns a tuple with the Quality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuality

`func (o *ImageEditInput) SetQuality(v string)`

SetQuality sets Quality field to given value.

### HasQuality

`func (o *ImageEditInput) HasQuality() bool`

HasQuality returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


