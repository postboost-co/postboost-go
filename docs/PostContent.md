# PostContent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Body** | Pointer to **string** | Post text/caption. | [optional] 
**Url** | Pointer to **string** |  | [optional] 
**Media** | Pointer to **[]int32** | Array of media IDs from the media library. | [optional] 
**VideoThumbs** | Pointer to **[]map[string]interface{}** |  | [optional] 

## Methods

### NewPostContent

`func NewPostContent() *PostContent`

NewPostContent instantiates a new PostContent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostContentWithDefaults

`func NewPostContentWithDefaults() *PostContent`

NewPostContentWithDefaults instantiates a new PostContent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBody

`func (o *PostContent) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *PostContent) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *PostContent) SetBody(v string)`

SetBody sets Body field to given value.

### HasBody

`func (o *PostContent) HasBody() bool`

HasBody returns a boolean if a field has been set.

### GetUrl

`func (o *PostContent) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *PostContent) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *PostContent) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *PostContent) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetMedia

`func (o *PostContent) GetMedia() []int32`

GetMedia returns the Media field if non-nil, zero value otherwise.

### GetMediaOk

`func (o *PostContent) GetMediaOk() (*[]int32, bool)`

GetMediaOk returns a tuple with the Media field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMedia

`func (o *PostContent) SetMedia(v []int32)`

SetMedia sets Media field to given value.

### HasMedia

`func (o *PostContent) HasMedia() bool`

HasMedia returns a boolean if a field has been set.

### GetVideoThumbs

`func (o *PostContent) GetVideoThumbs() []map[string]interface{}`

GetVideoThumbs returns the VideoThumbs field if non-nil, zero value otherwise.

### GetVideoThumbsOk

`func (o *PostContent) GetVideoThumbsOk() (*[]map[string]interface{}, bool)`

GetVideoThumbsOk returns a tuple with the VideoThumbs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVideoThumbs

`func (o *PostContent) SetVideoThumbs(v []map[string]interface{})`

SetVideoThumbs sets VideoThumbs field to given value.

### HasVideoThumbs

`func (o *PostContent) HasVideoThumbs() bool`

HasVideoThumbs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


