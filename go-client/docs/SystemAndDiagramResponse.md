# SystemAndDiagramResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Text** | Pointer to [**TextTranslation**](TextTranslation.md) |  | [optional] 
**From** | Pointer to **string** | if existent, indicates the start date of when the diagram is applicable | [optional] 
**To** | Pointer to **string** | if existent, indicates the end date of when the diagram is applicable | [optional] 
**DateFrom** | Pointer to **string** | if existent, indicates the start date of when the diagram is applicable | [optional] 
**DateTo** | Pointer to **string** | if existent, indicates the end date of when the diagram is applicable | [optional] 
**SystemType** | Pointer to **string** | Contains the systems associated with the system group | [optional] 
**Diagram** | Pointer to [**Diagram**](Diagram.md) |  | [optional] 

## Methods

### NewSystemAndDiagramResponse

`func NewSystemAndDiagramResponse() *SystemAndDiagramResponse`

NewSystemAndDiagramResponse instantiates a new SystemAndDiagramResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSystemAndDiagramResponseWithDefaults

`func NewSystemAndDiagramResponseWithDefaults() *SystemAndDiagramResponse`

NewSystemAndDiagramResponseWithDefaults instantiates a new SystemAndDiagramResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetText

`func (o *SystemAndDiagramResponse) GetText() TextTranslation`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *SystemAndDiagramResponse) GetTextOk() (*TextTranslation, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *SystemAndDiagramResponse) SetText(v TextTranslation)`

SetText sets Text field to given value.

### HasText

`func (o *SystemAndDiagramResponse) HasText() bool`

HasText returns a boolean if a field has been set.

### GetFrom

`func (o *SystemAndDiagramResponse) GetFrom() string`

GetFrom returns the From field if non-nil, zero value otherwise.

### GetFromOk

`func (o *SystemAndDiagramResponse) GetFromOk() (*string, bool)`

GetFromOk returns a tuple with the From field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFrom

`func (o *SystemAndDiagramResponse) SetFrom(v string)`

SetFrom sets From field to given value.

### HasFrom

`func (o *SystemAndDiagramResponse) HasFrom() bool`

HasFrom returns a boolean if a field has been set.

### GetTo

`func (o *SystemAndDiagramResponse) GetTo() string`

GetTo returns the To field if non-nil, zero value otherwise.

### GetToOk

`func (o *SystemAndDiagramResponse) GetToOk() (*string, bool)`

GetToOk returns a tuple with the To field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTo

`func (o *SystemAndDiagramResponse) SetTo(v string)`

SetTo sets To field to given value.

### HasTo

`func (o *SystemAndDiagramResponse) HasTo() bool`

HasTo returns a boolean if a field has been set.

### GetDateFrom

`func (o *SystemAndDiagramResponse) GetDateFrom() string`

GetDateFrom returns the DateFrom field if non-nil, zero value otherwise.

### GetDateFromOk

`func (o *SystemAndDiagramResponse) GetDateFromOk() (*string, bool)`

GetDateFromOk returns a tuple with the DateFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateFrom

`func (o *SystemAndDiagramResponse) SetDateFrom(v string)`

SetDateFrom sets DateFrom field to given value.

### HasDateFrom

`func (o *SystemAndDiagramResponse) HasDateFrom() bool`

HasDateFrom returns a boolean if a field has been set.

### GetDateTo

`func (o *SystemAndDiagramResponse) GetDateTo() string`

GetDateTo returns the DateTo field if non-nil, zero value otherwise.

### GetDateToOk

`func (o *SystemAndDiagramResponse) GetDateToOk() (*string, bool)`

GetDateToOk returns a tuple with the DateTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateTo

`func (o *SystemAndDiagramResponse) SetDateTo(v string)`

SetDateTo sets DateTo field to given value.

### HasDateTo

`func (o *SystemAndDiagramResponse) HasDateTo() bool`

HasDateTo returns a boolean if a field has been set.

### GetSystemType

`func (o *SystemAndDiagramResponse) GetSystemType() string`

GetSystemType returns the SystemType field if non-nil, zero value otherwise.

### GetSystemTypeOk

`func (o *SystemAndDiagramResponse) GetSystemTypeOk() (*string, bool)`

GetSystemTypeOk returns a tuple with the SystemType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemType

`func (o *SystemAndDiagramResponse) SetSystemType(v string)`

SetSystemType sets SystemType field to given value.

### HasSystemType

`func (o *SystemAndDiagramResponse) HasSystemType() bool`

HasSystemType returns a boolean if a field has been set.

### GetDiagram

`func (o *SystemAndDiagramResponse) GetDiagram() Diagram`

GetDiagram returns the Diagram field if non-nil, zero value otherwise.

### GetDiagramOk

`func (o *SystemAndDiagramResponse) GetDiagramOk() (*Diagram, bool)`

GetDiagramOk returns a tuple with the Diagram field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiagram

`func (o *SystemAndDiagramResponse) SetDiagram(v Diagram)`

SetDiagram sets Diagram field to given value.

### HasDiagram

`func (o *SystemAndDiagramResponse) HasDiagram() bool`

HasDiagram returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


