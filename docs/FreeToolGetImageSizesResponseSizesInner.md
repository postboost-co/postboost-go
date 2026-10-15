# FreeToolGetImageSizesResponseSizesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Network** | Pointer to **string** | Network name. | [optional] 
**NetworkKey** | Pointer to **string** | Key for &#x60;network&#x60; here and in calculateCrop. | [optional] 
**Placement** | Pointer to **string** | Where the image appears. | [optional] 
**FormatKey** | Pointer to **string** | Key for &#x60;format&#x60; in calculateCrop. | [optional] 
**Size** | Pointer to **string** | The size as the network states it, ranges included. | [optional] 
**Width** | Pointer to **NullableInt32** | Recommended width in pixels, when the size is one fixed size. | [optional] 
**Height** | Pointer to **NullableInt32** | Recommended height in pixels, when the size is one fixed size. | [optional] 
**Ratio** | Pointer to **string** | Aspect ratio. | [optional] 
**Limits** | Pointer to **string** | File type and size limits. | [optional] 
**Basis** | Pointer to **string** | &#x60;official&#x60; when the network itself states it, else how it was found. | [optional] 
**Source** | Pointer to **string** | URL of the source. | [optional] 

## Methods

### NewFreeToolGetImageSizesResponseSizesInner

`func NewFreeToolGetImageSizesResponseSizesInner() *FreeToolGetImageSizesResponseSizesInner`

NewFreeToolGetImageSizesResponseSizesInner instantiates a new FreeToolGetImageSizesResponseSizesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGetImageSizesResponseSizesInnerWithDefaults

`func NewFreeToolGetImageSizesResponseSizesInnerWithDefaults() *FreeToolGetImageSizesResponseSizesInner`

NewFreeToolGetImageSizesResponseSizesInnerWithDefaults instantiates a new FreeToolGetImageSizesResponseSizesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNetwork

`func (o *FreeToolGetImageSizesResponseSizesInner) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *FreeToolGetImageSizesResponseSizesInner) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *FreeToolGetImageSizesResponseSizesInner) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *FreeToolGetImageSizesResponseSizesInner) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetNetworkKey

`func (o *FreeToolGetImageSizesResponseSizesInner) GetNetworkKey() string`

GetNetworkKey returns the NetworkKey field if non-nil, zero value otherwise.

### GetNetworkKeyOk

`func (o *FreeToolGetImageSizesResponseSizesInner) GetNetworkKeyOk() (*string, bool)`

GetNetworkKeyOk returns a tuple with the NetworkKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkKey

`func (o *FreeToolGetImageSizesResponseSizesInner) SetNetworkKey(v string)`

SetNetworkKey sets NetworkKey field to given value.

### HasNetworkKey

`func (o *FreeToolGetImageSizesResponseSizesInner) HasNetworkKey() bool`

HasNetworkKey returns a boolean if a field has been set.

### GetPlacement

`func (o *FreeToolGetImageSizesResponseSizesInner) GetPlacement() string`

GetPlacement returns the Placement field if non-nil, zero value otherwise.

### GetPlacementOk

`func (o *FreeToolGetImageSizesResponseSizesInner) GetPlacementOk() (*string, bool)`

GetPlacementOk returns a tuple with the Placement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlacement

`func (o *FreeToolGetImageSizesResponseSizesInner) SetPlacement(v string)`

SetPlacement sets Placement field to given value.

### HasPlacement

`func (o *FreeToolGetImageSizesResponseSizesInner) HasPlacement() bool`

HasPlacement returns a boolean if a field has been set.

### GetFormatKey

`func (o *FreeToolGetImageSizesResponseSizesInner) GetFormatKey() string`

GetFormatKey returns the FormatKey field if non-nil, zero value otherwise.

### GetFormatKeyOk

`func (o *FreeToolGetImageSizesResponseSizesInner) GetFormatKeyOk() (*string, bool)`

GetFormatKeyOk returns a tuple with the FormatKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormatKey

`func (o *FreeToolGetImageSizesResponseSizesInner) SetFormatKey(v string)`

SetFormatKey sets FormatKey field to given value.

### HasFormatKey

`func (o *FreeToolGetImageSizesResponseSizesInner) HasFormatKey() bool`

HasFormatKey returns a boolean if a field has been set.

### GetSize

`func (o *FreeToolGetImageSizesResponseSizesInner) GetSize() string`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *FreeToolGetImageSizesResponseSizesInner) GetSizeOk() (*string, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *FreeToolGetImageSizesResponseSizesInner) SetSize(v string)`

