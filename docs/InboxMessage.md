# InboxMessage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Message UUID. | 
**Direction** | **string** |  | 
**Body** | **string** |  | 
**Author** | Pointer to [**InboxMessageAuthor**](InboxMessageAuthor.md) |  | [optional] 
**Sentiment** | Pointer to **NullableString** |  | [optional] 
**AiLabel** | Pointer to **NullableString** |  | [optional] 
**IsSpam** | Pointer to **bool** |  | [optional] 
**CreatedAt** | Pointer to **NullableTime** |  | [optional] 

## Methods

### NewInboxMessage

`func NewInboxMessage(id string, direction string, body string, ) *InboxMessage`

NewInboxMessage instantiates a new InboxMessage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInboxMessageWithDefaults

`func NewInboxMessageWithDefaults() *InboxMessage`

NewInboxMessageWithDefaults instantiates a new InboxMessage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InboxMessage) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InboxMessage) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InboxMessage) SetId(v string)`

SetId sets Id field to given value.


### GetDirection

`func (o *InboxMessage) GetDirection() string`

GetDirection returns the Direction field if non-nil, zero value otherwise.

### GetDirectionOk

`func (o *InboxMessage) GetDirectionOk() (*string, bool)`

GetDirectionOk returns a tuple with the Direction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDirection

`func (o *InboxMessage) SetDirection(v string)`

SetDirection sets Direction field to given value.


### GetBody

`func (o *InboxMessage) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *InboxMessage) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *InboxMessage) SetBody(v string)`

SetBody sets Body field to given value.


### GetAuthor

`func (o *InboxMessage) GetAuthor() InboxMessageAuthor`

GetAuthor returns the Author field if non-nil, zero value otherwise.

### GetAuthorOk

`func (o *InboxMessage) GetAuthorOk() (*InboxMessageAuthor, bool)`

GetAuthorOk returns a tuple with the Author field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthor

`func (o *InboxMessage) SetAuthor(v InboxMessageAuthor)`

SetAuthor sets Author field to given value.

### HasAuthor

`func (o *InboxMessage) HasAuthor() bool`

HasAuthor returns a boolean if a field has been set.

### GetSentiment

`func (o *InboxMessage) GetSentiment() string`

GetSentiment returns the Sentiment field if non-nil, zero value otherwise.

### GetSentimentOk

`func (o *InboxMessage) GetSentimentOk() (*string, bool)`

GetSentimentOk returns a tuple with the Sentiment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentiment

`func (o *InboxMessage) SetSentiment(v string)`

SetSentiment sets Sentiment field to given value.

### HasSentiment

`func (o *InboxMessage) HasSentiment() bool`

HasSentiment returns a boolean if a field has been set.

### SetSentimentNil

`func (o *InboxMessage) SetSentimentNil(b bool)`

 SetSentimentNil sets the value for Sentiment to be an explicit nil

### UnsetSentiment
`func (o *InboxMessage) UnsetSentiment()`

UnsetSentiment ensures that no value is present for Sentiment, not even an explicit nil
### GetAiLabel

`func (o *InboxMessage) GetAiLabel() string`

GetAiLabel returns the AiLabel field if non-nil, zero value otherwise.

### GetAiLabelOk

`func (o *InboxMessage) GetAiLabelOk() (*string, bool)`

GetAiLabelOk returns a tuple with the AiLabel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAiLabel

`func (o *InboxMessage) SetAiLabel(v string)`

SetAiLabel sets AiLabel field to given value.

### HasAiLabel

`func (o *InboxMessage) HasAiLabel() bool`

HasAiLabel returns a boolean if a field has been set.

### SetAiLabelNil

`func (o *InboxMessage) SetAiLabelNil(b bool)`

 SetAiLabelNil sets the value for AiLabel to be an explicit nil

### UnsetAiLabel
`func (o *InboxMessage) UnsetAiLabel()`

UnsetAiLabel ensures that no value is present for AiLabel, not even an explicit nil
### GetIsSpam

`func (o *InboxMessage) GetIsSpam() bool`

GetIsSpam returns the IsSpam field if non-nil, zero value otherwise.

### GetIsSpamOk

`func (o *InboxMessage) GetIsSpamOk() (*bool, bool)`

GetIsSpamOk returns a tuple with the IsSpam field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsSpam

`func (o *InboxMessage) SetIsSpam(v bool)`

SetIsSpam sets IsSpam field to given value.

### HasIsSpam

`func (o *InboxMessage) HasIsSpam() bool`

HasIsSpam returns a boolean if a field has been set.

### GetCreatedAt

`func (o *InboxMessage) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *InboxMessage) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *InboxMessage) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *InboxMessage) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### SetCreatedAtNil

`func (o *InboxMessage) SetCreatedAtNil(b bool)`

 SetCreatedAtNil sets the value for CreatedAt to be an explicit nil

### UnsetCreatedAt
`func (o *InboxMessage) UnsetCreatedAt()`

UnsetCreatedAt ensures that no value is present for CreatedAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


