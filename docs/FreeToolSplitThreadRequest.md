# FreeToolSplitThreadRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | Pointer to **string** | The long text, up to 10,000 characters. A line with only --- forces a new post. | [optional] [default to ""]
**Network** | Pointer to **string** |  | [optional] [default to "x"]
**Numbering** | Pointer to **bool** | End each post with \&quot; k/n\&quot;. | [optional] [default to false]

## Methods

### NewFreeToolSplitThreadRequest

`func NewFreeToolSplitThreadRequest() *FreeToolSplitThreadRequest`

NewFreeToolSplitThreadRequest instantiates a new FreeToolSplitThreadRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolSplitThreadRequestWithDefaults

`func NewFreeToolSplitThreadRequestWithDefaults() *FreeToolSplitThreadRequest`

NewFreeToolSplitThreadRequestWithDefaults instantiates a new FreeToolSplitThreadRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolSplitThreadRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolSplitThreadRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolSplitThreadRequest) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *FreeToolSplitThreadRequest) HasText() bool`

HasText returns a boolean if a field has been set.

### GetNetwork

`func (o *FreeToolSplitThreadRequest) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *FreeToolSplitThreadRequest) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *FreeToolSplitThreadRequest) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *FreeToolSplitThreadRequest) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetNumbering

`func (o *FreeToolSplitThreadRequest) GetNumbering() bool`

GetNumbering returns the Numbering field if non-nil, zero value otherwise.

### GetNumberingOk

`func (o *FreeToolSplitThreadRequest) GetNumberingOk() (*bool, bool)`

GetNumberingOk returns a tuple with the Numbering field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNumbering

`func (o *FreeToolSplitThreadRequest) SetNumbering(v bool)`

SetNumbering sets Numbering field to given value.

### HasNumbering

`func (o *FreeToolSplitThreadRequest) HasNumbering() bool`

HasNumbering returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


