# Error

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | Pointer to **string** | Error code | [optional] 
**Description** | Pointer to **string** | Error description | [optional] 
**Details** | Pointer to **[]string** | Error details | [optional] 

## Methods

### NewError

`func NewError() *Error`

NewError instantiates a new Error object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewErrorWithDefaults

`func NewErrorWithDefaults() *Error`

NewErrorWithDefaults instantiates a new Error object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *Error) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *Error) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *Error) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *Error) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetDescription

`func (o *Error) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *Error) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *Error) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *Error) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetDetails

`func (o *Error) GetDetails() []string`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *Error) GetDetailsOk() (*[]string, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *Error) SetDetails(v []string)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *Error) HasDetails() bool`

HasDetails returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


