# Periphery

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Datatype** | Pointer to **string** | Can have values to further specify the data type presented. Can have values such as: flatrateunit (repair times), fuserelay, composition (placements and organisation of different elements on the vehicle), stco (ECU coding), periphery (relevant periphery components to the main component), wiringdiagram, techdata, \&quot;techinfo\&quot; (proprietary knowledge database of Hella Gutmann), \&quot;componenttestvalues\&quot;, \&quot;bulletin\&quot;, \&quot;manual\&quot;, \&quot;gdst\&quot; (basic setting),  \&quot;faultcode\&quot;, \&quot;parameter\&quot; | [optional] 
**Order** | Pointer to **int32** | order | [optional] 
**IdPeriphery** | Pointer to **int32** | unique ID of the periphery | [optional] 
**Text** | Pointer to **string** | Text of the periphery | [optional] 
**Richtext** | Pointer to [**[]RichTextDTO**](RichTextDTO.md) | Contains structured texts to guide the interpretation of text values. | [optional] 
**VehicleInfo** | Pointer to **string** | vehicleInfo | [optional] 

## Methods

### NewPeriphery

`func NewPeriphery() *Periphery`

NewPeriphery instantiates a new Periphery object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPeripheryWithDefaults

`func NewPeripheryWithDefaults() *Periphery`

NewPeripheryWithDefaults instantiates a new Periphery object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDatatype

`func (o *Periphery) GetDatatype() string`

GetDatatype returns the Datatype field if non-nil, zero value otherwise.

### GetDatatypeOk

`func (o *Periphery) GetDatatypeOk() (*string, bool)`

GetDatatypeOk returns a tuple with the Datatype field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatatype

`func (o *Periphery) SetDatatype(v string)`

SetDatatype sets Datatype field to given value.

### HasDatatype

`func (o *Periphery) HasDatatype() bool`

HasDatatype returns a boolean if a field has been set.

### GetOrder

`func (o *Periphery) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *Periphery) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *Periphery) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *Periphery) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetIdPeriphery

`func (o *Periphery) GetIdPeriphery() int32`

GetIdPeriphery returns the IdPeriphery field if non-nil, zero value otherwise.

### GetIdPeripheryOk

`func (o *Periphery) GetIdPeripheryOk() (*int32, bool)`

GetIdPeripheryOk returns a tuple with the IdPeriphery field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdPeriphery

`func (o *Periphery) SetIdPeriphery(v int32)`

SetIdPeriphery sets IdPeriphery field to given value.

### HasIdPeriphery

`func (o *Periphery) HasIdPeriphery() bool`

HasIdPeriphery returns a boolean if a field has been set.

### GetText

`func (o *Periphery) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *Periphery) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *Periphery) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *Periphery) HasText() bool`

HasText returns a boolean if a field has been set.

### GetRichtext

`func (o *Periphery) GetRichtext() []RichTextDTO`

GetRichtext returns the Richtext field if non-nil, zero value otherwise.

### GetRichtextOk

`func (o *Periphery) GetRichtextOk() (*[]RichTextDTO, bool)`

GetRichtextOk returns a tuple with the Richtext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRichtext

`func (o *Periphery) SetRichtext(v []RichTextDTO)`

SetRichtext sets Richtext field to given value.

### HasRichtext

`func (o *Periphery) HasRichtext() bool`

HasRichtext returns a boolean if a field has been set.

### GetVehicleInfo

`func (o *Periphery) GetVehicleInfo() string`

GetVehicleInfo returns the VehicleInfo field if non-nil, zero value otherwise.

### GetVehicleInfoOk

`func (o *Periphery) GetVehicleInfoOk() (*string, bool)`

GetVehicleInfoOk returns a tuple with the VehicleInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVehicleInfo

`func (o *Periphery) SetVehicleInfo(v string)`

SetVehicleInfo sets VehicleInfo field to given value.

### HasVehicleInfo

`func (o *Periphery) HasVehicleInfo() bool`

HasVehicleInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


