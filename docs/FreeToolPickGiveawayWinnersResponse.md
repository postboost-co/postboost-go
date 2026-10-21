# FreeToolPickGiveawayWinnersResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Winners** | Pointer to **[]string** | Entrant keys in the drawn order. | [optional] 
**Alternates** | Pointer to **[]string** | Entrant keys drawn after the winners, in order. | [optional] 
**EntrantsBefore** | Pointer to **int32** | Comments received. | [optional] 
**EntrantsAfter** | Pointer to **int32** | Entries left after the filters: the length of entrant_list. | [optional] 
**EntrantList** | Pointer to **[]string** | The canonical entrant list to publish: keys sorted by UTF-8 bytes. Joined with \&quot;\\n\&quot; it is what entrants_hash hashes. | [optional] 
**EntrantsHash** | Pointer to **string** | SHA-256 (hex) of the canonical entrant list. | [optional] 
**Fingerprint** | Pointer to **string** | SHA-256 (hex) of the seed bytes: what to publish before the entries close. | [optional] 
**Seed** | Pointer to **string** | The seed used, lowercase hex. Publish it after the draw. | [optional] 
**PreCommitted** | Pointer to **bool** | False when the seed was generated for this draw, so no fingerprint could be published before it. | [optional] 
**Algorithm** | Pointer to **string** |  | [optional] 
**Warnings** | Pointer to [**[]FreeToolCheckPostResponseNetworksInnerErrorsInner**](FreeToolCheckPostResponseNetworksInnerErrorsInner.md) | Codes: not_enough_entrants, not_pre_committed. | [optional] 

## Methods

### NewFreeToolPickGiveawayWinnersResponse

`func NewFreeToolPickGiveawayWinnersResponse() *FreeToolPickGiveawayWinnersResponse`

NewFreeToolPickGiveawayWinnersResponse instantiates a new FreeToolPickGiveawayWinnersResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolPickGiveawayWinnersResponseWithDefaults

`func NewFreeToolPickGiveawayWinnersResponseWithDefaults() *FreeToolPickGiveawayWinnersResponse`

NewFreeToolPickGiveawayWinnersResponseWithDefaults instantiates a new FreeToolPickGiveawayWinnersResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWinners

`func (o *FreeToolPickGiveawayWinnersResponse) GetWinners() []string`

GetWinners returns the Winners field if non-nil, zero value otherwise.

### GetWinnersOk

`func (o *FreeToolPickGiveawayWinnersResponse) GetWinnersOk() (*[]string, bool)`

GetWinnersOk returns a tuple with the Winners field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWinners

`func (o *FreeToolPickGiveawayWinnersResponse) SetWinners(v []string)`

SetWinners sets Winners field to given value.

### HasWinners

`func (o *FreeToolPickGiveawayWinnersResponse) HasWinners() bool`

HasWinners returns a boolean if a field has been set.

### GetAlternates

`func (o *FreeToolPickGiveawayWinnersResponse) GetAlternates() []string`

GetAlternates returns the Alternates field if non-nil, zero value otherwise.

### GetAlternatesOk

`func (o *FreeToolPickGiveawayWinnersResponse) GetAlternatesOk() (*[]string, bool)`

GetAlternatesOk returns a tuple with the Alternates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternates

`func (o *FreeToolPickGiveawayWinnersResponse) SetAlternates(v []string)`

SetAlternates sets Alternates field to given value.

### HasAlternates

`func (o *FreeToolPickGiveawayWinnersResponse) HasAlternates() bool`

HasAlternates returns a boolean if a field has been set.

### GetEntrantsBefore

`func (o *FreeToolPickGiveawayWinnersResponse) GetEntrantsBefore() int32`

GetEntrantsBefore returns the EntrantsBefore field if non-nil, zero value otherwise.

### GetEntrantsBeforeOk

`func (o *FreeToolPickGiveawayWinnersResponse) GetEntrantsBeforeOk() (*int32, bool)`

GetEntrantsBeforeOk returns a tuple with the EntrantsBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntrantsBefore

`func (o *FreeToolPickGiveawayWinnersResponse) SetEntrantsBefore(v int32)`

SetEntrantsBefore sets EntrantsBefore field to given value.

### HasEntrantsBefore

`func (o *FreeToolPickGiveawayWinnersResponse) HasEntrantsBefore() bool`

HasEntrantsBefore returns a boolean if a field has been set.

### GetEntrantsAfter

`func (o *FreeToolPickGiveawayWinnersResponse) GetEntrantsAfter() int32`

GetEntrantsAfter returns the EntrantsAfter field if non-nil, zero value otherwise.

### GetEntrantsAfterOk

`func (o *FreeToolPickGiveawayWinnersResponse) GetEntrantsAfterOk() (*int32, bool)`

GetEntrantsAfterOk returns a tuple with the EntrantsAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntrantsAfter

`func (o *FreeToolPickGiveawayWinnersResponse) SetEntrantsAfter(v int32)`

SetEntrantsAfter sets EntrantsAfter field to given value.

### HasEntrantsAfter

