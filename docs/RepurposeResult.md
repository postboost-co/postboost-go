# RepurposeResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Source** | [**RepurposeResultSource**](RepurposeResultSource.md) |  | 
**Captions** | [**[]BlogToSocialCaption**](BlogToSocialCaption.md) |  | 
**Slides** | [**[]RepurposeSlide**](RepurposeSlide.md) | Carousel slides in order (hook first, call to action last). Empty without a carousel. | 
**Media** | Pointer to [**RepurposeResultMedia**](RepurposeResultMedia.md) |  | [optional] 
**PostUuid** | **NullableString** | The draft post; null when &#x60;create_post&#x60; was false. | 
**CreditsUsed** | **int32** |  | 
**CreditsRemaining** | **NullableInt32** | Null for unlimited plans. | 
**Warnings** | **[]string** | Parts that were skipped (for example a network that gets no carousel). | 

## Methods

### NewRepurposeResult

`func NewRepurposeResult(source RepurposeResultSource, captions []BlogToSocialCaption, slides []RepurposeSlide, postUuid NullableString, creditsUsed int32, creditsRemaining NullableInt32, warnings []string, ) *RepurposeResult`

NewRepurposeResult instantiates a new RepurposeResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRepurposeResultWithDefaults

`func NewRepurposeResultWithDefaults() *RepurposeResult`

NewRepurposeResultWithDefaults instantiates a new RepurposeResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSource

`func (o *RepurposeResult) GetSource() RepurposeResultSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *RepurposeResult) GetSourceOk() (*RepurposeResultSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *RepurposeResult) SetSource(v RepurposeResultSource)`

SetSource sets Source field to given value.


### GetCaptions

`func (o *RepurposeResult) GetCaptions() []BlogToSocialCaption`

GetCaptions returns the Captions field if non-nil, zero value otherwise.

### GetCaptionsOk

`func (o *RepurposeResult) GetCaptionsOk() (*[]BlogToSocialCaption, bool)`

GetCaptionsOk returns a tuple with the Captions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCaptions

`func (o *RepurposeResult) SetCaptions(v []BlogToSocialCaption)`

SetCaptions sets Captions field to given value.


### GetSlides

`func (o *RepurposeResult) GetSlides() []RepurposeSlide`

GetSlides returns the Slides field if non-nil, zero value otherwise.

### GetSlidesOk

`func (o *RepurposeResult) GetSlidesOk() (*[]RepurposeSlide, bool)`

GetSlidesOk returns a tuple with the Slides field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlides

`func (o *RepurposeResult) SetSlides(v []RepurposeSlide)`

SetSlides sets Slides field to given value.


### GetMedia

`func (o *RepurposeResult) GetMedia() RepurposeResultMedia`

GetMedia returns the Media field if non-nil, zero value otherwise.

### GetMediaOk

`func (o *RepurposeResult) GetMediaOk() (*RepurposeResultMedia, bool)`

GetMediaOk returns a tuple with the Media field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMedia

`func (o *RepurposeResult) SetMedia(v RepurposeResultMedia)`

SetMedia sets Media field to given value.

### HasMedia

`func (o *RepurposeResult) HasMedia() bool`

HasMedia returns a boolean if a field has been set.

### GetPostUuid

`func (o *RepurposeResult) GetPostUuid() string`

GetPostUuid returns the PostUuid field if non-nil, zero value otherwise.

### GetPostUuidOk

`func (o *RepurposeResult) GetPostUuidOk() (*string, bool)`

GetPostUuidOk returns a tuple with the PostUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostUuid

`func (o *RepurposeResult) SetPostUuid(v string)`

SetPostUuid sets PostUuid field to given value.


### SetPostUuidNil

`func (o *RepurposeResult) SetPostUuidNil(b bool)`

 SetPostUuidNil sets the value for PostUuid to be an explicit nil

### UnsetPostUuid
`func (o *RepurposeResult) UnsetPostUuid()`

UnsetPostUuid ensures that no value is present for PostUuid, not even an explicit nil
### GetCreditsUsed

`func (o *RepurposeResult) GetCreditsUsed() int32`

GetCreditsUsed returns the CreditsUsed field if non-nil, zero value otherwise.

### GetCreditsUsedOk

`func (o *RepurposeResult) GetCreditsUsedOk() (*int32, bool)`

GetCreditsUsedOk returns a tuple with the CreditsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsUsed

`func (o *RepurposeResult) SetCreditsUsed(v int32)`

SetCreditsUsed sets CreditsUsed field to given value.


### GetCreditsRemaining

`func (o *RepurposeResult) GetCreditsRemaining() int32`

GetCreditsRemaining returns the CreditsRemaining field if non-nil, zero value otherwise.

### GetCreditsRemainingOk

`func (o *RepurposeResult) GetCreditsRemainingOk() (*int32, bool)`

GetCreditsRemainingOk returns a tuple with the CreditsRemaining field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditsRemaining

`func (o *RepurposeResult) SetCreditsRemaining(v int32)`

SetCreditsRemaining sets CreditsRemaining field to given value.


### SetCreditsRemainingNil

`func (o *RepurposeResult) SetCreditsRemainingNil(b bool)`

 SetCreditsRemainingNil sets the value for CreditsRemaining to be an explicit nil

### UnsetCreditsRemaining
`func (o *RepurposeResult) UnsetCreditsRemaining()`

UnsetCreditsRemaining ensures that no value is present for CreditsRemaining, not even an explicit nil
### GetWarnings

`func (o *RepurposeResult) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *RepurposeResult) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *RepurposeResult) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


