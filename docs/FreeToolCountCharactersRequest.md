# FreeToolCountCharactersRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | Pointer to **string** | The post text, up to 10,000 characters (twice the longest network limit). | [optional] [default to ""]
**Network** | Pointer to **string** | Count for one network only; all networks when omitted. | [optional] 

## Methods

### NewFreeToolCountCharactersRequest

`func NewFreeToolCountCharactersRequest() *FreeToolCountCharactersRequest`

NewFreeToolCountCharactersRequest instantiates a new FreeToolCountCharactersRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCountCharactersRequestWithDefaults

`func NewFreeToolCountCharactersRequestWithDefaults() *FreeToolCountCharactersRequest`

NewFreeToolCountCharactersRequestWithDefaults instantiates a new FreeToolCountCharactersRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolCountCharactersRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolCountCharactersRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolCountCharactersRequest) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *FreeToolCountCharactersRequest) HasText() bool`

HasText returns a boolean if a field has been set.

### GetNetwork

`func (o *FreeToolCountCharactersRequest) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *FreeToolCountCharactersRequest) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *FreeToolCountCharactersRequest) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *FreeToolCountCharactersRequest) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


