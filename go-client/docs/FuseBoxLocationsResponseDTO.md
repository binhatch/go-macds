# FuseBoxLocationsResponseDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Id | [optional] 
**Name** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**YearFrom** | Pointer to **string** | Year From | [optional] 
**YearTo** | Pointer to **string** | Year To | [optional] 
**EngineCode** | Pointer to **string** | Engine Code | [optional] 
**Relays** | Pointer to [**[]RelayDTO**](RelayDTO.md) | Relays | [optional] 

## Methods

### NewFuseBoxLocationsResponseDTO

`func NewFuseBoxLocationsResponseDTO() *FuseBoxLocationsResponseDTO`

NewFuseBoxLocationsResponseDTO instantiates a new FuseBoxLocationsResponseDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFuseBoxLocationsResponseDTOWithDefaults

`func NewFuseBoxLocationsResponseDTOWithDefaults() *FuseBoxLocationsResponseDTO`

NewFuseBoxLocationsResponseDTOWithDefaults instantiates a new FuseBoxLocationsResponseDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *FuseBoxLocationsResponseDTO) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *FuseBoxLocationsResponseDTO) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *FuseBoxLocationsResponseDTO) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *FuseBoxLocationsResponseDTO) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *FuseBoxLocationsResponseDTO) GetName() Texts`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *FuseBoxLocationsResponseDTO) GetNameOk() (*Texts, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *FuseBoxLocationsResponseDTO) SetName(v Texts)`

SetName sets Name field to given value.

### HasName

`func (o *FuseBoxLocationsResponseDTO) HasName() bool`

HasName returns a boolean if a field has been set.

### GetYearFrom

`func (o *FuseBoxLocationsResponseDTO) GetYearFrom() string`

GetYearFrom returns the YearFrom field if non-nil, zero value otherwise.

### GetYearFromOk

`func (o *FuseBoxLocationsResponseDTO) GetYearFromOk() (*string, bool)`

GetYearFromOk returns a tuple with the YearFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearFrom

`func (o *FuseBoxLocationsResponseDTO) SetYearFrom(v string)`

SetYearFrom sets YearFrom field to given value.

### HasYearFrom

`func (o *FuseBoxLocationsResponseDTO) HasYearFrom() bool`

HasYearFrom returns a boolean if a field has been set.

### GetYearTo

`func (o *FuseBoxLocationsResponseDTO) GetYearTo() string`

GetYearTo returns the YearTo field if non-nil, zero value otherwise.

### GetYearToOk

`func (o *FuseBoxLocationsResponseDTO) GetYearToOk() (*string, bool)`

GetYearToOk returns a tuple with the YearTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearTo

`func (o *FuseBoxLocationsResponseDTO) SetYearTo(v string)`

SetYearTo sets YearTo field to given value.

### HasYearTo

`func (o *FuseBoxLocationsResponseDTO) HasYearTo() bool`

HasYearTo returns a boolean if a field has been set.

### GetEngineCode

`func (o *FuseBoxLocationsResponseDTO) GetEngineCode() string`

GetEngineCode returns the EngineCode field if non-nil, zero value otherwise.

### GetEngineCodeOk

`func (o *FuseBoxLocationsResponseDTO) GetEngineCodeOk() (*string, bool)`

GetEngineCodeOk returns a tuple with the EngineCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCode

`func (o *FuseBoxLocationsResponseDTO) SetEngineCode(v string)`

SetEngineCode sets EngineCode field to given value.

### HasEngineCode

`func (o *FuseBoxLocationsResponseDTO) HasEngineCode() bool`

HasEngineCode returns a boolean if a field has been set.

### GetRelays

`func (o *FuseBoxLocationsResponseDTO) GetRelays() []RelayDTO`

GetRelays returns the Relays field if non-nil, zero value otherwise.

### GetRelaysOk

`func (o *FuseBoxLocationsResponseDTO) GetRelaysOk() (*[]RelayDTO, bool)`

GetRelaysOk returns a tuple with the Relays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelays

`func (o *FuseBoxLocationsResponseDTO) SetRelays(v []RelayDTO)`

SetRelays sets Relays field to given value.

### HasRelays

`func (o *FuseBoxLocationsResponseDTO) HasRelays() bool`

HasRelays returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


