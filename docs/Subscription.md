# Subscription

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**PlatformSubscriptionId** | **string** |  | 
**PlatformPlanId** | **string** |  | 
**Status** | [**SubscriptionStatus**](SubscriptionStatus.md) |  | 
**Recurring** | **bool** |  | 
**TrialEndsAt** | Pointer to **time.Time** |  | [optional] 
**PausedFrom** | Pointer to **time.Time** |  | [optional] 
**EndsAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewSubscription

`func NewSubscription(name string, platformSubscriptionId string, platformPlanId string, status SubscriptionStatus, recurring bool, ) *Subscription`

NewSubscription instantiates a new Subscription object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionWithDefaults

`func NewSubscriptionWithDefaults() *Subscription`

NewSubscriptionWithDefaults instantiates a new Subscription object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *Subscription) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Subscription) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Subscription) SetName(v string)`

SetName sets Name field to given value.


### GetPlatformSubscriptionId

`func (o *Subscription) GetPlatformSubscriptionId() string`

GetPlatformSubscriptionId returns the PlatformSubscriptionId field if non-nil, zero value otherwise.

### GetPlatformSubscriptionIdOk

`func (o *Subscription) GetPlatformSubscriptionIdOk() (*string, bool)`

GetPlatformSubscriptionIdOk returns a tuple with the PlatformSubscriptionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatformSubscriptionId

`func (o *Subscription) SetPlatformSubscriptionId(v string)`

SetPlatformSubscriptionId sets PlatformSubscriptionId field to given value.


### GetPlatformPlanId

`func (o *Subscription) GetPlatformPlanId() string`

GetPlatformPlanId returns the PlatformPlanId field if non-nil, zero value otherwise.

### GetPlatformPlanIdOk

`func (o *Subscription) GetPlatformPlanIdOk() (*string, bool)`

GetPlatformPlanIdOk returns a tuple with the PlatformPlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatformPlanId

`func (o *Subscription) SetPlatformPlanId(v string)`

SetPlatformPlanId sets PlatformPlanId field to given value.


### GetStatus

`func (o *Subscription) GetStatus() SubscriptionStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Subscription) GetStatusOk() (*SubscriptionStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Subscription) SetStatus(v SubscriptionStatus)`

SetStatus sets Status field to given value.


### GetRecurring

`func (o *Subscription) GetRecurring() bool`

GetRecurring returns the Recurring field if non-nil, zero value otherwise.

### GetRecurringOk

`func (o *Subscription) GetRecurringOk() (*bool, bool)`

GetRecurringOk returns a tuple with the Recurring field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecurring

`func (o *Subscription) SetRecurring(v bool)`

SetRecurring sets Recurring field to given value.


### GetTrialEndsAt

`func (o *Subscription) GetTrialEndsAt() time.Time`

GetTrialEndsAt returns the TrialEndsAt field if non-nil, zero value otherwise.

### GetTrialEndsAtOk

`func (o *Subscription) GetTrialEndsAtOk() (*time.Time, bool)`

GetTrialEndsAtOk returns a tuple with the TrialEndsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialEndsAt

`func (o *Subscription) SetTrialEndsAt(v time.Time)`

SetTrialEndsAt sets TrialEndsAt field to given value.

### HasTrialEndsAt

`func (o *Subscription) HasTrialEndsAt() bool`

HasTrialEndsAt returns a boolean if a field has been set.

### GetPausedFrom

`func (o *Subscription) GetPausedFrom() time.Time`

GetPausedFrom returns the PausedFrom field if non-nil, zero value otherwise.

### GetPausedFromOk

`func (o *Subscription) GetPausedFromOk() (*time.Time, bool)`

GetPausedFromOk returns a tuple with the PausedFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedFrom

`func (o *Subscription) SetPausedFrom(v time.Time)`

SetPausedFrom sets PausedFrom field to given value.

### HasPausedFrom

`func (o *Subscription) HasPausedFrom() bool`

HasPausedFrom returns a boolean if a field has been set.

### GetEndsAt

`func (o *Subscription) GetEndsAt() time.Time`

GetEndsAt returns the EndsAt field if non-nil, zero value otherwise.

### GetEndsAtOk

`func (o *Subscription) GetEndsAtOk() (*time.Time, bool)`

GetEndsAtOk returns a tuple with the EndsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndsAt

`func (o *Subscription) SetEndsAt(v time.Time)`

SetEndsAt sets EndsAt field to given value.

### HasEndsAt

`func (o *Subscription) HasEndsAt() bool`

HasEndsAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


