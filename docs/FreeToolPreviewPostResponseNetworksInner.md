# FreeToolPreviewPostResponseNetworksInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | Pointer to **string** |  | [optional] 
**Count** | Pointer to **int32** |  | [optional] 
**Limit** | Pointer to **int32** |  | [optional] 
**Over** | Pointer to **bool** |  | [optional] 
**Preview** | Pointer to **string** | What the feed shows before the \&quot;more\&quot; link (approximate; varies by device). | [optional] 
**Folded** | Pointer to **bool** |  | [optional] 
**MinRatio** | Pointer to **string** | Tallest image ratio the feed shows uncropped (Instagram: the chosen ratio). Taller images are cropped from the centre. | [optional] 
**MaxRatio** | Pointer to **string** | Widest image ratio the feed shows uncropped (Instagram: the chosen ratio). Wider images are cropped from the centre. | [optional] 
**DisplayRatio** | Pointer to **float32** | Width / height the card shows the image at, 2 decimals. Only when image_width and image_height are given. | [optional] 
**Cropped** | Pointer to **bool** | Whether the card crops the image. Only when image_width and image_height are given. | [optional] 

## Methods

### NewFreeToolPreviewPostResponseNetworksInner

`func NewFreeToolPreviewPostResponseNetworksInner() *FreeToolPreviewPostResponseNetworksInner`

NewFreeToolPreviewPostResponseNetworksInner instantiates a new FreeToolPreviewPostResponseNetworksInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolPreviewPostResponseNetworksInnerWithDefaults

`func NewFreeToolPreviewPostResponseNetworksInnerWithDefaults() *FreeToolPreviewPostResponseNetworksInner`

NewFreeToolPreviewPostResponseNetworksInnerWithDefaults instantiates a new FreeToolPreviewPostResponseNetworksInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *FreeToolPreviewPostResponseNetworksInner) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *FreeToolPreviewPostResponseNetworksInner) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *FreeToolPreviewPostResponseNetworksInner) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *FreeToolPreviewPostResponseNetworksInner) HasKey() bool`

HasKey returns a boolean if a field has been set.

### GetCount

`func (o *FreeToolPreviewPostResponseNetworksInner) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *FreeToolPreviewPostResponseNetworksInner) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *FreeToolPreviewPostResponseNetworksInner) SetCount(v int32)`

SetCount sets Count field to given value.

### HasCount

`func (o *FreeToolPreviewPostResponseNetworksInner) HasCount() bool`

HasCount returns a boolean if a field has been set.

### GetLimit

`func (o *FreeToolPreviewPostResponseNetworksInner) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *FreeToolPreviewPostResponseNetworksInner) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *FreeToolPreviewPostResponseNetworksInner) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *FreeToolPreviewPostResponseNetworksInner) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetOver

`func (o *FreeToolPreviewPostResponseNetworksInner) GetOver() bool`

GetOver returns the Over field if non-nil, zero value otherwise.

### GetOverOk

`func (o *FreeToolPreviewPostResponseNetworksInner) GetOverOk() (*bool, bool)`

GetOverOk returns a tuple with the Over field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOver

`func (o *FreeToolPreviewPostResponseNetworksInner) SetOver(v bool)`

SetOver sets Over field to given value.

### HasOver

`func (o *FreeToolPreviewPostResponseNetworksInner) HasOver() bool`

HasOver returns a boolean if a field has been set.

### GetPreview

`func (o *FreeToolPreviewPostResponseNetworksInner) GetPreview() string`

GetPreview returns the Preview field if non-nil, zero value otherwise.

### GetPreviewOk

`func (o *FreeToolPreviewPostResponseNetworksInner) GetPreviewOk() (*string, bool)`

GetPreviewOk returns a tuple with the Preview field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreview

`func (o *FreeToolPreviewPostResponseNetworksInner) SetPreview(v string)`

SetPreview sets Preview field to given value.

### HasPreview

`func (o *FreeToolPreviewPostResponseNetworksInner) HasPreview() bool`

HasPreview returns a boolean if a field has been set.

### GetFolded

`func (o *FreeToolPreviewPostResponseNetworksInner) GetFolded() bool`

GetFolded returns the Folded field if non-nil, zero value otherwise.

### GetFoldedOk

`func (o *FreeToolPreviewPostResponseNetworksInner) GetFoldedOk() (*bool, bool)`

GetFoldedOk returns a tuple with the Folded field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFolded

`func (o *FreeToolPreviewPostResponseNetworksInner) SetFolded(v bool)`

SetFolded sets Folded field to given value.

### HasFolded

`func (o *FreeToolPreviewPostResponseNetworksInner) HasFolded() bool`

HasFolded returns a boolean if a field has been set.

### GetMinRatio

`func (o *FreeToolPreviewPostResponseNetworksInner) GetMinRatio() string`

GetMinRatio returns the MinRatio field if non-nil, zero value otherwise.

### GetMinRatioOk

`func (o *FreeToolPreviewPostResponseNetworksInner) GetMinRatioOk() (*string, bool)`

GetMinRatioOk returns a tuple with the MinRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinRatio

`func (o *FreeToolPreviewPostResponseNetworksInner) SetMinRatio(v string)`

SetMinRatio sets MinRatio field to given value.

### HasMinRatio

`func (o *FreeToolPreviewPostResponseNetworksInner) HasMinRatio() bool`

HasMinRatio returns a boolean if a field has been set.

### GetMaxRatio

`func (o *FreeToolPreviewPostResponseNetworksInner) GetMaxRatio() string`

GetMaxRatio returns the MaxRatio field if non-nil, zero value otherwise.

### GetMaxRatioOk

`func (o *FreeToolPreviewPostResponseNetworksInner) GetMaxRatioOk() (*string, bool)`

GetMaxRatioOk returns a tuple with the MaxRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRatio

`func (o *FreeToolPreviewPostResponseNetworksInner) SetMaxRatio(v string)`

SetMaxRatio sets MaxRatio field to given value.

### HasMaxRatio

`func (o *FreeToolPreviewPostResponseNetworksInner) HasMaxRatio() bool`

HasMaxRatio returns a boolean if a field has been set.

### GetDisplayRatio

`func (o *FreeToolPreviewPostResponseNetworksInner) GetDisplayRatio() float32`

GetDisplayRatio returns the DisplayRatio field if non-nil, zero value otherwise.

### GetDisplayRatioOk

`func (o *FreeToolPreviewPostResponseNetworksInner) GetDisplayRatioOk() (*float32, bool)`

GetDisplayRatioOk returns a tuple with the DisplayRatio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayRatio

`func (o *FreeToolPreviewPostResponseNetworksInner) SetDisplayRatio(v float32)`

SetDisplayRatio sets DisplayRatio field to given value.

### HasDisplayRatio

`func (o *FreeToolPreviewPostResponseNetworksInner) HasDisplayRatio() bool`

HasDisplayRatio returns a boolean if a field has been set.

### GetCropped

`func (o *FreeToolPreviewPostResponseNetworksInner) GetCropped() bool`

GetCropped returns the Cropped field if non-nil, zero value otherwise.

### GetCroppedOk

`func (o *FreeToolPreviewPostResponseNetworksInner) GetCroppedOk() (*bool, bool)`

GetCroppedOk returns a tuple with the Cropped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCropped

`func (o *FreeToolPreviewPostResponseNetworksInner) SetCropped(v bool)`

SetCropped sets Cropped field to given value.

### HasCropped

`func (o *FreeToolPreviewPostResponseNetworksInner) HasCropped() bool`

HasCropped returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


