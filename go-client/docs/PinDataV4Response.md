# PinDataV4Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **int32** | Status | [optional] 
**Error** | Pointer to [**Error**](Error.md) |  | [optional] 
**Page** | Pointer to **int32** | Page | [optional] 
**TotalItems** | Pointer to **int32** | Number of total items | [optional] 
**TotalPages** | Pointer to **int32** | Number of total pages | [optional] 
**Data** | Pointer to [**[]ComponentDataV4ResponseDTO**](ComponentDataV4ResponseDTO.md) |  | [optional] 

## Methods

### NewPinDataV4Response

`func NewPinDataV4Response() *PinDataV4Response`

NewPinDataV4Response instantiates a new PinDataV4Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPinDataV4ResponseWithDefaults

`func NewPinDataV4ResponseWithDefaults() *PinDataV4Response`

NewPinDataV4ResponseWithDefaults instantiates a new PinDataV4Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *PinDataV4Response) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PinDataV4Response) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PinDataV4Response) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PinDataV4Response) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetError

`func (o *PinDataV4Response) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *PinDataV4Response) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *PinDataV4Response) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *PinDataV4Response) HasError() bool`

HasError returns a boolean if a field has been set.

### GetPage

`func (o *PinDataV4Response) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *PinDataV4Response) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *PinDataV4Response) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *PinDataV4Response) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetTotalItems

`func (o *PinDataV4Response) GetTotalItems() int32`

GetTotalItems returns the TotalItems field if non-nil, zero value otherwise.

### GetTotalItemsOk

`func (o *PinDataV4Response) GetTotalItemsOk() (*int32, bool)`

GetTotalItemsOk returns a tuple with the TotalItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalItems

`func (o *PinDataV4Response) SetTotalItems(v int32)`

SetTotalItems sets TotalItems field to given value.

### HasTotalItems

`func (o *PinDataV4Response) HasTotalItems() bool`

HasTotalItems returns a boolean if a field has been set.

### GetTotalPages

`func (o *PinDataV4Response) GetTotalPages() int32`

GetTotalPages returns the TotalPages field if non-nil, zero value otherwise.

### GetTotalPagesOk

`func (o *PinDataV4Response) GetTotalPagesOk() (*int32, bool)`

GetTotalPagesOk returns a tuple with the TotalPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPages

`func (o *PinDataV4Response) SetTotalPages(v int32)`

SetTotalPages sets TotalPages field to given value.

### HasTotalPages

`func (o *PinDataV4Response) HasTotalPages() bool`

HasTotalPages returns a boolean if a field has been set.

### GetData

`func (o *PinDataV4Response) GetData() []ComponentDataV4ResponseDTO`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PinDataV4Response) GetDataOk() (*[]ComponentDataV4ResponseDTO, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PinDataV4Response) SetData(v []ComponentDataV4ResponseDTO)`

SetData sets Data field to given value.

### HasData

`func (o *PinDataV4Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


