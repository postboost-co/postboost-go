# FreeToolCalculateCarouselSlicesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Width** | **int32** | Source image width in pixels. | 
**Height** | **int32** | Source image height in pixels. | 
**Slides** | **int32** | Number of carousel slides, 2 to 10 (the most a carousel published through the Instagram API can hold). | 
**Ratio** | Pointer to **string** | Shape of each slide: &#x60;1:1&#x60; (1080 × 1080) or &#x60;4:5&#x60; (1080 × 1350). | [optional] [default to "4:5"]

## Methods

### NewFreeToolCalculateCarouselSlicesRequest

`func NewFreeToolCalculateCarouselSlicesRequest(width int32, height int32, slides int32, ) *FreeToolCalculateCarouselSlicesRequest`

NewFreeToolCalculateCarouselSlicesRequest instantiates a new FreeToolCalculateCarouselSlicesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCalculateCarouselSlicesRequestWithDefaults

`func NewFreeToolCalculateCarouselSlicesRequestWithDefaults() *FreeToolCalculateCarouselSlicesRequest`

NewFreeToolCalculateCarouselSlicesRequestWithDefaults instantiates a new FreeToolCalculateCarouselSlicesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWidth

`func (o *FreeToolCalculateCarouselSlicesRequest) GetWidth() int32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *FreeToolCalculateCarouselSlicesRequest) GetWidthOk() (*int32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *FreeToolCalculateCarouselSlicesRequest) SetWidth(v int32)`

SetWidth sets Width field to given value.


### GetHeight

`func (o *FreeToolCalculateCarouselSlicesRequest) GetHeight() int32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *FreeToolCalculateCarouselSlicesRequest) GetHeightOk() (*int32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *FreeToolCalculateCarouselSlicesRequest) SetHeight(v int32)`

SetHeight sets Height field to given value.


### GetSlides

`func (o *FreeToolCalculateCarouselSlicesRequest) GetSlides() int32`

GetSlides returns the Slides field if non-nil, zero value otherwise.

### GetSlidesOk

`func (o *FreeToolCalculateCarouselSlicesRequest) GetSlidesOk() (*int32, bool)`

GetSlidesOk returns a tuple with the Slides field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlides

`func (o *FreeToolCalculateCarouselSlicesRequest) SetSlides(v int32)`

SetSlides sets Slides field to given value.


### GetRatio

`func (o *FreeToolCalculateCarouselSlicesRequest) GetRatio() string`

GetRatio returns the Ratio field if non-nil, zero value otherwise.

### GetRatioOk

`func (o *FreeToolCalculateCarouselSlicesRequest) GetRatioOk() (*string, bool)`

GetRatioOk returns a tuple with the Ratio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRatio

`func (o *FreeToolCalculateCarouselSlicesRequest) SetRatio(v string)`

SetRatio sets Ratio field to given value.

### HasRatio

`func (o *FreeToolCalculateCarouselSlicesRequest) HasRatio() bool`

HasRatio returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


