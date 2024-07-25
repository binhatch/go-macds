# Guide

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Id | [optional] 
**Title** | Pointer to [**TitleText**](TitleText.md) |  | [optional] 
**GuideSteps** | Pointer to [**[]GuideStep**](GuideStep.md) | Guide Steps | [optional] 

## Methods

### NewGuide

`func NewGuide() *Guide`

NewGuide instantiates a new Guide object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGuideWithDefaults

`func NewGuideWithDefaults() *Guide`

NewGuideWithDefaults instantiates a new Guide object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Guide) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Guide) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Guide) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Guide) HasId() bool`

HasId returns a boolean if a field has been set.

### GetTitle

`func (o *Guide) GetTitle() TitleText`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *Guide) GetTitleOk() (*TitleText, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *Guide) SetTitle(v TitleText)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *Guide) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetGuideSteps

`func (o *Guide) GetGuideSteps() []GuideStep`

GetGuideSteps returns the GuideSteps field if non-nil, zero value otherwise.

### GetGuideStepsOk

`func (o *Guide) GetGuideStepsOk() (*[]GuideStep, bool)`

GetGuideStepsOk returns a tuple with the GuideSteps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuideSteps

`func (o *Guide) SetGuideSteps(v []GuideStep)`

SetGuideSteps sets GuideSteps field to given value.

### HasGuideSteps

`func (o *Guide) HasGuideSteps() bool`

HasGuideSteps returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


