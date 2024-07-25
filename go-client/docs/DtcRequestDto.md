# DtcRequestDto

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DtcReadType** | Pointer to **string** | If known, specify if you read out OBD, OE specific systems, or the OBD norm for commercial trucks. If not specified, the API will attempt to apply OBD first, then OE if no results found. | [optional] 
**Vin** | **string** | VIN - vehicle identifier number | 
**Language** | **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | 
**Page** | Pointer to **int64** | Requested page in case of more results | [optional] 
**WithRecommendation** | Pointer to **bool** | Parameter to indicate if user wants recommendations. | [optional] 
**WithClassification** | Pointer to **bool** | Parameter to indicate if user wants classifications. | [optional] 
**AllowMultipleResults** | Pointer to **bool** | If set to false, DTCs that translate to more than 1 meaning due to a missing specification of the parameter \&quot;ecuSystem\&quot; will return an error that the DTC is ambigious. If set to true, the API will return all results that match the specified DTC, along with the indication of the related ECU System. | [optional] 
**ComponentPredict** | Pointer to **bool** | If set to true, our AI will attempt to predict a component that is affected based on the DTCs provided. | [optional] 
**MilActive** | Pointer to **bool** | Set to true if the vehicle&#39;s malfunction indicator lamp (\&quot;MIL\&quot;), also known as \&quot;warning light\&quot; or \&quot;check engine light\&quot;, is on; used for calculating the criticality index | [optional] 
**RelatedRmi** | Pointer to **string** | Can be html or json. If json is not explicitly specified it defaults to html. | [optional] 
**Dtcs** | [**[]DtcsDto**](DtcsDto.md) | A list of DTC codes | 

## Methods

### NewDtcRequestDto

`func NewDtcRequestDto(vin string, language string, dtcs []DtcsDto, ) *DtcRequestDto`

NewDtcRequestDto instantiates a new DtcRequestDto object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDtcRequestDtoWithDefaults

`func NewDtcRequestDtoWithDefaults() *DtcRequestDto`

NewDtcRequestDtoWithDefaults instantiates a new DtcRequestDto object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDtcReadType

`func (o *DtcRequestDto) GetDtcReadType() string`

GetDtcReadType returns the DtcReadType field if non-nil, zero value otherwise.

### GetDtcReadTypeOk

`func (o *DtcRequestDto) GetDtcReadTypeOk() (*string, bool)`

GetDtcReadTypeOk returns a tuple with the DtcReadType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDtcReadType

`func (o *DtcRequestDto) SetDtcReadType(v string)`

SetDtcReadType sets DtcReadType field to given value.

### HasDtcReadType

`func (o *DtcRequestDto) HasDtcReadType() bool`

HasDtcReadType returns a boolean if a field has been set.

### GetVin

`func (o *DtcRequestDto) GetVin() string`

GetVin returns the Vin field if non-nil, zero value otherwise.

### GetVinOk

`func (o *DtcRequestDto) GetVinOk() (*string, bool)`

GetVinOk returns a tuple with the Vin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVin

`func (o *DtcRequestDto) SetVin(v string)`

SetVin sets Vin field to given value.


### GetLanguage

`func (o *DtcRequestDto) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *DtcRequestDto) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *DtcRequestDto) SetLanguage(v string)`

SetLanguage sets Language field to given value.


### GetPage

`func (o *DtcRequestDto) GetPage() int64`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *DtcRequestDto) GetPageOk() (*int64, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *DtcRequestDto) SetPage(v int64)`

SetPage sets Page field to given value.

### HasPage

`func (o *DtcRequestDto) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetWithRecommendation

`func (o *DtcRequestDto) GetWithRecommendation() bool`

GetWithRecommendation returns the WithRecommendation field if non-nil, zero value otherwise.

### GetWithRecommendationOk

`func (o *DtcRequestDto) GetWithRecommendationOk() (*bool, bool)`

GetWithRecommendationOk returns a tuple with the WithRecommendation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithRecommendation

`func (o *DtcRequestDto) SetWithRecommendation(v bool)`

