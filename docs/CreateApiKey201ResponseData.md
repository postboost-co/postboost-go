# CreateApiKey201ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Name** | **string** |  | 
**Abilities** | [**[]ApiKeyAbility**](ApiKeyAbility.md) |  | 
**AccountIds** | Pointer to **[]int32** |  | [optional] 
**CreatedBy** | Pointer to **string** | Name of the user the key acts as. | [optional] 
**LastUsedAt** | Pointer to **time.Time** |  | [optional] 
**ExpiresAt** | Pointer to **string** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**Token** | **string** | The plain API key. Shown only in this response. | 

## Methods

### NewCreateApiKey201ResponseData

`func NewCreateApiKey201ResponseData(id int32, name string, abilities []ApiKeyAbility, token string, ) *CreateApiKey201ResponseData`

NewCreateApiKey201ResponseData instantiates a new CreateApiKey201ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateApiKey201ResponseDataWithDefaults

`func NewCreateApiKey201ResponseDataWithDefaults() *CreateApiKey201ResponseData`

NewCreateApiKey201ResponseDataWithDefaults instantiates a new CreateApiKey201ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateApiKey201ResponseData) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateApiKey201ResponseData) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateApiKey201ResponseData) SetId(v int32)`

SetId sets Id field to given value.


### GetName

`func (o *CreateApiKey201ResponseData) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateApiKey201ResponseData) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateApiKey201ResponseData) SetName(v string)`

SetName sets Name field to given value.


### GetAbilities

`func (o *CreateApiKey201ResponseData) GetAbilities() []ApiKeyAbility`

GetAbilities returns the Abilities field if non-nil, zero value otherwise.

### GetAbilitiesOk

`func (o *CreateApiKey201ResponseData) GetAbilitiesOk() (*[]ApiKeyAbility, bool)`

GetAbilitiesOk returns a tuple with the Abilities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbilities

`func (o *CreateApiKey201ResponseData) SetAbilities(v []ApiKeyAbility)`

SetAbilities sets Abilities field to given value.


### GetAccountIds

`func (o *CreateApiKey201ResponseData) GetAccountIds() []int32`

GetAccountIds returns the AccountIds field if non-nil, zero value otherwise.

### GetAccountIdsOk

`func (o *CreateApiKey201ResponseData) GetAccountIdsOk() (*[]int32, bool)`

GetAccountIdsOk returns a tuple with the AccountIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountIds

`func (o *CreateApiKey201ResponseData) SetAccountIds(v []int32)`

SetAccountIds sets AccountIds field to given value.

### HasAccountIds

`func (o *CreateApiKey201ResponseData) HasAccountIds() bool`

HasAccountIds returns a boolean if a field has been set.

### GetCreatedBy

`func (o *CreateApiKey201ResponseData) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *CreateApiKey201ResponseData) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *CreateApiKey201ResponseData) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *CreateApiKey201ResponseData) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### GetLastUsedAt

`func (o *CreateApiKey201ResponseData) GetLastUsedAt() time.Time`

GetLastUsedAt returns the LastUsedAt field if non-nil, zero value otherwise.

### GetLastUsedAtOk

`func (o *CreateApiKey201ResponseData) GetLastUsedAtOk() (*time.Time, bool)`

GetLastUsedAtOk returns a tuple with the LastUsedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUsedAt

`func (o *CreateApiKey201ResponseData) SetLastUsedAt(v time.Time)`

SetLastUsedAt sets LastUsedAt field to given value.

### HasLastUsedAt

`func (o *CreateApiKey201ResponseData) HasLastUsedAt() bool`

HasLastUsedAt returns a boolean if a field has been set.

### GetExpiresAt

`func (o *CreateApiKey201ResponseData) GetExpiresAt() string`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *CreateApiKey201ResponseData) GetExpiresAtOk() (*string, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *CreateApiKey201ResponseData) SetExpiresAt(v string)`

SetExpiresAt sets ExpiresAt field to given value.

### HasExpiresAt

`func (o *CreateApiKey201ResponseData) HasExpiresAt() bool`

HasExpiresAt returns a boolean if a field has been set.

### GetCreatedAt

`func (o *CreateApiKey201ResponseData) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateApiKey201ResponseData) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateApiKey201ResponseData) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CreateApiKey201ResponseData) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetToken

`func (o *CreateApiKey201ResponseData) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *CreateApiKey201ResponseData) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *CreateApiKey201ResponseData) SetToken(v string)`

SetToken sets Token field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


