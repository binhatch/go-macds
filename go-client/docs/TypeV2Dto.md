# TypeV2Dto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ModelId** | Pointer to **int32** | Id of the model | [optional] 
**Name** | Pointer to **string** | Name of the make | [optional] 
**YearFrom** | Pointer to **int32** | Start of production | [optional] 
**YearTo** | Pointer to **int32** | End of production | [optional] 
**MakeId** | Pointer to **int32** | Id of the make | [optional] 
**ModelSeriesId** | Pointer to **int32** | Model Series Id | [optional] 
**PowerKw** | Pointer to **int32** | Power in kw | [optional] 
**PowerHp** | Pointer to **int32** | Power in hp | [optional] 
**Capacity** | Pointer to **int32** | Capacity | [optional] 
**FuelType** | Pointer to **string** | Fuel type | [optional] 
**EngineCode** | Pointer to **string** | Engine Code | [optional] 
**ModelType** | Pointer to **string** | Model Type | [optional] 
**TypeOfVehicle** | Pointer to **int32** | Type of the Vehicle as integer value:&lt;table&gt;&lt;tbody&gt;&lt;tr&gt;&lt;td&gt;0&lt;/td&gt;&lt;td&gt;None&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;1&lt;/td&gt;&lt;td&gt;Car&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;2&lt;/td&gt;&lt;td&gt;StationWagon&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;3&lt;/td&gt;&lt;td&gt;Van&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;4&lt;/td&gt;&lt;td&gt;Truck&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;5&lt;/td&gt;&lt;td&gt;MPV&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;6&lt;/td&gt;&lt;td&gt;Offroad&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;7&lt;/td&gt;&lt;td&gt;Bus&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;10&lt;/td&gt;&lt;td&gt;Pickup&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;11&lt;/td&gt;&lt;td&gt;Motorcycle&lt;/td&gt;&lt;/tr&gt;&lt;/tbody&gt;&lt;/table&gt; | [optional] 
**Ktypes** | Pointer to **[]int32** | KTypes | [optional] 

## Methods

### NewTypeV2Dto

`func NewTypeV2Dto() *TypeV2Dto`

NewTypeV2Dto instantiates a new TypeV2Dto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTypeV2DtoWithDefaults

`func NewTypeV2DtoWithDefaults() *TypeV2Dto`

NewTypeV2DtoWithDefaults instantiates a new TypeV2Dto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModelId

`func (o *TypeV2Dto) GetModelId() int32`

GetModelId returns the ModelId field if non-nil, zero value otherwise.

### GetModelIdOk

`func (o *TypeV2Dto) GetModelIdOk() (*int32, bool)`

GetModelIdOk returns a tuple with the ModelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelId

`func (o *TypeV2Dto) SetModelId(v int32)`

SetModelId sets ModelId field to given value.

### HasModelId

`func (o *TypeV2Dto) HasModelId() bool`

HasModelId returns a boolean if a field has been set.

### GetName

`func (o *TypeV2Dto) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TypeV2Dto) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TypeV2Dto) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *TypeV2Dto) HasName() bool`

HasName returns a boolean if a field has been set.

### GetYearFrom

`func (o *TypeV2Dto) GetYearFrom() int32`

GetYearFrom returns the YearFrom field if non-nil, zero value otherwise.

### GetYearFromOk

`func (o *TypeV2Dto) GetYearFromOk() (*int32, bool)`

GetYearFromOk returns a tuple with the YearFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearFrom

`func (o *TypeV2Dto) SetYearFrom(v int32)`

SetYearFrom sets YearFrom field to given value.

### HasYearFrom

`func (o *TypeV2Dto) HasYearFrom() bool`

HasYearFrom returns a boolean if a field has been set.

### GetYearTo

`func (o *TypeV2Dto) GetYearTo() int32`

GetYearTo returns the YearTo field if non-nil, zero value otherwise.

### GetYearToOk

`func (o *TypeV2Dto) GetYearToOk() (*int32, bool)`

GetYearToOk returns a tuple with the YearTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearTo

`func (o *TypeV2Dto) SetYearTo(v int32)`

SetYearTo sets YearTo field to given value.

### HasYearTo

`func (o *TypeV2Dto) HasYearTo() bool`

HasYearTo returns a boolean if a field has been set.

### GetMakeId

`func (o *TypeV2Dto) GetMakeId() int32`

GetMakeId returns the MakeId field if non-nil, zero value otherwise.

### GetMakeIdOk

`func (o *TypeV2Dto) GetMakeIdOk() (*int32, bool)`

GetMakeIdOk returns a tuple with the MakeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMakeId

`func (o *TypeV2Dto) SetMakeId(v int32)`

SetMakeId sets MakeId field to given value.

### HasMakeId

`func (o *TypeV2Dto) HasMakeId() bool`

HasMakeId returns a boolean if a field has been set.

### GetModelSeriesId

`func (o *TypeV2Dto) GetModelSeriesId() int32`

GetModelSeriesId returns the ModelSeriesId field if non-nil, zero value otherwise.

### GetModelSeriesIdOk

`func (o *TypeV2Dto) GetModelSeriesIdOk() (*int32, bool)`

