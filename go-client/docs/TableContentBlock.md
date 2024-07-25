# TableContentBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Order** | Pointer to **int32** | Order | [optional] 
**CellPadding** | Pointer to **int32** | Cell Padding | [optional] 
**CellSpacing** | Pointer to **int32** | Cell Spacing | [optional] 
**Border** | Pointer to **int32** | Border | [optional] 
**TableRows** | Pointer to [**[]TableRow**](TableRow.md) | List of Table Rows | [optional] 
**Type** | Pointer to **string** | Type | [optional] 

## Methods

### NewTableContentBlock

`func NewTableContentBlock() *TableContentBlock`

NewTableContentBlock instantiates a new TableContentBlock object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTableContentBlockWithDefaults

`func NewTableContentBlockWithDefaults() *TableContentBlock`

NewTableContentBlockWithDefaults instantiates a new TableContentBlock object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrder

`func (o *TableContentBlock) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *TableContentBlock) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *TableContentBlock) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *TableContentBlock) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetCellPadding

`func (o *TableContentBlock) GetCellPadding() int32`

GetCellPadding returns the CellPadding field if non-nil, zero value otherwise.

### GetCellPaddingOk

`func (o *TableContentBlock) GetCellPaddingOk() (*int32, bool)`

GetCellPaddingOk returns a tuple with the CellPadding field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCellPadding

`func (o *TableContentBlock) SetCellPadding(v int32)`

SetCellPadding sets CellPadding field to given value.

### HasCellPadding

`func (o *TableContentBlock) HasCellPadding() bool`

HasCellPadding returns a boolean if a field has been set.

### GetCellSpacing

`func (o *TableContentBlock) GetCellSpacing() int32`

GetCellSpacing returns the CellSpacing field if non-nil, zero value otherwise.

### GetCellSpacingOk

`func (o *TableContentBlock) GetCellSpacingOk() (*int32, bool)`

GetCellSpacingOk returns a tuple with the CellSpacing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCellSpacing

`func (o *TableContentBlock) SetCellSpacing(v int32)`

SetCellSpacing sets CellSpacing field to given value.

### HasCellSpacing

`func (o *TableContentBlock) HasCellSpacing() bool`

HasCellSpacing returns a boolean if a field has been set.

### GetBorder

`func (o *TableContentBlock) GetBorder() int32`

GetBorder returns the Border field if non-nil, zero value otherwise.

### GetBorderOk

`func (o *TableContentBlock) GetBorderOk() (*int32, bool)`

GetBorderOk returns a tuple with the Border field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBorder

`func (o *TableContentBlock) SetBorder(v int32)`

SetBorder sets Border field to given value.

### HasBorder

`func (o *TableContentBlock) HasBorder() bool`

HasBorder returns a boolean if a field has been set.

### GetTableRows

`func (o *TableContentBlock) GetTableRows() []TableRow`

GetTableRows returns the TableRows field if non-nil, zero value otherwise.

### GetTableRowsOk

`func (o *TableContentBlock) GetTableRowsOk() (*[]TableRow, bool)`

GetTableRowsOk returns a tuple with the TableRows field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTableRows

`func (o *TableContentBlock) SetTableRows(v []TableRow)`

SetTableRows sets TableRows field to given value.

### HasTableRows

`func (o *TableContentBlock) HasTableRows() bool`

HasTableRows returns a boolean if a field has been set.

### GetType

`func (o *TableContentBlock) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TableContentBlock) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TableContentBlock) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *TableContentBlock) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


