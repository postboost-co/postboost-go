# RecyclingRuleInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**IntervalDays** | **int32** | Days between copies. | 
**MaxRuns** | Pointer to **int32** | Copies to create before the rule stops; null &#x3D; no limit. | [optional] 
**Placement** | Pointer to **string** | &#x60;queue&#x60;: each account&#39;s next free queue slot (skipped when the queue is full for 14 days). &#x60;same_time&#x60;: the source post&#39;s time of day. &#x60;draft&#x60;: a draft only. | [optional] [default to "queue"]
**AccountIds** | Pointer to **[]int32** | Accounts for the copies; default the source post&#39;s accounts. For a tag pool, limits each picked post&#39;s accounts. | [optional] 
**StartAt** | Pointer to **time.Time** | First run; default one interval from now. | [optional] 
**Active** | Pointer to **bool** |  | [optional] [default to true]
**Type** | Pointer to **string** | Defaults to &#x60;post&#x60; when &#x60;post_uuid&#x60; is sent, else &#x60;tag_pool&#x60;. | [optional] 
**PostUuid** | Pointer to **string** | The post to recycle (type &#x60;post&#x60;). | [optional] 
**TagUuid** | Pointer to **string** | The tag whose published posts are recycled, least recently recycled first (type &#x60;tag_pool&#x60;). | [optional] 

## Methods

### NewRecyclingRuleInput

`func NewRecyclingRuleInput(intervalDays int32, ) *RecyclingRuleInput`

NewRecyclingRuleInput instantiates a new RecyclingRuleInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecyclingRuleInputWithDefaults

`func NewRecyclingRuleInputWithDefaults() *RecyclingRuleInput`

NewRecyclingRuleInputWithDefaults instantiates a new RecyclingRuleInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIntervalDays

`func (o *RecyclingRuleInput) GetIntervalDays() int32`

GetIntervalDays returns the IntervalDays field if non-nil, zero value otherwise.

### GetIntervalDaysOk

`func (o *RecyclingRuleInput) GetIntervalDaysOk() (*int32, bool)`

GetIntervalDaysOk returns a tuple with the IntervalDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIntervalDays

`func (o *RecyclingRuleInput) SetIntervalDays(v int32)`

SetIntervalDays sets IntervalDays field to given value.


### GetMaxRuns

`func (o *RecyclingRuleInput) GetMaxRuns() int32`

GetMaxRuns returns the MaxRuns field if non-nil, zero value otherwise.

### GetMaxRunsOk

`func (o *RecyclingRuleInput) GetMaxRunsOk() (*int32, bool)`

GetMaxRunsOk returns a tuple with the MaxRuns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxRuns

`func (o *RecyclingRuleInput) SetMaxRuns(v int32)`

SetMaxRuns sets MaxRuns field to given value.

### HasMaxRuns

`func (o *RecyclingRuleInput) HasMaxRuns() bool`

HasMaxRuns returns a boolean if a field has been set.

### GetPlacement

`func (o *RecyclingRuleInput) GetPlacement() string`

GetPlacement returns the Placement field if non-nil, zero value otherwise.

### GetPlacementOk

`func (o *RecyclingRuleInput) GetPlacementOk() (*string, bool)`

GetPlacementOk returns a tuple with the Placement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlacement

`func (o *RecyclingRuleInput) SetPlacement(v string)`

SetPlacement sets Placement field to given value.

### HasPlacement

`func (o *RecyclingRuleInput) HasPlacement() bool`

HasPlacement returns a boolean if a field has been set.

### GetAccountIds

`func (o *RecyclingRuleInput) GetAccountIds() []int32`

GetAccountIds returns the AccountIds field if non-nil, zero value otherwise.

### GetAccountIdsOk

`func (o *RecyclingRuleInput) GetAccountIdsOk() (*[]int32, bool)`

GetAccountIdsOk returns a tuple with the AccountIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountIds

`func (o *RecyclingRuleInput) SetAccountIds(v []int32)`

SetAccountIds sets AccountIds field to given value.

### HasAccountIds

`func (o *RecyclingRuleInput) HasAccountIds() bool`

HasAccountIds returns a boolean if a field has been set.

### GetStartAt

`func (o *RecyclingRuleInput) GetStartAt() time.Time`

GetStartAt returns the StartAt field if non-nil, zero value otherwise.

### GetStartAtOk

`func (o *RecyclingRuleInput) GetStartAtOk() (*time.Time, bool)`

GetStartAtOk returns a tuple with the StartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartAt

`func (o *RecyclingRuleInput) SetStartAt(v time.Time)`

SetStartAt sets StartAt field to given value.

### HasStartAt

`func (o *RecyclingRuleInput) HasStartAt() bool`

HasStartAt returns a boolean if a field has been set.

### GetActive

`func (o *RecyclingRuleInput) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *RecyclingRuleInput) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *RecyclingRuleInput) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *RecyclingRuleInput) HasActive() bool`

HasActive returns a boolean if a field has been set.

### GetType

`func (o *RecyclingRuleInput) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *RecyclingRuleInput) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *RecyclingRuleInput) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *RecyclingRuleInput) HasType() bool`

HasType returns a boolean if a field has been set.

### GetPostUuid

`func (o *RecyclingRuleInput) GetPostUuid() string`

GetPostUuid returns the PostUuid field if non-nil, zero value otherwise.

### GetPostUuidOk

`func (o *RecyclingRuleInput) GetPostUuidOk() (*string, bool)`

GetPostUuidOk returns a tuple with the PostUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostUuid

`func (o *RecyclingRuleInput) SetPostUuid(v string)`

SetPostUuid sets PostUuid field to given value.

### HasPostUuid

`func (o *RecyclingRuleInput) HasPostUuid() bool`

HasPostUuid returns a boolean if a field has been set.

### GetTagUuid

`func (o *RecyclingRuleInput) GetTagUuid() string`

GetTagUuid returns the TagUuid field if non-nil, zero value otherwise.

### GetTagUuidOk

`func (o *RecyclingRuleInput) GetTagUuidOk() (*string, bool)`

GetTagUuidOk returns a tuple with the TagUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTagUuid

`func (o *RecyclingRuleInput) SetTagUuid(v string)`

SetTagUuid sets TagUuid field to given value.

### HasTagUuid

`func (o *RecyclingRuleInput) HasTagUuid() bool`

HasTagUuid returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


