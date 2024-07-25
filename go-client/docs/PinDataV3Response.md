# PinDataV3Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **int32** | Status | [optional] 
**Error** | Pointer to [**Error**](Error.md) |  | [optional] 
**Page** | Pointer to **int32** | Page | [optional] 
**TotalItems** | Pointer to **int32** | Number of total items | [optional] 
**TotalPages** | Pointer to **int32** | Number of total pages | [optional] 
**Data** | Pointer to [**[]ComponentDataV3ResponseDTO**](ComponentDataV3ResponseDTO.md) |  | [optional] 

## Methods

### NewPinDataV3Response

`func NewPinDataV3Response() *PinDataV3Response`

NewPinDataV3Response instantiates a new PinDataV3Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPinDataV3ResponseWithDefaults

`func NewPinDataV3ResponseWithDefaults() *PinDataV3Response`

NewPinDataV3ResponseWithDefaults instantiates a new PinDataV3Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *PinDataV3Response) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *PinDataV3Response) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *PinDataV3Response) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *PinDataV3Response) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetError

`func (o *PinDataV3Response) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *PinDataV3Response) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *PinDataV3Response) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *PinDataV3Response) HasError() bool`

HasError returns a boolean if a field has been set.

### GetPage

`func (o *PinDataV3Response) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *PinDataV3Response) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *PinDataV3Response) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *PinDataV3Response) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetTotalItems

`func (o *PinDataV3Response) GetTotalItems() int32`

GetTotalItems returns the TotalItems field if non-nil, zero value otherwise.

### GetTotalItemsOk

`func (o *PinDataV3Response) GetTotalItemsOk() (*int32, bool)`

GetTotalItemsOk returns a tuple with the TotalItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalItems

`func (o *PinDataV3Response) SetTotalItems(v int32)`

SetTotalItems sets TotalItems field to given value.

### HasTotalItems

`func (o *PinDataV3Response) HasTotalItems() bool`

HasTotalItems returns a boolean if a field has been set.

### GetTotalPages

`func (o *PinDataV3Response) GetTotalPages() int32`

GetTotalPages returns the TotalPages field if non-nil, zero value otherwise.

### GetTotalPagesOk

`func (o *PinDataV3Response) GetTotalPagesOk() (*int32, bool)`

GetTotalPagesOk returns a tuple with the TotalPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPages

`func (o *PinDataV3Response) SetTotalPages(v int32)`

SetTotalPages sets TotalPages field to given value.

### HasTotalPages

`func (o *PinDataV3Response) HasTotalPages() bool`

HasTotalPages returns a boolean if a field has been set.

### GetData

`func (o *PinDataV3Response) GetData() []ComponentDataV3ResponseDTO`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *PinDataV3Response) GetDataOk() (*[]ComponentDataV3ResponseDTO, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *PinDataV3Response) SetData(v []ComponentDataV3ResponseDTO)`

SetData sets Data field to given value.

### HasData

`func (o *PinDataV3Response) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


