# RepairTimesCategoryResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | Name | [optional] 
**Code** | Pointer to **string** | Code | [optional] 
**Id** | Pointer to **int32** | Id | [optional] 
**Order** | Pointer to **int32** | Order | [optional] 
**SubCategories** | Pointer to [**[]RepairTimesCategoryResponse**](RepairTimesCategoryResponse.md) | A list of Repair Time Sub Categories (recursive) | [optional] 

## Methods

### NewRepairTimesCategoryResponse

`func NewRepairTimesCategoryResponse() *RepairTimesCategoryResponse`

NewRepairTimesCategoryResponse instantiates a new RepairTimesCategoryResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRepairTimesCategoryResponseWithDefaults

`func NewRepairTimesCategoryResponseWithDefaults() *RepairTimesCategoryResponse`

NewRepairTimesCategoryResponseWithDefaults instantiates a new RepairTimesCategoryResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *RepairTimesCategoryResponse) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *RepairTimesCategoryResponse) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *RepairTimesCategoryResponse) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *RepairTimesCategoryResponse) HasName() bool`

HasName returns a boolean if a field has been set.

### GetCode

`func (o *RepairTimesCategoryResponse) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *RepairTimesCategoryResponse) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *RepairTimesCategoryResponse) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *RepairTimesCategoryResponse) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetId

`func (o *RepairTimesCategoryResponse) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RepairTimesCategoryResponse) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RepairTimesCategoryResponse) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *RepairTimesCategoryResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetOrder

`func (o *RepairTimesCategoryResponse) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *RepairTimesCategoryResponse) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *RepairTimesCategoryResponse) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *RepairTimesCategoryResponse) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetSubCategories

`func (o *RepairTimesCategoryResponse) GetSubCategories() []RepairTimesCategoryResponse`

GetSubCategories returns the SubCategories field if non-nil, zero value otherwise.

### GetSubCategoriesOk

`func (o *RepairTimesCategoryResponse) GetSubCategoriesOk() (*[]RepairTimesCategoryResponse, bool)`

GetSubCategoriesOk returns a tuple with the SubCategories field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubCategories

`func (o *RepairTimesCategoryResponse) SetSubCategories(v []RepairTimesCategoryResponse)`

SetSubCategories sets SubCategories field to given value.

### HasSubCategories

`func (o *RepairTimesCategoryResponse) HasSubCategories() bool`

HasSubCategories returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


