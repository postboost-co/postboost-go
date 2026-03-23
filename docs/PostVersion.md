# PostVersion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | **int32** | Use &#x60;0&#x60; for the original/default version. | 
**IsOriginal** | **bool** | Must be &#x60;true&#x60; for the first version. | 
**Content** | [**[]PostContent**](PostContent.md) |  | 
**Options** | Pointer to **map[string]interface{}** | Platform-specific publishing options. | [optional] 

## Methods

### NewPostVersion

`func NewPostVersion(accountId int32, isOriginal bool, content []PostContent, ) *PostVersion`

NewPostVersion instantiates a new PostVersion object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostVersionWithDefaults

`func NewPostVersionWithDefaults() *PostVersion`

NewPostVersionWithDefaults instantiates a new PostVersion object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *PostVersion) GetAccountId() int32`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *PostVersion) GetAccountIdOk() (*int32, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *PostVersion) SetAccountId(v int32)`

SetAccountId sets AccountId field to given value.


### GetIsOriginal

`func (o *PostVersion) GetIsOriginal() bool`

GetIsOriginal returns the IsOriginal field if non-nil, zero value otherwise.

### GetIsOriginalOk

`func (o *PostVersion) GetIsOriginalOk() (*bool, bool)`

GetIsOriginalOk returns a tuple with the IsOriginal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsOriginal

`func (o *PostVersion) SetIsOriginal(v bool)`

SetIsOriginal sets IsOriginal field to given value.


### GetContent

`func (o *PostVersion) GetContent() []PostContent`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *PostVersion) GetContentOk() (*[]PostContent, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *PostVersion) SetContent(v []PostContent)`

SetContent sets Content field to given value.


### GetOptions

`func (o *PostVersion) GetOptions() map[string]interface{}`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *PostVersion) GetOptionsOk() (*map[string]interface{}, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *PostVersion) SetOptions(v map[string]interface{})`

SetOptions sets Options field to given value.

### HasOptions

`func (o *PostVersion) HasOptions() bool`

HasOptions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


