# ListReceipts200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Links** | Pointer to [**PaginationMetaLinks**](PaginationMetaLinks.md) |  | [optional] 
**Meta** | Pointer to [**PaginationMetaMeta**](PaginationMetaMeta.md) |  | [optional] 
**Data** | Pointer to [**[]Receipt**](Receipt.md) |  | [optional] 

## Methods

### NewListReceipts200Response

`func NewListReceipts200Response() *ListReceipts200Response`

NewListReceipts200Response instantiates a new ListReceipts200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListReceipts200ResponseWithDefaults

`func NewListReceipts200ResponseWithDefaults() *ListReceipts200Response`

NewListReceipts200ResponseWithDefaults instantiates a new ListReceipts200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLinks

`func (o *ListReceipts200Response) GetLinks() PaginationMetaLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *ListReceipts200Response) GetLinksOk() (*PaginationMetaLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *ListReceipts200Response) SetLinks(v PaginationMetaLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *ListReceipts200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *ListReceipts200Response) GetMeta() PaginationMetaMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ListReceipts200Response) GetMetaOk() (*PaginationMetaMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ListReceipts200Response) SetMeta(v PaginationMetaMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ListReceipts200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### GetData

`func (o *ListReceipts200Response) GetData() []Receipt`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListReceipts200Response) GetDataOk() (*[]Receipt, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListReceipts200Response) SetData(v []Receipt)`

SetData sets Data field to given value.

### HasData

`func (o *ListReceipts200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


