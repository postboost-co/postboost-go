# CreatePost201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Uuid** | **string** |  | 
**Status** | [**PostStatus**](PostStatus.md) |  | 
**PublishProgress** | Pointer to [**PublishProgress**](PublishProgress.md) | Only present while the post is publishing. | [optional] 
**Accounts** | [**[]Account**](Account.md) |  | 
**Versions** | [**[]PostVersion**](PostVersion.md) |  | 
**Tags** | [**[]Tag**](Tag.md) |  | 
**ScheduledAt** | Pointer to **string** | &#x60;Y-m-d H:i:s&#x60; in UTC (not RFC 3339). | [optional] 
**PublishedAt** | Pointer to **string** | &#x60;Y-m-d H:i:s&#x60; in UTC (not RFC 3339). | [optional] 
**CreatedAt** | **string** | &#x60;Y-m-d H:i:s&#x60; in UTC (not RFC 3339). | 
**Trashed** | **bool** |  | 
**Warnings** | Pointer to [**[]PostWarning**](PostWarning.md) | Present only when there is at least one warning. | [optional] 

## Methods

### NewCreatePost201Response

`func NewCreatePost201Response(id int32, uuid string, status PostStatus, accounts []Account, versions []PostVersion, tags []Tag, createdAt string, trashed bool, ) *CreatePost201Response`

NewCreatePost201Response instantiates a new CreatePost201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreatePost201ResponseWithDefaults

`func NewCreatePost201ResponseWithDefaults() *CreatePost201Response`

NewCreatePost201ResponseWithDefaults instantiates a new CreatePost201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreatePost201Response) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreatePost201Response) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreatePost201Response) SetId(v int32)`

SetId sets Id field to given value.


### GetUuid

`func (o *CreatePost201Response) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *CreatePost201Response) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *CreatePost201Response) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetStatus

`func (o *CreatePost201Response) GetStatus() PostStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CreatePost201Response) GetStatusOk() (*PostStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CreatePost201Response) SetStatus(v PostStatus)`

SetStatus sets Status field to given value.


### GetPublishProgress

`func (o *CreatePost201Response) GetPublishProgress() PublishProgress`

GetPublishProgress returns the PublishProgress field if non-nil, zero value otherwise.

### GetPublishProgressOk

`func (o *CreatePost201Response) GetPublishProgressOk() (*PublishProgress, bool)`

GetPublishProgressOk returns a tuple with the PublishProgress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishProgress

`func (o *CreatePost201Response) SetPublishProgress(v PublishProgress)`

SetPublishProgress sets PublishProgress field to given value.

### HasPublishProgress

`func (o *CreatePost201Response) HasPublishProgress() bool`

HasPublishProgress returns a boolean if a field has been set.

### GetAccounts

`func (o *CreatePost201Response) GetAccounts() []Account`

GetAccounts returns the Accounts field if non-nil, zero value otherwise.

### GetAccountsOk

`func (o *CreatePost201Response) GetAccountsOk() (*[]Account, bool)`

GetAccountsOk returns a tuple with the Accounts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccounts

`func (o *CreatePost201Response) SetAccounts(v []Account)`

SetAccounts sets Accounts field to given value.


### GetVersions

`func (o *CreatePost201Response) GetVersions() []PostVersion`

GetVersions returns the Versions field if non-nil, zero value otherwise.

### GetVersionsOk

`func (o *CreatePost201Response) GetVersionsOk() (*[]PostVersion, bool)`

GetVersionsOk returns a tuple with the Versions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersions

`func (o *CreatePost201Response) SetVersions(v []PostVersion)`

SetVersions sets Versions field to given value.


### GetTags

`func (o *CreatePost201Response) GetTags() []Tag`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *CreatePost201Response) GetTagsOk() (*[]Tag, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *CreatePost201Response) SetTags(v []Tag)`

SetTags sets Tags field to given value.


### GetScheduledAt

`func (o *CreatePost201Response) GetScheduledAt() string`

GetScheduledAt returns the ScheduledAt field if non-nil, zero value otherwise.

### GetScheduledAtOk

`func (o *CreatePost201Response) GetScheduledAtOk() (*string, bool)`

GetScheduledAtOk returns a tuple with the ScheduledAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledAt

`func (o *CreatePost201Response) SetScheduledAt(v string)`

SetScheduledAt sets ScheduledAt field to given value.

### HasScheduledAt

`func (o *CreatePost201Response) HasScheduledAt() bool`

HasScheduledAt returns a boolean if a field has been set.

### GetPublishedAt

`func (o *CreatePost201Response) GetPublishedAt() string`

GetPublishedAt returns the PublishedAt field if non-nil, zero value otherwise.

### GetPublishedAtOk

`func (o *CreatePost201Response) GetPublishedAtOk() (*string, bool)`

GetPublishedAtOk returns a tuple with the PublishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedAt

`func (o *CreatePost201Response) SetPublishedAt(v string)`

SetPublishedAt sets PublishedAt field to given value.

### HasPublishedAt

`func (o *CreatePost201Response) HasPublishedAt() bool`

HasPublishedAt returns a boolean if a field has been set.

### GetCreatedAt

`func (o *CreatePost201Response) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreatePost201Response) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreatePost201Response) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetTrashed

`func (o *CreatePost201Response) GetTrashed() bool`

GetTrashed returns the Trashed field if non-nil, zero value otherwise.

### GetTrashedOk

`func (o *CreatePost201Response) GetTrashedOk() (*bool, bool)`

GetTrashedOk returns a tuple with the Trashed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrashed

`func (o *CreatePost201Response) SetTrashed(v bool)`

SetTrashed sets Trashed field to given value.


### GetWarnings

`func (o *CreatePost201Response) GetWarnings() []PostWarning`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *CreatePost201Response) GetWarningsOk() (*[]PostWarning, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *CreatePost201Response) SetWarnings(v []PostWarning)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *CreatePost201Response) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


