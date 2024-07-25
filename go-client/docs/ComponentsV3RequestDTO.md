# ComponentsV3RequestDTO

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

### NewComponentsV3RequestDTO

`func NewComponentsV3RequestDTO(ktype int32, language string, ) *ComponentsV3RequestDTO`

NewComponentsV3RequestDTO instantiates a new ComponentsV3RequestDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComponentsV3RequestDTOWithDefaults

`func NewComponentsV3RequestDTOWithDefaults() *ComponentsV3RequestDTO`

NewComponentsV3RequestDTOWithDefaults instantiates a new ComponentsV3RequestDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKtype

`func (o *ComponentsV3RequestDTO) GetKtype() int32`

GetKtype returns the Ktype field if non-nil, zero value otherwise.

### GetKtypeOk

`func (o *ComponentsV3RequestDTO) GetKtypeOk() (*int32, bool)`

GetKtypeOk returns a tuple with the Ktype field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKtype

`func (o *ComponentsV3RequestDTO) SetKtype(v int32)`

SetKtype sets Ktype field to given value.


### GetLanguage

`func (o *ComponentsV3RequestDTO) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *ComponentsV3RequestDTO) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *ComponentsV3RequestDTO) SetLanguage(v string)`

SetLanguage sets Language field to given value.


### GetSystemIdent

`func (o *ComponentsV3RequestDTO) GetSystemIdent() string`

GetSystemIdent returns the SystemIdent field if non-nil, zero value otherwise.

### GetSystemIdentOk

`func (o *ComponentsV3RequestDTO) GetSystemIdentOk() (*string, bool)`

GetSystemIdentOk returns a tuple with the SystemIdent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemIdent

`func (o *ComponentsV3RequestDTO) SetSystemIdent(v string)`

SetSystemIdent sets SystemIdent field to given value.

### HasSystemIdent

`func (o *ComponentsV3RequestDTO) HasSystemIdent() bool`

HasSystemIdent returns a boolean if a field has been set.

### GetYearFrom

`func (o *ComponentsV3RequestDTO) GetYearFrom() string`

GetYearFrom returns the YearFrom field if non-nil, zero value otherwise.

### GetYearFromOk

`func (o *ComponentsV3RequestDTO) GetYearFromOk() (*string, bool)`

GetYearFromOk returns a tuple with the YearFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearFrom

`func (o *ComponentsV3RequestDTO) SetYearFrom(v string)`

SetYearFrom sets YearFrom field to given value.

### HasYearFrom

`func (o *ComponentsV3RequestDTO) HasYearFrom() bool`

HasYearFrom returns a boolean if a field has been set.

### GetYearTo

`func (o *ComponentsV3RequestDTO) GetYearTo() string`

GetYearTo returns the YearTo field if non-nil, zero value otherwise.

### GetYearToOk

`func (o *ComponentsV3RequestDTO) GetYearToOk() (*string, bool)`

GetYearToOk returns a tuple with the YearTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearTo

`func (o *ComponentsV3RequestDTO) SetYearTo(v string)`

SetYearTo sets YearTo field to given value.

### HasYearTo

`func (o *ComponentsV3RequestDTO) HasYearTo() bool`

HasYearTo returns a boolean if a field has been set.

### GetEngineCode

`func (o *ComponentsV3RequestDTO) GetEngineCode() string`

GetEngineCode returns the EngineCode field if non-nil, zero value otherwise.

### GetEngineCodeOk

`func (o *ComponentsV3RequestDTO) GetEngineCodeOk() (*string, bool)`

GetEngineCodeOk returns a tuple with the EngineCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCode

`func (o *ComponentsV3RequestDTO) SetEngineCode(v string)`

SetEngineCode sets EngineCode field to given value.

### HasEngineCode

`func (o *ComponentsV3RequestDTO) HasEngineCode() bool`

HasEngineCode returns a boolean if a field has been set.

### GetComponentIds

`func (o *ComponentsV3RequestDTO) GetComponentIds() []int32`

GetComponentIds returns the ComponentIds field if non-nil, zero value otherwise.

### GetComponentIdsOk

`func (o *ComponentsV3RequestDTO) GetComponentIdsOk() (*[]int32, bool)`

GetComponentIdsOk returns a tuple with the ComponentIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentIds

`func (o *ComponentsV3RequestDTO) SetComponentIds(v []int32)`

SetComponentIds sets ComponentIds field to given value.

### HasComponentIds

`func (o *ComponentsV3RequestDTO) HasComponentIds() bool`

HasComponentIds returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


