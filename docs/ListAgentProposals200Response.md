# ListAgentProposals200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]AgentProposal**](AgentProposal.md) |  | 
**Meta** | [**AgentPageMeta**](AgentPageMeta.md) |  | 

## Methods

### NewListAgentProposals200Response

`func NewListAgentProposals200Response(data []AgentProposal, meta AgentPageMeta, ) *ListAgentProposals200Response`

NewListAgentProposals200Response instantiates a new ListAgentProposals200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListAgentProposals200ResponseWithDefaults

`func NewListAgentProposals200ResponseWithDefaults() *ListAgentProposals200Response`

NewListAgentProposals200ResponseWithDefaults instantiates a new ListAgentProposals200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ListAgentProposals200Response) GetData() []AgentProposal`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListAgentProposals200Response) GetDataOk() (*[]AgentProposal, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListAgentProposals200Response) SetData(v []AgentProposal)`

SetData sets Data field to given value.


### GetMeta

`func (o *ListAgentProposals200Response) GetMeta() AgentPageMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ListAgentProposals200Response) GetMetaOk() (*AgentPageMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ListAgentProposals200Response) SetMeta(v AgentPageMeta)`

SetMeta sets Meta field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


