# FreeToolVerifyWebhookSignatureRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Body** | **string** | The raw request body exactly as received (up to 64 KB). Use a test payload, not production data. | 
**Secret** | **string** | The webhook secret. Use a test secret: never send a production secret to any third-party service. | 
**Signature** | **string** | The received signature header value, e.g. X-Signature. | 
**Algorithm** | Pointer to **string** |  | [optional] [default to "sha256"]
**Encoding** | Pointer to **string** |  | [optional] [default to "hex"]
**Prefix** | Pointer to **string** | A prefix the sender puts before the signature, e.g. \&quot;sha256&#x3D;\&quot; (GitHub). | [optional] [default to ""]

## Methods

### NewFreeToolVerifyWebhookSignatureRequest

`func NewFreeToolVerifyWebhookSignatureRequest(body string, secret string, signature string, ) *FreeToolVerifyWebhookSignatureRequest`

NewFreeToolVerifyWebhookSignatureRequest instantiates a new FreeToolVerifyWebhookSignatureRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolVerifyWebhookSignatureRequestWithDefaults

`func NewFreeToolVerifyWebhookSignatureRequestWithDefaults() *FreeToolVerifyWebhookSignatureRequest`

NewFreeToolVerifyWebhookSignatureRequestWithDefaults instantiates a new FreeToolVerifyWebhookSignatureRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBody

`func (o *FreeToolVerifyWebhookSignatureRequest) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *FreeToolVerifyWebhookSignatureRequest) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *FreeToolVerifyWebhookSignatureRequest) SetBody(v string)`

SetBody sets Body field to given value.


### GetSecret

`func (o *FreeToolVerifyWebhookSignatureRequest) GetSecret() string`

GetSecret returns the Secret field if non-nil, zero value otherwise.

### GetSecretOk

`func (o *FreeToolVerifyWebhookSignatureRequest) GetSecretOk() (*string, bool)`

GetSecretOk returns a tuple with the Secret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSecret

`func (o *FreeToolVerifyWebhookSignatureRequest) SetSecret(v string)`

SetSecret sets Secret field to given value.


### GetSignature

`func (o *FreeToolVerifyWebhookSignatureRequest) GetSignature() string`

GetSignature returns the Signature field if non-nil, zero value otherwise.

### GetSignatureOk

`func (o *FreeToolVerifyWebhookSignatureRequest) GetSignatureOk() (*string, bool)`

GetSignatureOk returns a tuple with the Signature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignature

`func (o *FreeToolVerifyWebhookSignatureRequest) SetSignature(v string)`

SetSignature sets Signature field to given value.


### GetAlgorithm

`func (o *FreeToolVerifyWebhookSignatureRequest) GetAlgorithm() string`

GetAlgorithm returns the Algorithm field if non-nil, zero value otherwise.

### GetAlgorithmOk

`func (o *FreeToolVerifyWebhookSignatureRequest) GetAlgorithmOk() (*string, bool)`

GetAlgorithmOk returns a tuple with the Algorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlgorithm

`func (o *FreeToolVerifyWebhookSignatureRequest) SetAlgorithm(v string)`

SetAlgorithm sets Algorithm field to given value.

### HasAlgorithm

`func (o *FreeToolVerifyWebhookSignatureRequest) HasAlgorithm() bool`

HasAlgorithm returns a boolean if a field has been set.

### GetEncoding

`func (o *FreeToolVerifyWebhookSignatureRequest) GetEncoding() string`

GetEncoding returns the Encoding field if non-nil, zero value otherwise.

### GetEncodingOk

`func (o *FreeToolVerifyWebhookSignatureRequest) GetEncodingOk() (*string, bool)`

GetEncodingOk returns a tuple with the Encoding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEncoding

`func (o *FreeToolVerifyWebhookSignatureRequest) SetEncoding(v string)`

SetEncoding sets Encoding field to given value.

### HasEncoding

`func (o *FreeToolVerifyWebhookSignatureRequest) HasEncoding() bool`

HasEncoding returns a boolean if a field has been set.

### GetPrefix

`func (o *FreeToolVerifyWebhookSignatureRequest) GetPrefix() string`

GetPrefix returns the Prefix field if non-nil, zero value otherwise.

### GetPrefixOk

`func (o *FreeToolVerifyWebhookSignatureRequest) GetPrefixOk() (*string, bool)`

GetPrefixOk returns a tuple with the Prefix field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrefix

`func (o *FreeToolVerifyWebhookSignatureRequest) SetPrefix(v string)`

SetPrefix sets Prefix field to given value.

### HasPrefix

`func (o *FreeToolVerifyWebhookSignatureRequest) HasPrefix() bool`

HasPrefix returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


