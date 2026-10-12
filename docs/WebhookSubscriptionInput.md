# WebhookSubscriptionInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CallbackUrl** | **string** | Public &#x60;https://&#x60; URL that receives the deliveries. | 
**Events** | [**[]WebhookEventName**](WebhookEventName.md) |  | 
**Name** | Pointer to **NullableString** | Label shown in Settings → Webhooks. Defaults to \&quot;&lt;Source&gt; trigger\&quot;. | [optional] 
**Source** | Pointer to **NullableString** | The tool creating the subscription. | [optional] 

## Methods

### NewWebhookSubscriptionInput

`func NewWebhookSubscriptionInput(callbackUrl string, events []WebhookEventName, ) *WebhookSubscriptionInput`

NewWebhookSubscriptionInput instantiates a new WebhookSubscriptionInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebhookSubscriptionInputWithDefaults

`func NewWebhookSubscriptionInputWithDefaults() *WebhookSubscriptionInput`

NewWebhookSubscriptionInputWithDefaults instantiates a new WebhookSubscriptionInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCallbackUrl

`func (o *WebhookSubscriptionInput) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *WebhookSubscriptionInput) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *WebhookSubscriptionInput) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.


### GetEvents

`func (o *WebhookSubscriptionInput) GetEvents() []WebhookEventName`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *WebhookSubscriptionInput) GetEventsOk() (*[]WebhookEventName, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *WebhookSubscriptionInput) SetEvents(v []WebhookEventName)`

SetEvents sets Events field to given value.


### GetName

`func (o *WebhookSubscriptionInput) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *WebhookSubscriptionInput) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *WebhookSubscriptionInput) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *WebhookSubscriptionInput) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *WebhookSubscriptionInput) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *WebhookSubscriptionInput) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetSource

`func (o *WebhookSubscriptionInput) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *WebhookSubscriptionInput) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *WebhookSubscriptionInput) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *WebhookSubscriptionInput) HasSource() bool`

HasSource returns a boolean if a field has been set.

### SetSourceNil

`func (o *WebhookSubscriptionInput) SetSourceNil(b bool)`

 SetSourceNil sets the value for Source to be an explicit nil

### UnsetSource
`func (o *WebhookSubscriptionInput) UnsetSource()`

UnsetSource ensures that no value is present for Source, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


