# CancelSubscriptionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Immediately** | Pointer to **bool** | Cancel now instead of at the end of the billing period. | [optional] [default to false]

## Methods

### NewCancelSubscriptionRequest

`func NewCancelSubscriptionRequest() *CancelSubscriptionRequest`

NewCancelSubscriptionRequest instantiates a new CancelSubscriptionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCancelSubscriptionRequestWithDefaults

`func NewCancelSubscriptionRequestWithDefaults() *CancelSubscriptionRequest`

NewCancelSubscriptionRequestWithDefaults instantiates a new CancelSubscriptionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImmediately

`func (o *CancelSubscriptionRequest) GetImmediately() bool`

GetImmediately returns the Immediately field if non-nil, zero value otherwise.

### GetImmediatelyOk

`func (o *CancelSubscriptionRequest) GetImmediatelyOk() (*bool, bool)`

GetImmediatelyOk returns a tuple with the Immediately field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImmediately

`func (o *CancelSubscriptionRequest) SetImmediately(v bool)`

SetImmediately sets Immediately field to given value.

### HasImmediately

`func (o *CancelSubscriptionRequest) HasImmediately() bool`

HasImmediately returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


