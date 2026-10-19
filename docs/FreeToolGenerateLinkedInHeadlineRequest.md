# FreeToolGenerateLinkedInHeadlineRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Role** | **string** | Your role or what you do. | 
**Skills** | **string** | Your skills and the value you bring. | 
**Audience** | Pointer to **string** | Who you help (optional). | [optional] [default to ""]
**Tone** | Pointer to **string** |  | [optional] [default to "professional"]
**Workspace** | Pointer to **string** | UUID of the workspace whose AI credits pay for the call. Default: your active workspace (a scoped API key: its own workspace). | [optional] 

## Methods

### NewFreeToolGenerateLinkedInHeadlineRequest

`func NewFreeToolGenerateLinkedInHeadlineRequest(role string, skills string, ) *FreeToolGenerateLinkedInHeadlineRequest`

NewFreeToolGenerateLinkedInHeadlineRequest instantiates a new FreeToolGenerateLinkedInHeadlineRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateLinkedInHeadlineRequestWithDefaults

`func NewFreeToolGenerateLinkedInHeadlineRequestWithDefaults() *FreeToolGenerateLinkedInHeadlineRequest`

NewFreeToolGenerateLinkedInHeadlineRequestWithDefaults instantiates a new FreeToolGenerateLinkedInHeadlineRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRole

`func (o *FreeToolGenerateLinkedInHeadlineRequest) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *FreeToolGenerateLinkedInHeadlineRequest) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *FreeToolGenerateLinkedInHeadlineRequest) SetRole(v string)`

SetRole sets Role field to given value.


### GetSkills

`func (o *FreeToolGenerateLinkedInHeadlineRequest) GetSkills() string`

GetSkills returns the Skills field if non-nil, zero value otherwise.

### GetSkillsOk

`func (o *FreeToolGenerateLinkedInHeadlineRequest) GetSkillsOk() (*string, bool)`

GetSkillsOk returns a tuple with the Skills field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkills

`func (o *FreeToolGenerateLinkedInHeadlineRequest) SetSkills(v string)`

SetSkills sets Skills field to given value.


### GetAudience

`func (o *FreeToolGenerateLinkedInHeadlineRequest) GetAudience() string`

GetAudience returns the Audience field if non-nil, zero value otherwise.

### GetAudienceOk

`func (o *FreeToolGenerateLinkedInHeadlineRequest) GetAudienceOk() (*string, bool)`

GetAudienceOk returns a tuple with the Audience field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAudience

`func (o *FreeToolGenerateLinkedInHeadlineRequest) SetAudience(v string)`

SetAudience sets Audience field to given value.

### HasAudience

`func (o *FreeToolGenerateLinkedInHeadlineRequest) HasAudience() bool`

HasAudience returns a boolean if a field has been set.

### GetTone

`func (o *FreeToolGenerateLinkedInHeadlineRequest) GetTone() string`

GetTone returns the Tone field if non-nil, zero value otherwise.

### GetToneOk

`func (o *FreeToolGenerateLinkedInHeadlineRequest) GetToneOk() (*string, bool)`

GetToneOk returns a tuple with the Tone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTone

`func (o *FreeToolGenerateLinkedInHeadlineRequest) SetTone(v string)`

SetTone sets Tone field to given value.

### HasTone

`func (o *FreeToolGenerateLinkedInHeadlineRequest) HasTone() bool`

HasTone returns a boolean if a field has been set.

### GetWorkspace

`func (o *FreeToolGenerateLinkedInHeadlineRequest) GetWorkspace() string`

GetWorkspace returns the Workspace field if non-nil, zero value otherwise.

### GetWorkspaceOk

`func (o *FreeToolGenerateLinkedInHeadlineRequest) GetWorkspaceOk() (*string, bool)`

GetWorkspaceOk returns a tuple with the Workspace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspace

`func (o *FreeToolGenerateLinkedInHeadlineRequest) SetWorkspace(v string)`

SetWorkspace sets Workspace field to given value.

### HasWorkspace

`func (o *FreeToolGenerateLinkedInHeadlineRequest) HasWorkspace() bool`

HasWorkspace returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


