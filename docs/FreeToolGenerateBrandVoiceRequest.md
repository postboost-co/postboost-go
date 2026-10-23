# FreeToolGenerateBrandVoiceRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Posts** | **[]string** | Your own posts, one per item: 3 to 10 different posts of 20 to 3,200 characters, 20,000 in total. An exact copy counts once. | 
**BusinessName** | Pointer to **string** | Your business name, used as given (never generated). | [optional] 
**Industry** | Pointer to **string** | Your industry, used as given (never generated). | [optional] 
**Workspace** | Pointer to **string** | UUID of the workspace whose AI credits pay for the call. Default: your active workspace (a scoped API key: its own workspace). | [optional] 

## Methods

### NewFreeToolGenerateBrandVoiceRequest

`func NewFreeToolGenerateBrandVoiceRequest(posts []string, ) *FreeToolGenerateBrandVoiceRequest`

NewFreeToolGenerateBrandVoiceRequest instantiates a new FreeToolGenerateBrandVoiceRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateBrandVoiceRequestWithDefaults

`func NewFreeToolGenerateBrandVoiceRequestWithDefaults() *FreeToolGenerateBrandVoiceRequest`

NewFreeToolGenerateBrandVoiceRequestWithDefaults instantiates a new FreeToolGenerateBrandVoiceRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPosts

`func (o *FreeToolGenerateBrandVoiceRequest) GetPosts() []string`

GetPosts returns the Posts field if non-nil, zero value otherwise.

### GetPostsOk

`func (o *FreeToolGenerateBrandVoiceRequest) GetPostsOk() (*[]string, bool)`

GetPostsOk returns a tuple with the Posts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPosts

`func (o *FreeToolGenerateBrandVoiceRequest) SetPosts(v []string)`

SetPosts sets Posts field to given value.


### GetBusinessName

`func (o *FreeToolGenerateBrandVoiceRequest) GetBusinessName() string`

GetBusinessName returns the BusinessName field if non-nil, zero value otherwise.

### GetBusinessNameOk

`func (o *FreeToolGenerateBrandVoiceRequest) GetBusinessNameOk() (*string, bool)`

GetBusinessNameOk returns a tuple with the BusinessName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusinessName

`func (o *FreeToolGenerateBrandVoiceRequest) SetBusinessName(v string)`

SetBusinessName sets BusinessName field to given value.

### HasBusinessName

`func (o *FreeToolGenerateBrandVoiceRequest) HasBusinessName() bool`

HasBusinessName returns a boolean if a field has been set.

### GetIndustry

`func (o *FreeToolGenerateBrandVoiceRequest) GetIndustry() string`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *FreeToolGenerateBrandVoiceRequest) GetIndustryOk() (*string, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *FreeToolGenerateBrandVoiceRequest) SetIndustry(v string)`

SetIndustry sets Industry field to given value.

### HasIndustry

`func (o *FreeToolGenerateBrandVoiceRequest) HasIndustry() bool`

HasIndustry returns a boolean if a field has been set.

### GetWorkspace

`func (o *FreeToolGenerateBrandVoiceRequest) GetWorkspace() string`

GetWorkspace returns the Workspace field if non-nil, zero value otherwise.

### GetWorkspaceOk

`func (o *FreeToolGenerateBrandVoiceRequest) GetWorkspaceOk() (*string, bool)`

GetWorkspaceOk returns a tuple with the Workspace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspace

`func (o *FreeToolGenerateBrandVoiceRequest) SetWorkspace(v string)`

SetWorkspace sets Workspace field to given value.

### HasWorkspace

`func (o *FreeToolGenerateBrandVoiceRequest) HasWorkspace() bool`

HasWorkspace returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


