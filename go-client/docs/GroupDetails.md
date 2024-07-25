# GroupDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Level** | Pointer to **int32** | Level | [optional] 
**Order** | Pointer to **int32** | Order | [optional] 
**Data** | Pointer to [**[]Data**](Data.md) | The contained Data | [optional] 
**Id** | Pointer to **string** | Id | [optional] 
**Text** | Pointer to [**Translation**](Translation.md) |  | [optional] 
**Groups** | Pointer to [**[]GroupDetails**](GroupDetails.md) | Another list of Group Details (recursive) | [optional] 

## Methods

### NewGroupDetails

`func NewGroupDetails() *GroupDetails`

NewGroupDetails instantiates a new GroupDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupDetailsWithDefaults

`func NewGroupDetailsWithDefaults() *GroupDetails`

NewGroupDetailsWithDefaults instantiates a new GroupDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLevel

`func (o *GroupDetails) GetLevel() int32`

GetLevel returns the Level field if non-nil, zero value otherwise.

### GetLevelOk

`func (o *GroupDetails) GetLevelOk() (*int32, bool)`

GetLevelOk returns a tuple with the Level field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLevel

`func (o *GroupDetails) SetLevel(v int32)`

SetLevel sets Level field to given value.

### HasLevel

`func (o *GroupDetails) HasLevel() bool`

HasLevel returns a boolean if a field has been set.

### GetOrder

`func (o *GroupDetails) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *GroupDetails) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *GroupDetails) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *GroupDetails) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetData

`func (o *GroupDetails) GetData() []Data`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *GroupDetails) GetDataOk() (*[]Data, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *GroupDetails) SetData(v []Data)`

SetData sets Data field to given value.

### HasData

`func (o *GroupDetails) HasData() bool`

HasData returns a boolean if a field has been set.

### GetId

`func (o *GroupDetails) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GroupDetails) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GroupDetails) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *GroupDetails) HasId() bool`

HasId returns a boolean if a field has been set.

### GetText

`func (o *GroupDetails) GetText() Translation`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *GroupDetails) GetTextOk() (*Translation, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *GroupDetails) SetText(v Translation)`

SetText sets Text field to given value.

### HasText

`func (o *GroupDetails) HasText() bool`

HasText returns a boolean if a field has been set.

### GetGroups

`func (o *GroupDetails) GetGroups() []GroupDetails`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *GroupDetails) GetGroupsOk() (*[]GroupDetails, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *GroupDetails) SetGroups(v []GroupDetails)`

SetGroups sets Groups field to given value.

### HasGroups

`func (o *GroupDetails) HasGroups() bool`

HasGroups returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


