# AnalyticsSummaryData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TotalFollowers** | Pointer to **int32** |  | [optional] 
**FollowerGrowth** | Pointer to **map[string]interface{}** | Growth in the period with the change against the previous period. | [optional] 
**TotalPosts** | Pointer to **map[string]interface{}** | Posts in the period with the change against the previous period. | [optional] 
**BestAccount** | Pointer to **map[string]interface{}** |  | [optional] 
**NeedsAttention** | Pointer to **map[string]interface{}** |  | [optional] 
**AudienceChart** | Pointer to **[]map[string]interface{}** |  | [optional] 
**Leaderboard** | Pointer to **[]map[string]interface{}** |  | [optional] 
**MostActive** | Pointer to **map[string]interface{}** |  | [optional] 
**LeastActive** | Pointer to **map[string]interface{}** |  | [optional] 
**FollowerDistribution** | Pointer to **[]map[string]interface{}** |  | [optional] 
**PostingStreak** | Pointer to **map[string]interface{}** |  | [optional] 

## Methods

### NewAnalyticsSummaryData

`func NewAnalyticsSummaryData() *AnalyticsSummaryData`

NewAnalyticsSummaryData instantiates a new AnalyticsSummaryData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAnalyticsSummaryDataWithDefaults

`func NewAnalyticsSummaryDataWithDefaults() *AnalyticsSummaryData`

NewAnalyticsSummaryDataWithDefaults instantiates a new AnalyticsSummaryData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotalFollowers

`func (o *AnalyticsSummaryData) GetTotalFollowers() int32`

GetTotalFollowers returns the TotalFollowers field if non-nil, zero value otherwise.

### GetTotalFollowersOk

`func (o *AnalyticsSummaryData) GetTotalFollowersOk() (*int32, bool)`

GetTotalFollowersOk returns a tuple with the TotalFollowers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalFollowers

`func (o *AnalyticsSummaryData) SetTotalFollowers(v int32)`

SetTotalFollowers sets TotalFollowers field to given value.

### HasTotalFollowers

`func (o *AnalyticsSummaryData) HasTotalFollowers() bool`

HasTotalFollowers returns a boolean if a field has been set.

### GetFollowerGrowth

`func (o *AnalyticsSummaryData) GetFollowerGrowth() map[string]interface{}`

GetFollowerGrowth returns the FollowerGrowth field if non-nil, zero value otherwise.

### GetFollowerGrowthOk

`func (o *AnalyticsSummaryData) GetFollowerGrowthOk() (*map[string]interface{}, bool)`

GetFollowerGrowthOk returns a tuple with the FollowerGrowth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFollowerGrowth

`func (o *AnalyticsSummaryData) SetFollowerGrowth(v map[string]interface{})`

SetFollowerGrowth sets FollowerGrowth field to given value.

### HasFollowerGrowth

`func (o *AnalyticsSummaryData) HasFollowerGrowth() bool`

HasFollowerGrowth returns a boolean if a field has been set.

### GetTotalPosts

`func (o *AnalyticsSummaryData) GetTotalPosts() map[string]interface{}`

GetTotalPosts returns the TotalPosts field if non-nil, zero value otherwise.

### GetTotalPostsOk

`func (o *AnalyticsSummaryData) GetTotalPostsOk() (*map[string]interface{}, bool)`

GetTotalPostsOk returns a tuple with the TotalPosts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPosts

`func (o *AnalyticsSummaryData) SetTotalPosts(v map[string]interface{})`

SetTotalPosts sets TotalPosts field to given value.

### HasTotalPosts

`func (o *AnalyticsSummaryData) HasTotalPosts() bool`

HasTotalPosts returns a boolean if a field has been set.

### GetBestAccount

`func (o *AnalyticsSummaryData) GetBestAccount() map[string]interface{}`

GetBestAccount returns the BestAccount field if non-nil, zero value otherwise.

### GetBestAccountOk

`func (o *AnalyticsSummaryData) GetBestAccountOk() (*map[string]interface{}, bool)`

GetBestAccountOk returns a tuple with the BestAccount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBestAccount

`func (o *AnalyticsSummaryData) SetBestAccount(v map[string]interface{})`

SetBestAccount sets BestAccount field to given value.

### HasBestAccount

`func (o *AnalyticsSummaryData) HasBestAccount() bool`

HasBestAccount returns a boolean if a field has been set.

### SetBestAccountNil

`func (o *AnalyticsSummaryData) SetBestAccountNil(b bool)`

 SetBestAccountNil sets the value for BestAccount to be an explicit nil

### UnsetBestAccount
`func (o *AnalyticsSummaryData) UnsetBestAccount()`

UnsetBestAccount ensures that no value is present for BestAccount, not even an explicit nil
### GetNeedsAttention

`func (o *AnalyticsSummaryData) GetNeedsAttention() map[string]interface{}`

GetNeedsAttention returns the NeedsAttention field if non-nil, zero value otherwise.

### GetNeedsAttentionOk

`func (o *AnalyticsSummaryData) GetNeedsAttentionOk() (*map[string]interface{}, bool)`

GetNeedsAttentionOk returns a tuple with the NeedsAttention field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNeedsAttention

`func (o *AnalyticsSummaryData) SetNeedsAttention(v map[string]interface{})`

SetNeedsAttention sets NeedsAttention field to given value.

### HasNeedsAttention

`func (o *AnalyticsSummaryData) HasNeedsAttention() bool`

HasNeedsAttention returns a boolean if a field has been set.

