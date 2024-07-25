# Variant

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Id | [optional] 
**Name** | Pointer to [**Name**](Name.md) |  | [optional] 

## Methods

### NewVariant

`func NewVariant() *Variant`

NewVariant instantiates a new Variant object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVariantWithDefaults

`func NewVariantWithDefaults() *Variant`

NewVariantWithDefaults instantiates a new Variant object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Variant) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Variant) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Variant) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Variant) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *Variant) GetName() Name`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Variant) GetNameOk() (*Name, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Variant) SetName(v Name)`

SetName sets Name field to given value.

### HasName

`func (o *Variant) HasName() bool`

HasName returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


