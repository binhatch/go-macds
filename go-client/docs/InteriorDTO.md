# InteriorDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Components** | Pointer to [**[]ComponentDTO**](ComponentDTO.md) | Components | [optional] 

## Methods

### NewInteriorDTO

`func NewInteriorDTO() *InteriorDTO`

NewInteriorDTO instantiates a new InteriorDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInteriorDTOWithDefaults

`func NewInteriorDTOWithDefaults() *InteriorDTO`

NewInteriorDTOWithDefaults instantiates a new InteriorDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComponents

`func (o *InteriorDTO) GetComponents() []ComponentDTO`

GetComponents returns the Components field if non-nil, zero value otherwise.

### GetComponentsOk

`func (o *InteriorDTO) GetComponentsOk() (*[]ComponentDTO, bool)`

GetComponentsOk returns a tuple with the Components field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponents

`func (o *InteriorDTO) SetComponents(v []ComponentDTO)`

SetComponents sets Components field to given value.

### HasComponents

`func (o *InteriorDTO) HasComponents() bool`

HasComponents returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


