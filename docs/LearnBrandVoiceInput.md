# LearnBrandVoiceInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Limit** | Pointer to **int32** | How many of the latest published posts to read. | [optional] [default to 10]
**AccountIds** | Pointer to **[]int32** | Only read posts whose accounts are all among these. | [optional] 
**Apply** | Pointer to **bool** | Save the proposed voice as the workspace brand voice. | [optional] [default to false]
**Overwrite** | Pointer to **bool** | Let learned values replace fields that are already set. | [optional] [default to false]

## Methods

### NewLearnBrandVoiceInput

`func NewLearnBrandVoiceInput() *LearnBrandVoiceInput`

NewLearnBrandVoiceInput instantiates a new LearnBrandVoiceInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLearnBrandVoiceInputWithDefaults

`func NewLearnBrandVoiceInputWithDefaults() *LearnBrandVoiceInput`

NewLearnBrandVoiceInputWithDefaults instantiates a new LearnBrandVoiceInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLimit

`func (o *LearnBrandVoiceInput) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *LearnBrandVoiceInput) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *LearnBrandVoiceInput) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *LearnBrandVoiceInput) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetAccountIds

`func (o *LearnBrandVoiceInput) GetAccountIds() []int32`

GetAccountIds returns the AccountIds field if non-nil, zero value otherwise.

### GetAccountIdsOk

`func (o *LearnBrandVoiceInput) GetAccountIdsOk() (*[]int32, bool)`

GetAccountIdsOk returns a tuple with the AccountIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountIds

`func (o *LearnBrandVoiceInput) SetAccountIds(v []int32)`

SetAccountIds sets AccountIds field to given value.

### HasAccountIds

`func (o *LearnBrandVoiceInput) HasAccountIds() bool`

HasAccountIds returns a boolean if a field has been set.

### GetApply

`func (o *LearnBrandVoiceInput) GetApply() bool`

GetApply returns the Apply field if non-nil, zero value otherwise.

### GetApplyOk

`func (o *LearnBrandVoiceInput) GetApplyOk() (*bool, bool)`

GetApplyOk returns a tuple with the Apply field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApply

`func (o *LearnBrandVoiceInput) SetApply(v bool)`

SetApply sets Apply field to given value.

### HasApply

`func (o *LearnBrandVoiceInput) HasApply() bool`

HasApply returns a boolean if a field has been set.

### GetOverwrite

`func (o *LearnBrandVoiceInput) GetOverwrite() bool`

GetOverwrite returns the Overwrite field if non-nil, zero value otherwise.

### GetOverwriteOk

`func (o *LearnBrandVoiceInput) GetOverwriteOk() (*bool, bool)`

GetOverwriteOk returns a tuple with the Overwrite field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverwrite

`func (o *LearnBrandVoiceInput) SetOverwrite(v bool)`

SetOverwrite sets Overwrite field to given value.

### HasOverwrite

`func (o *LearnBrandVoiceInput) HasOverwrite() bool`

HasOverwrite returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


