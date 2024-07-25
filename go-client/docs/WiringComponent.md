# WiringComponent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | Pointer to **string** | Type of the component | [optional] 
**Id** | Pointer to **string** | Id of the component | [optional] 
**Group** | Pointer to [**Translation**](Translation.md) |  | [optional] 
**Text** | Pointer to [**Translation**](Translation.md) |  | [optional] 

## Methods

### NewWiringComponent

`func NewWiringComponent() *WiringComponent`

NewWiringComponent instantiates a new WiringComponent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWiringComponentWithDefaults

`func NewWiringComponentWithDefaults() *WiringComponent`

NewWiringComponentWithDefaults instantiates a new WiringComponent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *WiringComponent) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *WiringComponent) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *WiringComponent) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *WiringComponent) HasType() bool`

HasType returns a boolean if a field has been set.

### GetId

`func (o *WiringComponent) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *WiringComponent) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *WiringComponent) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *WiringComponent) HasId() bool`

HasId returns a boolean if a field has been set.

### GetGroup

`func (o *WiringComponent) GetGroup() Translation`

GetGroup returns the Group field if non-nil, zero value otherwise.

### GetGroupOk

`func (o *WiringComponent) GetGroupOk() (*Translation, bool)`

GetGroupOk returns a tuple with the Group field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroup

`func (o *WiringComponent) SetGroup(v Translation)`

SetGroup sets Group field to given value.

### HasGroup

`func (o *WiringComponent) HasGroup() bool`

HasGroup returns a boolean if a field has been set.

### GetText

`func (o *WiringComponent) GetText() Translation`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *WiringComponent) GetTextOk() (*Translation, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *WiringComponent) SetText(v Translation)`

SetText sets Text field to given value.

### HasText

`func (o *WiringComponent) HasText() bool`

HasText returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


