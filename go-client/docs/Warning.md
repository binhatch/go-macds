# Warning

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Image** | Pointer to **string** | Image url | [optional] 
**Language** | Pointer to **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | [optional] 
**Title** | Pointer to **string** | Warning title | [optional] 
**Text** | Pointer to **string** | Warning text | [optional] 

## Methods

### NewWarning

`func NewWarning() *Warning`

NewWarning instantiates a new Warning object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWarningWithDefaults

`func NewWarningWithDefaults() *Warning`

NewWarningWithDefaults instantiates a new Warning object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetImage

`func (o *Warning) GetImage() string`

GetImage returns the Image field if non-nil, zero value otherwise.

### GetImageOk

`func (o *Warning) GetImageOk() (*string, bool)`

GetImageOk returns a tuple with the Image field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImage

`func (o *Warning) SetImage(v string)`

SetImage sets Image field to given value.

### HasImage

`func (o *Warning) HasImage() bool`

HasImage returns a boolean if a field has been set.

### GetLanguage

`func (o *Warning) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *Warning) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *Warning) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *Warning) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetTitle

`func (o *Warning) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Warning) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Warning) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *Warning) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetText

`func (o *Warning) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *Warning) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *Warning) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *Warning) HasText() bool`

HasText returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


