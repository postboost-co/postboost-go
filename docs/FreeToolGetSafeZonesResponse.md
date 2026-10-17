# FreeToolGetSafeZonesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Platform** | Pointer to **string** |  | [optional] 
**Label** | Pointer to **string** | Platform name. | [optional] 
**Width** | Pointer to **int32** |  | [optional] 
**Height** | Pointer to **int32** |  | [optional] 
**UnsafeAreas** | Pointer to [**[]FreeToolGetSafeZonesResponseUnsafeAreasInner**](FreeToolGetSafeZonesResponseUnsafeAreasInner.md) | Areas the app&#39;s UI usually covers, in frame pixels from the top-left corner. Edges are scaled from 1080 × 1920 and rounded to the nearest pixel (halves up), so neighbouring boxes stay edge to edge. | [optional] 
**SafeArea** | Pointer to [**FreeToolGetSafeZonesResponseSafeArea**](FreeToolGetSafeZonesResponseSafeArea.md) |  | [optional] 
**Source** | Pointer to [**FreeToolGetSafeZonesResponseSource**](FreeToolGetSafeZonesResponseSource.md) |  | [optional] 
**LastVerified** | Pointer to **string** | Date the sources were last checked (YYYY-MM-DD). | [optional] 
**Caveat** | Pointer to **string** |  | [optional] 
**Warnings** | Pointer to **[]string** | Set when the frame is not 9:16, so the boxes are stretched. | [optional] 

## Methods

### NewFreeToolGetSafeZonesResponse

`func NewFreeToolGetSafeZonesResponse() *FreeToolGetSafeZonesResponse`

NewFreeToolGetSafeZonesResponse instantiates a new FreeToolGetSafeZonesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGetSafeZonesResponseWithDefaults

`func NewFreeToolGetSafeZonesResponseWithDefaults() *FreeToolGetSafeZonesResponse`

NewFreeToolGetSafeZonesResponseWithDefaults instantiates a new FreeToolGetSafeZonesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlatform

`func (o *FreeToolGetSafeZonesResponse) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *FreeToolGetSafeZonesResponse) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *FreeToolGetSafeZonesResponse) SetPlatform(v string)`

SetPlatform sets Platform field to given value.

### HasPlatform

`func (o *FreeToolGetSafeZonesResponse) HasPlatform() bool`

HasPlatform returns a boolean if a field has been set.

### GetLabel

`func (o *FreeToolGetSafeZonesResponse) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *FreeToolGetSafeZonesResponse) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *FreeToolGetSafeZonesResponse) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *FreeToolGetSafeZonesResponse) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetWidth

`func (o *FreeToolGetSafeZonesResponse) GetWidth() int32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *FreeToolGetSafeZonesResponse) GetWidthOk() (*int32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *FreeToolGetSafeZonesResponse) SetWidth(v int32)`

SetWidth sets Width field to given value.

### HasWidth

`func (o *FreeToolGetSafeZonesResponse) HasWidth() bool`

HasWidth returns a boolean if a field has been set.

### GetHeight

`func (o *FreeToolGetSafeZonesResponse) GetHeight() int32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *FreeToolGetSafeZonesResponse) GetHeightOk() (*int32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *FreeToolGetSafeZonesResponse) SetHeight(v int32)`

SetHeight sets Height field to given value.

### HasHeight

`func (o *FreeToolGetSafeZonesResponse) HasHeight() bool`

HasHeight returns a boolean if a field has been set.

### GetUnsafeAreas

`func (o *FreeToolGetSafeZonesResponse) GetUnsafeAreas() []FreeToolGetSafeZonesResponseUnsafeAreasInner`

GetUnsafeAreas returns the UnsafeAreas field if non-nil, zero value otherwise.

### GetUnsafeAreasOk

`func (o *FreeToolGetSafeZonesResponse) GetUnsafeAreasOk() (*[]FreeToolGetSafeZonesResponseUnsafeAreasInner, bool)`

GetUnsafeAreasOk returns a tuple with the UnsafeAreas field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnsafeAreas

`func (o *FreeToolGetSafeZonesResponse) SetUnsafeAreas(v []FreeToolGetSafeZonesResponseUnsafeAreasInner)`

SetUnsafeAreas sets UnsafeAreas field to given value.

### HasUnsafeAreas

`func (o *FreeToolGetSafeZonesResponse) HasUnsafeAreas() bool`

HasUnsafeAreas returns a boolean if a field has been set.

### GetSafeArea

`func (o *FreeToolGetSafeZonesResponse) GetSafeArea() FreeToolGetSafeZonesResponseSafeArea`

GetSafeArea returns the SafeArea field if non-nil, zero value otherwise.

### GetSafeAreaOk

`func (o *FreeToolGetSafeZonesResponse) GetSafeAreaOk() (*FreeToolGetSafeZonesResponseSafeArea, bool)`

GetSafeAreaOk returns a tuple with the SafeArea field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSafeArea

`func (o *FreeToolGetSafeZonesResponse) SetSafeArea(v FreeToolGetSafeZonesResponseSafeArea)`

SetSafeArea sets SafeArea field to given value.

### HasSafeArea

`func (o *FreeToolGetSafeZonesResponse) HasSafeArea() bool`

HasSafeArea returns a boolean if a field has been set.

### GetSource

`func (o *FreeToolGetSafeZonesResponse) GetSource() FreeToolGetSafeZonesResponseSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *FreeToolGetSafeZonesResponse) GetSourceOk() (*FreeToolGetSafeZonesResponseSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *FreeToolGetSafeZonesResponse) SetSource(v FreeToolGetSafeZonesResponseSource)`

SetSource sets Source field to given value.

### HasSource

`func (o *FreeToolGetSafeZonesResponse) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetLastVerified

`func (o *FreeToolGetSafeZonesResponse) GetLastVerified() string`

GetLastVerified returns the LastVerified field if non-nil, zero value otherwise.

### GetLastVerifiedOk

`func (o *FreeToolGetSafeZonesResponse) GetLastVerifiedOk() (*string, bool)`

GetLastVerifiedOk returns a tuple with the LastVerified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastVerified

`func (o *FreeToolGetSafeZonesResponse) SetLastVerified(v string)`

SetLastVerified sets LastVerified field to given value.

### HasLastVerified

`func (o *FreeToolGetSafeZonesResponse) HasLastVerified() bool`

HasLastVerified returns a boolean if a field has been set.

### GetCaveat

`func (o *FreeToolGetSafeZonesResponse) GetCaveat() string`

GetCaveat returns the Caveat field if non-nil, zero value otherwise.

### GetCaveatOk

`func (o *FreeToolGetSafeZonesResponse) GetCaveatOk() (*string, bool)`

GetCaveatOk returns a tuple with the Caveat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCaveat

`func (o *FreeToolGetSafeZonesResponse) SetCaveat(v string)`

SetCaveat sets Caveat field to given value.

### HasCaveat

`func (o *FreeToolGetSafeZonesResponse) HasCaveat() bool`

HasCaveat returns a boolean if a field has been set.

### GetWarnings

`func (o *FreeToolGetSafeZonesResponse) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *FreeToolGetSafeZonesResponse) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *FreeToolGetSafeZonesResponse) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *FreeToolGetSafeZonesResponse) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


