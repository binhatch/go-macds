# TextTranslation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Language** | Pointer to **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | [optional] 
**SystemName** | Pointer to **string** | Textual representation of a wiring diagram. May be concatenated with the date properties &#39;from&#39; and &#39;to&#39;, if existent. May be &#39;null&#39; in which case it is the default wiring of the related system group. | [optional] 

## Methods

### NewTextTranslation

`func NewTextTranslation() *TextTranslation`

NewTextTranslation instantiates a new TextTranslation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTextTranslationWithDefaults

`func NewTextTranslationWithDefaults() *TextTranslation`

NewTextTranslationWithDefaults instantiates a new TextTranslation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLanguage

`func (o *TextTranslation) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *TextTranslation) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *TextTranslation) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *TextTranslation) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetSystemName

`func (o *TextTranslation) GetSystemName() string`

GetSystemName returns the SystemName field if non-nil, zero value otherwise.

### GetSystemNameOk

`func (o *TextTranslation) GetSystemNameOk() (*string, bool)`

GetSystemNameOk returns a tuple with the SystemName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemName

`func (o *TextTranslation) SetSystemName(v string)`

SetSystemName sets SystemName field to given value.

### HasSystemName

`func (o *TextTranslation) HasSystemName() bool`

HasSystemName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


