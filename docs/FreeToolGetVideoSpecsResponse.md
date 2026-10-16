# FreeToolGetVideoSpecsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Specs** | Pointer to [**[]FreeToolGetVideoSpecsResponseSpecsInner**](FreeToolGetVideoSpecsResponseSpecsInner.md) |  | [optional] 
**LastVerified** | Pointer to **NullableString** | When the data was last checked against its sources. | [optional] 
**Sources** | Pointer to [**[]FreeToolGetImageSizesResponseSourcesInner**](FreeToolGetImageSizesResponseSourcesInner.md) | Sources of the whole dataset (rows may name their own). | [optional] 

## Methods

### NewFreeToolGetVideoSpecsResponse

`func NewFreeToolGetVideoSpecsResponse() *FreeToolGetVideoSpecsResponse`

NewFreeToolGetVideoSpecsResponse instantiates a new FreeToolGetVideoSpecsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGetVideoSpecsResponseWithDefaults

`func NewFreeToolGetVideoSpecsResponseWithDefaults() *FreeToolGetVideoSpecsResponse`

NewFreeToolGetVideoSpecsResponseWithDefaults instantiates a new FreeToolGetVideoSpecsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSpecs

`func (o *FreeToolGetVideoSpecsResponse) GetSpecs() []FreeToolGetVideoSpecsResponseSpecsInner`

GetSpecs returns the Specs field if non-nil, zero value otherwise.

### GetSpecsOk

`func (o *FreeToolGetVideoSpecsResponse) GetSpecsOk() (*[]FreeToolGetVideoSpecsResponseSpecsInner, bool)`

GetSpecsOk returns a tuple with the Specs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpecs

`func (o *FreeToolGetVideoSpecsResponse) SetSpecs(v []FreeToolGetVideoSpecsResponseSpecsInner)`

SetSpecs sets Specs field to given value.

### HasSpecs

`func (o *FreeToolGetVideoSpecsResponse) HasSpecs() bool`

HasSpecs returns a boolean if a field has been set.

### GetLastVerified

`func (o *FreeToolGetVideoSpecsResponse) GetLastVerified() string`

GetLastVerified returns the LastVerified field if non-nil, zero value otherwise.

### GetLastVerifiedOk

`func (o *FreeToolGetVideoSpecsResponse) GetLastVerifiedOk() (*string, bool)`

GetLastVerifiedOk returns a tuple with the LastVerified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastVerified

`func (o *FreeToolGetVideoSpecsResponse) SetLastVerified(v string)`

SetLastVerified sets LastVerified field to given value.

### HasLastVerified

`func (o *FreeToolGetVideoSpecsResponse) HasLastVerified() bool`

HasLastVerified returns a boolean if a field has been set.

### SetLastVerifiedNil

`func (o *FreeToolGetVideoSpecsResponse) SetLastVerifiedNil(b bool)`

 SetLastVerifiedNil sets the value for LastVerified to be an explicit nil

### UnsetLastVerified
`func (o *FreeToolGetVideoSpecsResponse) UnsetLastVerified()`

UnsetLastVerified ensures that no value is present for LastVerified, not even an explicit nil
### GetSources

`func (o *FreeToolGetVideoSpecsResponse) GetSources() []FreeToolGetImageSizesResponseSourcesInner`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *FreeToolGetVideoSpecsResponse) GetSourcesOk() (*[]FreeToolGetImageSizesResponseSourcesInner, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *FreeToolGetVideoSpecsResponse) SetSources(v []FreeToolGetImageSizesResponseSourcesInner)`

SetSources sets Sources field to given value.

### HasSources

`func (o *FreeToolGetVideoSpecsResponse) HasSources() bool`

HasSources returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


