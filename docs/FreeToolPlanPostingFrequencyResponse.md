# FreeToolPlanPostingFrequencyResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PostsPerWeekCapacity** | Pointer to **int32** |  | [optional] 
**SumOfMinimums** | Pointer to **int32** | The recommended minimums of the chosen networks added up. | [optional] 
**Networks** | Pointer to [**[]FreeToolPlanPostingFrequencyResponseNetworksInner**](FreeToolPlanPostingFrequencyResponseNetworksInner.md) | One row per chosen network, in a fixed network order. | [optional] 
**Slots** | Pointer to [**[]FreeToolPlanPostingFrequencyResponseSlotsInner**](FreeToolPlanPostingFrequencyResponseSlotsInner.md) | The weekly grid: each network&#39;s posts spread evenly from Monday, sorted by day. | [optional] 
**Warnings** | Pointer to **[]string** |  | [optional] 
**LastVerified** | Pointer to **string** | When the ranges were last checked against their sources. | [optional] 

## Methods

### NewFreeToolPlanPostingFrequencyResponse

`func NewFreeToolPlanPostingFrequencyResponse() *FreeToolPlanPostingFrequencyResponse`

NewFreeToolPlanPostingFrequencyResponse instantiates a new FreeToolPlanPostingFrequencyResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolPlanPostingFrequencyResponseWithDefaults

`func NewFreeToolPlanPostingFrequencyResponseWithDefaults() *FreeToolPlanPostingFrequencyResponse`

NewFreeToolPlanPostingFrequencyResponseWithDefaults instantiates a new FreeToolPlanPostingFrequencyResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPostsPerWeekCapacity

`func (o *FreeToolPlanPostingFrequencyResponse) GetPostsPerWeekCapacity() int32`

GetPostsPerWeekCapacity returns the PostsPerWeekCapacity field if non-nil, zero value otherwise.

### GetPostsPerWeekCapacityOk

`func (o *FreeToolPlanPostingFrequencyResponse) GetPostsPerWeekCapacityOk() (*int32, bool)`

GetPostsPerWeekCapacityOk returns a tuple with the PostsPerWeekCapacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostsPerWeekCapacity

`func (o *FreeToolPlanPostingFrequencyResponse) SetPostsPerWeekCapacity(v int32)`

SetPostsPerWeekCapacity sets PostsPerWeekCapacity field to given value.

### HasPostsPerWeekCapacity

`func (o *FreeToolPlanPostingFrequencyResponse) HasPostsPerWeekCapacity() bool`

HasPostsPerWeekCapacity returns a boolean if a field has been set.

### GetSumOfMinimums

`func (o *FreeToolPlanPostingFrequencyResponse) GetSumOfMinimums() int32`

GetSumOfMinimums returns the SumOfMinimums field if non-nil, zero value otherwise.

### GetSumOfMinimumsOk

`func (o *FreeToolPlanPostingFrequencyResponse) GetSumOfMinimumsOk() (*int32, bool)`

GetSumOfMinimumsOk returns a tuple with the SumOfMinimums field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSumOfMinimums

`func (o *FreeToolPlanPostingFrequencyResponse) SetSumOfMinimums(v int32)`

SetSumOfMinimums sets SumOfMinimums field to given value.

### HasSumOfMinimums

`func (o *FreeToolPlanPostingFrequencyResponse) HasSumOfMinimums() bool`

HasSumOfMinimums returns a boolean if a field has been set.

### GetNetworks

`func (o *FreeToolPlanPostingFrequencyResponse) GetNetworks() []FreeToolPlanPostingFrequencyResponseNetworksInner`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *FreeToolPlanPostingFrequencyResponse) GetNetworksOk() (*[]FreeToolPlanPostingFrequencyResponseNetworksInner, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *FreeToolPlanPostingFrequencyResponse) SetNetworks(v []FreeToolPlanPostingFrequencyResponseNetworksInner)`

SetNetworks sets Networks field to given value.

### HasNetworks

`func (o *FreeToolPlanPostingFrequencyResponse) HasNetworks() bool`

HasNetworks returns a boolean if a field has been set.

### GetSlots

`func (o *FreeToolPlanPostingFrequencyResponse) GetSlots() []FreeToolPlanPostingFrequencyResponseSlotsInner`

GetSlots returns the Slots field if non-nil, zero value otherwise.

### GetSlotsOk

`func (o *FreeToolPlanPostingFrequencyResponse) GetSlotsOk() (*[]FreeToolPlanPostingFrequencyResponseSlotsInner, bool)`

GetSlotsOk returns a tuple with the Slots field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlots

`func (o *FreeToolPlanPostingFrequencyResponse) SetSlots(v []FreeToolPlanPostingFrequencyResponseSlotsInner)`

SetSlots sets Slots field to given value.

### HasSlots

`func (o *FreeToolPlanPostingFrequencyResponse) HasSlots() bool`

HasSlots returns a boolean if a field has been set.

### GetWarnings

`func (o *FreeToolPlanPostingFrequencyResponse) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *FreeToolPlanPostingFrequencyResponse) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *FreeToolPlanPostingFrequencyResponse) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *FreeToolPlanPostingFrequencyResponse) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.

### GetLastVerified

`func (o *FreeToolPlanPostingFrequencyResponse) GetLastVerified() string`

GetLastVerified returns the LastVerified field if non-nil, zero value otherwise.

### GetLastVerifiedOk

`func (o *FreeToolPlanPostingFrequencyResponse) GetLastVerifiedOk() (*string, bool)`

GetLastVerifiedOk returns a tuple with the LastVerified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastVerified

`func (o *FreeToolPlanPostingFrequencyResponse) SetLastVerified(v string)`

SetLastVerified sets LastVerified field to given value.

### HasLastVerified

`func (o *FreeToolPlanPostingFrequencyResponse) HasLastVerified() bool`

HasLastVerified returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


