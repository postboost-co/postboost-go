# ImageAltTextResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MediaUuid** | **string** |  | 
**AltText** | **string** |  | 
**CreditsUsed** | **int32** |  | 
**CreditsRemaining** | Pointer to **int32** |  | [optional] 

## Methods

### NewImageAltTextResponse

`func NewImageAltTextResponse(mediaUuid string, altText string, creditsUsed int32, ) *ImageAltTextResponse`

NewImageAltTextResponse instantiates a new ImageAltTextResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewImageAltTextResponseWithDefaults

`func NewImageAltTextResponseWithDefaults() *ImageAltTextResponse`

NewImageAltTextResponseWithDefaults instantiates a new ImageAltTextResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMediaUuid

`func (o *ImageAltTextResponse) GetMediaUuid() string`

GetMediaUuid returns the MediaUuid field if non-nil, zero value otherwise.

### GetMediaUuidOk

`func (o *ImageAltTextResponse) GetMediaUuidOk() (*string, bool)`

GetMediaUuidOk returns a tuple with the MediaUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMediaUuid

`func (o *ImageAltTextResponse) SetMediaUuid(v string)`

SetMediaUuid sets MediaUuid field to given value.


### GetAltText

`func (o *ImageAltTextResponse) GetAltText() string`

GetAltText returns the AltText field if non-nil, zero value otherwise.

### GetAltTextOk

`func (o *ImageAltTextResponse) GetAltTextOk() (*string, bool)`

GetAltTextOk returns a tuple with the AltText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAltText

`func (o *ImageAltTextResponse) SetAltText(v string)`

SetAltText sets AltText field to given value.


### GetCreditsUsed

`func (o *ImageAltTextResponse) GetCreditsUsed() int32`

GetCreditsUsed returns the CreditsUsed field if non-nil, zero value otherwise.

### GetCreditsUsedOk

`func (o *ImageAltTextResponse) GetCreditsUsedOk() (*int32, bool)`

GetCreditsUsedOk returns a tuple with the CreditsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsUsed

`func (o *ImageAltTextResponse) SetCreditsUsed(v int32)`

SetCreditsUsed sets CreditsUsed field to given value.


### GetCreditsRemaining

`func (o *ImageAltTextResponse) GetCreditsRemaining() int32`

GetCreditsRemaining returns the CreditsRemaining field if non-nil, zero value otherwise.

### GetCreditsRemainingOk

`func (o *ImageAltTextResponse) GetCreditsRemainingOk() (*int32, bool)`

GetCreditsRemainingOk returns a tuple with the CreditsRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsRemaining

`func (o *ImageAltTextResponse) SetCreditsRemaining(v int32)`

SetCreditsRemaining sets CreditsRemaining field to given value.

### HasCreditsRemaining

`func (o *ImageAltTextResponse) HasCreditsRemaining() bool`

HasCreditsRemaining returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


