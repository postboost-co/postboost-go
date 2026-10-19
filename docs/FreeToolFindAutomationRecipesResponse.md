# FreeToolFindAutomationRecipesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | Pointer to **int32** | Number of recipes returned. | [optional] 
**Recipes** | Pointer to [**[]FreeToolFindAutomationRecipesResponseRecipesInner**](FreeToolFindAutomationRecipesResponseRecipesInner.md) |  | [optional] 
**LastVerified** | Pointer to **string** | When the recipes were last checked against the API and the platforms. | [optional] 

## Methods

### NewFreeToolFindAutomationRecipesResponse

`func NewFreeToolFindAutomationRecipesResponse() *FreeToolFindAutomationRecipesResponse`

NewFreeToolFindAutomationRecipesResponse instantiates a new FreeToolFindAutomationRecipesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolFindAutomationRecipesResponseWithDefaults

`func NewFreeToolFindAutomationRecipesResponseWithDefaults() *FreeToolFindAutomationRecipesResponse`

NewFreeToolFindAutomationRecipesResponseWithDefaults instantiates a new FreeToolFindAutomationRecipesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *FreeToolFindAutomationRecipesResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *FreeToolFindAutomationRecipesResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *FreeToolFindAutomationRecipesResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *FreeToolFindAutomationRecipesResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetRecipes

`func (o *FreeToolFindAutomationRecipesResponse) GetRecipes() []FreeToolFindAutomationRecipesResponseRecipesInner`

GetRecipes returns the Recipes field if non-nil, zero value otherwise.

### GetRecipesOk

`func (o *FreeToolFindAutomationRecipesResponse) GetRecipesOk() (*[]FreeToolFindAutomationRecipesResponseRecipesInner, bool)`

GetRecipesOk returns a tuple with the Recipes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipes

`func (o *FreeToolFindAutomationRecipesResponse) SetRecipes(v []FreeToolFindAutomationRecipesResponseRecipesInner)`

SetRecipes sets Recipes field to given value.

### HasRecipes

`func (o *FreeToolFindAutomationRecipesResponse) HasRecipes() bool`

HasRecipes returns a boolean if a field has been set.

### GetLastVerified

`func (o *FreeToolFindAutomationRecipesResponse) GetLastVerified() string`

GetLastVerified returns the LastVerified field if non-nil, zero value otherwise.

### GetLastVerifiedOk

`func (o *FreeToolFindAutomationRecipesResponse) GetLastVerifiedOk() (*string, bool)`

GetLastVerifiedOk returns a tuple with the LastVerified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastVerified

`func (o *FreeToolFindAutomationRecipesResponse) SetLastVerified(v string)`

SetLastVerified sets LastVerified field to given value.

### HasLastVerified

`func (o *FreeToolFindAutomationRecipesResponse) HasLastVerified() bool`

HasLastVerified returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


