# FreeToolCheckReadabilityRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** | The post text. | 
**Language** | Pointer to **string** | Language code. Only English (&#x60;en&#x60;) is scored; other languages return &#x60;supported: false&#x60; and no scores. | [optional] [default to "en"]

## Methods

### NewFreeToolCheckReadabilityRequest

`func NewFreeToolCheckReadabilityRequest(text string, ) *FreeToolCheckReadabilityRequest`

NewFreeToolCheckReadabilityRequest instantiates a new FreeToolCheckReadabilityRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCheckReadabilityRequestWithDefaults

`func NewFreeToolCheckReadabilityRequestWithDefaults() *FreeToolCheckReadabilityRequest`

NewFreeToolCheckReadabilityRequestWithDefaults instantiates a new FreeToolCheckReadabilityRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolCheckReadabilityRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolCheckReadabilityRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolCheckReadabilityRequest) SetText(v string)`

SetText sets Text field to given value.


### GetLanguage

`func (o *FreeToolCheckReadabilityRequest) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *FreeToolCheckReadabilityRequest) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *FreeToolCheckReadabilityRequest) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *FreeToolCheckReadabilityRequest) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


