# TemplateInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Content** | Pointer to [**[]TemplateInputContentInner**](TemplateInputContentInner.md) | One item per post in a thread; usually one. | [optional] 

## Methods

### NewTemplateInput

`func NewTemplateInput(name string, ) *TemplateInput`

NewTemplateInput instantiates a new TemplateInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTemplateInputWithDefaults

`func NewTemplateInputWithDefaults() *TemplateInput`

NewTemplateInputWithDefaults instantiates a new TemplateInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *TemplateInput) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TemplateInput) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TemplateInput) SetName(v string)`

SetName sets Name field to given value.


### GetContent

`func (o *TemplateInput) GetContent() []TemplateInputContentInner`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *TemplateInput) GetContentOk() (*[]TemplateInputContentInner, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *TemplateInput) SetContent(v []TemplateInputContentInner)`

SetContent sets Content field to given value.

### HasContent

`func (o *TemplateInput) HasContent() bool`

HasContent returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


