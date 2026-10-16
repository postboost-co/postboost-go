# FreeToolGenerateSocialPostsFromBlogResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Posts** | Pointer to [**[]FreeToolGenerateSocialPostsFromBlogResponsePostsInner**](FreeToolGenerateSocialPostsFromBlogResponsePostsInner.md) | One post per platform that came back, in the order asked. | [optional] 
**Source** | Pointer to [**FreeToolGenerateSocialPostsFromBlogResponseSource**](FreeToolGenerateSocialPostsFromBlogResponseSource.md) |  | [optional] 
**Warnings** | Pointer to [**[]FreeToolGenerateSocialPostsFromBlogResponseWarningsInner**](FreeToolGenerateSocialPostsFromBlogResponseWarningsInner.md) |  | [optional] 
**CreditsSpent** | Pointer to **int32** | AI credits this call took from the workspace: one per post. | [optional] 

## Methods

### NewFreeToolGenerateSocialPostsFromBlogResponse

`func NewFreeToolGenerateSocialPostsFromBlogResponse() *FreeToolGenerateSocialPostsFromBlogResponse`

NewFreeToolGenerateSocialPostsFromBlogResponse instantiates a new FreeToolGenerateSocialPostsFromBlogResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateSocialPostsFromBlogResponseWithDefaults

`func NewFreeToolGenerateSocialPostsFromBlogResponseWithDefaults() *FreeToolGenerateSocialPostsFromBlogResponse`

NewFreeToolGenerateSocialPostsFromBlogResponseWithDefaults instantiates a new FreeToolGenerateSocialPostsFromBlogResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPosts

`func (o *FreeToolGenerateSocialPostsFromBlogResponse) GetPosts() []FreeToolGenerateSocialPostsFromBlogResponsePostsInner`

GetPosts returns the Posts field if non-nil, zero value otherwise.

### GetPostsOk

`func (o *FreeToolGenerateSocialPostsFromBlogResponse) GetPostsOk() (*[]FreeToolGenerateSocialPostsFromBlogResponsePostsInner, bool)`

GetPostsOk returns a tuple with the Posts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosts

`func (o *FreeToolGenerateSocialPostsFromBlogResponse) SetPosts(v []FreeToolGenerateSocialPostsFromBlogResponsePostsInner)`

SetPosts sets Posts field to given value.

### HasPosts

`func (o *FreeToolGenerateSocialPostsFromBlogResponse) HasPosts() bool`

HasPosts returns a boolean if a field has been set.

### GetSource

`func (o *FreeToolGenerateSocialPostsFromBlogResponse) GetSource() FreeToolGenerateSocialPostsFromBlogResponseSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *FreeToolGenerateSocialPostsFromBlogResponse) GetSourceOk() (*FreeToolGenerateSocialPostsFromBlogResponseSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *FreeToolGenerateSocialPostsFromBlogResponse) SetSource(v FreeToolGenerateSocialPostsFromBlogResponseSource)`

SetSource sets Source field to given value.

### HasSource

`func (o *FreeToolGenerateSocialPostsFromBlogResponse) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetWarnings

`func (o *FreeToolGenerateSocialPostsFromBlogResponse) GetWarnings() []FreeToolGenerateSocialPostsFromBlogResponseWarningsInner`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *FreeToolGenerateSocialPostsFromBlogResponse) GetWarningsOk() (*[]FreeToolGenerateSocialPostsFromBlogResponseWarningsInner, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *FreeToolGenerateSocialPostsFromBlogResponse) SetWarnings(v []FreeToolGenerateSocialPostsFromBlogResponseWarningsInner)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *FreeToolGenerateSocialPostsFromBlogResponse) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.

### GetCreditsSpent

`func (o *FreeToolGenerateSocialPostsFromBlogResponse) GetCreditsSpent() int32`

GetCreditsSpent returns the CreditsSpent field if non-nil, zero value otherwise.

### GetCreditsSpentOk

`func (o *FreeToolGenerateSocialPostsFromBlogResponse) GetCreditsSpentOk() (*int32, bool)`

GetCreditsSpentOk returns a tuple with the CreditsSpent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsSpent

`func (o *FreeToolGenerateSocialPostsFromBlogResponse) SetCreditsSpent(v int32)`

SetCreditsSpent sets CreditsSpent field to given value.

### HasCreditsSpent

`func (o *FreeToolGenerateSocialPostsFromBlogResponse) HasCreditsSpent() bool`

HasCreditsSpent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


