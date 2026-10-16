# FreeToolCalculateAspectRatioResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ratio** | Pointer to **string** | Simplified ratio, e.g. &#x60;4:5&#x60;. Decimal ratios stay as given. | [optional] 
**Decimal** | Pointer to **float32** | Width divided by height, 4 decimals. | [optional] 
**Width** | Pointer to **int32** |  | [optional] 
**Height** | Pointer to **int32** |  | [optional] 
**Rounding** | Pointer to [**FreeToolCalculateAspectRatioResponseRounding**](FreeToolCalculateAspectRatioResponseRounding.md) |  | [optional] 
**Orientation** | Pointer to **string** |  | [optional] 
**Matches** | Pointer to [**[]FreeToolCalculateAspectRatioResponseMatchesInner**](FreeToolCalculateAspectRatioResponseMatchesInner.md) | Social media image presets with the same ratio, else the nearest. | [optional] 

## Methods

### NewFreeToolCalculateAspectRatioResponse

`func NewFreeToolCalculateAspectRatioResponse() *FreeToolCalculateAspectRatioResponse`

NewFreeToolCalculateAspectRatioResponse instantiates a new FreeToolCalculateAspectRatioResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCalculateAspectRatioResponseWithDefaults

`func NewFreeToolCalculateAspectRatioResponseWithDefaults() *FreeToolCalculateAspectRatioResponse`

NewFreeToolCalculateAspectRatioResponseWithDefaults instantiates a new FreeToolCalculateAspectRatioResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRatio

`func (o *FreeToolCalculateAspectRatioResponse) GetRatio() string`

GetRatio returns the Ratio field if non-nil, zero value otherwise.

### GetRatioOk

`func (o *FreeToolCalculateAspectRatioResponse) GetRatioOk() (*string, bool)`

GetRatioOk returns a tuple with the Ratio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRatio

`func (o *FreeToolCalculateAspectRatioResponse) SetRatio(v string)`

SetRatio sets Ratio field to given value.

### HasRatio

`func (o *FreeToolCalculateAspectRatioResponse) HasRatio() bool`

HasRatio returns a boolean if a field has been set.

### GetDecimal

`func (o *FreeToolCalculateAspectRatioResponse) GetDecimal() float32`

GetDecimal returns the Decimal field if non-nil, zero value otherwise.

### GetDecimalOk

`func (o *FreeToolCalculateAspectRatioResponse) GetDecimalOk() (*float32, bool)`

GetDecimalOk returns a tuple with the Decimal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecimal

`func (o *FreeToolCalculateAspectRatioResponse) SetDecimal(v float32)`

SetDecimal sets Decimal field to given value.

### HasDecimal

`func (o *FreeToolCalculateAspectRatioResponse) HasDecimal() bool`

HasDecimal returns a boolean if a field has been set.

### GetWidth

`func (o *FreeToolCalculateAspectRatioResponse) GetWidth() int32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *FreeToolCalculateAspectRatioResponse) GetWidthOk() (*int32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *FreeToolCalculateAspectRatioResponse) SetWidth(v int32)`

SetWidth sets Width field to given value.

### HasWidth

`func (o *FreeToolCalculateAspectRatioResponse) HasWidth() bool`

HasWidth returns a boolean if a field has been set.

### GetHeight

`func (o *FreeToolCalculateAspectRatioResponse) GetHeight() int32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *FreeToolCalculateAspectRatioResponse) GetHeightOk() (*int32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *FreeToolCalculateAspectRatioResponse) SetHeight(v int32)`

SetHeight sets Height field to given value.

### HasHeight

`func (o *FreeToolCalculateAspectRatioResponse) HasHeight() bool`

HasHeight returns a boolean if a field has been set.

### GetRounding

`func (o *FreeToolCalculateAspectRatioResponse) GetRounding() FreeToolCalculateAspectRatioResponseRounding`

GetRounding returns the Rounding field if non-nil, zero value otherwise.

### GetRoundingOk

`func (o *FreeToolCalculateAspectRatioResponse) GetRoundingOk() (*FreeToolCalculateAspectRatioResponseRounding, bool)`

GetRoundingOk returns a tuple with the Rounding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRounding

`func (o *FreeToolCalculateAspectRatioResponse) SetRounding(v FreeToolCalculateAspectRatioResponseRounding)`

SetRounding sets Rounding field to given value.

### HasRounding

`func (o *FreeToolCalculateAspectRatioResponse) HasRounding() bool`

HasRounding returns a boolean if a field has been set.

### GetOrientation

`func (o *FreeToolCalculateAspectRatioResponse) GetOrientation() string`

GetOrientation returns the Orientation field if non-nil, zero value otherwise.

### GetOrientationOk

`func (o *FreeToolCalculateAspectRatioResponse) GetOrientationOk() (*string, bool)`

GetOrientationOk returns a tuple with the Orientation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrientation

`func (o *FreeToolCalculateAspectRatioResponse) SetOrientation(v string)`

SetOrientation sets Orientation field to given value.

### HasOrientation

`func (o *FreeToolCalculateAspectRatioResponse) HasOrientation() bool`

HasOrientation returns a boolean if a field has been set.

### GetMatches

`func (o *FreeToolCalculateAspectRatioResponse) GetMatches() []FreeToolCalculateAspectRatioResponseMatchesInner`

GetMatches returns the Matches field if non-nil, zero value otherwise.

### GetMatchesOk

`func (o *FreeToolCalculateAspectRatioResponse) GetMatchesOk() (*[]FreeToolCalculateAspectRatioResponseMatchesInner, bool)`

GetMatchesOk returns a tuple with the Matches field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatches

`func (o *FreeToolCalculateAspectRatioResponse) SetMatches(v []FreeToolCalculateAspectRatioResponseMatchesInner)`

SetMatches sets Matches field to given value.

### HasMatches

`func (o *FreeToolCalculateAspectRatioResponse) HasMatches() bool`

HasMatches returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


