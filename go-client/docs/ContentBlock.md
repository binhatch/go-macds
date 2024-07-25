# ContentBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** | Type | [optional] 
**Order** | Pointer to **int32** | Order | [optional] 
**TextFormatType** | Pointer to **string** | Suggestion of the text format for the respective content block. Values can be \&quot;break-line\&quot; or \&quot;break-page\&quot;. | [optional] 
**TextContent** | Pointer to **string** | Text Content | [optional] 
**Width** | Pointer to **string** | Width | [optional] 
**ImageName** | Pointer to **string** | Image Name | [optional] 
**ImageType** | Pointer to **string** | Image Type | [optional] 
**CellPadding** | Pointer to **int32** | Cell Padding | [optional] 
**CellSpacing** | Pointer to **int32** | Cell Spacing | [optional] 
**Border** | Pointer to **int32** | Border | [optional] 
**TableRows** | Pointer to [**[]TableRow**](TableRow.md) | List of Table Rows | [optional] 

## Methods

### NewContentBlock

`func NewContentBlock() *ContentBlock`

NewContentBlock instantiates a new ContentBlock object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContentBlockWithDefaults

`func NewContentBlockWithDefaults() *ContentBlock`

NewContentBlockWithDefaults instantiates a new ContentBlock object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *ContentBlock) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContentBlock) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContentBlock) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ContentBlock) HasType() bool`

HasType returns a boolean if a field has been set.

### GetOrder

`func (o *ContentBlock) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *ContentBlock) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *ContentBlock) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *ContentBlock) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetTextFormatType

`func (o *ContentBlock) GetTextFormatType() string`

GetTextFormatType returns the TextFormatType field if non-nil, zero value otherwise.

### GetTextFormatTypeOk

`func (o *ContentBlock) GetTextFormatTypeOk() (*string, bool)`

GetTextFormatTypeOk returns a tuple with the TextFormatType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTextFormatType

`func (o *ContentBlock) SetTextFormatType(v string)`

SetTextFormatType sets TextFormatType field to given value.

### HasTextFormatType

`func (o *ContentBlock) HasTextFormatType() bool`

HasTextFormatType returns a boolean if a field has been set.

### GetTextContent

`func (o *ContentBlock) GetTextContent() string`

GetTextContent returns the TextContent field if non-nil, zero value otherwise.

### GetTextContentOk

`func (o *ContentBlock) GetTextContentOk() (*string, bool)`

GetTextContentOk returns a tuple with the TextContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTextContent

`func (o *ContentBlock) SetTextContent(v string)`

SetTextContent sets TextContent field to given value.

### HasTextContent

`func (o *ContentBlock) HasTextContent() bool`

HasTextContent returns a boolean if a field has been set.

### GetWidth

`func (o *ContentBlock) GetWidth() string`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *ContentBlock) GetWidthOk() (*string, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *ContentBlock) SetWidth(v string)`

SetWidth sets Width field to given value.

### HasWidth

`func (o *ContentBlock) HasWidth() bool`

HasWidth returns a boolean if a field has been set.

### GetImageName

`func (o *ContentBlock) GetImageName() string`

GetImageName returns the ImageName field if non-nil, zero value otherwise.

### GetImageNameOk

`func (o *ContentBlock) GetImageNameOk() (*string, bool)`

GetImageNameOk returns a tuple with the ImageName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageName

`func (o *ContentBlock) SetImageName(v string)`

SetImageName sets ImageName field to given value.

### HasImageName

`func (o *ContentBlock) HasImageName() bool`

HasImageName returns a boolean if a field has been set.

### GetImageType

`func (o *ContentBlock) GetImageType() string`

GetImageType returns the ImageType field if non-nil, zero value otherwise.

### GetImageTypeOk

`func (o *ContentBlock) GetImageTypeOk() (*string, bool)`

GetImageTypeOk returns a tuple with the ImageType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageType

`func (o *ContentBlock) SetImageType(v string)`

SetImageType sets ImageType field to given value.

### HasImageType

`func (o *ContentBlock) HasImageType() bool`

HasImageType returns a boolean if a field has been set.

### GetCellPadding

`func (o *ContentBlock) GetCellPadding() int32`

GetCellPadding returns the CellPadding field if non-nil, zero value otherwise.

### GetCellPaddingOk

`func (o *ContentBlock) GetCellPaddingOk() (*int32, bool)`

GetCellPaddingOk returns a tuple with the CellPadding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCellPadding

`func (o *ContentBlock) SetCellPadding(v int32)`

SetCellPadding sets CellPadding field to given value.

### HasCellPadding

`func (o *ContentBlock) HasCellPadding() bool`

HasCellPadding returns a boolean if a field has been set.

### GetCellSpacing

`func (o *ContentBlock) GetCellSpacing() int32`

GetCellSpacing returns the CellSpacing field if non-nil, zero value otherwise.

### GetCellSpacingOk

`func (o *ContentBlock) GetCellSpacingOk() (*int32, bool)`

GetCellSpacingOk returns a tuple with the CellSpacing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCellSpacing

`func (o *ContentBlock) SetCellSpacing(v int32)`

SetCellSpacing sets CellSpacing field to given value.

### HasCellSpacing

`func (o *ContentBlock) HasCellSpacing() bool`

HasCellSpacing returns a boolean if a field has been set.

### GetBorder

`func (o *ContentBlock) GetBorder() int32`

GetBorder returns the Border field if non-nil, zero value otherwise.

### GetBorderOk

`func (o *ContentBlock) GetBorderOk() (*int32, bool)`

GetBorderOk returns a tuple with the Border field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorder

`func (o *ContentBlock) SetBorder(v int32)`

SetBorder sets Border field to given value.

### HasBorder

`func (o *ContentBlock) HasBorder() bool`

HasBorder returns a boolean if a field has been set.

### GetTableRows

`func (o *ContentBlock) GetTableRows() []TableRow`

GetTableRows returns the TableRows field if non-nil, zero value otherwise.

### GetTableRowsOk

`func (o *ContentBlock) GetTableRowsOk() (*[]TableRow, bool)`

GetTableRowsOk returns a tuple with the TableRows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTableRows

`func (o *ContentBlock) SetTableRows(v []TableRow)`

SetTableRows sets TableRows field to given value.

### HasTableRows

`func (o *ContentBlock) HasTableRows() bool`

HasTableRows returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


