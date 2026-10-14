# AccountHealthDailyCap

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Limit** | **int32** | Posts allowed per UTC day for this network; Free workspaces get half (rounded down, at least 1). | 
**UsedToday** | **int32** | Scheduled, awaiting-approval and published posts counted for today (UTC). | 

## Methods

### NewAccountHealthDailyCap

`func NewAccountHealthDailyCap(limit int32, usedToday int32, ) *AccountHealthDailyCap`

NewAccountHealthDailyCap instantiates a new AccountHealthDailyCap object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountHealthDailyCapWithDefaults

`func NewAccountHealthDailyCapWithDefaults() *AccountHealthDailyCap`

NewAccountHealthDailyCapWithDefaults instantiates a new AccountHealthDailyCap object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimit

`func (o *AccountHealthDailyCap) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *AccountHealthDailyCap) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *AccountHealthDailyCap) SetLimit(v int32)`

SetLimit sets Limit field to given value.


### GetUsedToday

`func (o *AccountHealthDailyCap) GetUsedToday() int32`

GetUsedToday returns the UsedToday field if non-nil, zero value otherwise.

### GetUsedTodayOk

`func (o *AccountHealthDailyCap) GetUsedTodayOk() (*int32, bool)`

GetUsedTodayOk returns a tuple with the UsedToday field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsedToday

`func (o *AccountHealthDailyCap) SetUsedToday(v int32)`

SetUsedToday sets UsedToday field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


