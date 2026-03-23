# ChangeSubscriptionPlanRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PlanId** | **int32** |  | 
**Cycle** | **string** |  | 
**Prorate** | **bool** |  | 
**BillingImmediately** | **bool** |  | 

## Methods

### NewChangeSubscriptionPlanRequest

`func NewChangeSubscriptionPlanRequest(planId int32, cycle string, prorate bool, billingImmediately bool, ) *ChangeSubscriptionPlanRequest`

NewChangeSubscriptionPlanRequest instantiates a new ChangeSubscriptionPlanRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChangeSubscriptionPlanRequestWithDefaults

`func NewChangeSubscriptionPlanRequestWithDefaults() *ChangeSubscriptionPlanRequest`

NewChangeSubscriptionPlanRequestWithDefaults instantiates a new ChangeSubscriptionPlanRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlanId

`func (o *ChangeSubscriptionPlanRequest) GetPlanId() int32`

GetPlanId returns the PlanId field if non-nil, zero value otherwise.

### GetPlanIdOk

`func (o *ChangeSubscriptionPlanRequest) GetPlanIdOk() (*int32, bool)`

GetPlanIdOk returns a tuple with the PlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanId

`func (o *ChangeSubscriptionPlanRequest) SetPlanId(v int32)`

SetPlanId sets PlanId field to given value.


### GetCycle

`func (o *ChangeSubscriptionPlanRequest) GetCycle() string`

GetCycle returns the Cycle field if non-nil, zero value otherwise.

### GetCycleOk

`func (o *ChangeSubscriptionPlanRequest) GetCycleOk() (*string, bool)`

GetCycleOk returns a tuple with the Cycle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycle

`func (o *ChangeSubscriptionPlanRequest) SetCycle(v string)`

SetCycle sets Cycle field to given value.


### GetProrate

`func (o *ChangeSubscriptionPlanRequest) GetProrate() bool`

GetProrate returns the Prorate field if non-nil, zero value otherwise.

### GetProrateOk

`func (o *ChangeSubscriptionPlanRequest) GetProrateOk() (*bool, bool)`

GetProrateOk returns a tuple with the Prorate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProrate

`func (o *ChangeSubscriptionPlanRequest) SetProrate(v bool)`

SetProrate sets Prorate field to given value.


### GetBillingImmediately

`func (o *ChangeSubscriptionPlanRequest) GetBillingImmediately() bool`

GetBillingImmediately returns the BillingImmediately field if non-nil, zero value otherwise.

### GetBillingImmediatelyOk

`func (o *ChangeSubscriptionPlanRequest) GetBillingImmediatelyOk() (*bool, bool)`

GetBillingImmediatelyOk returns a tuple with the BillingImmediately field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBillingImmediately

`func (o *ChangeSubscriptionPlanRequest) SetBillingImmediately(v bool)`

SetBillingImmediately sets BillingImmediately field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


