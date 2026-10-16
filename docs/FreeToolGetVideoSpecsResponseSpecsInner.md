# FreeToolGetVideoSpecsResponseSpecsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Network** | Pointer to **string** | Network name. | [optional] 
**NetworkKey** | Pointer to **string** | Key for &#x60;network&#x60;. | [optional] 
**Placement** | Pointer to **string** | Placement; &#x60;(app)&#x60; and &#x60;(publishing API)&#x60; rows differ where the network says so. | [optional] 
**PlacementKey** | Pointer to **string** | Key for &#x60;placement&#x60;. | [optional] 
**Ratio** | Pointer to **string** | Aspect ratios as the source states them. | [optional] 
**Resolution** | Pointer to **string** | Resolution, frame rate and codec notes. | [optional] 
**Length** | Pointer to **string** | Length limits. | [optional] 
**MaxSize** | Pointer to **string** | File size limit. | [optional] 
**Formats** | Pointer to **string** | Container and codec formats. | [optional] 
**SafeZone** | Pointer to **string** | Text safe zone, only where the network publishes one. | [optional] 
**Basis** | Pointer to **string** | &#x60;official&#x60; when the network itself states it, else how it was found. | [optional] 
**Sources** | Pointer to **[]string** | URLs of the sources. | [optional] 
**Limits** | Pointer to [**FreeToolGetVideoSpecsResponseSpecsInnerLimits**](FreeToolGetVideoSpecsResponseSpecsInnerLimits.md) |  | [optional] 

## Methods

### NewFreeToolGetVideoSpecsResponseSpecsInner

`func NewFreeToolGetVideoSpecsResponseSpecsInner() *FreeToolGetVideoSpecsResponseSpecsInner`

NewFreeToolGetVideoSpecsResponseSpecsInner instantiates a new FreeToolGetVideoSpecsResponseSpecsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGetVideoSpecsResponseSpecsInnerWithDefaults

`func NewFreeToolGetVideoSpecsResponseSpecsInnerWithDefaults() *FreeToolGetVideoSpecsResponseSpecsInner`

NewFreeToolGetVideoSpecsResponseSpecsInnerWithDefaults instantiates a new FreeToolGetVideoSpecsResponseSpecsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNetwork

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetNetworkKey

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetNetworkKey() string`

GetNetworkKey returns the NetworkKey field if non-nil, zero value otherwise.

### GetNetworkKeyOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetNetworkKeyOk() (*string, bool)`

GetNetworkKeyOk returns a tuple with the NetworkKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworkKey

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) SetNetworkKey(v string)`

SetNetworkKey sets NetworkKey field to given value.

### HasNetworkKey

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) HasNetworkKey() bool`

HasNetworkKey returns a boolean if a field has been set.

### GetPlacement

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetPlacement() string`

GetPlacement returns the Placement field if non-nil, zero value otherwise.

### GetPlacementOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetPlacementOk() (*string, bool)`

GetPlacementOk returns a tuple with the Placement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlacement

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) SetPlacement(v string)`

SetPlacement sets Placement field to given value.

### HasPlacement

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) HasPlacement() bool`

HasPlacement returns a boolean if a field has been set.

### GetPlacementKey

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetPlacementKey() string`

GetPlacementKey returns the PlacementKey field if non-nil, zero value otherwise.

### GetPlacementKeyOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetPlacementKeyOk() (*string, bool)`

GetPlacementKeyOk returns a tuple with the PlacementKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlacementKey

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) SetPlacementKey(v string)`

SetPlacementKey sets PlacementKey field to given value.

### HasPlacementKey

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) HasPlacementKey() bool`

HasPlacementKey returns a boolean if a field has been set.

### GetRatio

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetRatio() string`

GetRatio returns the Ratio field if non-nil, zero value otherwise.

### GetRatioOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetRatioOk() (*string, bool)`

GetRatioOk returns a tuple with the Ratio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRatio

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) SetRatio(v string)`

SetRatio sets Ratio field to given value.

### HasRatio

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) HasRatio() bool`

HasRatio returns a boolean if a field has been set.

### GetResolution

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetResolution() string`

GetResolution returns the Resolution field if non-nil, zero value otherwise.

### GetResolutionOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetResolutionOk() (*string, bool)`

GetResolutionOk returns a tuple with the Resolution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResolution

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) SetResolution(v string)`

SetResolution sets Resolution field to given value.

### HasResolution

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) HasResolution() bool`

HasResolution returns a boolean if a field has been set.

### GetLength

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetLength() string`

GetLength returns the Length field if non-nil, zero value otherwise.

### GetLengthOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetLengthOk() (*string, bool)`

GetLengthOk returns a tuple with the Length field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLength

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) SetLength(v string)`

SetLength sets Length field to given value.

### HasLength

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) HasLength() bool`

HasLength returns a boolean if a field has been set.

### GetMaxSize

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetMaxSize() string`

GetMaxSize returns the MaxSize field if non-nil, zero value otherwise.

### GetMaxSizeOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetMaxSizeOk() (*string, bool)`

GetMaxSizeOk returns a tuple with the MaxSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxSize

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) SetMaxSize(v string)`

SetMaxSize sets MaxSize field to given value.

### HasMaxSize

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) HasMaxSize() bool`

HasMaxSize returns a boolean if a field has been set.

### GetFormats

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetFormats() string`

GetFormats returns the Formats field if non-nil, zero value otherwise.

### GetFormatsOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetFormatsOk() (*string, bool)`

GetFormatsOk returns a tuple with the Formats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormats

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) SetFormats(v string)`

SetFormats sets Formats field to given value.

### HasFormats

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) HasFormats() bool`

HasFormats returns a boolean if a field has been set.

### GetSafeZone

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetSafeZone() string`

GetSafeZone returns the SafeZone field if non-nil, zero value otherwise.

### GetSafeZoneOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetSafeZoneOk() (*string, bool)`

GetSafeZoneOk returns a tuple with the SafeZone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSafeZone

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) SetSafeZone(v string)`

SetSafeZone sets SafeZone field to given value.

### HasSafeZone

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) HasSafeZone() bool`

HasSafeZone returns a boolean if a field has been set.

### GetBasis

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetBasis() string`

GetBasis returns the Basis field if non-nil, zero value otherwise.

### GetBasisOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetBasisOk() (*string, bool)`

GetBasisOk returns a tuple with the Basis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBasis

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) SetBasis(v string)`

SetBasis sets Basis field to given value.

### HasBasis

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) HasBasis() bool`

HasBasis returns a boolean if a field has been set.

### GetSources

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetSources() []string`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetSourcesOk() (*[]string, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) SetSources(v []string)`

SetSources sets Sources field to given value.

### HasSources

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) HasSources() bool`

HasSources returns a boolean if a field has been set.

### GetLimits

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetLimits() FreeToolGetVideoSpecsResponseSpecsInnerLimits`

GetLimits returns the Limits field if non-nil, zero value otherwise.

### GetLimitsOk

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) GetLimitsOk() (*FreeToolGetVideoSpecsResponseSpecsInnerLimits, bool)`

GetLimitsOk returns a tuple with the Limits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimits

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) SetLimits(v FreeToolGetVideoSpecsResponseSpecsInnerLimits)`

SetLimits sets Limits field to given value.

### HasLimits

`func (o *FreeToolGetVideoSpecsResponseSpecsInner) HasLimits() bool`

HasLimits returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


