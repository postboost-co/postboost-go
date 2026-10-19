# FreeToolGenerateAltTextRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ImageBase64** | Pointer to **string** | The image itself, base64-encoded without a &#x60;data:&#x60; prefix: JPEG, PNG, WebP or GIF (first frame), up to 5 MB. On the API you can upload the file as &#x60;image&#x60; in a multipart/form-data body instead. A request to the MCP server at /mcp/tools may be at most 1.5 MB, so send larger images as &#x60;image_url&#x60; there. Send this or &#x60;image_url&#x60;. | [optional] 
**ImageUrl** | Pointer to **string** | A public https URL of the image, up to 5 MB. Fetched once and never stored; each fetch also counts against the daily limit of the tools that load a URL. Send this or &#x60;image_base64&#x60;. | [optional] 
**Context** | Pointer to **string** | Optional: what the post is about, so the text describes what matters for it. | [optional] 
**Length** | Pointer to **string** | short (up to 125 characters) or detailed (up to 250). | [optional] [default to "short"]
**Workspace** | Pointer to **string** | UUID of the workspace whose AI credits pay for the call. Default: your active workspace (a scoped API key: its own workspace). | [optional] 

## Methods

### NewFreeToolGenerateAltTextRequest

`func NewFreeToolGenerateAltTextRequest() *FreeToolGenerateAltTextRequest`

NewFreeToolGenerateAltTextRequest instantiates a new FreeToolGenerateAltTextRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateAltTextRequestWithDefaults

`func NewFreeToolGenerateAltTextRequestWithDefaults() *FreeToolGenerateAltTextRequest`

NewFreeToolGenerateAltTextRequestWithDefaults instantiates a new FreeToolGenerateAltTextRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImageBase64

`func (o *FreeToolGenerateAltTextRequest) GetImageBase64() string`

GetImageBase64 returns the ImageBase64 field if non-nil, zero value otherwise.

### GetImageBase64Ok

`func (o *FreeToolGenerateAltTextRequest) GetImageBase64Ok() (*string, bool)`

GetImageBase64Ok returns a tuple with the ImageBase64 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageBase64

`func (o *FreeToolGenerateAltTextRequest) SetImageBase64(v string)`

SetImageBase64 sets ImageBase64 field to given value.

### HasImageBase64

`func (o *FreeToolGenerateAltTextRequest) HasImageBase64() bool`

HasImageBase64 returns a boolean if a field has been set.

### GetImageUrl

`func (o *FreeToolGenerateAltTextRequest) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *FreeToolGenerateAltTextRequest) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *FreeToolGenerateAltTextRequest) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *FreeToolGenerateAltTextRequest) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### GetContext

`func (o *FreeToolGenerateAltTextRequest) GetContext() string`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *FreeToolGenerateAltTextRequest) GetContextOk() (*string, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *FreeToolGenerateAltTextRequest) SetContext(v string)`

SetContext sets Context field to given value.

### HasContext

`func (o *FreeToolGenerateAltTextRequest) HasContext() bool`

HasContext returns a boolean if a field has been set.

### GetLength

`func (o *FreeToolGenerateAltTextRequest) GetLength() string`

GetLength returns the Length field if non-nil, zero value otherwise.

### GetLengthOk

`func (o *FreeToolGenerateAltTextRequest) GetLengthOk() (*string, bool)`

GetLengthOk returns a tuple with the Length field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLength

`func (o *FreeToolGenerateAltTextRequest) SetLength(v string)`

SetLength sets Length field to given value.

### HasLength

`func (o *FreeToolGenerateAltTextRequest) HasLength() bool`

HasLength returns a boolean if a field has been set.

### GetWorkspace

`func (o *FreeToolGenerateAltTextRequest) GetWorkspace() string`

GetWorkspace returns the Workspace field if non-nil, zero value otherwise.

### GetWorkspaceOk

`func (o *FreeToolGenerateAltTextRequest) GetWorkspaceOk() (*string, bool)`

GetWorkspaceOk returns a tuple with the Workspace field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkspace

`func (o *FreeToolGenerateAltTextRequest) SetWorkspace(v string)`

SetWorkspace sets Workspace field to given value.

### HasWorkspace

`func (o *FreeToolGenerateAltTextRequest) HasWorkspace() bool`

HasWorkspace returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


