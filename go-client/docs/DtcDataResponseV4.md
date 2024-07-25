# DtcDataResponseV4

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DtcInput** | Pointer to [**InputedData**](InputedData.md) |  | [optional] 
**Codes** | Pointer to [**Codes**](Codes.md) |  | [optional] 
**Code** | Pointer to **string** | Code | [optional] 
**DtcTextId** | Pointer to **string** | DTC Text Id | [optional] 
**Category** | Pointer to [**DtcTranslation**](DtcTranslation.md) |  | [optional] 
**Subcategory** | Pointer to [**DtcTranslation**](DtcTranslation.md) |  | [optional] 
**Information** | Pointer to [**DtcTranslation**](DtcTranslation.md) |  | [optional] 
**Warning** | Pointer to [**Warning**](Warning.md) |  | [optional] 
**Cause** | Pointer to [**DtcTranslation**](DtcTranslation.md) |  | [optional] 
**Effect** | Pointer to [**DtcTranslation**](DtcTranslation.md) |  | [optional] 
**Classification** | Pointer to **string** | Classification | [optional] 
**Recommendation** | Pointer to [**Recommendation**](Recommendation.md) |  | [optional] 
**EcuSystems** | Pointer to [**[]DtcTranslation**](DtcTranslation.md) | An array of all ECU system were the found DTC might exist | [optional] 
**Error** | Pointer to [**Error**](Error.md) |  | [optional] 
**Relevance** | Pointer to **string** | If multiple results are found, a ranking (based on statistical relevance) might be shown. | [optional] 

## Methods

### NewDtcDataResponseV4

`func NewDtcDataResponseV4() *DtcDataResponseV4`

NewDtcDataResponseV4 instantiates a new DtcDataResponseV4 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtcDataResponseV4WithDefaults

`func NewDtcDataResponseV4WithDefaults() *DtcDataResponseV4`

NewDtcDataResponseV4WithDefaults instantiates a new DtcDataResponseV4 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDtcInput

`func (o *DtcDataResponseV4) GetDtcInput() InputedData`

GetDtcInput returns the DtcInput field if non-nil, zero value otherwise.

### GetDtcInputOk

`func (o *DtcDataResponseV4) GetDtcInputOk() (*InputedData, bool)`

GetDtcInputOk returns a tuple with the DtcInput field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDtcInput

`func (o *DtcDataResponseV4) SetDtcInput(v InputedData)`

SetDtcInput sets DtcInput field to given value.

### HasDtcInput

`func (o *DtcDataResponseV4) HasDtcInput() bool`

HasDtcInput returns a boolean if a field has been set.

### GetCodes

`func (o *DtcDataResponseV4) GetCodes() Codes`

GetCodes returns the Codes field if non-nil, zero value otherwise.

### GetCodesOk

`func (o *DtcDataResponseV4) GetCodesOk() (*Codes, bool)`

GetCodesOk returns a tuple with the Codes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodes

`func (o *DtcDataResponseV4) SetCodes(v Codes)`

SetCodes sets Codes field to given value.

### HasCodes

`func (o *DtcDataResponseV4) HasCodes() bool`

HasCodes returns a boolean if a field has been set.

### GetCode

