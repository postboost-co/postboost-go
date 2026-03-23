# \ReceiptsAPI

All URIs are relative to *https://postboost.co/app/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateReceipt**](ReceiptsAPI.md#CreateReceipt) | **Post** /panel/receipts | Create receipt
[**DeleteReceipt**](ReceiptsAPI.md#DeleteReceipt) | **Delete** /panel/receipts/{receiptUuid} | Delete receipt
[**DeleteReceiptsBulk**](ReceiptsAPI.md#DeleteReceiptsBulk) | **Delete** /panel/receipts | Delete receipts (bulk)
[**GetReceipt**](ReceiptsAPI.md#GetReceipt) | **Get** /panel/receipts/{receiptUuid} | Get receipt
[**ListReceipts**](ReceiptsAPI.md#ListReceipts) | **Get** /panel/receipts | List receipts
[**UpdateReceipt**](ReceiptsAPI.md#UpdateReceipt) | **Put** /panel/receipts/{receiptUuid} | Update receipt



## CreateReceipt

> Receipt CreateReceipt(ctx).ReceiptInput(receiptInput).Execute()

Create receipt

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	receiptInput := *openapiclient.NewReceiptInput("WorkspaceUuid_example", "TransactionId_example", "InvoiceNumber_example", float32(123), float32(123), "USD", time.Now()) // ReceiptInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReceiptsAPI.CreateReceipt(context.Background()).ReceiptInput(receiptInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReceiptsAPI.CreateReceipt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateReceipt`: Receipt
	fmt.Fprintf(os.Stdout, "Response from `ReceiptsAPI.CreateReceipt`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateReceiptRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **receiptInput** | [**ReceiptInput**](ReceiptInput.md) |  | 

### Return type

[**Receipt**](Receipt.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteReceipt

> map[string]interface{} DeleteReceipt(ctx, receiptUuid).Execute()

Delete receipt

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	receiptUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the receipt.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReceiptsAPI.DeleteReceipt(context.Background(), receiptUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReceiptsAPI.DeleteReceipt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteReceipt`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `ReceiptsAPI.DeleteReceipt`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**receiptUuid** | **string** | UUID of the receipt. | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteReceiptRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

**map[string]interface{}**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DeleteReceiptsBulk

> map[string]interface{} DeleteReceiptsBulk(ctx).DeleteReceiptsBulkRequest(deleteReceiptsBulkRequest).Execute()

Delete receipts (bulk)

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	deleteReceiptsBulkRequest := *openapiclient.NewDeleteReceiptsBulkRequest([]string{"Receipts_example"}) // DeleteReceiptsBulkRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReceiptsAPI.DeleteReceiptsBulk(context.Background()).DeleteReceiptsBulkRequest(deleteReceiptsBulkRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReceiptsAPI.DeleteReceiptsBulk``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteReceiptsBulk`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `ReceiptsAPI.DeleteReceiptsBulk`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDeleteReceiptsBulkRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **deleteReceiptsBulkRequest** | [**DeleteReceiptsBulkRequest**](DeleteReceiptsBulkRequest.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetReceipt

> Receipt GetReceipt(ctx, receiptUuid).Execute()

Get receipt

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	receiptUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the receipt.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReceiptsAPI.GetReceipt(context.Background(), receiptUuid).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReceiptsAPI.GetReceipt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetReceipt`: Receipt
	fmt.Fprintf(os.Stdout, "Response from `ReceiptsAPI.GetReceipt`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**receiptUuid** | **string** | UUID of the receipt. | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetReceiptRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**Receipt**](Receipt.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListReceipts

> ListReceipts200Response ListReceipts(ctx).WorkspaceUuid(workspaceUuid).InvoiceNumber(invoiceNumber).Execute()

List receipts

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	workspaceUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string |  (optional)
	invoiceNumber := "invoiceNumber_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReceiptsAPI.ListReceipts(context.Background()).WorkspaceUuid(workspaceUuid).InvoiceNumber(invoiceNumber).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReceiptsAPI.ListReceipts``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListReceipts`: ListReceipts200Response
	fmt.Fprintf(os.Stdout, "Response from `ReceiptsAPI.ListReceipts`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListReceiptsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **workspaceUuid** | **string** |  | 
 **invoiceNumber** | **string** |  | 

### Return type

[**ListReceipts200Response**](ListReceipts200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UpdateReceipt

> map[string]interface{} UpdateReceipt(ctx, receiptUuid).ReceiptUpdateInput(receiptUpdateInput).Execute()

Update receipt

### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
    "time"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	receiptUuid := "38400000-8cf0-11bd-b23e-10b96e4ef00d" // string | UUID of the receipt.
	receiptUpdateInput := *openapiclient.NewReceiptUpdateInput("TransactionId_example", "InvoiceNumber_example", float32(123), "Currency_example", time.Now()) // ReceiptUpdateInput | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ReceiptsAPI.UpdateReceipt(context.Background(), receiptUuid).ReceiptUpdateInput(receiptUpdateInput).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ReceiptsAPI.UpdateReceipt``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UpdateReceipt`: map[string]interface{}
	fmt.Fprintf(os.Stdout, "Response from `ReceiptsAPI.UpdateReceipt`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**receiptUuid** | **string** | UUID of the receipt. | 

### Other Parameters

Other parameters are passed through a pointer to a apiUpdateReceiptRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **receiptUpdateInput** | [**ReceiptUpdateInput**](ReceiptUpdateInput.md) |  | 

### Return type

**map[string]interface{}**

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

