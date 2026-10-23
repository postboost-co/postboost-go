# FreeToolGenerateBrandVoiceResponseVoice

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BusinessName** | Pointer to **NullableString** | Your input, or null. | [optional] 
**Mission** | Pointer to **NullableString** | Only when the posts state it, else null. | [optional] 
**Industry** | Pointer to **NullableString** | Your input, or null. | [optional] 
**Personality** | Pointer to **string** | How the brand sounds. | [optional] 
**Audience** | Pointer to **[]string** | Who the posts speak to. At most 8 items. | [optional] 
**TopicsPreferred** | Pointer to **[]string** | Topics the posts come back to. At most 8 items. | [optional] 
**TopicsAvoided** | Pointer to **[]string** | Topics the posts clearly steer away from; often empty. At most 8 items. | [optional] 
**ToneFormal** | Pointer to **int32** | 1 very casual to 5 very formal, 3 neutral. | [optional] 
**TonePlayful** | Pointer to **int32** | 1 very serious to 5 very playful, 3 neutral. | [optional] 
**ToneTechnical** | Pointer to **int32** | 1 very simple to 5 very technical, 3 neutral. | [optional] 
**EmojiStyle** | Pointer to **string** |  | [optional] 
**HashtagStrategy** | Pointer to **string** |  | [optional] 
**AvoidWords** | Pointer to **[]string** | Words the posts clearly avoid; often empty. At most 8 items. | [optional] 
**PreferredCta** | Pointer to **[]string** | Calls to action the posts use. At most 8 items. | [optional] 
**ExamplePosts** | Pointer to **[]string** | Up to 5 of your posts that sound most typical, exactly as given. | [optional] 

## Methods

### NewFreeToolGenerateBrandVoiceResponseVoice

`func NewFreeToolGenerateBrandVoiceResponseVoice() *FreeToolGenerateBrandVoiceResponseVoice`

NewFreeToolGenerateBrandVoiceResponseVoice instantiates a new FreeToolGenerateBrandVoiceResponseVoice object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateBrandVoiceResponseVoiceWithDefaults

`func NewFreeToolGenerateBrandVoiceResponseVoiceWithDefaults() *FreeToolGenerateBrandVoiceResponseVoice`

NewFreeToolGenerateBrandVoiceResponseVoiceWithDefaults instantiates a new FreeToolGenerateBrandVoiceResponseVoice object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBusinessName

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetBusinessName() string`

GetBusinessName returns the BusinessName field if non-nil, zero value otherwise.

### GetBusinessNameOk

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetBusinessNameOk() (*string, bool)`

GetBusinessNameOk returns a tuple with the BusinessName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessName

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetBusinessName(v string)`

SetBusinessName sets BusinessName field to given value.

### HasBusinessName

`func (o *FreeToolGenerateBrandVoiceResponseVoice) HasBusinessName() bool`

HasBusinessName returns a boolean if a field has been set.

### SetBusinessNameNil

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetBusinessNameNil(b bool)`

 SetBusinessNameNil sets the value for BusinessName to be an explicit nil

### UnsetBusinessName
`func (o *FreeToolGenerateBrandVoiceResponseVoice) UnsetBusinessName()`

UnsetBusinessName ensures that no value is present for BusinessName, not even an explicit nil
### GetMission

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetMission() string`

GetMission returns the Mission field if non-nil, zero value otherwise.

### GetMissionOk

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetMissionOk() (*string, bool)`

GetMissionOk returns a tuple with the Mission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMission

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetMission(v string)`

SetMission sets Mission field to given value.

### HasMission

`func (o *FreeToolGenerateBrandVoiceResponseVoice) HasMission() bool`

HasMission returns a boolean if a field has been set.

### SetMissionNil

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetMissionNil(b bool)`

 SetMissionNil sets the value for Mission to be an explicit nil

### UnsetMission
`func (o *FreeToolGenerateBrandVoiceResponseVoice) UnsetMission()`

