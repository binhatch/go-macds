# ServiceSchedulesRequestDTO

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
**DateProduction** | Pointer to **string** | Optional; date of the production (or first registration) of the vehicle to calculate the next due service. (Is tied to \&quot;mileage \&quot;) | [optional] 
**MileageLastService** | Pointer to **int32** | Optional; mileage of when the last service was done; If not provided, the assumption is that no service was done so far. | [optional] 
**DateLastService** | Pointer to **string** | Optional; date of when the last service was done; If not provided, the assumption is that no service was done so far. | [optional] 
**KType** | **string** | KType | 

## Methods

### NewServiceSchedulesRequestDTO

`func NewServiceSchedulesRequestDTO(language string, kType string, ) *ServiceSchedulesRequestDTO`

NewServiceSchedulesRequestDTO instantiates a new ServiceSchedulesRequestDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceSchedulesRequestDTOWithDefaults

`func NewServiceSchedulesRequestDTOWithDefaults() *ServiceSchedulesRequestDTO`

NewServiceSchedulesRequestDTOWithDefaults instantiates a new ServiceSchedulesRequestDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLanguage

`func (o *ServiceSchedulesRequestDTO) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *ServiceSchedulesRequestDTO) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *ServiceSchedulesRequestDTO) SetLanguage(v string)`

SetLanguage sets Language field to given value.


### GetHgsManufId

`func (o *ServiceSchedulesRequestDTO) GetHgsManufId() string`

GetHgsManufId returns the HgsManufId field if non-nil, zero value otherwise.

### GetHgsManufIdOk

`func (o *ServiceSchedulesRequestDTO) GetHgsManufIdOk() (*string, bool)`

GetHgsManufIdOk returns a tuple with the HgsManufId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHgsManufId

`func (o *ServiceSchedulesRequestDTO) SetHgsManufId(v string)`

SetHgsManufId sets HgsManufId field to given value.

### HasHgsManufId

`func (o *ServiceSchedulesRequestDTO) HasHgsManufId() bool`

HasHgsManufId returns a boolean if a field has been set.

### GetHgsModelId

`func (o *ServiceSchedulesRequestDTO) GetHgsModelId() string`

GetHgsModelId returns the HgsModelId field if non-nil, zero value otherwise.

### GetHgsModelIdOk

`func (o *ServiceSchedulesRequestDTO) GetHgsModelIdOk() (*string, bool)`

GetHgsModelIdOk returns a tuple with the HgsModelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHgsModelId

`func (o *ServiceSchedulesRequestDTO) SetHgsModelId(v string)`

SetHgsModelId sets HgsModelId field to given value.

### HasHgsModelId

`func (o *ServiceSchedulesRequestDTO) HasHgsModelId() bool`

HasHgsModelId returns a boolean if a field has been set.

### GetEngineCode

`func (o *ServiceSchedulesRequestDTO) GetEngineCode() string`

GetEngineCode returns the EngineCode field if non-nil, zero value otherwise.

### GetEngineCodeOk

`func (o *ServiceSchedulesRequestDTO) GetEngineCodeOk() (*string, bool)`

GetEngineCodeOk returns a tuple with the EngineCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCode

`func (o *ServiceSchedulesRequestDTO) SetEngineCode(v string)`

SetEngineCode sets EngineCode field to given value.

### HasEngineCode

`func (o *ServiceSchedulesRequestDTO) HasEngineCode() bool`

HasEngineCode returns a boolean if a field has been set.

### GetEngineKw

`func (o *ServiceSchedulesRequestDTO) GetEngineKw() string`

GetEngineKw returns the EngineKw field if non-nil, zero value otherwise.

### GetEngineKwOk

`func (o *ServiceSchedulesRequestDTO) GetEngineKwOk() (*string, bool)`

GetEngineKwOk returns a tuple with the EngineKw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineKw

`func (o *ServiceSchedulesRequestDTO) SetEngineKw(v string)`

SetEngineKw sets EngineKw field to given value.

### HasEngineKw

`func (o *ServiceSchedulesRequestDTO) HasEngineKw() bool`

HasEngineKw returns a boolean if a field has been set.

### GetProductionYear

`func (o *ServiceSchedulesRequestDTO) GetProductionYear() string`

GetProductionYear returns the ProductionYear field if non-nil, zero value otherwise.

### GetProductionYearOk

`func (o *ServiceSchedulesRequestDTO) GetProductionYearOk() (*string, bool)`

GetProductionYearOk returns a tuple with the ProductionYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProductionYear

`func (o *ServiceSchedulesRequestDTO) SetProductionYear(v string)`

SetProductionYear sets ProductionYear field to given value.

