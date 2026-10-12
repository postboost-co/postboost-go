# ImageGenerate200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**ImageGenerationResponse**](ImageGenerationResponse.md) |  | 
**Meta** | Pointer to [**BrandVoiceMeta**](BrandVoiceMeta.md) |  | [optional] 

## Methods

### NewImageGenerate200Response

`func NewImageGenerate200Response(data ImageGenerationResponse, ) *ImageGenerate200Response`

NewImageGenerate200Response instantiates a new ImageGenerate200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageGenerate200ResponseWithDefaults

`func NewImageGenerate200ResponseWithDefaults() *ImageGenerate200Response`

NewImageGenerate200ResponseWithDefaults instantiates a new ImageGenerate200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ImageGenerate200Response) GetData() ImageGenerationResponse`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ImageGenerate200Response) GetDataOk() (*ImageGenerationResponse, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ImageGenerate200Response) SetData(v ImageGenerationResponse)`

SetData sets Data field to given value.


### GetMeta

`func (o *ImageGenerate200Response) GetMeta() BrandVoiceMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ImageGenerate200Response) GetMetaOk() (*BrandVoiceMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ImageGenerate200Response) SetMeta(v BrandVoiceMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ImageGenerate200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


