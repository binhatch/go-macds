# InputedData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | Pointer to **string** | The exact code that was inputted | [optional] 
**Format** | Pointer to **string** | The exact code format that was inputted, if provided | [optional] 
**EcuSystem** | Pointer to **string** | The exact ECU system that was inputted, if provided; Mapping as per the following:&lt;table&gt;&lt;tbody&gt;&lt;tr&gt;&lt;td&gt;MO&lt;/td&gt;&lt;td&gt;Engine&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;AB&lt;/td&gt;&lt;td&gt;ABS&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;AI&lt;/td&gt;&lt;td&gt;Airbag&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;KL&lt;/td&gt;&lt;td&gt;Air conditioning&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;KO&lt;/td&gt;&lt;td&gt;Comfort&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;GE&lt;/td&gt;&lt;td&gt;Transmission&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;DI&lt;/td&gt;&lt;td&gt;Anti-theft device&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;FA&lt;/td&gt;&lt;td&gt;Suspension&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;LE&lt;/td&gt;&lt;td&gt;Steering&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;AV&lt;/td&gt;&lt;td&gt;Audio/Video&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;RD&lt;/td&gt;&lt;td&gt;Tire pressure monitoring&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;OB&lt;/td&gt;&lt;td&gt;OBD&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;SI&lt;/td&gt;&lt;td&gt;Safety&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;RI&lt;/td&gt;&lt;td&gt;Readiness code&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;GW&lt;/td&gt;&lt;td&gt;Gateway&lt;/td&gt;&lt;/tr&gt;&lt;/tbody&gt;&lt;/table&gt; | [optional] 
**PageId** | Pointer to **string** | The pageId, if provided (internal) | [optional] 
**TableId** | Pointer to **string** | The tableId, if provided (internal) | [optional] 

## Methods

### NewInputedData

`func NewInputedData() *InputedData`

NewInputedData instantiates a new InputedData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInputedDataWithDefaults

`func NewInputedDataWithDefaults() *InputedData`

NewInputedDataWithDefaults instantiates a new InputedData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *InputedData) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *InputedData) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *InputedData) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *InputedData) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetFormat

`func (o *InputedData) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *InputedData) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *InputedData) SetFormat(v string)`

SetFormat sets Format field to given value.

### HasFormat

`func (o *InputedData) HasFormat() bool`

HasFormat returns a boolean if a field has been set.

### GetEcuSystem

`func (o *InputedData) GetEcuSystem() string`

GetEcuSystem returns the EcuSystem field if non-nil, zero value otherwise.

### GetEcuSystemOk

`func (o *InputedData) GetEcuSystemOk() (*string, bool)`

GetEcuSystemOk returns a tuple with the EcuSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEcuSystem

`func (o *InputedData) SetEcuSystem(v string)`

SetEcuSystem sets EcuSystem field to given value.

### HasEcuSystem

`func (o *InputedData) HasEcuSystem() bool`

HasEcuSystem returns a boolean if a field has been set.

### GetPageId

`func (o *InputedData) GetPageId() string`

GetPageId returns the PageId field if non-nil, zero value otherwise.

### GetPageIdOk

`func (o *InputedData) GetPageIdOk() (*string, bool)`

GetPageIdOk returns a tuple with the PageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPageId

`func (o *InputedData) SetPageId(v string)`

SetPageId sets PageId field to given value.

### HasPageId

`func (o *InputedData) HasPageId() bool`

HasPageId returns a boolean if a field has been set.

### GetTableId

`func (o *InputedData) GetTableId() string`

GetTableId returns the TableId field if non-nil, zero value otherwise.

### GetTableIdOk

`func (o *InputedData) GetTableIdOk() (*string, bool)`

GetTableIdOk returns a tuple with the TableId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTableId

`func (o *InputedData) SetTableId(v string)`

SetTableId sets TableId field to given value.

### HasTableId

`func (o *InputedData) HasTableId() bool`

HasTableId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


