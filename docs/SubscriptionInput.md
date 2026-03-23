# SubscriptionInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PlatformSubscriptionId** | **string** |  | 
**PlatformPlanId** | **string** |  | 
**Status** | [**SubscriptionStatus**](SubscriptionStatus.md) |  | 
**TrialEndsAt** | Pointer to **time.Time** | Required when status is &#x60;trialing&#x60;. | [optional] 

## Methods

### NewSubscriptionInput

`func NewSubscriptionInput(platformSubscriptionId string, platformPlanId string, status SubscriptionStatus, ) *SubscriptionInput`

NewSubscriptionInput instantiates a new SubscriptionInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubscriptionInputWithDefaults

`func NewSubscriptionInputWithDefaults() *SubscriptionInput`

NewSubscriptionInputWithDefaults instantiates a new SubscriptionInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlatformSubscriptionId

`func (o *SubscriptionInput) GetPlatformSubscriptionId() string`

GetPlatformSubscriptionId returns the PlatformSubscriptionId field if non-nil, zero value otherwise.

### GetPlatformSubscriptionIdOk

`func (o *SubscriptionInput) GetPlatformSubscriptionIdOk() (*string, bool)`

GetPlatformSubscriptionIdOk returns a tuple with the PlatformSubscriptionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatformSubscriptionId

`func (o *SubscriptionInput) SetPlatformSubscriptionId(v string)`

SetPlatformSubscriptionId sets PlatformSubscriptionId field to given value.


### GetPlatformPlanId

`func (o *SubscriptionInput) GetPlatformPlanId() string`

GetPlatformPlanId returns the PlatformPlanId field if non-nil, zero value otherwise.

### GetPlatformPlanIdOk

`func (o *SubscriptionInput) GetPlatformPlanIdOk() (*string, bool)`

GetPlatformPlanIdOk returns a tuple with the PlatformPlanId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatformPlanId

`func (o *SubscriptionInput) SetPlatformPlanId(v string)`

SetPlatformPlanId sets PlatformPlanId field to given value.


### GetStatus

`func (o *SubscriptionInput) GetStatus() SubscriptionStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SubscriptionInput) GetStatusOk() (*SubscriptionStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SubscriptionInput) SetStatus(v SubscriptionStatus)`

SetStatus sets Status field to given value.


### GetTrialEndsAt

`func (o *SubscriptionInput) GetTrialEndsAt() time.Time`

GetTrialEndsAt returns the TrialEndsAt field if non-nil, zero value otherwise.

### GetTrialEndsAtOk

`func (o *SubscriptionInput) GetTrialEndsAtOk() (*time.Time, bool)`

GetTrialEndsAtOk returns a tuple with the TrialEndsAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrialEndsAt

`func (o *SubscriptionInput) SetTrialEndsAt(v time.Time)`

SetTrialEndsAt sets TrialEndsAt field to given value.

### HasTrialEndsAt

`func (o *SubscriptionInput) HasTrialEndsAt() bool`

HasTrialEndsAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


