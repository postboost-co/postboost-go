# FreeToolBuildHashtagGroupsRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** | Hashtags or words, separated by spaces, commas or new lines. A missing # is added. | 
**Network** | Pointer to **string** | Network whose hashtag cap applies. | [optional] [default to "instagram"]
**GroupSize** | Pointer to **int32** | Hashtags per group. Default: the network&#39;s cap, or 5 when it has no hard cap. | [optional] 
**Case** | Pointer to **string** | keep the first spelling of each hashtag, or lower-case all of them. | [optional] [default to "keep"]
**Format** | Pointer to **string** | inline: one line of tags. first_comment: five \&quot;.\&quot; lines, then the tags. | [optional] [default to "inline"]

## Methods

### NewFreeToolBuildHashtagGroupsRequest

`func NewFreeToolBuildHashtagGroupsRequest(text string, ) *FreeToolBuildHashtagGroupsRequest`

NewFreeToolBuildHashtagGroupsRequest instantiates a new FreeToolBuildHashtagGroupsRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolBuildHashtagGroupsRequestWithDefaults

`func NewFreeToolBuildHashtagGroupsRequestWithDefaults() *FreeToolBuildHashtagGroupsRequest`

NewFreeToolBuildHashtagGroupsRequestWithDefaults instantiates a new FreeToolBuildHashtagGroupsRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolBuildHashtagGroupsRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolBuildHashtagGroupsRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolBuildHashtagGroupsRequest) SetText(v string)`

SetText sets Text field to given value.


### GetNetwork

`func (o *FreeToolBuildHashtagGroupsRequest) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *FreeToolBuildHashtagGroupsRequest) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *FreeToolBuildHashtagGroupsRequest) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *FreeToolBuildHashtagGroupsRequest) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### GetGroupSize

`func (o *FreeToolBuildHashtagGroupsRequest) GetGroupSize() int32`

GetGroupSize returns the GroupSize field if non-nil, zero value otherwise.

### GetGroupSizeOk

`func (o *FreeToolBuildHashtagGroupsRequest) GetGroupSizeOk() (*int32, bool)`

GetGroupSizeOk returns a tuple with the GroupSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupSize

`func (o *FreeToolBuildHashtagGroupsRequest) SetGroupSize(v int32)`

SetGroupSize sets GroupSize field to given value.

### HasGroupSize

`func (o *FreeToolBuildHashtagGroupsRequest) HasGroupSize() bool`

HasGroupSize returns a boolean if a field has been set.

### GetCase

`func (o *FreeToolBuildHashtagGroupsRequest) GetCase() string`

GetCase returns the Case field if non-nil, zero value otherwise.

### GetCaseOk

`func (o *FreeToolBuildHashtagGroupsRequest) GetCaseOk() (*string, bool)`

GetCaseOk returns a tuple with the Case field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCase

`func (o *FreeToolBuildHashtagGroupsRequest) SetCase(v string)`

SetCase sets Case field to given value.

### HasCase

`func (o *FreeToolBuildHashtagGroupsRequest) HasCase() bool`

HasCase returns a boolean if a field has been set.

### GetFormat

`func (o *FreeToolBuildHashtagGroupsRequest) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *FreeToolBuildHashtagGroupsRequest) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *FreeToolBuildHashtagGroupsRequest) SetFormat(v string)`

SetFormat sets Format field to given value.

### HasFormat

`func (o *FreeToolBuildHashtagGroupsRequest) HasFormat() bool`

HasFormat returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


