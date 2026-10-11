# CancelSubscription422Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** |  | [optional] 
**Errors** | Pointer to [**CancelSubscription422ResponseErrors**](CancelSubscription422ResponseErrors.md) |  | [optional] 

## Methods

### NewCancelSubscription422Response

`func NewCancelSubscription422Response() *CancelSubscription422Response`

NewCancelSubscription422Response instantiates a new CancelSubscription422Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCancelSubscription422ResponseWithDefaults

`func NewCancelSubscription422ResponseWithDefaults() *CancelSubscription422Response`

NewCancelSubscription422ResponseWithDefaults instantiates a new CancelSubscription422Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *CancelSubscription422Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *CancelSubscription422Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *CancelSubscription422Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *CancelSubscription422Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *CancelSubscription422Response) GetErrors() CancelSubscription422ResponseErrors`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *CancelSubscription422Response) GetErrorsOk() (*CancelSubscription422ResponseErrors, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *CancelSubscription422Response) SetErrors(v CancelSubscription422ResponseErrors)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *CancelSubscription422Response) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


