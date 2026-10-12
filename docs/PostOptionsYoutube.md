# PostOptionsYoutube

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Title** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] [default to "public"]
**MadeForKids** | Pointer to **bool** |  | [optional] [default to false]
**ContainsSyntheticMedia** | Pointer to **bool** | YouTube&#39;s \&quot;altered or synthetic content\&quot; disclosure. Set by &#x60;ai_generated&#x60;. | [optional] [default to false]

## Methods

### NewPostOptionsYoutube

`func NewPostOptionsYoutube() *PostOptionsYoutube`

NewPostOptionsYoutube instantiates a new PostOptionsYoutube object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPostOptionsYoutubeWithDefaults

`func NewPostOptionsYoutubeWithDefaults() *PostOptionsYoutube`

NewPostOptionsYoutubeWithDefaults instantiates a new PostOptionsYoutube object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTitle

`func (o *PostOptionsYoutube) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *PostOptionsYoutube) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *PostOptionsYoutube) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *PostOptionsYoutube) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetStatus

`func (o *PostOptionsYoutube) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PostOptionsYoutube) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PostOptionsYoutube) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PostOptionsYoutube) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetMadeForKids

`func (o *PostOptionsYoutube) GetMadeForKids() bool`

GetMadeForKids returns the MadeForKids field if non-nil, zero value otherwise.

### GetMadeForKidsOk

`func (o *PostOptionsYoutube) GetMadeForKidsOk() (*bool, bool)`

GetMadeForKidsOk returns a tuple with the MadeForKids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMadeForKids

`func (o *PostOptionsYoutube) SetMadeForKids(v bool)`

SetMadeForKids sets MadeForKids field to given value.

### HasMadeForKids

`func (o *PostOptionsYoutube) HasMadeForKids() bool`

HasMadeForKids returns a boolean if a field has been set.

### GetContainsSyntheticMedia

`func (o *PostOptionsYoutube) GetContainsSyntheticMedia() bool`

GetContainsSyntheticMedia returns the ContainsSyntheticMedia field if non-nil, zero value otherwise.

### GetContainsSyntheticMediaOk

`func (o *PostOptionsYoutube) GetContainsSyntheticMediaOk() (*bool, bool)`

GetContainsSyntheticMediaOk returns a tuple with the ContainsSyntheticMedia field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContainsSyntheticMedia

`func (o *PostOptionsYoutube) SetContainsSyntheticMedia(v bool)`

SetContainsSyntheticMedia sets ContainsSyntheticMedia field to given value.

### HasContainsSyntheticMedia

`func (o *PostOptionsYoutube) HasContainsSyntheticMedia() bool`

HasContainsSyntheticMedia returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


