# BreakContentBlock

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Order** | Pointer to **int32** | Order | [optional] 
**TextFormatType** | Pointer to **string** | Suggestion of the text format for the respective content block. Values can be \&quot;break-line\&quot; or \&quot;break-page\&quot;. | [optional] 
**Type** | Pointer to **string** | Break Type | [optional] 

## Methods

### NewBreakContentBlock

`func NewBreakContentBlock() *BreakContentBlock`

NewBreakContentBlock instantiates a new BreakContentBlock object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBreakContentBlockWithDefaults

`func NewBreakContentBlockWithDefaults() *BreakContentBlock`

NewBreakContentBlockWithDefaults instantiates a new BreakContentBlock object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetOrder

`func (o *BreakContentBlock) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *BreakContentBlock) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *BreakContentBlock) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *BreakContentBlock) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetTextFormatType

`func (o *BreakContentBlock) GetTextFormatType() string`

GetTextFormatType returns the TextFormatType field if non-nil, zero value otherwise.

### GetTextFormatTypeOk

`func (o *BreakContentBlock) GetTextFormatTypeOk() (*string, bool)`

GetTextFormatTypeOk returns a tuple with the TextFormatType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTextFormatType

`func (o *BreakContentBlock) SetTextFormatType(v string)`

SetTextFormatType sets TextFormatType field to given value.

### HasTextFormatType

`func (o *BreakContentBlock) HasTextFormatType() bool`

HasTextFormatType returns a boolean if a field has been set.

### GetType

`func (o *BreakContentBlock) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *BreakContentBlock) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *BreakContentBlock) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *BreakContentBlock) HasType() bool`

HasType returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


