# FreeToolCheckPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | Pointer to **string** | The post text, up to 10,000 characters; 5,000 without an API token. | [optional] [default to ""]
**Networks** | **[]string** | The networks to check the post for. | 
**Media** | Pointer to [**FreeToolCheckPostRequestMedia**](FreeToolCheckPostRequestMedia.md) |  | [optional] 

## Methods

### NewFreeToolCheckPostRequest

`func NewFreeToolCheckPostRequest(networks []string, ) *FreeToolCheckPostRequest`

NewFreeToolCheckPostRequest instantiates a new FreeToolCheckPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCheckPostRequestWithDefaults

`func NewFreeToolCheckPostRequestWithDefaults() *FreeToolCheckPostRequest`

NewFreeToolCheckPostRequestWithDefaults instantiates a new FreeToolCheckPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolCheckPostRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolCheckPostRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolCheckPostRequest) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *FreeToolCheckPostRequest) HasText() bool`

HasText returns a boolean if a field has been set.

### GetNetworks

`func (o *FreeToolCheckPostRequest) GetNetworks() []string`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *FreeToolCheckPostRequest) GetNetworksOk() (*[]string, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *FreeToolCheckPostRequest) SetNetworks(v []string)`

SetNetworks sets Networks field to given value.


### GetMedia

`func (o *FreeToolCheckPostRequest) GetMedia() FreeToolCheckPostRequestMedia`

GetMedia returns the Media field if non-nil, zero value otherwise.

### GetMediaOk

`func (o *FreeToolCheckPostRequest) GetMediaOk() (*FreeToolCheckPostRequestMedia, bool)`

GetMediaOk returns a tuple with the Media field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMedia

`func (o *FreeToolCheckPostRequest) SetMedia(v FreeToolCheckPostRequestMedia)`

SetMedia sets Media field to given value.

### HasMedia

`func (o *FreeToolCheckPostRequest) HasMedia() bool`

HasMedia returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


