# ReconnectLink

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | Single-use link to forward to the account owner. | 
**ExpiresAt** | **time.Time** |  | 
**AccountUuid** | **string** |  | 

## Methods

### NewReconnectLink

`func NewReconnectLink(url string, expiresAt time.Time, accountUuid string, ) *ReconnectLink`

NewReconnectLink instantiates a new ReconnectLink object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReconnectLinkWithDefaults

`func NewReconnectLinkWithDefaults() *ReconnectLink`

NewReconnectLinkWithDefaults instantiates a new ReconnectLink object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *ReconnectLink) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ReconnectLink) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ReconnectLink) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetExpiresAt

`func (o *ReconnectLink) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *ReconnectLink) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *ReconnectLink) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetAccountUuid

`func (o *ReconnectLink) GetAccountUuid() string`

GetAccountUuid returns the AccountUuid field if non-nil, zero value otherwise.

### GetAccountUuidOk

`func (o *ReconnectLink) GetAccountUuidOk() (*string, bool)`

GetAccountUuidOk returns a tuple with the AccountUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountUuid

`func (o *ReconnectLink) SetAccountUuid(v string)`

SetAccountUuid sets AccountUuid field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


