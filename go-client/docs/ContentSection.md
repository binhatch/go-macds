# ContentSection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Order** | Pointer to **int32** | Order | [optional] 
**ContentColumns** | Pointer to [**[]ContentColumn**](ContentColumn.md) | List of Content Columns | [optional] 

## Methods

### NewContentSection

`func NewContentSection() *ContentSection`

NewContentSection instantiates a new ContentSection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContentSectionWithDefaults

`func NewContentSectionWithDefaults() *ContentSection`

NewContentSectionWithDefaults instantiates a new ContentSection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrder

`func (o *ContentSection) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *ContentSection) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *ContentSection) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *ContentSection) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetContentColumns

`func (o *ContentSection) GetContentColumns() []ContentColumn`

GetContentColumns returns the ContentColumns field if non-nil, zero value otherwise.

### GetContentColumnsOk

`func (o *ContentSection) GetContentColumnsOk() (*[]ContentColumn, bool)`

GetContentColumnsOk returns a tuple with the ContentColumns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentColumns

`func (o *ContentSection) SetContentColumns(v []ContentColumn)`

SetContentColumns sets ContentColumns field to given value.

### HasContentColumns

`func (o *ContentSection) HasContentColumns() bool`

HasContentColumns returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


