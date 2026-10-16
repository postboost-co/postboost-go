# Mention

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Reference** | **int32** | Write &#x60;{{mention:&lt;reference&gt;}}&#x60; in a post body to mention this entry; it is resolved to each network&#39;s identity at publish time. | 
**Name** | **string** |  | 
**Avatar** | Pointer to **NullableString** |  | [optional] 
**Identities** | Pointer to [**[]MentionIdentity**](MentionIdentity.md) |  | [optional] 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewMention

`func NewMention(id string, reference int32, name string, createdAt time.Time, ) *Mention`

NewMention instantiates a new Mention object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMentionWithDefaults

`func NewMentionWithDefaults() *Mention`

NewMentionWithDefaults instantiates a new Mention object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Mention) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Mention) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Mention) SetId(v string)`

SetId sets Id field to given value.


### GetReference

`func (o *Mention) GetReference() int32`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *Mention) GetReferenceOk() (*int32, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *Mention) SetReference(v int32)`

SetReference sets Reference field to given value.


### GetName

`func (o *Mention) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Mention) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Mention) SetName(v string)`

SetName sets Name field to given value.


### GetAvatar

`func (o *Mention) GetAvatar() string`

GetAvatar returns the Avatar field if non-nil, zero value otherwise.

### GetAvatarOk

`func (o *Mention) GetAvatarOk() (*string, bool)`

GetAvatarOk returns a tuple with the Avatar field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatar

`func (o *Mention) SetAvatar(v string)`

SetAvatar sets Avatar field to given value.

### HasAvatar

`func (o *Mention) HasAvatar() bool`

HasAvatar returns a boolean if a field has been set.

### SetAvatarNil

`func (o *Mention) SetAvatarNil(b bool)`

 SetAvatarNil sets the value for Avatar to be an explicit nil

### UnsetAvatar
`func (o *Mention) UnsetAvatar()`

UnsetAvatar ensures that no value is present for Avatar, not even an explicit nil
### GetIdentities

`func (o *Mention) GetIdentities() []MentionIdentity`

GetIdentities returns the Identities field if non-nil, zero value otherwise.

### GetIdentitiesOk

`func (o *Mention) GetIdentitiesOk() (*[]MentionIdentity, bool)`

GetIdentitiesOk returns a tuple with the Identities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentities

`func (o *Mention) SetIdentities(v []MentionIdentity)`

SetIdentities sets Identities field to given value.

### HasIdentities

`func (o *Mention) HasIdentities() bool`

HasIdentities returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Mention) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Mention) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Mention) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


