# Icon

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Order** | Pointer to **int64** | Order | [optional] 
**ObjectReference** | Pointer to [**ObjectReference**](ObjectReference.md) |  | [optional] 
**FileExtension** | Pointer to **string** | File Extension | [optional] 

## Methods

### NewIcon

`func NewIcon() *Icon`

NewIcon instantiates a new Icon object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIconWithDefaults

`func NewIconWithDefaults() *Icon`

NewIconWithDefaults instantiates a new Icon object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrder

`func (o *Icon) GetOrder() int64`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *Icon) GetOrderOk() (*int64, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *Icon) SetOrder(v int64)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *Icon) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetObjectReference

`func (o *Icon) GetObjectReference() ObjectReference`

GetObjectReference returns the ObjectReference field if non-nil, zero value otherwise.

### GetObjectReferenceOk

`func (o *Icon) GetObjectReferenceOk() (*ObjectReference, bool)`

GetObjectReferenceOk returns a tuple with the ObjectReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectReference

`func (o *Icon) SetObjectReference(v ObjectReference)`

SetObjectReference sets ObjectReference field to given value.

### HasObjectReference

`func (o *Icon) HasObjectReference() bool`

HasObjectReference returns a boolean if a field has been set.

### GetFileExtension

`func (o *Icon) GetFileExtension() string`

GetFileExtension returns the FileExtension field if non-nil, zero value otherwise.

### GetFileExtensionOk

`func (o *Icon) GetFileExtensionOk() (*string, bool)`

GetFileExtensionOk returns a tuple with the FileExtension field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFileExtension

`func (o *Icon) SetFileExtension(v string)`

SetFileExtension sets FileExtension field to given value.

### HasFileExtension

`func (o *Icon) HasFileExtension() bool`

HasFileExtension returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


