# RepairTimesJobLinkDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Id | [optional] 
**Hint** | Pointer to **string** | Hint | [optional] 
**Order** | Pointer to **int32** | Order | [optional] 
**TotalRepairTime** | Pointer to **int32** | Total Repair Time | [optional] 
**AssociatedWorks** | Pointer to [**[]RepairTimesAssociatedWork**](RepairTimesAssociatedWork.md) | Includes the tasks that are covered for this job link type. | [optional] 
**LinkCriteria** | Pointer to [**RepairTimesLinkCriteria**](RepairTimesLinkCriteria.md) |  | [optional] 

## Methods

### NewRepairTimesJobLinkDetails

`func NewRepairTimesJobLinkDetails() *RepairTimesJobLinkDetails`

NewRepairTimesJobLinkDetails instantiates a new RepairTimesJobLinkDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRepairTimesJobLinkDetailsWithDefaults

`func NewRepairTimesJobLinkDetailsWithDefaults() *RepairTimesJobLinkDetails`

NewRepairTimesJobLinkDetailsWithDefaults instantiates a new RepairTimesJobLinkDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RepairTimesJobLinkDetails) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RepairTimesJobLinkDetails) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RepairTimesJobLinkDetails) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *RepairTimesJobLinkDetails) HasId() bool`

HasId returns a boolean if a field has been set.

### GetHint

`func (o *RepairTimesJobLinkDetails) GetHint() string`

GetHint returns the Hint field if non-nil, zero value otherwise.

### GetHintOk

`func (o *RepairTimesJobLinkDetails) GetHintOk() (*string, bool)`

GetHintOk returns a tuple with the Hint field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHint

`func (o *RepairTimesJobLinkDetails) SetHint(v string)`

SetHint sets Hint field to given value.

### HasHint

`func (o *RepairTimesJobLinkDetails) HasHint() bool`

HasHint returns a boolean if a field has been set.

### GetOrder

`func (o *RepairTimesJobLinkDetails) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *RepairTimesJobLinkDetails) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *RepairTimesJobLinkDetails) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *RepairTimesJobLinkDetails) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetTotalRepairTime

`func (o *RepairTimesJobLinkDetails) GetTotalRepairTime() int32`

GetTotalRepairTime returns the TotalRepairTime field if non-nil, zero value otherwise.

### GetTotalRepairTimeOk

`func (o *RepairTimesJobLinkDetails) GetTotalRepairTimeOk() (*int32, bool)`

GetTotalRepairTimeOk returns a tuple with the TotalRepairTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalRepairTime

`func (o *RepairTimesJobLinkDetails) SetTotalRepairTime(v int32)`

SetTotalRepairTime sets TotalRepairTime field to given value.

### HasTotalRepairTime

`func (o *RepairTimesJobLinkDetails) HasTotalRepairTime() bool`

HasTotalRepairTime returns a boolean if a field has been set.

### GetAssociatedWorks

`func (o *RepairTimesJobLinkDetails) GetAssociatedWorks() []RepairTimesAssociatedWork`

GetAssociatedWorks returns the AssociatedWorks field if non-nil, zero value otherwise.

### GetAssociatedWorksOk

`func (o *RepairTimesJobLinkDetails) GetAssociatedWorksOk() (*[]RepairTimesAssociatedWork, bool)`

GetAssociatedWorksOk returns a tuple with the AssociatedWorks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssociatedWorks

`func (o *RepairTimesJobLinkDetails) SetAssociatedWorks(v []RepairTimesAssociatedWork)`

SetAssociatedWorks sets AssociatedWorks field to given value.

### HasAssociatedWorks

`func (o *RepairTimesJobLinkDetails) HasAssociatedWorks() bool`

HasAssociatedWorks returns a boolean if a field has been set.

### GetLinkCriteria

`func (o *RepairTimesJobLinkDetails) GetLinkCriteria() RepairTimesLinkCriteria`

GetLinkCriteria returns the LinkCriteria field if non-nil, zero value otherwise.

### GetLinkCriteriaOk

`func (o *RepairTimesJobLinkDetails) GetLinkCriteriaOk() (*RepairTimesLinkCriteria, bool)`

GetLinkCriteriaOk returns a tuple with the LinkCriteria field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkCriteria

`func (o *RepairTimesJobLinkDetails) SetLinkCriteria(v RepairTimesLinkCriteria)`

SetLinkCriteria sets LinkCriteria field to given value.

### HasLinkCriteria

`func (o *RepairTimesJobLinkDetails) HasLinkCriteria() bool`

HasLinkCriteria returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


