# RecyclingRule

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**Type** | **string** |  | 
**PostUuid** | **NullableString** |  | 
**TagUuid** | **NullableString** |  | 
**AccountIds** | **[]int32** |  | 
**IntervalDays** | **int32** |  | 
**MaxRuns** | **NullableInt32** |  | 
**RunsDone** | **int32** | Copies created so far. | 
**Placement** | **string** |  | 
**Active** | **bool** |  | 
**NextRunAt** | **NullableTime** |  | 
**LastRunAt** | **NullableTime** |  | 
**CreatedAt** | **NullableTime** |  | 

## Methods

### NewRecyclingRule

`func NewRecyclingRule(uuid string, type_ string, postUuid NullableString, tagUuid NullableString, accountIds []int32, intervalDays int32, maxRuns NullableInt32, runsDone int32, placement string, active bool, nextRunAt NullableTime, lastRunAt NullableTime, createdAt NullableTime, ) *RecyclingRule`

NewRecyclingRule instantiates a new RecyclingRule object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecyclingRuleWithDefaults

`func NewRecyclingRuleWithDefaults() *RecyclingRule`

NewRecyclingRuleWithDefaults instantiates a new RecyclingRule object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *RecyclingRule) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *RecyclingRule) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *RecyclingRule) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetType

`func (o *RecyclingRule) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *RecyclingRule) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *RecyclingRule) SetType(v string)`

SetType sets Type field to given value.


### GetPostUuid

`func (o *RecyclingRule) GetPostUuid() string`

GetPostUuid returns the PostUuid field if non-nil, zero value otherwise.

### GetPostUuidOk

`func (o *RecyclingRule) GetPostUuidOk() (*string, bool)`

GetPostUuidOk returns a tuple with the PostUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostUuid

`func (o *RecyclingRule) SetPostUuid(v string)`

SetPostUuid sets PostUuid field to given value.


### SetPostUuidNil

`func (o *RecyclingRule) SetPostUuidNil(b bool)`

 SetPostUuidNil sets the value for PostUuid to be an explicit nil

### UnsetPostUuid
`func (o *RecyclingRule) UnsetPostUuid()`

UnsetPostUuid ensures that no value is present for PostUuid, not even an explicit nil
### GetTagUuid

`func (o *RecyclingRule) GetTagUuid() string`

GetTagUuid returns the TagUuid field if non-nil, zero value otherwise.

### GetTagUuidOk

`func (o *RecyclingRule) GetTagUuidOk() (*string, bool)`

GetTagUuidOk returns a tuple with the TagUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagUuid

`func (o *RecyclingRule) SetTagUuid(v string)`

SetTagUuid sets TagUuid field to given value.


### SetTagUuidNil

`func (o *RecyclingRule) SetTagUuidNil(b bool)`

 SetTagUuidNil sets the value for TagUuid to be an explicit nil

### UnsetTagUuid
`func (o *RecyclingRule) UnsetTagUuid()`

UnsetTagUuid ensures that no value is present for TagUuid, not even an explicit nil
### GetAccountIds

`func (o *RecyclingRule) GetAccountIds() []int32`

GetAccountIds returns the AccountIds field if non-nil, zero value otherwise.

### GetAccountIdsOk

`func (o *RecyclingRule) GetAccountIdsOk() (*[]int32, bool)`

GetAccountIdsOk returns a tuple with the AccountIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountIds

`func (o *RecyclingRule) SetAccountIds(v []int32)`

SetAccountIds sets AccountIds field to given value.


### SetAccountIdsNil

`func (o *RecyclingRule) SetAccountIdsNil(b bool)`

 SetAccountIdsNil sets the value for AccountIds to be an explicit nil

### UnsetAccountIds
`func (o *RecyclingRule) UnsetAccountIds()`

UnsetAccountIds ensures that no value is present for AccountIds, not even an explicit nil
### GetIntervalDays

`func (o *RecyclingRule) GetIntervalDays() int32`

GetIntervalDays returns the IntervalDays field if non-nil, zero value otherwise.

### GetIntervalDaysOk

