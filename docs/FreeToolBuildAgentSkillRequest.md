# FreeToolBuildAgentSkillRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Format** | Pointer to **string** | skill_md (an Agent Skills SKILL.md), agents_md (AGENTS.md) or system_prompt. | [optional] [default to "skill_md"]
**Name** | Pointer to **string** | The skill name, normalised to lowercase letters, digits and hyphens and cut to 64 characters. | [optional] [default to "postboost-social-media"]
**Brand** | Pointer to **string** | The brand the agent works for; omitted when empty. | [optional] [default to ""]
**Tasks** | Pointer to **[]string** | What the agent does; the output keeps this enum&#39;s order. | [optional] [default to [draft_posts, schedule_posts]]
**Networks** | Pointer to **[]string** | Networks to add character-limit rules for; none leaves the section out. | [optional] [default to []]
**Autonomy** | Pointer to **string** | How much the agent may do without asking. | [optional] [default to "drafts_only"]
**DailyCap** | Pointer to **int32** | Posts per day the agent may create; 0 adds no cap line. | [optional] [default to 5]
**BrandVoice** | Pointer to **bool** | Read the workspace brand voice before writing captions. | [optional] [default to true]
**Connection** | Pointer to **string** | connector (the OAuth MCP connector) or api_token (the advanced MCP server with an API key). | [optional] [default to "connector"]
**Rules** | Pointer to **[]string** | Your own do&#39;s and don&#39;ts, one per item. | [optional] [default to []]

## Methods

### NewFreeToolBuildAgentSkillRequest

`func NewFreeToolBuildAgentSkillRequest() *FreeToolBuildAgentSkillRequest`

NewFreeToolBuildAgentSkillRequest instantiates a new FreeToolBuildAgentSkillRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolBuildAgentSkillRequestWithDefaults

`func NewFreeToolBuildAgentSkillRequestWithDefaults() *FreeToolBuildAgentSkillRequest`

NewFreeToolBuildAgentSkillRequestWithDefaults instantiates a new FreeToolBuildAgentSkillRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFormat

`func (o *FreeToolBuildAgentSkillRequest) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *FreeToolBuildAgentSkillRequest) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *FreeToolBuildAgentSkillRequest) SetFormat(v string)`

SetFormat sets Format field to given value.

### HasFormat

`func (o *FreeToolBuildAgentSkillRequest) HasFormat() bool`

HasFormat returns a boolean if a field has been set.

### GetName

`func (o *FreeToolBuildAgentSkillRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *FreeToolBuildAgentSkillRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *FreeToolBuildAgentSkillRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *FreeToolBuildAgentSkillRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetBrand

`func (o *FreeToolBuildAgentSkillRequest) GetBrand() string`

GetBrand returns the Brand field if non-nil, zero value otherwise.

### GetBrandOk

`func (o *FreeToolBuildAgentSkillRequest) GetBrandOk() (*string, bool)`

GetBrandOk returns a tuple with the Brand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand

`func (o *FreeToolBuildAgentSkillRequest) SetBrand(v string)`

SetBrand sets Brand field to given value.

### HasBrand

`func (o *FreeToolBuildAgentSkillRequest) HasBrand() bool`

HasBrand returns a boolean if a field has been set.

### GetTasks

`func (o *FreeToolBuildAgentSkillRequest) GetTasks() []string`

GetTasks returns the Tasks field if non-nil, zero value otherwise.

### GetTasksOk

`func (o *FreeToolBuildAgentSkillRequest) GetTasksOk() (*[]string, bool)`

GetTasksOk returns a tuple with the Tasks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTasks

`func (o *FreeToolBuildAgentSkillRequest) SetTasks(v []string)`

SetTasks sets Tasks field to given value.

### HasTasks

`func (o *FreeToolBuildAgentSkillRequest) HasTasks() bool`

HasTasks returns a boolean if a field has been set.

### GetNetworks

`func (o *FreeToolBuildAgentSkillRequest) GetNetworks() []string`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *FreeToolBuildAgentSkillRequest) GetNetworksOk() (*[]string, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *FreeToolBuildAgentSkillRequest) SetNetworks(v []string)`

SetNetworks sets Networks field to given value.

### HasNetworks

`func (o *FreeToolBuildAgentSkillRequest) HasNetworks() bool`

HasNetworks returns a boolean if a field has been set.

### GetAutonomy

`func (o *FreeToolBuildAgentSkillRequest) GetAutonomy() string`

GetAutonomy returns the Autonomy field if non-nil, zero value otherwise.

### GetAutonomyOk

`func (o *FreeToolBuildAgentSkillRequest) GetAutonomyOk() (*string, bool)`

GetAutonomyOk returns a tuple with the Autonomy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutonomy

`func (o *FreeToolBuildAgentSkillRequest) SetAutonomy(v string)`

SetAutonomy sets Autonomy field to given value.

### HasAutonomy

`func (o *FreeToolBuildAgentSkillRequest) HasAutonomy() bool`

HasAutonomy returns a boolean if a field has been set.

### GetDailyCap

`func (o *FreeToolBuildAgentSkillRequest) GetDailyCap() int32`

GetDailyCap returns the DailyCap field if non-nil, zero value otherwise.

### GetDailyCapOk

`func (o *FreeToolBuildAgentSkillRequest) GetDailyCapOk() (*int32, bool)`

GetDailyCapOk returns a tuple with the DailyCap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyCap

`func (o *FreeToolBuildAgentSkillRequest) SetDailyCap(v int32)`

SetDailyCap sets DailyCap field to given value.

### HasDailyCap

`func (o *FreeToolBuildAgentSkillRequest) HasDailyCap() bool`

HasDailyCap returns a boolean if a field has been set.

### GetBrandVoice

`func (o *FreeToolBuildAgentSkillRequest) GetBrandVoice() bool`

GetBrandVoice returns the BrandVoice field if non-nil, zero value otherwise.

### GetBrandVoiceOk

`func (o *FreeToolBuildAgentSkillRequest) GetBrandVoiceOk() (*bool, bool)`

GetBrandVoiceOk returns a tuple with the BrandVoice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandVoice

`func (o *FreeToolBuildAgentSkillRequest) SetBrandVoice(v bool)`

SetBrandVoice sets BrandVoice field to given value.

### HasBrandVoice

`func (o *FreeToolBuildAgentSkillRequest) HasBrandVoice() bool`

HasBrandVoice returns a boolean if a field has been set.

### GetConnection

`func (o *FreeToolBuildAgentSkillRequest) GetConnection() string`

GetConnection returns the Connection field if non-nil, zero value otherwise.

### GetConnectionOk

`func (o *FreeToolBuildAgentSkillRequest) GetConnectionOk() (*string, bool)`

GetConnectionOk returns a tuple with the Connection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnection

`func (o *FreeToolBuildAgentSkillRequest) SetConnection(v string)`

SetConnection sets Connection field to given value.

### HasConnection

`func (o *FreeToolBuildAgentSkillRequest) HasConnection() bool`

HasConnection returns a boolean if a field has been set.

### GetRules

`func (o *FreeToolBuildAgentSkillRequest) GetRules() []string`

GetRules returns the Rules field if non-nil, zero value otherwise.

### GetRulesOk

`func (o *FreeToolBuildAgentSkillRequest) GetRulesOk() (*[]string, bool)`

GetRulesOk returns a tuple with the Rules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRules

`func (o *FreeToolBuildAgentSkillRequest) SetRules(v []string)`

SetRules sets Rules field to given value.

### HasRules

`func (o *FreeToolBuildAgentSkillRequest) HasRules() bool`

HasRules returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


