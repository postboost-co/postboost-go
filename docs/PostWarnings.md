# PostWarnings

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Warnings** | Pointer to [**[]PostWarning**](PostWarning.md) | Present only when there is at least one warning. | [optional] 

## Methods

### NewPostWarnings

`func NewPostWarnings() *PostWarnings`

NewPostWarnings instantiates a new PostWarnings object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostWarningsWithDefaults

`func NewPostWarningsWithDefaults() *PostWarnings`

NewPostWarningsWithDefaults instantiates a new PostWarnings object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetWarnings

`func (o *PostWarnings) GetWarnings() []PostWarning`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *PostWarnings) GetWarningsOk() (*[]PostWarning, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *PostWarnings) SetWarnings(v []PostWarning)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *PostWarnings) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


