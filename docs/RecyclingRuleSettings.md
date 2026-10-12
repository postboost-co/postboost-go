# RecyclingRuleSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IntervalDays** | **int32** | Days between copies. | 
**MaxRuns** | Pointer to **NullableInt32** | Copies to create before the rule stops; null &#x3D; no limit. | [optional] 
**Placement** | Pointer to **string** | &#x60;queue&#x60;: each account&#39;s next free queue slot (skipped when the queue is full for 14 days). &#x60;same_time&#x60;: the source post&#39;s time of day. &#x60;draft&#x60;: a draft only. | [optional] [default to "queue"]
**AccountIds** | Pointer to **[]int32** | Accounts for the copies; default the source post&#39;s accounts. For a tag pool, limits each picked post&#39;s accounts. | [optional] 
**StartAt** | Pointer to **NullableTime** | First run; default one interval from now. | [optional] 
**Active** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewRecyclingRuleSettings

`func NewRecyclingRuleSettings(intervalDays int32, ) *RecyclingRuleSettings`

NewRecyclingRuleSettings instantiates a new RecyclingRuleSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecyclingRuleSettingsWithDefaults

`func NewRecyclingRuleSettingsWithDefaults() *RecyclingRuleSettings`

NewRecyclingRuleSettingsWithDefaults instantiates a new RecyclingRuleSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIntervalDays

`func (o *RecyclingRuleSettings) GetIntervalDays() int32`

GetIntervalDays returns the IntervalDays field if non-nil, zero value otherwise.

### GetIntervalDaysOk

`func (o *RecyclingRuleSettings) GetIntervalDaysOk() (*int32, bool)`

GetIntervalDaysOk returns a tuple with the IntervalDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntervalDays

`func (o *RecyclingRuleSettings) SetIntervalDays(v int32)`

SetIntervalDays sets IntervalDays field to given value.


### GetMaxRuns

`func (o *RecyclingRuleSettings) GetMaxRuns() int32`

GetMaxRuns returns the MaxRuns field if non-nil, zero value otherwise.

### GetMaxRunsOk

`func (o *RecyclingRuleSettings) GetMaxRunsOk() (*int32, bool)`

GetMaxRunsOk returns a tuple with the MaxRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRuns

`func (o *RecyclingRuleSettings) SetMaxRuns(v int32)`

SetMaxRuns sets MaxRuns field to given value.

### HasMaxRuns

`func (o *RecyclingRuleSettings) HasMaxRuns() bool`

HasMaxRuns returns a boolean if a field has been set.

### SetMaxRunsNil

`func (o *RecyclingRuleSettings) SetMaxRunsNil(b bool)`

 SetMaxRunsNil sets the value for MaxRuns to be an explicit nil

### UnsetMaxRuns
`func (o *RecyclingRuleSettings) UnsetMaxRuns()`

UnsetMaxRuns ensures that no value is present for MaxRuns, not even an explicit nil
### GetPlacement

`func (o *RecyclingRuleSettings) GetPlacement() string`

GetPlacement returns the Placement field if non-nil, zero value otherwise.

### GetPlacementOk

`func (o *RecyclingRuleSettings) GetPlacementOk() (*string, bool)`

GetPlacementOk returns a tuple with the Placement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlacement

`func (o *RecyclingRuleSettings) SetPlacement(v string)`

SetPlacement sets Placement field to given value.

### HasPlacement

`func (o *RecyclingRuleSettings) HasPlacement() bool`

HasPlacement returns a boolean if a field has been set.

### GetAccountIds

`func (o *RecyclingRuleSettings) GetAccountIds() []int32`

GetAccountIds returns the AccountIds field if non-nil, zero value otherwise.

### GetAccountIdsOk

`func (o *RecyclingRuleSettings) GetAccountIdsOk() (*[]int32, bool)`

GetAccountIdsOk returns a tuple with the AccountIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountIds

`func (o *RecyclingRuleSettings) SetAccountIds(v []int32)`

SetAccountIds sets AccountIds field to given value.

### HasAccountIds

`func (o *RecyclingRuleSettings) HasAccountIds() bool`

HasAccountIds returns a boolean if a field has been set.

### SetAccountIdsNil

`func (o *RecyclingRuleSettings) SetAccountIdsNil(b bool)`

 SetAccountIdsNil sets the value for AccountIds to be an explicit nil

### UnsetAccountIds
`func (o *RecyclingRuleSettings) UnsetAccountIds()`

UnsetAccountIds ensures that no value is present for AccountIds, not even an explicit nil
### GetStartAt

`func (o *RecyclingRuleSettings) GetStartAt() time.Time`

GetStartAt returns the StartAt field if non-nil, zero value otherwise.

### GetStartAtOk

`func (o *RecyclingRuleSettings) GetStartAtOk() (*time.Time, bool)`

GetStartAtOk returns a tuple with the StartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartAt

`func (o *RecyclingRuleSettings) SetStartAt(v time.Time)`

SetStartAt sets StartAt field to given value.

### HasStartAt

`func (o *RecyclingRuleSettings) HasStartAt() bool`

HasStartAt returns a boolean if a field has been set.

### SetStartAtNil

`func (o *RecyclingRuleSettings) SetStartAtNil(b bool)`

 SetStartAtNil sets the value for StartAt to be an explicit nil

### UnsetStartAt
`func (o *RecyclingRuleSettings) UnsetStartAt()`

UnsetStartAt ensures that no value is present for StartAt, not even an explicit nil
### GetActive

`func (o *RecyclingRuleSettings) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *RecyclingRuleSettings) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *RecyclingRuleSettings) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *RecyclingRuleSettings) HasActive() bool`

HasActive returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


