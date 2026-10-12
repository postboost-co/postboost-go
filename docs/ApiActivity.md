# ApiActivity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **int32** |  | 
**UserId** | Pointer to **NullableInt32** |  | [optional] 
**TokenRef** | Pointer to **NullableString** | First 12 hex characters of the SHA-256 of the API token used, to tell tokens apart. | [optional] 
**Client** | Pointer to **NullableString** | &#x60;X-PostBoost-Client&#x60; header, else the &#x60;User-Agent&#x60;. | [optional] 
**RouteName** | Pointer to **NullableString** |  | [optional] 
**Method** | **string** |  | 
**PostUuid** | Pointer to **NullableString** |  | [optional] 
**Outcome** | [**ApiActivityOutcome**](ApiActivityOutcome.md) |  | 
**HttpStatus** | **int32** |  | 
**CreatedAt** | **time.Time** |  | 

## Methods

### NewApiActivity

`func NewApiActivity(id int32, method string, outcome ApiActivityOutcome, httpStatus int32, createdAt time.Time, ) *ApiActivity`

NewApiActivity instantiates a new ApiActivity object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiActivityWithDefaults

`func NewApiActivityWithDefaults() *ApiActivity`

NewApiActivityWithDefaults instantiates a new ApiActivity object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ApiActivity) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ApiActivity) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ApiActivity) SetId(v int32)`

SetId sets Id field to given value.


### GetUserId

`func (o *ApiActivity) GetUserId() int32`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *ApiActivity) GetUserIdOk() (*int32, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *ApiActivity) SetUserId(v int32)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *ApiActivity) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### SetUserIdNil

`func (o *ApiActivity) SetUserIdNil(b bool)`

 SetUserIdNil sets the value for UserId to be an explicit nil

### UnsetUserId
`func (o *ApiActivity) UnsetUserId()`

UnsetUserId ensures that no value is present for UserId, not even an explicit nil
### GetTokenRef

`func (o *ApiActivity) GetTokenRef() string`

GetTokenRef returns the TokenRef field if non-nil, zero value otherwise.

### GetTokenRefOk

`func (o *ApiActivity) GetTokenRefOk() (*string, bool)`

GetTokenRefOk returns a tuple with the TokenRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenRef

`func (o *ApiActivity) SetTokenRef(v string)`

SetTokenRef sets TokenRef field to given value.

### HasTokenRef

`func (o *ApiActivity) HasTokenRef() bool`

HasTokenRef returns a boolean if a field has been set.

### SetTokenRefNil

`func (o *ApiActivity) SetTokenRefNil(b bool)`

 SetTokenRefNil sets the value for TokenRef to be an explicit nil

### UnsetTokenRef
`func (o *ApiActivity) UnsetTokenRef()`

UnsetTokenRef ensures that no value is present for TokenRef, not even an explicit nil
### GetClient

`func (o *ApiActivity) GetClient() string`

GetClient returns the Client field if non-nil, zero value otherwise.

### GetClientOk

`func (o *ApiActivity) GetClientOk() (*string, bool)`

GetClientOk returns a tuple with the Client field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClient

`func (o *ApiActivity) SetClient(v string)`

SetClient sets Client field to given value.

### HasClient

`func (o *ApiActivity) HasClient() bool`

HasClient returns a boolean if a field has been set.

### SetClientNil

`func (o *ApiActivity) SetClientNil(b bool)`

 SetClientNil sets the value for Client to be an explicit nil

### UnsetClient
`func (o *ApiActivity) UnsetClient()`

UnsetClient ensures that no value is present for Client, not even an explicit nil
### GetRouteName

`func (o *ApiActivity) GetRouteName() string`

GetRouteName returns the RouteName field if non-nil, zero value otherwise.

### GetRouteNameOk

`func (o *ApiActivity) GetRouteNameOk() (*string, bool)`

GetRouteNameOk returns a tuple with the RouteName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRouteName

`func (o *ApiActivity) SetRouteName(v string)`

SetRouteName sets RouteName field to given value.

### HasRouteName

`func (o *ApiActivity) HasRouteName() bool`

HasRouteName returns a boolean if a field has been set.

### SetRouteNameNil

`func (o *ApiActivity) SetRouteNameNil(b bool)`

 SetRouteNameNil sets the value for RouteName to be an explicit nil

### UnsetRouteName
`func (o *ApiActivity) UnsetRouteName()`

UnsetRouteName ensures that no value is present for RouteName, not even an explicit nil
### GetMethod

`func (o *ApiActivity) GetMethod() string`

GetMethod returns the Method field if non-nil, zero value otherwise.

### GetMethodOk

`func (o *ApiActivity) GetMethodOk() (*string, bool)`

GetMethodOk returns a tuple with the Method field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethod

`func (o *ApiActivity) SetMethod(v string)`

SetMethod sets Method field to given value.


### GetPostUuid

`func (o *ApiActivity) GetPostUuid() string`

GetPostUuid returns the PostUuid field if non-nil, zero value otherwise.

### GetPostUuidOk

`func (o *ApiActivity) GetPostUuidOk() (*string, bool)`

GetPostUuidOk returns a tuple with the PostUuid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPostUuid

`func (o *ApiActivity) SetPostUuid(v string)`

SetPostUuid sets PostUuid field to given value.

### HasPostUuid

`func (o *ApiActivity) HasPostUuid() bool`

HasPostUuid returns a boolean if a field has been set.

### SetPostUuidNil

`func (o *ApiActivity) SetPostUuidNil(b bool)`

 SetPostUuidNil sets the value for PostUuid to be an explicit nil

### UnsetPostUuid
`func (o *ApiActivity) UnsetPostUuid()`

UnsetPostUuid ensures that no value is present for PostUuid, not even an explicit nil
### GetOutcome

`func (o *ApiActivity) GetOutcome() ApiActivityOutcome`

GetOutcome returns the Outcome field if non-nil, zero value otherwise.

### GetOutcomeOk

`func (o *ApiActivity) GetOutcomeOk() (*ApiActivityOutcome, bool)`

GetOutcomeOk returns a tuple with the Outcome field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutcome

`func (o *ApiActivity) SetOutcome(v ApiActivityOutcome)`

SetOutcome sets Outcome field to given value.


### GetHttpStatus

`func (o *ApiActivity) GetHttpStatus() int32`

GetHttpStatus returns the HttpStatus field if non-nil, zero value otherwise.

### GetHttpStatusOk

`func (o *ApiActivity) GetHttpStatusOk() (*int32, bool)`

GetHttpStatusOk returns a tuple with the HttpStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHttpStatus

`func (o *ApiActivity) SetHttpStatus(v int32)`

SetHttpStatus sets HttpStatus field to given value.


### GetCreatedAt

`func (o *ApiActivity) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ApiActivity) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ApiActivity) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


