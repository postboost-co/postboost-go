# AgentProposal

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**RunUuid** | Pointer to **NullableString** |  | [optional] 
**PostUuid** | Pointer to **NullableString** |  | [optional] 
**AccountId** | Pointer to **NullableInt32** |  | [optional] 
**Kind** | **string** | &#x60;hold_post&#x60; moves the post back to draft; &#x60;edit_caption&#x60; replaces one caption. | 
**Severity** | **string** |  | 
**Reason** | **string** |  | 
**Payload** | **map[string]interface{}** | The proposed change. &#x60;hold_post&#x60;: &#x60;reasons[]&#x60; (&#x60;code&#x60;, &#x60;account_id&#x60;, &#x60;message&#x60;, &#x60;severity&#x60;) and &#x60;scheduled_at&#x60;. &#x60;edit_caption&#x60;: &#x60;version_account_id&#x60; (0 &#x3D; original), &#x60;item_index&#x60;, &#x60;before&#x60;, &#x60;after&#x60;. Both carry &#x60;post_updated_at&#x60;.  | 
**Status** | **string** |  | 
**DecidedAt** | Pointer to **NullableTime** |  | [optional] 
**AppliedAt** | Pointer to **NullableTime** |  | [optional] 
**Note** | Pointer to **NullableString** |  | [optional] 
**Error** | Pointer to **NullableString** | Why a proposal went stale or failed. | [optional] 
**CreatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewAgentProposal

`func NewAgentProposal(uuid string, kind string, severity string, reason string, payload map[string]interface{}, status string, ) *AgentProposal`

NewAgentProposal instantiates a new AgentProposal object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAgentProposalWithDefaults

`func NewAgentProposalWithDefaults() *AgentProposal`

NewAgentProposalWithDefaults instantiates a new AgentProposal object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *AgentProposal) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *AgentProposal) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *AgentProposal) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetRunUuid

`func (o *AgentProposal) GetRunUuid() string`

GetRunUuid returns the RunUuid field if non-nil, zero value otherwise.

### GetRunUuidOk

`func (o *AgentProposal) GetRunUuidOk() (*string, bool)`

GetRunUuidOk returns a tuple with the RunUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunUuid

`func (o *AgentProposal) SetRunUuid(v string)`

SetRunUuid sets RunUuid field to given value.

### HasRunUuid

`func (o *AgentProposal) HasRunUuid() bool`

HasRunUuid returns a boolean if a field has been set.

### SetRunUuidNil

`func (o *AgentProposal) SetRunUuidNil(b bool)`

 SetRunUuidNil sets the value for RunUuid to be an explicit nil

### UnsetRunUuid
`func (o *AgentProposal) UnsetRunUuid()`

UnsetRunUuid ensures that no value is present for RunUuid, not even an explicit nil
### GetPostUuid

`func (o *AgentProposal) GetPostUuid() string`

GetPostUuid returns the PostUuid field if non-nil, zero value otherwise.

### GetPostUuidOk

`func (o *AgentProposal) GetPostUuidOk() (*string, bool)`

GetPostUuidOk returns a tuple with the PostUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostUuid

`func (o *AgentProposal) SetPostUuid(v string)`

SetPostUuid sets PostUuid field to given value.

### HasPostUuid

`func (o *AgentProposal) HasPostUuid() bool`

HasPostUuid returns a boolean if a field has been set.

### SetPostUuidNil

`func (o *AgentProposal) SetPostUuidNil(b bool)`

 SetPostUuidNil sets the value for PostUuid to be an explicit nil

### UnsetPostUuid
`func (o *AgentProposal) UnsetPostUuid()`

UnsetPostUuid ensures that no value is present for PostUuid, not even an explicit nil
### GetAccountId

`func (o *AgentProposal) GetAccountId() int32`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *AgentProposal) GetAccountIdOk() (*int32, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *AgentProposal) SetAccountId(v int32)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *AgentProposal) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### SetAccountIdNil

`func (o *AgentProposal) SetAccountIdNil(b bool)`

 SetAccountIdNil sets the value for AccountId to be an explicit nil

### UnsetAccountId
`func (o *AgentProposal) UnsetAccountId()`

