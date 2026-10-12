# ApiKeyInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Abilities** | [**[]ApiKeyAbility**](ApiKeyAbility.md) |  | 
**AccountIds** | Pointer to **[]int32** | Limit the key to these account ids of the workspace. Omit or null for every account. A limited key must send &#x60;account_ids&#x60; on recycling rules, report exports and AI drafts, and its lists show only its accounts. | [optional] 
**ExpiresAt** | Pointer to **NullableString** | Last day the key works. Must be after today. Omit for no expiry. | [optional] 

## Methods

### NewApiKeyInput

`func NewApiKeyInput(name string, abilities []ApiKeyAbility, ) *ApiKeyInput`

NewApiKeyInput instantiates a new ApiKeyInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiKeyInputWithDefaults

`func NewApiKeyInputWithDefaults() *ApiKeyInput`

NewApiKeyInputWithDefaults instantiates a new ApiKeyInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ApiKeyInput) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ApiKeyInput) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ApiKeyInput) SetName(v string)`

SetName sets Name field to given value.


### GetAbilities

`func (o *ApiKeyInput) GetAbilities() []ApiKeyAbility`

GetAbilities returns the Abilities field if non-nil, zero value otherwise.

### GetAbilitiesOk

`func (o *ApiKeyInput) GetAbilitiesOk() (*[]ApiKeyAbility, bool)`

GetAbilitiesOk returns a tuple with the Abilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbilities

`func (o *ApiKeyInput) SetAbilities(v []ApiKeyAbility)`

SetAbilities sets Abilities field to given value.


### GetAccountIds

`func (o *ApiKeyInput) GetAccountIds() []int32`

GetAccountIds returns the AccountIds field if non-nil, zero value otherwise.

### GetAccountIdsOk

`func (o *ApiKeyInput) GetAccountIdsOk() (*[]int32, bool)`

GetAccountIdsOk returns a tuple with the AccountIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountIds

`func (o *ApiKeyInput) SetAccountIds(v []int32)`

SetAccountIds sets AccountIds field to given value.

### HasAccountIds

`func (o *ApiKeyInput) HasAccountIds() bool`

HasAccountIds returns a boolean if a field has been set.

### SetAccountIdsNil

`func (o *ApiKeyInput) SetAccountIdsNil(b bool)`

 SetAccountIdsNil sets the value for AccountIds to be an explicit nil

### UnsetAccountIds
`func (o *ApiKeyInput) UnsetAccountIds()`

UnsetAccountIds ensures that no value is present for AccountIds, not even an explicit nil
### GetExpiresAt

`func (o *ApiKeyInput) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *ApiKeyInput) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *ApiKeyInput) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *ApiKeyInput) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### SetExpiresAtNil

`func (o *ApiKeyInput) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *ApiKeyInput) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