`func (o *RecyclingRule) GetIntervalDaysOk() (*int32, bool)`

GetIntervalDaysOk returns a tuple with the IntervalDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntervalDays

`func (o *RecyclingRule) SetIntervalDays(v int32)`

SetIntervalDays sets IntervalDays field to given value.


### GetMaxRuns

`func (o *RecyclingRule) GetMaxRuns() int32`

GetMaxRuns returns the MaxRuns field if non-nil, zero value otherwise.

### GetMaxRunsOk

`func (o *RecyclingRule) GetMaxRunsOk() (*int32, bool)`

GetMaxRunsOk returns a tuple with the MaxRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRuns

`func (o *RecyclingRule) SetMaxRuns(v int32)`

SetMaxRuns sets MaxRuns field to given value.


### SetMaxRunsNil

`func (o *RecyclingRule) SetMaxRunsNil(b bool)`

 SetMaxRunsNil sets the value for MaxRuns to be an explicit nil

### UnsetMaxRuns
`func (o *RecyclingRule) UnsetMaxRuns()`

UnsetMaxRuns ensures that no value is present for MaxRuns, not even an explicit nil
### GetRunsDone

`func (o *RecyclingRule) GetRunsDone() int32`

GetRunsDone returns the RunsDone field if non-nil, zero value otherwise.

### GetRunsDoneOk

`func (o *RecyclingRule) GetRunsDoneOk() (*int32, bool)`

GetRunsDoneOk returns a tuple with the RunsDone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunsDone

`func (o *RecyclingRule) SetRunsDone(v int32)`

SetRunsDone sets RunsDone field to given value.


### GetPlacement

`func (o *RecyclingRule) GetPlacement() string`

GetPlacement returns the Placement field if non-nil, zero value otherwise.

### GetPlacementOk

`func (o *RecyclingRule) GetPlacementOk() (*string, bool)`

GetPlacementOk returns a tuple with the Placement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlacement

`func (o *RecyclingRule) SetPlacement(v string)`

SetPlacement sets Placement field to given value.


### GetActive

`func (o *RecyclingRule) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *RecyclingRule) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *RecyclingRule) SetActive(v bool)`

SetActive sets Active field to given value.


### GetNextRunAt

`func (o *RecyclingRule) GetNextRunAt() time.Time`

GetNextRunAt returns the NextRunAt field if non-nil, zero value otherwise.

### GetNextRunAtOk

`func (o *RecyclingRule) GetNextRunAtOk() (*time.Time, bool)`

GetNextRunAtOk returns a tuple with the NextRunAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextRunAt

`func (o *RecyclingRule) SetNextRunAt(v time.Time)`

SetNextRunAt sets NextRunAt field to given value.


### SetNextRunAtNil

`func (o *RecyclingRule) SetNextRunAtNil(b bool)`

 SetNextRunAtNil sets the value for NextRunAt to be an explicit nil

### UnsetNextRunAt
`func (o *RecyclingRule) UnsetNextRunAt()`

UnsetNextRunAt ensures that no value is present for NextRunAt, not even an explicit nil
### GetLastRunAt

`func (o *RecyclingRule) GetLastRunAt() time.Time`

GetLastRunAt returns the LastRunAt field if non-nil, zero value otherwise.

### GetLastRunAtOk

`func (o *RecyclingRule) GetLastRunAtOk() (*time.Time, bool)`

GetLastRunAtOk returns a tuple with the LastRunAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastRunAt

`func (o *RecyclingRule) SetLastRunAt(v time.Time)`

SetLastRunAt sets LastRunAt field to given value.


### SetLastRunAtNil

`func (o *RecyclingRule) SetLastRunAtNil(b bool)`

 SetLastRunAtNil sets the value for LastRunAt to be an explicit nil

### UnsetLastRunAt
`func (o *RecyclingRule) UnsetLastRunAt()`

UnsetLastRunAt ensures that no value is present for LastRunAt, not even an explicit nil
### GetCreatedAt

`func (o *RecyclingRule) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RecyclingRule) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RecyclingRule) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### SetCreatedAtNil

`func (o *RecyclingRule) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *RecyclingRule) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


