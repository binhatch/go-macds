# Diagram

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | A descriptive name for the wiring diagram | [optional] 
**DiagramImageUrl** | Pointer to **string** | The URL pointing to the SVG image representation of the wiring diagram. | [optional] 
**ComponentCoordinates** | Pointer to [**[]ComponentCoordinates**](ComponentCoordinates.md) | A list components and their image coordinates for the diagram. | [optional] 

## Methods

### NewDiagram

`func NewDiagram() *Diagram`

NewDiagram instantiates a new Diagram object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiagramWithDefaults

`func NewDiagramWithDefaults() *Diagram`

NewDiagramWithDefaults instantiates a new Diagram object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *Diagram) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Diagram) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Diagram) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Diagram) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDiagramImageUrl

`func (o *Diagram) GetDiagramImageUrl() string`

GetDiagramImageUrl returns the DiagramImageUrl field if non-nil, zero value otherwise.

### GetDiagramImageUrlOk

`func (o *Diagram) GetDiagramImageUrlOk() (*string, bool)`

GetDiagramImageUrlOk returns a tuple with the DiagramImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiagramImageUrl

`func (o *Diagram) SetDiagramImageUrl(v string)`

SetDiagramImageUrl sets DiagramImageUrl field to given value.

### HasDiagramImageUrl

`func (o *Diagram) HasDiagramImageUrl() bool`

HasDiagramImageUrl returns a boolean if a field has been set.

### GetComponentCoordinates

`func (o *Diagram) GetComponentCoordinates() []ComponentCoordinates`

GetComponentCoordinates returns the ComponentCoordinates field if non-nil, zero value otherwise.

### GetComponentCoordinatesOk

`func (o *Diagram) GetComponentCoordinatesOk() (*[]ComponentCoordinates, bool)`

GetComponentCoordinatesOk returns a tuple with the ComponentCoordinates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentCoordinates

`func (o *Diagram) SetComponentCoordinates(v []ComponentCoordinates)`

SetComponentCoordinates sets ComponentCoordinates field to given value.

### HasComponentCoordinates

`func (o *Diagram) HasComponentCoordinates() bool`

HasComponentCoordinates returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


