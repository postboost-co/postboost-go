# AICredits

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Available** | **bool** | Whether the workspace can spend AI credits now. Always true when no balance is tracked. | 
**Balance** | **float32** | Remaining credit balance (2 decimals), or null when no balance is tracked. | 
**Low** | **bool** | True when the balance is above 0 and at most 10. | 

## Methods

### NewAICredits

`func NewAICredits(available bool, balance float32, low bool, ) *AICredits`

NewAICredits instantiates a new AICredits object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAICreditsWithDefaults

`func NewAICreditsWithDefaults() *AICredits`

NewAICreditsWithDefaults instantiates a new AICredits object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAvailable

`func (o *AICredits) GetAvailable() bool`

GetAvailable returns the Available field if non-nil, zero value otherwise.

### GetAvailableOk

`func (o *AICredits) GetAvailableOk() (*bool, bool)`

GetAvailableOk returns a tuple with the Available field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAvailable

`func (o *AICredits) SetAvailable(v bool)`

SetAvailable sets Available field to given value.


### GetBalance

`func (o *AICredits) GetBalance() float32`

GetBalance returns the Balance field if non-nil, zero value otherwise.

### GetBalanceOk

`func (o *AICredits) GetBalanceOk() (*float32, bool)`

GetBalanceOk returns a tuple with the Balance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalance

`func (o *AICredits) SetBalance(v float32)`

SetBalance sets Balance field to given value.


### GetLow

`func (o *AICredits) GetLow() bool`

GetLow returns the Low field if non-nil, zero value otherwise.

### GetLowOk

`func (o *AICredits) GetLowOk() (*bool, bool)`

GetLowOk returns a tuple with the Low field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLow

`func (o *AICredits) SetLow(v bool)`

SetLow sets Low field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


