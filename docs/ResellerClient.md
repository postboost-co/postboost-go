# ResellerClient

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** | The client workspace UUID; use it as &#x60;workspaceUuid&#x60; for the client&#39;s own endpoints. | 
**Name** | **string** |  | 
**Status** | **string** |  | 
**Accounts** | **int32** |  | 
**AccountsNeedingReconnect** | **int32** |  | 
**Members** | **int32** |  | 
**CreatedAt** | **NullableTime** |  | 
**ArchivedAt** | **NullableTime** |  | 

## Methods

### NewResellerClient

`func NewResellerClient(uuid string, name string, status string, accounts int32, accountsNeedingReconnect int32, members int32, createdAt NullableTime, archivedAt NullableTime, ) *ResellerClient`

NewResellerClient instantiates a new ResellerClient object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResellerClientWithDefaults

`func NewResellerClientWithDefaults() *ResellerClient`

NewResellerClientWithDefaults instantiates a new ResellerClient object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *ResellerClient) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *ResellerClient) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *ResellerClient) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *ResellerClient) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ResellerClient) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ResellerClient) SetName(v string)`

SetName sets Name field to given value.


### GetStatus

`func (o *ResellerClient) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ResellerClient) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ResellerClient) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetAccounts

`func (o *ResellerClient) GetAccounts() int32`

GetAccounts returns the Accounts field if non-nil, zero value otherwise.

### GetAccountsOk

`func (o *ResellerClient) GetAccountsOk() (*int32, bool)`

GetAccountsOk returns a tuple with the Accounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccounts

`func (o *ResellerClient) SetAccounts(v int32)`

SetAccounts sets Accounts field to given value.


### GetAccountsNeedingReconnect

`func (o *ResellerClient) GetAccountsNeedingReconnect() int32`

GetAccountsNeedingReconnect returns the AccountsNeedingReconnect field if non-nil, zero value otherwise.

### GetAccountsNeedingReconnectOk

`func (o *ResellerClient) GetAccountsNeedingReconnectOk() (*int32, bool)`

GetAccountsNeedingReconnectOk returns a tuple with the AccountsNeedingReconnect field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountsNeedingReconnect

`func (o *ResellerClient) SetAccountsNeedingReconnect(v int32)`

SetAccountsNeedingReconnect sets AccountsNeedingReconnect field to given value.


### GetMembers

`func (o *ResellerClient) GetMembers() int32`

GetMembers returns the Members field if non-nil, zero value otherwise.

### GetMembersOk

`func (o *ResellerClient) GetMembersOk() (*int32, bool)`

GetMembersOk returns a tuple with the Members field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMembers

`func (o *ResellerClient) SetMembers(v int32)`

SetMembers sets Members field to given value.


### GetCreatedAt

`func (o *ResellerClient) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ResellerClient) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ResellerClient) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### SetCreatedAtNil

`func (o *ResellerClient) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *ResellerClient) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetArchivedAt

`func (o *ResellerClient) GetArchivedAt() time.Time`

GetArchivedAt returns the ArchivedAt field if non-nil, zero value otherwise.

### GetArchivedAtOk

`func (o *ResellerClient) GetArchivedAtOk() (*time.Time, bool)`

GetArchivedAtOk returns a tuple with the ArchivedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedAt

`func (o *ResellerClient) SetArchivedAt(v time.Time)`

SetArchivedAt sets ArchivedAt field to given value.


### SetArchivedAtNil

`func (o *ResellerClient) SetArchivedAtNil(b bool)`

 SetArchivedAtNil sets the value for ArchivedAt to be an explicit nil

### UnsetArchivedAt
`func (o *ResellerClient) UnsetArchivedAt()`

UnsetArchivedAt ensures that no value is present for ArchivedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


