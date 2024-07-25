# RepairTimesJobResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ktype** | Pointer to **int32** | KType | [optional] 
**Category** | Pointer to **string** | Category | [optional] 
**SubCategory** | Pointer to **string** | Sub Category | [optional] 
**RepairTimes** | Pointer to [**[]RepairTime**](RepairTime.md) | Repair Times | [optional] 

## Methods

### NewRepairTimesJobResponse

`func NewRepairTimesJobResponse() *RepairTimesJobResponse`

NewRepairTimesJobResponse instantiates a new RepairTimesJobResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRepairTimesJobResponseWithDefaults

`func NewRepairTimesJobResponseWithDefaults() *RepairTimesJobResponse`

NewRepairTimesJobResponseWithDefaults instantiates a new RepairTimesJobResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKtype

`func (o *RepairTimesJobResponse) GetKtype() int32`

GetKtype returns the Ktype field if non-nil, zero value otherwise.

### GetKtypeOk

`func (o *RepairTimesJobResponse) GetKtypeOk() (*int32, bool)`

GetKtypeOk returns a tuple with the Ktype field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKtype

`func (o *RepairTimesJobResponse) SetKtype(v int32)`

SetKtype sets Ktype field to given value.

### HasKtype

`func (o *RepairTimesJobResponse) HasKtype() bool`

HasKtype returns a boolean if a field has been set.

### GetCategory

`func (o *RepairTimesJobResponse) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *RepairTimesJobResponse) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *RepairTimesJobResponse) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *RepairTimesJobResponse) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetSubCategory

`func (o *RepairTimesJobResponse) GetSubCategory() string`

GetSubCategory returns the SubCategory field if non-nil, zero value otherwise.

### GetSubCategoryOk

`func (o *RepairTimesJobResponse) GetSubCategoryOk() (*string, bool)`

GetSubCategoryOk returns a tuple with the SubCategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubCategory

`func (o *RepairTimesJobResponse) SetSubCategory(v string)`

SetSubCategory sets SubCategory field to given value.

### HasSubCategory

`func (o *RepairTimesJobResponse) HasSubCategory() bool`

HasSubCategory returns a boolean if a field has been set.

### GetRepairTimes

`func (o *RepairTimesJobResponse) GetRepairTimes() []RepairTime`

GetRepairTimes returns the RepairTimes field if non-nil, zero value otherwise.

### GetRepairTimesOk

`func (o *RepairTimesJobResponse) GetRepairTimesOk() (*[]RepairTime, bool)`

GetRepairTimesOk returns a tuple with the RepairTimes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepairTimes

`func (o *RepairTimesJobResponse) SetRepairTimes(v []RepairTime)`

SetRepairTimes sets RepairTimes field to given value.

### HasRepairTimes

`func (o *RepairTimesJobResponse) HasRepairTimes() bool`

HasRepairTimes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


