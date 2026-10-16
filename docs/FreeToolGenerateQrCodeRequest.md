# FreeToolGenerateQrCodeRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | **string** | The link or text to encode. | 
**Utm** | Pointer to [**FreeToolGenerateQrCodeRequestUtm**](FreeToolGenerateQrCodeRequestUtm.md) |  | [optional] 
**ErrorCorrection** | Pointer to **string** | How much of the code can be damaged and still scan: L 7%, M 15%, Q 25%, H 30%. | [optional] [default to "M"]
**Size** | Pointer to **int32** | Width and height of the SVG in pixels. | [optional] [default to 512]
**Foreground** | Pointer to **string** | Colour of the modules, #RRGGBB. | [optional] [default to "#000000"]
**Background** | Pointer to **string** | Background colour, #RRGGBB. | [optional] [default to "#FFFFFF"]

## Methods

### NewFreeToolGenerateQrCodeRequest

`func NewFreeToolGenerateQrCodeRequest(data string, ) *FreeToolGenerateQrCodeRequest`

NewFreeToolGenerateQrCodeRequest instantiates a new FreeToolGenerateQrCodeRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateQrCodeRequestWithDefaults

`func NewFreeToolGenerateQrCodeRequestWithDefaults() *FreeToolGenerateQrCodeRequest`

NewFreeToolGenerateQrCodeRequestWithDefaults instantiates a new FreeToolGenerateQrCodeRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *FreeToolGenerateQrCodeRequest) GetData() string`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FreeToolGenerateQrCodeRequest) GetDataOk() (*string, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FreeToolGenerateQrCodeRequest) SetData(v string)`

SetData sets Data field to given value.


### GetUtm

`func (o *FreeToolGenerateQrCodeRequest) GetUtm() FreeToolGenerateQrCodeRequestUtm`

GetUtm returns the Utm field if non-nil, zero value otherwise.

### GetUtmOk

`func (o *FreeToolGenerateQrCodeRequest) GetUtmOk() (*FreeToolGenerateQrCodeRequestUtm, bool)`

GetUtmOk returns a tuple with the Utm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUtm

`func (o *FreeToolGenerateQrCodeRequest) SetUtm(v FreeToolGenerateQrCodeRequestUtm)`

SetUtm sets Utm field to given value.

### HasUtm

`func (o *FreeToolGenerateQrCodeRequest) HasUtm() bool`

HasUtm returns a boolean if a field has been set.

### GetErrorCorrection

`func (o *FreeToolGenerateQrCodeRequest) GetErrorCorrection() string`

GetErrorCorrection returns the ErrorCorrection field if non-nil, zero value otherwise.

### GetErrorCorrectionOk

`func (o *FreeToolGenerateQrCodeRequest) GetErrorCorrectionOk() (*string, bool)`

GetErrorCorrectionOk returns a tuple with the ErrorCorrection field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorCorrection

`func (o *FreeToolGenerateQrCodeRequest) SetErrorCorrection(v string)`

SetErrorCorrection sets ErrorCorrection field to given value.

### HasErrorCorrection

`func (o *FreeToolGenerateQrCodeRequest) HasErrorCorrection() bool`

HasErrorCorrection returns a boolean if a field has been set.

### GetSize

`func (o *FreeToolGenerateQrCodeRequest) GetSize() int32`

GetSize returns the Size field if non-nil, zero value otherwise.

### GetSizeOk

`func (o *FreeToolGenerateQrCodeRequest) GetSizeOk() (*int32, bool)`

GetSizeOk returns a tuple with the Size field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSize

`func (o *FreeToolGenerateQrCodeRequest) SetSize(v int32)`

SetSize sets Size field to given value.

### HasSize

`func (o *FreeToolGenerateQrCodeRequest) HasSize() bool`

HasSize returns a boolean if a field has been set.

### GetForeground

`func (o *FreeToolGenerateQrCodeRequest) GetForeground() string`

GetForeground returns the Foreground field if non-nil, zero value otherwise.

### GetForegroundOk

`func (o *FreeToolGenerateQrCodeRequest) GetForegroundOk() (*string, bool)`

GetForegroundOk returns a tuple with the Foreground field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetForeground

`func (o *FreeToolGenerateQrCodeRequest) SetForeground(v string)`

SetForeground sets Foreground field to given value.

### HasForeground

`func (o *FreeToolGenerateQrCodeRequest) HasForeground() bool`

HasForeground returns a boolean if a field has been set.

### GetBackground

`func (o *FreeToolGenerateQrCodeRequest) GetBackground() string`

GetBackground returns the Background field if non-nil, zero value otherwise.

### GetBackgroundOk

`func (o *FreeToolGenerateQrCodeRequest) GetBackgroundOk() (*string, bool)`

GetBackgroundOk returns a tuple with the Background field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackground

`func (o *FreeToolGenerateQrCodeRequest) SetBackground(v string)`

SetBackground sets Background field to given value.

### HasBackground

`func (o *FreeToolGenerateQrCodeRequest) HasBackground() bool`

HasBackground returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


