# FreeToolGetHookTemplatesResponseHooksInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | Pointer to **string** | The hook, with &#x60;{topic}&#x60; filled in when a topic was given. | [optional] 
**Template** | Pointer to **string** | The template with its &#x60;{topic}&#x60; placeholder. | [optional] 
**Category** | Pointer to **string** | Hook style. | [optional] 
**Networks** | Pointer to **[]string** | Networks the hook suits. | [optional] 

## Methods

### NewFreeToolGetHookTemplatesResponseHooksInner

`func NewFreeToolGetHookTemplatesResponseHooksInner() *FreeToolGetHookTemplatesResponseHooksInner`

NewFreeToolGetHookTemplatesResponseHooksInner instantiates a new FreeToolGetHookTemplatesResponseHooksInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGetHookTemplatesResponseHooksInnerWithDefaults

`func NewFreeToolGetHookTemplatesResponseHooksInnerWithDefaults() *FreeToolGetHookTemplatesResponseHooksInner`

NewFreeToolGetHookTemplatesResponseHooksInnerWithDefaults instantiates a new FreeToolGetHookTemplatesResponseHooksInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolGetHookTemplatesResponseHooksInner) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolGetHookTemplatesResponseHooksInner) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolGetHookTemplatesResponseHooksInner) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *FreeToolGetHookTemplatesResponseHooksInner) HasText() bool`

HasText returns a boolean if a field has been set.

### GetTemplate

`func (o *FreeToolGetHookTemplatesResponseHooksInner) GetTemplate() string`

GetTemplate returns the Template field if non-nil, zero value otherwise.

### GetTemplateOk

`func (o *FreeToolGetHookTemplatesResponseHooksInner) GetTemplateOk() (*string, bool)`

GetTemplateOk returns a tuple with the Template field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplate

`func (o *FreeToolGetHookTemplatesResponseHooksInner) SetTemplate(v string)`

SetTemplate sets Template field to given value.

### HasTemplate

`func (o *FreeToolGetHookTemplatesResponseHooksInner) HasTemplate() bool`

HasTemplate returns a boolean if a field has been set.

### GetCategory

`func (o *FreeToolGetHookTemplatesResponseHooksInner) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *FreeToolGetHookTemplatesResponseHooksInner) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *FreeToolGetHookTemplatesResponseHooksInner) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *FreeToolGetHookTemplatesResponseHooksInner) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetNetworks

`func (o *FreeToolGetHookTemplatesResponseHooksInner) GetNetworks() []string`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *FreeToolGetHookTemplatesResponseHooksInner) GetNetworksOk() (*[]string, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *FreeToolGetHookTemplatesResponseHooksInner) SetNetworks(v []string)`

SetNetworks sets Networks field to given value.

### HasNetworks

`func (o *FreeToolGetHookTemplatesResponseHooksInner) HasNetworks() bool`

HasNetworks returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