### SetNeedsAttentionNil

`func (o *AnalyticsSummaryData) SetNeedsAttentionNil(b bool)`

 SetNeedsAttentionNil sets the value for NeedsAttention to be an explicit nil

### UnsetNeedsAttention
`func (o *AnalyticsSummaryData) UnsetNeedsAttention()`

UnsetNeedsAttention ensures that no value is present for NeedsAttention, not even an explicit nil
### GetAudienceChart

`func (o *AnalyticsSummaryData) GetAudienceChart() []map[string]interface{}`

GetAudienceChart returns the AudienceChart field if non-nil, zero value otherwise.

### GetAudienceChartOk

`func (o *AnalyticsSummaryData) GetAudienceChartOk() (*[]map[string]interface{}, bool)`

GetAudienceChartOk returns a tuple with the AudienceChart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAudienceChart

`func (o *AnalyticsSummaryData) SetAudienceChart(v []map[string]interface{})`

SetAudienceChart sets AudienceChart field to given value.

### HasAudienceChart

`func (o *AnalyticsSummaryData) HasAudienceChart() bool`

HasAudienceChart returns a boolean if a field has been set.

### GetLeaderboard

`func (o *AnalyticsSummaryData) GetLeaderboard() []map[string]interface{}`

GetLeaderboard returns the Leaderboard field if non-nil, zero value otherwise.

### GetLeaderboardOk

`func (o *AnalyticsSummaryData) GetLeaderboardOk() (*[]map[string]interface{}, bool)`

GetLeaderboardOk returns a tuple with the Leaderboard field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeaderboard

`func (o *AnalyticsSummaryData) SetLeaderboard(v []map[string]interface{})`

SetLeaderboard sets Leaderboard field to given value.

### HasLeaderboard

`func (o *AnalyticsSummaryData) HasLeaderboard() bool`

HasLeaderboard returns a boolean if a field has been set.

### GetMostActive

`func (o *AnalyticsSummaryData) GetMostActive() map[string]interface{}`

GetMostActive returns the MostActive field if non-nil, zero value otherwise.

### GetMostActiveOk

`func (o *AnalyticsSummaryData) GetMostActiveOk() (*map[string]interface{}, bool)`

GetMostActiveOk returns a tuple with the MostActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMostActive

`func (o *AnalyticsSummaryData) SetMostActive(v map[string]interface{})`

SetMostActive sets MostActive field to given value.

### HasMostActive

`func (o *AnalyticsSummaryData) HasMostActive() bool`

HasMostActive returns a boolean if a field has been set.

### SetMostActiveNil

`func (o *AnalyticsSummaryData) SetMostActiveNil(b bool)`

 SetMostActiveNil sets the value for MostActive to be an explicit nil

### UnsetMostActive
`func (o *AnalyticsSummaryData) UnsetMostActive()`

UnsetMostActive ensures that no value is present for MostActive, not even an explicit nil
### GetLeastActive

`func (o *AnalyticsSummaryData) GetLeastActive() map[string]interface{}`

GetLeastActive returns the LeastActive field if non-nil, zero value otherwise.

### GetLeastActiveOk

`func (o *AnalyticsSummaryData) GetLeastActiveOk() (*map[string]interface{}, bool)`

GetLeastActiveOk returns a tuple with the LeastActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeastActive

`func (o *AnalyticsSummaryData) SetLeastActive(v map[string]interface{})`

SetLeastActive sets LeastActive field to given value.

### HasLeastActive

`func (o *AnalyticsSummaryData) HasLeastActive() bool`

HasLeastActive returns a boolean if a field has been set.

### SetLeastActiveNil

`func (o *AnalyticsSummaryData) SetLeastActiveNil(b bool)`

 SetLeastActiveNil sets the value for LeastActive to be an explicit nil

### UnsetLeastActive
`func (o *AnalyticsSummaryData) UnsetLeastActive()`

UnsetLeastActive ensures that no value is present for LeastActive, not even an explicit nil
### GetFollowerDistribution

`func (o *AnalyticsSummaryData) GetFollowerDistribution() []map[string]interface{}`

GetFollowerDistribution returns the FollowerDistribution field if non-nil, zero value otherwise.

### GetFollowerDistributionOk

`func (o *AnalyticsSummaryData) GetFollowerDistributionOk() (*[]map[string]interface{}, bool)`

GetFollowerDistributionOk returns a tuple with the FollowerDistribution field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFollowerDistribution

`func (o *AnalyticsSummaryData) SetFollowerDistribution(v []map[string]interface{})`

SetFollowerDistribution sets FollowerDistribution field to given value.

### HasFollowerDistribution

`func (o *AnalyticsSummaryData) HasFollowerDistribution() bool`

HasFollowerDistribution returns a boolean if a field has been set.

### GetPostingStreak

`func (o *AnalyticsSummaryData) GetPostingStreak() map[string]interface{}`

GetPostingStreak returns the PostingStreak field if non-nil, zero value otherwise.

### GetPostingStreakOk

`func (o *AnalyticsSummaryData) GetPostingStreakOk() (*map[string]interface{}, bool)`

GetPostingStreakOk returns a tuple with the PostingStreak field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostingStreak

`func (o *AnalyticsSummaryData) SetPostingStreak(v map[string]interface{})`

SetPostingStreak sets PostingStreak field to given value.

### HasPostingStreak

`func (o *AnalyticsSummaryData) HasPostingStreak() bool`

HasPostingStreak returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


