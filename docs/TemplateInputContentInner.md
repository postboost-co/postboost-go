# TemplateInputContentInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Body** | Pointer to **NullableString** |  | [optional] 
**Media** | Pointer to **[]int32** | Media &#x60;id&#x60;s from the media library. | [optional] 

## Methods

### NewTemplateInputContentInner

`func NewTemplateInputContentInner() *TemplateInputContentInner`

NewTemplateInputContentInner instantiates a new TemplateInputContentInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTemplateInputContentInnerWithDefaults

`func NewTemplateInputContentInnerWithDefaults() *TemplateInputContentInner`

NewTemplateInputContentInnerWithDefaults instantiates a new TemplateInputContentInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBody

`func (o *TemplateInputContentInner) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *TemplateInputContentInner) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *TemplateInputContentInner) SetBody(v string)`

SetBody sets Body field to given value.

### HasBody

`func (o *TemplateInputContentInner) HasBody() bool`

HasBody returns a boolean if a field has been set.

### SetBodyNil

`func (o *TemplateInputContentInner) SetBodyNil(b bool)`

 SetBodyNil sets the value for Body to be an explicit nil

### UnsetBody
`func (o *TemplateInputContentInner) UnsetBody()`

UnsetBody ensures that no value is present for Body, not even an explicit nil
### GetMedia

`func (o *TemplateInputContentInner) GetMedia() []int32`

GetMedia returns the Media field if non-nil, zero value otherwise.

### GetMediaOk

`func (o *TemplateInputContentInner) GetMediaOk() (*[]int32, bool)`

GetMediaOk returns a tuple with the Media field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMedia

`func (o *TemplateInputContentInner) SetMedia(v []int32)`

SetMedia sets Media field to given value.

### HasMedia

`func (o *TemplateInputContentInner) HasMedia() bool`

HasMedia returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


