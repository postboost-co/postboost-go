# FreeToolError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | **string** |  | 
**RetryAfter** | Pointer to **int32** | 429 only: seconds until the limit resets. | [optional] 
**RegisterUrl** | Pointer to **string** | 429 for guests: sign up for a token with higher limits. | [optional] 
**UpgradeUrl** | Pointer to **string** | 429 when a token user reached the plan&#39;s daily cap. | [optional] 

## Methods

### NewFreeToolError

`func NewFreeToolError(message string, ) *FreeToolError`

NewFreeToolError instantiates a new FreeToolError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolErrorWithDefaults

`func NewFreeToolErrorWithDefaults() *FreeToolError`

NewFreeToolErrorWithDefaults instantiates a new FreeToolError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *FreeToolError) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *FreeToolError) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *FreeToolError) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetRetryAfter

`func (o *FreeToolError) GetRetryAfter() int32`

GetRetryAfter returns the RetryAfter field if non-nil, zero value otherwise.

### GetRetryAfterOk

`func (o *FreeToolError) GetRetryAfterOk() (*int32, bool)`

GetRetryAfterOk returns a tuple with the RetryAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryAfter

`func (o *FreeToolError) SetRetryAfter(v int32)`

SetRetryAfter sets RetryAfter field to given value.

### HasRetryAfter

`func (o *FreeToolError) HasRetryAfter() bool`

HasRetryAfter returns a boolean if a field has been set.

### GetRegisterUrl

`func (o *FreeToolError) GetRegisterUrl() string`

GetRegisterUrl returns the RegisterUrl field if non-nil, zero value otherwise.

### GetRegisterUrlOk

`func (o *FreeToolError) GetRegisterUrlOk() (*string, bool)`

GetRegisterUrlOk returns a tuple with the RegisterUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegisterUrl

`func (o *FreeToolError) SetRegisterUrl(v string)`

SetRegisterUrl sets RegisterUrl field to given value.

### HasRegisterUrl

`func (o *FreeToolError) HasRegisterUrl() bool`

HasRegisterUrl returns a boolean if a field has been set.

### GetUpgradeUrl

`func (o *FreeToolError) GetUpgradeUrl() string`

GetUpgradeUrl returns the UpgradeUrl field if non-nil, zero value otherwise.

### GetUpgradeUrlOk

`func (o *FreeToolError) GetUpgradeUrlOk() (*string, bool)`

GetUpgradeUrlOk returns a tuple with the UpgradeUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpgradeUrl

`func (o *FreeToolError) SetUpgradeUrl(v string)`

SetUpgradeUrl sets UpgradeUrl field to given value.

### HasUpgradeUrl

`func (o *FreeToolError) HasUpgradeUrl() bool`

HasUpgradeUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


