# KtypeComponentMappingResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **int32** | Status | [optional] 
**Error** | Pointer to [**Error**](Error.md) |  | [optional] 
**Page** | Pointer to **int32** | Page | [optional] 
**TotalItems** | Pointer to **int32** | Number of total items | [optional] 
**TotalPages** | Pointer to **int32** | Number of total pages | [optional] 
**Data** | Pointer to [**[]KtypeComponentMappingResponseDTO**](KtypeComponentMappingResponseDTO.md) |  | [optional] 

## Methods

### NewKtypeComponentMappingResponse

`func NewKtypeComponentMappingResponse() *KtypeComponentMappingResponse`

NewKtypeComponentMappingResponse instantiates a new KtypeComponentMappingResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKtypeComponentMappingResponseWithDefaults

`func NewKtypeComponentMappingResponseWithDefaults() *KtypeComponentMappingResponse`

NewKtypeComponentMappingResponseWithDefaults instantiates a new KtypeComponentMappingResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *KtypeComponentMappingResponse) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *KtypeComponentMappingResponse) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *KtypeComponentMappingResponse) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *KtypeComponentMappingResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetError

`func (o *KtypeComponentMappingResponse) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *KtypeComponentMappingResponse) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *KtypeComponentMappingResponse) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *KtypeComponentMappingResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### GetPage

`func (o *KtypeComponentMappingResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *KtypeComponentMappingResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *KtypeComponentMappingResponse) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *KtypeComponentMappingResponse) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetTotalItems

`func (o *KtypeComponentMappingResponse) GetTotalItems() int32`

GetTotalItems returns the TotalItems field if non-nil, zero value otherwise.

### GetTotalItemsOk

`func (o *KtypeComponentMappingResponse) GetTotalItemsOk() (*int32, bool)`

GetTotalItemsOk returns a tuple with the TotalItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalItems

`func (o *KtypeComponentMappingResponse) SetTotalItems(v int32)`

SetTotalItems sets TotalItems field to given value.

### HasTotalItems

`func (o *KtypeComponentMappingResponse) HasTotalItems() bool`

HasTotalItems returns a boolean if a field has been set.

### GetTotalPages

`func (o *KtypeComponentMappingResponse) GetTotalPages() int32`

GetTotalPages returns the TotalPages field if non-nil, zero value otherwise.

### GetTotalPagesOk

`func (o *KtypeComponentMappingResponse) GetTotalPagesOk() (*int32, bool)`

GetTotalPagesOk returns a tuple with the TotalPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPages

`func (o *KtypeComponentMappingResponse) SetTotalPages(v int32)`

SetTotalPages sets TotalPages field to given value.

### HasTotalPages

`func (o *KtypeComponentMappingResponse) HasTotalPages() bool`

HasTotalPages returns a boolean if a field has been set.

### GetData

`func (o *KtypeComponentMappingResponse) GetData() []KtypeComponentMappingResponseDTO`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *KtypeComponentMappingResponse) GetDataOk() (*[]KtypeComponentMappingResponseDTO, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *KtypeComponentMappingResponse) SetData(v []KtypeComponentMappingResponseDTO)`

SetData sets Data field to given value.

### HasData

`func (o *KtypeComponentMappingResponse) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


