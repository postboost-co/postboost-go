# RecyclingRuleUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IntervalDays** | Pointer to **int32** |  | [optional] 
**MaxRuns** | Pointer to **NullableInt32** |  | [optional] 
**Placement** | Pointer to **string** |  | [optional] 
**AccountIds** | Pointer to **[]int32** |  | [optional] 
**StartAt** | Pointer to **NullableTime** | Next run. | [optional] 
**Active** | Pointer to **bool** |  | [optional] 

## Methods

### NewRecyclingRuleUpdate

`func NewRecyclingRuleUpdate() *RecyclingRuleUpdate`

NewRecyclingRuleUpdate instantiates a new RecyclingRuleUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecyclingRuleUpdateWithDefaults

`func NewRecyclingRuleUpdateWithDefaults() *RecyclingRuleUpdate`

NewRecyclingRuleUpdateWithDefaults instantiates a new RecyclingRuleUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIntervalDays

`func (o *RecyclingRuleUpdate) GetIntervalDays() int32`

GetIntervalDays returns the IntervalDays field if non-nil, zero value otherwise.

### GetIntervalDaysOk

`func (o *RecyclingRuleUpdate) GetIntervalDaysOk() (*int32, bool)`

GetIntervalDaysOk returns a tuple with the IntervalDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntervalDays

`func (o *RecyclingRuleUpdate) SetIntervalDays(v int32)`

SetIntervalDays sets IntervalDays field to given value.

### HasIntervalDays

`func (o *RecyclingRuleUpdate) HasIntervalDays() bool`

HasIntervalDays returns a boolean if a field has been set.

### GetMaxRuns

`func (o *RecyclingRuleUpdate) GetMaxRuns() int32`

GetMaxRuns returns the MaxRuns field if non-nil, zero value otherwise.

### GetMaxRunsOk

`func (o *RecyclingRuleUpdate) GetMaxRunsOk() (*int32, bool)`

GetMaxRunsOk returns a tuple with the MaxRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRuns

`func (o *RecyclingRuleUpdate) SetMaxRuns(v int32)`

SetMaxRuns sets MaxRuns field to given value.

### HasMaxRuns

`func (o *RecyclingRuleUpdate) HasMaxRuns() bool`

HasMaxRuns returns a boolean if a field has been set.

### SetMaxRunsNil

`func (o *RecyclingRuleUpdate) SetMaxRunsNil(b bool)`

 SetMaxRunsNil sets the value for MaxRuns to be an explicit nil

### UnsetMaxRuns
`func (o *RecyclingRuleUpdate) UnsetMaxRuns()`

UnsetMaxRuns ensures that no value is present for MaxRuns, not even an explicit nil
### GetPlacement

`func (o *RecyclingRuleUpdate) GetPlacement() string`

GetPlacement returns the Placement field if non-nil, zero value otherwise.

### GetPlacementOk

`func (o *RecyclingRuleUpdate) GetPlacementOk() (*string, bool)`

GetPlacementOk returns a tuple with the Placement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlacement

`func (o *RecyclingRuleUpdate) SetPlacement(v string)`

SetPlacement sets Placement field to given value.

### HasPlacement

`func (o *RecyclingRuleUpdate) HasPlacement() bool`

HasPlacement returns a boolean if a field has been set.

### GetAccountIds

`func (o *RecyclingRuleUpdate) GetAccountIds() []int32`

GetAccountIds returns the AccountIds field if non-nil, zero value otherwise.

### GetAccountIdsOk

`func (o *RecyclingRuleUpdate) GetAccountIdsOk() (*[]int32, bool)`

GetAccountIdsOk returns a tuple with the AccountIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountIds

`func (o *RecyclingRuleUpdate) SetAccountIds(v []int32)`

SetAccountIds sets AccountIds field to given value.

### HasAccountIds

`func (o *RecyclingRuleUpdate) HasAccountIds() bool`

HasAccountIds returns a boolean if a field has been set.

### SetAccountIdsNil

`func (o *RecyclingRuleUpdate) SetAccountIdsNil(b bool)`

 SetAccountIdsNil sets the value for AccountIds to be an explicit nil

### UnsetAccountIds
`func (o *RecyclingRuleUpdate) UnsetAccountIds()`

UnsetAccountIds ensures that no value is present for AccountIds, not even an explicit nil
### GetStartAt

`func (o *RecyclingRuleUpdate) GetStartAt() time.Time`

GetStartAt returns the StartAt field if non-nil, zero value otherwise.

### GetStartAtOk

`func (o *RecyclingRuleUpdate) GetStartAtOk() (*time.Time, bool)`

GetStartAtOk returns a tuple with the StartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartAt

`func (o *RecyclingRuleUpdate) SetStartAt(v time.Time)`

SetStartAt sets StartAt field to given value.

### HasStartAt

`func (o *RecyclingRuleUpdate) HasStartAt() bool`

HasStartAt returns a boolean if a field has been set.

### SetStartAtNil

`func (o *RecyclingRuleUpdate) SetStartAtNil(b bool)`

 SetStartAtNil sets the value for StartAt to be an explicit nil

### UnsetStartAt
`func (o *RecyclingRuleUpdate) UnsetStartAt()`

UnsetStartAt ensures that no value is present for StartAt, not even an explicit nil
### GetActive

`func (o *RecyclingRuleUpdate) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *RecyclingRuleUpdate) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *RecyclingRuleUpdate) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *RecyclingRuleUpdate) HasActive() bool`

HasActive returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