GetModelSeriesIdOk returns a tuple with the ModelSeriesId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelSeriesId

`func (o *TypeV2Dto) SetModelSeriesId(v int32)`

SetModelSeriesId sets ModelSeriesId field to given value.

### HasModelSeriesId

`func (o *TypeV2Dto) HasModelSeriesId() bool`

HasModelSeriesId returns a boolean if a field has been set.

### GetPowerKw

`func (o *TypeV2Dto) GetPowerKw() int32`

GetPowerKw returns the PowerKw field if non-nil, zero value otherwise.

### GetPowerKwOk

`func (o *TypeV2Dto) GetPowerKwOk() (*int32, bool)`

GetPowerKwOk returns a tuple with the PowerKw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPowerKw

`func (o *TypeV2Dto) SetPowerKw(v int32)`

SetPowerKw sets PowerKw field to given value.

### HasPowerKw

`func (o *TypeV2Dto) HasPowerKw() bool`

HasPowerKw returns a boolean if a field has been set.

### GetPowerHp

`func (o *TypeV2Dto) GetPowerHp() int32`

GetPowerHp returns the PowerHp field if non-nil, zero value otherwise.

### GetPowerHpOk

`func (o *TypeV2Dto) GetPowerHpOk() (*int32, bool)`

GetPowerHpOk returns a tuple with the PowerHp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPowerHp

`func (o *TypeV2Dto) SetPowerHp(v int32)`

SetPowerHp sets PowerHp field to given value.

### HasPowerHp

`func (o *TypeV2Dto) HasPowerHp() bool`

HasPowerHp returns a boolean if a field has been set.

### GetCapacity

`func (o *TypeV2Dto) GetCapacity() int32`

GetCapacity returns the Capacity field if non-nil, zero value otherwise.

### GetCapacityOk

`func (o *TypeV2Dto) GetCapacityOk() (*int32, bool)`

GetCapacityOk returns a tuple with the Capacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCapacity

`func (o *TypeV2Dto) SetCapacity(v int32)`

SetCapacity sets Capacity field to given value.

### HasCapacity

`func (o *TypeV2Dto) HasCapacity() bool`

HasCapacity returns a boolean if a field has been set.

### GetFuelType

`func (o *TypeV2Dto) GetFuelType() string`

GetFuelType returns the FuelType field if non-nil, zero value otherwise.

### GetFuelTypeOk

`func (o *TypeV2Dto) GetFuelTypeOk() (*string, bool)`

GetFuelTypeOk returns a tuple with the FuelType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFuelType

`func (o *TypeV2Dto) SetFuelType(v string)`

SetFuelType sets FuelType field to given value.

### HasFuelType

`func (o *TypeV2Dto) HasFuelType() bool`

HasFuelType returns a boolean if a field has been set.

### GetEngineCode

`func (o *TypeV2Dto) GetEngineCode() string`

GetEngineCode returns the EngineCode field if non-nil, zero value otherwise.

### GetEngineCodeOk

`func (o *TypeV2Dto) GetEngineCodeOk() (*string, bool)`

GetEngineCodeOk returns a tuple with the EngineCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCode

`func (o *TypeV2Dto) SetEngineCode(v string)`

SetEngineCode sets EngineCode field to given value.

### HasEngineCode

`func (o *TypeV2Dto) HasEngineCode() bool`

HasEngineCode returns a boolean if a field has been set.

### GetModelType

`func (o *TypeV2Dto) GetModelType() string`

GetModelType returns the ModelType field if non-nil, zero value otherwise.

### GetModelTypeOk

`func (o *TypeV2Dto) GetModelTypeOk() (*string, bool)`

GetModelTypeOk returns a tuple with the ModelType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelType

`func (o *TypeV2Dto) SetModelType(v string)`

SetModelType sets ModelType field to given value.

### HasModelType

`func (o *TypeV2Dto) HasModelType() bool`

HasModelType returns a boolean if a field has been set.

### GetTypeOfVehicle

`func (o *TypeV2Dto) GetTypeOfVehicle() int32`

GetTypeOfVehicle returns the TypeOfVehicle field if non-nil, zero value otherwise.

### GetTypeOfVehicleOk

`func (o *TypeV2Dto) GetTypeOfVehicleOk() (*int32, bool)`

GetTypeOfVehicleOk returns a tuple with the TypeOfVehicle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypeOfVehicle

`func (o *TypeV2Dto) SetTypeOfVehicle(v int32)`

SetTypeOfVehicle sets TypeOfVehicle field to given value.

### HasTypeOfVehicle

`func (o *TypeV2Dto) HasTypeOfVehicle() bool`

HasTypeOfVehicle returns a boolean if a field has been set.

### GetKtypes

`func (o *TypeV2Dto) GetKtypes() []int32`

GetKtypes returns the Ktypes field if non-nil, zero value otherwise.

### GetKtypesOk

`func (o *TypeV2Dto) GetKtypesOk() (*[]int32, bool)`

GetKtypesOk returns a tuple with the Ktypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKtypes

`func (o *TypeV2Dto) SetKtypes(v []int32)`

SetKtypes sets Ktypes field to given value.

### HasKtypes

`func (o *TypeV2Dto) HasKtypes() bool`

HasKtypes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


