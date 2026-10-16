# FreeToolFormatInstagramCaptionRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** |  | 
**Spacer** | Pointer to **string** | What fills a blank line: braille (U+2800 Braille blank, shows as an empty line) or dot (a line with \&quot;.\&quot;). | [optional] [default to "braille"]
**HashtagsToEnd** | Pointer to **bool** | Move the hashtags that end a line to the bottom, after three spacer lines. A hashtag inside a sentence stays where it is. | [optional] [default to false]

## Methods

### NewFreeToolFormatInstagramCaptionRequest

`func NewFreeToolFormatInstagramCaptionRequest(text string, ) *FreeToolFormatInstagramCaptionRequest`

NewFreeToolFormatInstagramCaptionRequest instantiates a new FreeToolFormatInstagramCaptionRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolFormatInstagramCaptionRequestWithDefaults

`func NewFreeToolFormatInstagramCaptionRequestWithDefaults() *FreeToolFormatInstagramCaptionRequest`

NewFreeToolFormatInstagramCaptionRequestWithDefaults instantiates a new FreeToolFormatInstagramCaptionRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolFormatInstagramCaptionRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolFormatInstagramCaptionRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolFormatInstagramCaptionRequest) SetText(v string)`

SetText sets Text field to given value.


### GetSpacer

`func (o *FreeToolFormatInstagramCaptionRequest) GetSpacer() string`

GetSpacer returns the Spacer field if non-nil, zero value otherwise.

### GetSpacerOk

`func (o *FreeToolFormatInstagramCaptionRequest) GetSpacerOk() (*string, bool)`

GetSpacerOk returns a tuple with the Spacer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpacer

`func (o *FreeToolFormatInstagramCaptionRequest) SetSpacer(v string)`

SetSpacer sets Spacer field to given value.

### HasSpacer

`func (o *FreeToolFormatInstagramCaptionRequest) HasSpacer() bool`

HasSpacer returns a boolean if a field has been set.

### GetHashtagsToEnd

`func (o *FreeToolFormatInstagramCaptionRequest) GetHashtagsToEnd() bool`

GetHashtagsToEnd returns the HashtagsToEnd field if non-nil, zero value otherwise.

### GetHashtagsToEndOk

`func (o *FreeToolFormatInstagramCaptionRequest) GetHashtagsToEndOk() (*bool, bool)`

GetHashtagsToEndOk returns a tuple with the HashtagsToEnd field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHashtagsToEnd

`func (o *FreeToolFormatInstagramCaptionRequest) SetHashtagsToEnd(v bool)`

SetHashtagsToEnd sets HashtagsToEnd field to given value.

### HasHashtagsToEnd

`func (o *FreeToolFormatInstagramCaptionRequest) HasHashtagsToEnd() bool`

HasHashtagsToEnd returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


