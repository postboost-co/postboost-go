# WorkspaceAgentUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** |  | [optional] 
**Enabled** | Pointer to **bool** |  | [optional] 
**Schedule** | Pointer to **string** |  | [optional] 
**Settings** | Pointer to [**WorkspaceAgentSettings**](WorkspaceAgentSettings.md) |  | [optional] 

## Methods

### NewWorkspaceAgentUpdate

`func NewWorkspaceAgentUpdate() *WorkspaceAgentUpdate`

NewWorkspaceAgentUpdate instantiates a new WorkspaceAgentUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkspaceAgentUpdateWithDefaults

`func NewWorkspaceAgentUpdateWithDefaults() *WorkspaceAgentUpdate`

NewWorkspaceAgentUpdateWithDefaults instantiates a new WorkspaceAgentUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *WorkspaceAgentUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WorkspaceAgentUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WorkspaceAgentUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *WorkspaceAgentUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### GetEnabled

`func (o *WorkspaceAgentUpdate) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *WorkspaceAgentUpdate) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *WorkspaceAgentUpdate) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.

### HasEnabled

`func (o *WorkspaceAgentUpdate) HasEnabled() bool`

HasEnabled returns a boolean if a field has been set.

### GetSchedule

`func (o *WorkspaceAgentUpdate) GetSchedule() string`

GetSchedule returns the Schedule field if non-nil, zero value otherwise.

### GetScheduleOk

`func (o *WorkspaceAgentUpdate) GetScheduleOk() (*string, bool)`

GetScheduleOk returns a tuple with the Schedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedule

`func (o *WorkspaceAgentUpdate) SetSchedule(v string)`

SetSchedule sets Schedule field to given value.

### HasSchedule

`func (o *WorkspaceAgentUpdate) HasSchedule() bool`

HasSchedule returns a boolean if a field has been set.

### GetSettings

`func (o *WorkspaceAgentUpdate) GetSettings() WorkspaceAgentSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *WorkspaceAgentUpdate) GetSettingsOk() (*WorkspaceAgentSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *WorkspaceAgentUpdate) SetSettings(v WorkspaceAgentSettings)`

SetSettings sets Settings field to given value.

### HasSettings

`func (o *WorkspaceAgentUpdate) HasSettings() bool`

HasSettings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


