# IdTranslation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int64** | Id | [optional] 
**Translations** | Pointer to [**Translation**](Translation.md) |  | [optional] 

## Methods

### NewIdTranslation

`func NewIdTranslation() *IdTranslation`

NewIdTranslation instantiates a new IdTranslation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIdTranslationWithDefaults

`func NewIdTranslationWithDefaults() *IdTranslation`

NewIdTranslationWithDefaults instantiates a new IdTranslation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *IdTranslation) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *IdTranslation) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *IdTranslation) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *IdTranslation) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTranslations

`func (o *IdTranslation) GetTranslations() Translation`

GetTranslations returns the Translations field if non-nil, zero value otherwise.

### GetTranslationsOk

`func (o *IdTranslation) GetTranslationsOk() (*Translation, bool)`

GetTranslationsOk returns a tuple with the Translations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTranslations

`func (o *IdTranslation) SetTranslations(v Translation)`

SetTranslations sets Translations field to given value.

### HasTranslations

`func (o *IdTranslation) HasTranslations() bool`

HasTranslations returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


