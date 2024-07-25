# TextContentBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Order** | Pointer to **int32** | Order | [optional] 
**TextFormatType** | Pointer to **string** | Suggestion of the text format for the respective content block. Values can be e.g. \&quot;text-h1\&quot;, \&quot;text-body-1\&quot;, \&quot;text-body-2, \&quot;text-caption\&quot;, etc. | [optional] 
**TextContent** | Pointer to **string** | Text Content | [optional] 
**Type** | Pointer to **string** | Text Type | [optional] 

## Methods

### NewTextContentBlock

`func NewTextContentBlock() *TextContentBlock`

NewTextContentBlock instantiates a new TextContentBlock object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTextContentBlockWithDefaults

`func NewTextContentBlockWithDefaults() *TextContentBlock`

NewTextContentBlockWithDefaults instantiates a new TextContentBlock object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrder

`func (o *TextContentBlock) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *TextContentBlock) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *TextContentBlock) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *TextContentBlock) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetTextFormatType

`func (o *TextContentBlock) GetTextFormatType() string`

GetTextFormatType returns the TextFormatType field if non-nil, zero value otherwise.

### GetTextFormatTypeOk

`func (o *TextContentBlock) GetTextFormatTypeOk() (*string, bool)`

GetTextFormatTypeOk returns a tuple with the TextFormatType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTextFormatType

`func (o *TextContentBlock) SetTextFormatType(v string)`

SetTextFormatType sets TextFormatType field to given value.

### HasTextFormatType

`func (o *TextContentBlock) HasTextFormatType() bool`

HasTextFormatType returns a boolean if a field has been set.

### GetTextContent

`func (o *TextContentBlock) GetTextContent() string`

GetTextContent returns the TextContent field if non-nil, zero value otherwise.

### GetTextContentOk

`func (o *TextContentBlock) GetTextContentOk() (*string, bool)`

GetTextContentOk returns a tuple with the TextContent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTextContent

`func (o *TextContentBlock) SetTextContent(v string)`

SetTextContent sets TextContent field to given value.

### HasTextContent

`func (o *TextContentBlock) HasTextContent() bool`

HasTextContent returns a boolean if a field has been set.

### GetType

`func (o *TextContentBlock) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *TextContentBlock) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *TextContentBlock) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *TextContentBlock) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


