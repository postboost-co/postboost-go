# FreeToolGetBestTimesToPostResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Networks** | Pointer to [**[]FreeToolGetBestTimesToPostResponseNetworksInner**](FreeToolGetBestTimesToPostResponseNetworksInner.md) |  | [optional] 
**LastVerified** | Pointer to **NullableString** | When the data was last checked against its sources. | [optional] 
**Sources** | Pointer to [**[]FreeToolGetImageSizesResponseSourcesInner**](FreeToolGetImageSizesResponseSourcesInner.md) | Sources of the whole dataset (rows may name their own). | [optional] 
**PerAccount** | Pointer to **string** | Where to get times from your own accounts. | [optional] 

## Methods

### NewFreeToolGetBestTimesToPostResponse

`func NewFreeToolGetBestTimesToPostResponse() *FreeToolGetBestTimesToPostResponse`

NewFreeToolGetBestTimesToPostResponse instantiates a new FreeToolGetBestTimesToPostResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGetBestTimesToPostResponseWithDefaults

`func NewFreeToolGetBestTimesToPostResponseWithDefaults() *FreeToolGetBestTimesToPostResponse`

NewFreeToolGetBestTimesToPostResponseWithDefaults instantiates a new FreeToolGetBestTimesToPostResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNetworks

`func (o *FreeToolGetBestTimesToPostResponse) GetNetworks() []FreeToolGetBestTimesToPostResponseNetworksInner`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *FreeToolGetBestTimesToPostResponse) GetNetworksOk() (*[]FreeToolGetBestTimesToPostResponseNetworksInner, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *FreeToolGetBestTimesToPostResponse) SetNetworks(v []FreeToolGetBestTimesToPostResponseNetworksInner)`

SetNetworks sets Networks field to given value.

### HasNetworks

`func (o *FreeToolGetBestTimesToPostResponse) HasNetworks() bool`

HasNetworks returns a boolean if a field has been set.

### GetLastVerified

`func (o *FreeToolGetBestTimesToPostResponse) GetLastVerified() string`

GetLastVerified returns the LastVerified field if non-nil, zero value otherwise.

### GetLastVerifiedOk

`func (o *FreeToolGetBestTimesToPostResponse) GetLastVerifiedOk() (*string, bool)`

GetLastVerifiedOk returns a tuple with the LastVerified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastVerified

`func (o *FreeToolGetBestTimesToPostResponse) SetLastVerified(v string)`

SetLastVerified sets LastVerified field to given value.

### HasLastVerified

`func (o *FreeToolGetBestTimesToPostResponse) HasLastVerified() bool`

HasLastVerified returns a boolean if a field has been set.

### SetLastVerifiedNil

`func (o *FreeToolGetBestTimesToPostResponse) SetLastVerifiedNil(b bool)`

 SetLastVerifiedNil sets the value for LastVerified to be an explicit nil

### UnsetLastVerified
`func (o *FreeToolGetBestTimesToPostResponse) UnsetLastVerified()`

UnsetLastVerified ensures that no value is present for LastVerified, not even an explicit nil
### GetSources

`func (o *FreeToolGetBestTimesToPostResponse) GetSources() []FreeToolGetImageSizesResponseSourcesInner`

GetSources returns the Sources field if non-nil, zero value otherwise.

### GetSourcesOk

`func (o *FreeToolGetBestTimesToPostResponse) GetSourcesOk() (*[]FreeToolGetImageSizesResponseSourcesInner, bool)`

GetSourcesOk returns a tuple with the Sources field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSources

`func (o *FreeToolGetBestTimesToPostResponse) SetSources(v []FreeToolGetImageSizesResponseSourcesInner)`

SetSources sets Sources field to given value.

### HasSources

`func (o *FreeToolGetBestTimesToPostResponse) HasSources() bool`

HasSources returns a boolean if a field has been set.

### GetPerAccount

`func (o *FreeToolGetBestTimesToPostResponse) GetPerAccount() string`

GetPerAccount returns the PerAccount field if non-nil, zero value otherwise.

### GetPerAccountOk

`func (o *FreeToolGetBestTimesToPostResponse) GetPerAccountOk() (*string, bool)`

GetPerAccountOk returns a tuple with the PerAccount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPerAccount

`func (o *FreeToolGetBestTimesToPostResponse) SetPerAccount(v string)`

SetPerAccount sets PerAccount field to given value.

### HasPerAccount

`func (o *FreeToolGetBestTimesToPostResponse) HasPerAccount() bool`

HasPerAccount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


