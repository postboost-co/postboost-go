# FreeToolCheckReadabilityResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Supported** | Pointer to **bool** | False for a language other than English: no scores, hints or suggestions. | [optional] 
**Note** | Pointer to **NullableString** | Why the text was not scored, or null. | [optional] 
**FleschReadingEase** | Pointer to **NullableFloat32** | Flesch reading ease, one decimal: higher is easier, 60-70 is plain English. Null when not scored. | [optional] 
**FleschKincaidGrade** | Pointer to **NullableFloat32** | Flesch-Kincaid grade level, one decimal: the US school grade that can read the text. Null when not scored. | [optional] 
**Sentences** | Pointer to **int32** | Sentences with at least one word. | [optional] 
**Words** | Pointer to **int32** | Words, not counting hashtags, @mentions, links and emoji. | [optional] 
**Syllables** | Pointer to **int32** | Syllables, by the heuristic described in the docs. | [optional] 
**AvgWordsPerSentence** | Pointer to **float32** | Words per sentence, one decimal. | [optional] 
**LongSentences** | Pointer to [**[]FreeToolCheckReadabilityResponseLongSentencesInner**](FreeToolCheckReadabilityResponseLongSentencesInner.md) | Sentences of more than 25 words. | [optional] 
**PassiveHints** | Pointer to **int32** | Possible passive phrases (\&quot;was written\&quot;, \&quot;is being reviewed\&quot;). A hint, not a grammar check. | [optional] 
**EmojiCount** | Pointer to **int32** | Emoji (Extended_Pictographic characters). | [optional] 
**HashtagCount** | Pointer to **int32** | Hashtags. | [optional] 
**Suggestions** | Pointer to **[]string** | Plain fixes, e.g. which sentence to split. Empty when the text reads easily. | [optional] 

## Methods

### NewFreeToolCheckReadabilityResponse

`func NewFreeToolCheckReadabilityResponse() *FreeToolCheckReadabilityResponse`

NewFreeToolCheckReadabilityResponse instantiates a new FreeToolCheckReadabilityResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCheckReadabilityResponseWithDefaults

`func NewFreeToolCheckReadabilityResponseWithDefaults() *FreeToolCheckReadabilityResponse`

NewFreeToolCheckReadabilityResponseWithDefaults instantiates a new FreeToolCheckReadabilityResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSupported

`func (o *FreeToolCheckReadabilityResponse) GetSupported() bool`

GetSupported returns the Supported field if non-nil, zero value otherwise.

### GetSupportedOk

`func (o *FreeToolCheckReadabilityResponse) GetSupportedOk() (*bool, bool)`

GetSupportedOk returns a tuple with the Supported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupported

`func (o *FreeToolCheckReadabilityResponse) SetSupported(v bool)`

SetSupported sets Supported field to given value.

### HasSupported

`func (o *FreeToolCheckReadabilityResponse) HasSupported() bool`

HasSupported returns a boolean if a field has been set.

### GetNote

`func (o *FreeToolCheckReadabilityResponse) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *FreeToolCheckReadabilityResponse) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *FreeToolCheckReadabilityResponse) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *FreeToolCheckReadabilityResponse) HasNote() bool`

HasNote returns a boolean if a field has been set.

### SetNoteNil

`func (o *FreeToolCheckReadabilityResponse) SetNoteNil(b bool)`

 SetNoteNil sets the value for Note to be an explicit nil

### UnsetNote
`func (o *FreeToolCheckReadabilityResponse) UnsetNote()`

UnsetNote ensures that no value is present for Note, not even an explicit nil
### GetFleschReadingEase

`func (o *FreeToolCheckReadabilityResponse) GetFleschReadingEase() float32`

GetFleschReadingEase returns the FleschReadingEase field if non-nil, zero value otherwise.

### GetFleschReadingEaseOk

`func (o *FreeToolCheckReadabilityResponse) GetFleschReadingEaseOk() (*float32, bool)`

GetFleschReadingEaseOk returns a tuple with the FleschReadingEase field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFleschReadingEase

`func (o *FreeToolCheckReadabilityResponse) SetFleschReadingEase(v float32)`

SetFleschReadingEase sets FleschReadingEase field to given value.

### HasFleschReadingEase

