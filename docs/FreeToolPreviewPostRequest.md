# FreeToolPreviewPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** |  | 
**InstagramRatio** | Pointer to **string** | Image ratio of the Instagram feed post. | [optional] [default to "1:1"]
**ImageWidth** | Pointer to **int32** | Image width in pixels. Give it with image_height to get display_ratio and cropped per card. | [optional] 
**ImageHeight** | Pointer to **int32** | Image height in pixels. Give it with image_width. | [optional] 

## Methods

### NewFreeToolPreviewPostRequest

`func NewFreeToolPreviewPostRequest(text string, ) *FreeToolPreviewPostRequest`

NewFreeToolPreviewPostRequest instantiates a new FreeToolPreviewPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolPreviewPostRequestWithDefaults

`func NewFreeToolPreviewPostRequestWithDefaults() *FreeToolPreviewPostRequest`

NewFreeToolPreviewPostRequestWithDefaults instantiates a new FreeToolPreviewPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolPreviewPostRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolPreviewPostRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolPreviewPostRequest) SetText(v string)`

SetText sets Text field to given value.


### GetInstagramRatio

`func (o *FreeToolPreviewPostRequest) GetInstagramRatio() string`

GetInstagramRatio returns the InstagramRatio field if non-nil, zero value otherwise.

### GetInstagramRatioOk

`func (o *FreeToolPreviewPostRequest) GetInstagramRatioOk() (*string, bool)`

GetInstagramRatioOk returns a tuple with the InstagramRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstagramRatio

`func (o *FreeToolPreviewPostRequest) SetInstagramRatio(v string)`

SetInstagramRatio sets InstagramRatio field to given value.

### HasInstagramRatio

`func (o *FreeToolPreviewPostRequest) HasInstagramRatio() bool`

HasInstagramRatio returns a boolean if a field has been set.

### GetImageWidth

`func (o *FreeToolPreviewPostRequest) GetImageWidth() int32`

GetImageWidth returns the ImageWidth field if non-nil, zero value otherwise.

### GetImageWidthOk

`func (o *FreeToolPreviewPostRequest) GetImageWidthOk() (*int32, bool)`

GetImageWidthOk returns a tuple with the ImageWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageWidth

`func (o *FreeToolPreviewPostRequest) SetImageWidth(v int32)`

SetImageWidth sets ImageWidth field to given value.

### HasImageWidth

`func (o *FreeToolPreviewPostRequest) HasImageWidth() bool`

HasImageWidth returns a boolean if a field has been set.

### GetImageHeight

`func (o *FreeToolPreviewPostRequest) GetImageHeight() int32`

GetImageHeight returns the ImageHeight field if non-nil, zero value otherwise.

### GetImageHeightOk

`func (o *FreeToolPreviewPostRequest) GetImageHeightOk() (*int32, bool)`

GetImageHeightOk returns a tuple with the ImageHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageHeight

`func (o *FreeToolPreviewPostRequest) SetImageHeight(v int32)`

SetImageHeight sets ImageHeight field to given value.

### HasImageHeight

`func (o *FreeToolPreviewPostRequest) HasImageHeight() bool`

HasImageHeight returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


