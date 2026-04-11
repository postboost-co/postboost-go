# ImageVariationsInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MediaUuid** | **string** |  | 
**AspectRatio** | Pointer to **string** |  | [optional] [default to "1:1"]
**Count** | Pointer to **int32** |  | [optional] [default to 1]
**Quality** | Pointer to **string** |  | [optional] [default to "standard"]

## Methods

### NewImageVariationsInput

`func NewImageVariationsInput(mediaUuid string, ) *ImageVariationsInput`

NewImageVariationsInput instantiates a new ImageVariationsInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageVariationsInputWithDefaults

`func NewImageVariationsInputWithDefaults() *ImageVariationsInput`

NewImageVariationsInputWithDefaults instantiates a new ImageVariationsInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMediaUuid

`func (o *ImageVariationsInput) GetMediaUuid() string`

GetMediaUuid returns the MediaUuid field if non-nil, zero value otherwise.

### GetMediaUuidOk

`func (o *ImageVariationsInput) GetMediaUuidOk() (*string, bool)`

GetMediaUuidOk returns a tuple with the MediaUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMediaUuid

`func (o *ImageVariationsInput) SetMediaUuid(v string)`

SetMediaUuid sets MediaUuid field to given value.


### GetAspectRatio

`func (o *ImageVariationsInput) GetAspectRatio() string`

GetAspectRatio returns the AspectRatio field if non-nil, zero value otherwise.

### GetAspectRatioOk

`func (o *ImageVariationsInput) GetAspectRatioOk() (*string, bool)`

GetAspectRatioOk returns a tuple with the AspectRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAspectRatio

`func (o *ImageVariationsInput) SetAspectRatio(v string)`

SetAspectRatio sets AspectRatio field to given value.

### HasAspectRatio

`func (o *ImageVariationsInput) HasAspectRatio() bool`

HasAspectRatio returns a boolean if a field has been set.

### GetCount

`func (o *ImageVariationsInput) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *ImageVariationsInput) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *ImageVariationsInput) SetCount(v int32)`

SetCount sets Count field to given value.

### HasCount

`func (o *ImageVariationsInput) HasCount() bool`

HasCount returns a boolean if a field has been set.

### GetQuality

`func (o *ImageVariationsInput) GetQuality() string`

GetQuality returns the Quality field if non-nil, zero value otherwise.

### GetQualityOk

`func (o *ImageVariationsInput) GetQualityOk() (*string, bool)`

GetQualityOk returns a tuple with the Quality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuality

`func (o *ImageVariationsInput) SetQuality(v string)`

SetQuality sets Quality field to given value.

### HasQuality

`func (o *ImageVariationsInput) HasQuality() bool`

HasQuality returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


