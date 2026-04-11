# ImageVariationsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Images** | [**[]GeneratedImageItem**](GeneratedImageItem.md) |  | 
**AspectRatio** | **string** |  | 
**Quality** | **string** |  | 
**CreditsUsed** | **int32** |  | 
**CreditsRemaining** | Pointer to **int32** |  | [optional] 

## Methods

### NewImageVariationsResponse

`func NewImageVariationsResponse(images []GeneratedImageItem, aspectRatio string, quality string, creditsUsed int32, ) *ImageVariationsResponse`

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

`func (o *ImageVariationsResponse) GetImages() []GeneratedImageItem`

GetImages returns the Images field if non-nil, zero value otherwise.

### GetImagesOk

`func (o *ImageVariationsResponse) GetImagesOk() (*[]GeneratedImageItem, bool)`

GetImagesOk returns a tuple with the Images field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImages

`func (o *ImageVariationsResponse) SetImages(v []GeneratedImageItem)`

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


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


