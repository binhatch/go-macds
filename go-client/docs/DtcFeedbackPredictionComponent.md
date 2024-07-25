# DtcFeedbackPredictionComponent

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ComponentId** | Pointer to **string** | The unique component ID by Hella Gutmann | [optional] 
**ComponentText** | Pointer to **string** | Text or name of the component | [optional] 
**ComponentMainText** | Pointer to **string** | Text or name of the component group, which can be shown alongside the component text for additional context. | [optional] 
**Language** | Pointer to **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | [optional] 

## Methods

### NewDtcFeedbackPredictionComponent

`func NewDtcFeedbackPredictionComponent() *DtcFeedbackPredictionComponent`

NewDtcFeedbackPredictionComponent instantiates a new DtcFeedbackPredictionComponent object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtcFeedbackPredictionComponentWithDefaults

`func NewDtcFeedbackPredictionComponentWithDefaults() *DtcFeedbackPredictionComponent`

NewDtcFeedbackPredictionComponentWithDefaults instantiates a new DtcFeedbackPredictionComponent object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComponentId

`func (o *DtcFeedbackPredictionComponent) GetComponentId() string`

GetComponentId returns the ComponentId field if non-nil, zero value otherwise.

### GetComponentIdOk

`func (o *DtcFeedbackPredictionComponent) GetComponentIdOk() (*string, bool)`

GetComponentIdOk returns a tuple with the ComponentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentId

`func (o *DtcFeedbackPredictionComponent) SetComponentId(v string)`

SetComponentId sets ComponentId field to given value.

### HasComponentId

`func (o *DtcFeedbackPredictionComponent) HasComponentId() bool`

HasComponentId returns a boolean if a field has been set.

### GetComponentText

`func (o *DtcFeedbackPredictionComponent) GetComponentText() string`

GetComponentText returns the ComponentText field if non-nil, zero value otherwise.

### GetComponentTextOk

`func (o *DtcFeedbackPredictionComponent) GetComponentTextOk() (*string, bool)`

GetComponentTextOk returns a tuple with the ComponentText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentText

`func (o *DtcFeedbackPredictionComponent) SetComponentText(v string)`

SetComponentText sets ComponentText field to given value.

### HasComponentText

`func (o *DtcFeedbackPredictionComponent) HasComponentText() bool`

HasComponentText returns a boolean if a field has been set.

### GetComponentMainText

`func (o *DtcFeedbackPredictionComponent) GetComponentMainText() string`

GetComponentMainText returns the ComponentMainText field if non-nil, zero value otherwise.

### GetComponentMainTextOk

`func (o *DtcFeedbackPredictionComponent) GetComponentMainTextOk() (*string, bool)`

GetComponentMainTextOk returns a tuple with the ComponentMainText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentMainText

`func (o *DtcFeedbackPredictionComponent) SetComponentMainText(v string)`

SetComponentMainText sets ComponentMainText field to given value.

### HasComponentMainText

`func (o *DtcFeedbackPredictionComponent) HasComponentMainText() bool`

HasComponentMainText returns a boolean if a field has been set.

### GetLanguage

`func (o *DtcFeedbackPredictionComponent) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *DtcFeedbackPredictionComponent) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *DtcFeedbackPredictionComponent) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *DtcFeedbackPredictionComponent) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


