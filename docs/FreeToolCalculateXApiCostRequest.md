# FreeToolCalculateXApiCostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Posts** | Pointer to **int32** | Posts created per month, with or without a link. | [optional] [default to 0]
**LinkShare** | Pointer to **int32** | Percent of those posts that contain a URL (billed at the link-post price). | [optional] [default to 0]
**Replies** | Pointer to **int32** | Summoned replies per month. | [optional] [default to 0]
**PostReads** | Pointer to **int32** | Posts read per month. | [optional] [default to 0]
**UserReads** | Pointer to **int32** | Users read per month. | [optional] [default to 0]
**OwnedReads** | Pointer to **int32** | Owned resources read per month (your own posts, followers and so on). | [optional] [default to 0]

## Methods

### NewFreeToolCalculateXApiCostRequest

`func NewFreeToolCalculateXApiCostRequest() *FreeToolCalculateXApiCostRequest`

NewFreeToolCalculateXApiCostRequest instantiates a new FreeToolCalculateXApiCostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCalculateXApiCostRequestWithDefaults

`func NewFreeToolCalculateXApiCostRequestWithDefaults() *FreeToolCalculateXApiCostRequest`

NewFreeToolCalculateXApiCostRequestWithDefaults instantiates a new FreeToolCalculateXApiCostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPosts

`func (o *FreeToolCalculateXApiCostRequest) GetPosts() int32`

GetPosts returns the Posts field if non-nil, zero value otherwise.

### GetPostsOk

`func (o *FreeToolCalculateXApiCostRequest) GetPostsOk() (*int32, bool)`

GetPostsOk returns a tuple with the Posts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosts

`func (o *FreeToolCalculateXApiCostRequest) SetPosts(v int32)`

SetPosts sets Posts field to given value.

### HasPosts

`func (o *FreeToolCalculateXApiCostRequest) HasPosts() bool`

HasPosts returns a boolean if a field has been set.

### GetLinkShare

`func (o *FreeToolCalculateXApiCostRequest) GetLinkShare() int32`

GetLinkShare returns the LinkShare field if non-nil, zero value otherwise.

### GetLinkShareOk

`func (o *FreeToolCalculateXApiCostRequest) GetLinkShareOk() (*int32, bool)`

GetLinkShareOk returns a tuple with the LinkShare field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkShare

`func (o *FreeToolCalculateXApiCostRequest) SetLinkShare(v int32)`

SetLinkShare sets LinkShare field to given value.

### HasLinkShare

`func (o *FreeToolCalculateXApiCostRequest) HasLinkShare() bool`

HasLinkShare returns a boolean if a field has been set.

### GetReplies

`func (o *FreeToolCalculateXApiCostRequest) GetReplies() int32`

GetReplies returns the Replies field if non-nil, zero value otherwise.

### GetRepliesOk

`func (o *FreeToolCalculateXApiCostRequest) GetRepliesOk() (*int32, bool)`

GetRepliesOk returns a tuple with the Replies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplies

`func (o *FreeToolCalculateXApiCostRequest) SetReplies(v int32)`

SetReplies sets Replies field to given value.

### HasReplies

`func (o *FreeToolCalculateXApiCostRequest) HasReplies() bool`

HasReplies returns a boolean if a field has been set.

### GetPostReads

`func (o *FreeToolCalculateXApiCostRequest) GetPostReads() int32`

GetPostReads returns the PostReads field if non-nil, zero value otherwise.

### GetPostReadsOk

`func (o *FreeToolCalculateXApiCostRequest) GetPostReadsOk() (*int32, bool)`

GetPostReadsOk returns a tuple with the PostReads field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostReads

`func (o *FreeToolCalculateXApiCostRequest) SetPostReads(v int32)`

SetPostReads sets PostReads field to given value.

### HasPostReads

`func (o *FreeToolCalculateXApiCostRequest) HasPostReads() bool`

HasPostReads returns a boolean if a field has been set.

### GetUserReads

`func (o *FreeToolCalculateXApiCostRequest) GetUserReads() int32`

GetUserReads returns the UserReads field if non-nil, zero value otherwise.

### GetUserReadsOk

`func (o *FreeToolCalculateXApiCostRequest) GetUserReadsOk() (*int32, bool)`

GetUserReadsOk returns a tuple with the UserReads field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserReads

`func (o *FreeToolCalculateXApiCostRequest) SetUserReads(v int32)`

SetUserReads sets UserReads field to given value.

### HasUserReads

`func (o *FreeToolCalculateXApiCostRequest) HasUserReads() bool`

HasUserReads returns a boolean if a field has been set.

### GetOwnedReads

`func (o *FreeToolCalculateXApiCostRequest) GetOwnedReads() int32`

GetOwnedReads returns the OwnedReads field if non-nil, zero value otherwise.

### GetOwnedReadsOk

`func (o *FreeToolCalculateXApiCostRequest) GetOwnedReadsOk() (*int32, bool)`

GetOwnedReadsOk returns a tuple with the OwnedReads field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnedReads

`func (o *FreeToolCalculateXApiCostRequest) SetOwnedReads(v int32)`

SetOwnedReads sets OwnedReads field to given value.

### HasOwnedReads

`func (o *FreeToolCalculateXApiCostRequest) HasOwnedReads() bool`

HasOwnedReads returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


