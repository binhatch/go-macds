# SubGroup

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Id | [optional] 
**Title** | Pointer to **string** | Title | [optional] 
**ManualGroups** | Pointer to [**[]ManualGroup**](ManualGroup.md) | List of Manual Groups | [optional] 

## Methods

### NewSubGroup

`func NewSubGroup() *SubGroup`

NewSubGroup instantiates a new SubGroup object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSubGroupWithDefaults

`func NewSubGroupWithDefaults() *SubGroup`

NewSubGroupWithDefaults instantiates a new SubGroup object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SubGroup) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SubGroup) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SubGroup) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *SubGroup) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTitle

`func (o *SubGroup) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *SubGroup) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *SubGroup) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *SubGroup) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetManualGroups

`func (o *SubGroup) GetManualGroups() []ManualGroup`

GetManualGroups returns the ManualGroups field if non-nil, zero value otherwise.

### GetManualGroupsOk

`func (o *SubGroup) GetManualGroupsOk() (*[]ManualGroup, bool)`

GetManualGroupsOk returns a tuple with the ManualGroups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManualGroups

`func (o *SubGroup) SetManualGroups(v []ManualGroup)`

SetManualGroups sets ManualGroups field to given value.

### HasManualGroups

`func (o *SubGroup) HasManualGroups() bool`

HasManualGroups returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


