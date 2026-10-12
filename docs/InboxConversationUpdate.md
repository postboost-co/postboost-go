# InboxConversationUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** |  | [optional] 
**Unread** | Pointer to **bool** |  | [optional] 

## Methods

### NewInboxConversationUpdate

`func NewInboxConversationUpdate() *InboxConversationUpdate`

NewInboxConversationUpdate instantiates a new InboxConversationUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInboxConversationUpdateWithDefaults

`func NewInboxConversationUpdateWithDefaults() *InboxConversationUpdate`

NewInboxConversationUpdateWithDefaults instantiates a new InboxConversationUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *InboxConversationUpdate) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *InboxConversationUpdate) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *InboxConversationUpdate) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *InboxConversationUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetUnread

`func (o *InboxConversationUpdate) GetUnread() bool`

GetUnread returns the Unread field if non-nil, zero value otherwise.

### GetUnreadOk

`func (o *InboxConversationUpdate) GetUnreadOk() (*bool, bool)`

GetUnreadOk returns a tuple with the Unread field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnread

`func (o *InboxConversationUpdate) SetUnread(v bool)`

SetUnread sets Unread field to given value.

### HasUnread

`func (o *InboxConversationUpdate) HasUnread() bool`

HasUnread returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