UnsetMission ensures that no value is present for Mission, not even an explicit nil
### GetIndustry

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetIndustry() string`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetIndustryOk() (*string, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetIndustry(v string)`

SetIndustry sets Industry field to given value.

### HasIndustry

`func (o *FreeToolGenerateBrandVoiceResponseVoice) HasIndustry() bool`

HasIndustry returns a boolean if a field has been set.

### SetIndustryNil

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetIndustryNil(b bool)`

 SetIndustryNil sets the value for Industry to be an explicit nil

### UnsetIndustry
`func (o *FreeToolGenerateBrandVoiceResponseVoice) UnsetIndustry()`

UnsetIndustry ensures that no value is present for Industry, not even an explicit nil
### GetPersonality

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetPersonality() string`

GetPersonality returns the Personality field if non-nil, zero value otherwise.

### GetPersonalityOk

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetPersonalityOk() (*string, bool)`

GetPersonalityOk returns a tuple with the Personality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonality

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetPersonality(v string)`

SetPersonality sets Personality field to given value.

### HasPersonality

`func (o *FreeToolGenerateBrandVoiceResponseVoice) HasPersonality() bool`

HasPersonality returns a boolean if a field has been set.

### GetAudience

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetAudience() []string`

GetAudience returns the Audience field if non-nil, zero value otherwise.

### GetAudienceOk

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetAudienceOk() (*[]string, bool)`

GetAudienceOk returns a tuple with the Audience field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAudience

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetAudience(v []string)`

SetAudience sets Audience field to given value.

### HasAudience

`func (o *FreeToolGenerateBrandVoiceResponseVoice) HasAudience() bool`

HasAudience returns a boolean if a field has been set.

### GetTopicsPreferred

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetTopicsPreferred() []string`

GetTopicsPreferred returns the TopicsPreferred field if non-nil, zero value otherwise.

### GetTopicsPreferredOk

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetTopicsPreferredOk() (*[]string, bool)`

GetTopicsPreferredOk returns a tuple with the TopicsPreferred field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopicsPreferred

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetTopicsPreferred(v []string)`

SetTopicsPreferred sets TopicsPreferred field to given value.

### HasTopicsPreferred

`func (o *FreeToolGenerateBrandVoiceResponseVoice) HasTopicsPreferred() bool`

HasTopicsPreferred returns a boolean if a field has been set.

### GetTopicsAvoided

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetTopicsAvoided() []string`

GetTopicsAvoided returns the TopicsAvoided field if non-nil, zero value otherwise.

### GetTopicsAvoidedOk

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetTopicsAvoidedOk() (*[]string, bool)`

GetTopicsAvoidedOk returns a tuple with the TopicsAvoided field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopicsAvoided

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetTopicsAvoided(v []string)`

SetTopicsAvoided sets TopicsAvoided field to given value.

### HasTopicsAvoided

`func (o *FreeToolGenerateBrandVoiceResponseVoice) HasTopicsAvoided() bool`

HasTopicsAvoided returns a boolean if a field has been set.

### GetToneFormal

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetToneFormal() int32`

GetToneFormal returns the ToneFormal field if non-nil, zero value otherwise.

### GetToneFormalOk

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetToneFormalOk() (*int32, bool)`

GetToneFormalOk returns a tuple with the ToneFormal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToneFormal

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetToneFormal(v int32)`

SetToneFormal sets ToneFormal field to given value.

### HasToneFormal

`func (o *FreeToolGenerateBrandVoiceResponseVoice) HasToneFormal() bool`

HasToneFormal returns a boolean if a field has been set.

### GetTonePlayful

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetTonePlayful() int32`

GetTonePlayful returns the TonePlayful field if non-nil, zero value otherwise.

### GetTonePlayfulOk

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetTonePlayfulOk() (*int32, bool)`