`func (o *FreeToolCheckReadabilityResponse) HasFleschReadingEase() bool`

HasFleschReadingEase returns a boolean if a field has been set.

### SetFleschReadingEaseNil

`func (o *FreeToolCheckReadabilityResponse) SetFleschReadingEaseNil(b bool)`

 SetFleschReadingEaseNil sets the value for FleschReadingEase to be an explicit nil

### UnsetFleschReadingEase
`func (o *FreeToolCheckReadabilityResponse) UnsetFleschReadingEase()`

UnsetFleschReadingEase ensures that no value is present for FleschReadingEase, not even an explicit nil
### GetFleschKincaidGrade

`func (o *FreeToolCheckReadabilityResponse) GetFleschKincaidGrade() float32`

GetFleschKincaidGrade returns the FleschKincaidGrade field if non-nil, zero value otherwise.

### GetFleschKincaidGradeOk

`func (o *FreeToolCheckReadabilityResponse) GetFleschKincaidGradeOk() (*float32, bool)`

GetFleschKincaidGradeOk returns a tuple with the FleschKincaidGrade field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFleschKincaidGrade

`func (o *FreeToolCheckReadabilityResponse) SetFleschKincaidGrade(v float32)`

SetFleschKincaidGrade sets FleschKincaidGrade field to given value.

### HasFleschKincaidGrade

`func (o *FreeToolCheckReadabilityResponse) HasFleschKincaidGrade() bool`

HasFleschKincaidGrade returns a boolean if a field has been set.

### SetFleschKincaidGradeNil

`func (o *FreeToolCheckReadabilityResponse) SetFleschKincaidGradeNil(b bool)`

 SetFleschKincaidGradeNil sets the value for FleschKincaidGrade to be an explicit nil

### UnsetFleschKincaidGrade
`func (o *FreeToolCheckReadabilityResponse) UnsetFleschKincaidGrade()`

UnsetFleschKincaidGrade ensures that no value is present for FleschKincaidGrade, not even an explicit nil
### GetSentences

`func (o *FreeToolCheckReadabilityResponse) GetSentences() int32`

GetSentences returns the Sentences field if non-nil, zero value otherwise.

### GetSentencesOk

`func (o *FreeToolCheckReadabilityResponse) GetSentencesOk() (*int32, bool)`

GetSentencesOk returns a tuple with the Sentences field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentences

`func (o *FreeToolCheckReadabilityResponse) SetSentences(v int32)`

SetSentences sets Sentences field to given value.

### HasSentences

`func (o *FreeToolCheckReadabilityResponse) HasSentences() bool`

HasSentences returns a boolean if a field has been set.

### GetWords

`func (o *FreeToolCheckReadabilityResponse) GetWords() int32`

GetWords returns the Words field if non-nil, zero value otherwise.

### GetWordsOk

`func (o *FreeToolCheckReadabilityResponse) GetWordsOk() (*int32, bool)`

GetWordsOk returns a tuple with the Words field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWords

`func (o *FreeToolCheckReadabilityResponse) SetWords(v int32)`

SetWords sets Words field to given value.

### HasWords

`func (o *FreeToolCheckReadabilityResponse) HasWords() bool`

HasWords returns a boolean if a field has been set.

### GetSyllables

`func (o *FreeToolCheckReadabilityResponse) GetSyllables() int32`

GetSyllables returns the Syllables field if non-nil, zero value otherwise.

### GetSyllablesOk

`func (o *FreeToolCheckReadabilityResponse) GetSyllablesOk() (*int32, bool)`

GetSyllablesOk returns a tuple with the Syllables field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyllables

`func (o *FreeToolCheckReadabilityResponse) SetSyllables(v int32)`

SetSyllables sets Syllables field to given value.

### HasSyllables

`func (o *FreeToolCheckReadabilityResponse) HasSyllables() bool`

HasSyllables returns a boolean if a field has been set.

### GetAvgWordsPerSentence

`func (o *FreeToolCheckReadabilityResponse) GetAvgWordsPerSentence() float32`

GetAvgWordsPerSentence returns the AvgWordsPerSentence field if non-nil, zero value otherwise.

### GetAvgWordsPerSentenceOk

`func (o *FreeToolCheckReadabilityResponse) GetAvgWordsPerSentenceOk() (*float32, bool)`

