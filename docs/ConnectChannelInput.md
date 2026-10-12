# ConnectChannelInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BotToken** | Pointer to **string** | Telegram only. Bot token from @BotFather. | [optional] 
**Chat** | Pointer to **string** | Telegram only. Channel &#x60;@username&#x60; or numeric chat id. | [optional] 
**WebhookUrl** | Pointer to **string** | Discord or Slack incoming webhook URL. | [optional] 
**Name** | Pointer to **string** | Slack only. Display name for the channel (Slack webhooks do not report one). | [optional] 

## Methods

### NewConnectChannelInput

`func NewConnectChannelInput() *ConnectChannelInput`

NewConnectChannelInput instantiates a new ConnectChannelInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewConnectChannelInputWithDefaults

`func NewConnectChannelInputWithDefaults() *ConnectChannelInput`

NewConnectChannelInputWithDefaults instantiates a new ConnectChannelInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBotToken

`func (o *ConnectChannelInput) GetBotToken() string`

GetBotToken returns the BotToken field if non-nil, zero value otherwise.

### GetBotTokenOk

`func (o *ConnectChannelInput) GetBotTokenOk() (*string, bool)`

GetBotTokenOk returns a tuple with the BotToken field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBotToken

`func (o *ConnectChannelInput) SetBotToken(v string)`

SetBotToken sets BotToken field to given value.

### HasBotToken

`func (o *ConnectChannelInput) HasBotToken() bool`

HasBotToken returns a boolean if a field has been set.

### GetChat

`func (o *ConnectChannelInput) GetChat() string`

GetChat returns the Chat field if non-nil, zero value otherwise.

### GetChatOk

`func (o *ConnectChannelInput) GetChatOk() (*string, bool)`

GetChatOk returns a tuple with the Chat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChat

`func (o *ConnectChannelInput) SetChat(v string)`

SetChat sets Chat field to given value.

### HasChat

`func (o *ConnectChannelInput) HasChat() bool`

HasChat returns a boolean if a field has been set.

### GetWebhookUrl

`func (o *ConnectChannelInput) GetWebhookUrl() string`

GetWebhookUrl returns the WebhookUrl field if non-nil, zero value otherwise.

### GetWebhookUrlOk

`func (o *ConnectChannelInput) GetWebhookUrlOk() (*string, bool)`

GetWebhookUrlOk returns a tuple with the WebhookUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebhookUrl

`func (o *ConnectChannelInput) SetWebhookUrl(v string)`

SetWebhookUrl sets WebhookUrl field to given value.

### HasWebhookUrl

`func (o *ConnectChannelInput) HasWebhookUrl() bool`

HasWebhookUrl returns a boolean if a field has been set.

### GetName

`func (o *ConnectChannelInput) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ConnectChannelInput) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ConnectChannelInput) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ConnectChannelInput) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


