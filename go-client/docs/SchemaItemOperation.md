# SchemaItemOperation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Id | [optional] 
**Name** | Pointer to [**NameReference**](NameReference.md) |  | [optional] 
**SparepartOnlyRelevantIfNotOkay** | Pointer to **bool** | Spare Part only relevant if not okay | [optional] 

## Methods

### NewSchemaItemOperation

`func NewSchemaItemOperation() *SchemaItemOperation`

NewSchemaItemOperation instantiates a new SchemaItemOperation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSchemaItemOperationWithDefaults

`func NewSchemaItemOperationWithDefaults() *SchemaItemOperation`

NewSchemaItemOperationWithDefaults instantiates a new SchemaItemOperation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SchemaItemOperation) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SchemaItemOperation) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SchemaItemOperation) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SchemaItemOperation) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *SchemaItemOperation) GetName() NameReference`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *SchemaItemOperation) GetNameOk() (*NameReference, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *SchemaItemOperation) SetName(v NameReference)`

SetName sets Name field to given value.

### HasName

`func (o *SchemaItemOperation) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSparepartOnlyRelevantIfNotOkay

`func (o *SchemaItemOperation) GetSparepartOnlyRelevantIfNotOkay() bool`

GetSparepartOnlyRelevantIfNotOkay returns the SparepartOnlyRelevantIfNotOkay field if non-nil, zero value otherwise.

### GetSparepartOnlyRelevantIfNotOkayOk

`func (o *SchemaItemOperation) GetSparepartOnlyRelevantIfNotOkayOk() (*bool, bool)`

GetSparepartOnlyRelevantIfNotOkayOk returns a tuple with the SparepartOnlyRelevantIfNotOkay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSparepartOnlyRelevantIfNotOkay

`func (o *SchemaItemOperation) SetSparepartOnlyRelevantIfNotOkay(v bool)`

SetSparepartOnlyRelevantIfNotOkay sets SparepartOnlyRelevantIfNotOkay field to given value.

### HasSparepartOnlyRelevantIfNotOkay

`func (o *SchemaItemOperation) HasSparepartOnlyRelevantIfNotOkay() bool`

HasSparepartOnlyRelevantIfNotOkay returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


