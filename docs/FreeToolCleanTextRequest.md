# FreeToolCleanTextRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | **string** |  | 
**Dashes** | Pointer to **string** | What replaces an em or en dash between words: \&quot;, \&quot; (comma), \&quot;-\&quot; (hyphen), \&quot; - \&quot; (spaced) or nothing (keep). Number ranges like 2020–2024 always get a hyphen. | [optional] [default to "comma"]
**Quotes** | Pointer to **bool** | Curly quotes and apostrophes to straight ones. | [optional] [default to true]
**Invisible** | Pointer to **bool** | Remove zero-width characters and soft hyphens; turn non-breaking and thin spaces into normal spaces. | [optional] [default to true]
**Spaces** | Pointer to **bool** | Collapse double spaces between words and remove spaces at line ends. | [optional] [default to true]
**Ellipsis** | Pointer to **bool** | The ellipsis character to three dots. | [optional] [default to true]
**Markdown** | Pointer to **bool** | Strip **bold**, __bold__, *italic* and _italic_ markers, keeping the words. | [optional] [default to true]
**FlagPhrases** | Pointer to **bool** | List common AI phrases (e.g. \&quot;delve\&quot;) with their offsets. They are never changed. | [optional] [default to true]

## Methods

### NewFreeToolCleanTextRequest

`func NewFreeToolCleanTextRequest(text string, ) *FreeToolCleanTextRequest`

NewFreeToolCleanTextRequest instantiates a new FreeToolCleanTextRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolCleanTextRequestWithDefaults

`func NewFreeToolCleanTextRequestWithDefaults() *FreeToolCleanTextRequest`

NewFreeToolCleanTextRequestWithDefaults instantiates a new FreeToolCleanTextRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *FreeToolCleanTextRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *FreeToolCleanTextRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *FreeToolCleanTextRequest) SetText(v string)`

SetText sets Text field to given value.


### GetDashes

`func (o *FreeToolCleanTextRequest) GetDashes() string`

GetDashes returns the Dashes field if non-nil, zero value otherwise.

### GetDashesOk

`func (o *FreeToolCleanTextRequest) GetDashesOk() (*string, bool)`

GetDashesOk returns a tuple with the Dashes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDashes

`func (o *FreeToolCleanTextRequest) SetDashes(v string)`

SetDashes sets Dashes field to given value.

### HasDashes

`func (o *FreeToolCleanTextRequest) HasDashes() bool`

HasDashes returns a boolean if a field has been set.

### GetQuotes

`func (o *FreeToolCleanTextRequest) GetQuotes() bool`

GetQuotes returns the Quotes field if non-nil, zero value otherwise.

### GetQuotesOk

`func (o *FreeToolCleanTextRequest) GetQuotesOk() (*bool, bool)`

GetQuotesOk returns a tuple with the Quotes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuotes

`func (o *FreeToolCleanTextRequest) SetQuotes(v bool)`

SetQuotes sets Quotes field to given value.

### HasQuotes

`func (o *FreeToolCleanTextRequest) HasQuotes() bool`

HasQuotes returns a boolean if a field has been set.

### GetInvisible

`func (o *FreeToolCleanTextRequest) GetInvisible() bool`

GetInvisible returns the Invisible field if non-nil, zero value otherwise.

### GetInvisibleOk

`func (o *FreeToolCleanTextRequest) GetInvisibleOk() (*bool, bool)`

GetInvisibleOk returns a tuple with the Invisible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvisible

`func (o *FreeToolCleanTextRequest) SetInvisible(v bool)`

SetInvisible sets Invisible field to given value.

### HasInvisible

`func (o *FreeToolCleanTextRequest) HasInvisible() bool`

HasInvisible returns a boolean if a field has been set.

### GetSpaces

`func (o *FreeToolCleanTextRequest) GetSpaces() bool`

GetSpaces returns the Spaces field if non-nil, zero value otherwise.

### GetSpacesOk

`func (o *FreeToolCleanTextRequest) GetSpacesOk() (*bool, bool)`

GetSpacesOk returns a tuple with the Spaces field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSpaces

`func (o *FreeToolCleanTextRequest) SetSpaces(v bool)`

SetSpaces sets Spaces field to given value.

### HasSpaces

`func (o *FreeToolCleanTextRequest) HasSpaces() bool`

HasSpaces returns a boolean if a field has been set.

### GetEllipsis

`func (o *FreeToolCleanTextRequest) GetEllipsis() bool`

GetEllipsis returns the Ellipsis field if non-nil, zero value otherwise.

### GetEllipsisOk

`func (o *FreeToolCleanTextRequest) GetEllipsisOk() (*bool, bool)`

GetEllipsisOk returns a tuple with the Ellipsis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEllipsis

`func (o *FreeToolCleanTextRequest) SetEllipsis(v bool)`

SetEllipsis sets Ellipsis field to given value.

### HasEllipsis

`func (o *FreeToolCleanTextRequest) HasEllipsis() bool`

HasEllipsis returns a boolean if a field has been set.

### GetMarkdown

`func (o *FreeToolCleanTextRequest) GetMarkdown() bool`

GetMarkdown returns the Markdown field if non-nil, zero value otherwise.

### GetMarkdownOk

`func (o *FreeToolCleanTextRequest) GetMarkdownOk() (*bool, bool)`

GetMarkdownOk returns a tuple with the Markdown field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarkdown

`func (o *FreeToolCleanTextRequest) SetMarkdown(v bool)`

SetMarkdown sets Markdown field to given value.

### HasMarkdown

`func (o *FreeToolCleanTextRequest) HasMarkdown() bool`

HasMarkdown returns a boolean if a field has been set.

### GetFlagPhrases

`func (o *FreeToolCleanTextRequest) GetFlagPhrases() bool`

GetFlagPhrases returns the FlagPhrases field if non-nil, zero value otherwise.

### GetFlagPhrasesOk

`func (o *FreeToolCleanTextRequest) GetFlagPhrasesOk() (*bool, bool)`

GetFlagPhrasesOk returns a tuple with the FlagPhrases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFlagPhrases

`func (o *FreeToolCleanTextRequest) SetFlagPhrases(v bool)`

SetFlagPhrases sets FlagPhrases field to given value.

### HasFlagPhrases

`func (o *FreeToolCleanTextRequest) HasFlagPhrases() bool`

HasFlagPhrases returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


