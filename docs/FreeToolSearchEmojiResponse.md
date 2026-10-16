# FreeToolSearchEmojiResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Results** | Pointer to [**[]FreeToolSearchEmojiResponseResultsInner**](FreeToolSearchEmojiResponseResultsInner.md) |  | [optional] 
**Total** | Pointer to **int32** | Matches before &#x60;limit&#x60;. | [optional] 

## Methods

### NewFreeToolSearchEmojiResponse

`func NewFreeToolSearchEmojiResponse() *FreeToolSearchEmojiResponse`

NewFreeToolSearchEmojiResponse instantiates a new FreeToolSearchEmojiResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolSearchEmojiResponseWithDefaults

`func NewFreeToolSearchEmojiResponseWithDefaults() *FreeToolSearchEmojiResponse`

NewFreeToolSearchEmojiResponseWithDefaults instantiates a new FreeToolSearchEmojiResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResults

`func (o *FreeToolSearchEmojiResponse) GetResults() []FreeToolSearchEmojiResponseResultsInner`

GetResults returns the Results field if non-nil, zero value otherwise.

### GetResultsOk

`func (o *FreeToolSearchEmojiResponse) GetResultsOk() (*[]FreeToolSearchEmojiResponseResultsInner, bool)`

GetResultsOk returns a tuple with the Results field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResults

`func (o *FreeToolSearchEmojiResponse) SetResults(v []FreeToolSearchEmojiResponseResultsInner)`

SetResults sets Results field to given value.

### HasResults

`func (o *FreeToolSearchEmojiResponse) HasResults() bool`

HasResults returns a boolean if a field has been set.

### GetTotal

`func (o *FreeToolSearchEmojiResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *FreeToolSearchEmojiResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *FreeToolSearchEmojiResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *FreeToolSearchEmojiResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


