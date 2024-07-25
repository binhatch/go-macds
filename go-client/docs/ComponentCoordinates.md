# ComponentCoordinates

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Component** | Pointer to [**WiringComponent**](WiringComponent.md) |  | [optional] 
**X1** | Pointer to **float64** | The x-coordinate (horizontal position) of the starting point of a component in the diagram. | [optional] 
**Y1** | Pointer to **float64** | The y-coordinate (vertical position) of the starting point of a component in the diagram. | [optional] 
**X2** | Pointer to **float64** | The x-coordinate of the ending point of the component in the diagram. | [optional] 
**Y2** | Pointer to **float64** | The y-coordinate of the ending point of the component in the diagram. | [optional] 

## Methods

### NewComponentCoordinates

`func NewComponentCoordinates() *ComponentCoordinates`

NewComponentCoordinates instantiates a new ComponentCoordinates object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComponentCoordinatesWithDefaults

`func NewComponentCoordinatesWithDefaults() *ComponentCoordinates`

NewComponentCoordinatesWithDefaults instantiates a new ComponentCoordinates object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComponent

`func (o *ComponentCoordinates) GetComponent() WiringComponent`

GetComponent returns the Component field if non-nil, zero value otherwise.

### GetComponentOk

`func (o *ComponentCoordinates) GetComponentOk() (*WiringComponent, bool)`

GetComponentOk returns a tuple with the Component field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponent

`func (o *ComponentCoordinates) SetComponent(v WiringComponent)`

SetComponent sets Component field to given value.

### HasComponent

`func (o *ComponentCoordinates) HasComponent() bool`

HasComponent returns a boolean if a field has been set.

### GetX1

`func (o *ComponentCoordinates) GetX1() float64`

GetX1 returns the X1 field if non-nil, zero value otherwise.

### GetX1Ok

`func (o *ComponentCoordinates) GetX1Ok() (*float64, bool)`

GetX1Ok returns a tuple with the X1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX1

`func (o *ComponentCoordinates) SetX1(v float64)`

SetX1 sets X1 field to given value.

### HasX1

`func (o *ComponentCoordinates) HasX1() bool`

HasX1 returns a boolean if a field has been set.

### GetY1

`func (o *ComponentCoordinates) GetY1() float64`

GetY1 returns the Y1 field if non-nil, zero value otherwise.

### GetY1Ok

`func (o *ComponentCoordinates) GetY1Ok() (*float64, bool)`

GetY1Ok returns a tuple with the Y1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetY1

`func (o *ComponentCoordinates) SetY1(v float64)`

SetY1 sets Y1 field to given value.

### HasY1

`func (o *ComponentCoordinates) HasY1() bool`

HasY1 returns a boolean if a field has been set.

### GetX2

`func (o *ComponentCoordinates) GetX2() float64`

GetX2 returns the X2 field if non-nil, zero value otherwise.

### GetX2Ok

`func (o *ComponentCoordinates) GetX2Ok() (*float64, bool)`

GetX2Ok returns a tuple with the X2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetX2

`func (o *ComponentCoordinates) SetX2(v float64)`

SetX2 sets X2 field to given value.

### HasX2

`func (o *ComponentCoordinates) HasX2() bool`

HasX2 returns a boolean if a field has been set.

### GetY2

`func (o *ComponentCoordinates) GetY2() float64`

GetY2 returns the Y2 field if non-nil, zero value otherwise.

### GetY2Ok

`func (o *ComponentCoordinates) GetY2Ok() (*float64, bool)`

GetY2Ok returns a tuple with the Y2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetY2

`func (o *ComponentCoordinates) SetY2(v float64)`

SetY2 sets Y2 field to given value.

### HasY2

`func (o *ComponentCoordinates) HasY2() bool`

HasY2 returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