### HasProductionYear

`func (o *ServiceSchedulesRequestDTO) HasProductionYear() bool`

HasProductionYear returns a boolean if a field has been set.

### GetRegionCode

`func (o *ServiceSchedulesRequestDTO) GetRegionCode() string`

GetRegionCode returns the RegionCode field if non-nil, zero value otherwise.

### GetRegionCodeOk

`func (o *ServiceSchedulesRequestDTO) GetRegionCodeOk() (*string, bool)`

GetRegionCodeOk returns a tuple with the RegionCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionCode

`func (o *ServiceSchedulesRequestDTO) SetRegionCode(v string)`

SetRegionCode sets RegionCode field to given value.

### HasRegionCode

`func (o *ServiceSchedulesRequestDTO) HasRegionCode() bool`

HasRegionCode returns a boolean if a field has been set.

### GetPreview

`func (o *ServiceSchedulesRequestDTO) GetPreview() string`

GetPreview returns the Preview field if non-nil, zero value otherwise.

### GetPreviewOk

`func (o *ServiceSchedulesRequestDTO) GetPreviewOk() (*string, bool)`

GetPreviewOk returns a tuple with the Preview field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreview

`func (o *ServiceSchedulesRequestDTO) SetPreview(v string)`

SetPreview sets Preview field to given value.

### HasPreview

`func (o *ServiceSchedulesRequestDTO) HasPreview() bool`

HasPreview returns a boolean if a field has been set.

### GetMileage

`func (o *ServiceSchedulesRequestDTO) GetMileage() int32`

GetMileage returns the Mileage field if non-nil, zero value otherwise.

### GetMileageOk

`func (o *ServiceSchedulesRequestDTO) GetMileageOk() (*int32, bool)`

GetMileageOk returns a tuple with the Mileage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMileage

`func (o *ServiceSchedulesRequestDTO) SetMileage(v int32)`

SetMileage sets Mileage field to given value.

### HasMileage

`func (o *ServiceSchedulesRequestDTO) HasMileage() bool`

HasMileage returns a boolean if a field has been set.

### GetDateProduction

`func (o *ServiceSchedulesRequestDTO) GetDateProduction() string`

GetDateProduction returns the DateProduction field if non-nil, zero value otherwise.

### GetDateProductionOk

`func (o *ServiceSchedulesRequestDTO) GetDateProductionOk() (*string, bool)`

GetDateProductionOk returns a tuple with the DateProduction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateProduction

`func (o *ServiceSchedulesRequestDTO) SetDateProduction(v string)`

SetDateProduction sets DateProduction field to given value.

### HasDateProduction

`func (o *ServiceSchedulesRequestDTO) HasDateProduction() bool`

HasDateProduction returns a boolean if a field has been set.

### GetMileageLastService

`func (o *ServiceSchedulesRequestDTO) GetMileageLastService() int32`

GetMileageLastService returns the MileageLastService field if non-nil, zero value otherwise.

### GetMileageLastServiceOk

`func (o *ServiceSchedulesRequestDTO) GetMileageLastServiceOk() (*int32, bool)`

GetMileageLastServiceOk returns a tuple with the MileageLastService field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMileageLastService

`func (o *ServiceSchedulesRequestDTO) SetMileageLastService(v int32)`

SetMileageLastService sets MileageLastService field to given value.

### HasMileageLastService

`func (o *ServiceSchedulesRequestDTO) HasMileageLastService() bool`

HasMileageLastService returns a boolean if a field has been set.

### GetDateLastService

`func (o *ServiceSchedulesRequestDTO) GetDateLastService() string`

GetDateLastService returns the DateLastService field if non-nil, zero value otherwise.

### GetDateLastServiceOk

`func (o *ServiceSchedulesRequestDTO) GetDateLastServiceOk() (*string, bool)`

GetDateLastServiceOk returns a tuple with the DateLastService field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateLastService

`func (o *ServiceSchedulesRequestDTO) SetDateLastService(v string)`

SetDateLastService sets DateLastService field to given value.

### HasDateLastService

`func (o *ServiceSchedulesRequestDTO) HasDateLastService() bool`

HasDateLastService returns a boolean if a field has been set.

### GetKType

`func (o *ServiceSchedulesRequestDTO) GetKType() string`

GetKType returns the KType field if non-nil, zero value otherwise.

### GetKTypeOk

`func (o *ServiceSchedulesRequestDTO) GetKTypeOk() (*string, bool)`

GetKTypeOk returns a tuple with the KType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKType

`func (o *ServiceSchedulesRequestDTO) SetKType(v string)`

SetKType sets KType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


