# InitiateRemoteUpload200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | **string** | &#x60;completed&#x60; and &#x60;failed&#x60; are final; &#x60;pending&#x60; means the file downloads in the background. | 
**Media** | Pointer to [**Media**](Media.md) | Present when &#x60;status&#x60; is &#x60;completed&#x60;. This copy has no &#x60;size&#x60;; &#x60;getMedia&#x60; returns it. | [optional] 
**Error** | Pointer to **string** | Why the download failed. Present when &#x60;status&#x60; is &#x60;failed&#x60;. | [optional] 
**DownloadId** | Pointer to **string** | Present when &#x60;status&#x60; is &#x60;pending&#x60;. Pass it to &#x60;getRemoteUploadStatus&#x60;. | [optional] 

## Methods

### NewInitiateRemoteUpload200Response

`func NewInitiateRemoteUpload200Response(status string, ) *InitiateRemoteUpload200Response`

NewInitiateRemoteUpload200Response instantiates a new InitiateRemoteUpload200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInitiateRemoteUpload200ResponseWithDefaults

`func NewInitiateRemoteUpload200ResponseWithDefaults() *InitiateRemoteUpload200Response`

NewInitiateRemoteUpload200ResponseWithDefaults instantiates a new InitiateRemoteUpload200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *InitiateRemoteUpload200Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *InitiateRemoteUpload200Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *InitiateRemoteUpload200Response) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetMedia

`func (o *InitiateRemoteUpload200Response) GetMedia() Media`

GetMedia returns the Media field if non-nil, zero value otherwise.

### GetMediaOk

`func (o *InitiateRemoteUpload200Response) GetMediaOk() (*Media, bool)`

GetMediaOk returns a tuple with the Media field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMedia

`func (o *InitiateRemoteUpload200Response) SetMedia(v Media)`

SetMedia sets Media field to given value.

### HasMedia

`func (o *InitiateRemoteUpload200Response) HasMedia() bool`

HasMedia returns a boolean if a field has been set.

### GetError

`func (o *InitiateRemoteUpload200Response) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *InitiateRemoteUpload200Response) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *InitiateRemoteUpload200Response) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *InitiateRemoteUpload200Response) HasError() bool`

HasError returns a boolean if a field has been set.

### GetDownloadId

`func (o *InitiateRemoteUpload200Response) GetDownloadId() string`

GetDownloadId returns the DownloadId field if non-nil, zero value otherwise.

### GetDownloadIdOk

`func (o *InitiateRemoteUpload200Response) GetDownloadIdOk() (*string, bool)`

GetDownloadIdOk returns a tuple with the DownloadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownloadId

`func (o *InitiateRemoteUpload200Response) SetDownloadId(v string)`

SetDownloadId sets DownloadId field to given value.

### HasDownloadId

`func (o *InitiateRemoteUpload200Response) HasDownloadId() bool`

HasDownloadId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


