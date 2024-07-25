# TranslationContainer

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Id | [optional] 
**Text** | Pointer to [**Translation**](Translation.md) |  | [optional] 

## Methods

### NewTranslationContainer

`func NewTranslationContainer() *TranslationContainer`

NewTranslationContainer instantiates a new TranslationContainer object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTranslationContainerWithDefaults

`func NewTranslationContainerWithDefaults() *TranslationContainer`

NewTranslationContainerWithDefaults instantiates a new TranslationContainer object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TranslationContainer) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TranslationContainer) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TranslationContainer) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *TranslationContainer) HasId() bool`

HasId returns a boolean if a field has been set.

### GetText

`func (o *TranslationContainer) GetText() Translation`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *TranslationContainer) GetTextOk() (*Translation, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *TranslationContainer) SetText(v Translation)`

SetText sets Text field to given value.

### HasText

`func (o *TranslationContainer) HasText() bool`

HasText returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


