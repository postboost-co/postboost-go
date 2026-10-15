# FreeToolGenerateHashtagsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Topic** | **string** | What the post is about. | 
**Niche** | Pointer to **string** | Optional niche, e.g. \&quot;fitness\&quot; or \&quot;real estate\&quot;. | [optional] 
**Network** | Pointer to **string** | The network the text is written for. | [optional] [default to "instagram"]
**Workspace** | Pointer to **string** | UUID of the workspace whose AI credits pay for the call. Default: your active workspace (a scoped API key: its own workspace). | [optional] 

## Methods

### NewFreeToolGenerateHashtagsRequest

`func NewFreeToolGenerateHashtagsRequest(topic string, ) *FreeToolGenerateHashtagsRequest`

NewFreeToolGenerateHashtagsRequest instantiates a new FreeToolGenerateHashtagsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateHashtagsRequestWithDefaults

`func NewFreeToolGenerateHashtagsRequestWithDefaults() *FreeToolGenerateHashtagsRequest`

NewFreeToolGenerateHashtagsRequestWithDefaults instantiates a new FreeToolGenerateHashtagsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTopic

`func (o *FreeToolGenerateHashtagsRequest) GetTopic() string`

GetTopic returns the Topic field if non-nil, zero value otherwise.

### GetTopicOk

`func (o *FreeToolGenerateHashtagsRequest) GetTopicOk() (*string, bool)`

GetTopicOk returns a tuple with the Topic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopic

`func (o *FreeToolGenerateHashtagsRequest) SetTopic(v string)`

SetTopic sets Topic field to given value.


### GetNiche

`func (o *FreeToolGenerateHashtagsRequest) GetNiche() string`

GetNiche returns the Niche field if non-nil, zero value otherwise.

### GetNicheOk

`func (o *FreeToolGenerateHashtagsRequest) GetNicheOk() (*string, bool)`

GetNicheOk returns a tuple with the Niche field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNiche

`func (o *FreeToolGenerateHashtagsRequest) SetNiche(v string)`

SetNiche sets Niche field to given value.

### HasNiche

`func (o *FreeToolGenerateHashtagsRequest) HasNiche() bool`

HasNiche returns a boolean if a field has been set.

### GetNetwork

`func (o *FreeToolGenerateHashtagsRequest) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *FreeToolGenerateHashtagsRequest) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *FreeToolGenerateHashtagsRequest) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *FreeToolGenerateHashtagsRequest) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetWorkspace

`func (o *FreeToolGenerateHashtagsRequest) GetWorkspace() string`

GetWorkspace returns the Workspace field if non-nil, zero value otherwise.

### GetWorkspaceOk

`func (o *FreeToolGenerateHashtagsRequest) GetWorkspaceOk() (*string, bool)`

GetWorkspaceOk returns a tuple with the Workspace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspace

`func (o *FreeToolGenerateHashtagsRequest) SetWorkspace(v string)`

SetWorkspace sets Workspace field to given value.

### HasWorkspace

`func (o *FreeToolGenerateHashtagsRequest) HasWorkspace() bool`

HasWorkspace returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


