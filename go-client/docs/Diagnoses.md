# Diagnoses

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | id | [optional] 
**Datatype** | Pointer to **string** | Can have values to further specify the data type presented. Can have values such as: flatrateunit (repair times), fuserelay, composition (placements and organisation of different elements on the vehicle), stco (ECU coding), periphery (relevant periphery components to the main component), wiringdiagram, techdata, \&quot;techinfo\&quot; (proprietary knowledge database of Hella Gutmann), \&quot;componenttestvalues\&quot;, \&quot;bulletin\&quot;, \&quot;manual\&quot;, \&quot;gdst\&quot; (basic setting),  \&quot;faultcode\&quot;, \&quot;parameter\&quot; | [optional] 
**Order** | Pointer to **int32** | order | [optional] 
**Text** | Pointer to **string** | text | [optional] 
**Richtext** | Pointer to [**[]RichTextDTO**](RichTextDTO.md) | Contains structured texts to guide the interpretation of text values. | [optional] 
**TextSubSystem** | Pointer to **string** | The name of the sub system | [optional] 

## Methods

### NewDiagnoses

`func NewDiagnoses() *Diagnoses`

NewDiagnoses instantiates a new Diagnoses object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDiagnosesWithDefaults

`func NewDiagnosesWithDefaults() *Diagnoses`

NewDiagnosesWithDefaults instantiates a new Diagnoses object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Diagnoses) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Diagnoses) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Diagnoses) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Diagnoses) HasId() bool`

HasId returns a boolean if a field has been set.

### GetDatatype

`func (o *Diagnoses) GetDatatype() string`

GetDatatype returns the Datatype field if non-nil, zero value otherwise.

### GetDatatypeOk

`func (o *Diagnoses) GetDatatypeOk() (*string, bool)`

GetDatatypeOk returns a tuple with the Datatype field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatatype

`func (o *Diagnoses) SetDatatype(v string)`

SetDatatype sets Datatype field to given value.

### HasDatatype

`func (o *Diagnoses) HasDatatype() bool`

HasDatatype returns a boolean if a field has been set.

### GetOrder

`func (o *Diagnoses) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *Diagnoses) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *Diagnoses) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *Diagnoses) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetText

`func (o *Diagnoses) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *Diagnoses) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *Diagnoses) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *Diagnoses) HasText() bool`

HasText returns a boolean if a field has been set.

### GetRichtext

`func (o *Diagnoses) GetRichtext() []RichTextDTO`

GetRichtext returns the Richtext field if non-nil, zero value otherwise.

### GetRichtextOk

`func (o *Diagnoses) GetRichtextOk() (*[]RichTextDTO, bool)`

GetRichtextOk returns a tuple with the Richtext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRichtext

`func (o *Diagnoses) SetRichtext(v []RichTextDTO)`

SetRichtext sets Richtext field to given value.

### HasRichtext

`func (o *Diagnoses) HasRichtext() bool`

HasRichtext returns a boolean if a field has been set.

### GetTextSubSystem

`func (o *Diagnoses) GetTextSubSystem() string`

GetTextSubSystem returns the TextSubSystem field if non-nil, zero value otherwise.

### GetTextSubSystemOk

`func (o *Diagnoses) GetTextSubSystemOk() (*string, bool)`

GetTextSubSystemOk returns a tuple with the TextSubSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTextSubSystem

`func (o *Diagnoses) SetTextSubSystem(v string)`

SetTextSubSystem sets TextSubSystem field to given value.

### HasTextSubSystem

`func (o *Diagnoses) HasTextSubSystem() bool`

HasTextSubSystem returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


