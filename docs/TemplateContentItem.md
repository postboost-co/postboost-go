# TemplateContentItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Body** | **string** |  | 
**Media** | **[]map[string]interface{}** | Media items from the library (same shape as the media endpoints). | 

## Methods

### NewTemplateContentItem

`func NewTemplateContentItem(body string, media []map[string]interface{}, ) *TemplateContentItem`

NewTemplateContentItem instantiates a new TemplateContentItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTemplateContentItemWithDefaults

`func NewTemplateContentItemWithDefaults() *TemplateContentItem`

NewTemplateContentItemWithDefaults instantiates a new TemplateContentItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBody

`func (o *TemplateContentItem) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *TemplateContentItem) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *TemplateContentItem) SetBody(v string)`

SetBody sets Body field to given value.


### GetMedia

`func (o *TemplateContentItem) GetMedia() []map[string]interface{}`

GetMedia returns the Media field if non-nil, zero value otherwise.

### GetMediaOk

`func (o *TemplateContentItem) GetMediaOk() (*[]map[string]interface{}, bool)`

GetMediaOk returns a tuple with the Media field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMedia

`func (o *TemplateContentItem) SetMedia(v []map[string]interface{})`

SetMedia sets Media field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


