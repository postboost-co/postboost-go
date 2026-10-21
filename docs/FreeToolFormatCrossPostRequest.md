# FreeToolFormatCrossPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | Pointer to **string** | The post text, up to 10,000 characters. | [optional] [default to ""]
**Networks** | Pointer to **[]string** | The networks to format for, in the order the result lists them. | [optional] [default to [x, threads, bluesky, mastodon, linkedin]]
**Numbering** | Pointer to **bool** | End each post of a thread with \&quot; k/n\&quot;. | [optional] [default to false]

## Methods

### NewFreeToolFormatCrossPostRequest

`func NewFreeToolFormatCrossPostRequest() *FreeToolFormatCrossPostRequest`

NewFreeToolFormatCrossPostRequest instantiates a new FreeToolFormatCrossPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolFormatCrossPostRequestWithDefaults

`func NewFreeToolFormatCrossPostRequestWithDefaults() *FreeToolFormatCrossPostRequest`

NewFreeToolFormatCrossPostRequestWithDefaults instantiates a new FreeToolFormatCrossPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolFormatCrossPostRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolFormatCrossPostRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolFormatCrossPostRequest) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *FreeToolFormatCrossPostRequest) HasText() bool`

HasText returns a boolean if a field has been set.

### GetNetworks

`func (o *FreeToolFormatCrossPostRequest) GetNetworks() []string`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *FreeToolFormatCrossPostRequest) GetNetworksOk() (*[]string, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *FreeToolFormatCrossPostRequest) SetNetworks(v []string)`

SetNetworks sets Networks field to given value.

### HasNetworks

`func (o *FreeToolFormatCrossPostRequest) HasNetworks() bool`

HasNetworks returns a boolean if a field has been set.

### GetNumbering

`func (o *FreeToolFormatCrossPostRequest) GetNumbering() bool`

GetNumbering returns the Numbering field if non-nil, zero value otherwise.

### GetNumberingOk

`func (o *FreeToolFormatCrossPostRequest) GetNumberingOk() (*bool, bool)`

GetNumberingOk returns a tuple with the Numbering field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumbering

`func (o *FreeToolFormatCrossPostRequest) SetNumbering(v bool)`

SetNumbering sets Numbering field to given value.

### HasNumbering

`func (o *FreeToolFormatCrossPostRequest) HasNumbering() bool`

HasNumbering returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


