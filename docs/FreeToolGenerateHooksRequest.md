# FreeToolGenerateHooksRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Topic** | **string** | What the post is about. | 
**Tone** | Pointer to **string** | Tone of the hooks, as on the caption generator. | [optional] [default to "friendly"]
**Count** | Pointer to **int32** | How many hooks to write. | [optional] [default to 5]
**Network** | Pointer to **string** | The network the text is written for. | [optional] [default to "instagram"]
**Workspace** | Pointer to **string** | UUID of the workspace whose AI credits pay for the call. Default: your active workspace (a scoped API key: its own workspace). | [optional] 

## Methods

### NewFreeToolGenerateHooksRequest

`func NewFreeToolGenerateHooksRequest(topic string, ) *FreeToolGenerateHooksRequest`

NewFreeToolGenerateHooksRequest instantiates a new FreeToolGenerateHooksRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateHooksRequestWithDefaults

`func NewFreeToolGenerateHooksRequestWithDefaults() *FreeToolGenerateHooksRequest`

NewFreeToolGenerateHooksRequestWithDefaults instantiates a new FreeToolGenerateHooksRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTopic

`func (o *FreeToolGenerateHooksRequest) GetTopic() string`

GetTopic returns the Topic field if non-nil, zero value otherwise.

### GetTopicOk

`func (o *FreeToolGenerateHooksRequest) GetTopicOk() (*string, bool)`

GetTopicOk returns a tuple with the Topic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopic

`func (o *FreeToolGenerateHooksRequest) SetTopic(v string)`

SetTopic sets Topic field to given value.


### GetTone

`func (o *FreeToolGenerateHooksRequest) GetTone() string`

GetTone returns the Tone field if non-nil, zero value otherwise.

### GetToneOk

`func (o *FreeToolGenerateHooksRequest) GetToneOk() (*string, bool)`

GetToneOk returns a tuple with the Tone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTone

`func (o *FreeToolGenerateHooksRequest) SetTone(v string)`

SetTone sets Tone field to given value.

### HasTone

`func (o *FreeToolGenerateHooksRequest) HasTone() bool`

HasTone returns a boolean if a field has been set.

### GetCount

`func (o *FreeToolGenerateHooksRequest) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *FreeToolGenerateHooksRequest) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *FreeToolGenerateHooksRequest) SetCount(v int32)`

SetCount sets Count field to given value.

### HasCount

`func (o *FreeToolGenerateHooksRequest) HasCount() bool`

HasCount returns a boolean if a field has been set.

### GetNetwork

`func (o *FreeToolGenerateHooksRequest) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *FreeToolGenerateHooksRequest) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *FreeToolGenerateHooksRequest) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *FreeToolGenerateHooksRequest) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetWorkspace

`func (o *FreeToolGenerateHooksRequest) GetWorkspace() string`

GetWorkspace returns the Workspace field if non-nil, zero value otherwise.

### GetWorkspaceOk

`func (o *FreeToolGenerateHooksRequest) GetWorkspaceOk() (*string, bool)`

GetWorkspaceOk returns a tuple with the Workspace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspace

`func (o *FreeToolGenerateHooksRequest) SetWorkspace(v string)`

SetWorkspace sets Workspace field to given value.

### HasWorkspace

`func (o *FreeToolGenerateHooksRequest) HasWorkspace() bool`

HasWorkspace returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


