# Post

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Uuid** | **string** |  | 
**Status** | [**PostStatus**](PostStatus.md) |  | 
**Accounts** | [**[]Account**](Account.md) |  | 
**Versions** | [**[]PostVersion**](PostVersion.md) |  | 
**Tags** | [**[]Tag**](Tag.md) |  | 
**ScheduledAt** | Pointer to **time.Time** |  | [optional] 
**PublishedAt** | Pointer to **time.Time** |  | [optional] 
**CreatedAt** | **time.Time** |  | 
**Trashed** | **bool** |  | 

## Methods

### NewPost

`func NewPost(id int32, uuid string, status PostStatus, accounts []Account, versions []PostVersion, tags []Tag, createdAt time.Time, trashed bool, ) *Post`

NewPost instantiates a new Post object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostWithDefaults

`func NewPostWithDefaults() *Post`

NewPostWithDefaults instantiates a new Post object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Post) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Post) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Post) SetId(v int32)`

SetId sets Id field to given value.


### GetUuid

`func (o *Post) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *Post) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *Post) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetStatus

`func (o *Post) GetStatus() PostStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Post) GetStatusOk() (*PostStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Post) SetStatus(v PostStatus)`

SetStatus sets Status field to given value.


### GetAccounts

`func (o *Post) GetAccounts() []Account`

GetAccounts returns the Accounts field if non-nil, zero value otherwise.

### GetAccountsOk

`func (o *Post) GetAccountsOk() (*[]Account, bool)`

GetAccountsOk returns a tuple with the Accounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccounts

`func (o *Post) SetAccounts(v []Account)`

SetAccounts sets Accounts field to given value.


### GetVersions

`func (o *Post) GetVersions() []PostVersion`

GetVersions returns the Versions field if non-nil, zero value otherwise.

### GetVersionsOk

`func (o *Post) GetVersionsOk() (*[]PostVersion, bool)`

GetVersionsOk returns a tuple with the Versions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersions

`func (o *Post) SetVersions(v []PostVersion)`

SetVersions sets Versions field to given value.


### GetTags

`func (o *Post) GetTags() []Tag`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *Post) GetTagsOk() (*[]Tag, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *Post) SetTags(v []Tag)`

SetTags sets Tags field to given value.


### GetScheduledAt

`func (o *Post) GetScheduledAt() time.Time`

GetScheduledAt returns the ScheduledAt field if non-nil, zero value otherwise.

### GetScheduledAtOk

`func (o *Post) GetScheduledAtOk() (*time.Time, bool)`

GetScheduledAtOk returns a tuple with the ScheduledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledAt

`func (o *Post) SetScheduledAt(v time.Time)`

SetScheduledAt sets ScheduledAt field to given value.

### HasScheduledAt

`func (o *Post) HasScheduledAt() bool`

HasScheduledAt returns a boolean if a field has been set.

### GetPublishedAt

`func (o *Post) GetPublishedAt() time.Time`

GetPublishedAt returns the PublishedAt field if non-nil, zero value otherwise.

### GetPublishedAtOk

`func (o *Post) GetPublishedAtOk() (*time.Time, bool)`

GetPublishedAtOk returns a tuple with the PublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedAt

`func (o *Post) SetPublishedAt(v time.Time)`

SetPublishedAt sets PublishedAt field to given value.

### HasPublishedAt

`func (o *Post) HasPublishedAt() bool`

HasPublishedAt returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Post) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Post) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Post) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetTrashed

`func (o *Post) GetTrashed() bool`

GetTrashed returns the Trashed field if non-nil, zero value otherwise.

### GetTrashedOk

`func (o *Post) GetTrashedOk() (*bool, bool)`

GetTrashedOk returns a tuple with the Trashed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrashed

`func (o *Post) SetTrashed(v bool)`

SetTrashed sets Trashed field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


