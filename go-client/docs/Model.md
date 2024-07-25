# Model

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ModelId** | Pointer to **int32** | Model Id | [optional] 
**Cylinders** | Pointer to **int32** | Cylinders | [optional] 
**ModelType** | Pointer to **string** | Model Type | [optional] 
**EngineSize** | Pointer to **int32** | Engine Size | [optional] 
**ModelSeriesName** | Pointer to **string** | Model Series Name | [optional] 
**ModelSeriesAlias** | Pointer to **string** | Model Series Alias | [optional] 
**ModelName** | Pointer to **string** | Model Name | [optional] 
**TypeOfVehicle** | Pointer to **int32** | Type of the Vehicle as integer value:&lt;table&gt;&lt;tbody&gt;&lt;tr&gt;&lt;td&gt;0&lt;/td&gt;&lt;td&gt;None&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;1&lt;/td&gt;&lt;td&gt;Car&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;2&lt;/td&gt;&lt;td&gt;StationWagon&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;3&lt;/td&gt;&lt;td&gt;Van&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;4&lt;/td&gt;&lt;td&gt;Truck&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;5&lt;/td&gt;&lt;td&gt;MPV&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;6&lt;/td&gt;&lt;td&gt;Offroad&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;7&lt;/td&gt;&lt;td&gt;Bus&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;10&lt;/td&gt;&lt;td&gt;Pickup&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;11&lt;/td&gt;&lt;td&gt;Motorcycle&lt;/td&gt;&lt;/tr&gt;&lt;/tbody&gt;&lt;/table&gt; | [optional] 
**RegionCode** | Pointer to **string** | Region Code | [optional] 
**FromYear** | Pointer to **int32** | From Year | [optional] 
**ToYear** | Pointer to **int32** | To Year | [optional] 
**Years** | Pointer to [**[]ModelYear**](ModelYear.md) | List of Model Years | [optional] 
**ElectronicOEServiceRegistrationTId** | Pointer to **int32** | Electronic OE Service Registration TId | [optional] 

## Methods

### NewModel

`func NewModel() *Model`

NewModel instantiates a new Model object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewModelWithDefaults

`func NewModelWithDefaults() *Model`

NewModelWithDefaults instantiates a new Model object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetModelId

`func (o *Model) GetModelId() int32`

GetModelId returns the ModelId field if non-nil, zero value otherwise.

### GetModelIdOk

`func (o *Model) GetModelIdOk() (*int32, bool)`

GetModelIdOk returns a tuple with the ModelId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelId

`func (o *Model) SetModelId(v int32)`

SetModelId sets ModelId field to given value.

### HasModelId

`func (o *Model) HasModelId() bool`

HasModelId returns a boolean if a field has been set.

### GetCylinders

`func (o *Model) GetCylinders() int32`

GetCylinders returns the Cylinders field if non-nil, zero value otherwise.

### GetCylindersOk

`func (o *Model) GetCylindersOk() (*int32, bool)`

GetCylindersOk returns a tuple with the Cylinders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCylinders

`func (o *Model) SetCylinders(v int32)`

SetCylinders sets Cylinders field to given value.

### HasCylinders

`func (o *Model) HasCylinders() bool`

HasCylinders returns a boolean if a field has been set.

### GetModelType

`func (o *Model) GetModelType() string`

GetModelType returns the ModelType field if non-nil, zero value otherwise.

### GetModelTypeOk

`func (o *Model) GetModelTypeOk() (*string, bool)`

GetModelTypeOk returns a tuple with the ModelType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelType

`func (o *Model) SetModelType(v string)`

SetModelType sets ModelType field to given value.

### HasModelType

`func (o *Model) HasModelType() bool`

HasModelType returns a boolean if a field has been set.

### GetEngineSize

`func (o *Model) GetEngineSize() int32`

GetEngineSize returns the EngineSize field if non-nil, zero value otherwise.

### GetEngineSizeOk

`func (o *Model) GetEngineSizeOk() (*int32, bool)`

GetEngineSizeOk returns a tuple with the EngineSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineSize

`func (o *Model) SetEngineSize(v int32)`

SetEngineSize sets EngineSize field to given value.

### HasEngineSize

`func (o *Model) HasEngineSize() bool`

HasEngineSize returns a boolean if a field has been set.

### GetModelSeriesName

`func (o *Model) GetModelSeriesName() string`

GetModelSeriesName returns the ModelSeriesName field if non-nil, zero value otherwise.

### GetModelSeriesNameOk

`func (o *Model) GetModelSeriesNameOk() (*string, bool)`

GetModelSeriesNameOk returns a tuple with the ModelSeriesName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelSeriesName

`func (o *Model) SetModelSeriesName(v string)`

SetModelSeriesName sets ModelSeriesName field to given value.

### HasModelSeriesName

`func (o *Model) HasModelSeriesName() bool`

HasModelSeriesName returns a boolean if a field has been set.

