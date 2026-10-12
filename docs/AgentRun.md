# AgentRun

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**AgentUuid** | **NullableString** |  | 
**AgentType** | **NullableString** |  | 
**Trigger** | **string** |  | 
**Status** | **string** |  | 
**StartedAt** | Pointer to **NullableTime** |  | [optional] 
**FinishedAt** | Pointer to **NullableTime** |  | [optional] 
**ItemsChecked** | **int32** |  | 
**ProposalsCreated** | **int32** |  | 
**CreditsUsed** | **int32** | AI credits this run used. | 
**Summary** | Pointer to **NullableString** |  | [optional] 
**Error** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | Pointer to **NullableTime** |  | [optional] 
**Proposals** | Pointer to [**[]AgentProposal**](AgentProposal.md) | Only on &#x60;GET /agent-runs/{runUuid}&#x60;. | [optional] 

## Methods

### NewAgentRun

`func NewAgentRun(uuid string, agentUuid NullableString, agentType NullableString, trigger string, status string, itemsChecked int32, proposalsCreated int32, creditsUsed int32, ) *AgentRun`

NewAgentRun instantiates a new AgentRun object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentRunWithDefaults

`func NewAgentRunWithDefaults() *AgentRun`

NewAgentRunWithDefaults instantiates a new AgentRun object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *AgentRun) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *AgentRun) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *AgentRun) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetAgentUuid

`func (o *AgentRun) GetAgentUuid() string`

GetAgentUuid returns the AgentUuid field if non-nil, zero value otherwise.

### GetAgentUuidOk

`func (o *AgentRun) GetAgentUuidOk() (*string, bool)`

GetAgentUuidOk returns a tuple with the AgentUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentUuid

`func (o *AgentRun) SetAgentUuid(v string)`

SetAgentUuid sets AgentUuid field to given value.


### SetAgentUuidNil

`func (o *AgentRun) SetAgentUuidNil(b bool)`

 SetAgentUuidNil sets the value for AgentUuid to be an explicit nil

### UnsetAgentUuid
`func (o *AgentRun) UnsetAgentUuid()`

UnsetAgentUuid ensures that no value is present for AgentUuid, not even an explicit nil
### GetAgentType

`func (o *AgentRun) GetAgentType() string`

GetAgentType returns the AgentType field if non-nil, zero value otherwise.

### GetAgentTypeOk

`func (o *AgentRun) GetAgentTypeOk() (*string, bool)`

GetAgentTypeOk returns a tuple with the AgentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAgentType

`func (o *AgentRun) SetAgentType(v string)`

SetAgentType sets AgentType field to given value.


### SetAgentTypeNil

`func (o *AgentRun) SetAgentTypeNil(b bool)`

 SetAgentTypeNil sets the value for AgentType to be an explicit nil

### UnsetAgentType
`func (o *AgentRun) UnsetAgentType()`

UnsetAgentType ensures that no value is present for AgentType, not even an explicit nil
### GetTrigger

`func (o *AgentRun) GetTrigger() string`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *AgentRun) GetTriggerOk() (*string, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *AgentRun) SetTrigger(v string)`

SetTrigger sets Trigger field to given value.


### GetStatus

`func (o *AgentRun) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AgentRun) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AgentRun) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStartedAt

`func (o *AgentRun) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *AgentRun) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *AgentRun) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *AgentRun) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### SetStartedAtNil

`func (o *AgentRun) SetStartedAtNil(b bool)`

 SetStartedAtNil sets the value for StartedAt to be an explicit nil

### UnsetStartedAt
`func (o *AgentRun) UnsetStartedAt()`

UnsetStartedAt ensures that no value is present for StartedAt, not even an explicit nil
### GetFinishedAt

`func (o *AgentRun) GetFinishedAt() time.Time`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *AgentRun) GetFinishedAtOk() (*time.Time, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *AgentRun) SetFinishedAt(v time.Time)`

SetFinishedAt sets FinishedAt field to given value.

### HasFinishedAt

`func (o *AgentRun) HasFinishedAt() bool`

HasFinishedAt returns a boolean if a field has been set.

### SetFinishedAtNil

`func (o *AgentRun) SetFinishedAtNil(b bool)`

 SetFinishedAtNil sets the value for FinishedAt to be an explicit nil

### UnsetFinishedAt
`func (o *AgentRun) UnsetFinishedAt()`

UnsetFinishedAt ensures that no value is present for FinishedAt, not even an explicit nil
### GetItemsChecked

`func (o *AgentRun) GetItemsChecked() int32`

GetItemsChecked returns the ItemsChecked field if non-nil, zero value otherwise.

### GetItemsCheckedOk

`func (o *AgentRun) GetItemsCheckedOk() (*int32, bool)`

GetItemsCheckedOk returns a tuple with the ItemsChecked field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemsChecked

`func (o *AgentRun) SetItemsChecked(v int32)`

SetItemsChecked sets ItemsChecked field to given value.


### GetProposalsCreated

`func (o *AgentRun) GetProposalsCreated() int32`

GetProposalsCreated returns the ProposalsCreated field if non-nil, zero value otherwise.

### GetProposalsCreatedOk

`func (o *AgentRun) GetProposalsCreatedOk() (*int32, bool)`

GetProposalsCreatedOk returns a tuple with the ProposalsCreated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposalsCreated

`func (o *AgentRun) SetProposalsCreated(v int32)`

SetProposalsCreated sets ProposalsCreated field to given value.


### GetCreditsUsed

`func (o *AgentRun) GetCreditsUsed() int32`

GetCreditsUsed returns the CreditsUsed field if non-nil, zero value otherwise.

### GetCreditsUsedOk

`func (o *AgentRun) GetCreditsUsedOk() (*int32, bool)`

GetCreditsUsedOk returns a tuple with the CreditsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsUsed

`func (o *AgentRun) SetCreditsUsed(v int32)`

SetCreditsUsed sets CreditsUsed field to given value.


### GetSummary

`func (o *AgentRun) GetSummary() string`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *AgentRun) GetSummaryOk() (*string, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *AgentRun) SetSummary(v string)`

SetSummary sets Summary field to given value.

### HasSummary

`func (o *AgentRun) HasSummary() bool`

HasSummary returns a boolean if a field has been set.

### SetSummaryNil

`func (o *AgentRun) SetSummaryNil(b bool)`

 SetSummaryNil sets the value for Summary to be an explicit nil

### UnsetSummary
`func (o *AgentRun) UnsetSummary()`

UnsetSummary ensures that no value is present for Summary, not even an explicit nil
### GetError

`func (o *AgentRun) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AgentRun) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AgentRun) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *AgentRun) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *AgentRun) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *AgentRun) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetCreatedAt

`func (o *AgentRun) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AgentRun) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AgentRun) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *AgentRun) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *AgentRun) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *AgentRun) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetProposals

`func (o *AgentRun) GetProposals() []AgentProposal`

GetProposals returns the Proposals field if non-nil, zero value otherwise.

### GetProposalsOk

`func (o *AgentRun) GetProposalsOk() (*[]AgentProposal, bool)`

GetProposalsOk returns a tuple with the Proposals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProposals

`func (o *AgentRun) SetProposals(v []AgentProposal)`

SetProposals sets Proposals field to given value.

### HasProposals

`func (o *AgentRun) HasProposals() bool`

HasProposals returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


