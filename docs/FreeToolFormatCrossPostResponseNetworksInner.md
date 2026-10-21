# FreeToolFormatCrossPostResponseNetworksInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | Pointer to **string** |  | [optional] 
**Label** | Pointer to **string** |  | [optional] 
**Limit** | Pointer to **int32** |  | [optional] 
**Count** | Pointer to **int32** | Length as the network counts it. | [optional] 
**Fits** | Pointer to **bool** |  | [optional] 
**OverBy** | Pointer to **int32** | Characters over the limit; 0 when it fits. | [optional] 
**Links** | Pointer to **int32** | Unique http(s) links in the text (trailing punctuation trimmed), as Threads counts them. | [optional] 
**Warnings** | Pointer to [**[]FreeToolCheckPostResponseNetworksInnerErrorsInner**](FreeToolCheckPostResponseNetworksInnerErrorsInner.md) | Codes: threads_too_many_links, cut_by_fold, mentions_not_portable. | [optional] 
**Thread** | Pointer to [**[]FreeToolFormatCrossPostResponseNetworksInnerThreadInner**](FreeToolFormatCrossPostResponseNetworksInnerThreadInner.md) | The thread for a text that does not fit (X, Threads, Bluesky, Mastodon); null when it fits or on LinkedIn. | [optional] 

## Methods

### NewFreeToolFormatCrossPostResponseNetworksInner

`func NewFreeToolFormatCrossPostResponseNetworksInner() *FreeToolFormatCrossPostResponseNetworksInner`

NewFreeToolFormatCrossPostResponseNetworksInner instantiates a new FreeToolFormatCrossPostResponseNetworksInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolFormatCrossPostResponseNetworksInnerWithDefaults

`func NewFreeToolFormatCrossPostResponseNetworksInnerWithDefaults() *FreeToolFormatCrossPostResponseNetworksInner`

NewFreeToolFormatCrossPostResponseNetworksInnerWithDefaults instantiates a new FreeToolFormatCrossPostResponseNetworksInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *FreeToolFormatCrossPostResponseNetworksInner) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *FreeToolFormatCrossPostResponseNetworksInner) HasKey() bool`

HasKey returns a boolean if a field has been set.

### GetLabel

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *FreeToolFormatCrossPostResponseNetworksInner) SetLabel(v string)`

SetLabel sets Label field to given value.

### HasLabel

`func (o *FreeToolFormatCrossPostResponseNetworksInner) HasLabel() bool`

HasLabel returns a boolean if a field has been set.

### GetLimit

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *FreeToolFormatCrossPostResponseNetworksInner) SetLimit(v int32)`

SetLimit sets Limit field to given value.

### HasLimit

`func (o *FreeToolFormatCrossPostResponseNetworksInner) HasLimit() bool`

HasLimit returns a boolean if a field has been set.

### GetCount

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *FreeToolFormatCrossPostResponseNetworksInner) SetCount(v int32)`

SetCount sets Count field to given value.

### HasCount

`func (o *FreeToolFormatCrossPostResponseNetworksInner) HasCount() bool`

HasCount returns a boolean if a field has been set.

### GetFits

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetFits() bool`

GetFits returns the Fits field if non-nil, zero value otherwise.

### GetFitsOk

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetFitsOk() (*bool, bool)`

GetFitsOk returns a tuple with the Fits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFits

`func (o *FreeToolFormatCrossPostResponseNetworksInner) SetFits(v bool)`

SetFits sets Fits field to given value.

### HasFits

`func (o *FreeToolFormatCrossPostResponseNetworksInner) HasFits() bool`

HasFits returns a boolean if a field has been set.

### GetOverBy

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetOverBy() int32`

GetOverBy returns the OverBy field if non-nil, zero value otherwise.

### GetOverByOk

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetOverByOk() (*int32, bool)`

GetOverByOk returns a tuple with the OverBy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverBy

`func (o *FreeToolFormatCrossPostResponseNetworksInner) SetOverBy(v int32)`

SetOverBy sets OverBy field to given value.

### HasOverBy

`func (o *FreeToolFormatCrossPostResponseNetworksInner) HasOverBy() bool`

HasOverBy returns a boolean if a field has been set.

### GetLinks

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetLinks() int32`

GetLinks returns the Links field if non-nil, zero value otherwise.

### GetLinksOk

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetLinksOk() (*int32, bool)`

GetLinksOk returns a tuple with the Links field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinks

`func (o *FreeToolFormatCrossPostResponseNetworksInner) SetLinks(v int32)`

SetLinks sets Links field to given value.

### HasLinks

`func (o *FreeToolFormatCrossPostResponseNetworksInner) HasLinks() bool`

HasLinks returns a boolean if a field has been set.

### GetWarnings

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetWarnings() []FreeToolCheckPostResponseNetworksInnerErrorsInner`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetWarningsOk() (*[]FreeToolCheckPostResponseNetworksInnerErrorsInner, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *FreeToolFormatCrossPostResponseNetworksInner) SetWarnings(v []FreeToolCheckPostResponseNetworksInnerErrorsInner)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *FreeToolFormatCrossPostResponseNetworksInner) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.

### GetThread

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetThread() []FreeToolFormatCrossPostResponseNetworksInnerThreadInner`

GetThread returns the Thread field if non-nil, zero value otherwise.

### GetThreadOk

`func (o *FreeToolFormatCrossPostResponseNetworksInner) GetThreadOk() (*[]FreeToolFormatCrossPostResponseNetworksInnerThreadInner, bool)`

GetThreadOk returns a tuple with the Thread field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThread

`func (o *FreeToolFormatCrossPostResponseNetworksInner) SetThread(v []FreeToolFormatCrossPostResponseNetworksInnerThreadInner)`

SetThread sets Thread field to given value.

### HasThread

`func (o *FreeToolFormatCrossPostResponseNetworksInner) HasThread() bool`

HasThread returns a boolean if a field has been set.

### SetThreadNil

`func (o *FreeToolFormatCrossPostResponseNetworksInner) SetThreadNil(b bool)`

 SetThreadNil sets the value for Thread to be an explicit nil

### UnsetThread
`func (o *FreeToolFormatCrossPostResponseNetworksInner) UnsetThread()`

UnsetThread ensures that no value is present for Thread, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


