# MediaFolder

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uuid** | **string** |  | 
**Name** | **string** |  | 
**Parent** | **string** | UUID of the parent folder; null for a top-level folder. | 
**MediaCount** | **int32** | Media filed anywhere below the folder, including its sub-folders. | 

## Methods

### NewMediaFolder

`func NewMediaFolder(uuid string, name string, parent string, mediaCount int32, ) *MediaFolder`

NewMediaFolder instantiates a new MediaFolder object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMediaFolderWithDefaults

`func NewMediaFolderWithDefaults() *MediaFolder`

NewMediaFolderWithDefaults instantiates a new MediaFolder object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUuid

`func (o *MediaFolder) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *MediaFolder) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *MediaFolder) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *MediaFolder) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *MediaFolder) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *MediaFolder) SetName(v string)`

SetName sets Name field to given value.


### GetParent

`func (o *MediaFolder) GetParent() string`

GetParent returns the Parent field if non-nil, zero value otherwise.

### GetParentOk

`func (o *MediaFolder) GetParentOk() (*string, bool)`

GetParentOk returns a tuple with the Parent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParent

`func (o *MediaFolder) SetParent(v string)`

SetParent sets Parent field to given value.


### GetMediaCount

`func (o *MediaFolder) GetMediaCount() int32`

GetMediaCount returns the MediaCount field if non-nil, zero value otherwise.

### GetMediaCountOk

`func (o *MediaFolder) GetMediaCountOk() (*int32, bool)`

GetMediaCountOk returns a tuple with the MediaCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMediaCount

`func (o *MediaFolder) SetMediaCount(v int32)`

SetMediaCount sets MediaCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


