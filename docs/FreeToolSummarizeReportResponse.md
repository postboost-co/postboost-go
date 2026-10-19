# FreeToolSummarizeReportResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Posts** | Pointer to **int32** |  | [optional] 
**DateRange** | Pointer to [**FreeToolSummarizeReportResponseDateRange**](FreeToolSummarizeReportResponseDateRange.md) |  | [optional] 
**Views** | Pointer to **NullableInt32** |  | [optional] 
**Engagements** | Pointer to **int32** |  | [optional] 
**EngagementRate** | Pointer to **NullableFloat32** | Percent, 2 decimals; null without views. | [optional] 
**EngagementsFrom** | Pointer to **[]string** | The counts added up as engagements. | [optional] 
**Networks** | Pointer to [**[]FreeToolSummarizeReportResponseNetworksInner**](FreeToolSummarizeReportResponseNetworksInner.md) |  | [optional] 
**TopPosts** | Pointer to [**[]FreeToolSummarizeReportResponseTopPostsInner**](FreeToolSummarizeReportResponseTopPostsInner.md) |  | [optional] 
**Weekdays** | Pointer to [**[]FreeToolSummarizeReportResponseWeekdaysInner**](FreeToolSummarizeReportResponseWeekdaysInner.md) |  | [optional] 
**BestWeekday** | Pointer to **NullableString** | The weekday with the highest average engagements per post. | [optional] 

## Methods

### NewFreeToolSummarizeReportResponse

`func NewFreeToolSummarizeReportResponse() *FreeToolSummarizeReportResponse`

NewFreeToolSummarizeReportResponse instantiates a new FreeToolSummarizeReportResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolSummarizeReportResponseWithDefaults

`func NewFreeToolSummarizeReportResponseWithDefaults() *FreeToolSummarizeReportResponse`

NewFreeToolSummarizeReportResponseWithDefaults instantiates a new FreeToolSummarizeReportResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPosts

`func (o *FreeToolSummarizeReportResponse) GetPosts() int32`

GetPosts returns the Posts field if non-nil, zero value otherwise.

### GetPostsOk

`func (o *FreeToolSummarizeReportResponse) GetPostsOk() (*int32, bool)`

GetPostsOk returns a tuple with the Posts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosts

`func (o *FreeToolSummarizeReportResponse) SetPosts(v int32)`

SetPosts sets Posts field to given value.

### HasPosts

`func (o *FreeToolSummarizeReportResponse) HasPosts() bool`

HasPosts returns a boolean if a field has been set.

### GetDateRange

`func (o *FreeToolSummarizeReportResponse) GetDateRange() FreeToolSummarizeReportResponseDateRange`

GetDateRange returns the DateRange field if non-nil, zero value otherwise.

### GetDateRangeOk

`func (o *FreeToolSummarizeReportResponse) GetDateRangeOk() (*FreeToolSummarizeReportResponseDateRange, bool)`

GetDateRangeOk returns a tuple with the DateRange field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateRange

`func (o *FreeToolSummarizeReportResponse) SetDateRange(v FreeToolSummarizeReportResponseDateRange)`

SetDateRange sets DateRange field to given value.

### HasDateRange

`func (o *FreeToolSummarizeReportResponse) HasDateRange() bool`

HasDateRange returns a boolean if a field has been set.

### GetViews

`func (o *FreeToolSummarizeReportResponse) GetViews() int32`

GetViews returns the Views field if non-nil, zero value otherwise.

### GetViewsOk

`func (o *FreeToolSummarizeReportResponse) GetViewsOk() (*int32, bool)`

GetViewsOk returns a tuple with the Views field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetViews

`func (o *FreeToolSummarizeReportResponse) SetViews(v int32)`

SetViews sets Views field to given value.

### HasViews

`func (o *FreeToolSummarizeReportResponse) HasViews() bool`

HasViews returns a boolean if a field has been set.

### SetViewsNil

`func (o *FreeToolSummarizeReportResponse) SetViewsNil(b bool)`

 SetViewsNil sets the value for Views to be an explicit nil

### UnsetViews
`func (o *FreeToolSummarizeReportResponse) UnsetViews()`

UnsetViews ensures that no value is present for Views, not even an explicit nil
### GetEngagements

`func (o *FreeToolSummarizeReportResponse) GetEngagements() int32`

GetEngagements returns the Engagements field if non-nil, zero value otherwise.

### GetEngagementsOk

`func (o *FreeToolSummarizeReportResponse) GetEngagementsOk() (*int32, bool)`

GetEngagementsOk returns a tuple with the Engagements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngagements

`func (o *FreeToolSummarizeReportResponse) SetEngagements(v int32)`

SetEngagements sets Engagements field to given value.

### HasEngagements

`func (o *FreeToolSummarizeReportResponse) HasEngagements() bool`

HasEngagements returns a boolean if a field has been set.

### GetEngagementRate

`func (o *FreeToolSummarizeReportResponse) GetEngagementRate() float32`

GetEngagementRate returns the EngagementRate field if non-nil, zero value otherwise.

### GetEngagementRateOk

