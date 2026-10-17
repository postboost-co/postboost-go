# FreeToolListAwarenessDaysResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Covers** | Pointer to [**FreeToolListAwarenessDaysResponseCovers**](FreeToolListAwarenessDaysResponseCovers.md) |  | [optional] 
**Total** | Pointer to **int32** | Number of entries returned. | [optional] 
**Entries** | Pointer to [**[]FreeToolListAwarenessDaysResponseEntriesInner**](FreeToolListAwarenessDaysResponseEntriesInner.md) |  | [optional] 
**LastVerified** | Pointer to **NullableString** | When the data was last checked against its sources. | [optional] 
**Sources** | Pointer to [**[]FreeToolGetImageSizesResponseSourcesInner**](FreeToolGetImageSizesResponseSourcesInner.md) | Sources of the whole dataset (rows may name their own). | [optional] 

## Methods

### NewFreeToolListAwarenessDaysResponse

`func NewFreeToolListAwarenessDaysResponse() *FreeToolListAwarenessDaysResponse`

NewFreeToolListAwarenessDaysResponse instantiates a new FreeToolListAwarenessDaysResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolListAwarenessDaysResponseWithDefaults

`func NewFreeToolListAwarenessDaysResponseWithDefaults() *FreeToolListAwarenessDaysResponse`

NewFreeToolListAwarenessDaysResponseWithDefaults instantiates a new FreeToolListAwarenessDaysResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCovers

`func (o *FreeToolListAwarenessDaysResponse) GetCovers() FreeToolListAwarenessDaysResponseCovers`

GetCovers returns the Covers field if non-nil, zero value otherwise.

### GetCoversOk

`func (o *FreeToolListAwarenessDaysResponse) GetCoversOk() (*FreeToolListAwarenessDaysResponseCovers, bool)`

GetCoversOk returns a tuple with the Covers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCovers

`func (o *FreeToolListAwarenessDaysResponse) SetCovers(v FreeToolListAwarenessDaysResponseCovers)`

SetCovers sets Covers field to given value.

### HasCovers

`func (o *FreeToolListAwarenessDaysResponse) HasCovers() bool`

HasCovers returns a boolean if a field has been set.

### GetTotal

`func (o *FreeToolListAwarenessDaysResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *FreeToolListAwarenessDaysResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *FreeToolListAwarenessDaysResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *FreeToolListAwarenessDaysResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetEntries

`func (o *FreeToolListAwarenessDaysResponse) GetEntries() []FreeToolListAwarenessDaysResponseEntriesInner`

GetEntries returns the Entries field if non-nil, zero value otherwise.

### GetEntriesOk

`func (o *FreeToolListAwarenessDaysResponse) GetEntriesOk() (*[]FreeToolListAwarenessDaysResponseEntriesInner, bool)`

GetEntriesOk returns a tuple with the Entries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntries

`func (o *FreeToolListAwarenessDaysResponse) SetEntries(v []FreeToolListAwarenessDaysResponseEntriesInner)`

SetEntries sets Entries field to given value.

### HasEntries

`func (o *FreeToolListAwarenessDaysResponse) HasEntries() bool`

HasEntries returns a boolean if a field has been set.

### GetLastVerified

`func (o *FreeToolListAwarenessDaysResponse) GetLastVerified() string`

GetLastVerified returns the LastVerified field if non-nil, zero value otherwise.

### GetLastVerifiedOk

`func (o *FreeToolListAwarenessDaysResponse) GetLastVerifiedOk() (*string, bool)`

GetLastVerifiedOk returns a tuple with the LastVerified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastVerified

`func (o *FreeToolListAwarenessDaysResponse) SetLastVerified(v string)`

SetLastVerified sets LastVerified field to given value.

### HasLastVerified

`func (o *FreeToolListAwarenessDaysResponse) HasLastVerified() bool`

HasLastVerified returns a boolean if a field has been set.

### SetLastVerifiedNil

`func (o *FreeToolListAwarenessDaysResponse) SetLastVerifiedNil(b bool)`

 SetLastVerifiedNil sets the value for LastVerified to be an explicit nil

### UnsetLastVerified
`func (o *FreeToolListAwarenessDaysResponse) UnsetLastVerified()`

UnsetLastVerified ensures that no value is present for LastVerified, not even an explicit nil
### GetSources

`func (o *FreeToolListAwarenessDaysResponse) GetSources() []FreeToolGetImageSizesResponseSourcesInner`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *FreeToolListAwarenessDaysResponse) GetSourcesOk() (*[]FreeToolGetImageSizesResponseSourcesInner, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *FreeToolListAwarenessDaysResponse) SetSources(v []FreeToolGetImageSizesResponseSourcesInner)`

SetSources sets Sources field to given value.

### HasSources

`func (o *FreeToolListAwarenessDaysResponse) HasSources() bool`

HasSources returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


