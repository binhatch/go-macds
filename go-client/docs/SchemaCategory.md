# SchemaCategory

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Id | [optional] 
**Name** | Pointer to [**NameReference**](NameReference.md) |  | [optional] 
**Icon** | Pointer to [**ObjectReferenceContainer**](ObjectReferenceContainer.md) |  | [optional] 
**Items** | Pointer to [**[]SchemaItem**](SchemaItem.md) | List of items | [optional] 
**Order** | Pointer to **int32** | Order | [optional] 

## Methods

### NewSchemaCategory

`func NewSchemaCategory() *SchemaCategory`

NewSchemaCategory instantiates a new SchemaCategory object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSchemaCategoryWithDefaults

`func NewSchemaCategoryWithDefaults() *SchemaCategory`

NewSchemaCategoryWithDefaults instantiates a new SchemaCategory object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SchemaCategory) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SchemaCategory) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SchemaCategory) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *SchemaCategory) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *SchemaCategory) GetName() NameReference`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SchemaCategory) GetNameOk() (*NameReference, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SchemaCategory) SetName(v NameReference)`

SetName sets Name field to given value.

### HasName

`func (o *SchemaCategory) HasName() bool`

HasName returns a boolean if a field has been set.

### GetIcon

`func (o *SchemaCategory) GetIcon() ObjectReferenceContainer`

GetIcon returns the Icon field if non-nil, zero value otherwise.

### GetIconOk

`func (o *SchemaCategory) GetIconOk() (*ObjectReferenceContainer, bool)`

GetIconOk returns a tuple with the Icon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcon

`func (o *SchemaCategory) SetIcon(v ObjectReferenceContainer)`

SetIcon sets Icon field to given value.

### HasIcon

`func (o *SchemaCategory) HasIcon() bool`

HasIcon returns a boolean if a field has been set.

### GetItems

`func (o *SchemaCategory) GetItems() []SchemaItem`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *SchemaCategory) GetItemsOk() (*[]SchemaItem, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *SchemaCategory) SetItems(v []SchemaItem)`

SetItems sets Items field to given value.

### HasItems

`func (o *SchemaCategory) HasItems() bool`

HasItems returns a boolean if a field has been set.

### GetOrder

`func (o *SchemaCategory) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *SchemaCategory) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *SchemaCategory) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *SchemaCategory) HasOrder() bool`

HasOrder returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


