# FreeToolGenerateUsernamesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Your name, brand or a few keywords. Accents are dropped; only Latin letters and digits are used. | 
**Network** | Pointer to **string** | Whose username rules apply (Threads uses your Instagram username). | [optional] [default to "instagram"]
**Style** | Pointer to **string** | Which word list to mix in. | [optional] [default to "clean"]
**Numbers** | Pointer to **bool** | Allow a number at the end of some names. | [optional] [default to false]
**Seed** | Pointer to **int32** | The same input and seed give the same list; change it for more ideas. | [optional] [default to 0]

## Methods

### NewFreeToolGenerateUsernamesRequest

`func NewFreeToolGenerateUsernamesRequest(name string, ) *FreeToolGenerateUsernamesRequest`

NewFreeToolGenerateUsernamesRequest instantiates a new FreeToolGenerateUsernamesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateUsernamesRequestWithDefaults

`func NewFreeToolGenerateUsernamesRequestWithDefaults() *FreeToolGenerateUsernamesRequest`

NewFreeToolGenerateUsernamesRequestWithDefaults instantiates a new FreeToolGenerateUsernamesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *FreeToolGenerateUsernamesRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *FreeToolGenerateUsernamesRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *FreeToolGenerateUsernamesRequest) SetName(v string)`

SetName sets Name field to given value.


### GetNetwork

`func (o *FreeToolGenerateUsernamesRequest) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *FreeToolGenerateUsernamesRequest) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *FreeToolGenerateUsernamesRequest) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *FreeToolGenerateUsernamesRequest) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetStyle

`func (o *FreeToolGenerateUsernamesRequest) GetStyle() string`

GetStyle returns the Style field if non-nil, zero value otherwise.

### GetStyleOk

`func (o *FreeToolGenerateUsernamesRequest) GetStyleOk() (*string, bool)`

GetStyleOk returns a tuple with the Style field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStyle

`func (o *FreeToolGenerateUsernamesRequest) SetStyle(v string)`

SetStyle sets Style field to given value.

### HasStyle

`func (o *FreeToolGenerateUsernamesRequest) HasStyle() bool`

HasStyle returns a boolean if a field has been set.

### GetNumbers

`func (o *FreeToolGenerateUsernamesRequest) GetNumbers() bool`

GetNumbers returns the Numbers field if non-nil, zero value otherwise.

### GetNumbersOk

`func (o *FreeToolGenerateUsernamesRequest) GetNumbersOk() (*bool, bool)`

GetNumbersOk returns a tuple with the Numbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumbers

`func (o *FreeToolGenerateUsernamesRequest) SetNumbers(v bool)`

SetNumbers sets Numbers field to given value.

### HasNumbers

`func (o *FreeToolGenerateUsernamesRequest) HasNumbers() bool`

HasNumbers returns a boolean if a field has been set.

### GetSeed

`func (o *FreeToolGenerateUsernamesRequest) GetSeed() int32`

GetSeed returns the Seed field if non-nil, zero value otherwise.

### GetSeedOk

`func (o *FreeToolGenerateUsernamesRequest) GetSeedOk() (*int32, bool)`

GetSeedOk returns a tuple with the Seed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeed

`func (o *FreeToolGenerateUsernamesRequest) SetSeed(v int32)`

SetSeed sets Seed field to given value.

### HasSeed

`func (o *FreeToolGenerateUsernamesRequest) HasSeed() bool`

HasSeed returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


