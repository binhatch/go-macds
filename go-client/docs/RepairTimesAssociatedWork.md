# RepairTimesAssociatedWork

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Order** | Pointer to **int32** | Order in which the work item ought to be displayed, and thus executed. | [optional] 
**Display** | Pointer to **bool** | Indicates if this work item should be displayed in the UI, as it may already be appearing as repair time element text, but still have a repair time value. | [optional] 
**RepairTime** | Pointer to **int32** | Repair time value as 1/100 of hours, e.g. 0,4 would be 0,4*60 minutes &#x3D; 24 minutes | [optional] 
**Calculation** | Pointer to **int32** | 1 &#x3D; Labor Value may be calculated, 0 &#x3D; no calculation allowed | [optional] 
**Job** | Pointer to [**RepairTimesJob**](RepairTimesJob.md) |  | [optional] 

## Methods

### NewRepairTimesAssociatedWork

`func NewRepairTimesAssociatedWork() *RepairTimesAssociatedWork`

NewRepairTimesAssociatedWork instantiates a new RepairTimesAssociatedWork object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRepairTimesAssociatedWorkWithDefaults

`func NewRepairTimesAssociatedWorkWithDefaults() *RepairTimesAssociatedWork`

NewRepairTimesAssociatedWorkWithDefaults instantiates a new RepairTimesAssociatedWork object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrder

`func (o *RepairTimesAssociatedWork) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *RepairTimesAssociatedWork) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *RepairTimesAssociatedWork) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *RepairTimesAssociatedWork) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetDisplay

`func (o *RepairTimesAssociatedWork) GetDisplay() bool`

GetDisplay returns the Display field if non-nil, zero value otherwise.

### GetDisplayOk

`func (o *RepairTimesAssociatedWork) GetDisplayOk() (*bool, bool)`

GetDisplayOk returns a tuple with the Display field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplay

`func (o *RepairTimesAssociatedWork) SetDisplay(v bool)`

SetDisplay sets Display field to given value.

### HasDisplay

`func (o *RepairTimesAssociatedWork) HasDisplay() bool`

HasDisplay returns a boolean if a field has been set.

### GetRepairTime

`func (o *RepairTimesAssociatedWork) GetRepairTime() int32`

GetRepairTime returns the RepairTime field if non-nil, zero value otherwise.

### GetRepairTimeOk

`func (o *RepairTimesAssociatedWork) GetRepairTimeOk() (*int32, bool)`

GetRepairTimeOk returns a tuple with the RepairTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepairTime

`func (o *RepairTimesAssociatedWork) SetRepairTime(v int32)`

SetRepairTime sets RepairTime field to given value.

### HasRepairTime

`func (o *RepairTimesAssociatedWork) HasRepairTime() bool`

HasRepairTime returns a boolean if a field has been set.

### GetCalculation

`func (o *RepairTimesAssociatedWork) GetCalculation() int32`

GetCalculation returns the Calculation field if non-nil, zero value otherwise.

### GetCalculationOk

`func (o *RepairTimesAssociatedWork) GetCalculationOk() (*int32, bool)`

GetCalculationOk returns a tuple with the Calculation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCalculation

`func (o *RepairTimesAssociatedWork) SetCalculation(v int32)`

SetCalculation sets Calculation field to given value.

### HasCalculation

`func (o *RepairTimesAssociatedWork) HasCalculation() bool`

HasCalculation returns a boolean if a field has been set.

### GetJob

`func (o *RepairTimesAssociatedWork) GetJob() RepairTimesJob`

GetJob returns the Job field if non-nil, zero value otherwise.

### GetJobOk

`func (o *RepairTimesAssociatedWork) GetJobOk() (*RepairTimesJob, bool)`

GetJobOk returns a tuple with the Job field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJob

`func (o *RepairTimesAssociatedWork) SetJob(v RepairTimesJob)`

SetJob sets Job field to given value.

### HasJob

`func (o *RepairTimesAssociatedWork) HasJob() bool`

HasJob returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


