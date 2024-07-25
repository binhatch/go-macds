# Result

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EngineCode** | Pointer to **string** | Engine Code | [optional] 
**EnginePower** | Pointer to **int32** | Engine Power | [optional] 
**EngineSize** | Pointer to **int32** | Engine Size | [optional] 
**FuelSystem** | Pointer to **string** | Fuel System | [optional] 
**FuelType** | Pointer to **string** | Fuel Type | [optional] 
**KtypNumbers** | Pointer to [**[]KtypNumber**](KtypNumber.md) | KType Numbers | [optional] 
**ModelSeries** | Pointer to **string** | Model Series | [optional] 
**Name** | Pointer to **string** | Name | [optional] 
**ShortcutName** | Pointer to **string** | Shortcut Name | [optional] 
**VehicleTypeId** | Pointer to **int32** | Vehicle Type Id | [optional] 
**Vin** | Pointer to **string** | Vehicle Identification Number | [optional] 
**YearFrom** | Pointer to **time.Time** | Year From | [optional] 
**YearTo** | Pointer to **time.Time** | Year To | [optional] 

## Methods

### NewResult

`func NewResult() *Result`

NewResult instantiates a new Result object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResultWithDefaults

`func NewResultWithDefaults() *Result`

NewResultWithDefaults instantiates a new Result object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEngineCode

`func (o *Result) GetEngineCode() string`

GetEngineCode returns the EngineCode field if non-nil, zero value otherwise.

### GetEngineCodeOk

`func (o *Result) GetEngineCodeOk() (*string, bool)`

GetEngineCodeOk returns a tuple with the EngineCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCode

`func (o *Result) SetEngineCode(v string)`

SetEngineCode sets EngineCode field to given value.

### HasEngineCode

`func (o *Result) HasEngineCode() bool`

HasEngineCode returns a boolean if a field has been set.

### GetEnginePower

`func (o *Result) GetEnginePower() int32`

GetEnginePower returns the EnginePower field if non-nil, zero value otherwise.

### GetEnginePowerOk

`func (o *Result) GetEnginePowerOk() (*int32, bool)`

GetEnginePowerOk returns a tuple with the EnginePower field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnginePower

`func (o *Result) SetEnginePower(v int32)`

SetEnginePower sets EnginePower field to given value.

### HasEnginePower

`func (o *Result) HasEnginePower() bool`

HasEnginePower returns a boolean if a field has been set.

### GetEngineSize

`func (o *Result) GetEngineSize() int32`

GetEngineSize returns the EngineSize field if non-nil, zero value otherwise.

### GetEngineSizeOk

`func (o *Result) GetEngineSizeOk() (*int32, bool)`

GetEngineSizeOk returns a tuple with the EngineSize field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineSize

`func (o *Result) SetEngineSize(v int32)`

SetEngineSize sets EngineSize field to given value.

### HasEngineSize

`func (o *Result) HasEngineSize() bool`

HasEngineSize returns a boolean if a field has been set.

### GetFuelSystem

`func (o *Result) GetFuelSystem() string`

GetFuelSystem returns the FuelSystem field if non-nil, zero value otherwise.

### GetFuelSystemOk

`func (o *Result) GetFuelSystemOk() (*string, bool)`

GetFuelSystemOk returns a tuple with the FuelSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFuelSystem

`func (o *Result) SetFuelSystem(v string)`

SetFuelSystem sets FuelSystem field to given value.

### HasFuelSystem

`func (o *Result) HasFuelSystem() bool`

HasFuelSystem returns a boolean if a field has been set.

### GetFuelType

`func (o *Result) GetFuelType() string`

GetFuelType returns the FuelType field if non-nil, zero value otherwise.

### GetFuelTypeOk

`func (o *Result) GetFuelTypeOk() (*string, bool)`

GetFuelTypeOk returns a tuple with the FuelType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFuelType

`func (o *Result) SetFuelType(v string)`

SetFuelType sets FuelType field to given value.

### HasFuelType

`func (o *Result) HasFuelType() bool`

HasFuelType returns a boolean if a field has been set.

