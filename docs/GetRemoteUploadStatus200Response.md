# GetRemoteUploadStatus200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **string** |  | [optional] 
**Media** | Pointer to [**Media**](Media.md) | Present when status is complete. | [optional] 

## Methods

### NewGetRemoteUploadStatus200Response

`func NewGetRemoteUploadStatus200Response() *GetRemoteUploadStatus200Response`

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

### HasStatus

`func (o *GetRemoteUploadStatus200Response) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

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


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


