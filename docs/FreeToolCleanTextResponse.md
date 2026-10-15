# FreeToolCleanTextResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | Pointer to **string** |  | [optional] 
**Changes** | Pointer to [**[]FreeToolCleanTextResponseChangesInner**](FreeToolCleanTextResponseChangesInner.md) | One entry per change type that changed something. | [optional] 
**Flags** | Pointer to [**[]FreeToolCleanTextResponseFlagsInner**](FreeToolCleanTextResponseFlagsInner.md) | AI phrases in the cleaned text, by offset (Unicode code points). | [optional] 

## Methods

### NewFreeToolCleanTextResponse

`func NewFreeToolCleanTextResponse() *FreeToolCleanTextResponse`

NewFreeToolCleanTextResponse instantiates a new FreeToolCleanTextResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCleanTextResponseWithDefaults

`func NewFreeToolCleanTextResponseWithDefaults() *FreeToolCleanTextResponse`

NewFreeToolCleanTextResponseWithDefaults instantiates a new FreeToolCleanTextResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolCleanTextResponse) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolCleanTextResponse) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolCleanTextResponse) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *FreeToolCleanTextResponse) HasText() bool`

HasText returns a boolean if a field has been set.

### GetChanges

`func (o *FreeToolCleanTextResponse) GetChanges() []FreeToolCleanTextResponseChangesInner`

GetChanges returns the Changes field if non-nil, zero value otherwise.

### GetChangesOk

`func (o *FreeToolCleanTextResponse) GetChangesOk() (*[]FreeToolCleanTextResponseChangesInner, bool)`

GetChangesOk returns a tuple with the Changes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChanges

`func (o *FreeToolCleanTextResponse) SetChanges(v []FreeToolCleanTextResponseChangesInner)`

SetChanges sets Changes field to given value.

### HasChanges

`func (o *FreeToolCleanTextResponse) HasChanges() bool`

HasChanges returns a boolean if a field has been set.

### GetFlags

`func (o *FreeToolCleanTextResponse) GetFlags() []FreeToolCleanTextResponseFlagsInner`

GetFlags returns the Flags field if non-nil, zero value otherwise.

### GetFlagsOk

`func (o *FreeToolCleanTextResponse) GetFlagsOk() (*[]FreeToolCleanTextResponseFlagsInner, bool)`

GetFlagsOk returns a tuple with the Flags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlags

`func (o *FreeToolCleanTextResponse) SetFlags(v []FreeToolCleanTextResponseFlagsInner)`

SetFlags sets Flags field to given value.

### HasFlags

`func (o *FreeToolCleanTextResponse) HasFlags() bool`

HasFlags returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


