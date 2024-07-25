# Data

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Id | [optional] 
**Value** | Pointer to [**Value**](Value.md) |  | [optional] 
**Variant** | Pointer to [**Variant**](Variant.md) |  | [optional] 
**Criteria** | Pointer to [**Criteria**](Criteria.md) |  | [optional] 
**Guides** | Pointer to [**[]GuideReference**](GuideReference.md) | A list of Guide References | [optional] 
**Images** | Pointer to [**[]Image**](Image.md) | A list of Images | [optional] 
**Tables** | Pointer to [**[]Table**](Table.md) | A list of Tables | [optional] 
**Notes** | Pointer to [**[]Note**](Note.md) | A list of Notes | [optional] 

## Methods

### NewData

`func NewData() *Data`

NewData instantiates a new Data object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDataWithDefaults

`func NewDataWithDefaults() *Data`

NewDataWithDefaults instantiates a new Data object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Data) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Data) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Data) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Data) HasId() bool`

HasId returns a boolean if a field has been set.

### GetValue

`func (o *Data) GetValue() Value`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *Data) GetValueOk() (*Value, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *Data) SetValue(v Value)`

SetValue sets Value field to given value.

### HasValue

`func (o *Data) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetVariant

`func (o *Data) GetVariant() Variant`

GetVariant returns the Variant field if non-nil, zero value otherwise.

### GetVariantOk

`func (o *Data) GetVariantOk() (*Variant, bool)`

GetVariantOk returns a tuple with the Variant field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVariant

`func (o *Data) SetVariant(v Variant)`

SetVariant sets Variant field to given value.

### HasVariant

`func (o *Data) HasVariant() bool`

HasVariant returns a boolean if a field has been set.

### GetCriteria

`func (o *Data) GetCriteria() Criteria`

GetCriteria returns the Criteria field if non-nil, zero value otherwise.

### GetCriteriaOk

`func (o *Data) GetCriteriaOk() (*Criteria, bool)`

GetCriteriaOk returns a tuple with the Criteria field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCriteria

`func (o *Data) SetCriteria(v Criteria)`

SetCriteria sets Criteria field to given value.

### HasCriteria

`func (o *Data) HasCriteria() bool`

HasCriteria returns a boolean if a field has been set.

### GetGuides

`func (o *Data) GetGuides() []GuideReference`

GetGuides returns the Guides field if non-nil, zero value otherwise.

### GetGuidesOk

`func (o *Data) GetGuidesOk() (*[]GuideReference, bool)`

GetGuidesOk returns a tuple with the Guides field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuides

`func (o *Data) SetGuides(v []GuideReference)`

SetGuides sets Guides field to given value.

### HasGuides

`func (o *Data) HasGuides() bool`

HasGuides returns a boolean if a field has been set.

### GetImages

`func (o *Data) GetImages() []Image`

GetImages returns the Images field if non-nil, zero value otherwise.

### GetImagesOk

`func (o *Data) GetImagesOk() (*[]Image, bool)`

GetImagesOk returns a tuple with the Images field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImages

`func (o *Data) SetImages(v []Image)`

SetImages sets Images field to given value.

### HasImages

`func (o *Data) HasImages() bool`

HasImages returns a boolean if a field has been set.

### GetTables

`func (o *Data) GetTables() []Table`

GetTables returns the Tables field if non-nil, zero value otherwise.

### GetTablesOk

`func (o *Data) GetTablesOk() (*[]Table, bool)`

GetTablesOk returns a tuple with the Tables field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTables

`func (o *Data) SetTables(v []Table)`

SetTables sets Tables field to given value.

### HasTables

`func (o *Data) HasTables() bool`

HasTables returns a boolean if a field has been set.

### GetNotes

`func (o *Data) GetNotes() []Note`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *Data) GetNotesOk() (*[]Note, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *Data) SetNotes(v []Note)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *Data) HasNotes() bool`

HasNotes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


