# FreeToolCalculateAspectRatioRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Width** | Pointer to **int32** | Width in pixels. | [optional] 
**Height** | Pointer to **int32** | Height in pixels. | [optional] 
**Ratio** | Pointer to **string** | Ratio as width:height, e.g. &#x60;16:9&#x60; or &#x60;1.91:1&#x60;. Give it with width or height to get the other side. | [optional] 

## Methods

### NewFreeToolCalculateAspectRatioRequest

`func NewFreeToolCalculateAspectRatioRequest() *FreeToolCalculateAspectRatioRequest`

NewFreeToolCalculateAspectRatioRequest instantiates a new FreeToolCalculateAspectRatioRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCalculateAspectRatioRequestWithDefaults

`func NewFreeToolCalculateAspectRatioRequestWithDefaults() *FreeToolCalculateAspectRatioRequest`

NewFreeToolCalculateAspectRatioRequestWithDefaults instantiates a new FreeToolCalculateAspectRatioRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWidth

`func (o *FreeToolCalculateAspectRatioRequest) GetWidth() int32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *FreeToolCalculateAspectRatioRequest) GetWidthOk() (*int32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *FreeToolCalculateAspectRatioRequest) SetWidth(v int32)`

SetWidth sets Width field to given value.

### HasWidth

`func (o *FreeToolCalculateAspectRatioRequest) HasWidth() bool`

HasWidth returns a boolean if a field has been set.

### GetHeight

`func (o *FreeToolCalculateAspectRatioRequest) GetHeight() int32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *FreeToolCalculateAspectRatioRequest) GetHeightOk() (*int32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *FreeToolCalculateAspectRatioRequest) SetHeight(v int32)`

SetHeight sets Height field to given value.

### HasHeight

`func (o *FreeToolCalculateAspectRatioRequest) HasHeight() bool`

HasHeight returns a boolean if a field has been set.

### GetRatio

`func (o *FreeToolCalculateAspectRatioRequest) GetRatio() string`

GetRatio returns the Ratio field if non-nil, zero value otherwise.

### GetRatioOk

`func (o *FreeToolCalculateAspectRatioRequest) GetRatioOk() (*string, bool)`

GetRatioOk returns a tuple with the Ratio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRatio

`func (o *FreeToolCalculateAspectRatioRequest) SetRatio(v string)`

SetRatio sets Ratio field to given value.

### HasRatio

`func (o *FreeToolCalculateAspectRatioRequest) HasRatio() bool`

HasRatio returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


