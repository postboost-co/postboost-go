# PostOptionsInstagram

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** |  | [optional] [default to "post"]
**Collaborators** | Pointer to **[]string** | Usernames invited as collaborators (not for stories). | [optional] 
**AiGenerated** | Pointer to **bool** | Instagram&#39;s \&quot;AI info\&quot; label on the post (on the carousel itself for carousels; not for stories). Set by &#x60;ai_generated&#x60;. | [optional] [default to false]

## Methods

### NewPostOptionsInstagram

`func NewPostOptionsInstagram() *PostOptionsInstagram`

NewPostOptionsInstagram instantiates a new PostOptionsInstagram object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostOptionsInstagramWithDefaults

`func NewPostOptionsInstagramWithDefaults() *PostOptionsInstagram`

NewPostOptionsInstagramWithDefaults instantiates a new PostOptionsInstagram object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *PostOptionsInstagram) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PostOptionsInstagram) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PostOptionsInstagram) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *PostOptionsInstagram) HasType() bool`

HasType returns a boolean if a field has been set.

### GetCollaborators

`func (o *PostOptionsInstagram) GetCollaborators() []string`

GetCollaborators returns the Collaborators field if non-nil, zero value otherwise.

### GetCollaboratorsOk

`func (o *PostOptionsInstagram) GetCollaboratorsOk() (*[]string, bool)`

GetCollaboratorsOk returns a tuple with the Collaborators field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCollaborators

`func (o *PostOptionsInstagram) SetCollaborators(v []string)`

SetCollaborators sets Collaborators field to given value.

### HasCollaborators

`func (o *PostOptionsInstagram) HasCollaborators() bool`

HasCollaborators returns a boolean if a field has been set.

### GetAiGenerated

`func (o *PostOptionsInstagram) GetAiGenerated() bool`

GetAiGenerated returns the AiGenerated field if non-nil, zero value otherwise.

### GetAiGeneratedOk

`func (o *PostOptionsInstagram) GetAiGeneratedOk() (*bool, bool)`

GetAiGeneratedOk returns a tuple with the AiGenerated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAiGenerated

`func (o *PostOptionsInstagram) SetAiGenerated(v bool)`

SetAiGenerated sets AiGenerated field to given value.

### HasAiGenerated

`func (o *PostOptionsInstagram) HasAiGenerated() bool`

HasAiGenerated returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


