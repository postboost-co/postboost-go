# FreeToolGenerateLinkedInHeadlineResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Headlines** | Pointer to **[]string** | Three to five different headlines, each at most 220 characters as the character counter counts them. | [optional] 
**CreditsSpent** | Pointer to **int32** | AI credits this call took from the workspace: 1, or 0 for a cached result. | [optional] 
**Cached** | Pointer to **bool** | True when the same request was answered before (free). | [optional] 

## Methods

### NewFreeToolGenerateLinkedInHeadlineResponse

`func NewFreeToolGenerateLinkedInHeadlineResponse() *FreeToolGenerateLinkedInHeadlineResponse`

NewFreeToolGenerateLinkedInHeadlineResponse instantiates a new FreeToolGenerateLinkedInHeadlineResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateLinkedInHeadlineResponseWithDefaults

`func NewFreeToolGenerateLinkedInHeadlineResponseWithDefaults() *FreeToolGenerateLinkedInHeadlineResponse`

NewFreeToolGenerateLinkedInHeadlineResponseWithDefaults instantiates a new FreeToolGenerateLinkedInHeadlineResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHeadlines

`func (o *FreeToolGenerateLinkedInHeadlineResponse) GetHeadlines() []string`

GetHeadlines returns the Headlines field if non-nil, zero value otherwise.

### GetHeadlinesOk

`func (o *FreeToolGenerateLinkedInHeadlineResponse) GetHeadlinesOk() (*[]string, bool)`

GetHeadlinesOk returns a tuple with the Headlines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeadlines

`func (o *FreeToolGenerateLinkedInHeadlineResponse) SetHeadlines(v []string)`

SetHeadlines sets Headlines field to given value.

### HasHeadlines

`func (o *FreeToolGenerateLinkedInHeadlineResponse) HasHeadlines() bool`

HasHeadlines returns a boolean if a field has been set.

### GetCreditsSpent

`func (o *FreeToolGenerateLinkedInHeadlineResponse) GetCreditsSpent() int32`

GetCreditsSpent returns the CreditsSpent field if non-nil, zero value otherwise.

### GetCreditsSpentOk

`func (o *FreeToolGenerateLinkedInHeadlineResponse) GetCreditsSpentOk() (*int32, bool)`

GetCreditsSpentOk returns a tuple with the CreditsSpent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsSpent

`func (o *FreeToolGenerateLinkedInHeadlineResponse) SetCreditsSpent(v int32)`

SetCreditsSpent sets CreditsSpent field to given value.

### HasCreditsSpent

`func (o *FreeToolGenerateLinkedInHeadlineResponse) HasCreditsSpent() bool`

HasCreditsSpent returns a boolean if a field has been set.

### GetCached

`func (o *FreeToolGenerateLinkedInHeadlineResponse) GetCached() bool`

GetCached returns the Cached field if non-nil, zero value otherwise.

### GetCachedOk

`func (o *FreeToolGenerateLinkedInHeadlineResponse) GetCachedOk() (*bool, bool)`

GetCachedOk returns a tuple with the Cached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCached

`func (o *FreeToolGenerateLinkedInHeadlineResponse) SetCached(v bool)`

SetCached sets Cached field to given value.

### HasCached

`func (o *FreeToolGenerateLinkedInHeadlineResponse) HasCached() bool`

HasCached returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


