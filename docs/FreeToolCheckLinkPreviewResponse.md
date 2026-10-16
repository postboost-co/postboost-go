# FreeToolCheckLinkPreviewResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**FinalUrl** | Pointer to **string** | The URL after redirects. | [optional] 
**Status** | Pointer to **int32** | HTTP status of the final response. | [optional] 
**Redirects** | Pointer to [**[]FreeToolCheckLinkPreviewResponseRedirectsInner**](FreeToolCheckLinkPreviewResponseRedirectsInner.md) |  | [optional] 
**ContentType** | Pointer to **NullableString** |  | [optional] 
**Tags** | Pointer to [**FreeToolCheckLinkPreviewResponseTags**](FreeToolCheckLinkPreviewResponseTags.md) |  | [optional] 
**Image** | Pointer to [**FreeToolCheckLinkPreviewResponseImage**](FreeToolCheckLinkPreviewResponseImage.md) |  | [optional] 
**Previews** | Pointer to [**map[string]FreeToolCheckLinkPreviewResponsePreviewsValue**](FreeToolCheckLinkPreviewResponsePreviewsValue.md) | The card each network would show. | [optional] 
**Warnings** | Pointer to **[]string** |  | [optional] 

## Methods

### NewFreeToolCheckLinkPreviewResponse

`func NewFreeToolCheckLinkPreviewResponse() *FreeToolCheckLinkPreviewResponse`

NewFreeToolCheckLinkPreviewResponse instantiates a new FreeToolCheckLinkPreviewResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCheckLinkPreviewResponseWithDefaults

`func NewFreeToolCheckLinkPreviewResponseWithDefaults() *FreeToolCheckLinkPreviewResponse`

NewFreeToolCheckLinkPreviewResponseWithDefaults instantiates a new FreeToolCheckLinkPreviewResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFinalUrl

`func (o *FreeToolCheckLinkPreviewResponse) GetFinalUrl() string`

GetFinalUrl returns the FinalUrl field if non-nil, zero value otherwise.

### GetFinalUrlOk

`func (o *FreeToolCheckLinkPreviewResponse) GetFinalUrlOk() (*string, bool)`

GetFinalUrlOk returns a tuple with the FinalUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinalUrl

`func (o *FreeToolCheckLinkPreviewResponse) SetFinalUrl(v string)`

SetFinalUrl sets FinalUrl field to given value.

### HasFinalUrl

`func (o *FreeToolCheckLinkPreviewResponse) HasFinalUrl() bool`

HasFinalUrl returns a boolean if a field has been set.

### GetStatus

`func (o *FreeToolCheckLinkPreviewResponse) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *FreeToolCheckLinkPreviewResponse) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *FreeToolCheckLinkPreviewResponse) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *FreeToolCheckLinkPreviewResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetRedirects

`func (o *FreeToolCheckLinkPreviewResponse) GetRedirects() []FreeToolCheckLinkPreviewResponseRedirectsInner`

GetRedirects returns the Redirects field if non-nil, zero value otherwise.

### GetRedirectsOk

`func (o *FreeToolCheckLinkPreviewResponse) GetRedirectsOk() (*[]FreeToolCheckLinkPreviewResponseRedirectsInner, bool)`

GetRedirectsOk returns a tuple with the Redirects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRedirects

`func (o *FreeToolCheckLinkPreviewResponse) SetRedirects(v []FreeToolCheckLinkPreviewResponseRedirectsInner)`

SetRedirects sets Redirects field to given value.

### HasRedirects

`func (o *FreeToolCheckLinkPreviewResponse) HasRedirects() bool`

HasRedirects returns a boolean if a field has been set.

### GetContentType

`func (o *FreeToolCheckLinkPreviewResponse) GetContentType() string`

GetContentType returns the ContentType field if non-nil, zero value otherwise.

### GetContentTypeOk

`func (o *FreeToolCheckLinkPreviewResponse) GetContentTypeOk() (*string, bool)`

GetContentTypeOk returns a tuple with the ContentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentType

`func (o *FreeToolCheckLinkPreviewResponse) SetContentType(v string)`

SetContentType sets ContentType field to given value.

### HasContentType

`func (o *FreeToolCheckLinkPreviewResponse) HasContentType() bool`

HasContentType returns a boolean if a field has been set.

### SetContentTypeNil

`func (o *FreeToolCheckLinkPreviewResponse) SetContentTypeNil(b bool)`

 SetContentTypeNil sets the value for ContentType to be an explicit nil

### UnsetContentType
`func (o *FreeToolCheckLinkPreviewResponse) UnsetContentType()`

UnsetContentType ensures that no value is present for ContentType, not even an explicit nil
### GetTags

`func (o *FreeToolCheckLinkPreviewResponse) GetTags() FreeToolCheckLinkPreviewResponseTags`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *FreeToolCheckLinkPreviewResponse) GetTagsOk() (*FreeToolCheckLinkPreviewResponseTags, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *FreeToolCheckLinkPreviewResponse) SetTags(v FreeToolCheckLinkPreviewResponseTags)`

SetTags sets Tags field to given value.

### HasTags

`func (o *FreeToolCheckLinkPreviewResponse) HasTags() bool`

HasTags returns a boolean if a field has been set.

### GetImage

`func (o *FreeToolCheckLinkPreviewResponse) GetImage() FreeToolCheckLinkPreviewResponseImage`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *FreeToolCheckLinkPreviewResponse) GetImageOk() (*FreeToolCheckLinkPreviewResponseImage, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *FreeToolCheckLinkPreviewResponse) SetImage(v FreeToolCheckLinkPreviewResponseImage)`

SetImage sets Image field to given value.

### HasImage

`func (o *FreeToolCheckLinkPreviewResponse) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetPreviews

`func (o *FreeToolCheckLinkPreviewResponse) GetPreviews() map[string]FreeToolCheckLinkPreviewResponsePreviewsValue`

GetPreviews returns the Previews field if non-nil, zero value otherwise.

### GetPreviewsOk

`func (o *FreeToolCheckLinkPreviewResponse) GetPreviewsOk() (*map[string]FreeToolCheckLinkPreviewResponsePreviewsValue, bool)`

GetPreviewsOk returns a tuple with the Previews field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreviews

`func (o *FreeToolCheckLinkPreviewResponse) SetPreviews(v map[string]FreeToolCheckLinkPreviewResponsePreviewsValue)`

SetPreviews sets Previews field to given value.

### HasPreviews

`func (o *FreeToolCheckLinkPreviewResponse) HasPreviews() bool`

HasPreviews returns a boolean if a field has been set.

### GetWarnings

`func (o *FreeToolCheckLinkPreviewResponse) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *FreeToolCheckLinkPreviewResponse) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *FreeToolCheckLinkPreviewResponse) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *FreeToolCheckLinkPreviewResponse) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