SetSize sets Size field to given value.

### HasSize

`func (o *FreeToolGetImageSizesResponseSizesInner) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetWidth

`func (o *FreeToolGetImageSizesResponseSizesInner) GetWidth() int32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *FreeToolGetImageSizesResponseSizesInner) GetWidthOk() (*int32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *FreeToolGetImageSizesResponseSizesInner) SetWidth(v int32)`

SetWidth sets Width field to given value.

### HasWidth

`func (o *FreeToolGetImageSizesResponseSizesInner) HasWidth() bool`

HasWidth returns a boolean if a field has been set.

### SetWidthNil

`func (o *FreeToolGetImageSizesResponseSizesInner) SetWidthNil(b bool)`

 SetWidthNil sets the value for Width to be an explicit nil

### UnsetWidth
`func (o *FreeToolGetImageSizesResponseSizesInner) UnsetWidth()`

UnsetWidth ensures that no value is present for Width, not even an explicit nil
### GetHeight

`func (o *FreeToolGetImageSizesResponseSizesInner) GetHeight() int32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *FreeToolGetImageSizesResponseSizesInner) GetHeightOk() (*int32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *FreeToolGetImageSizesResponseSizesInner) SetHeight(v int32)`

SetHeight sets Height field to given value.

### HasHeight

`func (o *FreeToolGetImageSizesResponseSizesInner) HasHeight() bool`

HasHeight returns a boolean if a field has been set.

### SetHeightNil

`func (o *FreeToolGetImageSizesResponseSizesInner) SetHeightNil(b bool)`

 SetHeightNil sets the value for Height to be an explicit nil

### UnsetHeight
`func (o *FreeToolGetImageSizesResponseSizesInner) UnsetHeight()`

UnsetHeight ensures that no value is present for Height, not even an explicit nil
### GetRatio

`func (o *FreeToolGetImageSizesResponseSizesInner) GetRatio() string`

GetRatio returns the Ratio field if non-nil, zero value otherwise.

### GetRatioOk

`func (o *FreeToolGetImageSizesResponseSizesInner) GetRatioOk() (*string, bool)`

GetRatioOk returns a tuple with the Ratio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRatio

`func (o *FreeToolGetImageSizesResponseSizesInner) SetRatio(v string)`

SetRatio sets Ratio field to given value.

### HasRatio

`func (o *FreeToolGetImageSizesResponseSizesInner) HasRatio() bool`

HasRatio returns a boolean if a field has been set.

### GetLimits

`func (o *FreeToolGetImageSizesResponseSizesInner) GetLimits() string`

GetLimits returns the Limits field if non-nil, zero value otherwise.

### GetLimitsOk

`func (o *FreeToolGetImageSizesResponseSizesInner) GetLimitsOk() (*string, bool)`

GetLimitsOk returns a tuple with the Limits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimits

`func (o *FreeToolGetImageSizesResponseSizesInner) SetLimits(v string)`

SetLimits sets Limits field to given value.

### HasLimits

`func (o *FreeToolGetImageSizesResponseSizesInner) HasLimits() bool`

HasLimits returns a boolean if a field has been set.

### GetBasis

`func (o *FreeToolGetImageSizesResponseSizesInner) GetBasis() string`

GetBasis returns the Basis field if non-nil, zero value otherwise.

### GetBasisOk

`func (o *FreeToolGetImageSizesResponseSizesInner) GetBasisOk() (*string, bool)`

GetBasisOk returns a tuple with the Basis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBasis

`func (o *FreeToolGetImageSizesResponseSizesInner) SetBasis(v string)`

SetBasis sets Basis field to given value.

### HasBasis

`func (o *FreeToolGetImageSizesResponseSizesInner) HasBasis() bool`

HasBasis returns a boolean if a field has been set.

### GetSource

`func (o *FreeToolGetImageSizesResponseSizesInner) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *FreeToolGetImageSizesResponseSizesInner) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *FreeToolGetImageSizesResponseSizesInner) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *FreeToolGetImageSizesResponseSizesInner) HasSource() bool`

HasSource returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


