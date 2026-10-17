# FreeToolListAwarenessDaysResponseEntriesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Name of the holiday or observance. | [optional] 
**Type** | Pointer to **string** | Entry type. | [optional] 
**Date** | Pointer to **string** | The day, or the first day of a week or month. | [optional] 
**End** | Pointer to **NullableString** | Last day of a week or month (inclusive); null for a single day. | [optional] 
**Countries** | Pointer to **[]string** | Country codes, or &#x60;global&#x60;. | [optional] 
**Topics** | Pointer to **[]string** | Topics. | [optional] 
**Source** | Pointer to **string** | Official or organiser page the date comes from. | [optional] 
**Note** | Pointer to **NullableString** | Regional scope or a day off that differs from the date. | [optional] 
**Idea** | Pointer to **string** | A one-line post idea. | [optional] 

## Methods

### NewFreeToolListAwarenessDaysResponseEntriesInner

`func NewFreeToolListAwarenessDaysResponseEntriesInner() *FreeToolListAwarenessDaysResponseEntriesInner`

NewFreeToolListAwarenessDaysResponseEntriesInner instantiates a new FreeToolListAwarenessDaysResponseEntriesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolListAwarenessDaysResponseEntriesInnerWithDefaults

`func NewFreeToolListAwarenessDaysResponseEntriesInnerWithDefaults() *FreeToolListAwarenessDaysResponseEntriesInner`

NewFreeToolListAwarenessDaysResponseEntriesInnerWithDefaults instantiates a new FreeToolListAwarenessDaysResponseEntriesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) HasName() bool`

HasName returns a boolean if a field has been set.

### GetType

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) HasType() bool`

HasType returns a boolean if a field has been set.

### GetDate

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetDate() string`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetDateOk() (*string, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) SetDate(v string)`

SetDate sets Date field to given value.

### HasDate

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) HasDate() bool`

HasDate returns a boolean if a field has been set.

### GetEnd

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetEnd() string`

GetEnd returns the End field if non-nil, zero value otherwise.

### GetEndOk

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetEndOk() (*string, bool)`

GetEndOk returns a tuple with the End field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnd

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) SetEnd(v string)`

SetEnd sets End field to given value.

### HasEnd

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) HasEnd() bool`

HasEnd returns a boolean if a field has been set.

### SetEndNil

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) SetEndNil(b bool)`

 SetEndNil sets the value for End to be an explicit nil

### UnsetEnd
`func (o *FreeToolListAwarenessDaysResponseEntriesInner) UnsetEnd()`

UnsetEnd ensures that no value is present for End, not even an explicit nil
### GetCountries

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetCountries() []string`

GetCountries returns the Countries field if non-nil, zero value otherwise.

### GetCountriesOk

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetCountriesOk() (*[]string, bool)`

GetCountriesOk returns a tuple with the Countries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountries

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) SetCountries(v []string)`

SetCountries sets Countries field to given value.

### HasCountries

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) HasCountries() bool`

HasCountries returns a boolean if a field has been set.

### GetTopics

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetTopics() []string`

GetTopics returns the Topics field if non-nil, zero value otherwise.

### GetTopicsOk

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetTopicsOk() (*[]string, bool)`

GetTopicsOk returns a tuple with the Topics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopics

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) SetTopics(v []string)`

SetTopics sets Topics field to given value.

### HasTopics

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) HasTopics() bool`

HasTopics returns a boolean if a field has been set.

### GetSource

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetNote

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) HasNote() bool`

HasNote returns a boolean if a field has been set.

### SetNoteNil

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) SetNoteNil(b bool)`

 SetNoteNil sets the value for Note to be an explicit nil

### UnsetNote
`func (o *FreeToolListAwarenessDaysResponseEntriesInner) UnsetNote()`

UnsetNote ensures that no value is present for Note, not even an explicit nil
### GetIdea

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetIdea() string`

GetIdea returns the Idea field if non-nil, zero value otherwise.

### GetIdeaOk

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) GetIdeaOk() (*string, bool)`

GetIdeaOk returns a tuple with the Idea field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdea

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) SetIdea(v string)`

SetIdea sets Idea field to given value.

### HasIdea

`func (o *FreeToolListAwarenessDaysResponseEntriesInner) HasIdea() bool`

HasIdea returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


