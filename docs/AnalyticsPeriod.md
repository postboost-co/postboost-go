# AnalyticsPeriod

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StartDate** | **string** |  | 
**EndDate** | **string** |  | 
**PreviousStartDate** | **string** | Start of the equally long range before this one, used for comparisons. | 
**PreviousEndDate** | **string** |  | 

## Methods

### NewAnalyticsPeriod

`func NewAnalyticsPeriod(startDate string, endDate string, previousStartDate string, previousEndDate string, ) *AnalyticsPeriod`

NewAnalyticsPeriod instantiates a new AnalyticsPeriod object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsPeriodWithDefaults

`func NewAnalyticsPeriodWithDefaults() *AnalyticsPeriod`

NewAnalyticsPeriodWithDefaults instantiates a new AnalyticsPeriod object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStartDate

`func (o *AnalyticsPeriod) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *AnalyticsPeriod) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *AnalyticsPeriod) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.


### GetEndDate

`func (o *AnalyticsPeriod) GetEndDate() string`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *AnalyticsPeriod) GetEndDateOk() (*string, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *AnalyticsPeriod) SetEndDate(v string)`

SetEndDate sets EndDate field to given value.


### GetPreviousStartDate

`func (o *AnalyticsPeriod) GetPreviousStartDate() string`

GetPreviousStartDate returns the PreviousStartDate field if non-nil, zero value otherwise.

### GetPreviousStartDateOk

`func (o *AnalyticsPeriod) GetPreviousStartDateOk() (*string, bool)`

GetPreviousStartDateOk returns a tuple with the PreviousStartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousStartDate

`func (o *AnalyticsPeriod) SetPreviousStartDate(v string)`

SetPreviousStartDate sets PreviousStartDate field to given value.


### GetPreviousEndDate

`func (o *AnalyticsPeriod) GetPreviousEndDate() string`

GetPreviousEndDate returns the PreviousEndDate field if non-nil, zero value otherwise.

### GetPreviousEndDateOk

`func (o *AnalyticsPeriod) GetPreviousEndDateOk() (*string, bool)`

GetPreviousEndDateOk returns a tuple with the PreviousEndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviousEndDate

`func (o *AnalyticsPeriod) SetPreviousEndDate(v string)`

SetPreviousEndDate sets PreviousEndDate field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


