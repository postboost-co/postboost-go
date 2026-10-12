# InboxReplyDraft

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Draft UUID. | 
**Status** | **string** |  | 
**Body** | **string** |  | 
**Source** | **string** |  | 
**ConversationId** | Pointer to **NullableString** |  | [optional] 
**Provider** | Pointer to **NullableString** |  | [optional] 
**InReplyTo** | Pointer to **map[string]interface{}** | The incoming message this replies to (same shape as &#x60;InboxMessage&#x60;). | [optional] 
**CreatedBy** | Pointer to **NullableString** | Name of the user whose API key wrote the draft. | [optional] 
**ReviewedBy** | Pointer to **NullableString** |  | [optional] 
**ReviewedAt** | Pointer to **NullableTime** |  | [optional] 
**SentMessageId** | Pointer to **NullableString** | The sent reply&#39;s message UUID, once sent. | [optional] 
**Error** | Pointer to **NullableString** | Why sending failed. | [optional] 
**CreatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewInboxReplyDraft

`func NewInboxReplyDraft(id string, status string, body string, source string, ) *InboxReplyDraft`

NewInboxReplyDraft instantiates a new InboxReplyDraft object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInboxReplyDraftWithDefaults

`func NewInboxReplyDraftWithDefaults() *InboxReplyDraft`

NewInboxReplyDraftWithDefaults instantiates a new InboxReplyDraft object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InboxReplyDraft) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InboxReplyDraft) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InboxReplyDraft) SetId(v string)`

SetId sets Id field to given value.


### GetStatus

`func (o *InboxReplyDraft) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *InboxReplyDraft) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *InboxReplyDraft) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetBody

`func (o *InboxReplyDraft) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *InboxReplyDraft) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *InboxReplyDraft) SetBody(v string)`

SetBody sets Body field to given value.


### GetSource

`func (o *InboxReplyDraft) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *InboxReplyDraft) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *InboxReplyDraft) SetSource(v string)`

SetSource sets Source field to given value.


### GetConversationId

`func (o *InboxReplyDraft) GetConversationId() string`

GetConversationId returns the ConversationId field if non-nil, zero value otherwise.

### GetConversationIdOk

`func (o *InboxReplyDraft) GetConversationIdOk() (*string, bool)`

GetConversationIdOk returns a tuple with the ConversationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConversationId

`func (o *InboxReplyDraft) SetConversationId(v string)`

SetConversationId sets ConversationId field to given value.

### HasConversationId

`func (o *InboxReplyDraft) HasConversationId() bool`

HasConversationId returns a boolean if a field has been set.

### SetConversationIdNil

`func (o *InboxReplyDraft) SetConversationIdNil(b bool)`

 SetConversationIdNil sets the value for ConversationId to be an explicit nil

### UnsetConversationId
`func (o *InboxReplyDraft) UnsetConversationId()`

UnsetConversationId ensures that no value is present for ConversationId, not even an explicit nil
### GetProvider

`func (o *InboxReplyDraft) GetProvider() string`

GetProvider returns the Provider field if non-nil, zero value otherwise.

### GetProviderOk

`func (o *InboxReplyDraft) GetProviderOk() (*string, bool)`

GetProviderOk returns a tuple with the Provider field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvider

`func (o *InboxReplyDraft) SetProvider(v string)`

SetProvider sets Provider field to given value.

### HasProvider

`func (o *InboxReplyDraft) HasProvider() bool`

HasProvider returns a boolean if a field has been set.

### SetProviderNil

`func (o *InboxReplyDraft) SetProviderNil(b bool)`

 SetProviderNil sets the value for Provider to be an explicit nil

### UnsetProvider
`func (o *InboxReplyDraft) UnsetProvider()`

UnsetProvider ensures that no value is present for Provider, not even an explicit nil
### GetInReplyTo

`func (o *InboxReplyDraft) GetInReplyTo() map[string]interface{}`

GetInReplyTo returns the InReplyTo field if non-nil, zero value otherwise.

### GetInReplyToOk

`func (o *InboxReplyDraft) GetInReplyToOk() (*map[string]interface{}, bool)`

GetInReplyToOk returns a tuple with the InReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInReplyTo

`func (o *InboxReplyDraft) SetInReplyTo(v map[string]interface{})`

SetInReplyTo sets InReplyTo field to given value.

### HasInReplyTo

`func (o *InboxReplyDraft) HasInReplyTo() bool`

HasInReplyTo returns a boolean if a field has been set.

### SetInReplyToNil

`func (o *InboxReplyDraft) SetInReplyToNil(b bool)`

 SetInReplyToNil sets the value for InReplyTo to be an explicit nil

### UnsetInReplyTo
`func (o *InboxReplyDraft) UnsetInReplyTo()`

