# Unit

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UnitType** | Pointer to **string** | Unit Type | [optional] 
**MinValue** | Pointer to **int32** | Minimum Value | [optional] 
**MaxValue** | Pointer to **int32** | Maximum Value | [optional] 

## Methods

### NewUnit

`func NewUnit() *Unit`

NewUnit instantiates a new Unit object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUnitWithDefaults

`func NewUnitWithDefaults() *Unit`

NewUnitWithDefaults instantiates a new Unit object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUnitType

`func (o *Unit) GetUnitType() string`

GetUnitType returns the UnitType field if non-nil, zero value otherwise.

### GetUnitTypeOk

`func (o *Unit) GetUnitTypeOk() (*string, bool)`

GetUnitTypeOk returns a tuple with the UnitType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitType

`func (o *Unit) SetUnitType(v string)`

SetUnitType sets UnitType field to given value.

### HasUnitType

`func (o *Unit) HasUnitType() bool`

HasUnitType returns a boolean if a field has been set.

### GetMinValue

`func (o *Unit) GetMinValue() int32`

GetMinValue returns the MinValue field if non-nil, zero value otherwise.

### GetMinValueOk

`func (o *Unit) GetMinValueOk() (*int32, bool)`

GetMinValueOk returns a tuple with the MinValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMinValue

`func (o *Unit) SetMinValue(v int32)`

SetMinValue sets MinValue field to given value.

### HasMinValue

`func (o *Unit) HasMinValue() bool`

HasMinValue returns a boolean if a field has been set.

### GetMaxValue

`func (o *Unit) GetMaxValue() int32`

GetMaxValue returns the MaxValue field if non-nil, zero value otherwise.

### GetMaxValueOk

`func (o *Unit) GetMaxValueOk() (*int32, bool)`

GetMaxValueOk returns a tuple with the MaxValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxValue

`func (o *Unit) SetMaxValue(v int32)`

SetMaxValue sets MaxValue field to given value.

### HasMaxValue

`func (o *Unit) HasMaxValue() bool`

HasMaxValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