`func (o *FreeToolPickGiveawayWinnersResponse) HasEntrantsAfter() bool`

HasEntrantsAfter returns a boolean if a field has been set.

### GetEntrantList

`func (o *FreeToolPickGiveawayWinnersResponse) GetEntrantList() []string`

GetEntrantList returns the EntrantList field if non-nil, zero value otherwise.

### GetEntrantListOk

`func (o *FreeToolPickGiveawayWinnersResponse) GetEntrantListOk() (*[]string, bool)`

GetEntrantListOk returns a tuple with the EntrantList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntrantList

`func (o *FreeToolPickGiveawayWinnersResponse) SetEntrantList(v []string)`

SetEntrantList sets EntrantList field to given value.

### HasEntrantList

`func (o *FreeToolPickGiveawayWinnersResponse) HasEntrantList() bool`

HasEntrantList returns a boolean if a field has been set.

### GetEntrantsHash

`func (o *FreeToolPickGiveawayWinnersResponse) GetEntrantsHash() string`

GetEntrantsHash returns the EntrantsHash field if non-nil, zero value otherwise.

### GetEntrantsHashOk

`func (o *FreeToolPickGiveawayWinnersResponse) GetEntrantsHashOk() (*string, bool)`

GetEntrantsHashOk returns a tuple with the EntrantsHash field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntrantsHash

`func (o *FreeToolPickGiveawayWinnersResponse) SetEntrantsHash(v string)`

SetEntrantsHash sets EntrantsHash field to given value.

### HasEntrantsHash

`func (o *FreeToolPickGiveawayWinnersResponse) HasEntrantsHash() bool`

HasEntrantsHash returns a boolean if a field has been set.

### GetFingerprint

`func (o *FreeToolPickGiveawayWinnersResponse) GetFingerprint() string`

GetFingerprint returns the Fingerprint field if non-nil, zero value otherwise.

### GetFingerprintOk

`func (o *FreeToolPickGiveawayWinnersResponse) GetFingerprintOk() (*string, bool)`

GetFingerprintOk returns a tuple with the Fingerprint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFingerprint

`func (o *FreeToolPickGiveawayWinnersResponse) SetFingerprint(v string)`

SetFingerprint sets Fingerprint field to given value.

### HasFingerprint

`func (o *FreeToolPickGiveawayWinnersResponse) HasFingerprint() bool`

HasFingerprint returns a boolean if a field has been set.

### GetSeed

`func (o *FreeToolPickGiveawayWinnersResponse) GetSeed() string`

GetSeed returns the Seed field if non-nil, zero value otherwise.

### GetSeedOk

`func (o *FreeToolPickGiveawayWinnersResponse) GetSeedOk() (*string, bool)`

GetSeedOk returns a tuple with the Seed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeed

`func (o *FreeToolPickGiveawayWinnersResponse) SetSeed(v string)`

SetSeed sets Seed field to given value.

### HasSeed

`func (o *FreeToolPickGiveawayWinnersResponse) HasSeed() bool`

HasSeed returns a boolean if a field has been set.

### GetPreCommitted

`func (o *FreeToolPickGiveawayWinnersResponse) GetPreCommitted() bool`

GetPreCommitted returns the PreCommitted field if non-nil, zero value otherwise.

### GetPreCommittedOk

`func (o *FreeToolPickGiveawayWinnersResponse) GetPreCommittedOk() (*bool, bool)`

GetPreCommittedOk returns a tuple with the PreCommitted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreCommitted

`func (o *FreeToolPickGiveawayWinnersResponse) SetPreCommitted(v bool)`

SetPreCommitted sets PreCommitted field to given value.

### HasPreCommitted

`func (o *FreeToolPickGiveawayWinnersResponse) HasPreCommitted() bool`

HasPreCommitted returns a boolean if a field has been set.

### GetAlgorithm

`func (o *FreeToolPickGiveawayWinnersResponse) GetAlgorithm() string`

GetAlgorithm returns the Algorithm field if non-nil, zero value otherwise.

### GetAlgorithmOk

`func (o *FreeToolPickGiveawayWinnersResponse) GetAlgorithmOk() (*string, bool)`

GetAlgorithmOk returns a tuple with the Algorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlgorithm

`func (o *FreeToolPickGiveawayWinnersResponse) SetAlgorithm(v string)`

SetAlgorithm sets Algorithm field to given value.

### HasAlgorithm

`func (o *FreeToolPickGiveawayWinnersResponse) HasAlgorithm() bool`

HasAlgorithm returns a boolean if a field has been set.

### GetWarnings

`func (o *FreeToolPickGiveawayWinnersResponse) GetWarnings() []FreeToolCheckPostResponseNetworksInnerErrorsInner`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *FreeToolPickGiveawayWinnersResponse) GetWarningsOk() (*[]FreeToolCheckPostResponseNetworksInnerErrorsInner, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *FreeToolPickGiveawayWinnersResponse) SetWarnings(v []FreeToolCheckPostResponseNetworksInnerErrorsInner)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *FreeToolPickGiveawayWinnersResponse) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


