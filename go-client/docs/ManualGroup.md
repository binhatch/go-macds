# ManualGroup

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Id | [optional] 
**Title** | Pointer to **string** | Title | [optional] 
**Manuals** | Pointer to [**[]Manual**](Manual.md) | List of Manuals | [optional] 

## Methods

### NewManualGroup

`func NewManualGroup() *ManualGroup`

NewManualGroup instantiates a new ManualGroup object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewManualGroupWithDefaults

`func NewManualGroupWithDefaults() *ManualGroup`

NewManualGroupWithDefaults instantiates a new ManualGroup object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ManualGroup) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ManualGroup) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ManualGroup) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ManualGroup) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTitle

`func (o *ManualGroup) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ManualGroup) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ManualGroup) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *ManualGroup) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetManuals

`func (o *ManualGroup) GetManuals() []Manual`

GetManuals returns the Manuals field if non-nil, zero value otherwise.

### GetManualsOk

`func (o *ManualGroup) GetManualsOk() (*[]Manual, bool)`

GetManualsOk returns a tuple with the Manuals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManuals

`func (o *ManualGroup) SetManuals(v []Manual)`

SetManuals sets Manuals field to given value.

### HasManuals

`func (o *ManualGroup) HasManuals() bool`

HasManuals returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


