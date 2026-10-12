# GuardrailError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | **string** |  | 
**Code** | Pointer to **string** |  | [optional] 
**AccountId** | Pointer to **int32** | The account the problem is about. | [optional] 
**ExistingPostUuid** | Pointer to **string** | &#x60;duplicate_post&#x60; only: the earlier post with the same content. | [optional] 
**Limit** | Pointer to **int32** | &#x60;account_daily_cap_reached&#x60; only: the account&#39;s daily cap. | [optional] 
**Used** | Pointer to **int32** | &#x60;account_daily_cap_reached&#x60; only: posts already counted on that UTC day. | [optional] 

## Methods

### NewGuardrailError

`func NewGuardrailError(message string, ) *GuardrailError`

NewGuardrailError instantiates a new GuardrailError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGuardrailErrorWithDefaults

`func NewGuardrailErrorWithDefaults() *GuardrailError`

NewGuardrailErrorWithDefaults instantiates a new GuardrailError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *GuardrailError) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *GuardrailError) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *GuardrailError) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetCode

`func (o *GuardrailError) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *GuardrailError) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *GuardrailError) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *GuardrailError) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetAccountId

`func (o *GuardrailError) GetAccountId() int32`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *GuardrailError) GetAccountIdOk() (*int32, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *GuardrailError) SetAccountId(v int32)`

SetAccountId sets AccountId field to given value.

### HasAccountId

`func (o *GuardrailError) HasAccountId() bool`

HasAccountId returns a boolean if a field has been set.

### GetExistingPostUuid

`func (o *GuardrailError) GetExistingPostUuid() string`

GetExistingPostUuid returns the ExistingPostUuid field if non-nil, zero value otherwise.

### GetExistingPostUuidOk

`func (o *GuardrailError) GetExistingPostUuidOk() (*string, bool)`

GetExistingPostUuidOk returns a tuple with the ExistingPostUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExistingPostUuid

`func (o *GuardrailError) SetExistingPostUuid(v string)`

SetExistingPostUuid sets ExistingPostUuid field to given value.

### HasExistingPostUuid

`func (o *GuardrailError) HasExistingPostUuid() bool`

HasExistingPostUuid returns a boolean if a field has been set.

### GetLimit

`func (o *GuardrailError) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *GuardrailError) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *GuardrailError) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *GuardrailError) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetUsed

`func (o *GuardrailError) GetUsed() int32`

GetUsed returns the Used field if non-nil, zero value otherwise.

### GetUsedOk

`func (o *GuardrailError) GetUsedOk() (*int32, bool)`

GetUsedOk returns a tuple with the Used field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsed

`func (o *GuardrailError) SetUsed(v int32)`

SetUsed sets Used field to given value.

### HasUsed

`func (o *GuardrailError) HasUsed() bool`

HasUsed returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