### GetKtypNumbers

`func (o *Result) GetKtypNumbers() []KtypNumber`

GetKtypNumbers returns the KtypNumbers field if non-nil, zero value otherwise.

### GetKtypNumbersOk

`func (o *Result) GetKtypNumbersOk() (*[]KtypNumber, bool)`

GetKtypNumbersOk returns a tuple with the KtypNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKtypNumbers

`func (o *Result) SetKtypNumbers(v []KtypNumber)`

SetKtypNumbers sets KtypNumbers field to given value.

### HasKtypNumbers

`func (o *Result) HasKtypNumbers() bool`

HasKtypNumbers returns a boolean if a field has been set.

### GetModelSeries

`func (o *Result) GetModelSeries() string`

GetModelSeries returns the ModelSeries field if non-nil, zero value otherwise.

### GetModelSeriesOk

`func (o *Result) GetModelSeriesOk() (*string, bool)`

GetModelSeriesOk returns a tuple with the ModelSeries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelSeries

`func (o *Result) SetModelSeries(v string)`

SetModelSeries sets ModelSeries field to given value.

### HasModelSeries

`func (o *Result) HasModelSeries() bool`

HasModelSeries returns a boolean if a field has been set.

### GetName

`func (o *Result) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Result) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Result) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Result) HasName() bool`

HasName returns a boolean if a field has been set.

### GetShortcutName

`func (o *Result) GetShortcutName() string`

GetShortcutName returns the ShortcutName field if non-nil, zero value otherwise.

### GetShortcutNameOk

`func (o *Result) GetShortcutNameOk() (*string, bool)`

GetShortcutNameOk returns a tuple with the ShortcutName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortcutName

`func (o *Result) SetShortcutName(v string)`

SetShortcutName sets ShortcutName field to given value.

### HasShortcutName

`func (o *Result) HasShortcutName() bool`

HasShortcutName returns a boolean if a field has been set.

### GetVehicleTypeId

`func (o *Result) GetVehicleTypeId() int32`

GetVehicleTypeId returns the VehicleTypeId field if non-nil, zero value otherwise.

### GetVehicleTypeIdOk

`func (o *Result) GetVehicleTypeIdOk() (*int32, bool)`

GetVehicleTypeIdOk returns a tuple with the VehicleTypeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVehicleTypeId

`func (o *Result) SetVehicleTypeId(v int32)`

SetVehicleTypeId sets VehicleTypeId field to given value.

### HasVehicleTypeId

`func (o *Result) HasVehicleTypeId() bool`

HasVehicleTypeId returns a boolean if a field has been set.

### GetVin

`func (o *Result) GetVin() string`

GetVin returns the Vin field if non-nil, zero value otherwise.

### GetVinOk

`func (o *Result) GetVinOk() (*string, bool)`

GetVinOk returns a tuple with the Vin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVin

`func (o *Result) SetVin(v string)`

SetVin sets Vin field to given value.

### HasVin

`func (o *Result) HasVin() bool`

HasVin returns a boolean if a field has been set.

### GetYearFrom

`func (o *Result) GetYearFrom() time.Time`

GetYearFrom returns the YearFrom field if non-nil, zero value otherwise.

### GetYearFromOk

`func (o *Result) GetYearFromOk() (*time.Time, bool)`

GetYearFromOk returns a tuple with the YearFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearFrom

`func (o *Result) SetYearFrom(v time.Time)`

SetYearFrom sets YearFrom field to given value.

### HasYearFrom

`func (o *Result) HasYearFrom() bool`

HasYearFrom returns a boolean if a field has been set.

### GetYearTo

`func (o *Result) GetYearTo() time.Time`

GetYearTo returns the YearTo field if non-nil, zero value otherwise.

### GetYearToOk

`func (o *Result) GetYearToOk() (*time.Time, bool)`

GetYearToOk returns a tuple with the YearTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearTo

`func (o *Result) SetYearTo(v time.Time)`

SetYearTo sets YearTo field to given value.

### HasYearTo

`func (o *Result) HasYearTo() bool`

HasYearTo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


