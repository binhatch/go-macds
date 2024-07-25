# LocationsSystemDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SystemId** | Pointer to **string** | System Id | [optional] 
**SystemName** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**Components** | Pointer to [**[]ComponentDTO**](ComponentDTO.md) | Components | [optional] 

## Methods

### NewLocationsSystemDTO

`func NewLocationsSystemDTO() *LocationsSystemDTO`

NewLocationsSystemDTO instantiates a new LocationsSystemDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLocationsSystemDTOWithDefaults

`func NewLocationsSystemDTOWithDefaults() *LocationsSystemDTO`

NewLocationsSystemDTOWithDefaults instantiates a new LocationsSystemDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSystemId

`func (o *LocationsSystemDTO) GetSystemId() string`

GetSystemId returns the SystemId field if non-nil, zero value otherwise.

### GetSystemIdOk

`func (o *LocationsSystemDTO) GetSystemIdOk() (*string, bool)`

GetSystemIdOk returns a tuple with the SystemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemId

`func (o *LocationsSystemDTO) SetSystemId(v string)`

SetSystemId sets SystemId field to given value.

### HasSystemId

`func (o *LocationsSystemDTO) HasSystemId() bool`

HasSystemId returns a boolean if a field has been set.

### GetSystemName

`func (o *LocationsSystemDTO) GetSystemName() Texts`

GetSystemName returns the SystemName field if non-nil, zero value otherwise.

### GetSystemNameOk

`func (o *LocationsSystemDTO) GetSystemNameOk() (*Texts, bool)`

GetSystemNameOk returns a tuple with the SystemName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemName

`func (o *LocationsSystemDTO) SetSystemName(v Texts)`

SetSystemName sets SystemName field to given value.

### HasSystemName

`func (o *LocationsSystemDTO) HasSystemName() bool`

HasSystemName returns a boolean if a field has been set.

### GetComponents

`func (o *LocationsSystemDTO) GetComponents() []ComponentDTO`

GetComponents returns the Components field if non-nil, zero value otherwise.

### GetComponentsOk

`func (o *LocationsSystemDTO) GetComponentsOk() (*[]ComponentDTO, bool)`

GetComponentsOk returns a tuple with the Components field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponents

`func (o *LocationsSystemDTO) SetComponents(v []ComponentDTO)`

SetComponents sets Components field to given value.

### HasComponents

`func (o *LocationsSystemDTO) HasComponents() bool`

HasComponents returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


