# InitiateRemoteUpload200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Uuid** | Pointer to **string** |  | [optional] 
**Name** | Pointer to **string** |  | [optional] 
**MimeType** | Pointer to **string** |  | [optional] 
**Type** | Pointer to **string** |  | [optional] 
**Url** | Pointer to **string** |  | [optional] 
**ThumbUrl** | Pointer to **string** |  | [optional] 
**IsVideo** | Pointer to **bool** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**DownloadId** | Pointer to **string** |  | [optional] 

## Methods

### NewInitiateRemoteUpload200Response

`func NewInitiateRemoteUpload200Response() *InitiateRemoteUpload200Response`

NewInitiateRemoteUpload200Response instantiates a new InitiateRemoteUpload200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInitiateRemoteUpload200ResponseWithDefaults

`func NewInitiateRemoteUpload200ResponseWithDefaults() *InitiateRemoteUpload200Response`

NewInitiateRemoteUpload200ResponseWithDefaults instantiates a new InitiateRemoteUpload200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *InitiateRemoteUpload200Response) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *InitiateRemoteUpload200Response) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *InitiateRemoteUpload200Response) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *InitiateRemoteUpload200Response) HasId() bool`

HasId returns a boolean if a field has been set.

### GetUuid

`func (o *InitiateRemoteUpload200Response) GetUuid() string`

GetUuid returns the Uuid field if non-nil, zero value otherwise.

### GetUuidOk

`func (o *InitiateRemoteUpload200Response) GetUuidOk() (*string, bool)`

GetUuidOk returns a tuple with the Uuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUuid

`func (o *InitiateRemoteUpload200Response) SetUuid(v string)`

SetUuid sets Uuid field to given value.

### HasUuid

`func (o *InitiateRemoteUpload200Response) HasUuid() bool`

HasUuid returns a boolean if a field has been set.

### GetName

`func (o *InitiateRemoteUpload200Response) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *InitiateRemoteUpload200Response) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *InitiateRemoteUpload200Response) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *InitiateRemoteUpload200Response) HasName() bool`

HasName returns a boolean if a field has been set.

### GetMimeType

`func (o *InitiateRemoteUpload200Response) GetMimeType() string`

GetMimeType returns the MimeType field if non-nil, zero value otherwise.

### GetMimeTypeOk

`func (o *InitiateRemoteUpload200Response) GetMimeTypeOk() (*string, bool)`

GetMimeTypeOk returns a tuple with the MimeType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMimeType

`func (o *InitiateRemoteUpload200Response) SetMimeType(v string)`

SetMimeType sets MimeType field to given value.

### HasMimeType

`func (o *InitiateRemoteUpload200Response) HasMimeType() bool`

HasMimeType returns a boolean if a field has been set.

### GetType

`func (o *InitiateRemoteUpload200Response) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *InitiateRemoteUpload200Response) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *InitiateRemoteUpload200Response) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *InitiateRemoteUpload200Response) HasType() bool`

HasType returns a boolean if a field has been set.

### GetUrl

`func (o *InitiateRemoteUpload200Response) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *InitiateRemoteUpload200Response) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *InitiateRemoteUpload200Response) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *InitiateRemoteUpload200Response) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetThumbUrl

`func (o *InitiateRemoteUpload200Response) GetThumbUrl() string`

GetThumbUrl returns the ThumbUrl field if non-nil, zero value otherwise.

### GetThumbUrlOk

`func (o *InitiateRemoteUpload200Response) GetThumbUrlOk() (*string, bool)`

GetThumbUrlOk returns a tuple with the ThumbUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThumbUrl

`func (o *InitiateRemoteUpload200Response) SetThumbUrl(v string)`

SetThumbUrl sets ThumbUrl field to given value.

### HasThumbUrl

`func (o *InitiateRemoteUpload200Response) HasThumbUrl() bool`

HasThumbUrl returns a boolean if a field has been set.

### GetIsVideo

`func (o *InitiateRemoteUpload200Response) GetIsVideo() bool`

GetIsVideo returns the IsVideo field if non-nil, zero value otherwise.

### GetIsVideoOk

`func (o *InitiateRemoteUpload200Response) GetIsVideoOk() (*bool, bool)`

GetIsVideoOk returns a tuple with the IsVideo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsVideo

`func (o *InitiateRemoteUpload200Response) SetIsVideo(v bool)`

SetIsVideo sets IsVideo field to given value.

### HasIsVideo

`func (o *InitiateRemoteUpload200Response) HasIsVideo() bool`

HasIsVideo returns a boolean if a field has been set.

### GetCreatedAt

`func (o *InitiateRemoteUpload200Response) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *InitiateRemoteUpload200Response) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *InitiateRemoteUpload200Response) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *InitiateRemoteUpload200Response) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

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


