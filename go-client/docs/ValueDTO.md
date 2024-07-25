# ValueDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**UnitNo** | Pointer to **int32** | Unit Number | [optional] 
**UnitAbbreviation** | Pointer to **string** | Unit Abbreviation | [optional] 
**Decimals** | Pointer to **int32** | Decimals | [optional] 
**RoundingDecimals** | Pointer to **int32** | Rounding Decimals | [optional] 
**Value** | Pointer to **float64** | Value | [optional] 

## Methods

### NewValueDTO

`func NewValueDTO() *ValueDTO`

NewValueDTO instantiates a new ValueDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewValueDTOWithDefaults

`func NewValueDTOWithDefaults() *ValueDTO`

NewValueDTOWithDefaults instantiates a new ValueDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUnitNo

`func (o *ValueDTO) GetUnitNo() int32`

GetUnitNo returns the UnitNo field if non-nil, zero value otherwise.

### GetUnitNoOk

`func (o *ValueDTO) GetUnitNoOk() (*int32, bool)`

GetUnitNoOk returns a tuple with the UnitNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitNo

`func (o *ValueDTO) SetUnitNo(v int32)`

SetUnitNo sets UnitNo field to given value.

### HasUnitNo

`func (o *ValueDTO) HasUnitNo() bool`

HasUnitNo returns a boolean if a field has been set.

### GetUnitAbbreviation

`func (o *ValueDTO) GetUnitAbbreviation() string`

GetUnitAbbreviation returns the UnitAbbreviation field if non-nil, zero value otherwise.

### GetUnitAbbreviationOk

`func (o *ValueDTO) GetUnitAbbreviationOk() (*string, bool)`

GetUnitAbbreviationOk returns a tuple with the UnitAbbreviation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnitAbbreviation

`func (o *ValueDTO) SetUnitAbbreviation(v string)`

SetUnitAbbreviation sets UnitAbbreviation field to given value.

### HasUnitAbbreviation

`func (o *ValueDTO) HasUnitAbbreviation() bool`

HasUnitAbbreviation returns a boolean if a field has been set.

### GetDecimals

`func (o *ValueDTO) GetDecimals() int32`

GetDecimals returns the Decimals field if non-nil, zero value otherwise.

### GetDecimalsOk

`func (o *ValueDTO) GetDecimalsOk() (*int32, bool)`

GetDecimalsOk returns a tuple with the Decimals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDecimals

`func (o *ValueDTO) SetDecimals(v int32)`

SetDecimals sets Decimals field to given value.

### HasDecimals

`func (o *ValueDTO) HasDecimals() bool`

HasDecimals returns a boolean if a field has been set.

### GetRoundingDecimals

`func (o *ValueDTO) GetRoundingDecimals() int32`

GetRoundingDecimals returns the RoundingDecimals field if non-nil, zero value otherwise.

### GetRoundingDecimalsOk

`func (o *ValueDTO) GetRoundingDecimalsOk() (*int32, bool)`

GetRoundingDecimalsOk returns a tuple with the RoundingDecimals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoundingDecimals

`func (o *ValueDTO) SetRoundingDecimals(v int32)`

SetRoundingDecimals sets RoundingDecimals field to given value.

### HasRoundingDecimals

`func (o *ValueDTO) HasRoundingDecimals() bool`

HasRoundingDecimals returns a boolean if a field has been set.

### GetValue

`func (o *ValueDTO) GetValue() float64`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ValueDTO) GetValueOk() (*float64, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ValueDTO) SetValue(v float64)`

SetValue sets Value field to given value.

### HasValue

`func (o *ValueDTO) HasValue() bool`

HasValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


