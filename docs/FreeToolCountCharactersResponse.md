# FreeToolCountCharactersResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Hashtags** | Pointer to **int32** | Hashtags in the text (Instagram allows 5 per post in PostBoost). | [optional] 
**Networks** | Pointer to [**[]FreeToolCountCharactersResponseNetworksInner**](FreeToolCountCharactersResponseNetworksInner.md) |  | [optional] 

## Methods

### NewFreeToolCountCharactersResponse

`func NewFreeToolCountCharactersResponse() *FreeToolCountCharactersResponse`

NewFreeToolCountCharactersResponse instantiates a new FreeToolCountCharactersResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCountCharactersResponseWithDefaults

`func NewFreeToolCountCharactersResponseWithDefaults() *FreeToolCountCharactersResponse`

NewFreeToolCountCharactersResponseWithDefaults instantiates a new FreeToolCountCharactersResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHashtags

`func (o *FreeToolCountCharactersResponse) GetHashtags() int32`

GetHashtags returns the Hashtags field if non-nil, zero value otherwise.

### GetHashtagsOk

`func (o *FreeToolCountCharactersResponse) GetHashtagsOk() (*int32, bool)`

GetHashtagsOk returns a tuple with the Hashtags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHashtags

`func (o *FreeToolCountCharactersResponse) SetHashtags(v int32)`

SetHashtags sets Hashtags field to given value.

### HasHashtags

`func (o *FreeToolCountCharactersResponse) HasHashtags() bool`

HasHashtags returns a boolean if a field has been set.

### GetNetworks

`func (o *FreeToolCountCharactersResponse) GetNetworks() []FreeToolCountCharactersResponseNetworksInner`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *FreeToolCountCharactersResponse) GetNetworksOk() (*[]FreeToolCountCharactersResponseNetworksInner, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *FreeToolCountCharactersResponse) SetNetworks(v []FreeToolCountCharactersResponseNetworksInner)`

SetNetworks sets Networks field to given value.

### HasNetworks

`func (o *FreeToolCountCharactersResponse) HasNetworks() bool`

HasNetworks returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


