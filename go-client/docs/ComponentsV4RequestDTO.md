# ComponentsV4RequestDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ktype** | **int32** | KType | 
**Language** | **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | 
**SystemIdent** | Pointer to **string** | System identification | [optional] 
**YearFrom** | Pointer to **string** | Year from limit | [optional] 
**YearTo** | Pointer to **string** | Year to limit | [optional] 
**EngineCode** | Pointer to **string** | Engine Code | [optional] 
**ComponentIds** | Pointer to **[]int32** | A list of components Ids | [optional] 

## Methods

### NewComponentsV4RequestDTO

`func NewComponentsV4RequestDTO(ktype int32, language string, ) *ComponentsV4RequestDTO`

NewComponentsV4RequestDTO instantiates a new ComponentsV4RequestDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComponentsV4RequestDTOWithDefaults

`func NewComponentsV4RequestDTOWithDefaults() *ComponentsV4RequestDTO`

NewComponentsV4RequestDTOWithDefaults instantiates a new ComponentsV4RequestDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKtype

`func (o *ComponentsV4RequestDTO) GetKtype() int32`

GetKtype returns the Ktype field if non-nil, zero value otherwise.

### GetKtypeOk

`func (o *ComponentsV4RequestDTO) GetKtypeOk() (*int32, bool)`

GetKtypeOk returns a tuple with the Ktype field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKtype

`func (o *ComponentsV4RequestDTO) SetKtype(v int32)`

SetKtype sets Ktype field to given value.


### GetLanguage

`func (o *ComponentsV4RequestDTO) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *ComponentsV4RequestDTO) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *ComponentsV4RequestDTO) SetLanguage(v string)`

SetLanguage sets Language field to given value.


### GetSystemIdent

`func (o *ComponentsV4RequestDTO) GetSystemIdent() string`

GetSystemIdent returns the SystemIdent field if non-nil, zero value otherwise.

### GetSystemIdentOk

`func (o *ComponentsV4RequestDTO) GetSystemIdentOk() (*string, bool)`

GetSystemIdentOk returns a tuple with the SystemIdent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemIdent

`func (o *ComponentsV4RequestDTO) SetSystemIdent(v string)`

SetSystemIdent sets SystemIdent field to given value.

### HasSystemIdent

`func (o *ComponentsV4RequestDTO) HasSystemIdent() bool`

HasSystemIdent returns a boolean if a field has been set.

### GetYearFrom

`func (o *ComponentsV4RequestDTO) GetYearFrom() string`

GetYearFrom returns the YearFrom field if non-nil, zero value otherwise.

### GetYearFromOk

`func (o *ComponentsV4RequestDTO) GetYearFromOk() (*string, bool)`

GetYearFromOk returns a tuple with the YearFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearFrom

`func (o *ComponentsV4RequestDTO) SetYearFrom(v string)`

SetYearFrom sets YearFrom field to given value.

### HasYearFrom

`func (o *ComponentsV4RequestDTO) HasYearFrom() bool`

HasYearFrom returns a boolean if a field has been set.

### GetYearTo

`func (o *ComponentsV4RequestDTO) GetYearTo() string`

GetYearTo returns the YearTo field if non-nil, zero value otherwise.

### GetYearToOk

`func (o *ComponentsV4RequestDTO) GetYearToOk() (*string, bool)`

GetYearToOk returns a tuple with the YearTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearTo

`func (o *ComponentsV4RequestDTO) SetYearTo(v string)`

SetYearTo sets YearTo field to given value.

### HasYearTo

`func (o *ComponentsV4RequestDTO) HasYearTo() bool`

HasYearTo returns a boolean if a field has been set.

### GetEngineCode

`func (o *ComponentsV4RequestDTO) GetEngineCode() string`

GetEngineCode returns the EngineCode field if non-nil, zero value otherwise.

### GetEngineCodeOk

`func (o *ComponentsV4RequestDTO) GetEngineCodeOk() (*string, bool)`

GetEngineCodeOk returns a tuple with the EngineCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCode

`func (o *ComponentsV4RequestDTO) SetEngineCode(v string)`

SetEngineCode sets EngineCode field to given value.

### HasEngineCode

`func (o *ComponentsV4RequestDTO) HasEngineCode() bool`

HasEngineCode returns a boolean if a field has been set.

### GetComponentIds

`func (o *ComponentsV4RequestDTO) GetComponentIds() []int32`

GetComponentIds returns the ComponentIds field if non-nil, zero value otherwise.

### GetComponentIdsOk

`func (o *ComponentsV4RequestDTO) GetComponentIdsOk() (*[]int32, bool)`

GetComponentIdsOk returns a tuple with the ComponentIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentIds

`func (o *ComponentsV4RequestDTO) SetComponentIds(v []int32)`

SetComponentIds sets ComponentIds field to given value.

### HasComponentIds

`func (o *ComponentsV4RequestDTO) HasComponentIds() bool`

HasComponentIds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


