# MentionIdentity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Provider** | **string** | Mention provider key (network family). | 
**ProviderId** | Pointer to **NullableString** | The profile&#39;s network ID, when resolved. Never accepted from clients. | [optional] 
**Handle** | **string** |  | 
**Label** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewMentionIdentity

`func NewMentionIdentity(provider string, handle string, ) *MentionIdentity`

NewMentionIdentity instantiates a new MentionIdentity object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMentionIdentityWithDefaults

`func NewMentionIdentityWithDefaults() *MentionIdentity`

NewMentionIdentityWithDefaults instantiates a new MentionIdentity object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProvider

`func (o *MentionIdentity) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *MentionIdentity) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *MentionIdentity) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetProviderId

`func (o *MentionIdentity) GetProviderId() string`

GetProviderId returns the ProviderId field if non-nil, zero value otherwise.

### GetProviderIdOk

`func (o *MentionIdentity) GetProviderIdOk() (*string, bool)`

GetProviderIdOk returns a tuple with the ProviderId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderId

`func (o *MentionIdentity) SetProviderId(v string)`

SetProviderId sets ProviderId field to given value.

### HasProviderId

`func (o *MentionIdentity) HasProviderId() bool`

HasProviderId returns a boolean if a field has been set.

### SetProviderIdNil

`func (o *MentionIdentity) SetProviderIdNil(b bool)`

 SetProviderIdNil sets the value for ProviderId to be an explicit nil

### UnsetProviderId
`func (o *MentionIdentity) UnsetProviderId()`

UnsetProviderId ensures that no value is present for ProviderId, not even an explicit nil
### GetHandle

`func (o *MentionIdentity) GetHandle() string`

GetHandle returns the Handle field if non-nil, zero value otherwise.

### GetHandleOk

`func (o *MentionIdentity) GetHandleOk() (*string, bool)`

GetHandleOk returns a tuple with the Handle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHandle

`func (o *MentionIdentity) SetHandle(v string)`

SetHandle sets Handle field to given value.


### GetLabel

`func (o *MentionIdentity) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *MentionIdentity) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *MentionIdentity) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *MentionIdentity) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### SetLabelNil

`func (o *MentionIdentity) SetLabelNil(b bool)`

 SetLabelNil sets the value for Label to be an explicit nil

### UnsetLabel
`func (o *MentionIdentity) UnsetLabel()`

UnsetLabel ensures that no value is present for Label, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


