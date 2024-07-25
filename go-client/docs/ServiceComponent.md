# ServiceComponent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Id | [optional] 
**Name** | Pointer to [**NameReference**](NameReference.md) |  | [optional] 
**DefaultAmount** | Pointer to **int32** | Default Amount | [optional] 
**GenArtNo** | Pointer to **int64** | Generic Article Number | [optional] 

## Methods

### NewServiceComponent

`func NewServiceComponent() *ServiceComponent`

NewServiceComponent instantiates a new ServiceComponent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceComponentWithDefaults

`func NewServiceComponentWithDefaults() *ServiceComponent`

NewServiceComponentWithDefaults instantiates a new ServiceComponent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ServiceComponent) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ServiceComponent) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ServiceComponent) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ServiceComponent) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ServiceComponent) GetName() NameReference`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ServiceComponent) GetNameOk() (*NameReference, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ServiceComponent) SetName(v NameReference)`

SetName sets Name field to given value.

### HasName

`func (o *ServiceComponent) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDefaultAmount

`func (o *ServiceComponent) GetDefaultAmount() int32`

GetDefaultAmount returns the DefaultAmount field if non-nil, zero value otherwise.

### GetDefaultAmountOk

`func (o *ServiceComponent) GetDefaultAmountOk() (*int32, bool)`

GetDefaultAmountOk returns a tuple with the DefaultAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultAmount

`func (o *ServiceComponent) SetDefaultAmount(v int32)`

SetDefaultAmount sets DefaultAmount field to given value.

### HasDefaultAmount

`func (o *ServiceComponent) HasDefaultAmount() bool`

HasDefaultAmount returns a boolean if a field has been set.

### GetGenArtNo

`func (o *ServiceComponent) GetGenArtNo() int64`

GetGenArtNo returns the GenArtNo field if non-nil, zero value otherwise.

### GetGenArtNoOk

`func (o *ServiceComponent) GetGenArtNoOk() (*int64, bool)`

GetGenArtNoOk returns a tuple with the GenArtNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenArtNo

`func (o *ServiceComponent) SetGenArtNo(v int64)`

SetGenArtNo sets GenArtNo field to given value.

### HasGenArtNo

`func (o *ServiceComponent) HasGenArtNo() bool`

HasGenArtNo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


