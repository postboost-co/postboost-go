# CreateWebhookSubscription201ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**Name** | **string** |  | 
**CallbackUrl** | **string** |  | 
**Events** | **[]string** |  | 
**Active** | **bool** |  | 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**Secret** | **string** | Signing secret for &#x60;X-Signature&#x60;. Returned once. | 

## Methods

### NewCreateWebhookSubscription201ResponseData

`func NewCreateWebhookSubscription201ResponseData(uuid string, name string, callbackUrl string, events []string, active bool, secret string, ) *CreateWebhookSubscription201ResponseData`

NewCreateWebhookSubscription201ResponseData instantiates a new CreateWebhookSubscription201ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateWebhookSubscription201ResponseDataWithDefaults

`func NewCreateWebhookSubscription201ResponseDataWithDefaults() *CreateWebhookSubscription201ResponseData`

NewCreateWebhookSubscription201ResponseDataWithDefaults instantiates a new CreateWebhookSubscription201ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *CreateWebhookSubscription201ResponseData) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *CreateWebhookSubscription201ResponseData) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *CreateWebhookSubscription201ResponseData) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *CreateWebhookSubscription201ResponseData) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateWebhookSubscription201ResponseData) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateWebhookSubscription201ResponseData) SetName(v string)`

SetName sets Name field to given value.


### GetCallbackUrl

`func (o *CreateWebhookSubscription201ResponseData) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *CreateWebhookSubscription201ResponseData) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *CreateWebhookSubscription201ResponseData) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.


### GetEvents

`func (o *CreateWebhookSubscription201ResponseData) GetEvents() []string`

GetEvents returns the Events field if non-nil, zero value otherwise.

### GetEventsOk

`func (o *CreateWebhookSubscription201ResponseData) GetEventsOk() (*[]string, bool)`

GetEventsOk returns a tuple with the Events field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvents

`func (o *CreateWebhookSubscription201ResponseData) SetEvents(v []string)`

SetEvents sets Events field to given value.


### GetActive

`func (o *CreateWebhookSubscription201ResponseData) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *CreateWebhookSubscription201ResponseData) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *CreateWebhookSubscription201ResponseData) SetActive(v bool)`

SetActive sets Active field to given value.


### GetCreatedAt

`func (o *CreateWebhookSubscription201ResponseData) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateWebhookSubscription201ResponseData) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateWebhookSubscription201ResponseData) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CreateWebhookSubscription201ResponseData) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetSecret

`func (o *CreateWebhookSubscription201ResponseData) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *CreateWebhookSubscription201ResponseData) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *CreateWebhookSubscription201ResponseData) SetSecret(v string)`

SetSecret sets Secret field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


