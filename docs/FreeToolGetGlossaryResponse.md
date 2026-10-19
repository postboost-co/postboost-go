# FreeToolGetGlossaryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Total** | Pointer to **int32** | Number of terms returned. | [optional] 
**Terms** | Pointer to [**[]FreeToolGetGlossaryResponseTermsInner**](FreeToolGetGlossaryResponseTermsInner.md) |  | [optional] 
**LastVerified** | Pointer to **string** | When the definitions were last checked against their sources. | [optional] 

## Methods

### NewFreeToolGetGlossaryResponse

`func NewFreeToolGetGlossaryResponse() *FreeToolGetGlossaryResponse`

NewFreeToolGetGlossaryResponse instantiates a new FreeToolGetGlossaryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGetGlossaryResponseWithDefaults

`func NewFreeToolGetGlossaryResponseWithDefaults() *FreeToolGetGlossaryResponse`

NewFreeToolGetGlossaryResponseWithDefaults instantiates a new FreeToolGetGlossaryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTotal

`func (o *FreeToolGetGlossaryResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *FreeToolGetGlossaryResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *FreeToolGetGlossaryResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *FreeToolGetGlossaryResponse) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetTerms

`func (o *FreeToolGetGlossaryResponse) GetTerms() []FreeToolGetGlossaryResponseTermsInner`

GetTerms returns the Terms field if non-nil, zero value otherwise.

### GetTermsOk

`func (o *FreeToolGetGlossaryResponse) GetTermsOk() (*[]FreeToolGetGlossaryResponseTermsInner, bool)`

GetTermsOk returns a tuple with the Terms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTerms

`func (o *FreeToolGetGlossaryResponse) SetTerms(v []FreeToolGetGlossaryResponseTermsInner)`

SetTerms sets Terms field to given value.

### HasTerms

`func (o *FreeToolGetGlossaryResponse) HasTerms() bool`

HasTerms returns a boolean if a field has been set.

### GetLastVerified

`func (o *FreeToolGetGlossaryResponse) GetLastVerified() string`

GetLastVerified returns the LastVerified field if non-nil, zero value otherwise.

### GetLastVerifiedOk

`func (o *FreeToolGetGlossaryResponse) GetLastVerifiedOk() (*string, bool)`

GetLastVerifiedOk returns a tuple with the LastVerified field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastVerified

`func (o *FreeToolGetGlossaryResponse) SetLastVerified(v string)`

SetLastVerified sets LastVerified field to given value.

### HasLastVerified

`func (o *FreeToolGetGlossaryResponse) HasLastVerified() bool`

HasLastVerified returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


