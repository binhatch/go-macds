# RichTextDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | id | [optional] 
**Type** | Pointer to **string** | Defines the type of text, e.g. \&quot;third-order-headline\&quot;, \&quot;table\&quot;, \&quot;tbody\&quot;, \&quot;trow\&quot;, \&quot;tcell\&quot; | [optional] 
**Text** | Pointer to **string** | Text | [optional] 
**Texts** | Pointer to **[]string** | List of Texts | [optional] 
**ContentValue** | Pointer to **string** | Text content value | [optional] 
**ContentValues** | Pointer to **[]string** | List of text content values | [optional] 
**Content** | Pointer to [**RichTextDTO**](RichTextDTO.md) |  | [optional] 
**Attributes** | Pointer to [**Attributes**](Attributes.md) |  | [optional] 

## Methods

### NewRichTextDTO

`func NewRichTextDTO() *RichTextDTO`

NewRichTextDTO instantiates a new RichTextDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRichTextDTOWithDefaults

`func NewRichTextDTOWithDefaults() *RichTextDTO`

NewRichTextDTOWithDefaults instantiates a new RichTextDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RichTextDTO) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RichTextDTO) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RichTextDTO) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *RichTextDTO) HasId() bool`

HasId returns a boolean if a field has been set.

### GetType

`func (o *RichTextDTO) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *RichTextDTO) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *RichTextDTO) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *RichTextDTO) HasType() bool`

HasType returns a boolean if a field has been set.

### GetText

`func (o *RichTextDTO) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *RichTextDTO) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *RichTextDTO) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *RichTextDTO) HasText() bool`

HasText returns a boolean if a field has been set.

### GetTexts

`func (o *RichTextDTO) GetTexts() []string`

GetTexts returns the Texts field if non-nil, zero value otherwise.

### GetTextsOk

`func (o *RichTextDTO) GetTextsOk() (*[]string, bool)`

GetTextsOk returns a tuple with the Texts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTexts

`func (o *RichTextDTO) SetTexts(v []string)`

SetTexts sets Texts field to given value.

### HasTexts

`func (o *RichTextDTO) HasTexts() bool`

HasTexts returns a boolean if a field has been set.

### GetContentValue

`func (o *RichTextDTO) GetContentValue() string`

GetContentValue returns the ContentValue field if non-nil, zero value otherwise.

### GetContentValueOk

`func (o *RichTextDTO) GetContentValueOk() (*string, bool)`

GetContentValueOk returns a tuple with the ContentValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentValue

`func (o *RichTextDTO) SetContentValue(v string)`

SetContentValue sets ContentValue field to given value.

### HasContentValue

`func (o *RichTextDTO) HasContentValue() bool`

HasContentValue returns a boolean if a field has been set.

### GetContentValues

`func (o *RichTextDTO) GetContentValues() []string`

GetContentValues returns the ContentValues field if non-nil, zero value otherwise.

### GetContentValuesOk

`func (o *RichTextDTO) GetContentValuesOk() (*[]string, bool)`

GetContentValuesOk returns a tuple with the ContentValues field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentValues

`func (o *RichTextDTO) SetContentValues(v []string)`

SetContentValues sets ContentValues field to given value.

### HasContentValues

`func (o *RichTextDTO) HasContentValues() bool`

HasContentValues returns a boolean if a field has been set.

### GetContent

`func (o *RichTextDTO) GetContent() RichTextDTO`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *RichTextDTO) GetContentOk() (*RichTextDTO, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *RichTextDTO) SetContent(v RichTextDTO)`

SetContent sets Content field to given value.

### HasContent

`func (o *RichTextDTO) HasContent() bool`

HasContent returns a boolean if a field has been set.

### GetAttributes

`func (o *RichTextDTO) GetAttributes() Attributes`

GetAttributes returns the Attributes field if non-nil, zero value otherwise.

### GetAttributesOk

`func (o *RichTextDTO) GetAttributesOk() (*Attributes, bool)`

GetAttributesOk returns a tuple with the Attributes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttributes

`func (o *RichTextDTO) SetAttributes(v Attributes)`

SetAttributes sets Attributes field to given value.

### HasAttributes

`func (o *RichTextDTO) HasAttributes() bool`

HasAttributes returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


