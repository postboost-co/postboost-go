# FreeToolBuildAgentSkillResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Format** | Pointer to **string** |  | [optional] 
**Filename** | Pointer to **string** |  | [optional] 
**Content** | Pointer to **string** | The file, in Markdown. | [optional] 
**Install** | Pointer to **[]string** | Where to put the file. | [optional] 
**ToolsUsed** | Pointer to **[]string** | The connector tool names the content names, in first-appearance order; empty with api_token. | [optional] 
**Lines** | Pointer to **int32** |  | [optional] 
**Warnings** | Pointer to [**[]FreeToolCheckPostResponseNetworksInnerErrorsInner**](FreeToolCheckPostResponseNetworksInnerErrorsInner.md) | Codes: name_normalized, task_limited_by_autonomy, autonomy_high, too_long. | [optional] 

## Methods

### NewFreeToolBuildAgentSkillResponse

`func NewFreeToolBuildAgentSkillResponse() *FreeToolBuildAgentSkillResponse`

NewFreeToolBuildAgentSkillResponse instantiates a new FreeToolBuildAgentSkillResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFreeToolBuildAgentSkillResponseWithDefaults

`func NewFreeToolBuildAgentSkillResponseWithDefaults() *FreeToolBuildAgentSkillResponse`

NewFreeToolBuildAgentSkillResponseWithDefaults instantiates a new FreeToolBuildAgentSkillResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetFormat

`func (o *FreeToolBuildAgentSkillResponse) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *FreeToolBuildAgentSkillResponse) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *FreeToolBuildAgentSkillResponse) SetFormat(v string)`

SetFormat sets Format field to given value.

### HasFormat

`func (o *FreeToolBuildAgentSkillResponse) HasFormat() bool`

HasFormat returns a boolean if a field has been set.

### GetFilename

`func (o *FreeToolBuildAgentSkillResponse) GetFilename() string`

GetFilename returns the Filename field if non-nil, zero value otherwise.

### GetFilenameOk

`func (o *FreeToolBuildAgentSkillResponse) GetFilenameOk() (*string, bool)`

GetFilenameOk returns a tuple with the Filename field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFilename

`func (o *FreeToolBuildAgentSkillResponse) SetFilename(v string)`

SetFilename sets Filename field to given value.

### HasFilename

`func (o *FreeToolBuildAgentSkillResponse) HasFilename() bool`

HasFilename returns a boolean if a field has been set.

### GetContent

`func (o *FreeToolBuildAgentSkillResponse) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *FreeToolBuildAgentSkillResponse) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *FreeToolBuildAgentSkillResponse) SetContent(v string)`

SetContent sets Content field to given value.

### HasContent

`func (o *FreeToolBuildAgentSkillResponse) HasContent() bool`

HasContent returns a boolean if a field has been set.

### GetInstall

`func (o *FreeToolBuildAgentSkillResponse) GetInstall() []string`

GetInstall returns the Install field if non-nil, zero value otherwise.

### GetInstallOk

`func (o *FreeToolBuildAgentSkillResponse) GetInstallOk() (*[]string, bool)`

GetInstallOk returns a tuple with the Install field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstall

`func (o *FreeToolBuildAgentSkillResponse) SetInstall(v []string)`

SetInstall sets Install field to given value.

### HasInstall

`func (o *FreeToolBuildAgentSkillResponse) HasInstall() bool`

HasInstall returns a boolean if a field has been set.

### GetToolsUsed

`func (o *FreeToolBuildAgentSkillResponse) GetToolsUsed() []string`

GetToolsUsed returns the ToolsUsed field if non-nil, zero value otherwise.

### GetToolsUsedOk

`func (o *FreeToolBuildAgentSkillResponse) GetToolsUsedOk() (*[]string, bool)`

GetToolsUsedOk returns a tuple with the ToolsUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolsUsed

`func (o *FreeToolBuildAgentSkillResponse) SetToolsUsed(v []string)`

SetToolsUsed sets ToolsUsed field to given value.

### HasToolsUsed

`func (o *FreeToolBuildAgentSkillResponse) HasToolsUsed() bool`

HasToolsUsed returns a boolean if a field has been set.

### GetLines

`func (o *FreeToolBuildAgentSkillResponse) GetLines() int32`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *FreeToolBuildAgentSkillResponse) GetLinesOk() (*int32, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *FreeToolBuildAgentSkillResponse) SetLines(v int32)`

SetLines sets Lines field to given value.

### HasLines

`func (o *FreeToolBuildAgentSkillResponse) HasLines() bool`

HasLines returns a boolean if a field has been set.

### GetWarnings

`func (o *FreeToolBuildAgentSkillResponse) GetWarnings() []FreeToolCheckPostResponseNetworksInnerErrorsInner`

GetWarnings returns the Warnings field if non-nil, zero value otherwise.

### GetWarningsOk

`func (o *FreeToolBuildAgentSkillResponse) GetWarningsOk() (*[]FreeToolCheckPostResponseNetworksInnerErrorsInner, bool)`

GetWarningsOk returns a tuple with the Warnings field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarnings

`func (o *FreeToolBuildAgentSkillResponse) SetWarnings(v []FreeToolCheckPostResponseNetworksInnerErrorsInner)`

SetWarnings sets Warnings field to given value.

### HasWarnings

`func (o *FreeToolBuildAgentSkillResponse) HasWarnings() bool`

HasWarnings returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


