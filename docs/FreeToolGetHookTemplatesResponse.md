# FreeToolGetHookTemplatesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Hooks** | Pointer to [**[]FreeToolGetHookTemplatesResponseHooksInner**](FreeToolGetHookTemplatesResponseHooksInner.md) |  | [optional] 
**Total** | Pointer to **int32** | Number of hooks returned. | [optional] 

## Methods

### NewFreeToolGetHookTemplatesResponse

`func NewFreeToolGetHookTemplatesResponse() *FreeToolGetHookTemplatesResponse`

NewFreeToolGetHookTemplatesResponse instantiates a new FreeToolGetHookTemplatesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGetHookTemplatesResponseWithDefaults

`func NewFreeToolGetHookTemplatesResponseWithDefaults() *FreeToolGetHookTemplatesResponse`

NewFreeToolGetHookTemplatesResponseWithDefaults instantiates a new FreeToolGetHookTemplatesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHooks

`func (o *FreeToolGetHookTemplatesResponse) GetHooks() []FreeToolGetHookTemplatesResponseHooksInner`

GetHooks returns the Hooks field if non-nil, zero value otherwise.

### GetHooksOk

`func (o *FreeToolGetHookTemplatesResponse) GetHooksOk() (*[]FreeToolGetHookTemplatesResponseHooksInner, bool)`

GetHooksOk returns a tuple with the Hooks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHooks

`func (o *FreeToolGetHookTemplatesResponse) SetHooks(v []FreeToolGetHookTemplatesResponseHooksInner)`

SetHooks sets Hooks field to given value.

### HasHooks

`func (o *FreeToolGetHookTemplatesResponse) HasHooks() bool`

HasHooks returns a boolean if a field has been set.

### GetTotal

`func (o *FreeToolGetHookTemplatesResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *FreeToolGetHookTemplatesResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *FreeToolGetHookTemplatesResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *FreeToolGetHookTemplatesResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


