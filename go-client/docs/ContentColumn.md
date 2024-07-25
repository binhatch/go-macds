# ContentColumn

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Order** | Pointer to **int32** | Order | [optional] 
**ContentBlocks** | Pointer to [**[]ContentBlock**](ContentBlock.md) | List of Content Blocks | [optional] 

## Methods

### NewContentColumn

`func NewContentColumn() *ContentColumn`

NewContentColumn instantiates a new ContentColumn object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContentColumnWithDefaults

`func NewContentColumnWithDefaults() *ContentColumn`

NewContentColumnWithDefaults instantiates a new ContentColumn object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrder

`func (o *ContentColumn) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *ContentColumn) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *ContentColumn) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *ContentColumn) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetContentBlocks

`func (o *ContentColumn) GetContentBlocks() []ContentBlock`

GetContentBlocks returns the ContentBlocks field if non-nil, zero value otherwise.

### GetContentBlocksOk

`func (o *ContentColumn) GetContentBlocksOk() (*[]ContentBlock, bool)`

GetContentBlocksOk returns a tuple with the ContentBlocks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentBlocks

`func (o *ContentColumn) SetContentBlocks(v []ContentBlock)`

SetContentBlocks sets ContentBlocks field to given value.

### HasContentBlocks

`func (o *ContentColumn) HasContentBlocks() bool`

HasContentBlocks returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


