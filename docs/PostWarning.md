# PostWarning

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** | One of the codes above. The list grows over time (&#x60;x-extensible-enum&#x60;), so accept unknown values. | 
**AccountId** | **NullableInt32** | The account the warning is about; null when it is about the whole post. | 
**Message** | **string** |  | 

## Methods

### NewPostWarning

`func NewPostWarning(code string, accountId NullableInt32, message string, ) *PostWarning`

NewPostWarning instantiates a new PostWarning object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostWarningWithDefaults

`func NewPostWarningWithDefaults() *PostWarning`

NewPostWarningWithDefaults instantiates a new PostWarning object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *PostWarning) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *PostWarning) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *PostWarning) SetCode(v string)`

SetCode sets Code field to given value.


### GetAccountId

`func (o *PostWarning) GetAccountId() int32`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *PostWarning) GetAccountIdOk() (*int32, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *PostWarning) SetAccountId(v int32)`

SetAccountId sets AccountId field to given value.


### SetAccountIdNil

`func (o *PostWarning) SetAccountIdNil(b bool)`

 SetAccountIdNil sets the value for AccountId to be an explicit nil

### UnsetAccountId
`func (o *PostWarning) UnsetAccountId()`

UnsetAccountId ensures that no value is present for AccountId, not even an explicit nil
### GetMessage

`func (o *PostWarning) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *PostWarning) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *PostWarning) SetMessage(v string)`

SetMessage sets Message field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


