# SystemType

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SystemId** | Pointer to **string** | id of the system of which a wiring exists. It is found in the response of the /systems endpoint, and required as input of the /diagram endpoint. | [optional] 
**Text** | Pointer to [**TextTranslation**](TextTranslation.md) |  | [optional] 
**From** | Pointer to **string** | if existent, indicates the start date of when the diagram is applicable | [optional] 
**To** | Pointer to **string** | if existent, indicates the end date of when the diagram is applicable | [optional] 
**DateFrom** | Pointer to **string** | if existent, indicates the start date of when the diagram is applicable | [optional] 
**DateTo** | Pointer to **string** | if existent, indicates the end date of when the diagram is applicable | [optional] 

## Methods

### NewSystemType

`func NewSystemType() *SystemType`

NewSystemType instantiates a new SystemType object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemTypeWithDefaults

`func NewSystemTypeWithDefaults() *SystemType`

NewSystemTypeWithDefaults instantiates a new SystemType object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSystemId

`func (o *SystemType) GetSystemId() string`

GetSystemId returns the SystemId field if non-nil, zero value otherwise.

### GetSystemIdOk

`func (o *SystemType) GetSystemIdOk() (*string, bool)`

GetSystemIdOk returns a tuple with the SystemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemId

`func (o *SystemType) SetSystemId(v string)`

SetSystemId sets SystemId field to given value.

### HasSystemId

`func (o *SystemType) HasSystemId() bool`

HasSystemId returns a boolean if a field has been set.

### GetText

`func (o *SystemType) GetText() TextTranslation`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *SystemType) GetTextOk() (*TextTranslation, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *SystemType) SetText(v TextTranslation)`

SetText sets Text field to given value.

### HasText

`func (o *SystemType) HasText() bool`

HasText returns a boolean if a field has been set.

### GetFrom

`func (o *SystemType) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SystemType) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SystemType) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *SystemType) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *SystemType) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *SystemType) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *SystemType) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *SystemType) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetDateFrom

`func (o *SystemType) GetDateFrom() string`

GetDateFrom returns the DateFrom field if non-nil, zero value otherwise.

### GetDateFromOk

`func (o *SystemType) GetDateFromOk() (*string, bool)`

GetDateFromOk returns a tuple with the DateFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateFrom

`func (o *SystemType) SetDateFrom(v string)`

SetDateFrom sets DateFrom field to given value.

### HasDateFrom

`func (o *SystemType) HasDateFrom() bool`

HasDateFrom returns a boolean if a field has been set.

### GetDateTo

`func (o *SystemType) GetDateTo() string`

GetDateTo returns the DateTo field if non-nil, zero value otherwise.

### GetDateToOk

`func (o *SystemType) GetDateToOk() (*string, bool)`

GetDateToOk returns a tuple with the DateTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateTo

`func (o *SystemType) SetDateTo(v string)`

SetDateTo sets DateTo field to given value.

### HasDateTo

`func (o *SystemType) HasDateTo() bool`

HasDateTo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


