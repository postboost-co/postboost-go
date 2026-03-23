# AddGenericSubscriptionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PlanId** | **int32** |  | 
**TrialDays** | Pointer to **int32** |  | [optional] 
**KeepPrevTrialEndsAt** | **bool** |  | 

## Methods

### NewAddGenericSubscriptionRequest

`func NewAddGenericSubscriptionRequest(planId int32, keepPrevTrialEndsAt bool, ) *AddGenericSubscriptionRequest`

NewAddGenericSubscriptionRequest instantiates a new AddGenericSubscriptionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddGenericSubscriptionRequestWithDefaults

`func NewAddGenericSubscriptionRequestWithDefaults() *AddGenericSubscriptionRequest`

NewAddGenericSubscriptionRequestWithDefaults instantiates a new AddGenericSubscriptionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlanId

`func (o *AddGenericSubscriptionRequest) GetPlanId() int32`

GetPlanId returns the PlanId field if non-nil, zero value otherwise.

### GetPlanIdOk

`func (o *AddGenericSubscriptionRequest) GetPlanIdOk() (*int32, bool)`

GetPlanIdOk returns a tuple with the PlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanId

`func (o *AddGenericSubscriptionRequest) SetPlanId(v int32)`

SetPlanId sets PlanId field to given value.


### GetTrialDays

`func (o *AddGenericSubscriptionRequest) GetTrialDays() int32`

GetTrialDays returns the TrialDays field if non-nil, zero value otherwise.

### GetTrialDaysOk

`func (o *AddGenericSubscriptionRequest) GetTrialDaysOk() (*int32, bool)`

GetTrialDaysOk returns a tuple with the TrialDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialDays

`func (o *AddGenericSubscriptionRequest) SetTrialDays(v int32)`

SetTrialDays sets TrialDays field to given value.

### HasTrialDays

`func (o *AddGenericSubscriptionRequest) HasTrialDays() bool`

HasTrialDays returns a boolean if a field has been set.

### GetKeepPrevTrialEndsAt

`func (o *AddGenericSubscriptionRequest) GetKeepPrevTrialEndsAt() bool`

GetKeepPrevTrialEndsAt returns the KeepPrevTrialEndsAt field if non-nil, zero value otherwise.

### GetKeepPrevTrialEndsAtOk

`func (o *AddGenericSubscriptionRequest) GetKeepPrevTrialEndsAtOk() (*bool, bool)`

GetKeepPrevTrialEndsAtOk returns a tuple with the KeepPrevTrialEndsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeepPrevTrialEndsAt

`func (o *AddGenericSubscriptionRequest) SetKeepPrevTrialEndsAt(v bool)`

SetKeepPrevTrialEndsAt sets KeepPrevTrialEndsAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


