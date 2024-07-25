# Codes

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DtcHgs** | Pointer to **string** | Shows the DTC representation of how Hella Gutmann diagnostic devices store the trouble code | [optional] 
**DtcManuf** | Pointer to **string** | If existent, shows the DTC representation of how the manufacturer maintains the (proprietary) trouble codes | [optional] 
**PageId** | Pointer to **string** | Page Id (internal) | [optional] 
**PageIdArray** | Pointer to **[]string** | Page Id Array (internal) | [optional] 
**TableId** | Pointer to **string** | Table Id (internal) | [optional] 
**TableIdArray** | Pointer to **[]string** | Table Id Array (internal) | [optional] 

## Methods

### NewCodes

`func NewCodes() *Codes`

NewCodes instantiates a new Codes object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCodesWithDefaults

`func NewCodesWithDefaults() *Codes`

NewCodesWithDefaults instantiates a new Codes object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDtcHgs

`func (o *Codes) GetDtcHgs() string`

GetDtcHgs returns the DtcHgs field if non-nil, zero value otherwise.

### GetDtcHgsOk

`func (o *Codes) GetDtcHgsOk() (*string, bool)`

GetDtcHgsOk returns a tuple with the DtcHgs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDtcHgs

`func (o *Codes) SetDtcHgs(v string)`

SetDtcHgs sets DtcHgs field to given value.

### HasDtcHgs

`func (o *Codes) HasDtcHgs() bool`

HasDtcHgs returns a boolean if a field has been set.

### GetDtcManuf

`func (o *Codes) GetDtcManuf() string`

GetDtcManuf returns the DtcManuf field if non-nil, zero value otherwise.

### GetDtcManufOk

`func (o *Codes) GetDtcManufOk() (*string, bool)`

GetDtcManufOk returns a tuple with the DtcManuf field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDtcManuf

`func (o *Codes) SetDtcManuf(v string)`

SetDtcManuf sets DtcManuf field to given value.

### HasDtcManuf

`func (o *Codes) HasDtcManuf() bool`

HasDtcManuf returns a boolean if a field has been set.

### GetPageId

`func (o *Codes) GetPageId() string`

GetPageId returns the PageId field if non-nil, zero value otherwise.

### GetPageIdOk

`func (o *Codes) GetPageIdOk() (*string, bool)`

GetPageIdOk returns a tuple with the PageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageId

`func (o *Codes) SetPageId(v string)`

SetPageId sets PageId field to given value.

### HasPageId

`func (o *Codes) HasPageId() bool`

HasPageId returns a boolean if a field has been set.

### GetPageIdArray

`func (o *Codes) GetPageIdArray() []string`

GetPageIdArray returns the PageIdArray field if non-nil, zero value otherwise.

### GetPageIdArrayOk

`func (o *Codes) GetPageIdArrayOk() (*[]string, bool)`

GetPageIdArrayOk returns a tuple with the PageIdArray field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageIdArray

`func (o *Codes) SetPageIdArray(v []string)`

SetPageIdArray sets PageIdArray field to given value.

### HasPageIdArray

`func (o *Codes) HasPageIdArray() bool`

HasPageIdArray returns a boolean if a field has been set.

### GetTableId

`func (o *Codes) GetTableId() string`

GetTableId returns the TableId field if non-nil, zero value otherwise.

### GetTableIdOk

`func (o *Codes) GetTableIdOk() (*string, bool)`

GetTableIdOk returns a tuple with the TableId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTableId

`func (o *Codes) SetTableId(v string)`

SetTableId sets TableId field to given value.

### HasTableId

`func (o *Codes) HasTableId() bool`

HasTableId returns a boolean if a field has been set.

### GetTableIdArray

`func (o *Codes) GetTableIdArray() []string`

GetTableIdArray returns the TableIdArray field if non-nil, zero value otherwise.

### GetTableIdArrayOk

`func (o *Codes) GetTableIdArrayOk() (*[]string, bool)`

GetTableIdArrayOk returns a tuple with the TableIdArray field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTableIdArray

`func (o *Codes) SetTableIdArray(v []string)`

SetTableIdArray sets TableIdArray field to given value.

### HasTableIdArray

`func (o *Codes) HasTableIdArray() bool`

HasTableIdArray returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


