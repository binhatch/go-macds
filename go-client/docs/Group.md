# Group

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Id | [optional] 
**Text** | Pointer to [**Translation**](Translation.md) |  | [optional] 
**Data** | Pointer to [**[]Data**](Data.md) | List of Fata | [optional] 

## Methods

### NewGroup

`func NewGroup() *Group`

NewGroup instantiates a new Group object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGroupWithDefaults

`func NewGroupWithDefaults() *Group`

NewGroupWithDefaults instantiates a new Group object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Group) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Group) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Group) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Group) HasId() bool`

HasId returns a boolean if a field has been set.

### GetText

`func (o *Group) GetText() Translation`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *Group) GetTextOk() (*Translation, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *Group) SetText(v Translation)`

SetText sets Text field to given value.

### HasText

`func (o *Group) HasText() bool`

HasText returns a boolean if a field has been set.

### GetData

`func (o *Group) GetData() []Data`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *Group) GetDataOk() (*[]Data, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *Group) SetData(v []Data)`

SetData sets Data field to given value.

### HasData

`func (o *Group) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


