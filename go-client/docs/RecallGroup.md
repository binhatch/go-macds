# RecallGroup

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**RecallItems** | Pointer to [**[]RecallItem**](RecallItem.md) | List of Recall Items | [optional] 

## Methods

### NewRecallGroup

`func NewRecallGroup() *RecallGroup`

NewRecallGroup instantiates a new RecallGroup object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecallGroupWithDefaults

`func NewRecallGroupWithDefaults() *RecallGroup`

NewRecallGroupWithDefaults instantiates a new RecallGroup object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRecallItems

`func (o *RecallGroup) GetRecallItems() []RecallItem`

GetRecallItems returns the RecallItems field if non-nil, zero value otherwise.

### GetRecallItemsOk

`func (o *RecallGroup) GetRecallItemsOk() (*[]RecallItem, bool)`

GetRecallItemsOk returns a tuple with the RecallItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecallItems

`func (o *RecallGroup) SetRecallItems(v []RecallItem)`

SetRecallItems sets RecallItems field to given value.

### HasRecallItems

`func (o *RecallGroup) HasRecallItems() bool`

HasRecallItems returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


