# WorkspaceAgentInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** |  | 
**Name** | Pointer to **string** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] [default to true]
**Schedule** | Pointer to **string** |  | [optional] [default to "hourly"]
**Settings** | Pointer to [**WorkspaceAgentSettings**](WorkspaceAgentSettings.md) |  | [optional] 

## Methods

### NewWorkspaceAgentInput

`func NewWorkspaceAgentInput(type_ string, ) *WorkspaceAgentInput`

NewWorkspaceAgentInput instantiates a new WorkspaceAgentInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkspaceAgentInputWithDefaults

`func NewWorkspaceAgentInputWithDefaults() *WorkspaceAgentInput`

NewWorkspaceAgentInputWithDefaults instantiates a new WorkspaceAgentInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *WorkspaceAgentInput) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *WorkspaceAgentInput) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *WorkspaceAgentInput) SetType(v string)`

SetType sets Type field to given value.


### GetName

`func (o *WorkspaceAgentInput) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WorkspaceAgentInput) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WorkspaceAgentInput) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *WorkspaceAgentInput) HasName() bool`

HasName returns a boolean if a field has been set.

### GetEnabled

`func (o *WorkspaceAgentInput) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *WorkspaceAgentInput) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *WorkspaceAgentInput) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *WorkspaceAgentInput) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetSchedule

`func (o *WorkspaceAgentInput) GetSchedule() string`

GetSchedule returns the Schedule field if non-nil, zero value otherwise.

### GetScheduleOk

`func (o *WorkspaceAgentInput) GetScheduleOk() (*string, bool)`

GetScheduleOk returns a tuple with the Schedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedule

`func (o *WorkspaceAgentInput) SetSchedule(v string)`

SetSchedule sets Schedule field to given value.

### HasSchedule

`func (o *WorkspaceAgentInput) HasSchedule() bool`

HasSchedule returns a boolean if a field has been set.

### GetSettings

`func (o *WorkspaceAgentInput) GetSettings() WorkspaceAgentSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *WorkspaceAgentInput) GetSettingsOk() (*WorkspaceAgentSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *WorkspaceAgentInput) SetSettings(v WorkspaceAgentSettings)`

SetSettings sets Settings field to given value.

### HasSettings

`func (o *WorkspaceAgentInput) HasSettings() bool`

HasSettings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


