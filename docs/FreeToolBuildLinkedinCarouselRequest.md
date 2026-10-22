# FreeToolBuildLinkedinCarouselRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** | The post or outline. Blank lines separate slides; a first line starting with # (or a short first line without closing punctuation that is not a list item) is the slide heading; - * • lines become bullets. | 
**MaxSlides** | Pointer to **int32** | Most slides to return, 3 to 20. The cover and the CTA slide are always kept. | [optional] [default to 10]
**Size** | Pointer to **string** | Slide shape: &#x60;4:5&#x60; (1080 × 1350) or &#x60;1:1&#x60; (1080 × 1080). Every page of a LinkedIn document has the same size. | [optional] [default to "4:5"]
**Cover** | Pointer to **bool** | Start with a cover slide: the first heading, or the first line of the text. | [optional] [default to true]
**Cta** | Pointer to **string** | Text of a closing call-to-action slide. | [optional] 

## Methods

### NewFreeToolBuildLinkedinCarouselRequest

`func NewFreeToolBuildLinkedinCarouselRequest(text string, ) *FreeToolBuildLinkedinCarouselRequest`

NewFreeToolBuildLinkedinCarouselRequest instantiates a new FreeToolBuildLinkedinCarouselRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolBuildLinkedinCarouselRequestWithDefaults

`func NewFreeToolBuildLinkedinCarouselRequestWithDefaults() *FreeToolBuildLinkedinCarouselRequest`

NewFreeToolBuildLinkedinCarouselRequestWithDefaults instantiates a new FreeToolBuildLinkedinCarouselRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolBuildLinkedinCarouselRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolBuildLinkedinCarouselRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolBuildLinkedinCarouselRequest) SetText(v string)`

SetText sets Text field to given value.


### GetMaxSlides

`func (o *FreeToolBuildLinkedinCarouselRequest) GetMaxSlides() int32`

GetMaxSlides returns the MaxSlides field if non-nil, zero value otherwise.

### GetMaxSlidesOk

`func (o *FreeToolBuildLinkedinCarouselRequest) GetMaxSlidesOk() (*int32, bool)`

GetMaxSlidesOk returns a tuple with the MaxSlides field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxSlides

`func (o *FreeToolBuildLinkedinCarouselRequest) SetMaxSlides(v int32)`

SetMaxSlides sets MaxSlides field to given value.

### HasMaxSlides

`func (o *FreeToolBuildLinkedinCarouselRequest) HasMaxSlides() bool`

HasMaxSlides returns a boolean if a field has been set.

### GetSize

`func (o *FreeToolBuildLinkedinCarouselRequest) GetSize() string`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *FreeToolBuildLinkedinCarouselRequest) GetSizeOk() (*string, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *FreeToolBuildLinkedinCarouselRequest) SetSize(v string)`

SetSize sets Size field to given value.

### HasSize

`func (o *FreeToolBuildLinkedinCarouselRequest) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetCover

`func (o *FreeToolBuildLinkedinCarouselRequest) GetCover() bool`

GetCover returns the Cover field if non-nil, zero value otherwise.

### GetCoverOk

`func (o *FreeToolBuildLinkedinCarouselRequest) GetCoverOk() (*bool, bool)`

GetCoverOk returns a tuple with the Cover field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCover

`func (o *FreeToolBuildLinkedinCarouselRequest) SetCover(v bool)`

SetCover sets Cover field to given value.

### HasCover

`func (o *FreeToolBuildLinkedinCarouselRequest) HasCover() bool`

HasCover returns a boolean if a field has been set.

### GetCta

`func (o *FreeToolBuildLinkedinCarouselRequest) GetCta() string`

GetCta returns the Cta field if non-nil, zero value otherwise.

### GetCtaOk

`func (o *FreeToolBuildLinkedinCarouselRequest) GetCtaOk() (*string, bool)`

GetCtaOk returns a tuple with the Cta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCta

`func (o *FreeToolBuildLinkedinCarouselRequest) SetCta(v string)`

SetCta sets Cta field to given value.

### HasCta

`func (o *FreeToolBuildLinkedinCarouselRequest) HasCta() bool`

HasCta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


