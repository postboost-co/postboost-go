# FreeToolCalculateSmmPricingRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Networks** | **int32** | Number of social networks managed. | 
**PostsPerWeek** | **int32** | Posts per week on each network. | 
**ContentType** | Pointer to **string** | What goes into a post. Assumed minutes per post: copy 30, copy_design 60, copy_design_video 120. | [optional] [default to "copy_design"]
**CommunityHoursPerWeek** | Pointer to **float32** | Community management (replies, comments, DMs), hours per week. | [optional] [default to 0]
**ReportingHoursPerMonth** | Pointer to **float32** | Reporting, hours per month. | [optional] [default to 0]
**AdHoursPerMonth** | Pointer to **float32** | Paid social ad management, hours per month. | [optional] [default to 0]
**HourlyRate** | Pointer to **float32** | Your hourly rate. The default 50 is a round placeholder, not a market rate. | [optional] [default to 50]
**Currency** | Pointer to **string** | Currency for formatting only; nothing is converted. | [optional] [default to "USD"]
**PricingModel** | Pointer to **string** | Which price leads the quote: hourly, monthly retainer or per post. | [optional] [default to "retainer"]

## Methods

### NewFreeToolCalculateSmmPricingRequest

`func NewFreeToolCalculateSmmPricingRequest(networks int32, postsPerWeek int32, ) *FreeToolCalculateSmmPricingRequest`

NewFreeToolCalculateSmmPricingRequest instantiates a new FreeToolCalculateSmmPricingRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCalculateSmmPricingRequestWithDefaults

`func NewFreeToolCalculateSmmPricingRequestWithDefaults() *FreeToolCalculateSmmPricingRequest`

NewFreeToolCalculateSmmPricingRequestWithDefaults instantiates a new FreeToolCalculateSmmPricingRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNetworks

