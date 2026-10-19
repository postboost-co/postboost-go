# FreeToolFindAutomationRecipesResponseRecipesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Slug** | Pointer to **string** | Stable key of the recipe, also its anchor on the page. | [optional] 
**Title** | Pointer to **string** | What the recipe does. | [optional] 
**Trigger** | Pointer to **string** | What starts it. | [optional] 
**Goal** | Pointer to **string** | The result in one or two sentences. | [optional] 
**Native** | Pointer to [**FreeToolFindAutomationRecipesResponseRecipesInnerNative**](FreeToolFindAutomationRecipesResponseRecipesInnerNative.md) |  | [optional] 
**ApiOperations** | Pointer to [**[]FreeToolFindAutomationRecipesResponseRecipesInnerApiOperationsInner**](FreeToolFindAutomationRecipesResponseRecipesInnerApiOperationsInner.md) | The PostBoost API operations the recipe calls. | [optional] 
**Steps** | Pointer to [**FreeToolFindAutomationRecipesResponseRecipesInnerSteps**](FreeToolFindAutomationRecipesResponseRecipesInnerSteps.md) |  | [optional] 
**N8nWorkflow** | Pointer to **map[string]interface{}** | Importable n8n workflow (core nodes only; add a Header Auth credential named \&quot;PostBoost API token\&quot;) when &#x60;platform&#x60; is &#x60;n8n&#x60;; null otherwise. | [optional] 

## Methods

### NewFreeToolFindAutomationRecipesResponseRecipesInner

`func NewFreeToolFindAutomationRecipesResponseRecipesInner() *FreeToolFindAutomationRecipesResponseRecipesInner`

NewFreeToolFindAutomationRecipesResponseRecipesInner instantiates a new FreeToolFindAutomationRecipesResponseRecipesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolFindAutomationRecipesResponseRecipesInnerWithDefaults

`func NewFreeToolFindAutomationRecipesResponseRecipesInnerWithDefaults() *FreeToolFindAutomationRecipesResponseRecipesInner`

NewFreeToolFindAutomationRecipesResponseRecipesInnerWithDefaults instantiates a new FreeToolFindAutomationRecipesResponseRecipesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSlug

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) SetSlug(v string)`

SetSlug sets Slug field to given value.

### HasSlug

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) HasSlug() bool`

HasSlug returns a boolean if a field has been set.

### GetTitle

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetTrigger

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) GetTrigger() string`

GetTrigger returns the Trigger field if non-nil, zero value otherwise.

### GetTriggerOk

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) GetTriggerOk() (*string, bool)`

GetTriggerOk returns a tuple with the Trigger field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTrigger

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) SetTrigger(v string)`

SetTrigger sets Trigger field to given value.

### HasTrigger

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) HasTrigger() bool`

HasTrigger returns a boolean if a field has been set.

### GetGoal

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) GetGoal() string`

GetGoal returns the Goal field if non-nil, zero value otherwise.

### GetGoalOk

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) GetGoalOk() (*string, bool)`

GetGoalOk returns a tuple with the Goal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGoal

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) SetGoal(v string)`

SetGoal sets Goal field to given value.

### HasGoal

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) HasGoal() bool`

HasGoal returns a boolean if a field has been set.

### GetNative

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) GetNative() FreeToolFindAutomationRecipesResponseRecipesInnerNative`

GetNative returns the Native field if non-nil, zero value otherwise.

### GetNativeOk

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) GetNativeOk() (*FreeToolFindAutomationRecipesResponseRecipesInnerNative, bool)`

GetNativeOk returns a tuple with the Native field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNative

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) SetNative(v FreeToolFindAutomationRecipesResponseRecipesInnerNative)`

SetNative sets Native field to given value.

### HasNative

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) HasNative() bool`

HasNative returns a boolean if a field has been set.

### GetApiOperations

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) GetApiOperations() []FreeToolFindAutomationRecipesResponseRecipesInnerApiOperationsInner`

GetApiOperations returns the ApiOperations field if non-nil, zero value otherwise.

### GetApiOperationsOk

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) GetApiOperationsOk() (*[]FreeToolFindAutomationRecipesResponseRecipesInnerApiOperationsInner, bool)`

GetApiOperationsOk returns a tuple with the ApiOperations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiOperations

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) SetApiOperations(v []FreeToolFindAutomationRecipesResponseRecipesInnerApiOperationsInner)`

SetApiOperations sets ApiOperations field to given value.

### HasApiOperations

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) HasApiOperations() bool`

HasApiOperations returns a boolean if a field has been set.

### GetSteps

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) GetSteps() FreeToolFindAutomationRecipesResponseRecipesInnerSteps`

GetSteps returns the Steps field if non-nil, zero value otherwise.

### GetStepsOk

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) GetStepsOk() (*FreeToolFindAutomationRecipesResponseRecipesInnerSteps, bool)`

GetStepsOk returns a tuple with the Steps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSteps

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) SetSteps(v FreeToolFindAutomationRecipesResponseRecipesInnerSteps)`

SetSteps sets Steps field to given value.

### HasSteps

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) HasSteps() bool`

HasSteps returns a boolean if a field has been set.

### GetN8nWorkflow

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) GetN8nWorkflow() map[string]interface{}`

GetN8nWorkflow returns the N8nWorkflow field if non-nil, zero value otherwise.

### GetN8nWorkflowOk

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) GetN8nWorkflowOk() (*map[string]interface{}, bool)`

GetN8nWorkflowOk returns a tuple with the N8nWorkflow field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetN8nWorkflow

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) SetN8nWorkflow(v map[string]interface{})`

SetN8nWorkflow sets N8nWorkflow field to given value.

### HasN8nWorkflow

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) HasN8nWorkflow() bool`

HasN8nWorkflow returns a boolean if a field has been set.

### SetN8nWorkflowNil

`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) SetN8nWorkflowNil(b bool)`

 SetN8nWorkflowNil sets the value for N8nWorkflow to be an explicit nil

### UnsetN8nWorkflow
`func (o *FreeToolFindAutomationRecipesResponseRecipesInner) UnsetN8nWorkflow()`

UnsetN8nWorkflow ensures that no value is present for N8nWorkflow, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


