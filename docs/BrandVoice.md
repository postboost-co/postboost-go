# BrandVoice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BusinessName** | Pointer to **NullableString** |  | [optional] 
**Mission** | Pointer to **NullableString** |  | [optional] 
**Industry** | Pointer to **NullableString** |  | [optional] 
**Personality** | Pointer to **NullableString** |  | [optional] 
**Audience** | Pointer to **[]string** |  | [optional] 
**TopicsPreferred** | Pointer to **[]string** |  | [optional] 
**TopicsAvoided** | Pointer to **[]string** |  | [optional] 
**ToneFormal** | **int32** |  | 
**TonePlayful** | **int32** |  | 
**ToneTechnical** | **int32** |  | 
**EmojiStyle** | **string** |  | 
**HashtagStrategy** | **string** |  | 
**AvoidWords** | Pointer to **[]string** |  | [optional] 
**PreferredCta** | Pointer to **[]string** |  | [optional] 
**ExamplePosts** | Pointer to **[]string** |  | [optional] 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewBrandVoice

`func NewBrandVoice(toneFormal int32, tonePlayful int32, toneTechnical int32, emojiStyle string, hashtagStrategy string, ) *BrandVoice`

NewBrandVoice instantiates a new BrandVoice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBrandVoiceWithDefaults

`func NewBrandVoiceWithDefaults() *BrandVoice`

NewBrandVoiceWithDefaults instantiates a new BrandVoice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBusinessName

`func (o *BrandVoice) GetBusinessName() string`

GetBusinessName returns the BusinessName field if non-nil, zero value otherwise.

### GetBusinessNameOk

`func (o *BrandVoice) GetBusinessNameOk() (*string, bool)`

GetBusinessNameOk returns a tuple with the BusinessName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessName

`func (o *BrandVoice) SetBusinessName(v string)`

SetBusinessName sets BusinessName field to given value.

### HasBusinessName

`func (o *BrandVoice) HasBusinessName() bool`

HasBusinessName returns a boolean if a field has been set.

### SetBusinessNameNil

`func (o *BrandVoice) SetBusinessNameNil(b bool)`

 SetBusinessNameNil sets the value for BusinessName to be an explicit nil

### UnsetBusinessName
`func (o *BrandVoice) UnsetBusinessName()`

UnsetBusinessName ensures that no value is present for BusinessName, not even an explicit nil
### GetMission

`func (o *BrandVoice) GetMission() string`

GetMission returns the Mission field if non-nil, zero value otherwise.

### GetMissionOk

`func (o *BrandVoice) GetMissionOk() (*string, bool)`

GetMissionOk returns a tuple with the Mission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMission

`func (o *BrandVoice) SetMission(v string)`

SetMission sets Mission field to given value.

### HasMission

`func (o *BrandVoice) HasMission() bool`

HasMission returns a boolean if a field has been set.

### SetMissionNil

`func (o *BrandVoice) SetMissionNil(b bool)`

 SetMissionNil sets the value for Mission to be an explicit nil

### UnsetMission
`func (o *BrandVoice) UnsetMission()`

UnsetMission ensures that no value is present for Mission, not even an explicit nil
### GetIndustry

