# FreeToolGenerateQrCodeResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to **string** | The exact string encoded in the code (the link with its UTM tags). | [optional] 
**Svg** | Pointer to **string** | The QR code as an SVG document. | [optional] 
**Warnings** | Pointer to **[]string** |  | [optional] 

## Methods

### NewFreeToolGenerateQrCodeResponse

`func NewFreeToolGenerateQrCodeResponse() *FreeToolGenerateQrCodeResponse`

NewFreeToolGenerateQrCodeResponse instantiates a new FreeToolGenerateQrCodeResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolGenerateQrCodeResponseWithDefaults

`func NewFreeToolGenerateQrCodeResponseWithDefaults() *FreeToolGenerateQrCodeResponse`

NewFreeToolGenerateQrCodeResponseWithDefaults instantiates a new FreeToolGenerateQrCodeResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *FreeToolGenerateQrCodeResponse) GetData() string`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *FreeToolGenerateQrCodeResponse) GetDataOk() (*string, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *FreeToolGenerateQrCodeResponse) SetData(v string)`

SetData sets Data field to given value.

### HasData

`func (o *FreeToolGenerateQrCodeResponse) HasData() bool`

HasData returns a boolean if a field has been set.

### GetSvg

`func (o *FreeToolGenerateQrCodeResponse) GetSvg() string`

GetSvg returns the Svg field if non-nil, zero value otherwise.

### GetSvgOk

`func (o *FreeToolGenerateQrCodeResponse) GetSvgOk() (*string, bool)`

GetSvgOk returns a tuple with the Svg field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSvg

`func (o *FreeToolGenerateQrCodeResponse) SetSvg(v string)`

SetSvg sets Svg field to given value.

### HasSvg

`func (o *FreeToolGenerateQrCodeResponse) HasSvg() bool`

HasSvg returns a boolean if a field has been set.

### GetWarnings

`func (o *FreeToolGenerateQrCodeResponse) GetWarnings() []string`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *FreeToolGenerateQrCodeResponse) GetWarningsOk() (*[]string, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *FreeToolGenerateQrCodeResponse) SetWarnings(v []string)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *FreeToolGenerateQrCodeResponse) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