UnsetAccountId ensures that no value is present for AccountId, not even an explicit nil
### GetKind

`func (o *AgentProposal) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *AgentProposal) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *AgentProposal) SetKind(v string)`

SetKind sets Kind field to given value.


### GetSeverity

`func (o *AgentProposal) GetSeverity() string`

GetSeverity returns the Severity field if non-nil, zero value otherwise.

### GetSeverityOk

`func (o *AgentProposal) GetSeverityOk() (*string, bool)`

GetSeverityOk returns a tuple with the Severity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeverity

`func (o *AgentProposal) SetSeverity(v string)`

SetSeverity sets Severity field to given value.


### GetReason

`func (o *AgentProposal) GetReason() string`

GetReason returns the Reason field if non-nil, zero value otherwise.

### GetReasonOk

`func (o *AgentProposal) GetReasonOk() (*string, bool)`

GetReasonOk returns a tuple with the Reason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReason

`func (o *AgentProposal) SetReason(v string)`

SetReason sets Reason field to given value.


### GetPayload

`func (o *AgentProposal) GetPayload() map[string]interface{}`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *AgentProposal) GetPayloadOk() (*map[string]interface{}, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *AgentProposal) SetPayload(v map[string]interface{})`

SetPayload sets Payload field to given value.


### GetStatus

`func (o *AgentProposal) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AgentProposal) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AgentProposal) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetDecidedAt

`func (o *AgentProposal) GetDecidedAt() time.Time`

GetDecidedAt returns the DecidedAt field if non-nil, zero value otherwise.

### GetDecidedAtOk

`func (o *AgentProposal) GetDecidedAtOk() (*time.Time, bool)`

GetDecidedAtOk returns a tuple with the DecidedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecidedAt

`func (o *AgentProposal) SetDecidedAt(v time.Time)`

SetDecidedAt sets DecidedAt field to given value.

### HasDecidedAt

`func (o *AgentProposal) HasDecidedAt() bool`

HasDecidedAt returns a boolean if a field has been set.

### SetDecidedAtNil

`func (o *AgentProposal) SetDecidedAtNil(b bool)`

 SetDecidedAtNil sets the value for DecidedAt to be an explicit nil

### UnsetDecidedAt
`func (o *AgentProposal) UnsetDecidedAt()`

UnsetDecidedAt ensures that no value is present for DecidedAt, not even an explicit nil
### GetAppliedAt

`func (o *AgentProposal) GetAppliedAt() time.Time`

GetAppliedAt returns the AppliedAt field if non-nil, zero value otherwise.

### GetAppliedAtOk

`func (o *AgentProposal) GetAppliedAtOk() (*time.Time, bool)`

GetAppliedAtOk returns a tuple with the AppliedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAppliedAt

`func (o *AgentProposal) SetAppliedAt(v time.Time)`

SetAppliedAt sets AppliedAt field to given value.

### HasAppliedAt

`func (o *AgentProposal) HasAppliedAt() bool`

HasAppliedAt returns a boolean if a field has been set.

### SetAppliedAtNil

`func (o *AgentProposal) SetAppliedAtNil(b bool)`

 SetAppliedAtNil sets the value for AppliedAt to be an explicit nil

### UnsetAppliedAt
`func (o *AgentProposal) UnsetAppliedAt()`

UnsetAppliedAt ensures that no value is present for AppliedAt, not even an explicit nil
### GetNote

`func (o *AgentProposal) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *AgentProposal) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *AgentProposal) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *AgentProposal) HasNote() bool`

HasNote returns a boolean if a field has been set.

### SetNoteNil

`func (o *AgentProposal) SetNoteNil(b bool)`

 SetNoteNil sets the value for Note to be an explicit nil

### UnsetNote
`func (o *AgentProposal) UnsetNote()`

UnsetNote ensures that no value is present for Note, not even an explicit nil
### GetError

`func (o *AgentProposal) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AgentProposal) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AgentProposal) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *AgentProposal) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *AgentProposal) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *AgentProposal) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetCreatedAt

`func (o *AgentProposal) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *AgentProposal) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *AgentProposal) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *AgentProposal) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *AgentProposal) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *AgentProposal) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


