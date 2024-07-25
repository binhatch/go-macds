# VehicleInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Datatype** | Pointer to **string** | Can have values to further specify the data type presented. Can have values such as: flatrateunit (repair times), fuserelay, composition (placements and organisation of different elements on the vehicle), stco (ECU coding), periphery (relevant periphery components to the main component), wiringdiagram, techdata, \&quot;techinfo\&quot; (proprietary knowledge database of Hella Gutmann), \&quot;componenttestvalues\&quot;, \&quot;bulletin\&quot;, \&quot;manual\&quot;, \&quot;gdst\&quot; (basic setting),  \&quot;faultcode\&quot;, \&quot;parameter\&quot; | [optional] 
**Order** | Pointer to **int32** | order | [optional] 
**Richtext** | Pointer to [**[]RichTextDTO**](RichTextDTO.md) | Contains structured texts to guide the interpretation of text values. | [optional] 

## Methods

### NewVehicleInfo

`func NewVehicleInfo() *VehicleInfo`

NewVehicleInfo instantiates a new VehicleInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVehicleInfoWithDefaults

`func NewVehicleInfoWithDefaults() *VehicleInfo`

NewVehicleInfoWithDefaults instantiates a new VehicleInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDatatype

`func (o *VehicleInfo) GetDatatype() string`

GetDatatype returns the Datatype field if non-nil, zero value otherwise.

### GetDatatypeOk

`func (o *VehicleInfo) GetDatatypeOk() (*string, bool)`

GetDatatypeOk returns a tuple with the Datatype field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatatype

`func (o *VehicleInfo) SetDatatype(v string)`

SetDatatype sets Datatype field to given value.

### HasDatatype

`func (o *VehicleInfo) HasDatatype() bool`

HasDatatype returns a boolean if a field has been set.

### GetOrder

`func (o *VehicleInfo) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *VehicleInfo) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *VehicleInfo) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *VehicleInfo) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetRichtext

`func (o *VehicleInfo) GetRichtext() []RichTextDTO`

GetRichtext returns the Richtext field if non-nil, zero value otherwise.

### GetRichtextOk

`func (o *VehicleInfo) GetRichtextOk() (*[]RichTextDTO, bool)`

GetRichtextOk returns a tuple with the Richtext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRichtext

`func (o *VehicleInfo) SetRichtext(v []RichTextDTO)`

SetRichtext sets Richtext field to given value.

### HasRichtext

`func (o *VehicleInfo) HasRichtext() bool`

HasRichtext returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


