# PostVersion

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | **int32** | Use &#x60;0&#x60; for the original/default version. | 
**IsOriginal** | **bool** | Must be &#x60;true&#x60; for the first version. | 
**SyncedWith** | Pointer to **NullableInt32** | Account ID of the version this version follows (&#x60;0&#x60; &#x3D; the original), or null when it is edited independently. Ignored on the original version. | [optional] 
**Content** | [**[]PostContent**](PostContent.md) | Ordered content items. Item 0 is the post. Item 1 is the first comment on Facebook Page, Instagram and LinkedIn, or the next thread post on X, Threads, Bluesky, Mastodon and Pixelfed. See &#x60;PostContent&#x60;.  | 
**Options** | Pointer to [**PostVersionOptions**](PostVersionOptions.md) |  | [optional] 

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


### GetSyncedWith

`func (o *PostVersion) GetSyncedWith() int32`

GetSyncedWith returns the SyncedWith field if non-nil, zero value otherwise.

### GetSyncedWithOk

`func (o *PostVersion) GetSyncedWithOk() (*int32, bool)`

GetSyncedWithOk returns a tuple with the SyncedWith field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSyncedWith

`func (o *PostVersion) SetSyncedWith(v int32)`

SetSyncedWith sets SyncedWith field to given value.

### HasSyncedWith

`func (o *PostVersion) HasSyncedWith() bool`

HasSyncedWith returns a boolean if a field has been set.

### SetSyncedWithNil

`func (o *PostVersion) SetSyncedWithNil(b bool)`

 SetSyncedWithNil sets the value for SyncedWith to be an explicit nil

### UnsetSyncedWith
`func (o *PostVersion) UnsetSyncedWith()`

UnsetSyncedWith ensures that no value is present for SyncedWith, not even an explicit nil
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

`func (o *PostVersion) GetOptions() PostVersionOptions`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *PostVersion) GetOptionsOk() (*PostVersionOptions, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *PostVersion) SetOptions(v PostVersionOptions)`

SetOptions sets Options field to given value.

### HasOptions

`func (o *PostVersion) HasOptions() bool`

HasOptions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


