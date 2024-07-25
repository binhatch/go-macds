# Value

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Id | [optional] 
**TextReference** | Pointer to [**TranslationContainer**](TranslationContainer.md) |  | [optional] 

## Methods

### NewValue

`func NewValue() *Value`

NewValue instantiates a new Value object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValueWithDefaults

`func NewValueWithDefaults() *Value`

NewValueWithDefaults instantiates a new Value object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Value) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Value) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Value) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Value) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTextReference

`func (o *Value) GetTextReference() TranslationContainer`

GetTextReference returns the TextReference field if non-nil, zero value otherwise.

### GetTextReferenceOk

`func (o *Value) GetTextReferenceOk() (*TranslationContainer, bool)`

GetTextReferenceOk returns a tuple with the TextReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTextReference

`func (o *Value) SetTextReference(v TranslationContainer)`

SetTextReference sets TextReference field to given value.

### HasTextReference

`func (o *Value) HasTextReference() bool`

HasTextReference returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


