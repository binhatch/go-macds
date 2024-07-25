# TableRow

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Order** | Pointer to **int32** | Order | [optional] 
**TableColumns** | Pointer to [**[]TableColumn**](TableColumn.md) | List of Table Columns | [optional] 

## Methods

### NewTableRow

`func NewTableRow() *TableRow`

NewTableRow instantiates a new TableRow object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTableRowWithDefaults

`func NewTableRowWithDefaults() *TableRow`

NewTableRowWithDefaults instantiates a new TableRow object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrder

`func (o *TableRow) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *TableRow) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *TableRow) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *TableRow) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetTableColumns

`func (o *TableRow) GetTableColumns() []TableColumn`

GetTableColumns returns the TableColumns field if non-nil, zero value otherwise.

### GetTableColumnsOk

`func (o *TableRow) GetTableColumnsOk() (*[]TableColumn, bool)`

GetTableColumnsOk returns a tuple with the TableColumns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTableColumns

`func (o *TableRow) SetTableColumns(v []TableColumn)`

SetTableColumns sets TableColumns field to given value.

### HasTableColumns

`func (o *TableRow) HasTableColumns() bool`

HasTableColumns returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


