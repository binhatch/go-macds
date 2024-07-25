# SchemaItemPart

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Id | [optional] 
**DataInputs** | Pointer to [**[]DataInput**](DataInput.md) | List of Data Inputs | [optional] 
**ServiceComponents** | Pointer to [**[]ServiceComponent**](ServiceComponent.md) | List of Service Components | [optional] 
**DisplayGroups** | Pointer to [**[]ObjectReferenceContainer**](ObjectReferenceContainer.md) | List of Display Groups | [optional] 
**LabourTime** | Pointer to **int32** | Labour Time | [optional] 
**Awid** | Pointer to **string** | AW Id | [optional] 
**RelatedTechData** | Pointer to [**[]Group**](Group.md) | List of related Tech Data | [optional] 

## Methods

### NewSchemaItemPart

`func NewSchemaItemPart() *SchemaItemPart`

NewSchemaItemPart instantiates a new SchemaItemPart object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSchemaItemPartWithDefaults

`func NewSchemaItemPartWithDefaults() *SchemaItemPart`

NewSchemaItemPartWithDefaults instantiates a new SchemaItemPart object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SchemaItemPart) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SchemaItemPart) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SchemaItemPart) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SchemaItemPart) HasId() bool`

HasId returns a boolean if a field has been set.

### GetDataInputs

`func (o *SchemaItemPart) GetDataInputs() []DataInput`

GetDataInputs returns the DataInputs field if non-nil, zero value otherwise.

### GetDataInputsOk

`func (o *SchemaItemPart) GetDataInputsOk() (*[]DataInput, bool)`

GetDataInputsOk returns a tuple with the DataInputs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataInputs

`func (o *SchemaItemPart) SetDataInputs(v []DataInput)`

SetDataInputs sets DataInputs field to given value.

### HasDataInputs

`func (o *SchemaItemPart) HasDataInputs() bool`

HasDataInputs returns a boolean if a field has been set.

### GetServiceComponents

`func (o *SchemaItemPart) GetServiceComponents() []ServiceComponent`

GetServiceComponents returns the ServiceComponents field if non-nil, zero value otherwise.

### GetServiceComponentsOk

`func (o *SchemaItemPart) GetServiceComponentsOk() (*[]ServiceComponent, bool)`

GetServiceComponentsOk returns a tuple with the ServiceComponents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceComponents

`func (o *SchemaItemPart) SetServiceComponents(v []ServiceComponent)`

SetServiceComponents sets ServiceComponents field to given value.

### HasServiceComponents

`func (o *SchemaItemPart) HasServiceComponents() bool`

HasServiceComponents returns a boolean if a field has been set.

### GetDisplayGroups

`func (o *SchemaItemPart) GetDisplayGroups() []ObjectReferenceContainer`

GetDisplayGroups returns the DisplayGroups field if non-nil, zero value otherwise.

### GetDisplayGroupsOk

`func (o *SchemaItemPart) GetDisplayGroupsOk() (*[]ObjectReferenceContainer, bool)`

GetDisplayGroupsOk returns a tuple with the DisplayGroups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayGroups

`func (o *SchemaItemPart) SetDisplayGroups(v []ObjectReferenceContainer)`

SetDisplayGroups sets DisplayGroups field to given value.

### HasDisplayGroups

`func (o *SchemaItemPart) HasDisplayGroups() bool`

HasDisplayGroups returns a boolean if a field has been set.

### GetLabourTime

`func (o *SchemaItemPart) GetLabourTime() int32`

GetLabourTime returns the LabourTime field if non-nil, zero value otherwise.

### GetLabourTimeOk

`func (o *SchemaItemPart) GetLabourTimeOk() (*int32, bool)`

GetLabourTimeOk returns a tuple with the LabourTime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabourTime

`func (o *SchemaItemPart) SetLabourTime(v int32)`

SetLabourTime sets LabourTime field to given value.

### HasLabourTime

`func (o *SchemaItemPart) HasLabourTime() bool`

HasLabourTime returns a boolean if a field has been set.

### GetAwid

`func (o *SchemaItemPart) GetAwid() string`

GetAwid returns the Awid field if non-nil, zero value otherwise.

### GetAwidOk

`func (o *SchemaItemPart) GetAwidOk() (*string, bool)`

GetAwidOk returns a tuple with the Awid field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAwid

`func (o *SchemaItemPart) SetAwid(v string)`

SetAwid sets Awid field to given value.

### HasAwid

`func (o *SchemaItemPart) HasAwid() bool`

HasAwid returns a boolean if a field has been set.

### GetRelatedTechData

`func (o *SchemaItemPart) GetRelatedTechData() []Group`

GetRelatedTechData returns the RelatedTechData field if non-nil, zero value otherwise.

### GetRelatedTechDataOk

`func (o *SchemaItemPart) GetRelatedTechDataOk() (*[]Group, bool)`

GetRelatedTechDataOk returns a tuple with the RelatedTechData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelatedTechData

`func (o *SchemaItemPart) SetRelatedTechData(v []Group)`

SetRelatedTechData sets RelatedTechData field to given value.

### HasRelatedTechData

`func (o *SchemaItemPart) HasRelatedTechData() bool`

HasRelatedTechData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


