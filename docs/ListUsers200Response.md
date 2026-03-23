# ListUsers200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Links** | Pointer to [**PaginationMetaLinks**](PaginationMetaLinks.md) |  | [optional] 
**Meta** | Pointer to [**PaginationMetaMeta**](PaginationMetaMeta.md) |  | [optional] 
**Data** | Pointer to [**[]User**](User.md) |  | [optional] 

## Methods

### NewListUsers200Response

`func NewListUsers200Response() *ListUsers200Response`

NewListUsers200Response instantiates a new ListUsers200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListUsers200ResponseWithDefaults

`func NewListUsers200ResponseWithDefaults() *ListUsers200Response`

NewListUsers200ResponseWithDefaults instantiates a new ListUsers200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLinks

`func (o *ListUsers200Response) GetLinks() PaginationMetaLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *ListUsers200Response) GetLinksOk() (*PaginationMetaLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *ListUsers200Response) SetLinks(v PaginationMetaLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *ListUsers200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *ListUsers200Response) GetMeta() PaginationMetaMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ListUsers200Response) GetMetaOk() (*PaginationMetaMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ListUsers200Response) SetMeta(v PaginationMetaMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ListUsers200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### GetData

`func (o *ListUsers200Response) GetData() []User`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListUsers200Response) GetDataOk() (*[]User, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListUsers200Response) SetData(v []User)`

SetData sets Data field to given value.

### HasData

`func (o *ListUsers200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