GetAvgWordsPerSentenceOk returns a tuple with the AvgWordsPerSentence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvgWordsPerSentence

`func (o *FreeToolCheckReadabilityResponse) SetAvgWordsPerSentence(v float32)`

SetAvgWordsPerSentence sets AvgWordsPerSentence field to given value.

### HasAvgWordsPerSentence

`func (o *FreeToolCheckReadabilityResponse) HasAvgWordsPerSentence() bool`

HasAvgWordsPerSentence returns a boolean if a field has been set.

### GetLongSentences

`func (o *FreeToolCheckReadabilityResponse) GetLongSentences() []FreeToolCheckReadabilityResponseLongSentencesInner`

GetLongSentences returns the LongSentences field if non-nil, zero value otherwise.

### GetLongSentencesOk

`func (o *FreeToolCheckReadabilityResponse) GetLongSentencesOk() (*[]FreeToolCheckReadabilityResponseLongSentencesInner, bool)`

GetLongSentencesOk returns a tuple with the LongSentences field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLongSentences

`func (o *FreeToolCheckReadabilityResponse) SetLongSentences(v []FreeToolCheckReadabilityResponseLongSentencesInner)`

SetLongSentences sets LongSentences field to given value.

### HasLongSentences

`func (o *FreeToolCheckReadabilityResponse) HasLongSentences() bool`

HasLongSentences returns a boolean if a field has been set.

### GetPassiveHints

`func (o *FreeToolCheckReadabilityResponse) GetPassiveHints() int32`

GetPassiveHints returns the PassiveHints field if non-nil, zero value otherwise.

### GetPassiveHintsOk

`func (o *FreeToolCheckReadabilityResponse) GetPassiveHintsOk() (*int32, bool)`

GetPassiveHintsOk returns a tuple with the PassiveHints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassiveHints

`func (o *FreeToolCheckReadabilityResponse) SetPassiveHints(v int32)`

SetPassiveHints sets PassiveHints field to given value.

### HasPassiveHints

`func (o *FreeToolCheckReadabilityResponse) HasPassiveHints() bool`

HasPassiveHints returns a boolean if a field has been set.

### GetEmojiCount

`func (o *FreeToolCheckReadabilityResponse) GetEmojiCount() int32`

GetEmojiCount returns the EmojiCount field if non-nil, zero value otherwise.

### GetEmojiCountOk

`func (o *FreeToolCheckReadabilityResponse) GetEmojiCountOk() (*int32, bool)`

GetEmojiCountOk returns a tuple with the EmojiCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmojiCount

`func (o *FreeToolCheckReadabilityResponse) SetEmojiCount(v int32)`

SetEmojiCount sets EmojiCount field to given value.

### HasEmojiCount

`func (o *FreeToolCheckReadabilityResponse) HasEmojiCount() bool`

HasEmojiCount returns a boolean if a field has been set.

### GetHashtagCount

`func (o *FreeToolCheckReadabilityResponse) GetHashtagCount() int32`

GetHashtagCount returns the HashtagCount field if non-nil, zero value otherwise.

### GetHashtagCountOk

`func (o *FreeToolCheckReadabilityResponse) GetHashtagCountOk() (*int32, bool)`

GetHashtagCountOk returns a tuple with the HashtagCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHashtagCount

`func (o *FreeToolCheckReadabilityResponse) SetHashtagCount(v int32)`

SetHashtagCount sets HashtagCount field to given value.

### HasHashtagCount

`func (o *FreeToolCheckReadabilityResponse) HasHashtagCount() bool`

HasHashtagCount returns a boolean if a field has been set.

### GetSuggestions

`func (o *FreeToolCheckReadabilityResponse) GetSuggestions() []string`

GetSuggestions returns the Suggestions field if non-nil, zero value otherwise.

### GetSuggestionsOk

`func (o *FreeToolCheckReadabilityResponse) GetSuggestionsOk() (*[]string, bool)`

GetSuggestionsOk returns a tuple with the Suggestions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuggestions

`func (o *FreeToolCheckReadabilityResponse) SetSuggestions(v []string)`

SetSuggestions sets Suggestions field to given value.

### HasSuggestions

`func (o *FreeToolCheckReadabilityResponse) HasSuggestions() bool`

HasSuggestions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