`func (o *FreeToolCalculateSmmPricingRequest) GetNetworks() int32`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *FreeToolCalculateSmmPricingRequest) GetNetworksOk() (*int32, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *FreeToolCalculateSmmPricingRequest) SetNetworks(v int32)`

SetNetworks sets Networks field to given value.


### GetPostsPerWeek

`func (o *FreeToolCalculateSmmPricingRequest) GetPostsPerWeek() int32`

GetPostsPerWeek returns the PostsPerWeek field if non-nil, zero value otherwise.

### GetPostsPerWeekOk

`func (o *FreeToolCalculateSmmPricingRequest) GetPostsPerWeekOk() (*int32, bool)`

GetPostsPerWeekOk returns a tuple with the PostsPerWeek field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostsPerWeek

`func (o *FreeToolCalculateSmmPricingRequest) SetPostsPerWeek(v int32)`

SetPostsPerWeek sets PostsPerWeek field to given value.


### GetContentType

`func (o *FreeToolCalculateSmmPricingRequest) GetContentType() string`

GetContentType returns the ContentType field if non-nil, zero value otherwise.

### GetContentTypeOk

`func (o *FreeToolCalculateSmmPricingRequest) GetContentTypeOk() (*string, bool)`

GetContentTypeOk returns a tuple with the ContentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentType

`func (o *FreeToolCalculateSmmPricingRequest) SetContentType(v string)`

SetContentType sets ContentType field to given value.

### HasContentType

`func (o *FreeToolCalculateSmmPricingRequest) HasContentType() bool`

HasContentType returns a boolean if a field has been set.

### GetCommunityHoursPerWeek

`func (o *FreeToolCalculateSmmPricingRequest) GetCommunityHoursPerWeek() float32`

GetCommunityHoursPerWeek returns the CommunityHoursPerWeek field if non-nil, zero value otherwise.

### GetCommunityHoursPerWeekOk

`func (o *FreeToolCalculateSmmPricingRequest) GetCommunityHoursPerWeekOk() (*float32, bool)`

GetCommunityHoursPerWeekOk returns a tuple with the CommunityHoursPerWeek field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommunityHoursPerWeek

`func (o *FreeToolCalculateSmmPricingRequest) SetCommunityHoursPerWeek(v float32)`

SetCommunityHoursPerWeek sets CommunityHoursPerWeek field to given value.

### HasCommunityHoursPerWeek

`func (o *FreeToolCalculateSmmPricingRequest) HasCommunityHoursPerWeek() bool`

HasCommunityHoursPerWeek returns a boolean if a field has been set.

### GetReportingHoursPerMonth

`func (o *FreeToolCalculateSmmPricingRequest) GetReportingHoursPerMonth() float32`

GetReportingHoursPerMonth returns the ReportingHoursPerMonth field if non-nil, zero value otherwise.

### GetReportingHoursPerMonthOk

`func (o *FreeToolCalculateSmmPricingRequest) GetReportingHoursPerMonthOk() (*float32, bool)`

GetReportingHoursPerMonthOk returns a tuple with the ReportingHoursPerMonth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportingHoursPerMonth

`func (o *FreeToolCalculateSmmPricingRequest) SetReportingHoursPerMonth(v float32)`

SetReportingHoursPerMonth sets ReportingHoursPerMonth field to given value.

### HasReportingHoursPerMonth

`func (o *FreeToolCalculateSmmPricingRequest) HasReportingHoursPerMonth() bool`

HasReportingHoursPerMonth returns a boolean if a field has been set.

### GetAdHoursPerMonth

`func (o *FreeToolCalculateSmmPricingRequest) GetAdHoursPerMonth() float32`

GetAdHoursPerMonth returns the AdHoursPerMonth field if non-nil, zero value otherwise.

### GetAdHoursPerMonthOk

`func (o *FreeToolCalculateSmmPricingRequest) GetAdHoursPerMonthOk() (*float32, bool)`

GetAdHoursPerMonthOk returns a tuple with the AdHoursPerMonth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdHoursPerMonth

`func (o *FreeToolCalculateSmmPricingRequest) SetAdHoursPerMonth(v float32)`

SetAdHoursPerMonth sets AdHoursPerMonth field to given value.

### HasAdHoursPerMonth

`func (o *FreeToolCalculateSmmPricingRequest) HasAdHoursPerMonth() bool`

HasAdHoursPerMonth returns a boolean if a field has been set.

### GetHourlyRate

`func (o *FreeToolCalculateSmmPricingRequest) GetHourlyRate() float32`

GetHourlyRate returns the HourlyRate field if non-nil, zero value otherwise.

### GetHourlyRateOk

`func (o *FreeToolCalculateSmmPricingRequest) GetHourlyRateOk() (*float32, bool)`

GetHourlyRateOk returns a tuple with the HourlyRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHourlyRate

`func (o *FreeToolCalculateSmmPricingRequest) SetHourlyRate(v float32)`

SetHourlyRate sets HourlyRate field to given value.

### HasHourlyRate

`func (o *FreeToolCalculateSmmPricingRequest) HasHourlyRate() bool`

HasHourlyRate returns a boolean if a field has been set.

### GetCurrency

`func (o *FreeToolCalculateSmmPricingRequest) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *FreeToolCalculateSmmPricingRequest) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *FreeToolCalculateSmmPricingRequest) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *FreeToolCalculateSmmPricingRequest) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetPricingModel

`func (o *FreeToolCalculateSmmPricingRequest) GetPricingModel() string`

GetPricingModel returns the PricingModel field if non-nil, zero value otherwise.

### GetPricingModelOk

`func (o *FreeToolCalculateSmmPricingRequest) GetPricingModelOk() (*string, bool)`

GetPricingModelOk returns a tuple with the PricingModel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricingModel

`func (o *FreeToolCalculateSmmPricingRequest) SetPricingModel(v string)`

SetPricingModel sets PricingModel field to given value.

### HasPricingModel

`func (o *FreeToolCalculateSmmPricingRequest) HasPricingModel() bool`

HasPricingModel returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


