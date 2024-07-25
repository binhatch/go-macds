# JsonRmi

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**VehicleInfos** | Pointer to [**[]VehicleInfo**](VehicleInfo.md) | Shows information relevant to the vehicle. | [optional] 
**DiagnosesGdstStco** | Pointer to [**[]Diagnoses**](Diagnoses.md) | diagnosesGdstStco | [optional] 
**Peripheries** | Pointer to [**[]Periphery**](Periphery.md) | Array of components or symptoms associated with the main component | [optional] 

## Methods

### NewJsonRmi

`func NewJsonRmi() *JsonRmi`

NewJsonRmi instantiates a new JsonRmi object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewJsonRmiWithDefaults

`func NewJsonRmiWithDefaults() *JsonRmi`

NewJsonRmiWithDefaults instantiates a new JsonRmi object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVehicleInfos

`func (o *JsonRmi) GetVehicleInfos() []VehicleInfo`

GetVehicleInfos returns the VehicleInfos field if non-nil, zero value otherwise.

### GetVehicleInfosOk

`func (o *JsonRmi) GetVehicleInfosOk() (*[]VehicleInfo, bool)`

GetVehicleInfosOk returns a tuple with the VehicleInfos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVehicleInfos

`func (o *JsonRmi) SetVehicleInfos(v []VehicleInfo)`

SetVehicleInfos sets VehicleInfos field to given value.

### HasVehicleInfos

`func (o *JsonRmi) HasVehicleInfos() bool`

HasVehicleInfos returns a boolean if a field has been set.

### GetDiagnosesGdstStco

`func (o *JsonRmi) GetDiagnosesGdstStco() []Diagnoses`

GetDiagnosesGdstStco returns the DiagnosesGdstStco field if non-nil, zero value otherwise.

### GetDiagnosesGdstStcoOk

`func (o *JsonRmi) GetDiagnosesGdstStcoOk() (*[]Diagnoses, bool)`

GetDiagnosesGdstStcoOk returns a tuple with the DiagnosesGdstStco field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiagnosesGdstStco

`func (o *JsonRmi) SetDiagnosesGdstStco(v []Diagnoses)`

SetDiagnosesGdstStco sets DiagnosesGdstStco field to given value.

### HasDiagnosesGdstStco

`func (o *JsonRmi) HasDiagnosesGdstStco() bool`

HasDiagnosesGdstStco returns a boolean if a field has been set.

### GetPeripheries

`func (o *JsonRmi) GetPeripheries() []Periphery`

GetPeripheries returns the Peripheries field if non-nil, zero value otherwise.

### GetPeripheriesOk

`func (o *JsonRmi) GetPeripheriesOk() (*[]Periphery, bool)`

GetPeripheriesOk returns a tuple with the Peripheries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPeripheries

`func (o *JsonRmi) SetPeripheries(v []Periphery)`

SetPeripheries sets Peripheries field to given value.

### HasPeripheries

`func (o *JsonRmi) HasPeripheries() bool`

HasPeripheries returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


