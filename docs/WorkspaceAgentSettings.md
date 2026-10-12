# WorkspaceAgentSettings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**HorizonHours** | Pointer to **int32** | Check posts scheduled within this many hours. | [optional] [default to 24]
**CheckLinks** | Pointer to **bool** | Flag links in captions that answer an HTTP error. | [optional] [default to true]
**BannedPhrases** | Pointer to **[]string** | Phrases to propose removing from captions. | [optional] [default to []]
**AiReview** | Pointer to **bool** | Ask AI to review captions (one AI credit per reviewed post). | [optional] [default to false]
**MaxAiReviewsPerRun** | Pointer to **int32** |  | [optional] [default to 10]

## Methods

### NewWorkspaceAgentSettings

`func NewWorkspaceAgentSettings() *WorkspaceAgentSettings`

NewWorkspaceAgentSettings instantiates a new WorkspaceAgentSettings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWorkspaceAgentSettingsWithDefaults

`func NewWorkspaceAgentSettingsWithDefaults() *WorkspaceAgentSettings`

NewWorkspaceAgentSettingsWithDefaults instantiates a new WorkspaceAgentSettings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHorizonHours

`func (o *WorkspaceAgentSettings) GetHorizonHours() int32`

GetHorizonHours returns the HorizonHours field if non-nil, zero value otherwise.

### GetHorizonHoursOk

`func (o *WorkspaceAgentSettings) GetHorizonHoursOk() (*int32, bool)`

GetHorizonHoursOk returns a tuple with the HorizonHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHorizonHours

`func (o *WorkspaceAgentSettings) SetHorizonHours(v int32)`

SetHorizonHours sets HorizonHours field to given value.

### HasHorizonHours

`func (o *WorkspaceAgentSettings) HasHorizonHours() bool`

HasHorizonHours returns a boolean if a field has been set.

### GetCheckLinks

`func (o *WorkspaceAgentSettings) GetCheckLinks() bool`

GetCheckLinks returns the CheckLinks field if non-nil, zero value otherwise.

### GetCheckLinksOk

`func (o *WorkspaceAgentSettings) GetCheckLinksOk() (*bool, bool)`

GetCheckLinksOk returns a tuple with the CheckLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckLinks

`func (o *WorkspaceAgentSettings) SetCheckLinks(v bool)`

SetCheckLinks sets CheckLinks field to given value.

### HasCheckLinks

`func (o *WorkspaceAgentSettings) HasCheckLinks() bool`

HasCheckLinks returns a boolean if a field has been set.

### GetBannedPhrases

`func (o *WorkspaceAgentSettings) GetBannedPhrases() []string`

GetBannedPhrases returns the BannedPhrases field if non-nil, zero value otherwise.

### GetBannedPhrasesOk

`func (o *WorkspaceAgentSettings) GetBannedPhrasesOk() (*[]string, bool)`

GetBannedPhrasesOk returns a tuple with the BannedPhrases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBannedPhrases

`func (o *WorkspaceAgentSettings) SetBannedPhrases(v []string)`

SetBannedPhrases sets BannedPhrases field to given value.

### HasBannedPhrases

`func (o *WorkspaceAgentSettings) HasBannedPhrases() bool`

HasBannedPhrases returns a boolean if a field has been set.

### GetAiReview

`func (o *WorkspaceAgentSettings) GetAiReview() bool`

GetAiReview returns the AiReview field if non-nil, zero value otherwise.

### GetAiReviewOk

`func (o *WorkspaceAgentSettings) GetAiReviewOk() (*bool, bool)`

GetAiReviewOk returns a tuple with the AiReview field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAiReview

`func (o *WorkspaceAgentSettings) SetAiReview(v bool)`

SetAiReview sets AiReview field to given value.

### HasAiReview

`func (o *WorkspaceAgentSettings) HasAiReview() bool`

HasAiReview returns a boolean if a field has been set.

### GetMaxAiReviewsPerRun

`func (o *WorkspaceAgentSettings) GetMaxAiReviewsPerRun() int32`

GetMaxAiReviewsPerRun returns the MaxAiReviewsPerRun field if non-nil, zero value otherwise.

### GetMaxAiReviewsPerRunOk

`func (o *WorkspaceAgentSettings) GetMaxAiReviewsPerRunOk() (*int32, bool)`

GetMaxAiReviewsPerRunOk returns a tuple with the MaxAiReviewsPerRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxAiReviewsPerRun

`func (o *WorkspaceAgentSettings) SetMaxAiReviewsPerRun(v int32)`

SetMaxAiReviewsPerRun sets MaxAiReviewsPerRun field to given value.

### HasMaxAiReviewsPerRun

`func (o *WorkspaceAgentSettings) HasMaxAiReviewsPerRun() bool`

HasMaxAiReviewsPerRun returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


