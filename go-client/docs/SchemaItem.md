# SchemaItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Id | [optional] 
**ShortText** | Pointer to [**ReplacementNameReference**](ReplacementNameReference.md) |  | [optional] 
**Operation** | Pointer to [**SchemaItemOperation**](SchemaItemOperation.md) |  | [optional] 
**ItemParts** | Pointer to [**[]SchemaItemPart**](SchemaItemPart.md) | List of Item Parts | [optional] 
**ServiceComponents** | Pointer to [**[]ServiceComponent**](ServiceComponent.md) | List of Service Components | [optional] 
**IsAdditional** | Pointer to **bool** | Is additional | [optional] 
**Order** | Pointer to **int32** | Order | [optional] 
**AggregatedLabourTime** | Pointer to **int32** | Aggregated Labour Time | [optional] 
**DueInDistance** | Pointer to **int32** | If mileage, date of production and possibly date and mileage of last service was provided, it is calculated when the related item is due in terms of distance left. Can also be negative, if the service is overdue. | [optional] 
**DueInDays** | Pointer to **int32** | If mileage, date of production and possibly date and mileage of last service was provided, it is calculated when the related item is due in terms of days left. Can also be negative, if the service is overdue. | [optional] 

## Methods

### NewSchemaItem

`func NewSchemaItem() *SchemaItem`

NewSchemaItem instantiates a new SchemaItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSchemaItemWithDefaults

`func NewSchemaItemWithDefaults() *SchemaItem`

NewSchemaItemWithDefaults instantiates a new SchemaItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SchemaItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SchemaItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SchemaItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SchemaItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetShortText

`func (o *SchemaItem) GetShortText() ReplacementNameReference`

GetShortText returns the ShortText field if non-nil, zero value otherwise.

### GetShortTextOk

`func (o *SchemaItem) GetShortTextOk() (*ReplacementNameReference, bool)`

GetShortTextOk returns a tuple with the ShortText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortText

`func (o *SchemaItem) SetShortText(v ReplacementNameReference)`

SetShortText sets ShortText field to given value.

### HasShortText

`func (o *SchemaItem) HasShortText() bool`

HasShortText returns a boolean if a field has been set.

### GetOperation

`func (o *SchemaItem) GetOperation() SchemaItemOperation`

GetOperation returns the Operation field if non-nil, zero value otherwise.

### GetOperationOk

`func (o *SchemaItem) GetOperationOk() (*SchemaItemOperation, bool)`

GetOperationOk returns a tuple with the Operation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperation

`func (o *SchemaItem) SetOperation(v SchemaItemOperation)`

SetOperation sets Operation field to given value.

### HasOperation

`func (o *SchemaItem) HasOperation() bool`

HasOperation returns a boolean if a field has been set.

### GetItemParts

`func (o *SchemaItem) GetItemParts() []SchemaItemPart`

GetItemParts returns the ItemParts field if non-nil, zero value otherwise.

### GetItemPartsOk

`func (o *SchemaItem) GetItemPartsOk() (*[]SchemaItemPart, bool)`

GetItemPartsOk returns a tuple with the ItemParts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItemParts

`func (o *SchemaItem) SetItemParts(v []SchemaItemPart)`

SetItemParts sets ItemParts field to given value.

### HasItemParts

`func (o *SchemaItem) HasItemParts() bool`

HasItemParts returns a boolean if a field has been set.

### GetServiceComponents

`func (o *SchemaItem) GetServiceComponents() []ServiceComponent`

GetServiceComponents returns the ServiceComponents field if non-nil, zero value otherwise.

### GetServiceComponentsOk

`func (o *SchemaItem) GetServiceComponentsOk() (*[]ServiceComponent, bool)`

GetServiceComponentsOk returns a tuple with the ServiceComponents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceComponents

`func (o *SchemaItem) SetServiceComponents(v []ServiceComponent)`

SetServiceComponents sets ServiceComponents field to given value.

### HasServiceComponents

`func (o *SchemaItem) HasServiceComponents() bool`

HasServiceComponents returns a boolean if a field has been set.

### GetIsAdditional

`func (o *SchemaItem) GetIsAdditional() bool`

GetIsAdditional returns the IsAdditional field if non-nil, zero value otherwise.

### GetIsAdditionalOk

`func (o *SchemaItem) GetIsAdditionalOk() (*bool, bool)`

GetIsAdditionalOk returns a tuple with the IsAdditional field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsAdditional

`func (o *SchemaItem) SetIsAdditional(v bool)`

SetIsAdditional sets IsAdditional field to given value.

### HasIsAdditional

`func (o *SchemaItem) HasIsAdditional() bool`

HasIsAdditional returns a boolean if a field has been set.

### GetOrder

`func (o *SchemaItem) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *SchemaItem) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *SchemaItem) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *SchemaItem) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetAggregatedLabourTime

`func (o *SchemaItem) GetAggregatedLabourTime() int32`

GetAggregatedLabourTime returns the AggregatedLabourTime field if non-nil, zero value otherwise.

### GetAggregatedLabourTimeOk

`func (o *SchemaItem) GetAggregatedLabourTimeOk() (*int32, bool)`

GetAggregatedLabourTimeOk returns a tuple with the AggregatedLabourTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAggregatedLabourTime

`func (o *SchemaItem) SetAggregatedLabourTime(v int32)`

SetAggregatedLabourTime sets AggregatedLabourTime field to given value.

### HasAggregatedLabourTime

`func (o *SchemaItem) HasAggregatedLabourTime() bool`

HasAggregatedLabourTime returns a boolean if a field has been set.

### GetDueInDistance

`func (o *SchemaItem) GetDueInDistance() int32`

GetDueInDistance returns the DueInDistance field if non-nil, zero value otherwise.

### GetDueInDistanceOk

`func (o *SchemaItem) GetDueInDistanceOk() (*int32, bool)`

GetDueInDistanceOk returns a tuple with the DueInDistance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueInDistance

`func (o *SchemaItem) SetDueInDistance(v int32)`

SetDueInDistance sets DueInDistance field to given value.

### HasDueInDistance

`func (o *SchemaItem) HasDueInDistance() bool`

HasDueInDistance returns a boolean if a field has been set.

### GetDueInDays

`func (o *SchemaItem) GetDueInDays() int32`

GetDueInDays returns the DueInDays field if non-nil, zero value otherwise.

### GetDueInDaysOk

`func (o *SchemaItem) GetDueInDaysOk() (*int32, bool)`

GetDueInDaysOk returns a tuple with the DueInDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDueInDays

`func (o *SchemaItem) SetDueInDays(v int32)`

SetDueInDays sets DueInDays field to given value.

### HasDueInDays

`func (o *SchemaItem) HasDueInDays() bool`

HasDueInDays returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


