# WebhookEnvelope

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Event** | **string** |  | 
**Id** | **string** | Delivery ID, one per event. Retries and manual resends repeat it. | 
**OccurredAt** | **time.Time** | When the event happened (ISO 8601, UTC). | 
**WorkspaceUuid** | **NullableString** | The workspace the event belongs to (null only on instance-wide system webhooks). Also sent as the &#x60;X-PostBoost-Workspace&#x60; header. | 
**Data** | **map[string]interface{}** | The post (&#x60;post.*&#x60;, as &#x60;getPost&#x60; returns it, plus &#x60;account&#x60; on per-account events), the account (&#x60;account.*&#x60;) or the reply draft (&#x60;inbox.*&#x60;). | 

## Methods

### NewWebhookEnvelope

`func NewWebhookEnvelope(event string, id string, occurredAt time.Time, workspaceUuid NullableString, data map[string]interface{}, ) *WebhookEnvelope`

NewWebhookEnvelope instantiates a new WebhookEnvelope object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWebhookEnvelopeWithDefaults

`func NewWebhookEnvelopeWithDefaults() *WebhookEnvelope`

NewWebhookEnvelopeWithDefaults instantiates a new WebhookEnvelope object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEvent

`func (o *WebhookEnvelope) GetEvent() string`

GetEvent returns the Event field if non-nil, zero value otherwise.

### GetEventOk

`func (o *WebhookEnvelope) GetEventOk() (*string, bool)`

GetEventOk returns a tuple with the Event field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvent

`func (o *WebhookEnvelope) SetEvent(v string)`

SetEvent sets Event field to given value.


### GetId

`func (o *WebhookEnvelope) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WebhookEnvelope) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WebhookEnvelope) SetId(v string)`

SetId sets Id field to given value.


### GetOccurredAt

`func (o *WebhookEnvelope) GetOccurredAt() time.Time`

GetOccurredAt returns the OccurredAt field if non-nil, zero value otherwise.

### GetOccurredAtOk

`func (o *WebhookEnvelope) GetOccurredAtOk() (*time.Time, bool)`

GetOccurredAtOk returns a tuple with the OccurredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOccurredAt

`func (o *WebhookEnvelope) SetOccurredAt(v time.Time)`

SetOccurredAt sets OccurredAt field to given value.


### GetWorkspaceUuid

`func (o *WebhookEnvelope) GetWorkspaceUuid() string`

GetWorkspaceUuid returns the WorkspaceUuid field if non-nil, zero value otherwise.

### GetWorkspaceUuidOk

`func (o *WebhookEnvelope) GetWorkspaceUuidOk() (*string, bool)`

GetWorkspaceUuidOk returns a tuple with the WorkspaceUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspaceUuid

`func (o *WebhookEnvelope) SetWorkspaceUuid(v string)`

SetWorkspaceUuid sets WorkspaceUuid field to given value.


### SetWorkspaceUuidNil

`func (o *WebhookEnvelope) SetWorkspaceUuidNil(b bool)`

 SetWorkspaceUuidNil sets the value for WorkspaceUuid to be an explicit nil

### UnsetWorkspaceUuid
`func (o *WebhookEnvelope) UnsetWorkspaceUuid()`

UnsetWorkspaceUuid ensures that no value is present for WorkspaceUuid, not even an explicit nil
### GetData

`func (o *WebhookEnvelope) GetData() map[string]interface{}`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *WebhookEnvelope) GetDataOk() (*map[string]interface{}, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *WebhookEnvelope) SetData(v map[string]interface{})`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


