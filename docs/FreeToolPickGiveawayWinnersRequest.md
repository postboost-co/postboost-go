# FreeToolPickGiveawayWinnersRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Entrants** | [**[]FreeToolPickGiveawayWinnersRequestEntrantsInner**](FreeToolPickGiveawayWinnersRequestEntrantsInner.md) | The comments, one item each. The request body is capped at 128 KB. | 
**Seed** | Pointer to **string** | The secret seed, 64 hex characters (32 bytes), whose fingerprint you published before the entries closed. Without it, a seed is generated and pre_committed is false. The steps of the draw (pb-draw-v1) and a test vector are on the web tool page. | [optional] 
**OnePerPerson** | Pointer to **bool** | Count each username once. Off: every comment is an entry, so one person can win more than once. | [optional] [default to true]
**Keywords** | Pointer to **[]string** | Keep only comments that contain at least one of these, case-insensitive. | [optional] [default to []]
**MinMentions** | Pointer to **int32** | Keep only comments that tag at least this many other @handles. | [optional] [default to 0]
**Exclude** | Pointer to **[]string** | Usernames to leave out of the draw, such as the host account. | [optional] [default to []]
**Winners** | Pointer to **int32** |  | [optional] [default to 1]
**Alternates** | Pointer to **int32** | Runners-up drawn after the winners, in order. | [optional] [default to 0]

## Methods

### NewFreeToolPickGiveawayWinnersRequest

`func NewFreeToolPickGiveawayWinnersRequest(entrants []FreeToolPickGiveawayWinnersRequestEntrantsInner, ) *FreeToolPickGiveawayWinnersRequest`

NewFreeToolPickGiveawayWinnersRequest instantiates a new FreeToolPickGiveawayWinnersRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolPickGiveawayWinnersRequestWithDefaults

`func NewFreeToolPickGiveawayWinnersRequestWithDefaults() *FreeToolPickGiveawayWinnersRequest`

NewFreeToolPickGiveawayWinnersRequestWithDefaults instantiates a new FreeToolPickGiveawayWinnersRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEntrants

`func (o *FreeToolPickGiveawayWinnersRequest) GetEntrants() []FreeToolPickGiveawayWinnersRequestEntrantsInner`

GetEntrants returns the Entrants field if non-nil, zero value otherwise.

### GetEntrantsOk

`func (o *FreeToolPickGiveawayWinnersRequest) GetEntrantsOk() (*[]FreeToolPickGiveawayWinnersRequestEntrantsInner, bool)`

GetEntrantsOk returns a tuple with the Entrants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntrants

`func (o *FreeToolPickGiveawayWinnersRequest) SetEntrants(v []FreeToolPickGiveawayWinnersRequestEntrantsInner)`

SetEntrants sets Entrants field to given value.


### GetSeed

`func (o *FreeToolPickGiveawayWinnersRequest) GetSeed() string`

GetSeed returns the Seed field if non-nil, zero value otherwise.

### GetSeedOk

`func (o *FreeToolPickGiveawayWinnersRequest) GetSeedOk() (*string, bool)`

GetSeedOk returns a tuple with the Seed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeed

`func (o *FreeToolPickGiveawayWinnersRequest) SetSeed(v string)`

SetSeed sets Seed field to given value.

### HasSeed

`func (o *FreeToolPickGiveawayWinnersRequest) HasSeed() bool`

HasSeed returns a boolean if a field has been set.

### GetOnePerPerson

`func (o *FreeToolPickGiveawayWinnersRequest) GetOnePerPerson() bool`

GetOnePerPerson returns the OnePerPerson field if non-nil, zero value otherwise.

### GetOnePerPersonOk

`func (o *FreeToolPickGiveawayWinnersRequest) GetOnePerPersonOk() (*bool, bool)`

GetOnePerPersonOk returns a tuple with the OnePerPerson field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOnePerPerson

`func (o *FreeToolPickGiveawayWinnersRequest) SetOnePerPerson(v bool)`

SetOnePerPerson sets OnePerPerson field to given value.

### HasOnePerPerson

`func (o *FreeToolPickGiveawayWinnersRequest) HasOnePerPerson() bool`

HasOnePerPerson returns a boolean if a field has been set.

### GetKeywords

`func (o *FreeToolPickGiveawayWinnersRequest) GetKeywords() []string`

GetKeywords returns the Keywords field if non-nil, zero value otherwise.

### GetKeywordsOk

`func (o *FreeToolPickGiveawayWinnersRequest) GetKeywordsOk() (*[]string, bool)`

GetKeywordsOk returns a tuple with the Keywords field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKeywords

`func (o *FreeToolPickGiveawayWinnersRequest) SetKeywords(v []string)`

SetKeywords sets Keywords field to given value.

### HasKeywords

`func (o *FreeToolPickGiveawayWinnersRequest) HasKeywords() bool`

HasKeywords returns a boolean if a field has been set.

### GetMinMentions

`func (o *FreeToolPickGiveawayWinnersRequest) GetMinMentions() int32`

GetMinMentions returns the MinMentions field if non-nil, zero value otherwise.

### GetMinMentionsOk

`func (o *FreeToolPickGiveawayWinnersRequest) GetMinMentionsOk() (*int32, bool)`

GetMinMentionsOk returns a tuple with the MinMentions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinMentions

`func (o *FreeToolPickGiveawayWinnersRequest) SetMinMentions(v int32)`

SetMinMentions sets MinMentions field to given value.

### HasMinMentions

`func (o *FreeToolPickGiveawayWinnersRequest) HasMinMentions() bool`

HasMinMentions returns a boolean if a field has been set.

### GetExclude

`func (o *FreeToolPickGiveawayWinnersRequest) GetExclude() []string`

GetExclude returns the Exclude field if non-nil, zero value otherwise.

### GetExcludeOk

`func (o *FreeToolPickGiveawayWinnersRequest) GetExcludeOk() (*[]string, bool)`

GetExcludeOk returns a tuple with the Exclude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExclude

`func (o *FreeToolPickGiveawayWinnersRequest) SetExclude(v []string)`

SetExclude sets Exclude field to given value.

### HasExclude

`func (o *FreeToolPickGiveawayWinnersRequest) HasExclude() bool`

HasExclude returns a boolean if a field has been set.

### GetWinners

`func (o *FreeToolPickGiveawayWinnersRequest) GetWinners() int32`

GetWinners returns the Winners field if non-nil, zero value otherwise.

### GetWinnersOk

`func (o *FreeToolPickGiveawayWinnersRequest) GetWinnersOk() (*int32, bool)`

GetWinnersOk returns a tuple with the Winners field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWinners

`func (o *FreeToolPickGiveawayWinnersRequest) SetWinners(v int32)`

SetWinners sets Winners field to given value.

### HasWinners

`func (o *FreeToolPickGiveawayWinnersRequest) HasWinners() bool`

HasWinners returns a boolean if a field has been set.

### GetAlternates

`func (o *FreeToolPickGiveawayWinnersRequest) GetAlternates() int32`

GetAlternates returns the Alternates field if non-nil, zero value otherwise.

### GetAlternatesOk

`func (o *FreeToolPickGiveawayWinnersRequest) GetAlternatesOk() (*int32, bool)`

GetAlternatesOk returns a tuple with the Alternates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternates

`func (o *FreeToolPickGiveawayWinnersRequest) SetAlternates(v int32)`

SetAlternates sets Alternates field to given value.

### HasAlternates

`func (o *FreeToolPickGiveawayWinnersRequest) HasAlternates() bool`

HasAlternates returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


