# FreeToolGetSafeZonesRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Platform** | **string** | The app the vertical video is posted to. Approximate: platforms do not publish official overlay sizes for organic posts, and the UI varies by device and app version. The boxes come from each platform&#39;s guidance for vertical video ads. Sources last verified 2026-10-17. | 
**Width** | Pointer to **int32** | Frame width in pixels. The boxes are measured on 1080 × 1920 and scaled to the frame. | [optional] [default to 1080]
**Height** | Pointer to **int32** | Frame height in pixels. | [optional] [default to 1920]

## Methods

### NewFreeToolGetSafeZonesRequest

`func NewFreeToolGetSafeZonesRequest(platform string, ) *FreeToolGetSafeZonesRequest`

NewFreeToolGetSafeZonesRequest instantiates a new FreeToolGetSafeZonesRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGetSafeZonesRequestWithDefaults

`func NewFreeToolGetSafeZonesRequestWithDefaults() *FreeToolGetSafeZonesRequest`

NewFreeToolGetSafeZonesRequestWithDefaults instantiates a new FreeToolGetSafeZonesRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlatform

`func (o *FreeToolGetSafeZonesRequest) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *FreeToolGetSafeZonesRequest) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *FreeToolGetSafeZonesRequest) SetPlatform(v string)`

SetPlatform sets Platform field to given value.


### GetWidth

`func (o *FreeToolGetSafeZonesRequest) GetWidth() int32`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *FreeToolGetSafeZonesRequest) GetWidthOk() (*int32, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *FreeToolGetSafeZonesRequest) SetWidth(v int32)`

SetWidth sets Width field to given value.

### HasWidth

`func (o *FreeToolGetSafeZonesRequest) HasWidth() bool`

HasWidth returns a boolean if a field has been set.

### GetHeight

`func (o *FreeToolGetSafeZonesRequest) GetHeight() int32`

GetHeight returns the Height field if non-nil, zero value otherwise.

### GetHeightOk

`func (o *FreeToolGetSafeZonesRequest) GetHeightOk() (*int32, bool)`

GetHeightOk returns a tuple with the Height field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHeight

`func (o *FreeToolGetSafeZonesRequest) SetHeight(v int32)`

SetHeight sets Height field to given value.

### HasHeight

`func (o *FreeToolGetSafeZonesRequest) HasHeight() bool`

HasHeight returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


