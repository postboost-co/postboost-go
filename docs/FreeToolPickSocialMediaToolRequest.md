# FreeToolPickSocialMediaToolRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Needs** | Pointer to **[]string** | What you need: team_dashboard (Scheduling dashboard for a team), rest_openapi (REST API with a published OpenAPI spec), sdks (At least one official SDK), mcp (MCP server for AI agents), webhooks (Webhooks), free_tier (Free hosted plan), zapier (Native Zapier app), n8n (Native n8n node), make (Native Make app). Required unless use_case is set. | [optional] 
**UseCase** | Pointer to **string** | A shortcut used when needs is left out: team_scheduling (team_dashboard, free_tier), build_app (rest_openapi, sdks, webhooks), ai_agent (mcp, rest_openapi). | [optional] 

## Methods

### NewFreeToolPickSocialMediaToolRequest

`func NewFreeToolPickSocialMediaToolRequest() *FreeToolPickSocialMediaToolRequest`

NewFreeToolPickSocialMediaToolRequest instantiates a new FreeToolPickSocialMediaToolRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolPickSocialMediaToolRequestWithDefaults

`func NewFreeToolPickSocialMediaToolRequestWithDefaults() *FreeToolPickSocialMediaToolRequest`

NewFreeToolPickSocialMediaToolRequestWithDefaults instantiates a new FreeToolPickSocialMediaToolRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNeeds

`func (o *FreeToolPickSocialMediaToolRequest) GetNeeds() []string`

GetNeeds returns the Needs field if non-nil, zero value otherwise.

### GetNeedsOk

`func (o *FreeToolPickSocialMediaToolRequest) GetNeedsOk() (*[]string, bool)`

GetNeedsOk returns a tuple with the Needs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeeds

`func (o *FreeToolPickSocialMediaToolRequest) SetNeeds(v []string)`

SetNeeds sets Needs field to given value.

### HasNeeds

`func (o *FreeToolPickSocialMediaToolRequest) HasNeeds() bool`

HasNeeds returns a boolean if a field has been set.

### GetUseCase

`func (o *FreeToolPickSocialMediaToolRequest) GetUseCase() string`

GetUseCase returns the UseCase field if non-nil, zero value otherwise.

### GetUseCaseOk

`func (o *FreeToolPickSocialMediaToolRequest) GetUseCaseOk() (*string, bool)`

GetUseCaseOk returns a tuple with the UseCase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUseCase

`func (o *FreeToolPickSocialMediaToolRequest) SetUseCase(v string)`

SetUseCase sets UseCase field to given value.

### HasUseCase

`func (o *FreeToolPickSocialMediaToolRequest) HasUseCase() bool`

HasUseCase returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


