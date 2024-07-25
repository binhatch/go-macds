# RepairTime

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | Pointer to **string** | This is unique for each job. This node contains a string which is Alphanumeric in nature. | [optional] 
**Id** | Pointer to **int32** | uniquely identifies a job | [optional] 
**VariantCode** | Pointer to **string** | Represents the type of labor value. Each code corresponds to a specific type of work. - EK (&#x3D; Electronic work) - EL (&#x3D; Electrical work) - KA (&#x3D; Body work) - LA (&#x3D; Paint work) - WS (&#x3D; Workshop work) - ZB (&#x3D; Accessory work)  The related textual values are found in the property &#39;variantText&#39;. | [optional] 
**VariantText** | Pointer to **string** | Provides the text description of the labor value as specified by the &#39;variantCode&#39;: - Electronic work, - Electrical work, - Body work, - Paint work, - Workshop work, - Accessory work | [optional] 
**Name** | Pointer to **string** | This node tells you about the title of the job like: \&quot;Check leak-tightness of engine *\&quot;. | [optional] 
**GenericArticleNo** | Pointer to **[]int32** | List of Generic Article Numbers for a particular job, through which we can find the Spare Parts information. | [optional] 
**CalcMode** | Pointer to **int32** | This node tells you about Calculation Mode, whether this job needs to be taken into account to calculate the total repair time. It can be one of these: 0 &#x3D; do not calculate, 1 &#x3D; Minimum remains, 2 &#x3D; Maximum remains | [optional] 
**JobLinks** | Pointer to [**[]RepairTimesJobLink**](RepairTimesJobLink.md) | List of the linked jobs associated with a repair time element | [optional] 

## Methods

### NewRepairTime

`func NewRepairTime() *RepairTime`

NewRepairTime instantiates a new RepairTime object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRepairTimeWithDefaults

`func NewRepairTimeWithDefaults() *RepairTime`

NewRepairTimeWithDefaults instantiates a new RepairTime object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *RepairTime) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *RepairTime) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *RepairTime) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *RepairTime) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetId

`func (o *RepairTime) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RepairTime) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RepairTime) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *RepairTime) HasId() bool`

HasId returns a boolean if a field has been set.

### GetVariantCode

`func (o *RepairTime) GetVariantCode() string`

GetVariantCode returns the VariantCode field if non-nil, zero value otherwise.

### GetVariantCodeOk

`func (o *RepairTime) GetVariantCodeOk() (*string, bool)`

GetVariantCodeOk returns a tuple with the VariantCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariantCode

`func (o *RepairTime) SetVariantCode(v string)`

SetVariantCode sets VariantCode field to given value.

### HasVariantCode

`func (o *RepairTime) HasVariantCode() bool`

HasVariantCode returns a boolean if a field has been set.

### GetVariantText

`func (o *RepairTime) GetVariantText() string`

GetVariantText returns the VariantText field if non-nil, zero value otherwise.

### GetVariantTextOk

`func (o *RepairTime) GetVariantTextOk() (*string, bool)`

GetVariantTextOk returns a tuple with the VariantText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariantText

`func (o *RepairTime) SetVariantText(v string)`

SetVariantText sets VariantText field to given value.

### HasVariantText

`func (o *RepairTime) HasVariantText() bool`

HasVariantText returns a boolean if a field has been set.

### GetName

`func (o *RepairTime) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RepairTime) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RepairTime) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *RepairTime) HasName() bool`

HasName returns a boolean if a field has been set.

### GetGenericArticleNo

`func (o *RepairTime) GetGenericArticleNo() []int32`

GetGenericArticleNo returns the GenericArticleNo field if non-nil, zero value otherwise.

### GetGenericArticleNoOk

`func (o *RepairTime) GetGenericArticleNoOk() (*[]int32, bool)`

GetGenericArticleNoOk returns a tuple with the GenericArticleNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenericArticleNo

`func (o *RepairTime) SetGenericArticleNo(v []int32)`

SetGenericArticleNo sets GenericArticleNo field to given value.

### HasGenericArticleNo

`func (o *RepairTime) HasGenericArticleNo() bool`

HasGenericArticleNo returns a boolean if a field has been set.

### GetCalcMode

`func (o *RepairTime) GetCalcMode() int32`

GetCalcMode returns the CalcMode field if non-nil, zero value otherwise.

### GetCalcModeOk

`func (o *RepairTime) GetCalcModeOk() (*int32, bool)`

GetCalcModeOk returns a tuple with the CalcMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCalcMode

`func (o *RepairTime) SetCalcMode(v int32)`

SetCalcMode sets CalcMode field to given value.

### HasCalcMode

`func (o *RepairTime) HasCalcMode() bool`

HasCalcMode returns a boolean if a field has been set.

### GetJobLinks

`func (o *RepairTime) GetJobLinks() []RepairTimesJobLink`

GetJobLinks returns the JobLinks field if non-nil, zero value otherwise.

### GetJobLinksOk

`func (o *RepairTime) GetJobLinksOk() (*[]RepairTimesJobLink, bool)`

GetJobLinksOk returns a tuple with the JobLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobLinks

`func (o *RepairTime) SetJobLinks(v []RepairTimesJobLink)`

SetJobLinks sets JobLinks field to given value.

### HasJobLinks

`func (o *RepairTime) HasJobLinks() bool`

HasJobLinks returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


