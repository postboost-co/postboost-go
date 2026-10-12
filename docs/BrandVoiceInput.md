# BrandVoiceInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BusinessName** | Pointer to **NullableString** |  | [optional] 
**Mission** | Pointer to **NullableString** |  | [optional] 
**Industry** | Pointer to **NullableString** |  | [optional] 
**Personality** | Pointer to **NullableString** | How the brand sounds. The first sentence also feeds image prompts. | [optional] 
**Audience** | Pointer to **[]string** |  | [optional] 
**TopicsPreferred** | Pointer to **[]string** |  | [optional] 
**TopicsAvoided** | Pointer to **[]string** |  | [optional] 
**ToneFormal** | Pointer to **int32** | 1 very casual, 3 neutral, 5 very formal. | [optional] 
**TonePlayful** | Pointer to **int32** | 1 strictly serious, 3 neutral, 5 very playful. | [optional] 
**ToneTechnical** | Pointer to **int32** | 1 very simple, 3 neutral, 5 highly technical. | [optional] 
**EmojiStyle** | Pointer to **string** |  | [optional] 
**HashtagStrategy** | Pointer to **string** |  | [optional] 
**AvoidWords** | Pointer to **[]string** |  | [optional] 
**PreferredCta** | Pointer to **[]string** |  | [optional] 
**ExamplePosts** | Pointer to **[]string** |  | [optional] 

## Methods

### NewBrandVoiceInput

`func NewBrandVoiceInput() *BrandVoiceInput`

NewBrandVoiceInput instantiates a new BrandVoiceInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBrandVoiceInputWithDefaults

`func NewBrandVoiceInputWithDefaults() *BrandVoiceInput`

NewBrandVoiceInputWithDefaults instantiates a new BrandVoiceInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBusinessName

`func (o *BrandVoiceInput) GetBusinessName() string`

GetBusinessName returns the BusinessName field if non-nil, zero value otherwise.

### GetBusinessNameOk

`func (o *BrandVoiceInput) GetBusinessNameOk() (*string, bool)`

GetBusinessNameOk returns a tuple with the BusinessName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessName

`func (o *BrandVoiceInput) SetBusinessName(v string)`

SetBusinessName sets BusinessName field to given value.

### HasBusinessName

`func (o *BrandVoiceInput) HasBusinessName() bool`

HasBusinessName returns a boolean if a field has been set.

### SetBusinessNameNil

`func (o *BrandVoiceInput) SetBusinessNameNil(b bool)`

 SetBusinessNameNil sets the value for BusinessName to be an explicit nil

### UnsetBusinessName
`func (o *BrandVoiceInput) UnsetBusinessName()`

UnsetBusinessName ensures that no value is present for BusinessName, not even an explicit nil
### GetMission

`func (o *BrandVoiceInput) GetMission() string`

GetMission returns the Mission field if non-nil, zero value otherwise.

### GetMissionOk

`func (o *BrandVoiceInput) GetMissionOk() (*string, bool)`

GetMissionOk returns a tuple with the Mission field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMission

`func (o *BrandVoiceInput) SetMission(v string)`

SetMission sets Mission field to given value.

### HasMission

`func (o *BrandVoiceInput) HasMission() bool`

HasMission returns a boolean if a field has been set.

### SetMissionNil

`func (o *BrandVoiceInput) SetMissionNil(b bool)`

 SetMissionNil sets the value for Mission to be an explicit nil

### UnsetMission
`func (o *BrandVoiceInput) UnsetMission()`

UnsetMission ensures that no value is present for Mission, not even an explicit nil
### GetIndustry

