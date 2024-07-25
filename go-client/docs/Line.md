# Line

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int64** | Id | [optional] 
**Order** | Pointer to **int64** | Order | [optional] 
**TextReference** | Pointer to [**IdTranslation**](IdTranslation.md) |  | [optional] 
**IsListItem** | Pointer to **bool** | Is List Item | [optional] 

## Methods

### NewLine

`func NewLine() *Line`

NewLine instantiates a new Line object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLineWithDefaults

`func NewLineWithDefaults() *Line`

NewLineWithDefaults instantiates a new Line object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Line) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Line) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Line) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *Line) HasId() bool`

HasId returns a boolean if a field has been set.

### GetOrder

`func (o *Line) GetOrder() int64`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *Line) GetOrderOk() (*int64, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *Line) SetOrder(v int64)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *Line) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetTextReference

`func (o *Line) GetTextReference() IdTranslation`

GetTextReference returns the TextReference field if non-nil, zero value otherwise.

### GetTextReferenceOk

`func (o *Line) GetTextReferenceOk() (*IdTranslation, bool)`

GetTextReferenceOk returns a tuple with the TextReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTextReference

`func (o *Line) SetTextReference(v IdTranslation)`

SetTextReference sets TextReference field to given value.

### HasTextReference

`func (o *Line) HasTextReference() bool`

HasTextReference returns a boolean if a field has been set.

### GetIsListItem

`func (o *Line) GetIsListItem() bool`

GetIsListItem returns the IsListItem field if non-nil, zero value otherwise.

### GetIsListItemOk

`func (o *Line) GetIsListItemOk() (*bool, bool)`

GetIsListItemOk returns a tuple with the IsListItem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsListItem

`func (o *Line) SetIsListItem(v bool)`

SetIsListItem sets IsListItem field to given value.

### HasIsListItem

`func (o *Line) HasIsListItem() bool`

HasIsListItem returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


