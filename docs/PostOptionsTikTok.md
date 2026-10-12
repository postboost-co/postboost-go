# PostOptionsTikTok

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**PrivacyLevel** | Pointer to **map[string]string** |  | [optional] 
**IsAigc** | Pointer to **map[string]bool** | TikTok&#39;s \&quot;AI-generated content\&quot; label. | [optional] 
**AllowComments** | Pointer to **map[string]bool** |  | [optional] 
**AllowDuet** | Pointer to **map[string]bool** |  | [optional] 
**AllowStitch** | Pointer to **map[string]bool** |  | [optional] 
**AutoAddMusic** | Pointer to **map[string]bool** |  | [optional] 
**ContentDisclosure** | Pointer to **map[string]bool** | Discloses branded or promotional content; then set &#x60;brand_organic_toggle&#x60; and/or &#x60;brand_content_toggle&#x60;. | [optional] 
**BrandOrganicToggle** | Pointer to **map[string]bool** |  | [optional] 
**BrandContentToggle** | Pointer to **map[string]bool** |  | [optional] 

## Methods

### NewPostOptionsTikTok

`func NewPostOptionsTikTok() *PostOptionsTikTok`

NewPostOptionsTikTok instantiates a new PostOptionsTikTok object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostOptionsTikTokWithDefaults

`func NewPostOptionsTikTokWithDefaults() *PostOptionsTikTok`

NewPostOptionsTikTokWithDefaults instantiates a new PostOptionsTikTok object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPrivacyLevel

`func (o *PostOptionsTikTok) GetPrivacyLevel() map[string]string`

GetPrivacyLevel returns the PrivacyLevel field if non-nil, zero value otherwise.

### GetPrivacyLevelOk

`func (o *PostOptionsTikTok) GetPrivacyLevelOk() (*map[string]string, bool)`

GetPrivacyLevelOk returns a tuple with the PrivacyLevel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivacyLevel

`func (o *PostOptionsTikTok) SetPrivacyLevel(v map[string]string)`

SetPrivacyLevel sets PrivacyLevel field to given value.

### HasPrivacyLevel

`func (o *PostOptionsTikTok) HasPrivacyLevel() bool`

HasPrivacyLevel returns a boolean if a field has been set.

### GetIsAigc

`func (o *PostOptionsTikTok) GetIsAigc() map[string]bool`

GetIsAigc returns the IsAigc field if non-nil, zero value otherwise.

### GetIsAigcOk

`func (o *PostOptionsTikTok) GetIsAigcOk() (*map[string]bool, bool)`

GetIsAigcOk returns a tuple with the IsAigc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAigc

`func (o *PostOptionsTikTok) SetIsAigc(v map[string]bool)`

SetIsAigc sets IsAigc field to given value.

### HasIsAigc

`func (o *PostOptionsTikTok) HasIsAigc() bool`

HasIsAigc returns a boolean if a field has been set.

### GetAllowComments

`func (o *PostOptionsTikTok) GetAllowComments() map[string]bool`

GetAllowComments returns the AllowComments field if non-nil, zero value otherwise.

### GetAllowCommentsOk

`func (o *PostOptionsTikTok) GetAllowCommentsOk() (*map[string]bool, bool)`

GetAllowCommentsOk returns a tuple with the AllowComments field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowComments

`func (o *PostOptionsTikTok) SetAllowComments(v map[string]bool)`

SetAllowComments sets AllowComments field to given value.

### HasAllowComments

`func (o *PostOptionsTikTok) HasAllowComments() bool`

HasAllowComments returns a boolean if a field has been set.

### GetAllowDuet

`func (o *PostOptionsTikTok) GetAllowDuet() map[string]bool`

GetAllowDuet returns the AllowDuet field if non-nil, zero value otherwise.

### GetAllowDuetOk

`func (o *PostOptionsTikTok) GetAllowDuetOk() (*map[string]bool, bool)`

GetAllowDuetOk returns a tuple with the AllowDuet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowDuet

`func (o *PostOptionsTikTok) SetAllowDuet(v map[string]bool)`

