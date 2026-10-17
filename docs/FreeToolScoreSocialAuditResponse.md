# FreeToolScoreSocialAuditResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Score** | Pointer to **int32** | Overall score: all points over the maximum, as 0-100 rounded half up. | [optional] 
**Networks** | Pointer to [**[]FreeToolScoreSocialAuditResponseNetworksInner**](FreeToolScoreSocialAuditResponseNetworksInner.md) | One row per audited network, in a fixed network order. | [optional] 
**TopFixes** | Pointer to [**[]FreeToolScoreSocialAuditResponseTopFixesInner**](FreeToolScoreSocialAuditResponseTopFixesInner.md) | Up to 3 questions with the fewest points over all audited networks (ties: checklist order); only questions answered below yes somewhere. | [optional] 
**ReportMarkdown** | Pointer to **string** | The scorecard as a Markdown report: overall score, top fixes and every answer per network. | [optional] 

## Methods

### NewFreeToolScoreSocialAuditResponse

`func NewFreeToolScoreSocialAuditResponse() *FreeToolScoreSocialAuditResponse`

NewFreeToolScoreSocialAuditResponse instantiates a new FreeToolScoreSocialAuditResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolScoreSocialAuditResponseWithDefaults

`func NewFreeToolScoreSocialAuditResponseWithDefaults() *FreeToolScoreSocialAuditResponse`

NewFreeToolScoreSocialAuditResponseWithDefaults instantiates a new FreeToolScoreSocialAuditResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetScore

`func (o *FreeToolScoreSocialAuditResponse) GetScore() int32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *FreeToolScoreSocialAuditResponse) GetScoreOk() (*int32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *FreeToolScoreSocialAuditResponse) SetScore(v int32)`

SetScore sets Score field to given value.

### HasScore

`func (o *FreeToolScoreSocialAuditResponse) HasScore() bool`

HasScore returns a boolean if a field has been set.

### GetNetworks

`func (o *FreeToolScoreSocialAuditResponse) GetNetworks() []FreeToolScoreSocialAuditResponseNetworksInner`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *FreeToolScoreSocialAuditResponse) GetNetworksOk() (*[]FreeToolScoreSocialAuditResponseNetworksInner, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *FreeToolScoreSocialAuditResponse) SetNetworks(v []FreeToolScoreSocialAuditResponseNetworksInner)`

SetNetworks sets Networks field to given value.

### HasNetworks

`func (o *FreeToolScoreSocialAuditResponse) HasNetworks() bool`

HasNetworks returns a boolean if a field has been set.

### GetTopFixes

`func (o *FreeToolScoreSocialAuditResponse) GetTopFixes() []FreeToolScoreSocialAuditResponseTopFixesInner`

GetTopFixes returns the TopFixes field if non-nil, zero value otherwise.

### GetTopFixesOk

`func (o *FreeToolScoreSocialAuditResponse) GetTopFixesOk() (*[]FreeToolScoreSocialAuditResponseTopFixesInner, bool)`

GetTopFixesOk returns a tuple with the TopFixes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopFixes

`func (o *FreeToolScoreSocialAuditResponse) SetTopFixes(v []FreeToolScoreSocialAuditResponseTopFixesInner)`

SetTopFixes sets TopFixes field to given value.

### HasTopFixes

`func (o *FreeToolScoreSocialAuditResponse) HasTopFixes() bool`

HasTopFixes returns a boolean if a field has been set.

### GetReportMarkdown

`func (o *FreeToolScoreSocialAuditResponse) GetReportMarkdown() string`

GetReportMarkdown returns the ReportMarkdown field if non-nil, zero value otherwise.

### GetReportMarkdownOk

`func (o *FreeToolScoreSocialAuditResponse) GetReportMarkdownOk() (*string, bool)`

GetReportMarkdownOk returns a tuple with the ReportMarkdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReportMarkdown

`func (o *FreeToolScoreSocialAuditResponse) SetReportMarkdown(v string)`

SetReportMarkdown sets ReportMarkdown field to given value.

### HasReportMarkdown

`func (o *FreeToolScoreSocialAuditResponse) HasReportMarkdown() bool`

HasReportMarkdown returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