`func (o *BrandVoiceInput) GetIndustry() string`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *BrandVoiceInput) GetIndustryOk() (*string, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *BrandVoiceInput) SetIndustry(v string)`

SetIndustry sets Industry field to given value.

### HasIndustry

`func (o *BrandVoiceInput) HasIndustry() bool`

HasIndustry returns a boolean if a field has been set.

### SetIndustryNil

`func (o *BrandVoiceInput) SetIndustryNil(b bool)`

 SetIndustryNil sets the value for Industry to be an explicit nil

### UnsetIndustry
`func (o *BrandVoiceInput) UnsetIndustry()`

UnsetIndustry ensures that no value is present for Industry, not even an explicit nil
### GetPersonality

`func (o *BrandVoiceInput) GetPersonality() string`

GetPersonality returns the Personality field if non-nil, zero value otherwise.

### GetPersonalityOk

`func (o *BrandVoiceInput) GetPersonalityOk() (*string, bool)`

GetPersonalityOk returns a tuple with the Personality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonality

`func (o *BrandVoiceInput) SetPersonality(v string)`

SetPersonality sets Personality field to given value.

### HasPersonality

`func (o *BrandVoiceInput) HasPersonality() bool`

HasPersonality returns a boolean if a field has been set.

### SetPersonalityNil

`func (o *BrandVoiceInput) SetPersonalityNil(b bool)`

 SetPersonalityNil sets the value for Personality to be an explicit nil

### UnsetPersonality
`func (o *BrandVoiceInput) UnsetPersonality()`

UnsetPersonality ensures that no value is present for Personality, not even an explicit nil
### GetAudience

`func (o *BrandVoiceInput) GetAudience() []string`

GetAudience returns the Audience field if non-nil, zero value otherwise.

### GetAudienceOk

`func (o *BrandVoiceInput) GetAudienceOk() (*[]string, bool)`

GetAudienceOk returns a tuple with the Audience field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAudience

`func (o *BrandVoiceInput) SetAudience(v []string)`

SetAudience sets Audience field to given value.

### HasAudience

`func (o *BrandVoiceInput) HasAudience() bool`

HasAudience returns a boolean if a field has been set.

### SetAudienceNil

`func (o *BrandVoiceInput) SetAudienceNil(b bool)`

 SetAudienceNil sets the value for Audience to be an explicit nil

### UnsetAudience
`func (o *BrandVoiceInput) UnsetAudience()`

UnsetAudience ensures that no value is present for Audience, not even an explicit nil
### GetTopicsPreferred

`func (o *BrandVoiceInput) GetTopicsPreferred() []string`

GetTopicsPreferred returns the TopicsPreferred field if non-nil, zero value otherwise.

### GetTopicsPreferredOk

`func (o *BrandVoiceInput) GetTopicsPreferredOk() (*[]string, bool)`

GetTopicsPreferredOk returns a tuple with the TopicsPreferred field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopicsPreferred

`func (o *BrandVoiceInput) SetTopicsPreferred(v []string)`

SetTopicsPreferred sets TopicsPreferred field to given value.

### HasTopicsPreferred

`func (o *BrandVoiceInput) HasTopicsPreferred() bool`

HasTopicsPreferred returns a boolean if a field has been set.

### SetTopicsPreferredNil

`func (o *BrandVoiceInput) SetTopicsPreferredNil(b bool)`

 SetTopicsPreferredNil sets the value for TopicsPreferred to be an explicit nil

### UnsetTopicsPreferred
`func (o *BrandVoiceInput) UnsetTopicsPreferred()`

UnsetTopicsPreferred ensures that no value is present for TopicsPreferred, not even an explicit nil
### GetTopicsAvoided

`func (o *BrandVoiceInput) GetTopicsAvoided() []string`

GetTopicsAvoided returns the TopicsAvoided field if non-nil, zero value otherwise.

### GetTopicsAvoidedOk

`func (o *BrandVoiceInput) GetTopicsAvoidedOk() (*[]string, bool)`

GetTopicsAvoidedOk returns a tuple with the TopicsAvoided field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopicsAvoided

`func (o *BrandVoiceInput) SetTopicsAvoided(v []string)`

SetTopicsAvoided sets TopicsAvoided field to given value.

### HasTopicsAvoided

`func (o *BrandVoiceInput) HasTopicsAvoided() bool`

HasTopicsAvoided returns a boolean if a field has been set.

### SetTopicsAvoidedNil

`func (o *BrandVoiceInput) SetTopicsAvoidedNil(b bool)`

 SetTopicsAvoidedNil sets the value for TopicsAvoided to be an explicit nil

### UnsetTopicsAvoided
`func (o *BrandVoiceInput) UnsetTopicsAvoided()`

UnsetTopicsAvoided ensures that no value is present for TopicsAvoided, not even an explicit nil
### GetToneFormal

`func (o *BrandVoiceInput) GetToneFormal() int32`

GetToneFormal returns the ToneFormal field if non-nil, zero value otherwise.

### GetToneFormalOk

`func (o *BrandVoiceInput) GetToneFormalOk() (*int32, bool)`

GetToneFormalOk returns a tuple with the ToneFormal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToneFormal

`func (o *BrandVoiceInput) SetToneFormal(v int32)`

SetToneFormal sets ToneFormal field to given value.

### HasToneFormal

`func (o *BrandVoiceInput) HasToneFormal() bool`

HasToneFormal returns a boolean if a field has been set.

### GetTonePlayful

`func (o *BrandVoiceInput) GetTonePlayful() int32`

GetTonePlayful returns the TonePlayful field if non-nil, zero value otherwise.

### GetTonePlayfulOk

`func (o *BrandVoiceInput) GetTonePlayfulOk() (*int32, bool)`

GetTonePlayfulOk returns a tuple with the TonePlayful field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTonePlayful

`func (o *BrandVoiceInput) SetTonePlayful(v int32)`

SetTonePlayful sets TonePlayful field to given value.

### HasTonePlayful

`func (o *BrandVoiceInput) HasTonePlayful() bool`

HasTonePlayful returns a boolean if a field has been set.

### GetToneTechnical

`func (o *BrandVoiceInput) GetToneTechnical() int32`

GetToneTechnical returns the ToneTechnical field if non-nil, zero value otherwise.

### GetToneTechnicalOk

`func (o *BrandVoiceInput) GetToneTechnicalOk() (*int32, bool)`

GetToneTechnicalOk returns a tuple with the ToneTechnical field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToneTechnical

`func (o *BrandVoiceInput) SetToneTechnical(v int32)`

SetToneTechnical sets ToneTechnical field to given value.

### HasToneTechnical

`func (o *BrandVoiceInput) HasToneTechnical() bool`

HasToneTechnical returns a boolean if a field has been set.

### GetEmojiStyle

`func (o *BrandVoiceInput) GetEmojiStyle() string`

GetEmojiStyle returns the EmojiStyle field if non-nil, zero value otherwise.

### GetEmojiStyleOk

`func (o *BrandVoiceInput) GetEmojiStyleOk() (*string, bool)`

GetEmojiStyleOk returns a tuple with the EmojiStyle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmojiStyle

`func (o *BrandVoiceInput) SetEmojiStyle(v string)`

SetEmojiStyle sets EmojiStyle field to given value.

### HasEmojiStyle

`func (o *BrandVoiceInput) HasEmojiStyle() bool`

HasEmojiStyle returns a boolean if a field has been set.

### GetHashtagStrategy

`func (o *BrandVoiceInput) GetHashtagStrategy() string`

GetHashtagStrategy returns the HashtagStrategy field if non-nil, zero value otherwise.

### GetHashtagStrategyOk

`func (o *BrandVoiceInput) GetHashtagStrategyOk() (*string, bool)`

GetHashtagStrategyOk returns a tuple with the HashtagStrategy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHashtagStrategy

`func (o *BrandVoiceInput) SetHashtagStrategy(v string)`

SetHashtagStrategy sets HashtagStrategy field to given value.

### HasHashtagStrategy

`func (o *BrandVoiceInput) HasHashtagStrategy() bool`

HasHashtagStrategy returns a boolean if a field has been set.

### GetAvoidWords

`func (o *BrandVoiceInput) GetAvoidWords() []string`

GetAvoidWords returns the AvoidWords field if non-nil, zero value otherwise.

### GetAvoidWordsOk

`func (o *BrandVoiceInput) GetAvoidWordsOk() (*[]string, bool)`

GetAvoidWordsOk returns a tuple with the AvoidWords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvoidWords

`func (o *BrandVoiceInput) SetAvoidWords(v []string)`

SetAvoidWords sets AvoidWords field to given value.

### HasAvoidWords

`func (o *BrandVoiceInput) HasAvoidWords() bool`

HasAvoidWords returns a boolean if a field has been set.

### SetAvoidWordsNil

`func (o *BrandVoiceInput) SetAvoidWordsNil(b bool)`

 SetAvoidWordsNil sets the value for AvoidWords to be an explicit nil

### UnsetAvoidWords
`func (o *BrandVoiceInput) UnsetAvoidWords()`

UnsetAvoidWords ensures that no value is present for AvoidWords, not even an explicit nil
### GetPreferredCta

`func (o *BrandVoiceInput) GetPreferredCta() []string`

GetPreferredCta returns the PreferredCta field if non-nil, zero value otherwise.

### GetPreferredCtaOk

`func (o *BrandVoiceInput) GetPreferredCtaOk() (*[]string, bool)`

GetPreferredCtaOk returns a tuple with the PreferredCta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreferredCta

`func (o *BrandVoiceInput) SetPreferredCta(v []string)`

SetPreferredCta sets PreferredCta field to given value.

### HasPreferredCta

`func (o *BrandVoiceInput) HasPreferredCta() bool`

HasPreferredCta returns a boolean if a field has been set.

### SetPreferredCtaNil

`func (o *BrandVoiceInput) SetPreferredCtaNil(b bool)`

 SetPreferredCtaNil sets the value for PreferredCta to be an explicit nil

### UnsetPreferredCta
`func (o *BrandVoiceInput) UnsetPreferredCta()`

UnsetPreferredCta ensures that no value is present for PreferredCta, not even an explicit nil
### GetExamplePosts

`func (o *BrandVoiceInput) GetExamplePosts() []*string`

GetExamplePosts returns the ExamplePosts field if non-nil, zero value otherwise.

### GetExamplePostsOk

`func (o *BrandVoiceInput) GetExamplePostsOk() (*[]*string, bool)`

GetExamplePostsOk returns a tuple with the ExamplePosts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExamplePosts

`func (o *BrandVoiceInput) SetExamplePosts(v []*string)`

SetExamplePosts sets ExamplePosts field to given value.

### HasExamplePosts

`func (o *BrandVoiceInput) HasExamplePosts() bool`

HasExamplePosts returns a boolean if a field has been set.

### SetExamplePostsNil

`func (o *BrandVoiceInput) SetExamplePostsNil(b bool)`

 SetExamplePostsNil sets the value for ExamplePosts to be an explicit nil

### UnsetExamplePosts
`func (o *BrandVoiceInput) UnsetExamplePosts()`

UnsetExamplePosts ensures that no value is present for ExamplePosts, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