UnsetInReplyTo ensures that no value is present for InReplyTo, not even an explicit nil
### GetCreatedBy

`func (o *InboxReplyDraft) GetCreatedBy() string`

GetCreatedBy returns the CreatedBy field if non-nil, zero value otherwise.

### GetCreatedByOk

`func (o *InboxReplyDraft) GetCreatedByOk() (*string, bool)`

GetCreatedByOk returns a tuple with the CreatedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedBy

`func (o *InboxReplyDraft) SetCreatedBy(v string)`

SetCreatedBy sets CreatedBy field to given value.

### HasCreatedBy

`func (o *InboxReplyDraft) HasCreatedBy() bool`

HasCreatedBy returns a boolean if a field has been set.

### SetCreatedByNil

`func (o *InboxReplyDraft) SetCreatedByNil(b bool)`

 SetCreatedByNil sets the value for CreatedBy to be an explicit nil

### UnsetCreatedBy
`func (o *InboxReplyDraft) UnsetCreatedBy()`

UnsetCreatedBy ensures that no value is present for CreatedBy, not even an explicit nil
### GetReviewedBy

`func (o *InboxReplyDraft) GetReviewedBy() string`

GetReviewedBy returns the ReviewedBy field if non-nil, zero value otherwise.

### GetReviewedByOk

`func (o *InboxReplyDraft) GetReviewedByOk() (*string, bool)`

GetReviewedByOk returns a tuple with the ReviewedBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewedBy

`func (o *InboxReplyDraft) SetReviewedBy(v string)`

SetReviewedBy sets ReviewedBy field to given value.

### HasReviewedBy

`func (o *InboxReplyDraft) HasReviewedBy() bool`

HasReviewedBy returns a boolean if a field has been set.

### SetReviewedByNil

`func (o *InboxReplyDraft) SetReviewedByNil(b bool)`

 SetReviewedByNil sets the value for ReviewedBy to be an explicit nil

### UnsetReviewedBy
`func (o *InboxReplyDraft) UnsetReviewedBy()`

UnsetReviewedBy ensures that no value is present for ReviewedBy, not even an explicit nil
### GetReviewedAt

`func (o *InboxReplyDraft) GetReviewedAt() time.Time`

GetReviewedAt returns the ReviewedAt field if non-nil, zero value otherwise.

### GetReviewedAtOk

`func (o *InboxReplyDraft) GetReviewedAtOk() (*time.Time, bool)`

GetReviewedAtOk returns a tuple with the ReviewedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewedAt

`func (o *InboxReplyDraft) SetReviewedAt(v time.Time)`

SetReviewedAt sets ReviewedAt field to given value.

### HasReviewedAt

`func (o *InboxReplyDraft) HasReviewedAt() bool`

HasReviewedAt returns a boolean if a field has been set.

### SetReviewedAtNil

`func (o *InboxReplyDraft) SetReviewedAtNil(b bool)`

 SetReviewedAtNil sets the value for ReviewedAt to be an explicit nil

### UnsetReviewedAt
`func (o *InboxReplyDraft) UnsetReviewedAt()`

UnsetReviewedAt ensures that no value is present for ReviewedAt, not even an explicit nil
### GetSentMessageId

`func (o *InboxReplyDraft) GetSentMessageId() string`

GetSentMessageId returns the SentMessageId field if non-nil, zero value otherwise.

### GetSentMessageIdOk

`func (o *InboxReplyDraft) GetSentMessageIdOk() (*string, bool)`

GetSentMessageIdOk returns a tuple with the SentMessageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentMessageId

`func (o *InboxReplyDraft) SetSentMessageId(v string)`

SetSentMessageId sets SentMessageId field to given value.

### HasSentMessageId

`func (o *InboxReplyDraft) HasSentMessageId() bool`

HasSentMessageId returns a boolean if a field has been set.

### SetSentMessageIdNil

`func (o *InboxReplyDraft) SetSentMessageIdNil(b bool)`

 SetSentMessageIdNil sets the value for SentMessageId to be an explicit nil

### UnsetSentMessageId
`func (o *InboxReplyDraft) UnsetSentMessageId()`

UnsetSentMessageId ensures that no value is present for SentMessageId, not even an explicit nil
### GetError

`func (o *InboxReplyDraft) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *InboxReplyDraft) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *InboxReplyDraft) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *InboxReplyDraft) HasError() bool`

HasError returns a boolean if a field has been set.

### SetErrorNil

`func (o *InboxReplyDraft) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *InboxReplyDraft) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetCreatedAt

`func (o *InboxReplyDraft) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *InboxReplyDraft) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *InboxReplyDraft) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *InboxReplyDraft) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *InboxReplyDraft) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *InboxReplyDraft) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


