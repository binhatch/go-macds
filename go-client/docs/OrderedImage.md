# OrderedImage

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Order** | Pointer to **int64** | Order | [optional] 
**ObjectReference** | Pointer to [**ObjectReference**](ObjectReference.md) |  | [optional] 

## Methods

### NewOrderedImage

`func NewOrderedImage() *OrderedImage`

NewOrderedImage instantiates a new OrderedImage object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOrderedImageWithDefaults

`func NewOrderedImageWithDefaults() *OrderedImage`

NewOrderedImageWithDefaults instantiates a new OrderedImage object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrder

`func (o *OrderedImage) GetOrder() int64`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *OrderedImage) GetOrderOk() (*int64, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *OrderedImage) SetOrder(v int64)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *OrderedImage) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetObjectReference

`func (o *OrderedImage) GetObjectReference() ObjectReference`

GetObjectReference returns the ObjectReference field if non-nil, zero value otherwise.

### GetObjectReferenceOk

`func (o *OrderedImage) GetObjectReferenceOk() (*ObjectReference, bool)`

GetObjectReferenceOk returns a tuple with the ObjectReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectReference

`func (o *OrderedImage) SetObjectReference(v ObjectReference)`

SetObjectReference sets ObjectReference field to given value.

### HasObjectReference

`func (o *OrderedImage) HasObjectReference() bool`

HasObjectReference returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


