# FreeToolSummarizeReportRequestRowsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Date** | Pointer to **string** | Publish date; only a leading YYYY-MM-DD is read. | [optional] 
**Network** | Pointer to **string** |  | [optional] 
**Text** | Pointer to **string** | The post text, a full caption is fine; the top posts show its first 80 characters. | [optional] 
**Views** | Pointer to **int32** |  | [optional] 
**Likes** | Pointer to **int32** |  | [optional] 
**Comments** | Pointer to **int32** |  | [optional] 
**Shares** | Pointer to **int32** |  | [optional] 
**Clicks** | Pointer to **int32** |  | [optional] 
**Engagements** | Pointer to **int32** |  | [optional] 

## Methods

### NewFreeToolSummarizeReportRequestRowsInner

`func NewFreeToolSummarizeReportRequestRowsInner() *FreeToolSummarizeReportRequestRowsInner`

NewFreeToolSummarizeReportRequestRowsInner instantiates a new FreeToolSummarizeReportRequestRowsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolSummarizeReportRequestRowsInnerWithDefaults

`func NewFreeToolSummarizeReportRequestRowsInnerWithDefaults() *FreeToolSummarizeReportRequestRowsInner`

NewFreeToolSummarizeReportRequestRowsInnerWithDefaults instantiates a new FreeToolSummarizeReportRequestRowsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDate

`func (o *FreeToolSummarizeReportRequestRowsInner) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *FreeToolSummarizeReportRequestRowsInner) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *FreeToolSummarizeReportRequestRowsInner) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *FreeToolSummarizeReportRequestRowsInner) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetNetwork

`func (o *FreeToolSummarizeReportRequestRowsInner) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *FreeToolSummarizeReportRequestRowsInner) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *FreeToolSummarizeReportRequestRowsInner) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *FreeToolSummarizeReportRequestRowsInner) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetText

`func (o *FreeToolSummarizeReportRequestRowsInner) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolSummarizeReportRequestRowsInner) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolSummarizeReportRequestRowsInner) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *FreeToolSummarizeReportRequestRowsInner) HasText() bool`

HasText returns a boolean if a field has been set.

### GetViews

`func (o *FreeToolSummarizeReportRequestRowsInner) GetViews() int32`

GetViews returns the Views field if non-nil, zero value otherwise.

### GetViewsOk

`func (o *FreeToolSummarizeReportRequestRowsInner) GetViewsOk() (*int32, bool)`

GetViewsOk returns a tuple with the Views field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetViews

`func (o *FreeToolSummarizeReportRequestRowsInner) SetViews(v int32)`

SetViews sets Views field to given value.

### HasViews

`func (o *FreeToolSummarizeReportRequestRowsInner) HasViews() bool`

HasViews returns a boolean if a field has been set.

### GetLikes

`func (o *FreeToolSummarizeReportRequestRowsInner) GetLikes() int32`

GetLikes returns the Likes field if non-nil, zero value otherwise.

### GetLikesOk

`func (o *FreeToolSummarizeReportRequestRowsInner) GetLikesOk() (*int32, bool)`

GetLikesOk returns a tuple with the Likes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLikes

`func (o *FreeToolSummarizeReportRequestRowsInner) SetLikes(v int32)`

SetLikes sets Likes field to given value.

### HasLikes

`func (o *FreeToolSummarizeReportRequestRowsInner) HasLikes() bool`

HasLikes returns a boolean if a field has been set.

### GetComments

`func (o *FreeToolSummarizeReportRequestRowsInner) GetComments() int32`

GetComments returns the Comments field if non-nil, zero value otherwise.

### GetCommentsOk

`func (o *FreeToolSummarizeReportRequestRowsInner) GetCommentsOk() (*int32, bool)`

GetCommentsOk returns a tuple with the Comments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComments

`func (o *FreeToolSummarizeReportRequestRowsInner) SetComments(v int32)`

SetComments sets Comments field to given value.

### HasComments

`func (o *FreeToolSummarizeReportRequestRowsInner) HasComments() bool`

HasComments returns a boolean if a field has been set.

### GetShares

`func (o *FreeToolSummarizeReportRequestRowsInner) GetShares() int32`

GetShares returns the Shares field if non-nil, zero value otherwise.

### GetSharesOk

`func (o *FreeToolSummarizeReportRequestRowsInner) GetSharesOk() (*int32, bool)`

GetSharesOk returns a tuple with the Shares field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShares

`func (o *FreeToolSummarizeReportRequestRowsInner) SetShares(v int32)`

SetShares sets Shares field to given value.

### HasShares

`func (o *FreeToolSummarizeReportRequestRowsInner) HasShares() bool`

HasShares returns a boolean if a field has been set.

### GetClicks

`func (o *FreeToolSummarizeReportRequestRowsInner) GetClicks() int32`

GetClicks returns the Clicks field if non-nil, zero value otherwise.

### GetClicksOk

`func (o *FreeToolSummarizeReportRequestRowsInner) GetClicksOk() (*int32, bool)`

GetClicksOk returns a tuple with the Clicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClicks

`func (o *FreeToolSummarizeReportRequestRowsInner) SetClicks(v int32)`

SetClicks sets Clicks field to given value.

### HasClicks

`func (o *FreeToolSummarizeReportRequestRowsInner) HasClicks() bool`

HasClicks returns a boolean if a field has been set.

### GetEngagements

`func (o *FreeToolSummarizeReportRequestRowsInner) GetEngagements() int32`

GetEngagements returns the Engagements field if non-nil, zero value otherwise.

### GetEngagementsOk

`func (o *FreeToolSummarizeReportRequestRowsInner) GetEngagementsOk() (*int32, bool)`

GetEngagementsOk returns a tuple with the Engagements field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngagements

`func (o *FreeToolSummarizeReportRequestRowsInner) SetEngagements(v int32)`

SetEngagements sets Engagements field to given value.

### HasEngagements

`func (o *FreeToolSummarizeReportRequestRowsInner) HasEngagements() bool`

HasEngagements returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


