# FreeToolScoreSocialAuditRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TargetPostsPerWeek** | Pointer to **int32** | Your own posting target per network and week, used in the frequency question. | [optional] [default to 3]
**Instagram** | Pointer to [**FreeToolScoreSocialAuditRequestInstagram**](FreeToolScoreSocialAuditRequestInstagram.md) |  | [optional] 
**Facebook** | Pointer to [**FreeToolScoreSocialAuditRequestInstagram**](FreeToolScoreSocialAuditRequestInstagram.md) |  | [optional] 
**Linkedin** | Pointer to [**FreeToolScoreSocialAuditRequestInstagram**](FreeToolScoreSocialAuditRequestInstagram.md) |  | [optional] 
**X** | Pointer to [**FreeToolScoreSocialAuditRequestInstagram**](FreeToolScoreSocialAuditRequestInstagram.md) |  | [optional] 
**Tiktok** | Pointer to [**FreeToolScoreSocialAuditRequestInstagram**](FreeToolScoreSocialAuditRequestInstagram.md) |  | [optional] 
**Youtube** | Pointer to [**FreeToolScoreSocialAuditRequestInstagram**](FreeToolScoreSocialAuditRequestInstagram.md) |  | [optional] 
**Pinterest** | Pointer to [**FreeToolScoreSocialAuditRequestInstagram**](FreeToolScoreSocialAuditRequestInstagram.md) |  | [optional] 
**Threads** | Pointer to [**FreeToolScoreSocialAuditRequestInstagram**](FreeToolScoreSocialAuditRequestInstagram.md) |  | [optional] 
**Bluesky** | Pointer to [**FreeToolScoreSocialAuditRequestInstagram**](FreeToolScoreSocialAuditRequestInstagram.md) |  | [optional] 
**Mastodon** | Pointer to [**FreeToolScoreSocialAuditRequestInstagram**](FreeToolScoreSocialAuditRequestInstagram.md) |  | [optional] 

## Methods

### NewFreeToolScoreSocialAuditRequest

`func NewFreeToolScoreSocialAuditRequest() *FreeToolScoreSocialAuditRequest`

NewFreeToolScoreSocialAuditRequest instantiates a new FreeToolScoreSocialAuditRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolScoreSocialAuditRequestWithDefaults

`func NewFreeToolScoreSocialAuditRequestWithDefaults() *FreeToolScoreSocialAuditRequest`

NewFreeToolScoreSocialAuditRequestWithDefaults instantiates a new FreeToolScoreSocialAuditRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTargetPostsPerWeek

`func (o *FreeToolScoreSocialAuditRequest) GetTargetPostsPerWeek() int32`

GetTargetPostsPerWeek returns the TargetPostsPerWeek field if non-nil, zero value otherwise.

### GetTargetPostsPerWeekOk

`func (o *FreeToolScoreSocialAuditRequest) GetTargetPostsPerWeekOk() (*int32, bool)`

GetTargetPostsPerWeekOk returns a tuple with the TargetPostsPerWeek field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTargetPostsPerWeek

`func (o *FreeToolScoreSocialAuditRequest) SetTargetPostsPerWeek(v int32)`

SetTargetPostsPerWeek sets TargetPostsPerWeek field to given value.

### HasTargetPostsPerWeek

`func (o *FreeToolScoreSocialAuditRequest) HasTargetPostsPerWeek() bool`

HasTargetPostsPerWeek returns a boolean if a field has been set.

### GetInstagram

`func (o *FreeToolScoreSocialAuditRequest) GetInstagram() FreeToolScoreSocialAuditRequestInstagram`

GetInstagram returns the Instagram field if non-nil, zero value otherwise.

### GetInstagramOk

`func (o *FreeToolScoreSocialAuditRequest) GetInstagramOk() (*FreeToolScoreSocialAuditRequestInstagram, bool)`

GetInstagramOk returns a tuple with the Instagram field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstagram

`func (o *FreeToolScoreSocialAuditRequest) SetInstagram(v FreeToolScoreSocialAuditRequestInstagram)`

SetInstagram sets Instagram field to given value.

### HasInstagram

`func (o *FreeToolScoreSocialAuditRequest) HasInstagram() bool`

HasInstagram returns a boolean if a field has been set.

### GetFacebook

`func (o *FreeToolScoreSocialAuditRequest) GetFacebook() FreeToolScoreSocialAuditRequestInstagram`

GetFacebook returns the Facebook field if non-nil, zero value otherwise.

### GetFacebookOk

`func (o *FreeToolScoreSocialAuditRequest) GetFacebookOk() (*FreeToolScoreSocialAuditRequestInstagram, bool)`

GetFacebookOk returns a tuple with the Facebook field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFacebook

`func (o *FreeToolScoreSocialAuditRequest) SetFacebook(v FreeToolScoreSocialAuditRequestInstagram)`

SetFacebook sets Facebook field to given value.

### HasFacebook

`func (o *FreeToolScoreSocialAuditRequest) HasFacebook() bool`

HasFacebook returns a boolean if a field has been set.

### GetLinkedin

`func (o *FreeToolScoreSocialAuditRequest) GetLinkedin() FreeToolScoreSocialAuditRequestInstagram`

GetLinkedin returns the Linkedin field if non-nil, zero value otherwise.

### GetLinkedinOk

`func (o *FreeToolScoreSocialAuditRequest) GetLinkedinOk() (*FreeToolScoreSocialAuditRequestInstagram, bool)`

GetLinkedinOk returns a tuple with the Linkedin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkedin

`func (o *FreeToolScoreSocialAuditRequest) SetLinkedin(v FreeToolScoreSocialAuditRequestInstagram)`

SetLinkedin sets Linkedin field to given value.

