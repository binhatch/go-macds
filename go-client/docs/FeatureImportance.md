# FeatureImportance

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Plot** | Pointer to **string** | Plot | [optional] 
**Css** | Pointer to **string** | Css | [optional] 
**Sankey** | Pointer to [**[]Sankey**](Sankey.md) | Sankey diagram showing the relevance of each provided DTC and the component prediction it relates to, encoded as base64 | [optional] 

## Methods

### NewFeatureImportance

`func NewFeatureImportance() *FeatureImportance`

NewFeatureImportance instantiates a new FeatureImportance object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewFeatureImportanceWithDefaults

`func NewFeatureImportanceWithDefaults() *FeatureImportance`

NewFeatureImportanceWithDefaults instantiates a new FeatureImportance object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPlot

`func (o *FeatureImportance) GetPlot() string`

GetPlot returns the Plot field if non-nil, zero value otherwise.

### GetPlotOk

`func (o *FeatureImportance) GetPlotOk() (*string, bool)`

GetPlotOk returns a tuple with the Plot field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlot

`func (o *FeatureImportance) SetPlot(v string)`

SetPlot sets Plot field to given value.

### HasPlot

`func (o *FeatureImportance) HasPlot() bool`

HasPlot returns a boolean if a field has been set.

### GetCss

`func (o *FeatureImportance) GetCss() string`

GetCss returns the Css field if non-nil, zero value otherwise.

### GetCssOk

`func (o *FeatureImportance) GetCssOk() (*string, bool)`

GetCssOk returns a tuple with the Css field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCss

`func (o *FeatureImportance) SetCss(v string)`

SetCss sets Css field to given value.

### HasCss

`func (o *FeatureImportance) HasCss() bool`

HasCss returns a boolean if a field has been set.

### GetSankey

`func (o *FeatureImportance) GetSankey() []Sankey`

GetSankey returns the Sankey field if non-nil, zero value otherwise.

### GetSankeyOk

`func (o *FeatureImportance) GetSankeyOk() (*[]Sankey, bool)`

GetSankeyOk returns a tuple with the Sankey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSankey

`func (o *FeatureImportance) SetSankey(v []Sankey)`

SetSankey sets Sankey field to given value.

### HasSankey

`func (o *FeatureImportance) HasSankey() bool`

HasSankey returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


