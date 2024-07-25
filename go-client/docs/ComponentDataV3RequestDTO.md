# ComponentDataV3RequestDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ktype** | **int32** | KType | 
**Language** | **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | 
**SystemIdent** | **string** | System identification | 
**ComponentId** | **int32** | Component Id | 
**YearFrom** | Pointer to **string** | Year From | [optional] 
**YearTo** | Pointer to **string** | Year To | [optional] 
**EngineCode** | Pointer to **string** | Engine Code | [optional] 

## Methods

### NewComponentDataV3RequestDTO

`func NewComponentDataV3RequestDTO(ktype int32, language string, systemIdent string, componentId int32, ) *ComponentDataV3RequestDTO`

NewComponentDataV3RequestDTO instantiates a new ComponentDataV3RequestDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComponentDataV3RequestDTOWithDefaults

`func NewComponentDataV3RequestDTOWithDefaults() *ComponentDataV3RequestDTO`

NewComponentDataV3RequestDTOWithDefaults instantiates a new ComponentDataV3RequestDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKtype

`func (o *ComponentDataV3RequestDTO) GetKtype() int32`

GetKtype returns the Ktype field if non-nil, zero value otherwise.

### GetKtypeOk

`func (o *ComponentDataV3RequestDTO) GetKtypeOk() (*int32, bool)`

GetKtypeOk returns a tuple with the Ktype field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKtype

`func (o *ComponentDataV3RequestDTO) SetKtype(v int32)`

SetKtype sets Ktype field to given value.


### GetLanguage

`func (o *ComponentDataV3RequestDTO) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *ComponentDataV3RequestDTO) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *ComponentDataV3RequestDTO) SetLanguage(v string)`

SetLanguage sets Language field to given value.


### GetSystemIdent

`func (o *ComponentDataV3RequestDTO) GetSystemIdent() string`

GetSystemIdent returns the SystemIdent field if non-nil, zero value otherwise.

### GetSystemIdentOk

`func (o *ComponentDataV3RequestDTO) GetSystemIdentOk() (*string, bool)`

GetSystemIdentOk returns a tuple with the SystemIdent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemIdent

`func (o *ComponentDataV3RequestDTO) SetSystemIdent(v string)`

SetSystemIdent sets SystemIdent field to given value.


### GetComponentId

`func (o *ComponentDataV3RequestDTO) GetComponentId() int32`

GetComponentId returns the ComponentId field if non-nil, zero value otherwise.

### GetComponentIdOk

`func (o *ComponentDataV3RequestDTO) GetComponentIdOk() (*int32, bool)`

GetComponentIdOk returns a tuple with the ComponentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentId

`func (o *ComponentDataV3RequestDTO) SetComponentId(v int32)`

SetComponentId sets ComponentId field to given value.


### GetYearFrom

`func (o *ComponentDataV3RequestDTO) GetYearFrom() string`

GetYearFrom returns the YearFrom field if non-nil, zero value otherwise.

### GetYearFromOk

`func (o *ComponentDataV3RequestDTO) GetYearFromOk() (*string, bool)`

GetYearFromOk returns a tuple with the YearFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearFrom

`func (o *ComponentDataV3RequestDTO) SetYearFrom(v string)`

SetYearFrom sets YearFrom field to given value.

### HasYearFrom

`func (o *ComponentDataV3RequestDTO) HasYearFrom() bool`

HasYearFrom returns a boolean if a field has been set.

### GetYearTo

`func (o *ComponentDataV3RequestDTO) GetYearTo() string`

GetYearTo returns the YearTo field if non-nil, zero value otherwise.

### GetYearToOk

`func (o *ComponentDataV3RequestDTO) GetYearToOk() (*string, bool)`

GetYearToOk returns a tuple with the YearTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearTo

`func (o *ComponentDataV3RequestDTO) SetYearTo(v string)`

SetYearTo sets YearTo field to given value.

### HasYearTo

`func (o *ComponentDataV3RequestDTO) HasYearTo() bool`

HasYearTo returns a boolean if a field has been set.

### GetEngineCode

`func (o *ComponentDataV3RequestDTO) GetEngineCode() string`

GetEngineCode returns the EngineCode field if non-nil, zero value otherwise.

### GetEngineCodeOk

`func (o *ComponentDataV3RequestDTO) GetEngineCodeOk() (*string, bool)`

GetEngineCodeOk returns a tuple with the EngineCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCode

`func (o *ComponentDataV3RequestDTO) SetEngineCode(v string)`

SetEngineCode sets EngineCode field to given value.

### HasEngineCode

`func (o *ComponentDataV3RequestDTO) HasEngineCode() bool`

HasEngineCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


