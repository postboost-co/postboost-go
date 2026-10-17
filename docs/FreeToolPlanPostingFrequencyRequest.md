# FreeToolPlanPostingFrequencyRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Networks** | **[]string** | The networks you post on. Bluesky and Mastodon are not offered: no published frequency we could verify. | 
**PostsPerWeekCapacity** | **int32** | How many posts your team can make in a week, across all networks. | 

## Methods

### NewFreeToolPlanPostingFrequencyRequest

`func NewFreeToolPlanPostingFrequencyRequest(networks []string, postsPerWeekCapacity int32, ) *FreeToolPlanPostingFrequencyRequest`

NewFreeToolPlanPostingFrequencyRequest instantiates a new FreeToolPlanPostingFrequencyRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolPlanPostingFrequencyRequestWithDefaults

`func NewFreeToolPlanPostingFrequencyRequestWithDefaults() *FreeToolPlanPostingFrequencyRequest`

NewFreeToolPlanPostingFrequencyRequestWithDefaults instantiates a new FreeToolPlanPostingFrequencyRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNetworks

`func (o *FreeToolPlanPostingFrequencyRequest) GetNetworks() []string`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *FreeToolPlanPostingFrequencyRequest) GetNetworksOk() (*[]string, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *FreeToolPlanPostingFrequencyRequest) SetNetworks(v []string)`

SetNetworks sets Networks field to given value.


### GetPostsPerWeekCapacity

`func (o *FreeToolPlanPostingFrequencyRequest) GetPostsPerWeekCapacity() int32`

GetPostsPerWeekCapacity returns the PostsPerWeekCapacity field if non-nil, zero value otherwise.

### GetPostsPerWeekCapacityOk

`func (o *FreeToolPlanPostingFrequencyRequest) GetPostsPerWeekCapacityOk() (*int32, bool)`

GetPostsPerWeekCapacityOk returns a tuple with the PostsPerWeekCapacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostsPerWeekCapacity

`func (o *FreeToolPlanPostingFrequencyRequest) SetPostsPerWeekCapacity(v int32)`

SetPostsPerWeekCapacity sets PostsPerWeekCapacity field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


