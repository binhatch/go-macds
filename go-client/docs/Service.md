# Service

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Id | [optional] 
**Name** | Pointer to [**ReplacementNameReference**](ReplacementNameReference.md) |  | [optional] 
**Order** | Pointer to **int32** | Order | [optional] 
**Categories** | Pointer to [**[]SchemaCategory**](SchemaCategory.md) | List of Categories | [optional] 
**ReplacementIntervals** | Pointer to [**[]ReplacementInterval**](ReplacementInterval.md) | List of Replacement Intervals | [optional] 
**AggregatedLabourTime** | Pointer to **int32** | Aggregated Labour Time | [optional] 
**DueInDistance** | Pointer to **int32** | If mileage, date of production and possibly date and mileage of last service was provided, it is calculated when the related item is due in terms of distance left. Can also be negative, if the service is overdue. | [optional] 
**DueInDays** | Pointer to **int32** | If mileage, date of production and possibly date and mileage of last service was provided, it is calculated when the related item is due in terms of days left. Can also be negative, if the service is overdue. | [optional] 

## Methods

### NewService

`func NewService() *Service`

NewService instantiates a new Service object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceWithDefaults

`func NewServiceWithDefaults() *Service`

NewServiceWithDefaults instantiates a new Service object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Service) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Service) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Service) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Service) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *Service) GetName() ReplacementNameReference`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Service) GetNameOk() (*ReplacementNameReference, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Service) SetName(v ReplacementNameReference)`

SetName sets Name field to given value.

### HasName

`func (o *Service) HasName() bool`

HasName returns a boolean if a field has been set.

### GetOrder

`func (o *Service) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *Service) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *Service) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *Service) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetCategories

`func (o *Service) GetCategories() []SchemaCategory`

GetCategories returns the Categories field if non-nil, zero value otherwise.

### GetCategoriesOk

`func (o *Service) GetCategoriesOk() (*[]SchemaCategory, bool)`

GetCategoriesOk returns a tuple with the Categories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategories

`func (o *Service) SetCategories(v []SchemaCategory)`

SetCategories sets Categories field to given value.

### HasCategories

`func (o *Service) HasCategories() bool`

HasCategories returns a boolean if a field has been set.

### GetReplacementIntervals

`func (o *Service) GetReplacementIntervals() []ReplacementInterval`

GetReplacementIntervals returns the ReplacementIntervals field if non-nil, zero value otherwise.

### GetReplacementIntervalsOk

`func (o *Service) GetReplacementIntervalsOk() (*[]ReplacementInterval, bool)`

GetReplacementIntervalsOk returns a tuple with the ReplacementIntervals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplacementIntervals

`func (o *Service) SetReplacementIntervals(v []ReplacementInterval)`

SetReplacementIntervals sets ReplacementIntervals field to given value.

### HasReplacementIntervals

`func (o *Service) HasReplacementIntervals() bool`

HasReplacementIntervals returns a boolean if a field has been set.

### GetAggregatedLabourTime

`func (o *Service) GetAggregatedLabourTime() int32`

GetAggregatedLabourTime returns the AggregatedLabourTime field if non-nil, zero value otherwise.

### GetAggregatedLabourTimeOk

`func (o *Service) GetAggregatedLabourTimeOk() (*int32, bool)`

GetAggregatedLabourTimeOk returns a tuple with the AggregatedLabourTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregatedLabourTime

`func (o *Service) SetAggregatedLabourTime(v int32)`

SetAggregatedLabourTime sets AggregatedLabourTime field to given value.

### HasAggregatedLabourTime

`func (o *Service) HasAggregatedLabourTime() bool`

HasAggregatedLabourTime returns a boolean if a field has been set.

### GetDueInDistance

`func (o *Service) GetDueInDistance() int32`

GetDueInDistance returns the DueInDistance field if non-nil, zero value otherwise.

### GetDueInDistanceOk

`func (o *Service) GetDueInDistanceOk() (*int32, bool)`

GetDueInDistanceOk returns a tuple with the DueInDistance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueInDistance

`func (o *Service) SetDueInDistance(v int32)`

SetDueInDistance sets DueInDistance field to given value.

### HasDueInDistance

`func (o *Service) HasDueInDistance() bool`

HasDueInDistance returns a boolean if a field has been set.

### GetDueInDays

`func (o *Service) GetDueInDays() int32`

GetDueInDays returns the DueInDays field if non-nil, zero value otherwise.

### GetDueInDaysOk

`func (o *Service) GetDueInDaysOk() (*int32, bool)`

GetDueInDaysOk returns a tuple with the DueInDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueInDays

`func (o *Service) SetDueInDays(v int32)`

SetDueInDays sets DueInDays field to given value.

### HasDueInDays

`func (o *Service) HasDueInDays() bool`

HasDueInDays returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