GetTonePlayfulOk returns a tuple with the TonePlayful field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTonePlayful

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetTonePlayful(v int32)`

SetTonePlayful sets TonePlayful field to given value.

### HasTonePlayful

`func (o *FreeToolGenerateBrandVoiceResponseVoice) HasTonePlayful() bool`

HasTonePlayful returns a boolean if a field has been set.

### GetToneTechnical

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetToneTechnical() int32`

GetToneTechnical returns the ToneTechnical field if non-nil, zero value otherwise.

### GetToneTechnicalOk

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetToneTechnicalOk() (*int32, bool)`

GetToneTechnicalOk returns a tuple with the ToneTechnical field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToneTechnical

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetToneTechnical(v int32)`

SetToneTechnical sets ToneTechnical field to given value.

### HasToneTechnical

`func (o *FreeToolGenerateBrandVoiceResponseVoice) HasToneTechnical() bool`

HasToneTechnical returns a boolean if a field has been set.

### GetEmojiStyle

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetEmojiStyle() string`

GetEmojiStyle returns the EmojiStyle field if non-nil, zero value otherwise.

### GetEmojiStyleOk

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetEmojiStyleOk() (*string, bool)`

GetEmojiStyleOk returns a tuple with the EmojiStyle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmojiStyle

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetEmojiStyle(v string)`

SetEmojiStyle sets EmojiStyle field to given value.

### HasEmojiStyle

`func (o *FreeToolGenerateBrandVoiceResponseVoice) HasEmojiStyle() bool`

HasEmojiStyle returns a boolean if a field has been set.

### GetHashtagStrategy

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetHashtagStrategy() string`

GetHashtagStrategy returns the HashtagStrategy field if non-nil, zero value otherwise.

### GetHashtagStrategyOk

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetHashtagStrategyOk() (*string, bool)`

GetHashtagStrategyOk returns a tuple with the HashtagStrategy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHashtagStrategy

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetHashtagStrategy(v string)`

SetHashtagStrategy sets HashtagStrategy field to given value.

### HasHashtagStrategy

`func (o *FreeToolGenerateBrandVoiceResponseVoice) HasHashtagStrategy() bool`

HasHashtagStrategy returns a boolean if a field has been set.

### GetAvoidWords

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetAvoidWords() []string`

GetAvoidWords returns the AvoidWords field if non-nil, zero value otherwise.

### GetAvoidWordsOk

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetAvoidWordsOk() (*[]string, bool)`

GetAvoidWordsOk returns a tuple with the AvoidWords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvoidWords

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetAvoidWords(v []string)`

SetAvoidWords sets AvoidWords field to given value.

### HasAvoidWords

`func (o *FreeToolGenerateBrandVoiceResponseVoice) HasAvoidWords() bool`

HasAvoidWords returns a boolean if a field has been set.

### GetPreferredCta

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetPreferredCta() []string`

GetPreferredCta returns the PreferredCta field if non-nil, zero value otherwise.

### GetPreferredCtaOk

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetPreferredCtaOk() (*[]string, bool)`

GetPreferredCtaOk returns a tuple with the PreferredCta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreferredCta

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetPreferredCta(v []string)`

SetPreferredCta sets PreferredCta field to given value.

### HasPreferredCta

`func (o *FreeToolGenerateBrandVoiceResponseVoice) HasPreferredCta() bool`

HasPreferredCta returns a boolean if a field has been set.

### GetExamplePosts

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetExamplePosts() []string`

GetExamplePosts returns the ExamplePosts field if non-nil, zero value otherwise.

### GetExamplePostsOk

`func (o *FreeToolGenerateBrandVoiceResponseVoice) GetExamplePostsOk() (*[]string, bool)`

GetExamplePostsOk returns a tuple with the ExamplePosts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExamplePosts

`func (o *FreeToolGenerateBrandVoiceResponseVoice) SetExamplePosts(v []string)`

SetExamplePosts sets ExamplePosts field to given value.

### HasExamplePosts

`func (o *FreeToolGenerateBrandVoiceResponseVoice) HasExamplePosts() bool`

HasExamplePosts returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


