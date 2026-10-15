# FreeToolGetImageSizesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Sizes** | Pointer to [**[]FreeToolGetImageSizesResponseSizesInner**](FreeToolGetImageSizesResponseSizesInner.md) |  | [optional] 
**LastVerified** | Pointer to **NullableString** | When the data was last checked against its sources. | [optional] 
**Sources** | Pointer to [**[]FreeToolGetImageSizesResponseSourcesInner**](FreeToolGetImageSizesResponseSourcesInner.md) | Sources of the whole dataset (rows may name their own). | [optional] 

## Methods

### NewFreeToolGetImageSizesResponse

`func NewFreeToolGetImageSizesResponse() *FreeToolGetImageSizesResponse`

NewFreeToolGetImageSizesResponse instantiates a new FreeToolGetImageSizesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGetImageSizesResponseWithDefaults

`func NewFreeToolGetImageSizesResponseWithDefaults() *FreeToolGetImageSizesResponse`

NewFreeToolGetImageSizesResponseWithDefaults instantiates a new FreeToolGetImageSizesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSizes

`func (o *FreeToolGetImageSizesResponse) GetSizes() []FreeToolGetImageSizesResponseSizesInner`

GetSizes returns the Sizes field if non-nil, zero value otherwise.

### GetSizesOk

`func (o *FreeToolGetImageSizesResponse) GetSizesOk() (*[]FreeToolGetImageSizesResponseSizesInner, bool)`

GetSizesOk returns a tuple with the Sizes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSizes

`func (o *FreeToolGetImageSizesResponse) SetSizes(v []FreeToolGetImageSizesResponseSizesInner)`

SetSizes sets Sizes field to given value.

### HasSizes

`func (o *FreeToolGetImageSizesResponse) HasSizes() bool`

HasSizes returns a boolean if a field has been set.

### GetLastVerified

`func (o *FreeToolGetImageSizesResponse) GetLastVerified() string`

GetLastVerified returns the LastVerified field if non-nil, zero value otherwise.

### GetLastVerifiedOk

`func (o *FreeToolGetImageSizesResponse) GetLastVerifiedOk() (*string, bool)`

GetLastVerifiedOk returns a tuple with the LastVerified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastVerified

`func (o *FreeToolGetImageSizesResponse) SetLastVerified(v string)`

SetLastVerified sets LastVerified field to given value.

### HasLastVerified

`func (o *FreeToolGetImageSizesResponse) HasLastVerified() bool`

HasLastVerified returns a boolean if a field has been set.

### SetLastVerifiedNil

`func (o *FreeToolGetImageSizesResponse) SetLastVerifiedNil(b bool)`

 SetLastVerifiedNil sets the value for LastVerified to be an explicit nil

### UnsetLastVerified
`func (o *FreeToolGetImageSizesResponse) UnsetLastVerified()`

UnsetLastVerified ensures that no value is present for LastVerified, not even an explicit nil
### GetSources

`func (o *FreeToolGetImageSizesResponse) GetSources() []FreeToolGetImageSizesResponseSourcesInner`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *FreeToolGetImageSizesResponse) GetSourcesOk() (*[]FreeToolGetImageSizesResponseSourcesInner, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *FreeToolGetImageSizesResponse) SetSources(v []FreeToolGetImageSizesResponseSourcesInner)`

SetSources sets Sources field to given value.

### HasSources

`func (o *FreeToolGetImageSizesResponse) HasSources() bool`

HasSources returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


