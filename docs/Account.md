# Account

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Uuid** | **string** |  | 
**Name** | **string** |  | 
**Username** | **string** |  | 
**Image** | Pointer to **string** |  | [optional] 
**Provider** | **string** |  | 
**Data** | **map[string]interface{}** | Provider-specific metadata. | 
**Authorized** | **bool** |  | 
**ProfileUrl** | Pointer to **string** | Public URL of the account&#39;s profile on the network, when known. | [optional] 
**PublishStatus** | Pointer to **string** | Only present when the account is embedded in a post. Publishing state of this account for the post. | [optional] 
**PublishedParts** | Pointer to **int32** | Only present when the account is embedded in a post. How many parts (for example thread items or a first comment) are live on the network. | [optional] 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewAccount

`func NewAccount(id int32, uuid string, name string, username string, provider string, data map[string]interface{}, authorized bool, createdAt time.Time, ) *Account`

NewAccount instantiates a new Account object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountWithDefaults

`func NewAccountWithDefaults() *Account`

NewAccountWithDefaults instantiates a new Account object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Account) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Account) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Account) SetId(v int32)`

SetId sets Id field to given value.


### GetUuid

`func (o *Account) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *Account) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *Account) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *Account) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Account) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Account) SetName(v string)`

SetName sets Name field to given value.


### GetUsername

`func (o *Account) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *Account) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *Account) SetUsername(v string)`

SetUsername sets Username field to given value.


### GetImage

`func (o *Account) GetImage() string`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *Account) GetImageOk() (*string, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *Account) SetImage(v string)`

SetImage sets Image field to given value.

### HasImage

`func (o *Account) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetProvider

`func (o *Account) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *Account) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *Account) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetData

`func (o *Account) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *Account) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *Account) SetData(v map[string]interface{})`

SetData sets Data field to given value.


### GetAuthorized

`func (o *Account) GetAuthorized() bool`

GetAuthorized returns the Authorized field if non-nil, zero value otherwise.

### GetAuthorizedOk

`func (o *Account) GetAuthorizedOk() (*bool, bool)`

GetAuthorizedOk returns a tuple with the Authorized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorized

`func (o *Account) SetAuthorized(v bool)`

SetAuthorized sets Authorized field to given value.


### GetProfileUrl

`func (o *Account) GetProfileUrl() string`

GetProfileUrl returns the ProfileUrl field if non-nil, zero value otherwise.

### GetProfileUrlOk

`func (o *Account) GetProfileUrlOk() (*string, bool)`

GetProfileUrlOk returns a tuple with the ProfileUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfileUrl

`func (o *Account) SetProfileUrl(v string)`

SetProfileUrl sets ProfileUrl field to given value.

### HasProfileUrl

`func (o *Account) HasProfileUrl() bool`

HasProfileUrl returns a boolean if a field has been set.

### GetPublishStatus

`func (o *Account) GetPublishStatus() string`

GetPublishStatus returns the PublishStatus field if non-nil, zero value otherwise.

### GetPublishStatusOk

`func (o *Account) GetPublishStatusOk() (*string, bool)`

GetPublishStatusOk returns a tuple with the PublishStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishStatus

`func (o *Account) SetPublishStatus(v string)`

SetPublishStatus sets PublishStatus field to given value.

### HasPublishStatus

`func (o *Account) HasPublishStatus() bool`

HasPublishStatus returns a boolean if a field has been set.

### GetPublishedParts

`func (o *Account) GetPublishedParts() int32`

GetPublishedParts returns the PublishedParts field if non-nil, zero value otherwise.

### GetPublishedPartsOk

`func (o *Account) GetPublishedPartsOk() (*int32, bool)`

GetPublishedPartsOk returns a tuple with the PublishedParts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishedParts

`func (o *Account) SetPublishedParts(v int32)`

SetPublishedParts sets PublishedParts field to given value.

### HasPublishedParts

`func (o *Account) HasPublishedParts() bool`

HasPublishedParts returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Account) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Account) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Account) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