`func (o *BrandVoice) GetIndustry() string`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *BrandVoice) GetIndustryOk() (*string, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *BrandVoice) SetIndustry(v string)`

SetIndustry sets Industry field to given value.

### HasIndustry

`func (o *BrandVoice) HasIndustry() bool`

HasIndustry returns a boolean if a field has been set.

### SetIndustryNil

`func (o *BrandVoice) SetIndustryNil(b bool)`

 SetIndustryNil sets the value for Industry to be an explicit nil

### UnsetIndustry
`func (o *BrandVoice) UnsetIndustry()`

UnsetIndustry ensures that no value is present for Industry, not even an explicit nil
### GetPersonality

`func (o *BrandVoice) GetPersonality() string`

GetPersonality returns the Personality field if non-nil, zero value otherwise.

### GetPersonalityOk

`func (o *BrandVoice) GetPersonalityOk() (*string, bool)`

GetPersonalityOk returns a tuple with the Personality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonality

`func (o *BrandVoice) SetPersonality(v string)`

SetPersonality sets Personality field to given value.

### HasPersonality

`func (o *BrandVoice) HasPersonality() bool`

HasPersonality returns a boolean if a field has been set.

### SetPersonalityNil

`func (o *BrandVoice) SetPersonalityNil(b bool)`

 SetPersonalityNil sets the value for Personality to be an explicit nil

### UnsetPersonality
`func (o *BrandVoice) UnsetPersonality()`

UnsetPersonality ensures that no value is present for Personality, not even an explicit nil
### GetAudience

`func (o *BrandVoice) GetAudience() []string`

GetAudience returns the Audience field if non-nil, zero value otherwise.

### GetAudienceOk

`func (o *BrandVoice) GetAudienceOk() (*[]string, bool)`

GetAudienceOk returns a tuple with the Audience field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAudience

`func (o *BrandVoice) SetAudience(v []string)`

SetAudience sets Audience field to given value.

### HasAudience

`func (o *BrandVoice) HasAudience() bool`

HasAudience returns a boolean if a field has been set.

### GetTopicsPreferred

`func (o *BrandVoice) GetTopicsPreferred() []string`

GetTopicsPreferred returns the TopicsPreferred field if non-nil, zero value otherwise.

### GetTopicsPreferredOk

`func (o *BrandVoice) GetTopicsPreferredOk() (*[]string, bool)`

GetTopicsPreferredOk returns a tuple with the TopicsPreferred field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopicsPreferred

`func (o *BrandVoice) SetTopicsPreferred(v []string)`

SetTopicsPreferred sets TopicsPreferred field to given value.

### HasTopicsPreferred

`func (o *BrandVoice) HasTopicsPreferred() bool`

HasTopicsPreferred returns a boolean if a field has been set.

### GetTopicsAvoided

`func (o *BrandVoice) GetTopicsAvoided() []string`

GetTopicsAvoided returns the TopicsAvoided field if non-nil, zero value otherwise.

### GetTopicsAvoidedOk

`func (o *BrandVoice) GetTopicsAvoidedOk() (*[]string, bool)`

GetTopicsAvoidedOk returns a tuple with the TopicsAvoided field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopicsAvoided

`func (o *BrandVoice) SetTopicsAvoided(v []string)`

SetTopicsAvoided sets TopicsAvoided field to given value.

### HasTopicsAvoided

`func (o *BrandVoice) HasTopicsAvoided() bool`

HasTopicsAvoided returns a boolean if a field has been set.

### GetToneFormal

`func (o *BrandVoice) GetToneFormal() int32`

GetToneFormal returns the ToneFormal field if non-nil, zero value otherwise.

### GetToneFormalOk

`func (o *BrandVoice) GetToneFormalOk() (*int32, bool)`

GetToneFormalOk returns a tuple with the ToneFormal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToneFormal

`func (o *BrandVoice) SetToneFormal(v int32)`

SetToneFormal sets ToneFormal field to given value.


### GetTonePlayful

`func (o *BrandVoice) GetTonePlayful() int32`

GetTonePlayful returns the TonePlayful field if non-nil, zero value otherwise.

### GetTonePlayfulOk

`func (o *BrandVoice) GetTonePlayfulOk() (*int32, bool)`

GetTonePlayfulOk returns a tuple with the TonePlayful field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTonePlayful

`func (o *BrandVoice) SetTonePlayful(v int32)`

SetTonePlayful sets TonePlayful field to given value.


### GetToneTechnical

`func (o *BrandVoice) GetToneTechnical() int32`

GetToneTechnical returns the ToneTechnical field if non-nil, zero value otherwise.

### GetToneTechnicalOk

`func (o *BrandVoice) GetToneTechnicalOk() (*int32, bool)`

GetToneTechnicalOk returns a tuple with the ToneTechnical field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToneTechnical

`func (o *BrandVoice) SetToneTechnical(v int32)`

SetToneTechnical sets ToneTechnical field to given value.


### GetEmojiStyle

`func (o *BrandVoice) GetEmojiStyle() string`

GetEmojiStyle returns the EmojiStyle field if non-nil, zero value otherwise.

### GetEmojiStyleOk

`func (o *BrandVoice) GetEmojiStyleOk() (*string, bool)`

GetEmojiStyleOk returns a tuple with the EmojiStyle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmojiStyle

`func (o *BrandVoice) SetEmojiStyle(v string)`

SetEmojiStyle sets EmojiStyle field to given value.


### GetHashtagStrategy

`func (o *BrandVoice) GetHashtagStrategy() string`

GetHashtagStrategy returns the HashtagStrategy field if non-nil, zero value otherwise.

### GetHashtagStrategyOk

`func (o *BrandVoice) GetHashtagStrategyOk() (*string, bool)`

GetHashtagStrategyOk returns a tuple with the HashtagStrategy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHashtagStrategy

`func (o *BrandVoice) SetHashtagStrategy(v string)`

SetHashtagStrategy sets HashtagStrategy field to given value.


### GetAvoidWords

`func (o *BrandVoice) GetAvoidWords() []string`

GetAvoidWords returns the AvoidWords field if non-nil, zero value otherwise.

### GetAvoidWordsOk

`func (o *BrandVoice) GetAvoidWordsOk() (*[]string, bool)`

GetAvoidWordsOk returns a tuple with the AvoidWords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvoidWords

`func (o *BrandVoice) SetAvoidWords(v []string)`

SetAvoidWords sets AvoidWords field to given value.

### HasAvoidWords

`func (o *BrandVoice) HasAvoidWords() bool`

HasAvoidWords returns a boolean if a field has been set.

### GetPreferredCta

`func (o *BrandVoice) GetPreferredCta() []string`

GetPreferredCta returns the PreferredCta field if non-nil, zero value otherwise.

### GetPreferredCtaOk

`func (o *BrandVoice) GetPreferredCtaOk() (*[]string, bool)`

GetPreferredCtaOk returns a tuple with the PreferredCta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreferredCta

`func (o *BrandVoice) SetPreferredCta(v []string)`

SetPreferredCta sets PreferredCta field to given value.

### HasPreferredCta

`func (o *BrandVoice) HasPreferredCta() bool`

HasPreferredCta returns a boolean if a field has been set.

### GetExamplePosts

`func (o *BrandVoice) GetExamplePosts() []*string`

GetExamplePosts returns the ExamplePosts field if non-nil, zero value otherwise.

### GetExamplePostsOk

`func (o *BrandVoice) GetExamplePostsOk() (*[]*string, bool)`

GetExamplePostsOk returns a tuple with the ExamplePosts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExamplePosts

`func (o *BrandVoice) SetExamplePosts(v []*string)`

SetExamplePosts sets ExamplePosts field to given value.

### HasExamplePosts

`func (o *BrandVoice) HasExamplePosts() bool`

HasExamplePosts returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *BrandVoice) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *BrandVoice) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *BrandVoice) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *BrandVoice) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *BrandVoice) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *BrandVoice) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


