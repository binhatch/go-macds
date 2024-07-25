# ComponentNameDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Id | [optional] 
**Language** | Pointer to **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | [optional] 
**Text** | Pointer to **string** | System text | [optional] 

## Methods

### NewComponentNameDTO

`func NewComponentNameDTO() *ComponentNameDTO`

NewComponentNameDTO instantiates a new ComponentNameDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComponentNameDTOWithDefaults

`func NewComponentNameDTOWithDefaults() *ComponentNameDTO`

NewComponentNameDTOWithDefaults instantiates a new ComponentNameDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ComponentNameDTO) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ComponentNameDTO) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ComponentNameDTO) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ComponentNameDTO) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLanguage

`func (o *ComponentNameDTO) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *ComponentNameDTO) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *ComponentNameDTO) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *ComponentNameDTO) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetText

`func (o *ComponentNameDTO) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *ComponentNameDTO) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *ComponentNameDTO) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *ComponentNameDTO) HasText() bool`

HasText returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


