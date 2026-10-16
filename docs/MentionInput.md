# MentionInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Avatar** | Pointer to **NullableString** |  | [optional] 
**Identities** | Pointer to [**[]MentionIdentityInput**](MentionIdentityInput.md) |  | [optional] 

## Methods

### NewMentionInput

`func NewMentionInput(name string, ) *MentionInput`

NewMentionInput instantiates a new MentionInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMentionInputWithDefaults

`func NewMentionInputWithDefaults() *MentionInput`

NewMentionInputWithDefaults instantiates a new MentionInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *MentionInput) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *MentionInput) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *MentionInput) SetName(v string)`

SetName sets Name field to given value.


### GetAvatar

`func (o *MentionInput) GetAvatar() string`

GetAvatar returns the Avatar field if non-nil, zero value otherwise.

### GetAvatarOk

`func (o *MentionInput) GetAvatarOk() (*string, bool)`

GetAvatarOk returns a tuple with the Avatar field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvatar

`func (o *MentionInput) SetAvatar(v string)`

SetAvatar sets Avatar field to given value.

### HasAvatar

`func (o *MentionInput) HasAvatar() bool`

HasAvatar returns a boolean if a field has been set.

### SetAvatarNil

`func (o *MentionInput) SetAvatarNil(b bool)`

 SetAvatarNil sets the value for Avatar to be an explicit nil

### UnsetAvatar
`func (o *MentionInput) UnsetAvatar()`

UnsetAvatar ensures that no value is present for Avatar, not even an explicit nil
### GetIdentities

`func (o *MentionInput) GetIdentities() []MentionIdentityInput`

GetIdentities returns the Identities field if non-nil, zero value otherwise.

### GetIdentitiesOk

`func (o *MentionInput) GetIdentitiesOk() (*[]MentionIdentityInput, bool)`

GetIdentitiesOk returns a tuple with the Identities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentities

`func (o *MentionInput) SetIdentities(v []MentionIdentityInput)`

SetIdentities sets Identities field to given value.

### HasIdentities

`func (o *MentionInput) HasIdentities() bool`

HasIdentities returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


