# TextReference

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int64** | Id | [optional] 
**Text** | Pointer to **string** | Text | [optional] 

## Methods

### NewTextReference

`func NewTextReference() *TextReference`

NewTextReference instantiates a new TextReference object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTextReferenceWithDefaults

`func NewTextReferenceWithDefaults() *TextReference`

NewTextReferenceWithDefaults instantiates a new TextReference object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TextReference) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TextReference) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TextReference) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *TextReference) HasId() bool`

HasId returns a boolean if a field has been set.

### GetText

`func (o *TextReference) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *TextReference) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *TextReference) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *TextReference) HasText() bool`

HasText returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


