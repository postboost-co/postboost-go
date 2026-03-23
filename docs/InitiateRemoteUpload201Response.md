# InitiateRemoteUpload201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**Uuid** | **string** |  | 
**Name** | **string** |  | 
**MimeType** | **string** |  | 
**Type** | **string** |  | 
**Url** | **string** |  | 
**ThumbUrl** | Pointer to **string** |  | [optional] 
**IsVideo** | **bool** |  | 
**CreatedAt** | **time.Time** |  | 
**DownloadId** | Pointer to **string** |  | [optional] 

## Methods

### NewInitiateRemoteUpload201Response

`func NewInitiateRemoteUpload201Response(id int32, uuid string, name string, mimeType string, type_ string, url string, isVideo bool, createdAt time.Time, ) *InitiateRemoteUpload201Response`

NewInitiateRemoteUpload201Response instantiates a new InitiateRemoteUpload201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInitiateRemoteUpload201ResponseWithDefaults

`func NewInitiateRemoteUpload201ResponseWithDefaults() *InitiateRemoteUpload201Response`

NewInitiateRemoteUpload201ResponseWithDefaults instantiates a new InitiateRemoteUpload201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InitiateRemoteUpload201Response) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InitiateRemoteUpload201Response) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InitiateRemoteUpload201Response) SetId(v int32)`

SetId sets Id field to given value.


### GetUuid

`func (o *InitiateRemoteUpload201Response) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *InitiateRemoteUpload201Response) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *InitiateRemoteUpload201Response) SetUuid(v string)`

SetUuid sets Uuid field to given value.


### GetName

`func (o *InitiateRemoteUpload201Response) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *InitiateRemoteUpload201Response) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *InitiateRemoteUpload201Response) SetName(v string)`

SetName sets Name field to given value.


### GetMimeType

`func (o *InitiateRemoteUpload201Response) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *InitiateRemoteUpload201Response) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *InitiateRemoteUpload201Response) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.


### GetType

`func (o *InitiateRemoteUpload201Response) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *InitiateRemoteUpload201Response) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *InitiateRemoteUpload201Response) SetType(v string)`

SetType sets Type field to given value.


### GetUrl

`func (o *InitiateRemoteUpload201Response) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *InitiateRemoteUpload201Response) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *InitiateRemoteUpload201Response) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetThumbUrl

`func (o *InitiateRemoteUpload201Response) GetThumbUrl() string`

GetThumbUrl returns the ThumbUrl field if non-nil, zero value otherwise.

### GetThumbUrlOk

`func (o *InitiateRemoteUpload201Response) GetThumbUrlOk() (*string, bool)`

GetThumbUrlOk returns a tuple with the ThumbUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbUrl

`func (o *InitiateRemoteUpload201Response) SetThumbUrl(v string)`

SetThumbUrl sets ThumbUrl field to given value.

### HasThumbUrl

`func (o *InitiateRemoteUpload201Response) HasThumbUrl() bool`

HasThumbUrl returns a boolean if a field has been set.

### GetIsVideo

`func (o *InitiateRemoteUpload201Response) GetIsVideo() bool`

GetIsVideo returns the IsVideo field if non-nil, zero value otherwise.

### GetIsVideoOk

`func (o *InitiateRemoteUpload201Response) GetIsVideoOk() (*bool, bool)`

GetIsVideoOk returns a tuple with the IsVideo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsVideo

`func (o *InitiateRemoteUpload201Response) SetIsVideo(v bool)`

SetIsVideo sets IsVideo field to given value.


### GetCreatedAt

`func (o *InitiateRemoteUpload201Response) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *InitiateRemoteUpload201Response) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *InitiateRemoteUpload201Response) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetDownloadId

`func (o *InitiateRemoteUpload201Response) GetDownloadId() string`

GetDownloadId returns the DownloadId field if non-nil, zero value otherwise.

### GetDownloadIdOk

`func (o *InitiateRemoteUpload201Response) GetDownloadIdOk() (*string, bool)`

GetDownloadIdOk returns a tuple with the DownloadId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDownloadId

`func (o *InitiateRemoteUpload201Response) SetDownloadId(v string)`

SetDownloadId sets DownloadId field to given value.

### HasDownloadId

`func (o *InitiateRemoteUpload201Response) HasDownloadId() bool`

HasDownloadId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


