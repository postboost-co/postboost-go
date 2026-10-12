# AccountHealth

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Uuid** | **string** |  | 
**Name** | **string** |  | 
**Provider** | **string** |  | 
**Authorized** | **bool** | False when the account must be reconnected. | 
**HasToken** | **bool** | Whether an access token is stored for the account. | 
**Healthy** | **bool** | &#x60;authorized&#x60; and &#x60;has_token&#x60;: the account can publish. | 
**DailyCap** | [**AccountHealthDailyCap**](AccountHealthDailyCap.md) |  | 
**Connection** | [**AccountConnectionHealth**](AccountConnectionHealth.md) |  | 

## Methods

### NewAccountHealth

`func NewAccountHealth(id int32, uuid string, name string, provider string, authorized bool, hasToken bool, healthy bool, dailyCap AccountHealthDailyCap, connection AccountConnectionHealth, ) *AccountHealth`

NewAccountHealth instantiates a new AccountHealth object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountHealthWithDefaults

`func NewAccountHealthWithDefaults() *AccountHealth`

NewAccountHealthWithDefaults instantiates a new AccountHealth object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *AccountHealth) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *AccountHealth) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *AccountHealth) SetId(v int32)`

SetId sets Id field to given value.


### GetUuid

`func (o *AccountHealth) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *AccountHealth) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *AccountHealth) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *AccountHealth) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *AccountHealth) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *AccountHealth) SetName(v string)`

SetName sets Name field to given value.


### GetProvider

`func (o *AccountHealth) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *AccountHealth) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *AccountHealth) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetAuthorized

`func (o *AccountHealth) GetAuthorized() bool`

GetAuthorized returns the Authorized field if non-nil, zero value otherwise.

### GetAuthorizedOk

`func (o *AccountHealth) GetAuthorizedOk() (*bool, bool)`

GetAuthorizedOk returns a tuple with the Authorized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorized

`func (o *AccountHealth) SetAuthorized(v bool)`

SetAuthorized sets Authorized field to given value.


### GetHasToken

`func (o *AccountHealth) GetHasToken() bool`

GetHasToken returns the HasToken field if non-nil, zero value otherwise.

### GetHasTokenOk

`func (o *AccountHealth) GetHasTokenOk() (*bool, bool)`

GetHasTokenOk returns a tuple with the HasToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasToken

`func (o *AccountHealth) SetHasToken(v bool)`

SetHasToken sets HasToken field to given value.


### GetHealthy

`func (o *AccountHealth) GetHealthy() bool`

GetHealthy returns the Healthy field if non-nil, zero value otherwise.

### GetHealthyOk

`func (o *AccountHealth) GetHealthyOk() (*bool, bool)`

GetHealthyOk returns a tuple with the Healthy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHealthy

`func (o *AccountHealth) SetHealthy(v bool)`

SetHealthy sets Healthy field to given value.


### GetDailyCap

`func (o *AccountHealth) GetDailyCap() AccountHealthDailyCap`

GetDailyCap returns the DailyCap field if non-nil, zero value otherwise.

### GetDailyCapOk

`func (o *AccountHealth) GetDailyCapOk() (*AccountHealthDailyCap, bool)`

GetDailyCapOk returns a tuple with the DailyCap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDailyCap

`func (o *AccountHealth) SetDailyCap(v AccountHealthDailyCap)`

SetDailyCap sets DailyCap field to given value.


### GetConnection

`func (o *AccountHealth) GetConnection() AccountConnectionHealth`

GetConnection returns the Connection field if non-nil, zero value otherwise.

### GetConnectionOk

`func (o *AccountHealth) GetConnectionOk() (*AccountConnectionHealth, bool)`

GetConnectionOk returns a tuple with the Connection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConnection

`func (o *AccountHealth) SetConnection(v AccountConnectionHealth)`

SetConnection sets Connection field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


