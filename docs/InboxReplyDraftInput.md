# InboxReplyDraftInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Body** | **string** | The reply text. Limit depends on the network. | 
**InReplyTo** | Pointer to **string** | Message &#x60;id&#x60; to reply to; defaults to the latest incoming message. | [optional] 

## Methods

### NewInboxReplyDraftInput

`func NewInboxReplyDraftInput(body string, ) *InboxReplyDraftInput`

NewInboxReplyDraftInput instantiates a new InboxReplyDraftInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInboxReplyDraftInputWithDefaults

`func NewInboxReplyDraftInputWithDefaults() *InboxReplyDraftInput`

NewInboxReplyDraftInputWithDefaults instantiates a new InboxReplyDraftInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBody

`func (o *InboxReplyDraftInput) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *InboxReplyDraftInput) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *InboxReplyDraftInput) SetBody(v string)`

SetBody sets Body field to given value.


### GetInReplyTo

`func (o *InboxReplyDraftInput) GetInReplyTo() string`

GetInReplyTo returns the InReplyTo field if non-nil, zero value otherwise.

### GetInReplyToOk

`func (o *InboxReplyDraftInput) GetInReplyToOk() (*string, bool)`

GetInReplyToOk returns a tuple with the InReplyTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInReplyTo

`func (o *InboxReplyDraftInput) SetInReplyTo(v string)`

SetInReplyTo sets InReplyTo field to given value.

### HasInReplyTo

`func (o *InboxReplyDraftInput) HasInReplyTo() bool`

HasInReplyTo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


