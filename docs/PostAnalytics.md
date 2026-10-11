# PostAnalytics

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Summary** | **map[string]interface{}** | Totals (views, likes, comments, shares), trends, engagement rate, breakdown, funnel and peak day across the post&#39;s accounts. Empty when nothing is published yet. | 
**Winner** | Pointer to **interface{}** |  | [optional] 
**Accounts** | **[]map[string]interface{}** |  | 

## Methods

### NewPostAnalytics

`func NewPostAnalytics(summary map[string]interface{}, accounts []map[string]interface{}, ) *PostAnalytics`

NewPostAnalytics instantiates a new PostAnalytics object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostAnalyticsWithDefaults

`func NewPostAnalyticsWithDefaults() *PostAnalytics`

NewPostAnalyticsWithDefaults instantiates a new PostAnalytics object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSummary

`func (o *PostAnalytics) GetSummary() map[string]interface{}`

GetSummary returns the Summary field if non-nil, zero value otherwise.

### GetSummaryOk

`func (o *PostAnalytics) GetSummaryOk() (*map[string]interface{}, bool)`

GetSummaryOk returns a tuple with the Summary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSummary

`func (o *PostAnalytics) SetSummary(v map[string]interface{})`

SetSummary sets Summary field to given value.


### GetWinner

`func (o *PostAnalytics) GetWinner() interface{}`

GetWinner returns the Winner field if non-nil, zero value otherwise.

### GetWinnerOk

`func (o *PostAnalytics) GetWinnerOk() (*interface{}, bool)`

GetWinnerOk returns a tuple with the Winner field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWinner

`func (o *PostAnalytics) SetWinner(v interface{})`

SetWinner sets Winner field to given value.

### HasWinner

`func (o *PostAnalytics) HasWinner() bool`

HasWinner returns a boolean if a field has been set.

### SetWinnerNil

`func (o *PostAnalytics) SetWinnerNil(b bool)`

 SetWinnerNil sets the value for Winner to be an explicit nil

### UnsetWinner
`func (o *PostAnalytics) UnsetWinner()`

UnsetWinner ensures that no value is present for Winner, not even an explicit nil
### GetAccounts

`func (o *PostAnalytics) GetAccounts() []map[string]interface{}`

GetAccounts returns the Accounts field if non-nil, zero value otherwise.

### GetAccountsOk

`func (o *PostAnalytics) GetAccountsOk() (*[]map[string]interface{}, bool)`

GetAccountsOk returns a tuple with the Accounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccounts

`func (o *PostAnalytics) SetAccounts(v []map[string]interface{})`

SetAccounts sets Accounts field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


