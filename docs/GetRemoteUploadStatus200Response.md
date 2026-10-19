# GetRemoteUploadStatus200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | **string** |  | 
**Progress** | **int32** | Percent done. It stays &#x60;0&#x60; until the file is stored and is &#x60;100&#x60; once &#x60;status&#x60; is &#x60;completed&#x60;, so poll on &#x60;status&#x60;. | 
**Media** | Pointer to [**Media**](Media.md) | Present when &#x60;status&#x60; is &#x60;completed&#x60; (absent if the item was deleted before this poll). | [optional] 
**Error** | Pointer to **string** | Why the download failed. Present when &#x60;status&#x60; is &#x60;failed&#x60;. | [optional] 

## Methods

### NewGetRemoteUploadStatus200Response

`func NewGetRemoteUploadStatus200Response(status string, progress int32, ) *GetRemoteUploadStatus200Response`

NewGetRemoteUploadStatus200Response instantiates a new GetRemoteUploadStatus200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetRemoteUploadStatus200ResponseWithDefaults

`func NewGetRemoteUploadStatus200ResponseWithDefaults() *GetRemoteUploadStatus200Response`

NewGetRemoteUploadStatus200ResponseWithDefaults instantiates a new GetRemoteUploadStatus200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *GetRemoteUploadStatus200Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GetRemoteUploadStatus200Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GetRemoteUploadStatus200Response) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetProgress

`func (o *GetRemoteUploadStatus200Response) GetProgress() int32`

GetProgress returns the Progress field if non-nil, zero value otherwise.

### GetProgressOk

`func (o *GetRemoteUploadStatus200Response) GetProgressOk() (*int32, bool)`

GetProgressOk returns a tuple with the Progress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgress

`func (o *GetRemoteUploadStatus200Response) SetProgress(v int32)`

SetProgress sets Progress field to given value.


### GetMedia

`func (o *GetRemoteUploadStatus200Response) GetMedia() Media`

GetMedia returns the Media field if non-nil, zero value otherwise.

### GetMediaOk

`func (o *GetRemoteUploadStatus200Response) GetMediaOk() (*Media, bool)`

GetMediaOk returns a tuple with the Media field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMedia

`func (o *GetRemoteUploadStatus200Response) SetMedia(v Media)`

SetMedia sets Media field to given value.

### HasMedia

`func (o *GetRemoteUploadStatus200Response) HasMedia() bool`

HasMedia returns a boolean if a field has been set.

### GetError

`func (o *GetRemoteUploadStatus200Response) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *GetRemoteUploadStatus200Response) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *GetRemoteUploadStatus200Response) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *GetRemoteUploadStatus200Response) HasError() bool`

HasError returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


