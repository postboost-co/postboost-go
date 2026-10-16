# FreeToolSearchEmojiRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Query** | Pointer to **string** | Words to look for in the emoji name and keywords, e.g. &#x60;fire&#x60; or &#x60;party&#x60;. Empty lists the category in Unicode order. | [optional] [default to ""]
**Category** | Pointer to **string** | Only emoji of this Unicode category. | [optional] 
**Limit** | Pointer to **int32** |  | [optional] [default to 30]

## Methods

### NewFreeToolSearchEmojiRequest

`func NewFreeToolSearchEmojiRequest() *FreeToolSearchEmojiRequest`

NewFreeToolSearchEmojiRequest instantiates a new FreeToolSearchEmojiRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolSearchEmojiRequestWithDefaults

`func NewFreeToolSearchEmojiRequestWithDefaults() *FreeToolSearchEmojiRequest`

NewFreeToolSearchEmojiRequestWithDefaults instantiates a new FreeToolSearchEmojiRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuery

`func (o *FreeToolSearchEmojiRequest) GetQuery() string`

GetQuery returns the Query field if non-nil, zero value otherwise.

### GetQueryOk

`func (o *FreeToolSearchEmojiRequest) GetQueryOk() (*string, bool)`

GetQueryOk returns a tuple with the Query field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuery

`func (o *FreeToolSearchEmojiRequest) SetQuery(v string)`

SetQuery sets Query field to given value.

### HasQuery

`func (o *FreeToolSearchEmojiRequest) HasQuery() bool`

HasQuery returns a boolean if a field has been set.

### GetCategory

`func (o *FreeToolSearchEmojiRequest) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *FreeToolSearchEmojiRequest) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *FreeToolSearchEmojiRequest) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *FreeToolSearchEmojiRequest) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetLimit

`func (o *FreeToolSearchEmojiRequest) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *FreeToolSearchEmojiRequest) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *FreeToolSearchEmojiRequest) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *FreeToolSearchEmojiRequest) HasLimit() bool`

HasLimit returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


