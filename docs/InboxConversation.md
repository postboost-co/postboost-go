# InboxConversation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Conversation UUID. | 
**Provider** | **string** |  | 
**Type** | Pointer to **NullableString** |  | [optional] 
**Status** | **string** |  | 
**Unread** | **bool** |  | 
**Sentiment** | Pointer to **NullableString** |  | [optional] 
**AiLabel** | Pointer to **NullableString** |  | [optional] 
**IsSpam** | Pointer to **bool** |  | [optional] 
**IsHidden** | Pointer to **bool** |  | [optional] 
**ProviderPostId** | Pointer to **NullableString** |  | [optional] 
**Account** | Pointer to [**InboxConversationAccount**](InboxConversationAccount.md) |  | [optional] 
**Author** | Pointer to [**InboxMessageAuthor**](InboxMessageAuthor.md) |  | [optional] 
**LatestMessage** | Pointer to **map[string]interface{}** | Only in lists. | [optional] 
**Messages** | Pointer to [**[]InboxMessage**](InboxMessage.md) | Only on &#x60;GET inbox/conversations/{conversationId}&#x60;. | [optional] 
**LastMessageAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewInboxConversation

`func NewInboxConversation(id string, provider string, status string, unread bool, ) *InboxConversation`

NewInboxConversation instantiates a new InboxConversation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInboxConversationWithDefaults

`func NewInboxConversationWithDefaults() *InboxConversation`

NewInboxConversationWithDefaults instantiates a new InboxConversation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InboxConversation) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InboxConversation) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InboxConversation) SetId(v string)`

SetId sets Id field to given value.


### GetProvider

`func (o *InboxConversation) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *InboxConversation) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *InboxConversation) SetProvider(v string)`

SetProvider sets Provider field to given value.


### GetType

`func (o *InboxConversation) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *InboxConversation) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *InboxConversation) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *InboxConversation) HasType() bool`

HasType returns a boolean if a field has been set.

### SetTypeNil

`func (o *InboxConversation) SetTypeNil(b bool)`

 SetTypeNil sets the value for Type to be an explicit nil

### UnsetType
`func (o *InboxConversation) UnsetType()`

UnsetType ensures that no value is present for Type, not even an explicit nil
### GetStatus

`func (o *InboxConversation) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *InboxConversation) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *InboxConversation) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetUnread

`func (o *InboxConversation) GetUnread() bool`

GetUnread returns the Unread field if non-nil, zero value otherwise.

### GetUnreadOk

`func (o *InboxConversation) GetUnreadOk() (*bool, bool)`

GetUnreadOk returns a tuple with the Unread field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnread

`func (o *InboxConversation) SetUnread(v bool)`

SetUnread sets Unread field to given value.


### GetSentiment

`func (o *InboxConversation) GetSentiment() string`

GetSentiment returns the Sentiment field if non-nil, zero value otherwise.

### GetSentimentOk

`func (o *InboxConversation) GetSentimentOk() (*string, bool)`

GetSentimentOk returns a tuple with the Sentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentiment

`func (o *InboxConversation) SetSentiment(v string)`

SetSentiment sets Sentiment field to given value.

### HasSentiment

`func (o *InboxConversation) HasSentiment() bool`

HasSentiment returns a boolean if a field has been set.

### SetSentimentNil

`func (o *InboxConversation) SetSentimentNil(b bool)`

 SetSentimentNil sets the value for Sentiment to be an explicit nil

### UnsetSentiment
`func (o *InboxConversation) UnsetSentiment()`

UnsetSentiment ensures that no value is present for Sentiment, not even an explicit nil
### GetAiLabel

`func (o *InboxConversation) GetAiLabel() string`

GetAiLabel returns the AiLabel field if non-nil, zero value otherwise.

### GetAiLabelOk

`func (o *InboxConversation) GetAiLabelOk() (*string, bool)`

GetAiLabelOk returns a tuple with the AiLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAiLabel

`func (o *InboxConversation) SetAiLabel(v string)`

SetAiLabel sets AiLabel field to given value.

### HasAiLabel

`func (o *InboxConversation) HasAiLabel() bool`

HasAiLabel returns a boolean if a field has been set.

### SetAiLabelNil

`func (o *InboxConversation) SetAiLabelNil(b bool)`

 SetAiLabelNil sets the value for AiLabel to be an explicit nil

### UnsetAiLabel
`func (o *InboxConversation) UnsetAiLabel()`

UnsetAiLabel ensures that no value is present for AiLabel, not even an explicit nil
### GetIsSpam

`func (o *InboxConversation) GetIsSpam() bool`

GetIsSpam returns the IsSpam field if non-nil, zero value otherwise.

### GetIsSpamOk

`func (o *InboxConversation) GetIsSpamOk() (*bool, bool)`

GetIsSpamOk returns a tuple with the IsSpam field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSpam

`func (o *InboxConversation) SetIsSpam(v bool)`

SetIsSpam sets IsSpam field to given value.

### HasIsSpam

`func (o *InboxConversation) HasIsSpam() bool`

HasIsSpam returns a boolean if a field has been set.

### GetIsHidden

`func (o *InboxConversation) GetIsHidden() bool`