### HasLinkedin

`func (o *FreeToolScoreSocialAuditRequest) HasLinkedin() bool`

HasLinkedin returns a boolean if a field has been set.

### GetX

`func (o *FreeToolScoreSocialAuditRequest) GetX() FreeToolScoreSocialAuditRequestInstagram`

GetX returns the X field if non-nil, zero value otherwise.

### GetXOk

`func (o *FreeToolScoreSocialAuditRequest) GetXOk() (*FreeToolScoreSocialAuditRequestInstagram, bool)`

GetXOk returns a tuple with the X field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX

`func (o *FreeToolScoreSocialAuditRequest) SetX(v FreeToolScoreSocialAuditRequestInstagram)`

SetX sets X field to given value.

### HasX

`func (o *FreeToolScoreSocialAuditRequest) HasX() bool`

HasX returns a boolean if a field has been set.

### GetTiktok

`func (o *FreeToolScoreSocialAuditRequest) GetTiktok() FreeToolScoreSocialAuditRequestInstagram`

GetTiktok returns the Tiktok field if non-nil, zero value otherwise.

### GetTiktokOk

`func (o *FreeToolScoreSocialAuditRequest) GetTiktokOk() (*FreeToolScoreSocialAuditRequestInstagram, bool)`

GetTiktokOk returns a tuple with the Tiktok field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTiktok

`func (o *FreeToolScoreSocialAuditRequest) SetTiktok(v FreeToolScoreSocialAuditRequestInstagram)`

SetTiktok sets Tiktok field to given value.

### HasTiktok

`func (o *FreeToolScoreSocialAuditRequest) HasTiktok() bool`

HasTiktok returns a boolean if a field has been set.

### GetYoutube

`func (o *FreeToolScoreSocialAuditRequest) GetYoutube() FreeToolScoreSocialAuditRequestInstagram`

GetYoutube returns the Youtube field if non-nil, zero value otherwise.

### GetYoutubeOk

`func (o *FreeToolScoreSocialAuditRequest) GetYoutubeOk() (*FreeToolScoreSocialAuditRequestInstagram, bool)`

GetYoutubeOk returns a tuple with the Youtube field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYoutube

`func (o *FreeToolScoreSocialAuditRequest) SetYoutube(v FreeToolScoreSocialAuditRequestInstagram)`

SetYoutube sets Youtube field to given value.

### HasYoutube

`func (o *FreeToolScoreSocialAuditRequest) HasYoutube() bool`

HasYoutube returns a boolean if a field has been set.

### GetPinterest

`func (o *FreeToolScoreSocialAuditRequest) GetPinterest() FreeToolScoreSocialAuditRequestInstagram`

GetPinterest returns the Pinterest field if non-nil, zero value otherwise.

### GetPinterestOk

`func (o *FreeToolScoreSocialAuditRequest) GetPinterestOk() (*FreeToolScoreSocialAuditRequestInstagram, bool)`

GetPinterestOk returns a tuple with the Pinterest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinterest

`func (o *FreeToolScoreSocialAuditRequest) SetPinterest(v FreeToolScoreSocialAuditRequestInstagram)`

SetPinterest sets Pinterest field to given value.

### HasPinterest

`func (o *FreeToolScoreSocialAuditRequest) HasPinterest() bool`

HasPinterest returns a boolean if a field has been set.

### GetThreads

`func (o *FreeToolScoreSocialAuditRequest) GetThreads() FreeToolScoreSocialAuditRequestInstagram`

GetThreads returns the Threads field if non-nil, zero value otherwise.

### GetThreadsOk

`func (o *FreeToolScoreSocialAuditRequest) GetThreadsOk() (*FreeToolScoreSocialAuditRequestInstagram, bool)`

GetThreadsOk returns a tuple with the Threads field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetThreads

`func (o *FreeToolScoreSocialAuditRequest) SetThreads(v FreeToolScoreSocialAuditRequestInstagram)`

SetThreads sets Threads field to given value.

### HasThreads

`func (o *FreeToolScoreSocialAuditRequest) HasThreads() bool`

HasThreads returns a boolean if a field has been set.

### GetBluesky

`func (o *FreeToolScoreSocialAuditRequest) GetBluesky() FreeToolScoreSocialAuditRequestInstagram`

GetBluesky returns the Bluesky field if non-nil, zero value otherwise.

### GetBlueskyOk

`func (o *FreeToolScoreSocialAuditRequest) GetBlueskyOk() (*FreeToolScoreSocialAuditRequestInstagram, bool)`

GetBlueskyOk returns a tuple with the Bluesky field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBluesky

`func (o *FreeToolScoreSocialAuditRequest) SetBluesky(v FreeToolScoreSocialAuditRequestInstagram)`

SetBluesky sets Bluesky field to given value.

### HasBluesky

`func (o *FreeToolScoreSocialAuditRequest) HasBluesky() bool`

HasBluesky returns a boolean if a field has been set.

### GetMastodon

`func (o *FreeToolScoreSocialAuditRequest) GetMastodon() FreeToolScoreSocialAuditRequestInstagram`

GetMastodon returns the Mastodon field if non-nil, zero value otherwise.

### GetMastodonOk

`func (o *FreeToolScoreSocialAuditRequest) GetMastodonOk() (*FreeToolScoreSocialAuditRequestInstagram, bool)`

GetMastodonOk returns a tuple with the Mastodon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMastodon

`func (o *FreeToolScoreSocialAuditRequest) SetMastodon(v FreeToolScoreSocialAuditRequestInstagram)`

SetMastodon sets Mastodon field to given value.

### HasMastodon

`func (o *FreeToolScoreSocialAuditRequest) HasMastodon() bool`

HasMastodon returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


