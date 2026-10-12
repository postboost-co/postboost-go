# CompetitorInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountId** | **int32** | Your Instagram account &#x60;id&#x60; (connected through a Facebook Page) used to look the competitor up. | 
**Username** | **string** | Instagram username, with or without &#x60;@&#x60;. | 

## Methods

### NewCompetitorInput

`func NewCompetitorInput(accountId int32, username string, ) *CompetitorInput`

NewCompetitorInput instantiates a new CompetitorInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCompetitorInputWithDefaults

`func NewCompetitorInputWithDefaults() *CompetitorInput`

NewCompetitorInputWithDefaults instantiates a new CompetitorInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountId

`func (o *CompetitorInput) GetAccountId() int32`

GetAccountId returns the AccountId field if non-nil, zero value otherwise.

### GetAccountIdOk

`func (o *CompetitorInput) GetAccountIdOk() (*int32, bool)`

GetAccountIdOk returns a tuple with the AccountId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountId

`func (o *CompetitorInput) SetAccountId(v int32)`

SetAccountId sets AccountId field to given value.


### GetUsername

`func (o *CompetitorInput) GetUsername() string`

GetUsername returns the Username field if non-nil, zero value otherwise.

### GetUsernameOk

`func (o *CompetitorInput) GetUsernameOk() (*string, bool)`

GetUsernameOk returns a tuple with the Username field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsername

`func (o *CompetitorInput) SetUsername(v string)`

SetUsername sets Username field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


