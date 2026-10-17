# PreflightResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Valid** | **bool** | True when create-post with the same body would succeed. Warnings do not change it. | 
**Errors** | **map[string][]string** | Validation and network-requirement errors keyed by field, as create-post would report them in a &#x60;422&#x60;. | 
**Issues** | [**[]GuardrailError**](GuardrailError.md) | Guardrail problems, in the order create-post would report the first of them. | 
**Warnings** | [**[]PostWarning**](PostWarning.md) | The warnings create-post would return for the same body (same codes and messages); empty when there are none. | 
**PublishAt** | **NullableTime** | UTC time the post would publish at; null for a draft. | 
**Accounts** | [**[]AccountHealth**](AccountHealth.md) |  | 

## Methods

### NewPreflightResult

`func NewPreflightResult(valid bool, errors map[string][]string, issues []GuardrailError, warnings []PostWarning, publishAt NullableTime, accounts []AccountHealth, ) *PreflightResult`

NewPreflightResult instantiates a new PreflightResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPreflightResultWithDefaults

`func NewPreflightResultWithDefaults() *PreflightResult`

NewPreflightResultWithDefaults instantiates a new PreflightResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValid

`func (o *PreflightResult) GetValid() bool`

GetValid returns the Valid field if non-nil, zero value otherwise.

### GetValidOk

`func (o *PreflightResult) GetValidOk() (*bool, bool)`

GetValidOk returns a tuple with the Valid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValid

`func (o *PreflightResult) SetValid(v bool)`

SetValid sets Valid field to given value.


### GetErrors

`func (o *PreflightResult) GetErrors() map[string][]string`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *PreflightResult) GetErrorsOk() (*map[string][]string, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *PreflightResult) SetErrors(v map[string][]string)`

SetErrors sets Errors field to given value.


### GetIssues

`func (o *PreflightResult) GetIssues() []GuardrailError`

GetIssues returns the Issues field if non-nil, zero value otherwise.

### GetIssuesOk

`func (o *PreflightResult) GetIssuesOk() (*[]GuardrailError, bool)`

GetIssuesOk returns a tuple with the Issues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssues

`func (o *PreflightResult) SetIssues(v []GuardrailError)`

SetIssues sets Issues field to given value.


### GetWarnings

`func (o *PreflightResult) GetWarnings() []PostWarning`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *PreflightResult) GetWarningsOk() (*[]PostWarning, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *PreflightResult) SetWarnings(v []PostWarning)`

SetWarnings sets Warnings field to given value.


### GetPublishAt

`func (o *PreflightResult) GetPublishAt() time.Time`

GetPublishAt returns the PublishAt field if non-nil, zero value otherwise.

### GetPublishAtOk

`func (o *PreflightResult) GetPublishAtOk() (*time.Time, bool)`

GetPublishAtOk returns a tuple with the PublishAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishAt

`func (o *PreflightResult) SetPublishAt(v time.Time)`

SetPublishAt sets PublishAt field to given value.


### SetPublishAtNil

`func (o *PreflightResult) SetPublishAtNil(b bool)`

 SetPublishAtNil sets the value for PublishAt to be an explicit nil

### UnsetPublishAt
`func (o *PreflightResult) UnsetPublishAt()`

UnsetPublishAt ensures that no value is present for PublishAt, not even an explicit nil
### GetAccounts

`func (o *PreflightResult) GetAccounts() []AccountHealth`

GetAccounts returns the Accounts field if non-nil, zero value otherwise.

### GetAccountsOk

`func (o *PreflightResult) GetAccountsOk() (*[]AccountHealth, bool)`

GetAccountsOk returns a tuple with the Accounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccounts

`func (o *PreflightResult) SetAccounts(v []AccountHealth)`

SetAccounts sets Accounts field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


