# FreeToolGetGlossaryResponseTermsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Term** | Pointer to **string** | The term. | [optional] 
**Slug** | Pointer to **string** | Stable key of the term, also its anchor on the page. | [optional] 
**Category** | Pointer to **string** | Category. | [optional] 
**Definition** | Pointer to **string** | Plain-language definition in one to three sentences. | [optional] 
**Networks** | Pointer to **[]string** | Networks the term is specific to (provider keys); empty when it applies to all. | [optional] 
**Related** | Pointer to **[]string** | Slugs of related terms. | [optional] 
**Url** | Pointer to **string** | The term on the glossary page. | [optional] 
**LearnUrl** | Pointer to **NullableString** | A PostBoost guide that goes deeper, or null. | [optional] 
**ToolUrl** | Pointer to **NullableString** | A free tool for the job, or null. | [optional] 
**FeatureUrl** | Pointer to **NullableString** | The PostBoost feature page, or null. | [optional] 
**Source** | Pointer to **NullableString** | Where a platform rule or number in the definition comes from, or null. | [optional] 

## Methods

### NewFreeToolGetGlossaryResponseTermsInner

`func NewFreeToolGetGlossaryResponseTermsInner() *FreeToolGetGlossaryResponseTermsInner`

NewFreeToolGetGlossaryResponseTermsInner instantiates a new FreeToolGetGlossaryResponseTermsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGetGlossaryResponseTermsInnerWithDefaults

`func NewFreeToolGetGlossaryResponseTermsInnerWithDefaults() *FreeToolGetGlossaryResponseTermsInner`

NewFreeToolGetGlossaryResponseTermsInnerWithDefaults instantiates a new FreeToolGetGlossaryResponseTermsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTerm

`func (o *FreeToolGetGlossaryResponseTermsInner) GetTerm() string`

GetTerm returns the Term field if non-nil, zero value otherwise.

### GetTermOk

`func (o *FreeToolGetGlossaryResponseTermsInner) GetTermOk() (*string, bool)`

GetTermOk returns a tuple with the Term field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerm

`func (o *FreeToolGetGlossaryResponseTermsInner) SetTerm(v string)`

SetTerm sets Term field to given value.

### HasTerm

`func (o *FreeToolGetGlossaryResponseTermsInner) HasTerm() bool`

HasTerm returns a boolean if a field has been set.

### GetSlug

`func (o *FreeToolGetGlossaryResponseTermsInner) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *FreeToolGetGlossaryResponseTermsInner) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *FreeToolGetGlossaryResponseTermsInner) SetSlug(v string)`

SetSlug sets Slug field to given value.

### HasSlug

`func (o *FreeToolGetGlossaryResponseTermsInner) HasSlug() bool`

HasSlug returns a boolean if a field has been set.

### GetCategory

