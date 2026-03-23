# PaginationMeta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Links** | Pointer to [**PaginationMetaLinks**](PaginationMetaLinks.md) |  | [optional] 
**Meta** | Pointer to [**PaginationMetaMeta**](PaginationMetaMeta.md) |  | [optional] 

## Methods

### NewPaginationMeta

`func NewPaginationMeta() *PaginationMeta`

NewPaginationMeta instantiates a new PaginationMeta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaginationMetaWithDefaults

`func NewPaginationMetaWithDefaults() *PaginationMeta`

NewPaginationMetaWithDefaults instantiates a new PaginationMeta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLinks

`func (o *PaginationMeta) GetLinks() PaginationMetaLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *PaginationMeta) GetLinksOk() (*PaginationMetaLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *PaginationMeta) SetLinks(v PaginationMetaLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *PaginationMeta) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *PaginationMeta) GetMeta() PaginationMetaMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *PaginationMeta) GetMetaOk() (*PaginationMetaMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *PaginationMeta) SetMeta(v PaginationMetaMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *PaginationMeta) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


