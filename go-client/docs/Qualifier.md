# Qualifier

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Id | [optional] 
**Title** | Pointer to **string** | Title | [optional] 

## Methods

### NewQualifier

`func NewQualifier() *Qualifier`

NewQualifier instantiates a new Qualifier object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQualifierWithDefaults

`func NewQualifierWithDefaults() *Qualifier`

NewQualifierWithDefaults instantiates a new Qualifier object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Qualifier) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Qualifier) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Qualifier) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Qualifier) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTitle

`func (o *Qualifier) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Qualifier) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Qualifier) SetTitle(v string)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *Qualifier) HasTitle() bool`

HasTitle returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


