# FreeToolPickSocialMediaToolResponseResultsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Slug** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**Score** | Pointer to **int32** | How many of your needs the tool meets. | [optional] 
**Matched** | Pointer to **[]string** |  | [optional] 
**Missing** | Pointer to **[]string** |  | [optional] 
**Unknown** | Pointer to **[]string** | Needs the tool&#39;s public docs did not show either way (\&quot;not documented\&quot;). | [optional] 
**CompareUrl** | Pointer to **NullableString** | Path of the full PostBoost comparison page; null for PostBoost. | [optional] 
**CheckedAt** | Pointer to **string** | When the tool&#39;s data was last checked. | [optional] 
**PickIf** | Pointer to **NullableString** | When this tool is the better choice; null for PostBoost. | [optional] 
**PostboostIf** | Pointer to **NullableString** | When PostBoost is the better choice; null for PostBoost. | [optional] 

## Methods

### NewFreeToolPickSocialMediaToolResponseResultsInner

`func NewFreeToolPickSocialMediaToolResponseResultsInner() *FreeToolPickSocialMediaToolResponseResultsInner`

NewFreeToolPickSocialMediaToolResponseResultsInner instantiates a new FreeToolPickSocialMediaToolResponseResultsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolPickSocialMediaToolResponseResultsInnerWithDefaults

`func NewFreeToolPickSocialMediaToolResponseResultsInnerWithDefaults() *FreeToolPickSocialMediaToolResponseResultsInner`

NewFreeToolPickSocialMediaToolResponseResultsInnerWithDefaults instantiates a new FreeToolPickSocialMediaToolResponseResultsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSlug

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) SetSlug(v string)`

SetSlug sets Slug field to given value.

### HasSlug

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) HasSlug() bool`

HasSlug returns a boolean if a field has been set.

### GetName

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) HasName() bool`

HasName returns a boolean if a field has been set.

### GetScore

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetScore() int32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetScoreOk() (*int32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) SetScore(v int32)`

SetScore sets Score field to given value.

### HasScore

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) HasScore() bool`

HasScore returns a boolean if a field has been set.

### GetMatched

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetMatched() []string`

GetMatched returns the Matched field if non-nil, zero value otherwise.

### GetMatchedOk

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetMatchedOk() (*[]string, bool)`

GetMatchedOk returns a tuple with the Matched field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMatched

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) SetMatched(v []string)`

SetMatched sets Matched field to given value.

### HasMatched

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) HasMatched() bool`

HasMatched returns a boolean if a field has been set.

### GetMissing

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetMissing() []string`

GetMissing returns the Missing field if non-nil, zero value otherwise.

### GetMissingOk

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetMissingOk() (*[]string, bool)`

GetMissingOk returns a tuple with the Missing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMissing

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) SetMissing(v []string)`

SetMissing sets Missing field to given value.

### HasMissing

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) HasMissing() bool`

HasMissing returns a boolean if a field has been set.

### GetUnknown

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetUnknown() []string`

GetUnknown returns the Unknown field if non-nil, zero value otherwise.

### GetUnknownOk

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetUnknownOk() (*[]string, bool)`

GetUnknownOk returns a tuple with the Unknown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnknown

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) SetUnknown(v []string)`

SetUnknown sets Unknown field to given value.

### HasUnknown

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) HasUnknown() bool`

HasUnknown returns a boolean if a field has been set.

### GetCompareUrl

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetCompareUrl() string`

GetCompareUrl returns the CompareUrl field if non-nil, zero value otherwise.

### GetCompareUrlOk

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetCompareUrlOk() (*string, bool)`

GetCompareUrlOk returns a tuple with the CompareUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompareUrl

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) SetCompareUrl(v string)`

SetCompareUrl sets CompareUrl field to given value.

### HasCompareUrl

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) HasCompareUrl() bool`

HasCompareUrl returns a boolean if a field has been set.

### SetCompareUrlNil

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) SetCompareUrlNil(b bool)`

 SetCompareUrlNil sets the value for CompareUrl to be an explicit nil

### UnsetCompareUrl
`func (o *FreeToolPickSocialMediaToolResponseResultsInner) UnsetCompareUrl()`

UnsetCompareUrl ensures that no value is present for CompareUrl, not even an explicit nil
### GetCheckedAt

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetCheckedAt() string`

GetCheckedAt returns the CheckedAt field if non-nil, zero value otherwise.

### GetCheckedAtOk

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetCheckedAtOk() (*string, bool)`

GetCheckedAtOk returns a tuple with the CheckedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckedAt

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) SetCheckedAt(v string)`

SetCheckedAt sets CheckedAt field to given value.

### HasCheckedAt

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) HasCheckedAt() bool`

HasCheckedAt returns a boolean if a field has been set.

### GetPickIf

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetPickIf() string`

GetPickIf returns the PickIf field if non-nil, zero value otherwise.

### GetPickIfOk

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetPickIfOk() (*string, bool)`

GetPickIfOk returns a tuple with the PickIf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPickIf

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) SetPickIf(v string)`

SetPickIf sets PickIf field to given value.

### HasPickIf

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) HasPickIf() bool`

HasPickIf returns a boolean if a field has been set.

### SetPickIfNil

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) SetPickIfNil(b bool)`

 SetPickIfNil sets the value for PickIf to be an explicit nil

### UnsetPickIf
`func (o *FreeToolPickSocialMediaToolResponseResultsInner) UnsetPickIf()`

UnsetPickIf ensures that no value is present for PickIf, not even an explicit nil
### GetPostboostIf

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetPostboostIf() string`

GetPostboostIf returns the PostboostIf field if non-nil, zero value otherwise.

### GetPostboostIfOk

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) GetPostboostIfOk() (*string, bool)`

GetPostboostIfOk returns a tuple with the PostboostIf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostboostIf

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) SetPostboostIf(v string)`

SetPostboostIf sets PostboostIf field to given value.

### HasPostboostIf

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) HasPostboostIf() bool`

HasPostboostIf returns a boolean if a field has been set.

### SetPostboostIfNil

`func (o *FreeToolPickSocialMediaToolResponseResultsInner) SetPostboostIfNil(b bool)`

 SetPostboostIfNil sets the value for PostboostIf to be an explicit nil

### UnsetPostboostIf
`func (o *FreeToolPickSocialMediaToolResponseResultsInner) UnsetPostboostIf()`

UnsetPostboostIf ensures that no value is present for PostboostIf, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


