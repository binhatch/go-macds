# InspectionsRequestDTO

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
**Preview** | Pointer to **string** | Preview | [optional] 
**Mileage** | Pointer to **int32** | Optional; Current mileage of the vehicle to calculate the next due service. (Is tied to \&quot;dateProduction\&quot;) | [optional] 
**DateProduction** | Pointer to **string** | Optional; date of the production (or first registration) of the vehicle to calculate the next due service. (Is tied to \&quot;mileage\&quot;) | [optional] 
**MileageLastService** | Pointer to **int32** | Optional; mileage of when the last service was done; If not provided, the assumption is that no service was done so far. | [optional] 
**DateLastService** | Pointer to **string** | Optional; date of when the last service was done; If not provided, the assumption is that no service was done so far. | [optional] 
**ServiceIds** | **[]int32** | Service Ids | 
**KType** | **string** | KType | 

## Methods

### NewInspectionsRequestDTO

`func NewInspectionsRequestDTO(language string, serviceIds []int32, kType string, ) *InspectionsRequestDTO`

NewInspectionsRequestDTO instantiates a new InspectionsRequestDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInspectionsRequestDTOWithDefaults

`func NewInspectionsRequestDTOWithDefaults() *InspectionsRequestDTO`

NewInspectionsRequestDTOWithDefaults instantiates a new InspectionsRequestDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLanguage

`func (o *InspectionsRequestDTO) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *InspectionsRequestDTO) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *InspectionsRequestDTO) SetLanguage(v string)`

SetLanguage sets Language field to given value.


### GetHgsManufId

`func (o *InspectionsRequestDTO) GetHgsManufId() string`

GetHgsManufId returns the HgsManufId field if non-nil, zero value otherwise.

### GetHgsManufIdOk

`func (o *InspectionsRequestDTO) GetHgsManufIdOk() (*string, bool)`

GetHgsManufIdOk returns a tuple with the HgsManufId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHgsManufId

`func (o *InspectionsRequestDTO) SetHgsManufId(v string)`

SetHgsManufId sets HgsManufId field to given value.

### HasHgsManufId

`func (o *InspectionsRequestDTO) HasHgsManufId() bool`

HasHgsManufId returns a boolean if a field has been set.

### GetHgsModelId

`func (o *InspectionsRequestDTO) GetHgsModelId() string`

GetHgsModelId returns the HgsModelId field if non-nil, zero value otherwise.

### GetHgsModelIdOk

`func (o *InspectionsRequestDTO) GetHgsModelIdOk() (*string, bool)`

GetHgsModelIdOk returns a tuple with the HgsModelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHgsModelId

`func (o *InspectionsRequestDTO) SetHgsModelId(v string)`

SetHgsModelId sets HgsModelId field to given value.

### HasHgsModelId

`func (o *InspectionsRequestDTO) HasHgsModelId() bool`

HasHgsModelId returns a boolean if a field has been set.

### GetEngineCode

`func (o *InspectionsRequestDTO) GetEngineCode() string`

GetEngineCode returns the EngineCode field if non-nil, zero value otherwise.

### GetEngineCodeOk

`func (o *InspectionsRequestDTO) GetEngineCodeOk() (*string, bool)`

GetEngineCodeOk returns a tuple with the EngineCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCode

`func (o *InspectionsRequestDTO) SetEngineCode(v string)`

SetEngineCode sets EngineCode field to given value.

### HasEngineCode

`func (o *InspectionsRequestDTO) HasEngineCode() bool`

HasEngineCode returns a boolean if a field has been set.

### GetEngineKw

`func (o *InspectionsRequestDTO) GetEngineKw() string`

GetEngineKw returns the EngineKw field if non-nil, zero value otherwise.

### GetEngineKwOk

`func (o *InspectionsRequestDTO) GetEngineKwOk() (*string, bool)`

GetEngineKwOk returns a tuple with the EngineKw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineKw

`func (o *InspectionsRequestDTO) SetEngineKw(v string)`

SetEngineKw sets EngineKw field to given value.

### HasEngineKw

`func (o *InspectionsRequestDTO) HasEngineKw() bool`

HasEngineKw returns a boolean if a field has been set.

### GetProductionYear

`func (o *InspectionsRequestDTO) GetProductionYear() string`

GetProductionYear returns the ProductionYear field if non-nil, zero value otherwise.

### GetProductionYearOk

`func (o *InspectionsRequestDTO) GetProductionYearOk() (*string, bool)`

GetProductionYearOk returns a tuple with the ProductionYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionYear

`func (o *InspectionsRequestDTO) SetProductionYear(v string)`

SetProductionYear sets ProductionYear field to given value.

### HasProductionYear

`func (o *InspectionsRequestDTO) HasProductionYear() bool`

