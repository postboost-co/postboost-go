# FreeToolGenerateSocialPostsFromVideoResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Outputs** | Pointer to [**FreeToolGenerateSocialPostsFromVideoResponseOutputs**](FreeToolGenerateSocialPostsFromVideoResponseOutputs.md) |  | [optional] 
**OutputsSkipped** | Pointer to **[]string** | Requested outputs that came back empty: generate again to get them. | [optional] 
**Warnings** | Pointer to **[]string** | What to know before posting, in plain words. | [optional] 
**VideoUrl** | Pointer to **NullableString** | The normalised video link the posts use, or null. | [optional] 
**CleanedChars** | Pointer to **int32** | Characters of caption text left after cleaning; the model read these. | [optional] 
**RemovedTimestamps** | Pointer to **bool** | True when timestamps, cue numbers, tags or repeated caption lines were removed. | [optional] 
**CreditsSpent** | Pointer to **int32** | AI credits this call took from the workspace: 1, or 0 for a cached result. | [optional] 
**Cached** | Pointer to **bool** | True when the same request was answered before (free). | [optional] 

## Methods

### NewFreeToolGenerateSocialPostsFromVideoResponse

`func NewFreeToolGenerateSocialPostsFromVideoResponse() *FreeToolGenerateSocialPostsFromVideoResponse`

NewFreeToolGenerateSocialPostsFromVideoResponse instantiates a new FreeToolGenerateSocialPostsFromVideoResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateSocialPostsFromVideoResponseWithDefaults

`func NewFreeToolGenerateSocialPostsFromVideoResponseWithDefaults() *FreeToolGenerateSocialPostsFromVideoResponse`

NewFreeToolGenerateSocialPostsFromVideoResponseWithDefaults instantiates a new FreeToolGenerateSocialPostsFromVideoResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOutputs

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) GetOutputs() FreeToolGenerateSocialPostsFromVideoResponseOutputs`

GetOutputs returns the Outputs field if non-nil, zero value otherwise.

### GetOutputsOk

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) GetOutputsOk() (*FreeToolGenerateSocialPostsFromVideoResponseOutputs, bool)`

GetOutputsOk returns a tuple with the Outputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputs

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) SetOutputs(v FreeToolGenerateSocialPostsFromVideoResponseOutputs)`

SetOutputs sets Outputs field to given value.

### HasOutputs

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) HasOutputs() bool`

HasOutputs returns a boolean if a field has been set.

### GetOutputsSkipped

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) GetOutputsSkipped() []string`

GetOutputsSkipped returns the OutputsSkipped field if non-nil, zero value otherwise.

### GetOutputsSkippedOk

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) GetOutputsSkippedOk() (*[]string, bool)`

GetOutputsSkippedOk returns a tuple with the OutputsSkipped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputsSkipped

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) SetOutputsSkipped(v []string)`

SetOutputsSkipped sets OutputsSkipped field to given value.

### HasOutputsSkipped

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) HasOutputsSkipped() bool`

HasOutputsSkipped returns a boolean if a field has been set.

### GetWarnings

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.

### GetVideoUrl

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) GetVideoUrl() string`

GetVideoUrl returns the VideoUrl field if non-nil, zero value otherwise.

### GetVideoUrlOk

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) GetVideoUrlOk() (*string, bool)`

GetVideoUrlOk returns a tuple with the VideoUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoUrl

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) SetVideoUrl(v string)`

SetVideoUrl sets VideoUrl field to given value.

### HasVideoUrl

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) HasVideoUrl() bool`

HasVideoUrl returns a boolean if a field has been set.

### SetVideoUrlNil

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) SetVideoUrlNil(b bool)`

 SetVideoUrlNil sets the value for VideoUrl to be an explicit nil

### UnsetVideoUrl
`func (o *FreeToolGenerateSocialPostsFromVideoResponse) UnsetVideoUrl()`

UnsetVideoUrl ensures that no value is present for VideoUrl, not even an explicit nil
### GetCleanedChars

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) GetCleanedChars() int32`

GetCleanedChars returns the CleanedChars field if non-nil, zero value otherwise.

### GetCleanedCharsOk

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) GetCleanedCharsOk() (*int32, bool)`

GetCleanedCharsOk returns a tuple with the CleanedChars field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCleanedChars

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) SetCleanedChars(v int32)`

SetCleanedChars sets CleanedChars field to given value.

### HasCleanedChars

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) HasCleanedChars() bool`

HasCleanedChars returns a boolean if a field has been set.

### GetRemovedTimestamps

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) GetRemovedTimestamps() bool`

GetRemovedTimestamps returns the RemovedTimestamps field if non-nil, zero value otherwise.

### GetRemovedTimestampsOk

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) GetRemovedTimestampsOk() (*bool, bool)`

GetRemovedTimestampsOk returns a tuple with the RemovedTimestamps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemovedTimestamps

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) SetRemovedTimestamps(v bool)`

SetRemovedTimestamps sets RemovedTimestamps field to given value.

### HasRemovedTimestamps

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) HasRemovedTimestamps() bool`

HasRemovedTimestamps returns a boolean if a field has been set.

### GetCreditsSpent

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) GetCreditsSpent() int32`

GetCreditsSpent returns the CreditsSpent field if non-nil, zero value otherwise.

### GetCreditsSpentOk

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) GetCreditsSpentOk() (*int32, bool)`

GetCreditsSpentOk returns a tuple with the CreditsSpent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsSpent

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) SetCreditsSpent(v int32)`

SetCreditsSpent sets CreditsSpent field to given value.

### HasCreditsSpent

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) HasCreditsSpent() bool`

HasCreditsSpent returns a boolean if a field has been set.

### GetCached

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) GetCached() bool`

GetCached returns the Cached field if non-nil, zero value otherwise.

### GetCachedOk

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) GetCachedOk() (*bool, bool)`

GetCachedOk returns a tuple with the Cached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCached

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) SetCached(v bool)`

SetCached sets Cached field to given value.

### HasCached

`func (o *FreeToolGenerateSocialPostsFromVideoResponse) HasCached() bool`

HasCached returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


