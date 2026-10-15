# ConnectLink

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | Single-use link for the signed-in user who created it. Valid 15 minutes. | 
**ExpiresAt** | **time.Time** |  | 
**Provider** | **string** |  | 

## Methods

### NewConnectLink

`func NewConnectLink(url string, expiresAt time.Time, provider string, ) *ConnectLink`

NewConnectLink instantiates a new ConnectLink object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectLinkWithDefaults

`func NewConnectLinkWithDefaults() *ConnectLink`

NewConnectLinkWithDefaults instantiates a new ConnectLink object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *ConnectLink) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *ConnectLink) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *ConnectLink) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetExpiresAt

`func (o *ConnectLink) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *ConnectLink) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *ConnectLink) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetProvider

`func (o *ConnectLink) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *ConnectLink) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *ConnectLink) SetProvider(v string)`

SetProvider sets Provider field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