GetIsHidden returns the IsHidden field if non-nil, zero value otherwise.

### GetIsHiddenOk

`func (o *InboxConversation) GetIsHiddenOk() (*bool, bool)`

GetIsHiddenOk returns a tuple with the IsHidden field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsHidden

`func (o *InboxConversation) SetIsHidden(v bool)`

SetIsHidden sets IsHidden field to given value.

### HasIsHidden

`func (o *InboxConversation) HasIsHidden() bool`

HasIsHidden returns a boolean if a field has been set.

### GetProviderPostId

`func (o *InboxConversation) GetProviderPostId() string`

GetProviderPostId returns the ProviderPostId field if non-nil, zero value otherwise.

### GetProviderPostIdOk

`func (o *InboxConversation) GetProviderPostIdOk() (*string, bool)`

GetProviderPostIdOk returns a tuple with the ProviderPostId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProviderPostId

`func (o *InboxConversation) SetProviderPostId(v string)`

SetProviderPostId sets ProviderPostId field to given value.

### HasProviderPostId

`func (o *InboxConversation) HasProviderPostId() bool`

HasProviderPostId returns a boolean if a field has been set.

### SetProviderPostIdNil

`func (o *InboxConversation) SetProviderPostIdNil(b bool)`

 SetProviderPostIdNil sets the value for ProviderPostId to be an explicit nil

### UnsetProviderPostId
`func (o *InboxConversation) UnsetProviderPostId()`

UnsetProviderPostId ensures that no value is present for ProviderPostId, not even an explicit nil
### GetAccount

`func (o *InboxConversation) GetAccount() InboxConversationAccount`

GetAccount returns the Account field if non-nil, zero value otherwise.

### GetAccountOk

`func (o *InboxConversation) GetAccountOk() (*InboxConversationAccount, bool)`

GetAccountOk returns a tuple with the Account field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccount

`func (o *InboxConversation) SetAccount(v InboxConversationAccount)`

SetAccount sets Account field to given value.

### HasAccount

`func (o *InboxConversation) HasAccount() bool`

HasAccount returns a boolean if a field has been set.

### GetAuthor

`func (o *InboxConversation) GetAuthor() InboxMessageAuthor`

GetAuthor returns the Author field if non-nil, zero value otherwise.

### GetAuthorOk

`func (o *InboxConversation) GetAuthorOk() (*InboxMessageAuthor, bool)`

GetAuthorOk returns a tuple with the Author field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthor

`func (o *InboxConversation) SetAuthor(v InboxMessageAuthor)`

SetAuthor sets Author field to given value.

### HasAuthor

`func (o *InboxConversation) HasAuthor() bool`

HasAuthor returns a boolean if a field has been set.

### GetLatestMessage

`func (o *InboxConversation) GetLatestMessage() map[string]interface{}`

GetLatestMessage returns the LatestMessage field if non-nil, zero value otherwise.

### GetLatestMessageOk

`func (o *InboxConversation) GetLatestMessageOk() (*map[string]interface{}, bool)`

GetLatestMessageOk returns a tuple with the LatestMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLatestMessage

`func (o *InboxConversation) SetLatestMessage(v map[string]interface{})`

SetLatestMessage sets LatestMessage field to given value.

### HasLatestMessage

`func (o *InboxConversation) HasLatestMessage() bool`

HasLatestMessage returns a boolean if a field has been set.

### SetLatestMessageNil

`func (o *InboxConversation) SetLatestMessageNil(b bool)`

 SetLatestMessageNil sets the value for LatestMessage to be an explicit nil

### UnsetLatestMessage
`func (o *InboxConversation) UnsetLatestMessage()`

UnsetLatestMessage ensures that no value is present for LatestMessage, not even an explicit nil
### GetMessages

`func (o *InboxConversation) GetMessages() []InboxMessage`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *InboxConversation) GetMessagesOk() (*[]InboxMessage, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *InboxConversation) SetMessages(v []InboxMessage)`

SetMessages sets Messages field to given value.

### HasMessages

`func (o *InboxConversation) HasMessages() bool`

HasMessages returns a boolean if a field has been set.

### GetLastMessageAt

`func (o *InboxConversation) GetLastMessageAt() time.Time`

GetLastMessageAt returns the LastMessageAt field if non-nil, zero value otherwise.

### GetLastMessageAtOk

`func (o *InboxConversation) GetLastMessageAtOk() (*time.Time, bool)`

GetLastMessageAtOk returns a tuple with the LastMessageAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastMessageAt

`func (o *InboxConversation) SetLastMessageAt(v time.Time)`

SetLastMessageAt sets LastMessageAt field to given value.

### HasLastMessageAt

`func (o *InboxConversation) HasLastMessageAt() bool`

HasLastMessageAt returns a boolean if a field has been set.

### SetLastMessageAtNil

`func (o *InboxConversation) SetLastMessageAtNil(b bool)`

 SetLastMessageAtNil sets the value for LastMessageAt to be an explicit nil

### UnsetLastMessageAt
`func (o *InboxConversation) UnsetLastMessageAt()`

UnsetLastMessageAt ensures that no value is present for LastMessageAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


