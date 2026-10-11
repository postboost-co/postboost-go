# PublishProgress

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | **int32** | Number of accounts the post goes to. | 
**Published** | **int32** |  | 
**Failed** | **int32** |  | 

## Methods

### NewPublishProgress

`func NewPublishProgress(total int32, published int32, failed int32, ) *PublishProgress`

NewPublishProgress instantiates a new PublishProgress object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPublishProgressWithDefaults

`func NewPublishProgressWithDefaults() *PublishProgress`

NewPublishProgressWithDefaults instantiates a new PublishProgress object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *PublishProgress) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *PublishProgress) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *PublishProgress) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetPublished

`func (o *PublishProgress) GetPublished() int32`

GetPublished returns the Published field if non-nil, zero value otherwise.

### GetPublishedOk

`func (o *PublishProgress) GetPublishedOk() (*int32, bool)`

GetPublishedOk returns a tuple with the Published field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublished

`func (o *PublishProgress) SetPublished(v int32)`

SetPublished sets Published field to given value.


### GetFailed

`func (o *PublishProgress) GetFailed() int32`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *PublishProgress) GetFailedOk() (*int32, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *PublishProgress) SetFailed(v int32)`

SetFailed sets Failed field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