`func (o *FreeToolGetGlossaryResponseTermsInner) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *FreeToolGetGlossaryResponseTermsInner) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *FreeToolGetGlossaryResponseTermsInner) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *FreeToolGetGlossaryResponseTermsInner) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetDefinition

`func (o *FreeToolGetGlossaryResponseTermsInner) GetDefinition() string`

GetDefinition returns the Definition field if non-nil, zero value otherwise.

### GetDefinitionOk

`func (o *FreeToolGetGlossaryResponseTermsInner) GetDefinitionOk() (*string, bool)`

GetDefinitionOk returns a tuple with the Definition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefinition

`func (o *FreeToolGetGlossaryResponseTermsInner) SetDefinition(v string)`

SetDefinition sets Definition field to given value.

### HasDefinition

`func (o *FreeToolGetGlossaryResponseTermsInner) HasDefinition() bool`

HasDefinition returns a boolean if a field has been set.

### GetNetworks

`func (o *FreeToolGetGlossaryResponseTermsInner) GetNetworks() []string`

GetNetworks returns the Networks field if non-nil, zero value otherwise.

### GetNetworksOk

`func (o *FreeToolGetGlossaryResponseTermsInner) GetNetworksOk() (*[]string, bool)`

GetNetworksOk returns a tuple with the Networks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetworks

`func (o *FreeToolGetGlossaryResponseTermsInner) SetNetworks(v []string)`

SetNetworks sets Networks field to given value.

### HasNetworks

`func (o *FreeToolGetGlossaryResponseTermsInner) HasNetworks() bool`

HasNetworks returns a boolean if a field has been set.

### GetRelated

`func (o *FreeToolGetGlossaryResponseTermsInner) GetRelated() []string`

GetRelated returns the Related field if non-nil, zero value otherwise.

### GetRelatedOk

`func (o *FreeToolGetGlossaryResponseTermsInner) GetRelatedOk() (*[]string, bool)`

GetRelatedOk returns a tuple with the Related field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelated

`func (o *FreeToolGetGlossaryResponseTermsInner) SetRelated(v []string)`

SetRelated sets Related field to given value.

### HasRelated

`func (o *FreeToolGetGlossaryResponseTermsInner) HasRelated() bool`

HasRelated returns a boolean if a field has been set.

### GetUrl

`func (o *FreeToolGetGlossaryResponseTermsInner) GetUrl() string`

GetUrl returns the Url field if non-nil, zero value otherwise.

### GetUrlOk

`func (o *FreeToolGetGlossaryResponseTermsInner) GetUrlOk() (*string, bool)`

GetUrlOk returns a tuple with the Url field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrl

`func (o *FreeToolGetGlossaryResponseTermsInner) SetUrl(v string)`

SetUrl sets Url field to given value.

### HasUrl

`func (o *FreeToolGetGlossaryResponseTermsInner) HasUrl() bool`

HasUrl returns a boolean if a field has been set.

### GetLearnUrl

`func (o *FreeToolGetGlossaryResponseTermsInner) GetLearnUrl() string`

GetLearnUrl returns the LearnUrl field if non-nil, zero value otherwise.

### GetLearnUrlOk

`func (o *FreeToolGetGlossaryResponseTermsInner) GetLearnUrlOk() (*string, bool)`

GetLearnUrlOk returns a tuple with the LearnUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLearnUrl

`func (o *FreeToolGetGlossaryResponseTermsInner) SetLearnUrl(v string)`

SetLearnUrl sets LearnUrl field to given value.

### HasLearnUrl

`func (o *FreeToolGetGlossaryResponseTermsInner) HasLearnUrl() bool`

HasLearnUrl returns a boolean if a field has been set.

### SetLearnUrlNil

`func (o *FreeToolGetGlossaryResponseTermsInner) SetLearnUrlNil(b bool)`

 SetLearnUrlNil sets the value for LearnUrl to be an explicit nil

### UnsetLearnUrl
`func (o *FreeToolGetGlossaryResponseTermsInner) UnsetLearnUrl()`

UnsetLearnUrl ensures that no value is present for LearnUrl, not even an explicit nil
### GetToolUrl

`func (o *FreeToolGetGlossaryResponseTermsInner) GetToolUrl() string`

GetToolUrl returns the ToolUrl field if non-nil, zero value otherwise.

### GetToolUrlOk

`func (o *FreeToolGetGlossaryResponseTermsInner) GetToolUrlOk() (*string, bool)`

GetToolUrlOk returns a tuple with the ToolUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolUrl

`func (o *FreeToolGetGlossaryResponseTermsInner) SetToolUrl(v string)`

SetToolUrl sets ToolUrl field to given value.

### HasToolUrl

`func (o *FreeToolGetGlossaryResponseTermsInner) HasToolUrl() bool`

HasToolUrl returns a boolean if a field has been set.

### SetToolUrlNil

`func (o *FreeToolGetGlossaryResponseTermsInner) SetToolUrlNil(b bool)`

 SetToolUrlNil sets the value for ToolUrl to be an explicit nil

### UnsetToolUrl
`func (o *FreeToolGetGlossaryResponseTermsInner) UnsetToolUrl()`

UnsetToolUrl ensures that no value is present for ToolUrl, not even an explicit nil
### GetFeatureUrl

`func (o *FreeToolGetGlossaryResponseTermsInner) GetFeatureUrl() string`

GetFeatureUrl returns the FeatureUrl field if non-nil, zero value otherwise.

### GetFeatureUrlOk

`func (o *FreeToolGetGlossaryResponseTermsInner) GetFeatureUrlOk() (*string, bool)`

GetFeatureUrlOk returns a tuple with the FeatureUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureUrl

`func (o *FreeToolGetGlossaryResponseTermsInner) SetFeatureUrl(v string)`

SetFeatureUrl sets FeatureUrl field to given value.

### HasFeatureUrl

`func (o *FreeToolGetGlossaryResponseTermsInner) HasFeatureUrl() bool`

HasFeatureUrl returns a boolean if a field has been set.

### SetFeatureUrlNil

`func (o *FreeToolGetGlossaryResponseTermsInner) SetFeatureUrlNil(b bool)`

 SetFeatureUrlNil sets the value for FeatureUrl to be an explicit nil

### UnsetFeatureUrl
`func (o *FreeToolGetGlossaryResponseTermsInner) UnsetFeatureUrl()`

UnsetFeatureUrl ensures that no value is present for FeatureUrl, not even an explicit nil
### GetSource

`func (o *FreeToolGetGlossaryResponseTermsInner) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *FreeToolGetGlossaryResponseTermsInner) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *FreeToolGetGlossaryResponseTermsInner) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *FreeToolGetGlossaryResponseTermsInner) HasSource() bool`

HasSource returns a boolean if a field has been set.

### SetSourceNil

`func (o *FreeToolGetGlossaryResponseTermsInner) SetSourceNil(b bool)`

 SetSourceNil sets the value for Source to be an explicit nil

### UnsetSource
`func (o *FreeToolGetGlossaryResponseTermsInner) UnsetSource()`

UnsetSource ensures that no value is present for Source, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


