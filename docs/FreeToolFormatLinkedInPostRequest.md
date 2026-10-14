# FreeToolFormatLinkedInPostRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** |  | 
**Style** | Pointer to **string** | Unicode style for the whole text, e.g. bold. | [optional] 
**List** | Pointer to **string** | Prefix every non-empty line with \&quot;• \&quot; or \&quot;1. \&quot;, \&quot;2. \&quot; (plain digits). | [optional] 

## Methods

### NewFreeToolFormatLinkedInPostRequest

`func NewFreeToolFormatLinkedInPostRequest(text string, ) *FreeToolFormatLinkedInPostRequest`

NewFreeToolFormatLinkedInPostRequest instantiates a new FreeToolFormatLinkedInPostRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolFormatLinkedInPostRequestWithDefaults

`func NewFreeToolFormatLinkedInPostRequestWithDefaults() *FreeToolFormatLinkedInPostRequest`

NewFreeToolFormatLinkedInPostRequestWithDefaults instantiates a new FreeToolFormatLinkedInPostRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolFormatLinkedInPostRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolFormatLinkedInPostRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolFormatLinkedInPostRequest) SetText(v string)`

SetText sets Text field to given value.


### GetStyle

`func (o *FreeToolFormatLinkedInPostRequest) GetStyle() string`

GetStyle returns the Style field if non-nil, zero value otherwise.

### GetStyleOk

`func (o *FreeToolFormatLinkedInPostRequest) GetStyleOk() (*string, bool)`

GetStyleOk returns a tuple with the Style field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStyle

`func (o *FreeToolFormatLinkedInPostRequest) SetStyle(v string)`

SetStyle sets Style field to given value.

### HasStyle

`func (o *FreeToolFormatLinkedInPostRequest) HasStyle() bool`

HasStyle returns a boolean if a field has been set.

### GetList

`func (o *FreeToolFormatLinkedInPostRequest) GetList() string`

GetList returns the List field if non-nil, zero value otherwise.

### GetListOk

`func (o *FreeToolFormatLinkedInPostRequest) GetListOk() (*string, bool)`

GetListOk returns a tuple with the List field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetList

`func (o *FreeToolFormatLinkedInPostRequest) SetList(v string)`

SetList sets List field to given value.

### HasList

`func (o *FreeToolFormatLinkedInPostRequest) HasList() bool`

HasList returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


