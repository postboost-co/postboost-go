# SubscriptionUpdateInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PlatformPlanId** | **string** |  | 
**Status** | [**SubscriptionStatus**](SubscriptionStatus.md) |  | 
**TrialEndsAt** | Pointer to **time.Time** | Required when status is &#x60;trialing&#x60;. | [optional] 
**PausedFrom** | Pointer to **time.Time** | Required when status is &#x60;paused&#x60;. | [optional] 

## Methods

### NewSubscriptionUpdateInput

`func NewSubscriptionUpdateInput(platformPlanId string, status SubscriptionStatus, ) *SubscriptionUpdateInput`

NewSubscriptionUpdateInput instantiates a new SubscriptionUpdateInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionUpdateInputWithDefaults

`func NewSubscriptionUpdateInputWithDefaults() *SubscriptionUpdateInput`

NewSubscriptionUpdateInputWithDefaults instantiates a new SubscriptionUpdateInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlatformPlanId

`func (o *SubscriptionUpdateInput) GetPlatformPlanId() string`

GetPlatformPlanId returns the PlatformPlanId field if non-nil, zero value otherwise.

### GetPlatformPlanIdOk

`func (o *SubscriptionUpdateInput) GetPlatformPlanIdOk() (*string, bool)`

GetPlatformPlanIdOk returns a tuple with the PlatformPlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatformPlanId

`func (o *SubscriptionUpdateInput) SetPlatformPlanId(v string)`

SetPlatformPlanId sets PlatformPlanId field to given value.


### GetStatus

`func (o *SubscriptionUpdateInput) GetStatus() SubscriptionStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SubscriptionUpdateInput) GetStatusOk() (*SubscriptionStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SubscriptionUpdateInput) SetStatus(v SubscriptionStatus)`

SetStatus sets Status field to given value.


### GetTrialEndsAt

`func (o *SubscriptionUpdateInput) GetTrialEndsAt() time.Time`

GetTrialEndsAt returns the TrialEndsAt field if non-nil, zero value otherwise.

### GetTrialEndsAtOk

`func (o *SubscriptionUpdateInput) GetTrialEndsAtOk() (*time.Time, bool)`

GetTrialEndsAtOk returns a tuple with the TrialEndsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialEndsAt

`func (o *SubscriptionUpdateInput) SetTrialEndsAt(v time.Time)`

SetTrialEndsAt sets TrialEndsAt field to given value.

### HasTrialEndsAt

`func (o *SubscriptionUpdateInput) HasTrialEndsAt() bool`

HasTrialEndsAt returns a boolean if a field has been set.

### GetPausedFrom

`func (o *SubscriptionUpdateInput) GetPausedFrom() time.Time`

GetPausedFrom returns the PausedFrom field if non-nil, zero value otherwise.

### GetPausedFromOk

`func (o *SubscriptionUpdateInput) GetPausedFromOk() (*time.Time, bool)`

GetPausedFromOk returns a tuple with the PausedFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPausedFrom

`func (o *SubscriptionUpdateInput) SetPausedFrom(v time.Time)`

SetPausedFrom sets PausedFrom field to given value.

### HasPausedFrom

`func (o *SubscriptionUpdateInput) HasPausedFrom() bool`

HasPausedFrom returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