HasProductionYear returns a boolean if a field has been set.

### GetRegionCode

`func (o *InspectionsRequestDTO) GetRegionCode() string`

GetRegionCode returns the RegionCode field if non-nil, zero value otherwise.

### GetRegionCodeOk

`func (o *InspectionsRequestDTO) GetRegionCodeOk() (*string, bool)`

GetRegionCodeOk returns a tuple with the RegionCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionCode

`func (o *InspectionsRequestDTO) SetRegionCode(v string)`

SetRegionCode sets RegionCode field to given value.

### HasRegionCode

`func (o *InspectionsRequestDTO) HasRegionCode() bool`

HasRegionCode returns a boolean if a field has been set.

### GetPreview

`func (o *InspectionsRequestDTO) GetPreview() string`

GetPreview returns the Preview field if non-nil, zero value otherwise.

### GetPreviewOk

`func (o *InspectionsRequestDTO) GetPreviewOk() (*string, bool)`

GetPreviewOk returns a tuple with the Preview field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreview

`func (o *InspectionsRequestDTO) SetPreview(v string)`

SetPreview sets Preview field to given value.

### HasPreview

`func (o *InspectionsRequestDTO) HasPreview() bool`

HasPreview returns a boolean if a field has been set.

### GetMileage

`func (o *InspectionsRequestDTO) GetMileage() int32`

GetMileage returns the Mileage field if non-nil, zero value otherwise.

### GetMileageOk

`func (o *InspectionsRequestDTO) GetMileageOk() (*int32, bool)`

GetMileageOk returns a tuple with the Mileage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMileage

`func (o *InspectionsRequestDTO) SetMileage(v int32)`

SetMileage sets Mileage field to given value.

### HasMileage

`func (o *InspectionsRequestDTO) HasMileage() bool`

HasMileage returns a boolean if a field has been set.

### GetDateProduction

`func (o *InspectionsRequestDTO) GetDateProduction() string`

GetDateProduction returns the DateProduction field if non-nil, zero value otherwise.

### GetDateProductionOk

`func (o *InspectionsRequestDTO) GetDateProductionOk() (*string, bool)`

GetDateProductionOk returns a tuple with the DateProduction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateProduction

`func (o *InspectionsRequestDTO) SetDateProduction(v string)`

SetDateProduction sets DateProduction field to given value.

### HasDateProduction

`func (o *InspectionsRequestDTO) HasDateProduction() bool`

HasDateProduction returns a boolean if a field has been set.

### GetMileageLastService

`func (o *InspectionsRequestDTO) GetMileageLastService() int32`

GetMileageLastService returns the MileageLastService field if non-nil, zero value otherwise.

### GetMileageLastServiceOk

`func (o *InspectionsRequestDTO) GetMileageLastServiceOk() (*int32, bool)`

GetMileageLastServiceOk returns a tuple with the MileageLastService field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMileageLastService

`func (o *InspectionsRequestDTO) SetMileageLastService(v int32)`

SetMileageLastService sets MileageLastService field to given value.

### HasMileageLastService

`func (o *InspectionsRequestDTO) HasMileageLastService() bool`

HasMileageLastService returns a boolean if a field has been set.

### GetDateLastService

`func (o *InspectionsRequestDTO) GetDateLastService() string`

GetDateLastService returns the DateLastService field if non-nil, zero value otherwise.

### GetDateLastServiceOk

`func (o *InspectionsRequestDTO) GetDateLastServiceOk() (*string, bool)`

GetDateLastServiceOk returns a tuple with the DateLastService field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateLastService

`func (o *InspectionsRequestDTO) SetDateLastService(v string)`

SetDateLastService sets DateLastService field to given value.

### HasDateLastService

`func (o *InspectionsRequestDTO) HasDateLastService() bool`

HasDateLastService returns a boolean if a field has been set.

### GetServiceIds

`func (o *InspectionsRequestDTO) GetServiceIds() []int32`

GetServiceIds returns the ServiceIds field if non-nil, zero value otherwise.

### GetServiceIdsOk

`func (o *InspectionsRequestDTO) GetServiceIdsOk() (*[]int32, bool)`

GetServiceIdsOk returns a tuple with the ServiceIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceIds

`func (o *InspectionsRequestDTO) SetServiceIds(v []int32)`

SetServiceIds sets ServiceIds field to given value.


### GetKType

`func (o *InspectionsRequestDTO) GetKType() string`

GetKType returns the KType field if non-nil, zero value otherwise.

### GetKTypeOk

`func (o *InspectionsRequestDTO) GetKTypeOk() (*string, bool)`

GetKTypeOk returns a tuple with the KType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKType

`func (o *InspectionsRequestDTO) SetKType(v string)`

SetKType sets KType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


