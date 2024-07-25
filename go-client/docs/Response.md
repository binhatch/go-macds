# Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Status** | Pointer to **int32** | Status | [optional] 
**Error** | Pointer to [**Error**](Error.md) |  | [optional] 
**Page** | Pointer to **int32** | Page | [optional] 
**TotalItems** | Pointer to **int32** | Number of total items | [optional] 
**TotalPages** | Pointer to **int32** | Number of total pages | [optional] 
**Data** | Pointer to [**[]DtcDataResponseV4**](DtcDataResponseV4.md) | Response data array of objects | [optional] 
**PredictedComponents** | Pointer to [**[]Component**](Component.md) | Array containing predicted components and further information. | [optional] 
**FeatureImportance** | Pointer to [**FeatureImportance**](FeatureImportance.md) |  | [optional] 
**Criticality** | Pointer to **float32** | Numerical index based on the number and severity of trouble codes (critical, warning) | [optional] 
**PredictionFeedbackReference** | Pointer to **string** | Unique string which references the related request and response of the component prediction for tracking purpose. | [optional] 

## Methods

### NewResponse

`func NewResponse() *Response`

NewResponse instantiates a new Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResponseWithDefaults

`func NewResponseWithDefaults() *Response`

NewResponseWithDefaults instantiates a new Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStatus

`func (o *Response) GetStatus() int32`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Response) GetStatusOk() (*int32, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Response) SetStatus(v int32)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Response) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetError

`func (o *Response) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *Response) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *Response) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *Response) HasError() bool`

HasError returns a boolean if a field has been set.

### GetPage

`func (o *Response) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *Response) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *Response) SetPage(v int32)`

SetPage sets Page field to given value.

### HasPage

`func (o *Response) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetTotalItems

`func (o *Response) GetTotalItems() int32`

GetTotalItems returns the TotalItems field if non-nil, zero value otherwise.

### GetTotalItemsOk

`func (o *Response) GetTotalItemsOk() (*int32, bool)`

GetTotalItemsOk returns a tuple with the TotalItems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalItems

`func (o *Response) SetTotalItems(v int32)`

SetTotalItems sets TotalItems field to given value.

### HasTotalItems

`func (o *Response) HasTotalItems() bool`

HasTotalItems returns a boolean if a field has been set.

### GetTotalPages

`func (o *Response) GetTotalPages() int32`

GetTotalPages returns the TotalPages field if non-nil, zero value otherwise.

### GetTotalPagesOk

`func (o *Response) GetTotalPagesOk() (*int32, bool)`

GetTotalPagesOk returns a tuple with the TotalPages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPages

`func (o *Response) SetTotalPages(v int32)`

SetTotalPages sets TotalPages field to given value.

### HasTotalPages

`func (o *Response) HasTotalPages() bool`

HasTotalPages returns a boolean if a field has been set.

### GetData

`func (o *Response) GetData() []DtcDataResponseV4`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *Response) GetDataOk() (*[]DtcDataResponseV4, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *Response) SetData(v []DtcDataResponseV4)`

SetData sets Data field to given value.

### HasData

`func (o *Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetPredictedComponents

`func (o *Response) GetPredictedComponents() []Component`

GetPredictedComponents returns the PredictedComponents field if non-nil, zero value otherwise.

### GetPredictedComponentsOk

`func (o *Response) GetPredictedComponentsOk() (*[]Component, bool)`

GetPredictedComponentsOk returns a tuple with the PredictedComponents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPredictedComponents

`func (o *Response) SetPredictedComponents(v []Component)`

SetPredictedComponents sets PredictedComponents field to given value.

### HasPredictedComponents

`func (o *Response) HasPredictedComponents() bool`

HasPredictedComponents returns a boolean if a field has been set.

### GetFeatureImportance

`func (o *Response) GetFeatureImportance() FeatureImportance`

GetFeatureImportance returns the FeatureImportance field if non-nil, zero value otherwise.

### GetFeatureImportanceOk

`func (o *Response) GetFeatureImportanceOk() (*FeatureImportance, bool)`

GetFeatureImportanceOk returns a tuple with the FeatureImportance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFeatureImportance

`func (o *Response) SetFeatureImportance(v FeatureImportance)`

SetFeatureImportance sets FeatureImportance field to given value.

### HasFeatureImportance

`func (o *Response) HasFeatureImportance() bool`

HasFeatureImportance returns a boolean if a field has been set.

### GetCriticality

`func (o *Response) GetCriticality() float32`

GetCriticality returns the Criticality field if non-nil, zero value otherwise.

### GetCriticalityOk

`func (o *Response) GetCriticalityOk() (*float32, bool)`

GetCriticalityOk returns a tuple with the Criticality field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCriticality

`func (o *Response) SetCriticality(v float32)`

SetCriticality sets Criticality field to given value.

### HasCriticality

`func (o *Response) HasCriticality() bool`

HasCriticality returns a boolean if a field has been set.

### GetPredictionFeedbackReference

`func (o *Response) GetPredictionFeedbackReference() string`

GetPredictionFeedbackReference returns the PredictionFeedbackReference field if non-nil, zero value otherwise.

### GetPredictionFeedbackReferenceOk

`func (o *Response) GetPredictionFeedbackReferenceOk() (*string, bool)`

GetPredictionFeedbackReferenceOk returns a tuple with the PredictionFeedbackReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPredictionFeedbackReference

`func (o *Response) SetPredictionFeedbackReference(v string)`

SetPredictionFeedbackReference sets PredictionFeedbackReference field to given value.

### HasPredictionFeedbackReference

`func (o *Response) HasPredictionFeedbackReference() bool`

HasPredictionFeedbackReference returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


