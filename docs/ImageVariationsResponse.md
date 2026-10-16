# ImageVariationsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Images** | [**[]Media**](Media.md) |  | 
**AspectRatio** | **string** |  | 
**Quality** | **string** |  | 
**CreditsUsed** | **int32** | Text credits only. 0 while the image credit pool is on; &#x60;count × credit_weight&#x60; when it is switched off. | 
**CreditsRemaining** | Pointer to **NullableInt32** | Text credits left this billing cycle (null &#x3D; no limit). | [optional] 
**ImageCreditsUsed** | **int32** | Image credits this call spent (1 per image; 0 when the image credit pool is switched off). | 
**ImageCreditsRemaining** | **NullableInt32** | Image credits left this month (null &#x3D; no limit, or the image credit pool is switched off). | 

## Methods

### NewImageVariationsResponse

`func NewImageVariationsResponse(images []Media, aspectRatio string, quality string, creditsUsed int32, imageCreditsUsed int32, imageCreditsRemaining NullableInt32, ) *ImageVariationsResponse`

NewImageVariationsResponse instantiates a new ImageVariationsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageVariationsResponseWithDefaults

`func NewImageVariationsResponseWithDefaults() *ImageVariationsResponse`

NewImageVariationsResponseWithDefaults instantiates a new ImageVariationsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImages

`func (o *ImageVariationsResponse) GetImages() []Media`

GetImages returns the Images field if non-nil, zero value otherwise.

### GetImagesOk

`func (o *ImageVariationsResponse) GetImagesOk() (*[]Media, bool)`

GetImagesOk returns a tuple with the Images field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImages

`func (o *ImageVariationsResponse) SetImages(v []Media)`

SetImages sets Images field to given value.


### GetAspectRatio

`func (o *ImageVariationsResponse) GetAspectRatio() string`

GetAspectRatio returns the AspectRatio field if non-nil, zero value otherwise.

### GetAspectRatioOk

`func (o *ImageVariationsResponse) GetAspectRatioOk() (*string, bool)`

GetAspectRatioOk returns a tuple with the AspectRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAspectRatio

`func (o *ImageVariationsResponse) SetAspectRatio(v string)`

SetAspectRatio sets AspectRatio field to given value.


### GetQuality

`func (o *ImageVariationsResponse) GetQuality() string`

GetQuality returns the Quality field if non-nil, zero value otherwise.

### GetQualityOk

`func (o *ImageVariationsResponse) GetQualityOk() (*string, bool)`

GetQualityOk returns a tuple with the Quality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuality

`func (o *ImageVariationsResponse) SetQuality(v string)`

SetQuality sets Quality field to given value.


### GetCreditsUsed

`func (o *ImageVariationsResponse) GetCreditsUsed() int32`

GetCreditsUsed returns the CreditsUsed field if non-nil, zero value otherwise.

### GetCreditsUsedOk

`func (o *ImageVariationsResponse) GetCreditsUsedOk() (*int32, bool)`

GetCreditsUsedOk returns a tuple with the CreditsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsUsed

`func (o *ImageVariationsResponse) SetCreditsUsed(v int32)`

SetCreditsUsed sets CreditsUsed field to given value.


### GetCreditsRemaining

`func (o *ImageVariationsResponse) GetCreditsRemaining() int32`

GetCreditsRemaining returns the CreditsRemaining field if non-nil, zero value otherwise.

### GetCreditsRemainingOk

`func (o *ImageVariationsResponse) GetCreditsRemainingOk() (*int32, bool)`

GetCreditsRemainingOk returns a tuple with the CreditsRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsRemaining

`func (o *ImageVariationsResponse) SetCreditsRemaining(v int32)`

SetCreditsRemaining sets CreditsRemaining field to given value.

### HasCreditsRemaining

`func (o *ImageVariationsResponse) HasCreditsRemaining() bool`

HasCreditsRemaining returns a boolean if a field has been set.

### SetCreditsRemainingNil

`func (o *ImageVariationsResponse) SetCreditsRemainingNil(b bool)`

 SetCreditsRemainingNil sets the value for CreditsRemaining to be an explicit nil

### UnsetCreditsRemaining
`func (o *ImageVariationsResponse) UnsetCreditsRemaining()`

UnsetCreditsRemaining ensures that no value is present for CreditsRemaining, not even an explicit nil
### GetImageCreditsUsed

`func (o *ImageVariationsResponse) GetImageCreditsUsed() int32`

GetImageCreditsUsed returns the ImageCreditsUsed field if non-nil, zero value otherwise.

### GetImageCreditsUsedOk

`func (o *ImageVariationsResponse) GetImageCreditsUsedOk() (*int32, bool)`

GetImageCreditsUsedOk returns a tuple with the ImageCreditsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageCreditsUsed

`func (o *ImageVariationsResponse) SetImageCreditsUsed(v int32)`

SetImageCreditsUsed sets ImageCreditsUsed field to given value.


### GetImageCreditsRemaining

`func (o *ImageVariationsResponse) GetImageCreditsRemaining() int32`

GetImageCreditsRemaining returns the ImageCreditsRemaining field if non-nil, zero value otherwise.

### GetImageCreditsRemainingOk

`func (o *ImageVariationsResponse) GetImageCreditsRemainingOk() (*int32, bool)`

GetImageCreditsRemainingOk returns a tuple with the ImageCreditsRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageCreditsRemaining

`func (o *ImageVariationsResponse) SetImageCreditsRemaining(v int32)`

SetImageCreditsRemaining sets ImageCreditsRemaining field to given value.


### SetImageCreditsRemainingNil

`func (o *ImageVariationsResponse) SetImageCreditsRemainingNil(b bool)`

 SetImageCreditsRemainingNil sets the value for ImageCreditsRemaining to be an explicit nil

### UnsetImageCreditsRemaining
`func (o *ImageVariationsResponse) UnsetImageCreditsRemaining()`

UnsetImageCreditsRemaining ensures that no value is present for ImageCreditsRemaining, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


