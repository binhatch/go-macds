# MainGroup

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Id | [optional] 
**Title** | Pointer to **string** | Title | [optional] 
**SubGroups** | Pointer to [**[]SubGroup**](SubGroup.md) | List of Sub Groups | [optional] 

## Methods

### NewMainGroup

`func NewMainGroup() *MainGroup`

NewMainGroup instantiates a new MainGroup object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMainGroupWithDefaults

`func NewMainGroupWithDefaults() *MainGroup`

NewMainGroupWithDefaults instantiates a new MainGroup object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *MainGroup) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MainGroup) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MainGroup) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *MainGroup) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTitle

`func (o *MainGroup) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *MainGroup) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *MainGroup) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *MainGroup) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetSubGroups

`func (o *MainGroup) GetSubGroups() []SubGroup`

GetSubGroups returns the SubGroups field if non-nil, zero value otherwise.

### GetSubGroupsOk

`func (o *MainGroup) GetSubGroupsOk() (*[]SubGroup, bool)`

GetSubGroupsOk returns a tuple with the SubGroups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubGroups

`func (o *MainGroup) SetSubGroups(v []SubGroup)`

SetSubGroups sets SubGroups field to given value.

### HasSubGroups

`func (o *MainGroup) HasSubGroups() bool`

HasSubGroups returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


