# FreeToolGenerateUsernamesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Network** | Pointer to **string** |  | [optional] 
**Style** | Pointer to **string** |  | [optional] 
**Seed** | Pointer to **int32** |  | [optional] 
**Usernames** | Pointer to [**[]FreeToolGenerateUsernamesResponseUsernamesInner**](FreeToolGenerateUsernamesResponseUsernamesInner.md) | Up to 30 names, each valid for the network. Not checked for availability: open the profile URL to see whether a name is taken. | [optional] 
**Rules** | Pointer to [**FreeToolGenerateUsernamesResponseRules**](FreeToolGenerateUsernamesResponseRules.md) |  | [optional] 

## Methods

### NewFreeToolGenerateUsernamesResponse

`func NewFreeToolGenerateUsernamesResponse() *FreeToolGenerateUsernamesResponse`

NewFreeToolGenerateUsernamesResponse instantiates a new FreeToolGenerateUsernamesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateUsernamesResponseWithDefaults

`func NewFreeToolGenerateUsernamesResponseWithDefaults() *FreeToolGenerateUsernamesResponse`

NewFreeToolGenerateUsernamesResponseWithDefaults instantiates a new FreeToolGenerateUsernamesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNetwork

`func (o *FreeToolGenerateUsernamesResponse) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *FreeToolGenerateUsernamesResponse) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *FreeToolGenerateUsernamesResponse) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *FreeToolGenerateUsernamesResponse) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetStyle

`func (o *FreeToolGenerateUsernamesResponse) GetStyle() string`

GetStyle returns the Style field if non-nil, zero value otherwise.

### GetStyleOk

`func (o *FreeToolGenerateUsernamesResponse) GetStyleOk() (*string, bool)`

GetStyleOk returns a tuple with the Style field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStyle

`func (o *FreeToolGenerateUsernamesResponse) SetStyle(v string)`

SetStyle sets Style field to given value.

### HasStyle

`func (o *FreeToolGenerateUsernamesResponse) HasStyle() bool`

HasStyle returns a boolean if a field has been set.

### GetSeed

`func (o *FreeToolGenerateUsernamesResponse) GetSeed() int32`

GetSeed returns the Seed field if non-nil, zero value otherwise.

### GetSeedOk

`func (o *FreeToolGenerateUsernamesResponse) GetSeedOk() (*int32, bool)`

GetSeedOk returns a tuple with the Seed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeed

`func (o *FreeToolGenerateUsernamesResponse) SetSeed(v int32)`

SetSeed sets Seed field to given value.

### HasSeed

`func (o *FreeToolGenerateUsernamesResponse) HasSeed() bool`

HasSeed returns a boolean if a field has been set.

### GetUsernames

`func (o *FreeToolGenerateUsernamesResponse) GetUsernames() []FreeToolGenerateUsernamesResponseUsernamesInner`

GetUsernames returns the Usernames field if non-nil, zero value otherwise.

### GetUsernamesOk

`func (o *FreeToolGenerateUsernamesResponse) GetUsernamesOk() (*[]FreeToolGenerateUsernamesResponseUsernamesInner, bool)`

GetUsernamesOk returns a tuple with the Usernames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsernames

`func (o *FreeToolGenerateUsernamesResponse) SetUsernames(v []FreeToolGenerateUsernamesResponseUsernamesInner)`

SetUsernames sets Usernames field to given value.

### HasUsernames

`func (o *FreeToolGenerateUsernamesResponse) HasUsernames() bool`

HasUsernames returns a boolean if a field has been set.

### GetRules

`func (o *FreeToolGenerateUsernamesResponse) GetRules() FreeToolGenerateUsernamesResponseRules`

GetRules returns the Rules field if non-nil, zero value otherwise.

### GetRulesOk

`func (o *FreeToolGenerateUsernamesResponse) GetRulesOk() (*FreeToolGenerateUsernamesResponseRules, bool)`

GetRulesOk returns a tuple with the Rules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRules

`func (o *FreeToolGenerateUsernamesResponse) SetRules(v FreeToolGenerateUsernamesResponseRules)`

SetRules sets Rules field to given value.

### HasRules

`func (o *FreeToolGenerateUsernamesResponse) HasRules() bool`

HasRules returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


