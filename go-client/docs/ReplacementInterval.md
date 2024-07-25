# ReplacementInterval

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ReplacementPartNo** | Pointer to **int32** | Identifier uniquely identifying the part name and its array of genArtNos | [optional] 
**ReplacementType** | Pointer to **string** | Can be: Interval, AdditionalText, TechnicalData | [optional] 
**ReplacementIntervalPart** | Pointer to [**ReplacementIntervalPart**](ReplacementIntervalPart.md) |  | [optional] 

## Methods

### NewReplacementInterval

`func NewReplacementInterval() *ReplacementInterval`

NewReplacementInterval instantiates a new ReplacementInterval object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReplacementIntervalWithDefaults

`func NewReplacementIntervalWithDefaults() *ReplacementInterval`

NewReplacementIntervalWithDefaults instantiates a new ReplacementInterval object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReplacementPartNo

`func (o *ReplacementInterval) GetReplacementPartNo() int32`

GetReplacementPartNo returns the ReplacementPartNo field if non-nil, zero value otherwise.

### GetReplacementPartNoOk

`func (o *ReplacementInterval) GetReplacementPartNoOk() (*int32, bool)`

GetReplacementPartNoOk returns a tuple with the ReplacementPartNo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplacementPartNo

`func (o *ReplacementInterval) SetReplacementPartNo(v int32)`

SetReplacementPartNo sets ReplacementPartNo field to given value.

### HasReplacementPartNo

`func (o *ReplacementInterval) HasReplacementPartNo() bool`

HasReplacementPartNo returns a boolean if a field has been set.

### GetReplacementType

`func (o *ReplacementInterval) GetReplacementType() string`

GetReplacementType returns the ReplacementType field if non-nil, zero value otherwise.

### GetReplacementTypeOk

`func (o *ReplacementInterval) GetReplacementTypeOk() (*string, bool)`

GetReplacementTypeOk returns a tuple with the ReplacementType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplacementType

`func (o *ReplacementInterval) SetReplacementType(v string)`

SetReplacementType sets ReplacementType field to given value.

### HasReplacementType

`func (o *ReplacementInterval) HasReplacementType() bool`

HasReplacementType returns a boolean if a field has been set.

### GetReplacementIntervalPart

`func (o *ReplacementInterval) GetReplacementIntervalPart() ReplacementIntervalPart`

GetReplacementIntervalPart returns the ReplacementIntervalPart field if non-nil, zero value otherwise.

### GetReplacementIntervalPartOk

`func (o *ReplacementInterval) GetReplacementIntervalPartOk() (*ReplacementIntervalPart, bool)`

GetReplacementIntervalPartOk returns a tuple with the ReplacementIntervalPart field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReplacementIntervalPart

`func (o *ReplacementInterval) SetReplacementIntervalPart(v ReplacementIntervalPart)`

SetReplacementIntervalPart sets ReplacementIntervalPart field to given value.

### HasReplacementIntervalPart

`func (o *ReplacementInterval) HasReplacementIntervalPart() bool`

HasReplacementIntervalPart returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


