# FreeToolPlanContentCalendarRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StartDate** | **string** | First day of the calendar (YYYY-MM-DD). Each week starts on this weekday. | 
**Weeks** | Pointer to **int32** |  | [optional] [default to 4]
**PostsPerWeek** | [**FreeToolPlanContentCalendarRequestPostsPerWeek**](FreeToolPlanContentCalendarRequestPostsPerWeek.md) |  | 
**Times** | Pointer to [**FreeToolPlanContentCalendarRequestTimes**](FreeToolPlanContentCalendarRequestTimes.md) |  | [optional] 
**Pillars** | Pointer to **[]string** | Content themes, rotated over the posts in date order. | [optional] 

## Methods

### NewFreeToolPlanContentCalendarRequest

`func NewFreeToolPlanContentCalendarRequest(startDate string, postsPerWeek FreeToolPlanContentCalendarRequestPostsPerWeek, ) *FreeToolPlanContentCalendarRequest`

NewFreeToolPlanContentCalendarRequest instantiates a new FreeToolPlanContentCalendarRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolPlanContentCalendarRequestWithDefaults

`func NewFreeToolPlanContentCalendarRequestWithDefaults() *FreeToolPlanContentCalendarRequest`

NewFreeToolPlanContentCalendarRequestWithDefaults instantiates a new FreeToolPlanContentCalendarRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStartDate

`func (o *FreeToolPlanContentCalendarRequest) GetStartDate() string`

GetStartDate returns the StartDate field if non-nil, zero value otherwise.

### GetStartDateOk

`func (o *FreeToolPlanContentCalendarRequest) GetStartDateOk() (*string, bool)`

GetStartDateOk returns a tuple with the StartDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartDate

`func (o *FreeToolPlanContentCalendarRequest) SetStartDate(v string)`

SetStartDate sets StartDate field to given value.


### GetWeeks

`func (o *FreeToolPlanContentCalendarRequest) GetWeeks() int32`

GetWeeks returns the Weeks field if non-nil, zero value otherwise.

### GetWeeksOk

`func (o *FreeToolPlanContentCalendarRequest) GetWeeksOk() (*int32, bool)`

GetWeeksOk returns a tuple with the Weeks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeeks

`func (o *FreeToolPlanContentCalendarRequest) SetWeeks(v int32)`

SetWeeks sets Weeks field to given value.

### HasWeeks

`func (o *FreeToolPlanContentCalendarRequest) HasWeeks() bool`

HasWeeks returns a boolean if a field has been set.

### GetPostsPerWeek

`func (o *FreeToolPlanContentCalendarRequest) GetPostsPerWeek() FreeToolPlanContentCalendarRequestPostsPerWeek`

GetPostsPerWeek returns the PostsPerWeek field if non-nil, zero value otherwise.

### GetPostsPerWeekOk

`func (o *FreeToolPlanContentCalendarRequest) GetPostsPerWeekOk() (*FreeToolPlanContentCalendarRequestPostsPerWeek, bool)`

GetPostsPerWeekOk returns a tuple with the PostsPerWeek field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostsPerWeek

`func (o *FreeToolPlanContentCalendarRequest) SetPostsPerWeek(v FreeToolPlanContentCalendarRequestPostsPerWeek)`

SetPostsPerWeek sets PostsPerWeek field to given value.


### GetTimes

`func (o *FreeToolPlanContentCalendarRequest) GetTimes() FreeToolPlanContentCalendarRequestTimes`

GetTimes returns the Times field if non-nil, zero value otherwise.

### GetTimesOk

`func (o *FreeToolPlanContentCalendarRequest) GetTimesOk() (*FreeToolPlanContentCalendarRequestTimes, bool)`

GetTimesOk returns a tuple with the Times field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimes

`func (o *FreeToolPlanContentCalendarRequest) SetTimes(v FreeToolPlanContentCalendarRequestTimes)`

SetTimes sets Times field to given value.

### HasTimes

`func (o *FreeToolPlanContentCalendarRequest) HasTimes() bool`

HasTimes returns a boolean if a field has been set.

### GetPillars

`func (o *FreeToolPlanContentCalendarRequest) GetPillars() []string`

GetPillars returns the Pillars field if non-nil, zero value otherwise.

### GetPillarsOk

`func (o *FreeToolPlanContentCalendarRequest) GetPillarsOk() (*[]string, bool)`

GetPillarsOk returns a tuple with the Pillars field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPillars

`func (o *FreeToolPlanContentCalendarRequest) SetPillars(v []string)`

SetPillars sets Pillars field to given value.

### HasPillars

`func (o *FreeToolPlanContentCalendarRequest) HasPillars() bool`

HasPillars returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


