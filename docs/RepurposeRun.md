# RepurposeRun

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RunId** | **int32** |  | 
**Status** | **string** |  | 
**Error** | **NullableString** | Why the run failed. | 
**PostUuid** | **NullableString** | The draft post, once created. | 
**CreditsUsed** | **int32** |  | 
**Result** | [**NullableRepurposeResult**](RepurposeResult.md) |  | 

## Methods

### NewRepurposeRun

`func NewRepurposeRun(runId int32, status string, error_ NullableString, postUuid NullableString, creditsUsed int32, result NullableRepurposeResult, ) *RepurposeRun`

NewRepurposeRun instantiates a new RepurposeRun object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRepurposeRunWithDefaults

`func NewRepurposeRunWithDefaults() *RepurposeRun`

NewRepurposeRunWithDefaults instantiates a new RepurposeRun object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRunId

`func (o *RepurposeRun) GetRunId() int32`

GetRunId returns the RunId field if non-nil, zero value otherwise.

### GetRunIdOk

`func (o *RepurposeRun) GetRunIdOk() (*int32, bool)`

GetRunIdOk returns a tuple with the RunId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRunId

`func (o *RepurposeRun) SetRunId(v int32)`

SetRunId sets RunId field to given value.


### GetStatus

`func (o *RepurposeRun) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RepurposeRun) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RepurposeRun) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetError

`func (o *RepurposeRun) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *RepurposeRun) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *RepurposeRun) SetError(v string)`

SetError sets Error field to given value.


### SetErrorNil

`func (o *RepurposeRun) SetErrorNil(b bool)`

 SetErrorNil sets the value for Error to be an explicit nil

### UnsetError
`func (o *RepurposeRun) UnsetError()`

UnsetError ensures that no value is present for Error, not even an explicit nil
### GetPostUuid

`func (o *RepurposeRun) GetPostUuid() string`

GetPostUuid returns the PostUuid field if non-nil, zero value otherwise.

### GetPostUuidOk

`func (o *RepurposeRun) GetPostUuidOk() (*string, bool)`

GetPostUuidOk returns a tuple with the PostUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostUuid

`func (o *RepurposeRun) SetPostUuid(v string)`

SetPostUuid sets PostUuid field to given value.


### SetPostUuidNil

`func (o *RepurposeRun) SetPostUuidNil(b bool)`

 SetPostUuidNil sets the value for PostUuid to be an explicit nil

### UnsetPostUuid
`func (o *RepurposeRun) UnsetPostUuid()`

UnsetPostUuid ensures that no value is present for PostUuid, not even an explicit nil
### GetCreditsUsed

`func (o *RepurposeRun) GetCreditsUsed() int32`

GetCreditsUsed returns the CreditsUsed field if non-nil, zero value otherwise.

### GetCreditsUsedOk

`func (o *RepurposeRun) GetCreditsUsedOk() (*int32, bool)`

GetCreditsUsedOk returns a tuple with the CreditsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsUsed

`func (o *RepurposeRun) SetCreditsUsed(v int32)`

SetCreditsUsed sets CreditsUsed field to given value.


### GetResult

`func (o *RepurposeRun) GetResult() RepurposeResult`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *RepurposeRun) GetResultOk() (*RepurposeResult, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *RepurposeRun) SetResult(v RepurposeResult)`

SetResult sets Result field to given value.


### SetResultNil

`func (o *RepurposeRun) SetResultNil(b bool)`

 SetResultNil sets the value for Result to be an explicit nil

### UnsetResult
`func (o *RepurposeRun) UnsetResult()`

UnsetResult ensures that no value is present for Result, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


