# TableColumn

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Order** | Pointer to **int32** | Order | [optional] 
**Width** | Pointer to **string** | Width | [optional] 

## Methods

### NewTableColumn

`func NewTableColumn() *TableColumn`

NewTableColumn instantiates a new TableColumn object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTableColumnWithDefaults

`func NewTableColumnWithDefaults() *TableColumn`

NewTableColumnWithDefaults instantiates a new TableColumn object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrder

`func (o *TableColumn) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *TableColumn) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *TableColumn) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *TableColumn) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetWidth

`func (o *TableColumn) GetWidth() string`

GetWidth returns the Width field if non-nil, zero value otherwise.

### GetWidthOk

`func (o *TableColumn) GetWidthOk() (*string, bool)`

GetWidthOk returns a tuple with the Width field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWidth

`func (o *TableColumn) SetWidth(v string)`

SetWidth sets Width field to given value.

### HasWidth

`func (o *TableColumn) HasWidth() bool`

HasWidth returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


