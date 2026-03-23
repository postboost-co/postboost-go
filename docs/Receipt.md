# Receipt

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | Pointer to **string** |  | [optional] 
**TransactionId** | Pointer to **string** |  | [optional] 
**InvoiceNumber** | Pointer to **string** |  | [optional] 
**Amount** | Pointer to **float32** |  | [optional] 
**Tax** | Pointer to **float32** |  | [optional] 
**Currency** | Pointer to **string** |  | [optional] 
**ReceiptUrl** | Pointer to **string** |  | [optional] 
**Description** | Pointer to **string** |  | [optional] 
**PaidAt** | Pointer to **time.Time** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 

## Methods

### NewReceipt

`func NewReceipt() *Receipt`

NewReceipt instantiates a new Receipt object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReceiptWithDefaults

`func NewReceiptWithDefaults() *Receipt`

NewReceiptWithDefaults instantiates a new Receipt object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *Receipt) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *Receipt) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *Receipt) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *Receipt) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetTransactionId

`func (o *Receipt) GetTransactionId() string`

GetTransactionId returns the TransactionId field if non-nil, zero value otherwise.

### GetTransactionIdOk

`func (o *Receipt) GetTransactionIdOk() (*string, bool)`

GetTransactionIdOk returns a tuple with the TransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionId

`func (o *Receipt) SetTransactionId(v string)`

SetTransactionId sets TransactionId field to given value.

### HasTransactionId

`func (o *Receipt) HasTransactionId() bool`

HasTransactionId returns a boolean if a field has been set.

### GetInvoiceNumber

`func (o *Receipt) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *Receipt) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *Receipt) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.

### HasInvoiceNumber

`func (o *Receipt) HasInvoiceNumber() bool`

HasInvoiceNumber returns a boolean if a field has been set.

### GetAmount

`func (o *Receipt) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *Receipt) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *Receipt) SetAmount(v float32)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *Receipt) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetTax

`func (o *Receipt) GetTax() float32`

GetTax returns the Tax field if non-nil, zero value otherwise.

### GetTaxOk

`func (o *Receipt) GetTaxOk() (*float32, bool)`

GetTaxOk returns a tuple with the Tax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTax

`func (o *Receipt) SetTax(v float32)`

SetTax sets Tax field to given value.

### HasTax

`func (o *Receipt) HasTax() bool`

HasTax returns a boolean if a field has been set.

### GetCurrency

`func (o *Receipt) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Receipt) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Receipt) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *Receipt) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetReceiptUrl

`func (o *Receipt) GetReceiptUrl() string`

GetReceiptUrl returns the ReceiptUrl field if non-nil, zero value otherwise.

### GetReceiptUrlOk

`func (o *Receipt) GetReceiptUrlOk() (*string, bool)`

GetReceiptUrlOk returns a tuple with the ReceiptUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptUrl

`func (o *Receipt) SetReceiptUrl(v string)`

SetReceiptUrl sets ReceiptUrl field to given value.

### HasReceiptUrl

`func (o *Receipt) HasReceiptUrl() bool`

HasReceiptUrl returns a boolean if a field has been set.

### GetDescription

`func (o *Receipt) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Receipt) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Receipt) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Receipt) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetPaidAt

`func (o *Receipt) GetPaidAt() time.Time`

GetPaidAt returns the PaidAt field if non-nil, zero value otherwise.

### GetPaidAtOk

`func (o *Receipt) GetPaidAtOk() (*time.Time, bool)`

GetPaidAtOk returns a tuple with the PaidAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidAt

`func (o *Receipt) SetPaidAt(v time.Time)`

SetPaidAt sets PaidAt field to given value.

### HasPaidAt

`func (o *Receipt) HasPaidAt() bool`

HasPaidAt returns a boolean if a field has been set.

### GetCreatedAt

`func (o *Receipt) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Receipt) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Receipt) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Receipt) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


