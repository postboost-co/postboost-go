# ReportExportInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Format** | **string** |  | 
**Dataset** | Pointer to **NullableString** | CSV rows; default &#x60;posts&#x60;. Ignored for PDF. | [optional] 
**Period** | Pointer to **NullableString** | Default &#x60;last_month&#x60;. Ignored when &#x60;date_from&#x60; and &#x60;date_to&#x60; are sent. | [optional] 
**DateFrom** | Pointer to **NullableString** |  | [optional] 
**DateTo** | Pointer to **NullableString** | At most 366 days after &#x60;date_from&#x60;. | [optional] 
**AccountIds** | Pointer to **[]int32** | Limit the report to these accounts; default all. | [optional] 

## Methods

### NewReportExportInput

`func NewReportExportInput(format string, ) *ReportExportInput`

NewReportExportInput instantiates a new ReportExportInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReportExportInputWithDefaults

`func NewReportExportInputWithDefaults() *ReportExportInput`

NewReportExportInputWithDefaults instantiates a new ReportExportInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFormat

`func (o *ReportExportInput) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *ReportExportInput) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *ReportExportInput) SetFormat(v string)`

SetFormat sets Format field to given value.


### GetDataset

`func (o *ReportExportInput) GetDataset() string`

GetDataset returns the Dataset field if non-nil, zero value otherwise.

### GetDatasetOk

`func (o *ReportExportInput) GetDatasetOk() (*string, bool)`

GetDatasetOk returns a tuple with the Dataset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataset

`func (o *ReportExportInput) SetDataset(v string)`

SetDataset sets Dataset field to given value.

### HasDataset

`func (o *ReportExportInput) HasDataset() bool`

HasDataset returns a boolean if a field has been set.

### SetDatasetNil

`func (o *ReportExportInput) SetDatasetNil(b bool)`

 SetDatasetNil sets the value for Dataset to be an explicit nil

### UnsetDataset
`func (o *ReportExportInput) UnsetDataset()`

UnsetDataset ensures that no value is present for Dataset, not even an explicit nil
### GetPeriod

`func (o *ReportExportInput) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *ReportExportInput) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *ReportExportInput) SetPeriod(v string)`

SetPeriod sets Period field to given value.

### HasPeriod

`func (o *ReportExportInput) HasPeriod() bool`

HasPeriod returns a boolean if a field has been set.

### SetPeriodNil

`func (o *ReportExportInput) SetPeriodNil(b bool)`

 SetPeriodNil sets the value for Period to be an explicit nil

### UnsetPeriod
`func (o *ReportExportInput) UnsetPeriod()`

UnsetPeriod ensures that no value is present for Period, not even an explicit nil
### GetDateFrom

`func (o *ReportExportInput) GetDateFrom() string`

GetDateFrom returns the DateFrom field if non-nil, zero value otherwise.

### GetDateFromOk

`func (o *ReportExportInput) GetDateFromOk() (*string, bool)`

GetDateFromOk returns a tuple with the DateFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateFrom

`func (o *ReportExportInput) SetDateFrom(v string)`

SetDateFrom sets DateFrom field to given value.

### HasDateFrom

`func (o *ReportExportInput) HasDateFrom() bool`

HasDateFrom returns a boolean if a field has been set.

### SetDateFromNil

`func (o *ReportExportInput) SetDateFromNil(b bool)`

 SetDateFromNil sets the value for DateFrom to be an explicit nil

### UnsetDateFrom
`func (o *ReportExportInput) UnsetDateFrom()`

UnsetDateFrom ensures that no value is present for DateFrom, not even an explicit nil
### GetDateTo

`func (o *ReportExportInput) GetDateTo() string`

GetDateTo returns the DateTo field if non-nil, zero value otherwise.

### GetDateToOk

`func (o *ReportExportInput) GetDateToOk() (*string, bool)`

GetDateToOk returns a tuple with the DateTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateTo

`func (o *ReportExportInput) SetDateTo(v string)`

SetDateTo sets DateTo field to given value.

### HasDateTo

`func (o *ReportExportInput) HasDateTo() bool`

HasDateTo returns a boolean if a field has been set.

### SetDateToNil

`func (o *ReportExportInput) SetDateToNil(b bool)`

 SetDateToNil sets the value for DateTo to be an explicit nil

### UnsetDateTo
`func (o *ReportExportInput) UnsetDateTo()`

UnsetDateTo ensures that no value is present for DateTo, not even an explicit nil
### GetAccountIds

`func (o *ReportExportInput) GetAccountIds() []int32`

GetAccountIds returns the AccountIds field if non-nil, zero value otherwise.

### GetAccountIdsOk

`func (o *ReportExportInput) GetAccountIdsOk() (*[]int32, bool)`

GetAccountIdsOk returns a tuple with the AccountIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountIds

`func (o *ReportExportInput) SetAccountIds(v []int32)`

SetAccountIds sets AccountIds field to given value.

### HasAccountIds

`func (o *ReportExportInput) HasAccountIds() bool`

HasAccountIds returns a boolean if a field has been set.

### SetAccountIdsNil

`func (o *ReportExportInput) SetAccountIdsNil(b bool)`

 SetAccountIdsNil sets the value for AccountIds to be an explicit nil

### UnsetAccountIds
`func (o *ReportExportInput) UnsetAccountIds()`

UnsetAccountIds ensures that no value is present for AccountIds, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


