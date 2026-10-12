# ListInboxReplyDrafts200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Links** | Pointer to [**PaginationMetaLinks**](PaginationMetaLinks.md) |  | [optional] 
**Meta** | Pointer to [**PaginationMetaMeta**](PaginationMetaMeta.md) |  | [optional] 
**Data** | Pointer to [**[]InboxReplyDraft**](InboxReplyDraft.md) |  | [optional] 

## Methods

### NewListInboxReplyDrafts200Response

`func NewListInboxReplyDrafts200Response() *ListInboxReplyDrafts200Response`

NewListInboxReplyDrafts200Response instantiates a new ListInboxReplyDrafts200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListInboxReplyDrafts200ResponseWithDefaults

`func NewListInboxReplyDrafts200ResponseWithDefaults() *ListInboxReplyDrafts200Response`

NewListInboxReplyDrafts200ResponseWithDefaults instantiates a new ListInboxReplyDrafts200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLinks

`func (o *ListInboxReplyDrafts200Response) GetLinks() PaginationMetaLinks`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *ListInboxReplyDrafts200Response) GetLinksOk() (*PaginationMetaLinks, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *ListInboxReplyDrafts200Response) SetLinks(v PaginationMetaLinks)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *ListInboxReplyDrafts200Response) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetMeta

`func (o *ListInboxReplyDrafts200Response) GetMeta() PaginationMetaMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ListInboxReplyDrafts200Response) GetMetaOk() (*PaginationMetaMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ListInboxReplyDrafts200Response) SetMeta(v PaginationMetaMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ListInboxReplyDrafts200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.

### GetData

`func (o *ListInboxReplyDrafts200Response) GetData() []InboxReplyDraft`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListInboxReplyDrafts200Response) GetDataOk() (*[]InboxReplyDraft, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListInboxReplyDrafts200Response) SetData(v []InboxReplyDraft)`

SetData sets Data field to given value.

### HasData

`func (o *ListInboxReplyDrafts200Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