`func (o *DtcDataResponseV4) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *DtcDataResponseV4) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *DtcDataResponseV4) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *DtcDataResponseV4) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetDtcTextId

`func (o *DtcDataResponseV4) GetDtcTextId() string`

GetDtcTextId returns the DtcTextId field if non-nil, zero value otherwise.

### GetDtcTextIdOk

`func (o *DtcDataResponseV4) GetDtcTextIdOk() (*string, bool)`

GetDtcTextIdOk returns a tuple with the DtcTextId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDtcTextId

`func (o *DtcDataResponseV4) SetDtcTextId(v string)`

SetDtcTextId sets DtcTextId field to given value.

### HasDtcTextId

`func (o *DtcDataResponseV4) HasDtcTextId() bool`

HasDtcTextId returns a boolean if a field has been set.

### GetCategory

`func (o *DtcDataResponseV4) GetCategory() DtcTranslation`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *DtcDataResponseV4) GetCategoryOk() (*DtcTranslation, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *DtcDataResponseV4) SetCategory(v DtcTranslation)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *DtcDataResponseV4) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### GetSubcategory

`func (o *DtcDataResponseV4) GetSubcategory() DtcTranslation`

GetSubcategory returns the Subcategory field if non-nil, zero value otherwise.

### GetSubcategoryOk

`func (o *DtcDataResponseV4) GetSubcategoryOk() (*DtcTranslation, bool)`

GetSubcategoryOk returns a tuple with the Subcategory field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubcategory

`func (o *DtcDataResponseV4) SetSubcategory(v DtcTranslation)`

SetSubcategory sets Subcategory field to given value.

### HasSubcategory

`func (o *DtcDataResponseV4) HasSubcategory() bool`

HasSubcategory returns a boolean if a field has been set.

### GetInformation

`func (o *DtcDataResponseV4) GetInformation() DtcTranslation`

GetInformation returns the Information field if non-nil, zero value otherwise.

### GetInformationOk

`func (o *DtcDataResponseV4) GetInformationOk() (*DtcTranslation, bool)`

GetInformationOk returns a tuple with the Information field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInformation

`func (o *DtcDataResponseV4) SetInformation(v DtcTranslation)`

SetInformation sets Information field to given value.

### HasInformation

`func (o *DtcDataResponseV4) HasInformation() bool`

HasInformation returns a boolean if a field has been set.

### GetWarning

`func (o *DtcDataResponseV4) GetWarning() Warning`

GetWarning returns the Warning field if non-nil, zero value otherwise.

### GetWarningOk

`func (o *DtcDataResponseV4) GetWarningOk() (*Warning, bool)`

GetWarningOk returns a tuple with the Warning field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWarning

`func (o *DtcDataResponseV4) SetWarning(v Warning)`

SetWarning sets Warning field to given value.

### HasWarning

`func (o *DtcDataResponseV4) HasWarning() bool`

HasWarning returns a boolean if a field has been set.

### GetCause

`func (o *DtcDataResponseV4) GetCause() DtcTranslation`

GetCause returns the Cause field if non-nil, zero value otherwise.

### GetCauseOk

`func (o *DtcDataResponseV4) GetCauseOk() (*DtcTranslation, bool)`

GetCauseOk returns a tuple with the Cause field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCause

`func (o *DtcDataResponseV4) SetCause(v DtcTranslation)`

SetCause sets Cause field to given value.

### HasCause

`func (o *DtcDataResponseV4) HasCause() bool`

HasCause returns a boolean if a field has been set.

### GetEffect

`func (o *DtcDataResponseV4) GetEffect() DtcTranslation`

GetEffect returns the Effect field if non-nil, zero value otherwise.

### GetEffectOk

`func (o *DtcDataResponseV4) GetEffectOk() (*DtcTranslation, bool)`

GetEffectOk returns a tuple with the Effect field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEffect

`func (o *DtcDataResponseV4) SetEffect(v DtcTranslation)`

SetEffect sets Effect field to given value.

### HasEffect

`func (o *DtcDataResponseV4) HasEffect() bool`

HasEffect returns a boolean if a field has been set.

### GetClassification

`func (o *DtcDataResponseV4) GetClassification() string`

GetClassification returns the Classification field if non-nil, zero value otherwise.

### GetClassificationOk

`func (o *DtcDataResponseV4) GetClassificationOk() (*string, bool)`

GetClassificationOk returns a tuple with the Classification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetClassification

`func (o *DtcDataResponseV4) SetClassification(v string)`

SetClassification sets Classification field to given value.

### HasClassification

`func (o *DtcDataResponseV4) HasClassification() bool`

HasClassification returns a boolean if a field has been set.

### GetRecommendation

`func (o *DtcDataResponseV4) GetRecommendation() Recommendation`

GetRecommendation returns the Recommendation field if non-nil, zero value otherwise.

### GetRecommendationOk

`func (o *DtcDataResponseV4) GetRecommendationOk() (*Recommendation, bool)`

GetRecommendationOk returns a tuple with the Recommendation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecommendation

`func (o *DtcDataResponseV4) SetRecommendation(v Recommendation)`

SetRecommendation sets Recommendation field to given value.

### HasRecommendation

`func (o *DtcDataResponseV4) HasRecommendation() bool`

HasRecommendation returns a boolean if a field has been set.

### GetEcuSystems

`func (o *DtcDataResponseV4) GetEcuSystems() []DtcTranslation`

GetEcuSystems returns the EcuSystems field if non-nil, zero value otherwise.

### GetEcuSystemsOk

`func (o *DtcDataResponseV4) GetEcuSystemsOk() (*[]DtcTranslation, bool)`

GetEcuSystemsOk returns a tuple with the EcuSystems field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEcuSystems

`func (o *DtcDataResponseV4) SetEcuSystems(v []DtcTranslation)`

SetEcuSystems sets EcuSystems field to given value.

### HasEcuSystems

`func (o *DtcDataResponseV4) HasEcuSystems() bool`

HasEcuSystems returns a boolean if a field has been set.

### GetError

`func (o *DtcDataResponseV4) GetError() Error`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *DtcDataResponseV4) GetErrorOk() (*Error, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *DtcDataResponseV4) SetError(v Error)`

SetError sets Error field to given value.

### HasError

`func (o *DtcDataResponseV4) HasError() bool`

HasError returns a boolean if a field has been set.

### GetRelevance

`func (o *DtcDataResponseV4) GetRelevance() string`

GetRelevance returns the Relevance field if non-nil, zero value otherwise.

### GetRelevanceOk

`func (o *DtcDataResponseV4) GetRelevanceOk() (*string, bool)`

GetRelevanceOk returns a tuple with the Relevance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelevance

`func (o *DtcDataResponseV4) SetRelevance(v string)`

SetRelevance sets Relevance field to given value.

### HasRelevance

`func (o *DtcDataResponseV4) HasRelevance() bool`

HasRelevance returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


