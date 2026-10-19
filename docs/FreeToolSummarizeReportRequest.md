# FreeToolSummarizeReportRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Rows** | [**[]FreeToolSummarizeReportRequestRowsInner**](FreeToolSummarizeReportRequestRowsInner.md) | One object per post, already mapped to these fields. Leave out a count the export does not have. | 

## Methods

### NewFreeToolSummarizeReportRequest

`func NewFreeToolSummarizeReportRequest(rows []FreeToolSummarizeReportRequestRowsInner, ) *FreeToolSummarizeReportRequest`

NewFreeToolSummarizeReportRequest instantiates a new FreeToolSummarizeReportRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolSummarizeReportRequestWithDefaults

`func NewFreeToolSummarizeReportRequestWithDefaults() *FreeToolSummarizeReportRequest`

NewFreeToolSummarizeReportRequestWithDefaults instantiates a new FreeToolSummarizeReportRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRows

`func (o *FreeToolSummarizeReportRequest) GetRows() []FreeToolSummarizeReportRequestRowsInner`

GetRows returns the Rows field if non-nil, zero value otherwise.

### GetRowsOk

`func (o *FreeToolSummarizeReportRequest) GetRowsOk() (*[]FreeToolSummarizeReportRequestRowsInner, bool)`

GetRowsOk returns a tuple with the Rows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRows

`func (o *FreeToolSummarizeReportRequest) SetRows(v []FreeToolSummarizeReportRequestRowsInner)`

SetRows sets Rows field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


