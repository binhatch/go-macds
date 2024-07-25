# DtcsDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** | The exact code that was inputted | 
**Format** | Pointer to **string** | The exact code format that was inputted, if provided | [optional] 
**EcuSystem** | Pointer to **string** | The exact ECU system that was inputted, if provided; Mapping as per the following:&lt;table&gt;&lt;tbody&gt;&lt;tr&gt;&lt;td&gt;MO&lt;/td&gt;&lt;td&gt;Engine&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;AB&lt;/td&gt;&lt;td&gt;ABS&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;AI&lt;/td&gt;&lt;td&gt;Airbag&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;KL&lt;/td&gt;&lt;td&gt;Air conditioning&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;KO&lt;/td&gt;&lt;td&gt;Comfort&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;GE&lt;/td&gt;&lt;td&gt;Transmission&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;DI&lt;/td&gt;&lt;td&gt;Anti-theft device&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;FA&lt;/td&gt;&lt;td&gt;Suspension&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;LE&lt;/td&gt;&lt;td&gt;Steering&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;AV&lt;/td&gt;&lt;td&gt;Audio/Video&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;RD&lt;/td&gt;&lt;td&gt;Tire pressure monitoring&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;OB&lt;/td&gt;&lt;td&gt;OBD&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;SI&lt;/td&gt;&lt;td&gt;Safety&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;RI&lt;/td&gt;&lt;td&gt;Readiness code&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;GW&lt;/td&gt;&lt;td&gt;Gateway&lt;/td&gt;&lt;/tr&gt;&lt;/tbody&gt;&lt;/table&gt; | [optional] 
**PageId** | Pointer to **string** | The pageId, if provided (internal) | [optional] 
**TableId** | Pointer to **string** | The tableId, if provided (internal) | [optional] 
**DtcMetaInfo** | Pointer to **string** | additional information from the vehicle byte stream for a particular DTC such as request/response ID (txid, rxid) and ecu Id | [optional] 
**IsTemporary** | Pointer to **bool** | Set to true if the trouble code is a temporary or intermittent code; used for calculating the criticality index | [optional] 

## Methods

### NewDtcsDto

`func NewDtcsDto(code string, ) *DtcsDto`

NewDtcsDto instantiates a new DtcsDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtcsDtoWithDefaults

`func NewDtcsDtoWithDefaults() *DtcsDto`

NewDtcsDtoWithDefaults instantiates a new DtcsDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *DtcsDto) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *DtcsDto) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *DtcsDto) SetCode(v string)`

SetCode sets Code field to given value.


### GetFormat

`func (o *DtcsDto) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *DtcsDto) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *DtcsDto) SetFormat(v string)`

SetFormat sets Format field to given value.

### HasFormat

`func (o *DtcsDto) HasFormat() bool`

HasFormat returns a boolean if a field has been set.

### GetEcuSystem

`func (o *DtcsDto) GetEcuSystem() string`

GetEcuSystem returns the EcuSystem field if non-nil, zero value otherwise.

### GetEcuSystemOk

`func (o *DtcsDto) GetEcuSystemOk() (*string, bool)`

GetEcuSystemOk returns a tuple with the EcuSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEcuSystem

`func (o *DtcsDto) SetEcuSystem(v string)`

SetEcuSystem sets EcuSystem field to given value.

### HasEcuSystem

`func (o *DtcsDto) HasEcuSystem() bool`

HasEcuSystem returns a boolean if a field has been set.

### GetPageId

`func (o *DtcsDto) GetPageId() string`

GetPageId returns the PageId field if non-nil, zero value otherwise.

### GetPageIdOk

`func (o *DtcsDto) GetPageIdOk() (*string, bool)`

GetPageIdOk returns a tuple with the PageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageId

`func (o *DtcsDto) SetPageId(v string)`

SetPageId sets PageId field to given value.

### HasPageId

`func (o *DtcsDto) HasPageId() bool`

HasPageId returns a boolean if a field has been set.

### GetTableId

`func (o *DtcsDto) GetTableId() string`

GetTableId returns the TableId field if non-nil, zero value otherwise.

### GetTableIdOk

`func (o *DtcsDto) GetTableIdOk() (*string, bool)`

GetTableIdOk returns a tuple with the TableId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTableId

`func (o *DtcsDto) SetTableId(v string)`

SetTableId sets TableId field to given value.

### HasTableId

`func (o *DtcsDto) HasTableId() bool`

HasTableId returns a boolean if a field has been set.

### GetDtcMetaInfo

`func (o *DtcsDto) GetDtcMetaInfo() string`

GetDtcMetaInfo returns the DtcMetaInfo field if non-nil, zero value otherwise.

### GetDtcMetaInfoOk

`func (o *DtcsDto) GetDtcMetaInfoOk() (*string, bool)`

GetDtcMetaInfoOk returns a tuple with the DtcMetaInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDtcMetaInfo

`func (o *DtcsDto) SetDtcMetaInfo(v string)`

SetDtcMetaInfo sets DtcMetaInfo field to given value.

### HasDtcMetaInfo

`func (o *DtcsDto) HasDtcMetaInfo() bool`

HasDtcMetaInfo returns a boolean if a field has been set.

### GetIsTemporary

`func (o *DtcsDto) GetIsTemporary() bool`

GetIsTemporary returns the IsTemporary field if non-nil, zero value otherwise.

### GetIsTemporaryOk

`func (o *DtcsDto) GetIsTemporaryOk() (*bool, bool)`

GetIsTemporaryOk returns a tuple with the IsTemporary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsTemporary

`func (o *DtcsDto) SetIsTemporary(v bool)`

SetIsTemporary sets IsTemporary field to given value.

### HasIsTemporary

`func (o *DtcsDto) HasIsTemporary() bool`

HasIsTemporary returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