### GetModelSeriesAlias

`func (o *Model) GetModelSeriesAlias() string`

GetModelSeriesAlias returns the ModelSeriesAlias field if non-nil, zero value otherwise.

### GetModelSeriesAliasOk

`func (o *Model) GetModelSeriesAliasOk() (*string, bool)`

GetModelSeriesAliasOk returns a tuple with the ModelSeriesAlias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelSeriesAlias

`func (o *Model) SetModelSeriesAlias(v string)`

SetModelSeriesAlias sets ModelSeriesAlias field to given value.

### HasModelSeriesAlias

`func (o *Model) HasModelSeriesAlias() bool`

HasModelSeriesAlias returns a boolean if a field has been set.

### GetModelName

`func (o *Model) GetModelName() string`

GetModelName returns the ModelName field if non-nil, zero value otherwise.

### GetModelNameOk

`func (o *Model) GetModelNameOk() (*string, bool)`

GetModelNameOk returns a tuple with the ModelName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelName

`func (o *Model) SetModelName(v string)`

SetModelName sets ModelName field to given value.

### HasModelName

`func (o *Model) HasModelName() bool`

HasModelName returns a boolean if a field has been set.

### GetTypeOfVehicle

`func (o *Model) GetTypeOfVehicle() int32`

GetTypeOfVehicle returns the TypeOfVehicle field if non-nil, zero value otherwise.

### GetTypeOfVehicleOk

`func (o *Model) GetTypeOfVehicleOk() (*int32, bool)`

GetTypeOfVehicleOk returns a tuple with the TypeOfVehicle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypeOfVehicle

`func (o *Model) SetTypeOfVehicle(v int32)`

SetTypeOfVehicle sets TypeOfVehicle field to given value.

### HasTypeOfVehicle

`func (o *Model) HasTypeOfVehicle() bool`

HasTypeOfVehicle returns a boolean if a field has been set.

### GetRegionCode

`func (o *Model) GetRegionCode() string`

GetRegionCode returns the RegionCode field if non-nil, zero value otherwise.

### GetRegionCodeOk

`func (o *Model) GetRegionCodeOk() (*string, bool)`

GetRegionCodeOk returns a tuple with the RegionCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegionCode

`func (o *Model) SetRegionCode(v string)`

SetRegionCode sets RegionCode field to given value.

### HasRegionCode

`func (o *Model) HasRegionCode() bool`

HasRegionCode returns a boolean if a field has been set.

### GetFromYear

`func (o *Model) GetFromYear() int32`

GetFromYear returns the FromYear field if non-nil, zero value otherwise.

### GetFromYearOk

`func (o *Model) GetFromYearOk() (*int32, bool)`

GetFromYearOk returns a tuple with the FromYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFromYear

`func (o *Model) SetFromYear(v int32)`

SetFromYear sets FromYear field to given value.

### HasFromYear

`func (o *Model) HasFromYear() bool`

HasFromYear returns a boolean if a field has been set.

### GetToYear

`func (o *Model) GetToYear() int32`

GetToYear returns the ToYear field if non-nil, zero value otherwise.

### GetToYearOk

`func (o *Model) GetToYearOk() (*int32, bool)`

GetToYearOk returns a tuple with the ToYear field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToYear

`func (o *Model) SetToYear(v int32)`

SetToYear sets ToYear field to given value.

### HasToYear

`func (o *Model) HasToYear() bool`

HasToYear returns a boolean if a field has been set.

### GetYears

`func (o *Model) GetYears() []ModelYear`

GetYears returns the Years field if non-nil, zero value otherwise.

### GetYearsOk

`func (o *Model) GetYearsOk() (*[]ModelYear, bool)`

GetYearsOk returns a tuple with the Years field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYears

`func (o *Model) SetYears(v []ModelYear)`

SetYears sets Years field to given value.

### HasYears

`func (o *Model) HasYears() bool`

HasYears returns a boolean if a field has been set.

### GetElectronicOEServiceRegistrationTId

`func (o *Model) GetElectronicOEServiceRegistrationTId() int32`

GetElectronicOEServiceRegistrationTId returns the ElectronicOEServiceRegistrationTId field if non-nil, zero value otherwise.

### GetElectronicOEServiceRegistrationTIdOk

`func (o *Model) GetElectronicOEServiceRegistrationTIdOk() (*int32, bool)`

GetElectronicOEServiceRegistrationTIdOk returns a tuple with the ElectronicOEServiceRegistrationTId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetElectronicOEServiceRegistrationTId

`func (o *Model) SetElectronicOEServiceRegistrationTId(v int32)`

SetElectronicOEServiceRegistrationTId sets ElectronicOEServiceRegistrationTId field to given value.

### HasElectronicOEServiceRegistrationTId

`func (o *Model) HasElectronicOEServiceRegistrationTId() bool`

HasElectronicOEServiceRegistrationTId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


