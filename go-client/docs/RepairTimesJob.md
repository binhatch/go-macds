# RepairTimesJob

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CalcMode** | Pointer to **int32** | This node tells you about Calculation Mode, whether this job needs to be taken into account to calculate the total repair time. It can be one of these:0 &#x3D; do not calculate, 1 &#x3D; Minimum remains, 2 &#x3D; Maximum remains | [optional] 
**Code** | Pointer to **string** | Code | [optional] 
**Name** | Pointer to **string** | Name | [optional] 
**VariantCode** | Pointer to **string** | Variant Code. Can be one of the following: EK, EL, KA, LA, WS, ZB | [optional] 
**VariantText** | Pointer to **string** | Variant Text. Can be one of the following: Electronic work, Electrical work, Body work, Paint work, Workshop work, Accessory work | [optional] 
**GenericArticleNo** | Pointer to **[]int32** | Generic Article Number | [optional] 

## Methods

### NewRepairTimesJob

`func NewRepairTimesJob() *RepairTimesJob`

NewRepairTimesJob instantiates a new RepairTimesJob object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRepairTimesJobWithDefaults

`func NewRepairTimesJobWithDefaults() *RepairTimesJob`

NewRepairTimesJobWithDefaults instantiates a new RepairTimesJob object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCalcMode

`func (o *RepairTimesJob) GetCalcMode() int32`

GetCalcMode returns the CalcMode field if non-nil, zero value otherwise.

### GetCalcModeOk

`func (o *RepairTimesJob) GetCalcModeOk() (*int32, bool)`

GetCalcModeOk returns a tuple with the CalcMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCalcMode

`func (o *RepairTimesJob) SetCalcMode(v int32)`

SetCalcMode sets CalcMode field to given value.

### HasCalcMode

`func (o *RepairTimesJob) HasCalcMode() bool`

HasCalcMode returns a boolean if a field has been set.

### GetCode

`func (o *RepairTimesJob) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *RepairTimesJob) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *RepairTimesJob) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *RepairTimesJob) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetName

`func (o *RepairTimesJob) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RepairTimesJob) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RepairTimesJob) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *RepairTimesJob) HasName() bool`

HasName returns a boolean if a field has been set.

### GetVariantCode

`func (o *RepairTimesJob) GetVariantCode() string`

GetVariantCode returns the VariantCode field if non-nil, zero value otherwise.

### GetVariantCodeOk

`func (o *RepairTimesJob) GetVariantCodeOk() (*string, bool)`

GetVariantCodeOk returns a tuple with the VariantCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariantCode

`func (o *RepairTimesJob) SetVariantCode(v string)`

SetVariantCode sets VariantCode field to given value.

### HasVariantCode

`func (o *RepairTimesJob) HasVariantCode() bool`

HasVariantCode returns a boolean if a field has been set.

### GetVariantText

`func (o *RepairTimesJob) GetVariantText() string`

GetVariantText returns the VariantText field if non-nil, zero value otherwise.

### GetVariantTextOk

`func (o *RepairTimesJob) GetVariantTextOk() (*string, bool)`

GetVariantTextOk returns a tuple with the VariantText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariantText

`func (o *RepairTimesJob) SetVariantText(v string)`

SetVariantText sets VariantText field to given value.

### HasVariantText

`func (o *RepairTimesJob) HasVariantText() bool`

HasVariantText returns a boolean if a field has been set.

### GetGenericArticleNo

`func (o *RepairTimesJob) GetGenericArticleNo() []int32`

GetGenericArticleNo returns the GenericArticleNo field if non-nil, zero value otherwise.

### GetGenericArticleNoOk

`func (o *RepairTimesJob) GetGenericArticleNoOk() (*[]int32, bool)`

GetGenericArticleNoOk returns a tuple with the GenericArticleNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenericArticleNo

`func (o *RepairTimesJob) SetGenericArticleNo(v []int32)`

SetGenericArticleNo sets GenericArticleNo field to given value.

### HasGenericArticleNo

`func (o *RepairTimesJob) HasGenericArticleNo() bool`

HasGenericArticleNo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


