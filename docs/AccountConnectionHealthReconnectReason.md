# AccountConnectionHealthReconnectReason

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** |  | 
**Message** | **string** | The reason in plain language. | 
**FoundAt** | **time.Time** | When the check first found the token dead. | 

## Methods

### NewAccountConnectionHealthReconnectReason

`func NewAccountConnectionHealthReconnectReason(code string, message string, foundAt time.Time, ) *AccountConnectionHealthReconnectReason`

NewAccountConnectionHealthReconnectReason instantiates a new AccountConnectionHealthReconnectReason object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountConnectionHealthReconnectReasonWithDefaults

`func NewAccountConnectionHealthReconnectReasonWithDefaults() *AccountConnectionHealthReconnectReason`

NewAccountConnectionHealthReconnectReasonWithDefaults instantiates a new AccountConnectionHealthReconnectReason object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *AccountConnectionHealthReconnectReason) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *AccountConnectionHealthReconnectReason) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *AccountConnectionHealthReconnectReason) SetCode(v string)`

SetCode sets Code field to given value.


### GetMessage

`func (o *AccountConnectionHealthReconnectReason) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *AccountConnectionHealthReconnectReason) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *AccountConnectionHealthReconnectReason) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetFoundAt

`func (o *AccountConnectionHealthReconnectReason) GetFoundAt() time.Time`

GetFoundAt returns the FoundAt field if non-nil, zero value otherwise.

### GetFoundAtOk

`func (o *AccountConnectionHealthReconnectReason) GetFoundAtOk() (*time.Time, bool)`

GetFoundAtOk returns a tuple with the FoundAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFoundAt

`func (o *AccountConnectionHealthReconnectReason) SetFoundAt(v time.Time)`

SetFoundAt sets FoundAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


