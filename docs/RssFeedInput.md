# RssFeedInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Url** | **string** | Public http(s) URL of an RSS 2.0 or Atom feed. | 
**Name** | Pointer to **NullableString** |  | [optional] 
**AccountIds** | **[]int32** |  | 
**Mode** | Pointer to **string** |  | [optional] [default to "draft"]
**Template** | Pointer to **NullableString** | Post text. Placeholders: &#x60;{title}&#x60;, &#x60;{link}&#x60;, &#x60;{summary}&#x60; (up to 280 characters). Default &#x60;{title}&#x60; + blank line + &#x60;{link}&#x60;. | [optional] 
**MaxItemsPerRun** | Pointer to **int32** |  | [optional] [default to 3]
**Active** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewRssFeedInput

`func NewRssFeedInput(url string, accountIds []int32, ) *RssFeedInput`

NewRssFeedInput instantiates a new RssFeedInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRssFeedInputWithDefaults

`func NewRssFeedInputWithDefaults() *RssFeedInput`

NewRssFeedInputWithDefaults instantiates a new RssFeedInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUrl

`func (o *RssFeedInput) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *RssFeedInput) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *RssFeedInput) SetUrl(v string)`

SetUrl sets Url field to given value.


### GetName

`func (o *RssFeedInput) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RssFeedInput) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RssFeedInput) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *RssFeedInput) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *RssFeedInput) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *RssFeedInput) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetAccountIds

`func (o *RssFeedInput) GetAccountIds() []int32`

GetAccountIds returns the AccountIds field if non-nil, zero value otherwise.

### GetAccountIdsOk

`func (o *RssFeedInput) GetAccountIdsOk() (*[]int32, bool)`

GetAccountIdsOk returns a tuple with the AccountIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountIds

`func (o *RssFeedInput) SetAccountIds(v []int32)`

SetAccountIds sets AccountIds field to given value.


### GetMode

`func (o *RssFeedInput) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *RssFeedInput) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *RssFeedInput) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *RssFeedInput) HasMode() bool`

HasMode returns a boolean if a field has been set.

### GetTemplate

`func (o *RssFeedInput) GetTemplate() string`

GetTemplate returns the Template field if non-nil, zero value otherwise.

### GetTemplateOk

`func (o *RssFeedInput) GetTemplateOk() (*string, bool)`

GetTemplateOk returns a tuple with the Template field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplate

`func (o *RssFeedInput) SetTemplate(v string)`

SetTemplate sets Template field to given value.

### HasTemplate

`func (o *RssFeedInput) HasTemplate() bool`

HasTemplate returns a boolean if a field has been set.

### SetTemplateNil

`func (o *RssFeedInput) SetTemplateNil(b bool)`

 SetTemplateNil sets the value for Template to be an explicit nil

### UnsetTemplate
`func (o *RssFeedInput) UnsetTemplate()`

UnsetTemplate ensures that no value is present for Template, not even an explicit nil
### GetMaxItemsPerRun

`func (o *RssFeedInput) GetMaxItemsPerRun() int32`

GetMaxItemsPerRun returns the MaxItemsPerRun field if non-nil, zero value otherwise.

### GetMaxItemsPerRunOk

`func (o *RssFeedInput) GetMaxItemsPerRunOk() (*int32, bool)`

GetMaxItemsPerRunOk returns a tuple with the MaxItemsPerRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxItemsPerRun

`func (o *RssFeedInput) SetMaxItemsPerRun(v int32)`

SetMaxItemsPerRun sets MaxItemsPerRun field to given value.

### HasMaxItemsPerRun

`func (o *RssFeedInput) HasMaxItemsPerRun() bool`

HasMaxItemsPerRun returns a boolean if a field has been set.

### GetActive

`func (o *RssFeedInput) GetActive() bool`

GetActive returns the Active field if non-nil, zero value otherwise.

### GetActiveOk

`func (o *RssFeedInput) GetActiveOk() (*bool, bool)`

GetActiveOk returns a tuple with the Active field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActive

`func (o *RssFeedInput) SetActive(v bool)`

SetActive sets Active field to given value.

### HasActive

`func (o *RssFeedInput) HasActive() bool`

HasActive returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


