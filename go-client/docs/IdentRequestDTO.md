# IdentRequestDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Vin** | **string** | vehicle identification number | 
**EngineCode** | Pointer to **string** | The engine code | [optional] 
**SingleTrustedResult** | Pointer to **bool** | True if only one (trusted) or none results should be returned; otherwise the result list longer along with a confidence score of the respective result | [optional] 
**EnrichOutputVehicle** | Pointer to **bool** | True if additional vehicle information other than just KType or KBA are needed | [optional] 
**OutputVehicle** | Pointer to **string** | Choose between outputting Ktype numbers (&#x3D;1) or KBA/HSN-TSN number (&#x3D;2) | [optional] 

## Methods

### NewIdentRequestDTO

`func NewIdentRequestDTO(vin string, ) *IdentRequestDTO`

NewIdentRequestDTO instantiates a new IdentRequestDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIdentRequestDTOWithDefaults

`func NewIdentRequestDTOWithDefaults() *IdentRequestDTO`

NewIdentRequestDTOWithDefaults instantiates a new IdentRequestDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetVin

`func (o *IdentRequestDTO) GetVin() string`

GetVin returns the Vin field if non-nil, zero value otherwise.

### GetVinOk

`func (o *IdentRequestDTO) GetVinOk() (*string, bool)`

GetVinOk returns a tuple with the Vin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVin

`func (o *IdentRequestDTO) SetVin(v string)`

SetVin sets Vin field to given value.


### GetEngineCode

`func (o *IdentRequestDTO) GetEngineCode() string`

GetEngineCode returns the EngineCode field if non-nil, zero value otherwise.

### GetEngineCodeOk

`func (o *IdentRequestDTO) GetEngineCodeOk() (*string, bool)`

GetEngineCodeOk returns a tuple with the EngineCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCode

`func (o *IdentRequestDTO) SetEngineCode(v string)`

SetEngineCode sets EngineCode field to given value.

### HasEngineCode

`func (o *IdentRequestDTO) HasEngineCode() bool`

HasEngineCode returns a boolean if a field has been set.

### GetSingleTrustedResult

`func (o *IdentRequestDTO) GetSingleTrustedResult() bool`

GetSingleTrustedResult returns the SingleTrustedResult field if non-nil, zero value otherwise.

### GetSingleTrustedResultOk

`func (o *IdentRequestDTO) GetSingleTrustedResultOk() (*bool, bool)`

GetSingleTrustedResultOk returns a tuple with the SingleTrustedResult field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSingleTrustedResult

`func (o *IdentRequestDTO) SetSingleTrustedResult(v bool)`

SetSingleTrustedResult sets SingleTrustedResult field to given value.

### HasSingleTrustedResult

`func (o *IdentRequestDTO) HasSingleTrustedResult() bool`

HasSingleTrustedResult returns a boolean if a field has been set.

### GetEnrichOutputVehicle

`func (o *IdentRequestDTO) GetEnrichOutputVehicle() bool`

GetEnrichOutputVehicle returns the EnrichOutputVehicle field if non-nil, zero value otherwise.

### GetEnrichOutputVehicleOk

`func (o *IdentRequestDTO) GetEnrichOutputVehicleOk() (*bool, bool)`

GetEnrichOutputVehicleOk returns a tuple with the EnrichOutputVehicle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEnrichOutputVehicle

`func (o *IdentRequestDTO) SetEnrichOutputVehicle(v bool)`

SetEnrichOutputVehicle sets EnrichOutputVehicle field to given value.

### HasEnrichOutputVehicle

`func (o *IdentRequestDTO) HasEnrichOutputVehicle() bool`

HasEnrichOutputVehicle returns a boolean if a field has been set.

### GetOutputVehicle

`func (o *IdentRequestDTO) GetOutputVehicle() string`

GetOutputVehicle returns the OutputVehicle field if non-nil, zero value otherwise.

### GetOutputVehicleOk

`func (o *IdentRequestDTO) GetOutputVehicleOk() (*string, bool)`

GetOutputVehicleOk returns a tuple with the OutputVehicle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputVehicle

`func (o *IdentRequestDTO) SetOutputVehicle(v string)`

SetOutputVehicle sets OutputVehicle field to given value.

### HasOutputVehicle

`func (o *IdentRequestDTO) HasOutputVehicle() bool`

HasOutputVehicle returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


