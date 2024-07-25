# SystemGroupTree

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SystemGroups** | Pointer to [**[]SystemGroup**](SystemGroup.md) | Recursive element representing the categories of wiring diagrams. Most recurring categories are engine, ABS, Airbag, climate. All other categories are considered &#39;Additional&#39; and include (sub)categories such as &#39;Comfort&#39;. | [optional] 

## Methods

### NewSystemGroupTree

`func NewSystemGroupTree() *SystemGroupTree`

NewSystemGroupTree instantiates a new SystemGroupTree object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemGroupTreeWithDefaults

`func NewSystemGroupTreeWithDefaults() *SystemGroupTree`

NewSystemGroupTreeWithDefaults instantiates a new SystemGroupTree object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSystemGroups

`func (o *SystemGroupTree) GetSystemGroups() []SystemGroup`

GetSystemGroups returns the SystemGroups field if non-nil, zero value otherwise.

### GetSystemGroupsOk

`func (o *SystemGroupTree) GetSystemGroupsOk() (*[]SystemGroup, bool)`

GetSystemGroupsOk returns a tuple with the SystemGroups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemGroups

`func (o *SystemGroupTree) SetSystemGroups(v []SystemGroup)`

SetSystemGroups sets SystemGroups field to given value.

### HasSystemGroups

`func (o *SystemGroupTree) HasSystemGroups() bool`

HasSystemGroups returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


