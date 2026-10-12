# PollRssFeed200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Created** | **int32** | Posts created from new items. | 
**Skipped** | **int32** | New items refused by a guardrail. | 
**Data** | [**RssFeed**](RssFeed.md) |  | 

## Methods

### NewPollRssFeed200Response

`func NewPollRssFeed200Response(created int32, skipped int32, data RssFeed, ) *PollRssFeed200Response`

NewPollRssFeed200Response instantiates a new PollRssFeed200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPollRssFeed200ResponseWithDefaults

`func NewPollRssFeed200ResponseWithDefaults() *PollRssFeed200Response`

NewPollRssFeed200ResponseWithDefaults instantiates a new PollRssFeed200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCreated

`func (o *PollRssFeed200Response) GetCreated() int32`

GetCreated returns the Created field if non-nil, zero value otherwise.

### GetCreatedOk

`func (o *PollRssFeed200Response) GetCreatedOk() (*int32, bool)`

GetCreatedOk returns a tuple with the Created field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreated

`func (o *PollRssFeed200Response) SetCreated(v int32)`

SetCreated sets Created field to given value.


### GetSkipped

`func (o *PollRssFeed200Response) GetSkipped() int32`

GetSkipped returns the Skipped field if non-nil, zero value otherwise.

### GetSkippedOk

`func (o *PollRssFeed200Response) GetSkippedOk() (*int32, bool)`

GetSkippedOk returns a tuple with the Skipped field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSkipped

`func (o *PollRssFeed200Response) SetSkipped(v int32)`

SetSkipped sets Skipped field to given value.


### GetData

`func (o *PollRssFeed200Response) GetData() RssFeed`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PollRssFeed200Response) GetDataOk() (*RssFeed, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PollRssFeed200Response) SetData(v RssFeed)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