`func (o *FreeToolSummarizeReportResponse) GetEngagementRateOk() (*float32, bool)`

GetEngagementRateOk returns a tuple with the EngagementRate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngagementRate

`func (o *FreeToolSummarizeReportResponse) SetEngagementRate(v float32)`

SetEngagementRate sets EngagementRate field to given value.

### HasEngagementRate

`func (o *FreeToolSummarizeReportResponse) HasEngagementRate() bool`

HasEngagementRate returns a boolean if a field has been set.

### SetEngagementRateNil

`func (o *FreeToolSummarizeReportResponse) SetEngagementRateNil(b bool)`

 SetEngagementRateNil sets the value for EngagementRate to be an explicit nil

### UnsetEngagementRate
`func (o *FreeToolSummarizeReportResponse) UnsetEngagementRate()`

UnsetEngagementRate ensures that no value is present for EngagementRate, not even an explicit nil
### GetEngagementsFrom

`func (o *FreeToolSummarizeReportResponse) GetEngagementsFrom() []string`

GetEngagementsFrom returns the EngagementsFrom field if non-nil, zero value otherwise.

### GetEngagementsFromOk

`func (o *FreeToolSummarizeReportResponse) GetEngagementsFromOk() (*[]string, bool)`

GetEngagementsFromOk returns a tuple with the EngagementsFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngagementsFrom

`func (o *FreeToolSummarizeReportResponse) SetEngagementsFrom(v []string)`

SetEngagementsFrom sets EngagementsFrom field to given value.

### HasEngagementsFrom

`func (o *FreeToolSummarizeReportResponse) HasEngagementsFrom() bool`

HasEngagementsFrom returns a boolean if a field has been set.

### GetNetworks

`func (o *FreeToolSummarizeReportResponse) GetNetworks() []FreeToolSummarizeReportResponseNetworksInner`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *FreeToolSummarizeReportResponse) GetNetworksOk() (*[]FreeToolSummarizeReportResponseNetworksInner, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *FreeToolSummarizeReportResponse) SetNetworks(v []FreeToolSummarizeReportResponseNetworksInner)`

SetNetworks sets Networks field to given value.

### HasNetworks

`func (o *FreeToolSummarizeReportResponse) HasNetworks() bool`

HasNetworks returns a boolean if a field has been set.

### GetTopPosts

`func (o *FreeToolSummarizeReportResponse) GetTopPosts() []FreeToolSummarizeReportResponseTopPostsInner`

GetTopPosts returns the TopPosts field if non-nil, zero value otherwise.

### GetTopPostsOk

`func (o *FreeToolSummarizeReportResponse) GetTopPostsOk() (*[]FreeToolSummarizeReportResponseTopPostsInner, bool)`

GetTopPostsOk returns a tuple with the TopPosts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopPosts

`func (o *FreeToolSummarizeReportResponse) SetTopPosts(v []FreeToolSummarizeReportResponseTopPostsInner)`

SetTopPosts sets TopPosts field to given value.

### HasTopPosts

`func (o *FreeToolSummarizeReportResponse) HasTopPosts() bool`

HasTopPosts returns a boolean if a field has been set.

### GetWeekdays

`func (o *FreeToolSummarizeReportResponse) GetWeekdays() []FreeToolSummarizeReportResponseWeekdaysInner`

GetWeekdays returns the Weekdays field if non-nil, zero value otherwise.

### GetWeekdaysOk

`func (o *FreeToolSummarizeReportResponse) GetWeekdaysOk() (*[]FreeToolSummarizeReportResponseWeekdaysInner, bool)`

GetWeekdaysOk returns a tuple with the Weekdays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeekdays

`func (o *FreeToolSummarizeReportResponse) SetWeekdays(v []FreeToolSummarizeReportResponseWeekdaysInner)`

SetWeekdays sets Weekdays field to given value.

### HasWeekdays

`func (o *FreeToolSummarizeReportResponse) HasWeekdays() bool`

HasWeekdays returns a boolean if a field has been set.

### GetBestWeekday

`func (o *FreeToolSummarizeReportResponse) GetBestWeekday() string`

GetBestWeekday returns the BestWeekday field if non-nil, zero value otherwise.

### GetBestWeekdayOk

`func (o *FreeToolSummarizeReportResponse) GetBestWeekdayOk() (*string, bool)`

GetBestWeekdayOk returns a tuple with the BestWeekday field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBestWeekday

`func (o *FreeToolSummarizeReportResponse) SetBestWeekday(v string)`

SetBestWeekday sets BestWeekday field to given value.

### HasBestWeekday

`func (o *FreeToolSummarizeReportResponse) HasBestWeekday() bool`

HasBestWeekday returns a boolean if a field has been set.

### SetBestWeekdayNil

`func (o *FreeToolSummarizeReportResponse) SetBestWeekdayNil(b bool)`

 SetBestWeekdayNil sets the value for BestWeekday to be an explicit nil

### UnsetBestWeekday
`func (o *FreeToolSummarizeReportResponse) UnsetBestWeekday()`

UnsetBestWeekday ensures that no value is present for BestWeekday, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


