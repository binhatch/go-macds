# NameReference

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TextReference** | Pointer to [**TextReference**](TextReference.md) |  | [optional] 
**Order** | Pointer to **int32** | Order | [optional] 

## Methods

### NewNameReference

`func NewNameReference() *NameReference`

NewNameReference instantiates a new NameReference object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewNameReferenceWithDefaults

`func NewNameReferenceWithDefaults() *NameReference`

NewNameReferenceWithDefaults instantiates a new NameReference object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTextReference

`func (o *NameReference) GetTextReference() TextReference`

GetTextReference returns the TextReference field if non-nil, zero value otherwise.

### GetTextReferenceOk

`func (o *NameReference) GetTextReferenceOk() (*TextReference, bool)`

GetTextReferenceOk returns a tuple with the TextReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTextReference

`func (o *NameReference) SetTextReference(v TextReference)`

SetTextReference sets TextReference field to given value.

### HasTextReference

`func (o *NameReference) HasTextReference() bool`

HasTextReference returns a boolean if a field has been set.

### GetOrder

`func (o *NameReference) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *NameReference) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *NameReference) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *NameReference) HasOrder() bool`

HasOrder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


