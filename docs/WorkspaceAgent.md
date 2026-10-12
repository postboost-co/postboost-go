# WorkspaceAgent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**Type** | **string** |  | 
**Name** | **string** |  | 
**Enabled** | **bool** |  | 
**Schedule** | **string** |  | 
**Settings** | [**WorkspaceAgentSettings**](WorkspaceAgentSettings.md) |  | 
**LastRunAt** | **NullableTime** |  | 
**NextRunAt** | **NullableTime** |  | 
**CreatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewWorkspaceAgent

`func NewWorkspaceAgent(uuid string, type_ string, name string, enabled bool, schedule string, settings WorkspaceAgentSettings, lastRunAt NullableTime, nextRunAt NullableTime, ) *WorkspaceAgent`

NewWorkspaceAgent instantiates a new WorkspaceAgent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkspaceAgentWithDefaults

`func NewWorkspaceAgentWithDefaults() *WorkspaceAgent`

NewWorkspaceAgentWithDefaults instantiates a new WorkspaceAgent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *WorkspaceAgent) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *WorkspaceAgent) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *WorkspaceAgent) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetType

`func (o *WorkspaceAgent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *WorkspaceAgent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *WorkspaceAgent) SetType(v string)`

SetType sets Type field to given value.


### GetName

`func (o *WorkspaceAgent) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WorkspaceAgent) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WorkspaceAgent) SetName(v string)`

SetName sets Name field to given value.


### GetEnabled

`func (o *WorkspaceAgent) GetEnabled() bool`

GetEnabled returns the Enabled field if non-nil, zero value otherwise.

### GetEnabledOk

`func (o *WorkspaceAgent) GetEnabledOk() (*bool, bool)`

GetEnabledOk returns a tuple with the Enabled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnabled

`func (o *WorkspaceAgent) SetEnabled(v bool)`

SetEnabled sets Enabled field to given value.


### GetSchedule

`func (o *WorkspaceAgent) GetSchedule() string`

GetSchedule returns the Schedule field if non-nil, zero value otherwise.

### GetScheduleOk

`func (o *WorkspaceAgent) GetScheduleOk() (*string, bool)`

GetScheduleOk returns a tuple with the Schedule field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchedule

`func (o *WorkspaceAgent) SetSchedule(v string)`

SetSchedule sets Schedule field to given value.


### GetSettings

`func (o *WorkspaceAgent) GetSettings() WorkspaceAgentSettings`

GetSettings returns the Settings field if non-nil, zero value otherwise.

### GetSettingsOk

`func (o *WorkspaceAgent) GetSettingsOk() (*WorkspaceAgentSettings, bool)`

GetSettingsOk returns a tuple with the Settings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettings

`func (o *WorkspaceAgent) SetSettings(v WorkspaceAgentSettings)`

SetSettings sets Settings field to given value.


### GetLastRunAt

`func (o *WorkspaceAgent) GetLastRunAt() time.Time`

GetLastRunAt returns the LastRunAt field if non-nil, zero value otherwise.

### GetLastRunAtOk

`func (o *WorkspaceAgent) GetLastRunAtOk() (*time.Time, bool)`

GetLastRunAtOk returns a tuple with the LastRunAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastRunAt

`func (o *WorkspaceAgent) SetLastRunAt(v time.Time)`

SetLastRunAt sets LastRunAt field to given value.


### SetLastRunAtNil

`func (o *WorkspaceAgent) SetLastRunAtNil(b bool)`

 SetLastRunAtNil sets the value for LastRunAt to be an explicit nil

### UnsetLastRunAt
`func (o *WorkspaceAgent) UnsetLastRunAt()`

UnsetLastRunAt ensures that no value is present for LastRunAt, not even an explicit nil
### GetNextRunAt

`func (o *WorkspaceAgent) GetNextRunAt() time.Time`

GetNextRunAt returns the NextRunAt field if non-nil, zero value otherwise.

### GetNextRunAtOk

`func (o *WorkspaceAgent) GetNextRunAtOk() (*time.Time, bool)`

GetNextRunAtOk returns a tuple with the NextRunAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextRunAt

`func (o *WorkspaceAgent) SetNextRunAt(v time.Time)`

SetNextRunAt sets NextRunAt field to given value.


### SetNextRunAtNil

`func (o *WorkspaceAgent) SetNextRunAtNil(b bool)`

 SetNextRunAtNil sets the value for NextRunAt to be an explicit nil

### UnsetNextRunAt
`func (o *WorkspaceAgent) UnsetNextRunAt()`

UnsetNextRunAt ensures that no value is present for NextRunAt, not even an explicit nil
### GetCreatedAt

`func (o *WorkspaceAgent) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *WorkspaceAgent) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *WorkspaceAgent) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *WorkspaceAgent) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *WorkspaceAgent) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *WorkspaceAgent) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


