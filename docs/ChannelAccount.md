# ChannelAccount

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Uuid** | **string** |  | 
**Name** | **string** |  | 
**Username** | Pointer to **NullableString** | Telegram public channel username; null for private channels, Discord and Slack. | [optional] 
**Image** | Pointer to **NullableString** |  | [optional] 
**Provider** | **string** |  | 
**Data** | **map[string]interface{}** | Provider metadata (Telegram &#x60;chat_id&#x60;, Discord &#x60;channel_id&#x60;/&#x60;guild_id&#x60;, Slack &#x60;team_id&#x60;). | 
**Authorized** | **bool** |  | 
**ProfileUrl** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | **string** |  | 

## Methods

### NewChannelAccount

`func NewChannelAccount(id int32, uuid string, name string, provider string, data map[string]interface{}, authorized bool, createdAt string, ) *ChannelAccount`

NewChannelAccount instantiates a new ChannelAccount object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChannelAccountWithDefaults

`func NewChannelAccountWithDefaults() *ChannelAccount`

NewChannelAccountWithDefaults instantiates a new ChannelAccount object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ChannelAccount) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ChannelAccount) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ChannelAccount) SetId(v int32)`

SetId sets Id field to given value.


### GetUuid

`func (o *ChannelAccount) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *ChannelAccount) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *ChannelAccount) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *ChannelAccount) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ChannelAccount) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ChannelAccount) SetName(v string)`

SetName sets Name field to given value.


### GetUsername

`func (o *ChannelAccount) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *ChannelAccount) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *ChannelAccount) SetUsername(v string)`

SetUsername sets Username field to given value.

### HasUsername

`func (o *ChannelAccount) HasUsername() bool`

HasUsername returns a boolean if a field has been set.

### SetUsernameNil

`func (o *ChannelAccount) SetUsernameNil(b bool)`

 SetUsernameNil sets the value for Username to be an explicit nil

### UnsetUsername
`func (o *ChannelAccount) UnsetUsername()`

UnsetUsername ensures that no value is present for Username, not even an explicit nil
### GetImage

`func (o *ChannelAccount) GetImage() string`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *ChannelAccount) GetImageOk() (*string, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *ChannelAccount) SetImage(v string)`

SetImage sets Image field to given value.

### HasImage

`func (o *ChannelAccount) HasImage() bool`

HasImage returns a boolean if a field has been set.

### SetImageNil

`func (o *ChannelAccount) SetImageNil(b bool)`

 SetImageNil sets the value for Image to be an explicit nil

### UnsetImage
`func (o *ChannelAccount) UnsetImage()`

UnsetImage ensures that no value is present for Image, not even an explicit nil
### GetProvider

`func (o *ChannelAccount) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *ChannelAccount) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *ChannelAccount) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetData

`func (o *ChannelAccount) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ChannelAccount) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ChannelAccount) SetData(v map[string]interface{})`

SetData sets Data field to given value.


### SetDataNil

`func (o *ChannelAccount) SetDataNil(b bool)`

 SetDataNil sets the value for Data to be an explicit nil

### UnsetData
`func (o *ChannelAccount) UnsetData()`

UnsetData ensures that no value is present for Data, not even an explicit nil
### GetAuthorized

`func (o *ChannelAccount) GetAuthorized() bool`

GetAuthorized returns the Authorized field if non-nil, zero value otherwise.

### GetAuthorizedOk

`func (o *ChannelAccount) GetAuthorizedOk() (*bool, bool)`

GetAuthorizedOk returns a tuple with the Authorized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthorized

`func (o *ChannelAccount) SetAuthorized(v bool)`

SetAuthorized sets Authorized field to given value.


### GetProfileUrl

`func (o *ChannelAccount) GetProfileUrl() string`

GetProfileUrl returns the ProfileUrl field if non-nil, zero value otherwise.

### GetProfileUrlOk

`func (o *ChannelAccount) GetProfileUrlOk() (*string, bool)`

GetProfileUrlOk returns a tuple with the ProfileUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProfileUrl

`func (o *ChannelAccount) SetProfileUrl(v string)`

SetProfileUrl sets ProfileUrl field to given value.

### HasProfileUrl

`func (o *ChannelAccount) HasProfileUrl() bool`

HasProfileUrl returns a boolean if a field has been set.

### SetProfileUrlNil

`func (o *ChannelAccount) SetProfileUrlNil(b bool)`

 SetProfileUrlNil sets the value for ProfileUrl to be an explicit nil

### UnsetProfileUrl
`func (o *ChannelAccount) UnsetProfileUrl()`

UnsetProfileUrl ensures that no value is present for ProfileUrl, not even an explicit nil
### GetCreatedAt

`func (o *ChannelAccount) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ChannelAccount) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ChannelAccount) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


