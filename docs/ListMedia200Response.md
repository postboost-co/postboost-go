# ListMedia200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Links** | Pointer to [**PaginationMetaLinks**](PaginationMetaLinks.md) |  | [optional] 
**Meta** | Pointer to [**PaginationMetaMeta**](PaginationMetaMeta.md) |  | [optional] 
**Data** | Pointer to [**[]Media**](Media.md) |  | [optional] 

## Methods

### NewListMedia200Response

`func NewListMedia200Response() *ListMedia200Response`

NewListMedia200Response instantiates a new ListMedia200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListMedia200ResponseWithDefaults

`func NewListMedia200ResponseWithDefaults() *ListMedia200Response`

NewListMedia200ResponseWithDefaults instantiates a new ListMedia200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLinks

`func (o *ListMedia200Response) GetLinks() PaginationMetaLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *ListMedia200Response) GetLinksOk() (*PaginationMetaLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *ListMedia200Response) SetLinks(v PaginationMetaLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *ListMedia200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *ListMedia200Response) GetMeta() PaginationMetaMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ListMedia200Response) GetMetaOk() (*PaginationMetaMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ListMedia200Response) SetMeta(v PaginationMetaMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ListMedia200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### GetData

`func (o *ListMedia200Response) GetData() []Media`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListMedia200Response) GetDataOk() (*[]Media, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListMedia200Response) SetData(v []Media)`

SetData sets Data field to given value.

### HasData

`func (o *ListMedia200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


