# UserUpdateInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** |  | 
**Email** | **string** |  | 
**Password** | Pointer to **string** | Omit or set to null to keep the current password. | [optional] 
**PasswordConfirmation** | Pointer to **string** |  | [optional] 
**IsAdmin** | **bool** |  | 

## Methods

### NewUserUpdateInput

`func NewUserUpdateInput(name string, email string, isAdmin bool, ) *UserUpdateInput`

NewUserUpdateInput instantiates a new UserUpdateInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserUpdateInputWithDefaults

`func NewUserUpdateInputWithDefaults() *UserUpdateInput`

NewUserUpdateInputWithDefaults instantiates a new UserUpdateInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *UserUpdateInput) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *UserUpdateInput) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *UserUpdateInput) SetName(v string)`

SetName sets Name field to given value.


### GetEmail

`func (o *UserUpdateInput) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *UserUpdateInput) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *UserUpdateInput) SetEmail(v string)`

SetEmail sets Email field to given value.


### GetPassword

`func (o *UserUpdateInput) GetPassword() string`

GetPassword returns the Password field if non-nil, zero value otherwise.

### GetPasswordOk

`func (o *UserUpdateInput) GetPasswordOk() (*string, bool)`

GetPasswordOk returns a tuple with the Password field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassword

`func (o *UserUpdateInput) SetPassword(v string)`

SetPassword sets Password field to given value.

### HasPassword

`func (o *UserUpdateInput) HasPassword() bool`

HasPassword returns a boolean if a field has been set.

### GetPasswordConfirmation

`func (o *UserUpdateInput) GetPasswordConfirmation() string`

GetPasswordConfirmation returns the PasswordConfirmation field if non-nil, zero value otherwise.

### GetPasswordConfirmationOk

`func (o *UserUpdateInput) GetPasswordConfirmationOk() (*string, bool)`

GetPasswordConfirmationOk returns a tuple with the PasswordConfirmation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPasswordConfirmation

`func (o *UserUpdateInput) SetPasswordConfirmation(v string)`

SetPasswordConfirmation sets PasswordConfirmation field to given value.

### HasPasswordConfirmation

`func (o *UserUpdateInput) HasPasswordConfirmation() bool`

HasPasswordConfirmation returns a boolean if a field has been set.

### GetIsAdmin

`func (o *UserUpdateInput) GetIsAdmin() bool`

GetIsAdmin returns the IsAdmin field if non-nil, zero value otherwise.

### GetIsAdminOk

`func (o *UserUpdateInput) GetIsAdminOk() (*bool, bool)`

GetIsAdminOk returns a tuple with the IsAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAdmin

`func (o *UserUpdateInput) SetIsAdmin(v bool)`

SetIsAdmin sets IsAdmin field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


