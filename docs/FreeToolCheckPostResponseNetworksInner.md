# FreeToolCheckPostResponseNetworksInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | Pointer to **string** |  | [optional] 
**Label** | Pointer to **string** |  | [optional] 
**Ok** | Pointer to **bool** | False when an error would stop the post from publishing. | [optional] 
**Count** | Pointer to **int32** | Characters as this network counts them. | [optional] 
**Limit** | Pointer to **int32** |  | [optional] 
**Errors** | Pointer to [**[]FreeToolCheckPostResponseNetworksInnerErrorsInner**](FreeToolCheckPostResponseNetworksInnerErrorsInner.md) | Codes: too_long, too_many_hashtags, media_required, too_many_media, media_type, video_too_long, video_too_short. | [optional] 
**Warnings** | Pointer to [**[]FreeToolCheckPostResponseNetworksInnerErrorsInner**](FreeToolCheckPostResponseNetworksInnerErrorsInner.md) | Codes: cut_by_fold, link_not_clickable. | [optional] 

## Methods

### NewFreeToolCheckPostResponseNetworksInner

`func NewFreeToolCheckPostResponseNetworksInner() *FreeToolCheckPostResponseNetworksInner`

NewFreeToolCheckPostResponseNetworksInner instantiates a new FreeToolCheckPostResponseNetworksInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCheckPostResponseNetworksInnerWithDefaults

`func NewFreeToolCheckPostResponseNetworksInnerWithDefaults() *FreeToolCheckPostResponseNetworksInner`

NewFreeToolCheckPostResponseNetworksInnerWithDefaults instantiates a new FreeToolCheckPostResponseNetworksInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *FreeToolCheckPostResponseNetworksInner) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *FreeToolCheckPostResponseNetworksInner) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *FreeToolCheckPostResponseNetworksInner) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *FreeToolCheckPostResponseNetworksInner) HasKey() bool`

HasKey returns a boolean if a field has been set.

### GetLabel

`func (o *FreeToolCheckPostResponseNetworksInner) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *FreeToolCheckPostResponseNetworksInner) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *FreeToolCheckPostResponseNetworksInner) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *FreeToolCheckPostResponseNetworksInner) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetOk

`func (o *FreeToolCheckPostResponseNetworksInner) GetOk() bool`

GetOk returns the Ok field if non-nil, zero value otherwise.

### GetOkOk

`func (o *FreeToolCheckPostResponseNetworksInner) GetOkOk() (*bool, bool)`

GetOkOk returns a tuple with the Ok field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOk

`func (o *FreeToolCheckPostResponseNetworksInner) SetOk(v bool)`

SetOk sets Ok field to given value.

### HasOk

`func (o *FreeToolCheckPostResponseNetworksInner) HasOk() bool`

HasOk returns a boolean if a field has been set.

### GetCount

`func (o *FreeToolCheckPostResponseNetworksInner) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *FreeToolCheckPostResponseNetworksInner) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *FreeToolCheckPostResponseNetworksInner) SetCount(v int32)`

SetCount sets Count field to given value.

### HasCount

`func (o *FreeToolCheckPostResponseNetworksInner) HasCount() bool`

HasCount returns a boolean if a field has been set.

### GetLimit

`func (o *FreeToolCheckPostResponseNetworksInner) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *FreeToolCheckPostResponseNetworksInner) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *FreeToolCheckPostResponseNetworksInner) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *FreeToolCheckPostResponseNetworksInner) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetErrors

`func (o *FreeToolCheckPostResponseNetworksInner) GetErrors() []FreeToolCheckPostResponseNetworksInnerErrorsInner`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *FreeToolCheckPostResponseNetworksInner) GetErrorsOk() (*[]FreeToolCheckPostResponseNetworksInnerErrorsInner, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *FreeToolCheckPostResponseNetworksInner) SetErrors(v []FreeToolCheckPostResponseNetworksInnerErrorsInner)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *FreeToolCheckPostResponseNetworksInner) HasErrors() bool`

HasErrors returns a boolean if a field has been set.

### GetWarnings

`func (o *FreeToolCheckPostResponseNetworksInner) GetWarnings() []FreeToolCheckPostResponseNetworksInnerErrorsInner`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *FreeToolCheckPostResponseNetworksInner) GetWarningsOk() (*[]FreeToolCheckPostResponseNetworksInnerErrorsInner, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *FreeToolCheckPostResponseNetworksInner) SetWarnings(v []FreeToolCheckPostResponseNetworksInnerErrorsInner)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *FreeToolCheckPostResponseNetworksInner) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


