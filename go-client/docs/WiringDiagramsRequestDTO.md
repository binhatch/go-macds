# WiringDiagramsRequestDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Language** | **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | 
**HgsManufId** | Pointer to **string** | HGS Manufacturer Id | [optional] 
**HgsModelId** | Pointer to **string** | HGS Model Id | [optional] 
**EngineCode** | Pointer to **string** | Engine Code | [optional] 
**EngineKw** | Pointer to **string** | Engine kW | [optional] 
**ProductionYear** | Pointer to **string** | Production Year | [optional] 
**RegionCode** | Pointer to **string** | Region Code | [optional] 
**KType** | **string** | kType | 

## Methods

### NewWiringDiagramsRequestDTO

`func NewWiringDiagramsRequestDTO(language string, kType string, ) *WiringDiagramsRequestDTO`

NewWiringDiagramsRequestDTO instantiates a new WiringDiagramsRequestDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWiringDiagramsRequestDTOWithDefaults

`func NewWiringDiagramsRequestDTOWithDefaults() *WiringDiagramsRequestDTO`

NewWiringDiagramsRequestDTOWithDefaults instantiates a new WiringDiagramsRequestDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLanguage

`func (o *WiringDiagramsRequestDTO) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *WiringDiagramsRequestDTO) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *WiringDiagramsRequestDTO) SetLanguage(v string)`

SetLanguage sets Language field to given value.


### GetHgsManufId

`func (o *WiringDiagramsRequestDTO) GetHgsManufId() string`

GetHgsManufId returns the HgsManufId field if non-nil, zero value otherwise.

### GetHgsManufIdOk

`func (o *WiringDiagramsRequestDTO) GetHgsManufIdOk() (*string, bool)`

GetHgsManufIdOk returns a tuple with the HgsManufId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHgsManufId

`func (o *WiringDiagramsRequestDTO) SetHgsManufId(v string)`

SetHgsManufId sets HgsManufId field to given value.

### HasHgsManufId

`func (o *WiringDiagramsRequestDTO) HasHgsManufId() bool`

HasHgsManufId returns a boolean if a field has been set.

### GetHgsModelId

`func (o *WiringDiagramsRequestDTO) GetHgsModelId() string`

GetHgsModelId returns the HgsModelId field if non-nil, zero value otherwise.

### GetHgsModelIdOk

`func (o *WiringDiagramsRequestDTO) GetHgsModelIdOk() (*string, bool)`

GetHgsModelIdOk returns a tuple with the HgsModelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHgsModelId

`func (o *WiringDiagramsRequestDTO) SetHgsModelId(v string)`

SetHgsModelId sets HgsModelId field to given value.

### HasHgsModelId

`func (o *WiringDiagramsRequestDTO) HasHgsModelId() bool`

HasHgsModelId returns a boolean if a field has been set.

### GetEngineCode

`func (o *WiringDiagramsRequestDTO) GetEngineCode() string`

GetEngineCode returns the EngineCode field if non-nil, zero value otherwise.

### GetEngineCodeOk

`func (o *WiringDiagramsRequestDTO) GetEngineCodeOk() (*string, bool)`

GetEngineCodeOk returns a tuple with the EngineCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCode

`func (o *WiringDiagramsRequestDTO) SetEngineCode(v string)`

SetEngineCode sets EngineCode field to given value.

### HasEngineCode

`func (o *WiringDiagramsRequestDTO) HasEngineCode() bool`

HasEngineCode returns a boolean if a field has been set.

### GetEngineKw

`func (o *WiringDiagramsRequestDTO) GetEngineKw() string`

GetEngineKw returns the EngineKw field if non-nil, zero value otherwise.

### GetEngineKwOk

`func (o *WiringDiagramsRequestDTO) GetEngineKwOk() (*string, bool)`

GetEngineKwOk returns a tuple with the EngineKw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineKw

`func (o *WiringDiagramsRequestDTO) SetEngineKw(v string)`

SetEngineKw sets EngineKw field to given value.

### HasEngineKw

`func (o *WiringDiagramsRequestDTO) HasEngineKw() bool`

HasEngineKw returns a boolean if a field has been set.

### GetProductionYear

`func (o *WiringDiagramsRequestDTO) GetProductionYear() string`

GetProductionYear returns the ProductionYear field if non-nil, zero value otherwise.

### GetProductionYearOk

`func (o *WiringDiagramsRequestDTO) GetProductionYearOk() (*string, bool)`

GetProductionYearOk returns a tuple with the ProductionYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionYear

`func (o *WiringDiagramsRequestDTO) SetProductionYear(v string)`

SetProductionYear sets ProductionYear field to given value.

### HasProductionYear

`func (o *WiringDiagramsRequestDTO) HasProductionYear() bool`

HasProductionYear returns a boolean if a field has been set.

### GetRegionCode

`func (o *WiringDiagramsRequestDTO) GetRegionCode() string`

GetRegionCode returns the RegionCode field if non-nil, zero value otherwise.

### GetRegionCodeOk

`func (o *WiringDiagramsRequestDTO) GetRegionCodeOk() (*string, bool)`

GetRegionCodeOk returns a tuple with the RegionCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionCode

`func (o *WiringDiagramsRequestDTO) SetRegionCode(v string)`

SetRegionCode sets RegionCode field to given value.

### HasRegionCode

`func (o *WiringDiagramsRequestDTO) HasRegionCode() bool`

HasRegionCode returns a boolean if a field has been set.

### GetKType

`func (o *WiringDiagramsRequestDTO) GetKType() string`

GetKType returns the KType field if non-nil, zero value otherwise.

### GetKTypeOk

`func (o *WiringDiagramsRequestDTO) GetKTypeOk() (*string, bool)`

GetKTypeOk returns a tuple with the KType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKType

`func (o *WiringDiagramsRequestDTO) SetKType(v string)`

SetKType sets KType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