SetWithRecommendation sets WithRecommendation field to given value.

### HasWithRecommendation

`func (o *DtcRequestDto) HasWithRecommendation() bool`

HasWithRecommendation returns a boolean if a field has been set.

### GetWithClassification

`func (o *DtcRequestDto) GetWithClassification() bool`

GetWithClassification returns the WithClassification field if non-nil, zero value otherwise.

### GetWithClassificationOk

`func (o *DtcRequestDto) GetWithClassificationOk() (*bool, bool)`

GetWithClassificationOk returns a tuple with the WithClassification field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWithClassification

`func (o *DtcRequestDto) SetWithClassification(v bool)`

SetWithClassification sets WithClassification field to given value.

### HasWithClassification

`func (o *DtcRequestDto) HasWithClassification() bool`

HasWithClassification returns a boolean if a field has been set.

### GetAllowMultipleResults

`func (o *DtcRequestDto) GetAllowMultipleResults() bool`

GetAllowMultipleResults returns the AllowMultipleResults field if non-nil, zero value otherwise.

### GetAllowMultipleResultsOk

`func (o *DtcRequestDto) GetAllowMultipleResultsOk() (*bool, bool)`

GetAllowMultipleResultsOk returns a tuple with the AllowMultipleResults field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowMultipleResults

`func (o *DtcRequestDto) SetAllowMultipleResults(v bool)`

SetAllowMultipleResults sets AllowMultipleResults field to given value.

### HasAllowMultipleResults

`func (o *DtcRequestDto) HasAllowMultipleResults() bool`

HasAllowMultipleResults returns a boolean if a field has been set.

### GetComponentPredict

`func (o *DtcRequestDto) GetComponentPredict() bool`

GetComponentPredict returns the ComponentPredict field if non-nil, zero value otherwise.

### GetComponentPredictOk

`func (o *DtcRequestDto) GetComponentPredictOk() (*bool, bool)`

GetComponentPredictOk returns a tuple with the ComponentPredict field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentPredict

`func (o *DtcRequestDto) SetComponentPredict(v bool)`

SetComponentPredict sets ComponentPredict field to given value.

### HasComponentPredict

`func (o *DtcRequestDto) HasComponentPredict() bool`

HasComponentPredict returns a boolean if a field has been set.

### GetMilActive

`func (o *DtcRequestDto) GetMilActive() bool`

GetMilActive returns the MilActive field if non-nil, zero value otherwise.

### GetMilActiveOk

`func (o *DtcRequestDto) GetMilActiveOk() (*bool, bool)`

GetMilActiveOk returns a tuple with the MilActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMilActive

`func (o *DtcRequestDto) SetMilActive(v bool)`

SetMilActive sets MilActive field to given value.

### HasMilActive

`func (o *DtcRequestDto) HasMilActive() bool`

HasMilActive returns a boolean if a field has been set.

### GetRelatedRmi

`func (o *DtcRequestDto) GetRelatedRmi() string`

GetRelatedRmi returns the RelatedRmi field if non-nil, zero value otherwise.

### GetRelatedRmiOk

`func (o *DtcRequestDto) GetRelatedRmiOk() (*string, bool)`

GetRelatedRmiOk returns a tuple with the RelatedRmi field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelatedRmi

`func (o *DtcRequestDto) SetRelatedRmi(v string)`

SetRelatedRmi sets RelatedRmi field to given value.

### HasRelatedRmi

`func (o *DtcRequestDto) HasRelatedRmi() bool`

HasRelatedRmi returns a boolean if a field has been set.

### GetDtcs

`func (o *DtcRequestDto) GetDtcs() []DtcsDto`

GetDtcs returns the Dtcs field if non-nil, zero value otherwise.

### GetDtcsOk

`func (o *DtcRequestDto) GetDtcsOk() (*[]DtcsDto, bool)`

GetDtcsOk returns a tuple with the Dtcs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDtcs

`func (o *DtcRequestDto) SetDtcs(v []DtcsDto)`

SetDtcs sets Dtcs field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


