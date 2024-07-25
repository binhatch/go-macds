# TranslationDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Language** | Pointer to **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | [optional] 
**Text** | Pointer to **string** | Text | [optional] 

## Methods

### NewTranslationDTO

`func NewTranslationDTO() *TranslationDTO`

NewTranslationDTO instantiates a new TranslationDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTranslationDTOWithDefaults

`func NewTranslationDTOWithDefaults() *TranslationDTO`

NewTranslationDTOWithDefaults instantiates a new TranslationDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLanguage

`func (o *TranslationDTO) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *TranslationDTO) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *TranslationDTO) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *TranslationDTO) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetText

`func (o *TranslationDTO) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *TranslationDTO) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *TranslationDTO) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *TranslationDTO) HasText() bool`

HasText returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


