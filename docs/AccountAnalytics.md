# AccountAnalytics

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Account** | [**Account**](Account.md) |  | 
**Type** | **string** | The analytics tab returned. | 
**Tabs** | **[]string** | Tabs this account supports; any of them can be passed as &#x60;type&#x60;. | 
**Period** | [**AnalyticsPeriod**](AnalyticsPeriod.md) |  | 
**InitialSync** | [**AccountAnalyticsInitialSync**](AccountAnalyticsInitialSync.md) |  | 
**Data** | **map[string]interface{}** | Provider- and tab-specific metrics. Chart series are lists of &#x60;{date, value}&#x60; points. | 

## Methods

### NewAccountAnalytics

`func NewAccountAnalytics(account Account, type_ string, tabs []string, period AnalyticsPeriod, initialSync AccountAnalyticsInitialSync, data map[string]interface{}, ) *AccountAnalytics`

NewAccountAnalytics instantiates a new AccountAnalytics object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountAnalyticsWithDefaults

`func NewAccountAnalyticsWithDefaults() *AccountAnalytics`

NewAccountAnalyticsWithDefaults instantiates a new AccountAnalytics object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccount

`func (o *AccountAnalytics) GetAccount() Account`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *AccountAnalytics) GetAccountOk() (*Account, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *AccountAnalytics) SetAccount(v Account)`

SetAccount sets Account field to given value.


### GetType

`func (o *AccountAnalytics) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *AccountAnalytics) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *AccountAnalytics) SetType(v string)`

SetType sets Type field to given value.


### GetTabs

`func (o *AccountAnalytics) GetTabs() []string`

GetTabs returns the Tabs field if non-nil, zero value otherwise.

### GetTabsOk

`func (o *AccountAnalytics) GetTabsOk() (*[]string, bool)`

GetTabsOk returns a tuple with the Tabs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTabs

`func (o *AccountAnalytics) SetTabs(v []string)`

SetTabs sets Tabs field to given value.


### GetPeriod

`func (o *AccountAnalytics) GetPeriod() AnalyticsPeriod`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *AccountAnalytics) GetPeriodOk() (*AnalyticsPeriod, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *AccountAnalytics) SetPeriod(v AnalyticsPeriod)`

SetPeriod sets Period field to given value.


### GetInitialSync

`func (o *AccountAnalytics) GetInitialSync() AccountAnalyticsInitialSync`

GetInitialSync returns the InitialSync field if non-nil, zero value otherwise.

### GetInitialSyncOk

`func (o *AccountAnalytics) GetInitialSyncOk() (*AccountAnalyticsInitialSync, bool)`

GetInitialSyncOk returns a tuple with the InitialSync field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInitialSync

`func (o *AccountAnalytics) SetInitialSync(v AccountAnalyticsInitialSync)`

SetInitialSync sets InitialSync field to given value.


### GetData

`func (o *AccountAnalytics) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AccountAnalytics) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AccountAnalytics) SetData(v map[string]interface{})`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


