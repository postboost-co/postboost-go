# FreeToolPlanContentCalendarResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EndDate** | Pointer to **string** | Last day of the calendar (YYYY-MM-DD). | [optional] 
**Total** | Pointer to **int32** | Number of posts planned. | [optional] 
**Slots** | Pointer to [**[]FreeToolPlanContentCalendarResponseSlotsInner**](FreeToolPlanContentCalendarResponseSlotsInner.md) |  | [optional] 
**Csv** | Pointer to **string** | The calendar as CSV (UTF-8 with BOM): Date, Day, Time, Network, Pillar, Idea. | [optional] 
**Ics** | Pointer to **string** | The calendar as an iCalendar file: one 15-minute event per post, in floating local time. | [optional] 

## Methods

### NewFreeToolPlanContentCalendarResponse

`func NewFreeToolPlanContentCalendarResponse() *FreeToolPlanContentCalendarResponse`

NewFreeToolPlanContentCalendarResponse instantiates a new FreeToolPlanContentCalendarResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolPlanContentCalendarResponseWithDefaults

`func NewFreeToolPlanContentCalendarResponseWithDefaults() *FreeToolPlanContentCalendarResponse`

NewFreeToolPlanContentCalendarResponseWithDefaults instantiates a new FreeToolPlanContentCalendarResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEndDate

`func (o *FreeToolPlanContentCalendarResponse) GetEndDate() string`

GetEndDate returns the EndDate field if non-nil, zero value otherwise.

### GetEndDateOk

`func (o *FreeToolPlanContentCalendarResponse) GetEndDateOk() (*string, bool)`

GetEndDateOk returns a tuple with the EndDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEndDate

`func (o *FreeToolPlanContentCalendarResponse) SetEndDate(v string)`

SetEndDate sets EndDate field to given value.

### HasEndDate

`func (o *FreeToolPlanContentCalendarResponse) HasEndDate() bool`

HasEndDate returns a boolean if a field has been set.

### GetTotal

`func (o *FreeToolPlanContentCalendarResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *FreeToolPlanContentCalendarResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *FreeToolPlanContentCalendarResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *FreeToolPlanContentCalendarResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetSlots

`func (o *FreeToolPlanContentCalendarResponse) GetSlots() []FreeToolPlanContentCalendarResponseSlotsInner`

GetSlots returns the Slots field if non-nil, zero value otherwise.

### GetSlotsOk

`func (o *FreeToolPlanContentCalendarResponse) GetSlotsOk() (*[]FreeToolPlanContentCalendarResponseSlotsInner, bool)`

GetSlotsOk returns a tuple with the Slots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlots

`func (o *FreeToolPlanContentCalendarResponse) SetSlots(v []FreeToolPlanContentCalendarResponseSlotsInner)`

SetSlots sets Slots field to given value.

### HasSlots

`func (o *FreeToolPlanContentCalendarResponse) HasSlots() bool`

HasSlots returns a boolean if a field has been set.

### GetCsv

`func (o *FreeToolPlanContentCalendarResponse) GetCsv() string`

GetCsv returns the Csv field if non-nil, zero value otherwise.

### GetCsvOk

`func (o *FreeToolPlanContentCalendarResponse) GetCsvOk() (*string, bool)`

GetCsvOk returns a tuple with the Csv field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCsv

`func (o *FreeToolPlanContentCalendarResponse) SetCsv(v string)`

SetCsv sets Csv field to given value.

### HasCsv

`func (o *FreeToolPlanContentCalendarResponse) HasCsv() bool`

HasCsv returns a boolean if a field has been set.

### GetIcs

`func (o *FreeToolPlanContentCalendarResponse) GetIcs() string`

GetIcs returns the Ics field if non-nil, zero value otherwise.

### GetIcsOk

`func (o *FreeToolPlanContentCalendarResponse) GetIcsOk() (*string, bool)`

GetIcsOk returns a tuple with the Ics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcs

`func (o *FreeToolPlanContentCalendarResponse) SetIcs(v string)`

SetIcs sets Ics field to given value.

### HasIcs

`func (o *FreeToolPlanContentCalendarResponse) HasIcs() bool`

HasIcs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


