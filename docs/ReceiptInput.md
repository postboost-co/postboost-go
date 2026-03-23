# ReceiptInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**WorkspaceUuid** | **string** |  | 
**TransactionId** | **string** |  | 
**InvoiceNumber** | **string** |  | 
**Amount** | **float32** |  | 
**Tax** | **float32** |  | 
**Currency** | **string** |  | 
**Description** | Pointer to **string** |  | [optional] 
**ReceiptUrl** | Pointer to **string** |  | [optional] 
**PaidAt** | **string** |  | 

## Methods

### NewReceiptInput

`func NewReceiptInput(workspaceUuid string, transactionId string, invoiceNumber string, amount float32, tax float32, currency string, paidAt string, ) *ReceiptInput`

NewReceiptInput instantiates a new ReceiptInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReceiptInputWithDefaults

`func NewReceiptInputWithDefaults() *ReceiptInput`

NewReceiptInputWithDefaults instantiates a new ReceiptInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWorkspaceUuid

`func (o *ReceiptInput) GetWorkspaceUuid() string`

GetWorkspaceUuid returns the WorkspaceUuid field if non-nil, zero value otherwise.

### GetWorkspaceUuidOk

`func (o *ReceiptInput) GetWorkspaceUuidOk() (*string, bool)`

GetWorkspaceUuidOk returns a tuple with the WorkspaceUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspaceUuid

`func (o *ReceiptInput) SetWorkspaceUuid(v string)`

SetWorkspaceUuid sets WorkspaceUuid field to given value.


### GetTransactionId

`func (o *ReceiptInput) GetTransactionId() string`

GetTransactionId returns the TransactionId field if non-nil, zero value otherwise.

### GetTransactionIdOk

`func (o *ReceiptInput) GetTransactionIdOk() (*string, bool)`

GetTransactionIdOk returns a tuple with the TransactionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransactionId

`func (o *ReceiptInput) SetTransactionId(v string)`

SetTransactionId sets TransactionId field to given value.


### GetInvoiceNumber

`func (o *ReceiptInput) GetInvoiceNumber() string`

GetInvoiceNumber returns the InvoiceNumber field if non-nil, zero value otherwise.

### GetInvoiceNumberOk

`func (o *ReceiptInput) GetInvoiceNumberOk() (*string, bool)`

GetInvoiceNumberOk returns a tuple with the InvoiceNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvoiceNumber

`func (o *ReceiptInput) SetInvoiceNumber(v string)`

SetInvoiceNumber sets InvoiceNumber field to given value.


### GetAmount

`func (o *ReceiptInput) GetAmount() float32`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *ReceiptInput) GetAmountOk() (*float32, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *ReceiptInput) SetAmount(v float32)`

SetAmount sets Amount field to given value.


### GetTax

`func (o *ReceiptInput) GetTax() float32`

GetTax returns the Tax field if non-nil, zero value otherwise.

### GetTaxOk

`func (o *ReceiptInput) GetTaxOk() (*float32, bool)`

GetTaxOk returns a tuple with the Tax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTax

`func (o *ReceiptInput) SetTax(v float32)`

SetTax sets Tax field to given value.


### GetCurrency

`func (o *ReceiptInput) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ReceiptInput) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ReceiptInput) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetDescription

`func (o *ReceiptInput) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ReceiptInput) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ReceiptInput) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ReceiptInput) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetReceiptUrl

`func (o *ReceiptInput) GetReceiptUrl() string`

GetReceiptUrl returns the ReceiptUrl field if non-nil, zero value otherwise.

### GetReceiptUrlOk

`func (o *ReceiptInput) GetReceiptUrlOk() (*string, bool)`

GetReceiptUrlOk returns a tuple with the ReceiptUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptUrl

`func (o *ReceiptInput) SetReceiptUrl(v string)`

SetReceiptUrl sets ReceiptUrl field to given value.

### HasReceiptUrl

`func (o *ReceiptInput) HasReceiptUrl() bool`

HasReceiptUrl returns a boolean if a field has been set.

### GetPaidAt

`func (o *ReceiptInput) GetPaidAt() string`

GetPaidAt returns the PaidAt field if non-nil, zero value otherwise.

### GetPaidAtOk

`func (o *ReceiptInput) GetPaidAtOk() (*string, bool)`

GetPaidAtOk returns a tuple with the PaidAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaidAt

`func (o *ReceiptInput) SetPaidAt(v string)`

SetPaidAt sets PaidAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


