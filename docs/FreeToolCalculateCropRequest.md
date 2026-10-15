# FreeToolCalculateCropRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Width** | **int32** | Source image width in pixels. | 
**Height** | **int32** | Source image height in pixels. | 
**Network** | Pointer to **string** | Network key from getImageSizes (&#x60;network_key&#x60;), e.g. &#x60;instagram&#x60;. With &#x60;format&#x60;, picks the target size. | [optional] 
**Format** | Pointer to **string** | Format key from getImageSizes (&#x60;format_key&#x60;), e.g. &#x60;feed-square&#x60;. | [optional] 
**TargetWidth** | Pointer to **int32** | Target width in pixels, instead of &#x60;network&#x60; + &#x60;format&#x60;. | [optional] 
**TargetHeight** | Pointer to **int32** | Target height in pixels, instead of &#x60;network&#x60; + &#x60;format&#x60;. | [optional] 
**Fit** | Pointer to **string** | &#x60;cover&#x60; crops to fill the target; &#x60;contain&#x60; keeps the whole image and centres it. | [optional] [default to "cover"]

## Methods

### NewFreeToolCalculateCropRequest

`func NewFreeToolCalculateCropRequest(width int32, height int32, ) *FreeToolCalculateCropRequest`

NewFreeToolCalculateCropRequest instantiates a new FreeToolCalculateCropRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCalculateCropRequestWithDefaults

`func NewFreeToolCalculateCropRequestWithDefaults() *FreeToolCalculateCropRequest`

NewFreeToolCalculateCropRequestWithDefaults instantiates a new FreeToolCalculateCropRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWidth

`func (o *FreeToolCalculateCropRequest) GetWidth() int32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *FreeToolCalculateCropRequest) GetWidthOk() (*int32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *FreeToolCalculateCropRequest) SetWidth(v int32)`

SetWidth sets Width field to given value.


### GetHeight

`func (o *FreeToolCalculateCropRequest) GetHeight() int32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *FreeToolCalculateCropRequest) GetHeightOk() (*int32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *FreeToolCalculateCropRequest) SetHeight(v int32)`

SetHeight sets Height field to given value.


### GetNetwork

`func (o *FreeToolCalculateCropRequest) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *FreeToolCalculateCropRequest) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *FreeToolCalculateCropRequest) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *FreeToolCalculateCropRequest) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetFormat

`func (o *FreeToolCalculateCropRequest) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *FreeToolCalculateCropRequest) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *FreeToolCalculateCropRequest) SetFormat(v string)`

SetFormat sets Format field to given value.

### HasFormat

`func (o *FreeToolCalculateCropRequest) HasFormat() bool`

HasFormat returns a boolean if a field has been set.

### GetTargetWidth

`func (o *FreeToolCalculateCropRequest) GetTargetWidth() int32`

GetTargetWidth returns the TargetWidth field if non-nil, zero value otherwise.

### GetTargetWidthOk

`func (o *FreeToolCalculateCropRequest) GetTargetWidthOk() (*int32, bool)`

GetTargetWidthOk returns a tuple with the TargetWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetWidth

`func (o *FreeToolCalculateCropRequest) SetTargetWidth(v int32)`

SetTargetWidth sets TargetWidth field to given value.

### HasTargetWidth

`func (o *FreeToolCalculateCropRequest) HasTargetWidth() bool`

HasTargetWidth returns a boolean if a field has been set.

### GetTargetHeight

`func (o *FreeToolCalculateCropRequest) GetTargetHeight() int32`

GetTargetHeight returns the TargetHeight field if non-nil, zero value otherwise.

### GetTargetHeightOk

`func (o *FreeToolCalculateCropRequest) GetTargetHeightOk() (*int32, bool)`

GetTargetHeightOk returns a tuple with the TargetHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetHeight

`func (o *FreeToolCalculateCropRequest) SetTargetHeight(v int32)`

SetTargetHeight sets TargetHeight field to given value.

### HasTargetHeight

`func (o *FreeToolCalculateCropRequest) HasTargetHeight() bool`

HasTargetHeight returns a boolean if a field has been set.

### GetFit

`func (o *FreeToolCalculateCropRequest) GetFit() string`

GetFit returns the Fit field if non-nil, zero value otherwise.

### GetFitOk

`func (o *FreeToolCalculateCropRequest) GetFitOk() (*string, bool)`

GetFitOk returns a tuple with the Fit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFit

`func (o *FreeToolCalculateCropRequest) SetFit(v string)`

SetFit sets Fit field to given value.

### HasFit

`func (o *FreeToolCalculateCropRequest) HasFit() bool`

HasFit returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


