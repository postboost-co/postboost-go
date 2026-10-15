# AccountConnectionHealth

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | **string** | &#x60;expired&#x60;: must be reconnected now. &#x60;expiring&#x60;: the connection hits its hard expiry within 7 days. &#x60;failing&#x60;: the latest publish attempt failed. &#x60;healthy&#x60;: none of these.  | 
**ExpiryKind** | **string** | What limits the connection: &#x60;access&#x60; (the access token), &#x60;refresh&#x60; (the refresh token), &#x60;expired&#x60;, &#x60;unknown&#x60; (refreshed automatically, no known hard limit) or &#x60;none&#x60; (the network&#39;s connections do not expire on a schedule).  | 
**ExpiresAt** | **NullableTime** | When the connection stops working unless reconnected; null without a hard expiry. | 
**DaysLeft** | **NullableInt32** | Whole days until &#x60;expires_at&#x60; (0 &#x3D; less than a day). | 
**Refreshable** | **bool** | PostBoost refreshes the token automatically until the hard expiry. | 
**Note** | **string** | Plain-language explanation of the prediction. | 
**ReconnectReason** | [**AccountConnectionHealthReconnectReason**](AccountConnectionHealthReconnectReason.md) |  | 
**LastSuccessAt** | **NullableTime** | When the account last published successfully. | 
**LastError** | **NullableString** | The error of the account&#39;s latest failed publish, shortened to 300 characters. | 
**ReconnectUrl** | **string** | Where a workspace member reconnects the account. | 

## Methods

### NewAccountConnectionHealth

`func NewAccountConnectionHealth(status string, expiryKind string, expiresAt NullableTime, daysLeft NullableInt32, refreshable bool, note string, reconnectReason AccountConnectionHealthReconnectReason, lastSuccessAt NullableTime, lastError NullableString, reconnectUrl string, ) *AccountConnectionHealth`

NewAccountConnectionHealth instantiates a new AccountConnectionHealth object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountConnectionHealthWithDefaults

`func NewAccountConnectionHealthWithDefaults() *AccountConnectionHealth`

NewAccountConnectionHealthWithDefaults instantiates a new AccountConnectionHealth object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *AccountConnectionHealth) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *AccountConnectionHealth) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *AccountConnectionHealth) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetExpiryKind

`func (o *AccountConnectionHealth) GetExpiryKind() string`

GetExpiryKind returns the ExpiryKind field if non-nil, zero value otherwise.

### GetExpiryKindOk

`func (o *AccountConnectionHealth) GetExpiryKindOk() (*string, bool)`

GetExpiryKindOk returns a tuple with the ExpiryKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiryKind

`func (o *AccountConnectionHealth) SetExpiryKind(v string)`

SetExpiryKind sets ExpiryKind field to given value.


### GetExpiresAt

`func (o *AccountConnectionHealth) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *AccountConnectionHealth) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *AccountConnectionHealth) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### SetExpiresAtNil

`func (o *AccountConnectionHealth) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *AccountConnectionHealth) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil
### GetDaysLeft

`func (o *AccountConnectionHealth) GetDaysLeft() int32`

GetDaysLeft returns the DaysLeft field if non-nil, zero value otherwise.

### GetDaysLeftOk

`func (o *AccountConnectionHealth) GetDaysLeftOk() (*int32, bool)`

GetDaysLeftOk returns a tuple with the DaysLeft field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDaysLeft

`func (o *AccountConnectionHealth) SetDaysLeft(v int32)`

SetDaysLeft sets DaysLeft field to given value.


### SetDaysLeftNil

`func (o *AccountConnectionHealth) SetDaysLeftNil(b bool)`

 SetDaysLeftNil sets the value for DaysLeft to be an explicit nil

### UnsetDaysLeft
`func (o *AccountConnectionHealth) UnsetDaysLeft()`

UnsetDaysLeft ensures that no value is present for DaysLeft, not even an explicit nil
### GetRefreshable

`func (o *AccountConnectionHealth) GetRefreshable() bool`

GetRefreshable returns the Refreshable field if non-nil, zero value otherwise.

### GetRefreshableOk

`func (o *AccountConnectionHealth) GetRefreshableOk() (*bool, bool)`

GetRefreshableOk returns a tuple with the Refreshable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefreshable

`func (o *AccountConnectionHealth) SetRefreshable(v bool)`

SetRefreshable sets Refreshable field to given value.


### GetNote

`func (o *AccountConnectionHealth) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *AccountConnectionHealth) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *AccountConnectionHealth) SetNote(v string)`

SetNote sets Note field to given value.


### GetReconnectReason

`func (o *AccountConnectionHealth) GetReconnectReason() AccountConnectionHealthReconnectReason`

GetReconnectReason returns the ReconnectReason field if non-nil, zero value otherwise.

### GetReconnectReasonOk

`func (o *AccountConnectionHealth) GetReconnectReasonOk() (*AccountConnectionHealthReconnectReason, bool)`

GetReconnectReasonOk returns a tuple with the ReconnectReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReconnectReason

`func (o *AccountConnectionHealth) SetReconnectReason(v AccountConnectionHealthReconnectReason)`

SetReconnectReason sets ReconnectReason field to given value.


### GetLastSuccessAt

`func (o *AccountConnectionHealth) GetLastSuccessAt() time.Time`

GetLastSuccessAt returns the LastSuccessAt field if non-nil, zero value otherwise.

### GetLastSuccessAtOk

`func (o *AccountConnectionHealth) GetLastSuccessAtOk() (*time.Time, bool)`

GetLastSuccessAtOk returns a tuple with the LastSuccessAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastSuccessAt

`func (o *AccountConnectionHealth) SetLastSuccessAt(v time.Time)`

SetLastSuccessAt sets LastSuccessAt field to given value.


### SetLastSuccessAtNil

`func (o *AccountConnectionHealth) SetLastSuccessAtNil(b bool)`

 SetLastSuccessAtNil sets the value for LastSuccessAt to be an explicit nil

### UnsetLastSuccessAt
`func (o *AccountConnectionHealth) UnsetLastSuccessAt()`

UnsetLastSuccessAt ensures that no value is present for LastSuccessAt, not even an explicit nil
### GetLastError

`func (o *AccountConnectionHealth) GetLastError() string`

GetLastError returns the LastError field if non-nil, zero value otherwise.

### GetLastErrorOk

`func (o *AccountConnectionHealth) GetLastErrorOk() (*string, bool)`

GetLastErrorOk returns a tuple with the LastError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastError

`func (o *AccountConnectionHealth) SetLastError(v string)`

SetLastError sets LastError field to given value.


### SetLastErrorNil

`func (o *AccountConnectionHealth) SetLastErrorNil(b bool)`

 SetLastErrorNil sets the value for LastError to be an explicit nil

### UnsetLastError
`func (o *AccountConnectionHealth) UnsetLastError()`

UnsetLastError ensures that no value is present for LastError, not even an explicit nil
### GetReconnectUrl

`func (o *AccountConnectionHealth) GetReconnectUrl() string`

GetReconnectUrl returns the ReconnectUrl field if non-nil, zero value otherwise.

### GetReconnectUrlOk

`func (o *AccountConnectionHealth) GetReconnectUrlOk() (*string, bool)`

GetReconnectUrlOk returns a tuple with the ReconnectUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReconnectUrl

`func (o *AccountConnectionHealth) SetReconnectUrl(v string)`

SetReconnectUrl sets ReconnectUrl field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


