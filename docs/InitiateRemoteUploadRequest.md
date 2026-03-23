# InitiateRemoteUploadRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | URL of the remote file to download. | 
**AltText** | Pointer to **string** |  | [optional] 

## Methods

### NewInitiateRemoteUploadRequest

`func NewInitiateRemoteUploadRequest(url string, ) *InitiateRemoteUploadRequest`

NewInitiateRemoteUploadRequest instantiates a new InitiateRemoteUploadRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInitiateRemoteUploadRequestWithDefaults

`func NewInitiateRemoteUploadRequestWithDefaults() *InitiateRemoteUploadRequest`

NewInitiateRemoteUploadRequestWithDefaults instantiates a new InitiateRemoteUploadRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *InitiateRemoteUploadRequest) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *InitiateRemoteUploadRequest) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *InitiateRemoteUploadRequest) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetAltText

`func (o *InitiateRemoteUploadRequest) GetAltText() string`

GetAltText returns the AltText field if non-nil, zero value otherwise.

### GetAltTextOk

`func (o *InitiateRemoteUploadRequest) GetAltTextOk() (*string, bool)`

GetAltTextOk returns a tuple with the AltText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAltText

`func (o *InitiateRemoteUploadRequest) SetAltText(v string)`

SetAltText sets AltText field to given value.

### HasAltText

`func (o *InitiateRemoteUploadRequest) HasAltText() bool`

HasAltText returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


