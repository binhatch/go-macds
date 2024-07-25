# SystemGroup

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Order** | Pointer to **int32** | Indicates the order of appearance, e.g. in a GUI. | [optional] 
**Text** | Pointer to [**Translation**](Translation.md) |  | [optional] 
**SystemTypes** | Pointer to [**[]SystemType**](SystemType.md) | Contains the systems associated with the system group. | [optional] 
**SystemGroups** | Pointer to [**[]SystemGroup**](SystemGroup.md) | Another list of System Groups (recursive) | [optional] 

## Methods

### NewSystemGroup

`func NewSystemGroup() *SystemGroup`

NewSystemGroup instantiates a new SystemGroup object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemGroupWithDefaults

`func NewSystemGroupWithDefaults() *SystemGroup`

NewSystemGroupWithDefaults instantiates a new SystemGroup object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrder

`func (o *SystemGroup) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *SystemGroup) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *SystemGroup) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *SystemGroup) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetText

`func (o *SystemGroup) GetText() Translation`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *SystemGroup) GetTextOk() (*Translation, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *SystemGroup) SetText(v Translation)`

SetText sets Text field to given value.

### HasText

`func (o *SystemGroup) HasText() bool`

HasText returns a boolean if a field has been set.

### GetSystemTypes

`func (o *SystemGroup) GetSystemTypes() []SystemType`

GetSystemTypes returns the SystemTypes field if non-nil, zero value otherwise.

### GetSystemTypesOk

`func (o *SystemGroup) GetSystemTypesOk() (*[]SystemType, bool)`

GetSystemTypesOk returns a tuple with the SystemTypes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemTypes

`func (o *SystemGroup) SetSystemTypes(v []SystemType)`

SetSystemTypes sets SystemTypes field to given value.

### HasSystemTypes

`func (o *SystemGroup) HasSystemTypes() bool`

HasSystemTypes returns a boolean if a field has been set.

### GetSystemGroups

`func (o *SystemGroup) GetSystemGroups() []SystemGroup`

GetSystemGroups returns the SystemGroups field if non-nil, zero value otherwise.

### GetSystemGroupsOk

`func (o *SystemGroup) GetSystemGroupsOk() (*[]SystemGroup, bool)`

GetSystemGroupsOk returns a tuple with the SystemGroups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemGroups

`func (o *SystemGroup) SetSystemGroups(v []SystemGroup)`

SetSystemGroups sets SystemGroups field to given value.

### HasSystemGroups

`func (o *SystemGroup) HasSystemGroups() bool`

HasSystemGroups returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


