# XUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PeriodStart** | **time.Time** |  | 
**PeriodEnd** | **time.Time** |  | 
**Enforced** | **bool** | Whether an allowance applies to this workspace. | 
**Posts** | [**XUsageCounter**](XUsageCounter.md) |  | 
**LinkPosts** | [**XUsageCounter**](XUsageCounter.md) |  | 
**EstimatedCostUsd** | **float32** | PostBoost&#39;s estimate of what X charged for these posts. Informational; you are not billed per post. | 

## Methods

### NewXUsage

`func NewXUsage(periodStart time.Time, periodEnd time.Time, enforced bool, posts XUsageCounter, linkPosts XUsageCounter, estimatedCostUsd float32, ) *XUsage`

NewXUsage instantiates a new XUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewXUsageWithDefaults

`func NewXUsageWithDefaults() *XUsage`

NewXUsageWithDefaults instantiates a new XUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPeriodStart

`func (o *XUsage) GetPeriodStart() time.Time`

GetPeriodStart returns the PeriodStart field if non-nil, zero value otherwise.

### GetPeriodStartOk

`func (o *XUsage) GetPeriodStartOk() (*time.Time, bool)`

GetPeriodStartOk returns a tuple with the PeriodStart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodStart

`func (o *XUsage) SetPeriodStart(v time.Time)`

SetPeriodStart sets PeriodStart field to given value.


### GetPeriodEnd

`func (o *XUsage) GetPeriodEnd() time.Time`

GetPeriodEnd returns the PeriodEnd field if non-nil, zero value otherwise.

### GetPeriodEndOk

`func (o *XUsage) GetPeriodEndOk() (*time.Time, bool)`

GetPeriodEndOk returns a tuple with the PeriodEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeriodEnd

`func (o *XUsage) SetPeriodEnd(v time.Time)`

SetPeriodEnd sets PeriodEnd field to given value.


### GetEnforced

`func (o *XUsage) GetEnforced() bool`

GetEnforced returns the Enforced field if non-nil, zero value otherwise.

### GetEnforcedOk

`func (o *XUsage) GetEnforcedOk() (*bool, bool)`

GetEnforcedOk returns a tuple with the Enforced field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnforced

`func (o *XUsage) SetEnforced(v bool)`

SetEnforced sets Enforced field to given value.


### GetPosts

`func (o *XUsage) GetPosts() XUsageCounter`

GetPosts returns the Posts field if non-nil, zero value otherwise.

### GetPostsOk

`func (o *XUsage) GetPostsOk() (*XUsageCounter, bool)`

GetPostsOk returns a tuple with the Posts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosts

`func (o *XUsage) SetPosts(v XUsageCounter)`

SetPosts sets Posts field to given value.


### GetLinkPosts

`func (o *XUsage) GetLinkPosts() XUsageCounter`

GetLinkPosts returns the LinkPosts field if non-nil, zero value otherwise.

### GetLinkPostsOk

`func (o *XUsage) GetLinkPostsOk() (*XUsageCounter, bool)`

GetLinkPostsOk returns a tuple with the LinkPosts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkPosts

`func (o *XUsage) SetLinkPosts(v XUsageCounter)`

SetLinkPosts sets LinkPosts field to given value.


### GetEstimatedCostUsd

`func (o *XUsage) GetEstimatedCostUsd() float32`

GetEstimatedCostUsd returns the EstimatedCostUsd field if non-nil, zero value otherwise.

### GetEstimatedCostUsdOk

`func (o *XUsage) GetEstimatedCostUsdOk() (*float32, bool)`

GetEstimatedCostUsdOk returns a tuple with the EstimatedCostUsd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedCostUsd

`func (o *XUsage) SetEstimatedCostUsd(v float32)`

SetEstimatedCostUsd sets EstimatedCostUsd field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


