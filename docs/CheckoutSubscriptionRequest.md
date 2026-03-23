# CheckoutSubscriptionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PlanId** | **int32** |  | 
**Cycle** | **string** |  | 
**Coupon** | Pointer to **string** |  | [optional] 

## Methods

### NewCheckoutSubscriptionRequest

`func NewCheckoutSubscriptionRequest(planId int32, cycle string, ) *CheckoutSubscriptionRequest`

NewCheckoutSubscriptionRequest instantiates a new CheckoutSubscriptionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCheckoutSubscriptionRequestWithDefaults

`func NewCheckoutSubscriptionRequestWithDefaults() *CheckoutSubscriptionRequest`

NewCheckoutSubscriptionRequestWithDefaults instantiates a new CheckoutSubscriptionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlanId

`func (o *CheckoutSubscriptionRequest) GetPlanId() int32`

GetPlanId returns the PlanId field if non-nil, zero value otherwise.

### GetPlanIdOk

`func (o *CheckoutSubscriptionRequest) GetPlanIdOk() (*int32, bool)`

GetPlanIdOk returns a tuple with the PlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlanId

`func (o *CheckoutSubscriptionRequest) SetPlanId(v int32)`

SetPlanId sets PlanId field to given value.


### GetCycle

`func (o *CheckoutSubscriptionRequest) GetCycle() string`

GetCycle returns the Cycle field if non-nil, zero value otherwise.

### GetCycleOk

`func (o *CheckoutSubscriptionRequest) GetCycleOk() (*string, bool)`

GetCycleOk returns a tuple with the Cycle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCycle

`func (o *CheckoutSubscriptionRequest) SetCycle(v string)`

SetCycle sets Cycle field to given value.


### GetCoupon

`func (o *CheckoutSubscriptionRequest) GetCoupon() string`

GetCoupon returns the Coupon field if non-nil, zero value otherwise.

### GetCouponOk

`func (o *CheckoutSubscriptionRequest) GetCouponOk() (*string, bool)`

GetCouponOk returns a tuple with the Coupon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoupon

`func (o *CheckoutSubscriptionRequest) SetCoupon(v string)`

SetCoupon sets Coupon field to given value.

### HasCoupon

`func (o *CheckoutSubscriptionRequest) HasCoupon() bool`

HasCoupon returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


