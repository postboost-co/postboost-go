# MentionIdentityInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Provider** | **string** | Mention provider key. One identity per provider. | 
**Handle** | **string** | Profile handle; a leading &#x60;@&#x60; is stripped. | 
**Label** | Pointer to **NullableString** |  | [optional] 
**Token** | Pointer to **NullableString** | Sealed lookup result that names the profile&#39;s network ID. | [optional] 
**AccountUuid** | Pointer to **NullableString** | A connected account of this workspace that names the profile. Wins over &#x60;token&#x60; when both are sent. | [optional] 

## Methods

### NewMentionIdentityInput

`func NewMentionIdentityInput(provider string, handle string, ) *MentionIdentityInput`

NewMentionIdentityInput instantiates a new MentionIdentityInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMentionIdentityInputWithDefaults

`func NewMentionIdentityInputWithDefaults() *MentionIdentityInput`

NewMentionIdentityInputWithDefaults instantiates a new MentionIdentityInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProvider

`func (o *MentionIdentityInput) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *MentionIdentityInput) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *MentionIdentityInput) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetHandle

`func (o *MentionIdentityInput) GetHandle() string`

GetHandle returns the Handle field if non-nil, zero value otherwise.

### GetHandleOk

`func (o *MentionIdentityInput) GetHandleOk() (*string, bool)`

GetHandleOk returns a tuple with the Handle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHandle

`func (o *MentionIdentityInput) SetHandle(v string)`

SetHandle sets Handle field to given value.


### GetLabel

`func (o *MentionIdentityInput) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *MentionIdentityInput) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *MentionIdentityInput) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *MentionIdentityInput) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### SetLabelNil

`func (o *MentionIdentityInput) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *MentionIdentityInput) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil
### GetToken

`func (o *MentionIdentityInput) GetToken() string`

GetToken returns the Token field if non-nil, zero value otherwise.

### GetTokenOk

`func (o *MentionIdentityInput) GetTokenOk() (*string, bool)`

GetTokenOk returns a tuple with the Token field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToken

`func (o *MentionIdentityInput) SetToken(v string)`

SetToken sets Token field to given value.

### HasToken

`func (o *MentionIdentityInput) HasToken() bool`

HasToken returns a boolean if a field has been set.

### SetTokenNil

`func (o *MentionIdentityInput) SetTokenNil(b bool)`

 SetTokenNil sets the value for Token to be an explicit nil

### UnsetToken
`func (o *MentionIdentityInput) UnsetToken()`

UnsetToken ensures that no value is present for Token, not even an explicit nil
### GetAccountUuid

`func (o *MentionIdentityInput) GetAccountUuid() string`

GetAccountUuid returns the AccountUuid field if non-nil, zero value otherwise.

### GetAccountUuidOk

`func (o *MentionIdentityInput) GetAccountUuidOk() (*string, bool)`

GetAccountUuidOk returns a tuple with the AccountUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountUuid

`func (o *MentionIdentityInput) SetAccountUuid(v string)`

SetAccountUuid sets AccountUuid field to given value.

### HasAccountUuid

`func (o *MentionIdentityInput) HasAccountUuid() bool`

HasAccountUuid returns a boolean if a field has been set.

### SetAccountUuidNil

`func (o *MentionIdentityInput) SetAccountUuidNil(b bool)`

 SetAccountUuidNil sets the value for AccountUuid to be an explicit nil

### UnsetAccountUuid
`func (o *MentionIdentityInput) UnsetAccountUuid()`

UnsetAccountUuid ensures that no value is present for AccountUuid, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


