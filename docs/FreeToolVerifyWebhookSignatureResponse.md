# FreeToolVerifyWebhookSignatureResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Valid** | Pointer to **bool** |  | [optional] 
**Expected** | Pointer to **string** | The signature the body and secret give, with the prefix. | [optional] 
**Hints** | Pointer to **[]string** | When invalid: the usual mistakes that would make it valid, each checked. | [optional] 

## Methods

### NewFreeToolVerifyWebhookSignatureResponse

`func NewFreeToolVerifyWebhookSignatureResponse() *FreeToolVerifyWebhookSignatureResponse`

NewFreeToolVerifyWebhookSignatureResponse instantiates a new FreeToolVerifyWebhookSignatureResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolVerifyWebhookSignatureResponseWithDefaults

`func NewFreeToolVerifyWebhookSignatureResponseWithDefaults() *FreeToolVerifyWebhookSignatureResponse`

NewFreeToolVerifyWebhookSignatureResponseWithDefaults instantiates a new FreeToolVerifyWebhookSignatureResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValid

`func (o *FreeToolVerifyWebhookSignatureResponse) GetValid() bool`

GetValid returns the Valid field if non-nil, zero value otherwise.

### GetValidOk

`func (o *FreeToolVerifyWebhookSignatureResponse) GetValidOk() (*bool, bool)`

GetValidOk returns a tuple with the Valid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValid

`func (o *FreeToolVerifyWebhookSignatureResponse) SetValid(v bool)`

SetValid sets Valid field to given value.

### HasValid

`func (o *FreeToolVerifyWebhookSignatureResponse) HasValid() bool`

HasValid returns a boolean if a field has been set.

### GetExpected

`func (o *FreeToolVerifyWebhookSignatureResponse) GetExpected() string`

GetExpected returns the Expected field if non-nil, zero value otherwise.

### GetExpectedOk

`func (o *FreeToolVerifyWebhookSignatureResponse) GetExpectedOk() (*string, bool)`

GetExpectedOk returns a tuple with the Expected field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpected

`func (o *FreeToolVerifyWebhookSignatureResponse) SetExpected(v string)`

SetExpected sets Expected field to given value.

### HasExpected

`func (o *FreeToolVerifyWebhookSignatureResponse) HasExpected() bool`

HasExpected returns a boolean if a field has been set.

### GetHints

`func (o *FreeToolVerifyWebhookSignatureResponse) GetHints() []string`

GetHints returns the Hints field if non-nil, zero value otherwise.

### GetHintsOk

`func (o *FreeToolVerifyWebhookSignatureResponse) GetHintsOk() (*[]string, bool)`

GetHintsOk returns a tuple with the Hints field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHints

`func (o *FreeToolVerifyWebhookSignatureResponse) SetHints(v []string)`

SetHints sets Hints field to given value.

### HasHints

`func (o *FreeToolVerifyWebhookSignatureResponse) HasHints() bool`

HasHints returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


