# FreeToolCalculateEngagementRateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Likes** | Pointer to **int32** |  | [optional] [default to 0]
**Comments** | Pointer to **int32** |  | [optional] [default to 0]
**Shares** | Pointer to **int32** |  | [optional] [default to 0]
**Saves** | Pointer to **int32** |  | [optional] [default to 0]
**Clicks** | Pointer to **int32** |  | [optional] [default to 0]
**Method** | Pointer to **string** | What to divide by. | [optional] [default to "followers"]
**Base** | **int32** | Followers, or the total reach or impressions of the posts. | 
**Posts** | Pointer to **int32** | Number of posts the engagements come from. | [optional] [default to 1]

## Methods

### NewFreeToolCalculateEngagementRateRequest

`func NewFreeToolCalculateEngagementRateRequest(base int32, ) *FreeToolCalculateEngagementRateRequest`

NewFreeToolCalculateEngagementRateRequest instantiates a new FreeToolCalculateEngagementRateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCalculateEngagementRateRequestWithDefaults

`func NewFreeToolCalculateEngagementRateRequestWithDefaults() *FreeToolCalculateEngagementRateRequest`

NewFreeToolCalculateEngagementRateRequestWithDefaults instantiates a new FreeToolCalculateEngagementRateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLikes

`func (o *FreeToolCalculateEngagementRateRequest) GetLikes() int32`

GetLikes returns the Likes field if non-nil, zero value otherwise.

### GetLikesOk

`func (o *FreeToolCalculateEngagementRateRequest) GetLikesOk() (*int32, bool)`

GetLikesOk returns a tuple with the Likes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLikes

`func (o *FreeToolCalculateEngagementRateRequest) SetLikes(v int32)`

SetLikes sets Likes field to given value.

### HasLikes

`func (o *FreeToolCalculateEngagementRateRequest) HasLikes() bool`

HasLikes returns a boolean if a field has been set.

### GetComments

`func (o *FreeToolCalculateEngagementRateRequest) GetComments() int32`

GetComments returns the Comments field if non-nil, zero value otherwise.

### GetCommentsOk

`func (o *FreeToolCalculateEngagementRateRequest) GetCommentsOk() (*int32, bool)`

GetCommentsOk returns a tuple with the Comments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComments

`func (o *FreeToolCalculateEngagementRateRequest) SetComments(v int32)`

SetComments sets Comments field to given value.

### HasComments

`func (o *FreeToolCalculateEngagementRateRequest) HasComments() bool`

HasComments returns a boolean if a field has been set.

### GetShares

`func (o *FreeToolCalculateEngagementRateRequest) GetShares() int32`

GetShares returns the Shares field if non-nil, zero value otherwise.

### GetSharesOk

`func (o *FreeToolCalculateEngagementRateRequest) GetSharesOk() (*int32, bool)`

GetSharesOk returns a tuple with the Shares field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShares

`func (o *FreeToolCalculateEngagementRateRequest) SetShares(v int32)`

SetShares sets Shares field to given value.

### HasShares

`func (o *FreeToolCalculateEngagementRateRequest) HasShares() bool`

HasShares returns a boolean if a field has been set.

### GetSaves

`func (o *FreeToolCalculateEngagementRateRequest) GetSaves() int32`

GetSaves returns the Saves field if non-nil, zero value otherwise.

### GetSavesOk

`func (o *FreeToolCalculateEngagementRateRequest) GetSavesOk() (*int32, bool)`

GetSavesOk returns a tuple with the Saves field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSaves

`func (o *FreeToolCalculateEngagementRateRequest) SetSaves(v int32)`

SetSaves sets Saves field to given value.

### HasSaves

`func (o *FreeToolCalculateEngagementRateRequest) HasSaves() bool`

HasSaves returns a boolean if a field has been set.

### GetClicks

`func (o *FreeToolCalculateEngagementRateRequest) GetClicks() int32`

GetClicks returns the Clicks field if non-nil, zero value otherwise.

### GetClicksOk

`func (o *FreeToolCalculateEngagementRateRequest) GetClicksOk() (*int32, bool)`

GetClicksOk returns a tuple with the Clicks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClicks

`func (o *FreeToolCalculateEngagementRateRequest) SetClicks(v int32)`

SetClicks sets Clicks field to given value.

### HasClicks

`func (o *FreeToolCalculateEngagementRateRequest) HasClicks() bool`

HasClicks returns a boolean if a field has been set.

### GetMethod

`func (o *FreeToolCalculateEngagementRateRequest) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *FreeToolCalculateEngagementRateRequest) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *FreeToolCalculateEngagementRateRequest) SetMethod(v string)`

SetMethod sets Method field to given value.

### HasMethod

`func (o *FreeToolCalculateEngagementRateRequest) HasMethod() bool`

HasMethod returns a boolean if a field has been set.

### GetBase

`func (o *FreeToolCalculateEngagementRateRequest) GetBase() int32`

GetBase returns the Base field if non-nil, zero value otherwise.

### GetBaseOk

`func (o *FreeToolCalculateEngagementRateRequest) GetBaseOk() (*int32, bool)`

GetBaseOk returns a tuple with the Base field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBase

`func (o *FreeToolCalculateEngagementRateRequest) SetBase(v int32)`

SetBase sets Base field to given value.


### GetPosts

`func (o *FreeToolCalculateEngagementRateRequest) GetPosts() int32`

GetPosts returns the Posts field if non-nil, zero value otherwise.

### GetPostsOk

`func (o *FreeToolCalculateEngagementRateRequest) GetPostsOk() (*int32, bool)`

GetPostsOk returns a tuple with the Posts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosts

`func (o *FreeToolCalculateEngagementRateRequest) SetPosts(v int32)`

SetPosts sets Posts field to given value.

### HasPosts

`func (o *FreeToolCalculateEngagementRateRequest) HasPosts() bool`

HasPosts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