SetAllowDuet sets AllowDuet field to given value.

### HasAllowDuet

`func (o *PostOptionsTikTok) HasAllowDuet() bool`

HasAllowDuet returns a boolean if a field has been set.

### GetAllowStitch

`func (o *PostOptionsTikTok) GetAllowStitch() map[string]bool`

GetAllowStitch returns the AllowStitch field if non-nil, zero value otherwise.

### GetAllowStitchOk

`func (o *PostOptionsTikTok) GetAllowStitchOk() (*map[string]bool, bool)`

GetAllowStitchOk returns a tuple with the AllowStitch field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowStitch

`func (o *PostOptionsTikTok) SetAllowStitch(v map[string]bool)`

SetAllowStitch sets AllowStitch field to given value.

### HasAllowStitch

`func (o *PostOptionsTikTok) HasAllowStitch() bool`

HasAllowStitch returns a boolean if a field has been set.

### GetAutoAddMusic

`func (o *PostOptionsTikTok) GetAutoAddMusic() map[string]bool`

GetAutoAddMusic returns the AutoAddMusic field if non-nil, zero value otherwise.

### GetAutoAddMusicOk

`func (o *PostOptionsTikTok) GetAutoAddMusicOk() (*map[string]bool, bool)`

GetAutoAddMusicOk returns a tuple with the AutoAddMusic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAutoAddMusic

`func (o *PostOptionsTikTok) SetAutoAddMusic(v map[string]bool)`

SetAutoAddMusic sets AutoAddMusic field to given value.

### HasAutoAddMusic

`func (o *PostOptionsTikTok) HasAutoAddMusic() bool`

HasAutoAddMusic returns a boolean if a field has been set.

### GetContentDisclosure

`func (o *PostOptionsTikTok) GetContentDisclosure() map[string]bool`

GetContentDisclosure returns the ContentDisclosure field if non-nil, zero value otherwise.

### GetContentDisclosureOk

`func (o *PostOptionsTikTok) GetContentDisclosureOk() (*map[string]bool, bool)`

GetContentDisclosureOk returns a tuple with the ContentDisclosure field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentDisclosure

`func (o *PostOptionsTikTok) SetContentDisclosure(v map[string]bool)`

SetContentDisclosure sets ContentDisclosure field to given value.

### HasContentDisclosure

`func (o *PostOptionsTikTok) HasContentDisclosure() bool`

HasContentDisclosure returns a boolean if a field has been set.

### GetBrandOrganicToggle

`func (o *PostOptionsTikTok) GetBrandOrganicToggle() map[string]bool`

GetBrandOrganicToggle returns the BrandOrganicToggle field if non-nil, zero value otherwise.

### GetBrandOrganicToggleOk

`func (o *PostOptionsTikTok) GetBrandOrganicToggleOk() (*map[string]bool, bool)`

GetBrandOrganicToggleOk returns a tuple with the BrandOrganicToggle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandOrganicToggle

`func (o *PostOptionsTikTok) SetBrandOrganicToggle(v map[string]bool)`

SetBrandOrganicToggle sets BrandOrganicToggle field to given value.

### HasBrandOrganicToggle

`func (o *PostOptionsTikTok) HasBrandOrganicToggle() bool`

HasBrandOrganicToggle returns a boolean if a field has been set.

### GetBrandContentToggle

`func (o *PostOptionsTikTok) GetBrandContentToggle() map[string]bool`

GetBrandContentToggle returns the BrandContentToggle field if non-nil, zero value otherwise.

### GetBrandContentToggleOk

`func (o *PostOptionsTikTok) GetBrandContentToggleOk() (*map[string]bool, bool)`

GetBrandContentToggleOk returns a tuple with the BrandContentToggle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandContentToggle

`func (o *PostOptionsTikTok) SetBrandContentToggle(v map[string]bool)`

SetBrandContentToggle sets BrandContentToggle field to given value.

### HasBrandContentToggle

`func (o *PostOptionsTikTok) HasBrandContentToggle() bool`

HasBrandContentToggle returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


