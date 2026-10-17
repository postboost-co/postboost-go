# FreeToolCalculateCarouselSlicesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Slides** | Pointer to [**[]FreeToolCalculateCarouselSlicesResponseSlidesInner**](FreeToolCalculateCarouselSlicesResponseSlidesInner.md) | The part of the source image each slide shows, left to right, in source pixels. | [optional] 
**Output** | Pointer to [**FreeToolCalculateCarouselSlicesResponseOutput**](FreeToolCalculateCarouselSlicesResponseOutput.md) |  | [optional] 
**Scale** | Pointer to **float32** | Output pixels per source pixel, 4 decimals. | [optional] 
**Upscaled** | Pointer to **bool** | True when the source is enlarged (scale above 1), which can look soft. | [optional] 
**Warnings** | Pointer to **[]string** | Upscaling and how much of the source is cropped away. | [optional] 

## Methods

### NewFreeToolCalculateCarouselSlicesResponse

`func NewFreeToolCalculateCarouselSlicesResponse() *FreeToolCalculateCarouselSlicesResponse`

NewFreeToolCalculateCarouselSlicesResponse instantiates a new FreeToolCalculateCarouselSlicesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCalculateCarouselSlicesResponseWithDefaults

`func NewFreeToolCalculateCarouselSlicesResponseWithDefaults() *FreeToolCalculateCarouselSlicesResponse`

NewFreeToolCalculateCarouselSlicesResponseWithDefaults instantiates a new FreeToolCalculateCarouselSlicesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSlides

`func (o *FreeToolCalculateCarouselSlicesResponse) GetSlides() []FreeToolCalculateCarouselSlicesResponseSlidesInner`

GetSlides returns the Slides field if non-nil, zero value otherwise.

### GetSlidesOk

`func (o *FreeToolCalculateCarouselSlicesResponse) GetSlidesOk() (*[]FreeToolCalculateCarouselSlicesResponseSlidesInner, bool)`

GetSlidesOk returns a tuple with the Slides field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlides

`func (o *FreeToolCalculateCarouselSlicesResponse) SetSlides(v []FreeToolCalculateCarouselSlicesResponseSlidesInner)`

SetSlides sets Slides field to given value.

### HasSlides

`func (o *FreeToolCalculateCarouselSlicesResponse) HasSlides() bool`

HasSlides returns a boolean if a field has been set.

### GetOutput

`func (o *FreeToolCalculateCarouselSlicesResponse) GetOutput() FreeToolCalculateCarouselSlicesResponseOutput`

GetOutput returns the Output field if non-nil, zero value otherwise.

### GetOutputOk

`func (o *FreeToolCalculateCarouselSlicesResponse) GetOutputOk() (*FreeToolCalculateCarouselSlicesResponseOutput, bool)`

GetOutputOk returns a tuple with the Output field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutput

`func (o *FreeToolCalculateCarouselSlicesResponse) SetOutput(v FreeToolCalculateCarouselSlicesResponseOutput)`

SetOutput sets Output field to given value.

### HasOutput

`func (o *FreeToolCalculateCarouselSlicesResponse) HasOutput() bool`

HasOutput returns a boolean if a field has been set.

### GetScale

`func (o *FreeToolCalculateCarouselSlicesResponse) GetScale() float32`

GetScale returns the Scale field if non-nil, zero value otherwise.

### GetScaleOk

`func (o *FreeToolCalculateCarouselSlicesResponse) GetScaleOk() (*float32, bool)`

GetScaleOk returns a tuple with the Scale field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScale

`func (o *FreeToolCalculateCarouselSlicesResponse) SetScale(v float32)`

SetScale sets Scale field to given value.

### HasScale

`func (o *FreeToolCalculateCarouselSlicesResponse) HasScale() bool`

HasScale returns a boolean if a field has been set.

### GetUpscaled

`func (o *FreeToolCalculateCarouselSlicesResponse) GetUpscaled() bool`

GetUpscaled returns the Upscaled field if non-nil, zero value otherwise.

### GetUpscaledOk

`func (o *FreeToolCalculateCarouselSlicesResponse) GetUpscaledOk() (*bool, bool)`

GetUpscaledOk returns a tuple with the Upscaled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpscaled

`func (o *FreeToolCalculateCarouselSlicesResponse) SetUpscaled(v bool)`

SetUpscaled sets Upscaled field to given value.

### HasUpscaled

`func (o *FreeToolCalculateCarouselSlicesResponse) HasUpscaled() bool`

HasUpscaled returns a boolean if a field has been set.

### GetWarnings

`func (o *FreeToolCalculateCarouselSlicesResponse) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *FreeToolCalculateCarouselSlicesResponse) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *FreeToolCalculateCarouselSlicesResponse) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *FreeToolCalculateCarouselSlicesResponse) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


