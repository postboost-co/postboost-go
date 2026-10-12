# AccountGroupInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Accounts** | Pointer to **[]int32** | Account &#x60;id&#x60;s of this workspace. Replaces the group&#39;s accounts. | [optional] 

## Methods

### NewAccountGroupInput

`func NewAccountGroupInput(name string, ) *AccountGroupInput`

NewAccountGroupInput instantiates a new AccountGroupInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountGroupInputWithDefaults

`func NewAccountGroupInputWithDefaults() *AccountGroupInput`

NewAccountGroupInputWithDefaults instantiates a new AccountGroupInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *AccountGroupInput) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AccountGroupInput) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AccountGroupInput) SetName(v string)`

SetName sets Name field to given value.


### GetAccounts

`func (o *AccountGroupInput) GetAccounts() []int32`

GetAccounts returns the Accounts field if non-nil, zero value otherwise.

### GetAccountsOk

`func (o *AccountGroupInput) GetAccountsOk() (*[]int32, bool)`

GetAccountsOk returns a tuple with the Accounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccounts

`func (o *AccountGroupInput) SetAccounts(v []int32)`

SetAccounts sets Accounts field to given value.

### HasAccounts

`func (o *AccountGroupInput) HasAccounts() bool`

HasAccounts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


