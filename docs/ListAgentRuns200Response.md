# ListAgentRuns200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]AgentRun**](AgentRun.md) |  | 
**Meta** | [**AgentPageMeta**](AgentPageMeta.md) |  | 

## Methods

### NewListAgentRuns200Response

`func NewListAgentRuns200Response(data []AgentRun, meta AgentPageMeta, ) *ListAgentRuns200Response`

NewListAgentRuns200Response instantiates a new ListAgentRuns200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListAgentRuns200ResponseWithDefaults

`func NewListAgentRuns200ResponseWithDefaults() *ListAgentRuns200Response`

NewListAgentRuns200ResponseWithDefaults instantiates a new ListAgentRuns200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ListAgentRuns200Response) GetData() []AgentRun`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListAgentRuns200Response) GetDataOk() (*[]AgentRun, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListAgentRuns200Response) SetData(v []AgentRun)`

SetData sets Data field to given value.


### GetMeta

`func (o *ListAgentRuns200Response) GetMeta() AgentPageMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ListAgentRuns200Response) GetMetaOk() (*AgentPageMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ListAgentRuns200Response) SetMeta(v AgentPageMeta)`

SetMeta sets Meta field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


