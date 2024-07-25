# LocationsVehicleDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EngineCode** | Pointer to **string** | Engine Code | [optional] 
**YearFrom** | Pointer to **string** | Year From | [optional] 
**YearTo** | Pointer to **string** | Year To | [optional] 
**EngineCompartment** | Pointer to [**EngineCompartment**](EngineCompartment.md) |  | [optional] 
**Interior** | Pointer to [**InteriorDTO**](InteriorDTO.md) |  | [optional] 

## Methods

### NewLocationsVehicleDTO

`func NewLocationsVehicleDTO() *LocationsVehicleDTO`

NewLocationsVehicleDTO instantiates a new LocationsVehicleDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLocationsVehicleDTOWithDefaults

`func NewLocationsVehicleDTOWithDefaults() *LocationsVehicleDTO`

NewLocationsVehicleDTOWithDefaults instantiates a new LocationsVehicleDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEngineCode

`func (o *LocationsVehicleDTO) GetEngineCode() string`

GetEngineCode returns the EngineCode field if non-nil, zero value otherwise.

### GetEngineCodeOk

`func (o *LocationsVehicleDTO) GetEngineCodeOk() (*string, bool)`

GetEngineCodeOk returns a tuple with the EngineCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCode

`func (o *LocationsVehicleDTO) SetEngineCode(v string)`

SetEngineCode sets EngineCode field to given value.

### HasEngineCode

`func (o *LocationsVehicleDTO) HasEngineCode() bool`

HasEngineCode returns a boolean if a field has been set.

### GetYearFrom

`func (o *LocationsVehicleDTO) GetYearFrom() string`

GetYearFrom returns the YearFrom field if non-nil, zero value otherwise.

### GetYearFromOk

`func (o *LocationsVehicleDTO) GetYearFromOk() (*string, bool)`

GetYearFromOk returns a tuple with the YearFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearFrom

`func (o *LocationsVehicleDTO) SetYearFrom(v string)`

SetYearFrom sets YearFrom field to given value.

### HasYearFrom

`func (o *LocationsVehicleDTO) HasYearFrom() bool`

HasYearFrom returns a boolean if a field has been set.

### GetYearTo

`func (o *LocationsVehicleDTO) GetYearTo() string`

GetYearTo returns the YearTo field if non-nil, zero value otherwise.

### GetYearToOk

`func (o *LocationsVehicleDTO) GetYearToOk() (*string, bool)`

GetYearToOk returns a tuple with the YearTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearTo

`func (o *LocationsVehicleDTO) SetYearTo(v string)`

SetYearTo sets YearTo field to given value.

### HasYearTo

`func (o *LocationsVehicleDTO) HasYearTo() bool`

HasYearTo returns a boolean if a field has been set.

### GetEngineCompartment

`func (o *LocationsVehicleDTO) GetEngineCompartment() EngineCompartment`

GetEngineCompartment returns the EngineCompartment field if non-nil, zero value otherwise.

### GetEngineCompartmentOk

`func (o *LocationsVehicleDTO) GetEngineCompartmentOk() (*EngineCompartment, bool)`

GetEngineCompartmentOk returns a tuple with the EngineCompartment field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCompartment

`func (o *LocationsVehicleDTO) SetEngineCompartment(v EngineCompartment)`

SetEngineCompartment sets EngineCompartment field to given value.

### HasEngineCompartment

`func (o *LocationsVehicleDTO) HasEngineCompartment() bool`

HasEngineCompartment returns a boolean if a field has been set.

### GetInterior

`func (o *LocationsVehicleDTO) GetInterior() InteriorDTO`

GetInterior returns the Interior field if non-nil, zero value otherwise.

### GetInteriorOk

`func (o *LocationsVehicleDTO) GetInteriorOk() (*InteriorDTO, bool)`

GetInteriorOk returns a tuple with the Interior field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInterior

`func (o *LocationsVehicleDTO) SetInterior(v InteriorDTO)`

SetInterior sets Interior field to given value.

### HasInterior

`func (o *LocationsVehicleDTO) HasInterior() bool`

HasInterior returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


