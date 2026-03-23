# ReceiptUpdateInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TransactionId** | **string** |  | 
**InvoiceNumber** | **string** |  | 
**Amount** | **float32** |  | 
**Tax** | Pointer to **float32** |  | [optional] 
**Currency** | **string** |  | 
**Description** | Pointer to **string** |  | [optional] 
**ReceiptUrl** | Pointer to **string** |  | [optional] 
**PaidAt** | **string** |  | 

## Methods

### NewReceiptUpdateInput

`func NewReceiptUpdateInput(transactionId string, invoiceNumber string, amount float32, currency string, paidAt string, ) *ReceiptUpdateInput`

NewReceiptUpdateInput instantiates a new ReceiptUpdateInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReceiptUpdateInputWithDefaults

`func NewReceiptUpdateInputWithDefaults() *ReceiptUpdateInput`

NewReceiptUpdateInputWithDefaults instantiates a new ReceiptUpdateInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTransactionId

`func (o *ReceiptUpdateInput) GetTransactionId() string`

GetTransactionId returns the TransactionId field if non-nil, zero value otherwise.

### GetTransactionIdOk

`func (o *ReceiptUpdateInput) GetTransactionIdOk() (*string, bool)`

GetTransactionIdOk returns a tuple with the TransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionId

`func (o *ReceiptUpdateInput) SetTransactionId(v string)`

SetTransactionId sets TransactionId field to given value.


### GetInvoiceNumber

`func (o *ReceiptUpdateInput) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *ReceiptUpdateInput) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *ReceiptUpdateInput) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.


### GetAmount

`func (o *ReceiptUpdateInput) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *ReceiptUpdateInput) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *ReceiptUpdateInput) SetAmount(v float32)`

SetAmount sets Amount field to given value.


### GetTax

`func (o *ReceiptUpdateInput) GetTax() float32`

GetTax returns the Tax field if non-nil, zero value otherwise.

### GetTaxOk

`func (o *ReceiptUpdateInput) GetTaxOk() (*float32, bool)`

GetTaxOk returns a tuple with the Tax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTax

`func (o *ReceiptUpdateInput) SetTax(v float32)`

SetTax sets Tax field to given value.

### HasTax

`func (o *ReceiptUpdateInput) HasTax() bool`

HasTax returns a boolean if a field has been set.

### GetCurrency

`func (o *ReceiptUpdateInput) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ReceiptUpdateInput) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ReceiptUpdateInput) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDescription

`func (o *ReceiptUpdateInput) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ReceiptUpdateInput) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ReceiptUpdateInput) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ReceiptUpdateInput) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetReceiptUrl

`func (o *ReceiptUpdateInput) GetReceiptUrl() string`

GetReceiptUrl returns the ReceiptUrl field if non-nil, zero value otherwise.

### GetReceiptUrlOk

`func (o *ReceiptUpdateInput) GetReceiptUrlOk() (*string, bool)`

GetReceiptUrlOk returns a tuple with the ReceiptUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptUrl

`func (o *ReceiptUpdateInput) SetReceiptUrl(v string)`

SetReceiptUrl sets ReceiptUrl field to given value.

### HasReceiptUrl

`func (o *ReceiptUpdateInput) HasReceiptUrl() bool`

HasReceiptUrl returns a boolean if a field has been set.

### GetPaidAt

`func (o *ReceiptUpdateInput) GetPaidAt() string`

GetPaidAt returns the PaidAt field if non-nil, zero value otherwise.

### GetPaidAtOk

`func (o *ReceiptUpdateInput) GetPaidAtOk() (*string, bool)`

GetPaidAtOk returns a tuple with the PaidAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidAt

`func (o *ReceiptUpdateInput) SetPaidAt(v string)`

SetPaidAt sets PaidAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


