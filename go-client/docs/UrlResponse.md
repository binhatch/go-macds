# UrlResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **int32** | Status | [optional] 
**Error** | Pointer to [**Error**](Error.md) |  | [optional] 
**Page** | Pointer to **int32** | Page | [optional] 
**TotalItems** | Pointer to **int32** | Number of total items | [optional] 
**TotalPages** | Pointer to **int32** | Number of total pages | [optional] 
**Data** | Pointer to **[]string** |  | [optional] 

## Methods

### NewUrlResponse

`func NewUrlResponse() *UrlResponse`

NewUrlResponse instantiates a new UrlResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUrlResponseWithDefaults

`func NewUrlResponseWithDefaults() *UrlResponse`

NewUrlResponseWithDefaults instantiates a new UrlResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *UrlResponse) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UrlResponse) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UrlResponse) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *UrlResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetError

`func (o *UrlResponse) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *UrlResponse) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *UrlResponse) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *UrlResponse) HasError() bool`

HasError returns a boolean if a field has been set.

### GetPage

`func (o *UrlResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *UrlResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *UrlResponse) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *UrlResponse) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetTotalItems

`func (o *UrlResponse) GetTotalItems() int32`

GetTotalItems returns the TotalItems field if non-nil, zero value otherwise.

### GetTotalItemsOk

`func (o *UrlResponse) GetTotalItemsOk() (*int32, bool)`

GetTotalItemsOk returns a tuple with the TotalItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalItems

`func (o *UrlResponse) SetTotalItems(v int32)`

SetTotalItems sets TotalItems field to given value.

### HasTotalItems

`func (o *UrlResponse) HasTotalItems() bool`

HasTotalItems returns a boolean if a field has been set.

### GetTotalPages

`func (o *UrlResponse) GetTotalPages() int32`

GetTotalPages returns the TotalPages field if non-nil, zero value otherwise.

### GetTotalPagesOk

`func (o *UrlResponse) GetTotalPagesOk() (*int32, bool)`

GetTotalPagesOk returns a tuple with the TotalPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPages

`func (o *UrlResponse) SetTotalPages(v int32)`

SetTotalPages sets TotalPages field to given value.

### HasTotalPages

`func (o *UrlResponse) HasTotalPages() bool`

HasTotalPages returns a boolean if a field has been set.

### GetData

`func (o *UrlResponse) GetData() []string`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *UrlResponse) GetDataOk() (*[]string, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *UrlResponse) SetData(v []string)`

SetData sets Data field to given value.

### HasData

`func (o *UrlResponse) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


