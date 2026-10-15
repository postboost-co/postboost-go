# FreeToolCalculateCropResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Crop** | Pointer to [**FreeToolCalculateCropResponseCrop**](FreeToolCalculateCropResponseCrop.md) |  | [optional] 
**Output** | Pointer to [**FreeToolCalculateCropResponseOutput**](FreeToolCalculateCropResponseOutput.md) |  | [optional] 
**Image** | Pointer to [**FreeToolCalculateCropResponseImage**](FreeToolCalculateCropResponseImage.md) |  | [optional] 
**Scale** | Pointer to **float32** | Output pixels per source pixel, 4 decimals. | [optional] 
**Upscaled** | Pointer to **bool** | True when the source is enlarged (scale above 1), which can look soft. | [optional] 

## Methods

### NewFreeToolCalculateCropResponse

`func NewFreeToolCalculateCropResponse() *FreeToolCalculateCropResponse`

NewFreeToolCalculateCropResponse instantiates a new FreeToolCalculateCropResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCalculateCropResponseWithDefaults

`func NewFreeToolCalculateCropResponseWithDefaults() *FreeToolCalculateCropResponse`

NewFreeToolCalculateCropResponseWithDefaults instantiates a new FreeToolCalculateCropResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCrop

`func (o *FreeToolCalculateCropResponse) GetCrop() FreeToolCalculateCropResponseCrop`

GetCrop returns the Crop field if non-nil, zero value otherwise.

### GetCropOk

`func (o *FreeToolCalculateCropResponse) GetCropOk() (*FreeToolCalculateCropResponseCrop, bool)`

GetCropOk returns a tuple with the Crop field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCrop

`func (o *FreeToolCalculateCropResponse) SetCrop(v FreeToolCalculateCropResponseCrop)`

SetCrop sets Crop field to given value.

### HasCrop

`func (o *FreeToolCalculateCropResponse) HasCrop() bool`

HasCrop returns a boolean if a field has been set.

### GetOutput

`func (o *FreeToolCalculateCropResponse) GetOutput() FreeToolCalculateCropResponseOutput`

GetOutput returns the Output field if non-nil, zero value otherwise.

### GetOutputOk

`func (o *FreeToolCalculateCropResponse) GetOutputOk() (*FreeToolCalculateCropResponseOutput, bool)`

GetOutputOk returns a tuple with the Output field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutput

`func (o *FreeToolCalculateCropResponse) SetOutput(v FreeToolCalculateCropResponseOutput)`

SetOutput sets Output field to given value.

### HasOutput

`func (o *FreeToolCalculateCropResponse) HasOutput() bool`

HasOutput returns a boolean if a field has been set.

### GetImage

`func (o *FreeToolCalculateCropResponse) GetImage() FreeToolCalculateCropResponseImage`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *FreeToolCalculateCropResponse) GetImageOk() (*FreeToolCalculateCropResponseImage, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *FreeToolCalculateCropResponse) SetImage(v FreeToolCalculateCropResponseImage)`

SetImage sets Image field to given value.

### HasImage

`func (o *FreeToolCalculateCropResponse) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetScale

`func (o *FreeToolCalculateCropResponse) GetScale() float32`

GetScale returns the Scale field if non-nil, zero value otherwise.

### GetScaleOk

`func (o *FreeToolCalculateCropResponse) GetScaleOk() (*float32, bool)`

GetScaleOk returns a tuple with the Scale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScale

`func (o *FreeToolCalculateCropResponse) SetScale(v float32)`

SetScale sets Scale field to given value.

### HasScale

`func (o *FreeToolCalculateCropResponse) HasScale() bool`

HasScale returns a boolean if a field has been set.

### GetUpscaled

`func (o *FreeToolCalculateCropResponse) GetUpscaled() bool`

GetUpscaled returns the Upscaled field if non-nil, zero value otherwise.

### GetUpscaledOk

`func (o *FreeToolCalculateCropResponse) GetUpscaledOk() (*bool, bool)`

GetUpscaledOk returns a tuple with the Upscaled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpscaled

`func (o *FreeToolCalculateCropResponse) SetUpscaled(v bool)`

SetUpscaled sets Upscaled field to given value.

### HasUpscaled

`func (o *FreeToolCalculateCropResponse) HasUpscaled() bool`

HasUpscaled returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


