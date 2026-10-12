# RssFeed

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**Url** | **string** |  | 
**Name** | **NullableString** |  | 
**AccountIds** | **[]int32** |  | 
**Mode** | **string** |  | 
**Template** | **string** |  | 
**MaxItemsPerRun** | **int32** |  | 
**Active** | **bool** |  | 
**LastPolledAt** | **NullableTime** |  | 
**LastError** | **NullableString** | Error of the last check; after 5 failures in a row the feed is checked every 6 hours. | 
**CreatedAt** | **NullableTime** |  | 

## Methods

### NewRssFeed

`func NewRssFeed(uuid string, url string, name NullableString, accountIds []int32, mode string, template string, maxItemsPerRun int32, active bool, lastPolledAt NullableTime, lastError NullableString, createdAt NullableTime, ) *RssFeed`

NewRssFeed instantiates a new RssFeed object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRssFeedWithDefaults

`func NewRssFeedWithDefaults() *RssFeed`

NewRssFeedWithDefaults instantiates a new RssFeed object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *RssFeed) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *RssFeed) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *RssFeed) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetUrl

`func (o *RssFeed) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *RssFeed) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *RssFeed) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetName

`func (o *RssFeed) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RssFeed) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RssFeed) SetName(v string)`

SetName sets Name field to given value.


### SetNameNil

`func (o *RssFeed) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *RssFeed) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetAccountIds

`func (o *RssFeed) GetAccountIds() []int32`

GetAccountIds returns the AccountIds field if non-nil, zero value otherwise.

### GetAccountIdsOk

`func (o *RssFeed) GetAccountIdsOk() (*[]int32, bool)`

GetAccountIdsOk returns a tuple with the AccountIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountIds

`func (o *RssFeed) SetAccountIds(v []int32)`

SetAccountIds sets AccountIds field to given value.


### GetMode

`func (o *RssFeed) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *RssFeed) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *RssFeed) SetMode(v string)`

SetMode sets Mode field to given value.


### GetTemplate

`func (o *RssFeed) GetTemplate() string`

GetTemplate returns the Template field if non-nil, zero value otherwise.

### GetTemplateOk

`func (o *RssFeed) GetTemplateOk() (*string, bool)`

GetTemplateOk returns a tuple with the Template field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplate

`func (o *RssFeed) SetTemplate(v string)`

SetTemplate sets Template field to given value.


### GetMaxItemsPerRun

`func (o *RssFeed) GetMaxItemsPerRun() int32`

GetMaxItemsPerRun returns the MaxItemsPerRun field if non-nil, zero value otherwise.

### GetMaxItemsPerRunOk

`func (o *RssFeed) GetMaxItemsPerRunOk() (*int32, bool)`

GetMaxItemsPerRunOk returns a tuple with the MaxItemsPerRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxItemsPerRun

`func (o *RssFeed) SetMaxItemsPerRun(v int32)`

SetMaxItemsPerRun sets MaxItemsPerRun field to given value.


### GetActive

`func (o *RssFeed) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *RssFeed) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *RssFeed) SetActive(v bool)`

SetActive sets Active field to given value.


### GetLastPolledAt

`func (o *RssFeed) GetLastPolledAt() time.Time`

GetLastPolledAt returns the LastPolledAt field if non-nil, zero value otherwise.

### GetLastPolledAtOk

`func (o *RssFeed) GetLastPolledAtOk() (*time.Time, bool)`

GetLastPolledAtOk returns a tuple with the LastPolledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPolledAt

`func (o *RssFeed) SetLastPolledAt(v time.Time)`

SetLastPolledAt sets LastPolledAt field to given value.


### SetLastPolledAtNil

`func (o *RssFeed) SetLastPolledAtNil(b bool)`

 SetLastPolledAtNil sets the value for LastPolledAt to be an explicit nil

### UnsetLastPolledAt
`func (o *RssFeed) UnsetLastPolledAt()`

UnsetLastPolledAt ensures that no value is present for LastPolledAt, not even an explicit nil
### GetLastError

`func (o *RssFeed) GetLastError() string`

GetLastError returns the LastError field if non-nil, zero value otherwise.

### GetLastErrorOk

`func (o *RssFeed) GetLastErrorOk() (*string, bool)`

GetLastErrorOk returns a tuple with the LastError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastError

`func (o *RssFeed) SetLastError(v string)`

SetLastError sets LastError field to given value.


### SetLastErrorNil

`func (o *RssFeed) SetLastErrorNil(b bool)`

 SetLastErrorNil sets the value for LastError to be an explicit nil

### UnsetLastError
`func (o *RssFeed) UnsetLastError()`

UnsetLastError ensures that no value is present for LastError, not even an explicit nil
### GetCreatedAt

`func (o *RssFeed) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *RssFeed) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *RssFeed) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### SetCreatedAtNil

`func (o *RssFeed) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *RssFeed) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


