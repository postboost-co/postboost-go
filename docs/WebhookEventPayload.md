# WebhookEventPayload

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Event** | [**WebhookEventName**](WebhookEventName.md) |  | 
**Data** | **map[string]interface{}** |  | 

## Methods

### NewWebhookEventPayload

`func NewWebhookEventPayload(event WebhookEventName, data map[string]interface{}, ) *WebhookEventPayload`

NewWebhookEventPayload instantiates a new WebhookEventPayload object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebhookEventPayloadWithDefaults

`func NewWebhookEventPayloadWithDefaults() *WebhookEventPayload`

NewWebhookEventPayloadWithDefaults instantiates a new WebhookEventPayload object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEvent

`func (o *WebhookEventPayload) GetEvent() WebhookEventName`

GetEvent returns the Event field if non-nil, zero value otherwise.

### GetEventOk

`func (o *WebhookEventPayload) GetEventOk() (*WebhookEventName, bool)`

GetEventOk returns a tuple with the Event field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvent

`func (o *WebhookEventPayload) SetEvent(v WebhookEventName)`

SetEvent sets Event field to given value.


### GetData

`func (o *WebhookEventPayload) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *WebhookEventPayload) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *WebhookEventPayload) SetData(v map[string]interface{})`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


