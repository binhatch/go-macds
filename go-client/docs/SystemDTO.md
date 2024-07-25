# SystemDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SystemIdent** | Pointer to **string** | System identification | [optional] 
**Language** | Pointer to **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | [optional] 
**Text** | Pointer to **string** | System text | [optional] 

## Methods

### NewSystemDTO

`func NewSystemDTO() *SystemDTO`

NewSystemDTO instantiates a new SystemDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemDTOWithDefaults

`func NewSystemDTOWithDefaults() *SystemDTO`

NewSystemDTOWithDefaults instantiates a new SystemDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSystemIdent

`func (o *SystemDTO) GetSystemIdent() string`

GetSystemIdent returns the SystemIdent field if non-nil, zero value otherwise.

### GetSystemIdentOk

`func (o *SystemDTO) GetSystemIdentOk() (*string, bool)`

GetSystemIdentOk returns a tuple with the SystemIdent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemIdent

`func (o *SystemDTO) SetSystemIdent(v string)`

SetSystemIdent sets SystemIdent field to given value.

### HasSystemIdent

`func (o *SystemDTO) HasSystemIdent() bool`

HasSystemIdent returns a boolean if a field has been set.

### GetLanguage

`func (o *SystemDTO) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *SystemDTO) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *SystemDTO) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *SystemDTO) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetText

`func (o *SystemDTO) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *SystemDTO) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *SystemDTO) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *SystemDTO) HasText() bool`

HasText returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


