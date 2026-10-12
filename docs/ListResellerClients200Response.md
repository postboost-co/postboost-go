# ListResellerClients200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | [**[]ResellerClient**](ResellerClient.md) |  | 
**Meta** | [**ResellerClientUsage**](ResellerClientUsage.md) |  | 

## Methods

### NewListResellerClients200Response

`func NewListResellerClients200Response(data []ResellerClient, meta ResellerClientUsage, ) *ListResellerClients200Response`

NewListResellerClients200Response instantiates a new ListResellerClients200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListResellerClients200ResponseWithDefaults

`func NewListResellerClients200ResponseWithDefaults() *ListResellerClients200Response`

NewListResellerClients200ResponseWithDefaults instantiates a new ListResellerClients200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ListResellerClients200Response) GetData() []ResellerClient`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ListResellerClients200Response) GetDataOk() (*[]ResellerClient, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ListResellerClients200Response) SetData(v []ResellerClient)`

SetData sets Data field to given value.


### GetMeta

`func (o *ListResellerClients200Response) GetMeta() ResellerClientUsage`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ListResellerClients200Response) GetMetaOk() (*ResellerClientUsage, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ListResellerClients200Response) SetMeta(v ResellerClientUsage)`

SetMeta sets Meta field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


