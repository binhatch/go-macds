# DataInput

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DataInputTypeId** | Pointer to **string** | Data Input Type Id | [optional] 
**Name** | Pointer to [**NameReference**](NameReference.md) |  | [optional] 
**DataInputType** | Pointer to **string** | Data Input Type | [optional] 
**Units** | Pointer to [**[]Unit**](Unit.md) | List of Units | [optional] 
**LabourTime** | Pointer to **int32** | Labour Time | [optional] 
**IsMandatory** | Pointer to **bool** | Is mandatory | [optional] 

## Methods

### NewDataInput

`func NewDataInput() *DataInput`

NewDataInput instantiates a new DataInput object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDataInputWithDefaults

`func NewDataInputWithDefaults() *DataInput`

NewDataInputWithDefaults instantiates a new DataInput object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDataInputTypeId

`func (o *DataInput) GetDataInputTypeId() string`

GetDataInputTypeId returns the DataInputTypeId field if non-nil, zero value otherwise.

### GetDataInputTypeIdOk

`func (o *DataInput) GetDataInputTypeIdOk() (*string, bool)`

GetDataInputTypeIdOk returns a tuple with the DataInputTypeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataInputTypeId

`func (o *DataInput) SetDataInputTypeId(v string)`

SetDataInputTypeId sets DataInputTypeId field to given value.

### HasDataInputTypeId

`func (o *DataInput) HasDataInputTypeId() bool`

HasDataInputTypeId returns a boolean if a field has been set.

### GetName

`func (o *DataInput) GetName() NameReference`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DataInput) GetNameOk() (*NameReference, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DataInput) SetName(v NameReference)`

SetName sets Name field to given value.

### HasName

`func (o *DataInput) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDataInputType

`func (o *DataInput) GetDataInputType() string`

GetDataInputType returns the DataInputType field if non-nil, zero value otherwise.

### GetDataInputTypeOk

`func (o *DataInput) GetDataInputTypeOk() (*string, bool)`

GetDataInputTypeOk returns a tuple with the DataInputType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataInputType

`func (o *DataInput) SetDataInputType(v string)`

SetDataInputType sets DataInputType field to given value.

### HasDataInputType

`func (o *DataInput) HasDataInputType() bool`

HasDataInputType returns a boolean if a field has been set.

### GetUnits

`func (o *DataInput) GetUnits() []Unit`

GetUnits returns the Units field if non-nil, zero value otherwise.

### GetUnitsOk

`func (o *DataInput) GetUnitsOk() (*[]Unit, bool)`

GetUnitsOk returns a tuple with the Units field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnits

`func (o *DataInput) SetUnits(v []Unit)`

SetUnits sets Units field to given value.

### HasUnits

`func (o *DataInput) HasUnits() bool`

HasUnits returns a boolean if a field has been set.

### GetLabourTime

`func (o *DataInput) GetLabourTime() int32`

GetLabourTime returns the LabourTime field if non-nil, zero value otherwise.

### GetLabourTimeOk

`func (o *DataInput) GetLabourTimeOk() (*int32, bool)`

GetLabourTimeOk returns a tuple with the LabourTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabourTime

`func (o *DataInput) SetLabourTime(v int32)`

SetLabourTime sets LabourTime field to given value.

### HasLabourTime

`func (o *DataInput) HasLabourTime() bool`

HasLabourTime returns a boolean if a field has been set.

### GetIsMandatory

`func (o *DataInput) GetIsMandatory() bool`

GetIsMandatory returns the IsMandatory field if non-nil, zero value otherwise.

### GetIsMandatoryOk

`func (o *DataInput) GetIsMandatoryOk() (*bool, bool)`

GetIsMandatoryOk returns a tuple with the IsMandatory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsMandatory

`func (o *DataInput) SetIsMandatory(v bool)`

SetIsMandatory sets IsMandatory field to given value.

### HasIsMandatory

`func (o *DataInput) HasIsMandatory() bool`

HasIsMandatory returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


