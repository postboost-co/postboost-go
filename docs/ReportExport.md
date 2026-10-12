# ReportExport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**Format** | **string** |  | 
**Dataset** | **NullableString** |  | 
**Period** | **NullableString** |  | 
**DateFrom** | **string** |  | 
**DateTo** | **string** |  | 
**AccountIds** | **[]int32** |  | 
**Status** | **string** |  | 
**Error** | **NullableString** |  | 
**Bytes** | **NullableInt32** |  | 
**DownloadUrl** | **NullableString** | Authenticated download URL while the file is available. | 
**CreatedAt** | **NullableTime** |  | 
**ExpiresAt** | **NullableTime** |  | 

## Methods

### NewReportExport

`func NewReportExport(uuid string, format string, dataset NullableString, period NullableString, dateFrom string, dateTo string, accountIds []int32, status string, error_ NullableString, bytes NullableInt32, downloadUrl NullableString, createdAt NullableTime, expiresAt NullableTime, ) *ReportExport`

NewReportExport instantiates a new ReportExport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReportExportWithDefaults

`func NewReportExportWithDefaults() *ReportExport`

NewReportExportWithDefaults instantiates a new ReportExport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *ReportExport) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *ReportExport) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *ReportExport) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetFormat

`func (o *ReportExport) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *ReportExport) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *ReportExport) SetFormat(v string)`

SetFormat sets Format field to given value.


### GetDataset

`func (o *ReportExport) GetDataset() string`

GetDataset returns the Dataset field if non-nil, zero value otherwise.

### GetDatasetOk

`func (o *ReportExport) GetDatasetOk() (*string, bool)`

GetDatasetOk returns a tuple with the Dataset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataset

`func (o *ReportExport) SetDataset(v string)`

SetDataset sets Dataset field to given value.


### SetDatasetNil

`func (o *ReportExport) SetDatasetNil(b bool)`

 SetDatasetNil sets the value for Dataset to be an explicit nil

### UnsetDataset
`func (o *ReportExport) UnsetDataset()`

UnsetDataset ensures that no value is present for Dataset, not even an explicit nil
### GetPeriod

`func (o *ReportExport) GetPeriod() string`

GetPeriod returns the Period field if non-nil, zero value otherwise.

### GetPeriodOk

`func (o *ReportExport) GetPeriodOk() (*string, bool)`

GetPeriodOk returns a tuple with the Period field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriod

`func (o *ReportExport) SetPeriod(v string)`

SetPeriod sets Period field to given value.


### SetPeriodNil

`func (o *ReportExport) SetPeriodNil(b bool)`

 SetPeriodNil sets the value for Period to be an explicit nil

### UnsetPeriod
`func (o *ReportExport) UnsetPeriod()`

UnsetPeriod ensures that no value is present for Period, not even an explicit nil
### GetDateFrom

`func (o *ReportExport) GetDateFrom() string`

GetDateFrom returns the DateFrom field if non-nil, zero value otherwise.

### GetDateFromOk

`func (o *ReportExport) GetDateFromOk() (*string, bool)`

GetDateFromOk returns a tuple with the DateFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateFrom

`func (o *ReportExport) SetDateFrom(v string)`

SetDateFrom sets DateFrom field to given value.


### GetDateTo

`func (o *ReportExport) GetDateTo() string`

GetDateTo returns the DateTo field if non-nil, zero value otherwise.

### GetDateToOk

`func (o *ReportExport) GetDateToOk() (*string, bool)`

GetDateToOk returns a tuple with the DateTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateTo

`func (o *ReportExport) SetDateTo(v string)`

SetDateTo sets DateTo field to given value.


### GetAccountIds

`func (o *ReportExport) GetAccountIds() []int32`

GetAccountIds returns the AccountIds field if non-nil, zero value otherwise.

### GetAccountIdsOk

`func (o *ReportExport) GetAccountIdsOk() (*[]int32, bool)`

GetAccountIdsOk returns a tuple with the AccountIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountIds

`func (o *ReportExport) SetAccountIds(v []int32)`

SetAccountIds sets AccountIds field to given value.


### SetAccountIdsNil

`func (o *ReportExport) SetAccountIdsNil(b bool)`

 SetAccountIdsNil sets the value for AccountIds to be an explicit nil

### UnsetAccountIds
`func (o *ReportExport) UnsetAccountIds()`

UnsetAccountIds ensures that no value is present for AccountIds, not even an explicit nil
### GetStatus

`func (o *ReportExport) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ReportExport) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ReportExport) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetError

`func (o *ReportExport) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ReportExport) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ReportExport) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *ReportExport) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *ReportExport) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetBytes

`func (o *ReportExport) GetBytes() int32`

GetBytes returns the Bytes field if non-nil, zero value otherwise.

### GetBytesOk

`func (o *ReportExport) GetBytesOk() (*int32, bool)`

GetBytesOk returns a tuple with the Bytes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBytes

`func (o *ReportExport) SetBytes(v int32)`

SetBytes sets Bytes field to given value.


### SetBytesNil

`func (o *ReportExport) SetBytesNil(b bool)`

 SetBytesNil sets the value for Bytes to be an explicit nil

### UnsetBytes
`func (o *ReportExport) UnsetBytes()`

UnsetBytes ensures that no value is present for Bytes, not even an explicit nil
### GetDownloadUrl

`func (o *ReportExport) GetDownloadUrl() string`

GetDownloadUrl returns the DownloadUrl field if non-nil, zero value otherwise.

### GetDownloadUrlOk

`func (o *ReportExport) GetDownloadUrlOk() (*string, bool)`

GetDownloadUrlOk returns a tuple with the DownloadUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownloadUrl

`func (o *ReportExport) SetDownloadUrl(v string)`

SetDownloadUrl sets DownloadUrl field to given value.


### SetDownloadUrlNil

`func (o *ReportExport) SetDownloadUrlNil(b bool)`

 SetDownloadUrlNil sets the value for DownloadUrl to be an explicit nil

### UnsetDownloadUrl
`func (o *ReportExport) UnsetDownloadUrl()`

UnsetDownloadUrl ensures that no value is present for DownloadUrl, not even an explicit nil
### GetCreatedAt

`func (o *ReportExport) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ReportExport) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ReportExport) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### SetCreatedAtNil

`func (o *ReportExport) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *ReportExport) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil
### GetExpiresAt

`func (o *ReportExport) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *ReportExport) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *ReportExport) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### SetExpiresAtNil

`func (o *ReportExport) SetExpiresAtNil(b bool)`

 SetExpiresAtNil sets the value for ExpiresAt to be an explicit nil

### UnsetExpiresAt
`func (o *ReportExport) UnsetExpiresAt()`

UnsetExpiresAt ensures that no value is present for ExpiresAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


