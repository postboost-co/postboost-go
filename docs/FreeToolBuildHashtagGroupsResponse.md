# FreeToolBuildHashtagGroupsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Hashtags** | Pointer to **[]string** | Clean hashtags in input order, duplicates removed. | [optional] 
**Removed** | Pointer to [**[]FreeToolBuildHashtagGroupsResponseRemovedInner**](FreeToolBuildHashtagGroupsResponseRemovedInner.md) | Entries that were dropped, with the reason. | [optional] 
**Cap** | Pointer to **NullableInt32** | Hashtags PostBoost allows per post on the network; null &#x3D; no hard limit. | [optional] 
**GroupSize** | Pointer to **int32** | Hashtags per group that was used. | [optional] 
**Groups** | Pointer to [**[]FreeToolBuildHashtagGroupsResponseGroupsInner**](FreeToolBuildHashtagGroupsResponseGroupsInner.md) |  | [optional] 
**OverCap** | Pointer to **bool** | A group holds more hashtags than the cap. | [optional] 

## Methods

### NewFreeToolBuildHashtagGroupsResponse

`func NewFreeToolBuildHashtagGroupsResponse() *FreeToolBuildHashtagGroupsResponse`

NewFreeToolBuildHashtagGroupsResponse instantiates a new FreeToolBuildHashtagGroupsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolBuildHashtagGroupsResponseWithDefaults

`func NewFreeToolBuildHashtagGroupsResponseWithDefaults() *FreeToolBuildHashtagGroupsResponse`

NewFreeToolBuildHashtagGroupsResponseWithDefaults instantiates a new FreeToolBuildHashtagGroupsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHashtags

`func (o *FreeToolBuildHashtagGroupsResponse) GetHashtags() []string`

GetHashtags returns the Hashtags field if non-nil, zero value otherwise.

### GetHashtagsOk

`func (o *FreeToolBuildHashtagGroupsResponse) GetHashtagsOk() (*[]string, bool)`

GetHashtagsOk returns a tuple with the Hashtags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHashtags

`func (o *FreeToolBuildHashtagGroupsResponse) SetHashtags(v []string)`

SetHashtags sets Hashtags field to given value.

### HasHashtags

`func (o *FreeToolBuildHashtagGroupsResponse) HasHashtags() bool`

HasHashtags returns a boolean if a field has been set.

### GetRemoved

`func (o *FreeToolBuildHashtagGroupsResponse) GetRemoved() []FreeToolBuildHashtagGroupsResponseRemovedInner`

GetRemoved returns the Removed field if non-nil, zero value otherwise.

### GetRemovedOk

`func (o *FreeToolBuildHashtagGroupsResponse) GetRemovedOk() (*[]FreeToolBuildHashtagGroupsResponseRemovedInner, bool)`

GetRemovedOk returns a tuple with the Removed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoved

`func (o *FreeToolBuildHashtagGroupsResponse) SetRemoved(v []FreeToolBuildHashtagGroupsResponseRemovedInner)`

SetRemoved sets Removed field to given value.

### HasRemoved

`func (o *FreeToolBuildHashtagGroupsResponse) HasRemoved() bool`

HasRemoved returns a boolean if a field has been set.

### GetCap

`func (o *FreeToolBuildHashtagGroupsResponse) GetCap() int32`

GetCap returns the Cap field if non-nil, zero value otherwise.

### GetCapOk

`func (o *FreeToolBuildHashtagGroupsResponse) GetCapOk() (*int32, bool)`

GetCapOk returns a tuple with the Cap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCap

`func (o *FreeToolBuildHashtagGroupsResponse) SetCap(v int32)`

SetCap sets Cap field to given value.

### HasCap

`func (o *FreeToolBuildHashtagGroupsResponse) HasCap() bool`

HasCap returns a boolean if a field has been set.

### SetCapNil

`func (o *FreeToolBuildHashtagGroupsResponse) SetCapNil(b bool)`

 SetCapNil sets the value for Cap to be an explicit nil

### UnsetCap
`func (o *FreeToolBuildHashtagGroupsResponse) UnsetCap()`

UnsetCap ensures that no value is present for Cap, not even an explicit nil
### GetGroupSize

`func (o *FreeToolBuildHashtagGroupsResponse) GetGroupSize() int32`

GetGroupSize returns the GroupSize field if non-nil, zero value otherwise.

### GetGroupSizeOk

`func (o *FreeToolBuildHashtagGroupsResponse) GetGroupSizeOk() (*int32, bool)`

GetGroupSizeOk returns a tuple with the GroupSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroupSize

`func (o *FreeToolBuildHashtagGroupsResponse) SetGroupSize(v int32)`

SetGroupSize sets GroupSize field to given value.

### HasGroupSize

`func (o *FreeToolBuildHashtagGroupsResponse) HasGroupSize() bool`

HasGroupSize returns a boolean if a field has been set.

### GetGroups

`func (o *FreeToolBuildHashtagGroupsResponse) GetGroups() []FreeToolBuildHashtagGroupsResponseGroupsInner`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *FreeToolBuildHashtagGroupsResponse) GetGroupsOk() (*[]FreeToolBuildHashtagGroupsResponseGroupsInner, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *FreeToolBuildHashtagGroupsResponse) SetGroups(v []FreeToolBuildHashtagGroupsResponseGroupsInner)`

SetGroups sets Groups field to given value.

### HasGroups

`func (o *FreeToolBuildHashtagGroupsResponse) HasGroups() bool`

HasGroups returns a boolean if a field has been set.

### GetOverCap

`func (o *FreeToolBuildHashtagGroupsResponse) GetOverCap() bool`

GetOverCap returns the OverCap field if non-nil, zero value otherwise.

### GetOverCapOk

`func (o *FreeToolBuildHashtagGroupsResponse) GetOverCapOk() (*bool, bool)`

GetOverCapOk returns a tuple with the OverCap field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOverCap

`func (o *FreeToolBuildHashtagGroupsResponse) SetOverCap(v bool)`

SetOverCap sets OverCap field to given value.

### HasOverCap

`func (o *FreeToolBuildHashtagGroupsResponse) HasOverCap() bool`

HasOverCap returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


