# ResellerClientUsage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Used** | **int32** | Active client workspaces. | 
**Limit** | **int32** | Client workspaces the Reseller plan allows. | 

## Methods

### NewResellerClientUsage

`func NewResellerClientUsage(used int32, limit int32, ) *ResellerClientUsage`

NewResellerClientUsage instantiates a new ResellerClientUsage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResellerClientUsageWithDefaults

`func NewResellerClientUsageWithDefaults() *ResellerClientUsage`

NewResellerClientUsageWithDefaults instantiates a new ResellerClientUsage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUsed

`func (o *ResellerClientUsage) GetUsed() int32`

GetUsed returns the Used field if non-nil, zero value otherwise.

### GetUsedOk

`func (o *ResellerClientUsage) GetUsedOk() (*int32, bool)`

GetUsedOk returns a tuple with the Used field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsed

`func (o *ResellerClientUsage) SetUsed(v int32)`

SetUsed sets Used field to given value.


### GetLimit

`func (o *ResellerClientUsage) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *ResellerClientUsage) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *ResellerClientUsage) SetLimit(v int32)`

SetLimit sets Limit field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


