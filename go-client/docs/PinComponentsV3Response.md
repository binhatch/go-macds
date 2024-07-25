# PinComponentsV3Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **int32** | Status | [optional] 
**Error** | Pointer to [**Error**](Error.md) |  | [optional] 
**Page** | Pointer to **int32** | Page | [optional] 
**TotalItems** | Pointer to **int32** | Number of total items | [optional] 
**TotalPages** | Pointer to **int32** | Number of total pages | [optional] 
**Data** | Pointer to [**[]ComponentV3ResponseDTO**](ComponentV3ResponseDTO.md) |  | [optional] 

## Methods

### NewPinComponentsV3Response

`func NewPinComponentsV3Response() *PinComponentsV3Response`

NewPinComponentsV3Response instantiates a new PinComponentsV3Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPinComponentsV3ResponseWithDefaults

`func NewPinComponentsV3ResponseWithDefaults() *PinComponentsV3Response`

NewPinComponentsV3ResponseWithDefaults instantiates a new PinComponentsV3Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *PinComponentsV3Response) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PinComponentsV3Response) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PinComponentsV3Response) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PinComponentsV3Response) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetError

`func (o *PinComponentsV3Response) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *PinComponentsV3Response) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *PinComponentsV3Response) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *PinComponentsV3Response) HasError() bool`

HasError returns a boolean if a field has been set.

### GetPage

`func (o *PinComponentsV3Response) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *PinComponentsV3Response) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *PinComponentsV3Response) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *PinComponentsV3Response) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetTotalItems

`func (o *PinComponentsV3Response) GetTotalItems() int32`

GetTotalItems returns the TotalItems field if non-nil, zero value otherwise.

### GetTotalItemsOk

`func (o *PinComponentsV3Response) GetTotalItemsOk() (*int32, bool)`

GetTotalItemsOk returns a tuple with the TotalItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalItems

`func (o *PinComponentsV3Response) SetTotalItems(v int32)`

SetTotalItems sets TotalItems field to given value.

### HasTotalItems

`func (o *PinComponentsV3Response) HasTotalItems() bool`

HasTotalItems returns a boolean if a field has been set.

### GetTotalPages

`func (o *PinComponentsV3Response) GetTotalPages() int32`

GetTotalPages returns the TotalPages field if non-nil, zero value otherwise.

### GetTotalPagesOk

`func (o *PinComponentsV3Response) GetTotalPagesOk() (*int32, bool)`

GetTotalPagesOk returns a tuple with the TotalPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPages

`func (o *PinComponentsV3Response) SetTotalPages(v int32)`

SetTotalPages sets TotalPages field to given value.

### HasTotalPages

`func (o *PinComponentsV3Response) HasTotalPages() bool`

HasTotalPages returns a boolean if a field has been set.

### GetData

`func (o *PinComponentsV3Response) GetData() []ComponentV3ResponseDTO`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PinComponentsV3Response) GetDataOk() (*[]ComponentV3ResponseDTO, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PinComponentsV3Response) SetData(v []ComponentV3ResponseDTO)`

SetData sets Data field to given value.

### HasData

`func (o *PinComponentsV3Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


