# WiringDiagramsDiagramsRequestDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**SystemId** | **string** | id of the system of which a wiring exists. It is found in the response of the /systems endpoint, and required as input of the /diagram endpoint. | 
**Language** | **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | 

## Methods

### NewWiringDiagramsDiagramsRequestDTO

`func NewWiringDiagramsDiagramsRequestDTO(systemId string, language string, ) *WiringDiagramsDiagramsRequestDTO`

NewWiringDiagramsDiagramsRequestDTO instantiates a new WiringDiagramsDiagramsRequestDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewWiringDiagramsDiagramsRequestDTOWithDefaults

`func NewWiringDiagramsDiagramsRequestDTOWithDefaults() *WiringDiagramsDiagramsRequestDTO`

NewWiringDiagramsDiagramsRequestDTOWithDefaults instantiates a new WiringDiagramsDiagramsRequestDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSystemId

`func (o *WiringDiagramsDiagramsRequestDTO) GetSystemId() string`

GetSystemId returns the SystemId field if non-nil, zero value otherwise.

### GetSystemIdOk

`func (o *WiringDiagramsDiagramsRequestDTO) GetSystemIdOk() (*string, bool)`

GetSystemIdOk returns a tuple with the SystemId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemId

`func (o *WiringDiagramsDiagramsRequestDTO) SetSystemId(v string)`

SetSystemId sets SystemId field to given value.


### GetLanguage

`func (o *WiringDiagramsDiagramsRequestDTO) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *WiringDiagramsDiagramsRequestDTO) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *WiringDiagramsDiagramsRequestDTO) SetLanguage(v string)`

SetLanguage sets Language field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


