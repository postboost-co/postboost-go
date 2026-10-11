# AddPostToQueueRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Timezone** | Pointer to **string** | Accepted and validated for consistency with the other scheduling endpoints; queue slots are always taken from the workspace posting schedule. | [optional] 

## Methods

### NewAddPostToQueueRequest

`func NewAddPostToQueueRequest() *AddPostToQueueRequest`

NewAddPostToQueueRequest instantiates a new AddPostToQueueRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAddPostToQueueRequestWithDefaults

`func NewAddPostToQueueRequestWithDefaults() *AddPostToQueueRequest`

NewAddPostToQueueRequestWithDefaults instantiates a new AddPostToQueueRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTimezone

`func (o *AddPostToQueueRequest) GetTimezone() string`

GetTimezone returns the Timezone field if non-nil, zero value otherwise.

### GetTimezoneOk

`func (o *AddPostToQueueRequest) GetTimezoneOk() (*string, bool)`

GetTimezoneOk returns a tuple with the Timezone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimezone

`func (o *AddPostToQueueRequest) SetTimezone(v string)`

SetTimezone sets Timezone field to given value.

### HasTimezone

`func (o *AddPostToQueueRequest) HasTimezone() bool`

HasTimezone returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


