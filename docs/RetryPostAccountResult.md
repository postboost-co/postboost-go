# RetryPostAccountResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Status** | [**PostStatus**](PostStatus.md) |  | 
**PublishProgress** | [**PublishProgress**](PublishProgress.md) |  | 

## Methods

### NewRetryPostAccountResult

`func NewRetryPostAccountResult(success bool, status PostStatus, publishProgress PublishProgress, ) *RetryPostAccountResult`

NewRetryPostAccountResult instantiates a new RetryPostAccountResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRetryPostAccountResultWithDefaults

`func NewRetryPostAccountResultWithDefaults() *RetryPostAccountResult`

NewRetryPostAccountResultWithDefaults instantiates a new RetryPostAccountResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *RetryPostAccountResult) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *RetryPostAccountResult) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *RetryPostAccountResult) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetStatus

`func (o *RetryPostAccountResult) GetStatus() PostStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RetryPostAccountResult) GetStatusOk() (*PostStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RetryPostAccountResult) SetStatus(v PostStatus)`

SetStatus sets Status field to given value.


### GetPublishProgress

`func (o *RetryPostAccountResult) GetPublishProgress() PublishProgress`

GetPublishProgress returns the PublishProgress field if non-nil, zero value otherwise.

### GetPublishProgressOk

`func (o *RetryPostAccountResult) GetPublishProgressOk() (*PublishProgress, bool)`

GetPublishProgressOk returns a tuple with the PublishProgress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPublishProgress

`func (o *RetryPostAccountResult) SetPublishProgress(v PublishProgress)`

SetPublishProgress sets PublishProgress field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


