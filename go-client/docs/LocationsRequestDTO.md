# LocationsRequestDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ktype** | **int32** | KType | 
**Language** | **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | 
**YearFrom** | Pointer to **string** | Year From | [optional] 
**YearTo** | Pointer to **string** | Year To | [optional] 
**EngineCode** | Pointer to **string** | Engine Code | [optional] 
**ComponentId** | Pointer to **int32** | Component Id | [optional] 
**ImageId** | Pointer to **int32** | Image Id | [optional] 

## Methods

### NewLocationsRequestDTO

`func NewLocationsRequestDTO(ktype int32, language string, ) *LocationsRequestDTO`

NewLocationsRequestDTO instantiates a new LocationsRequestDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLocationsRequestDTOWithDefaults

`func NewLocationsRequestDTOWithDefaults() *LocationsRequestDTO`

NewLocationsRequestDTOWithDefaults instantiates a new LocationsRequestDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKtype

`func (o *LocationsRequestDTO) GetKtype() int32`

GetKtype returns the Ktype field if non-nil, zero value otherwise.

### GetKtypeOk

`func (o *LocationsRequestDTO) GetKtypeOk() (*int32, bool)`

GetKtypeOk returns a tuple with the Ktype field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKtype

`func (o *LocationsRequestDTO) SetKtype(v int32)`

SetKtype sets Ktype field to given value.


### GetLanguage

`func (o *LocationsRequestDTO) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *LocationsRequestDTO) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *LocationsRequestDTO) SetLanguage(v string)`

SetLanguage sets Language field to given value.


### GetYearFrom

`func (o *LocationsRequestDTO) GetYearFrom() string`

GetYearFrom returns the YearFrom field if non-nil, zero value otherwise.

### GetYearFromOk

`func (o *LocationsRequestDTO) GetYearFromOk() (*string, bool)`

GetYearFromOk returns a tuple with the YearFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearFrom

`func (o *LocationsRequestDTO) SetYearFrom(v string)`

SetYearFrom sets YearFrom field to given value.

### HasYearFrom

`func (o *LocationsRequestDTO) HasYearFrom() bool`

HasYearFrom returns a boolean if a field has been set.

### GetYearTo

`func (o *LocationsRequestDTO) GetYearTo() string`

GetYearTo returns the YearTo field if non-nil, zero value otherwise.

### GetYearToOk

`func (o *LocationsRequestDTO) GetYearToOk() (*string, bool)`

GetYearToOk returns a tuple with the YearTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearTo

`func (o *LocationsRequestDTO) SetYearTo(v string)`

SetYearTo sets YearTo field to given value.

### HasYearTo

`func (o *LocationsRequestDTO) HasYearTo() bool`

HasYearTo returns a boolean if a field has been set.

### GetEngineCode

`func (o *LocationsRequestDTO) GetEngineCode() string`

GetEngineCode returns the EngineCode field if non-nil, zero value otherwise.

### GetEngineCodeOk

`func (o *LocationsRequestDTO) GetEngineCodeOk() (*string, bool)`

GetEngineCodeOk returns a tuple with the EngineCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCode

`func (o *LocationsRequestDTO) SetEngineCode(v string)`

SetEngineCode sets EngineCode field to given value.

### HasEngineCode

`func (o *LocationsRequestDTO) HasEngineCode() bool`

HasEngineCode returns a boolean if a field has been set.

### GetComponentId

`func (o *LocationsRequestDTO) GetComponentId() int32`

GetComponentId returns the ComponentId field if non-nil, zero value otherwise.

### GetComponentIdOk

`func (o *LocationsRequestDTO) GetComponentIdOk() (*int32, bool)`

GetComponentIdOk returns a tuple with the ComponentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentId

`func (o *LocationsRequestDTO) SetComponentId(v int32)`

SetComponentId sets ComponentId field to given value.

### HasComponentId

`func (o *LocationsRequestDTO) HasComponentId() bool`

HasComponentId returns a boolean if a field has been set.

### GetImageId

`func (o *LocationsRequestDTO) GetImageId() int32`

GetImageId returns the ImageId field if non-nil, zero value otherwise.

### GetImageIdOk

`func (o *LocationsRequestDTO) GetImageIdOk() (*int32, bool)`

GetImageIdOk returns a tuple with the ImageId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageId

`func (o *LocationsRequestDTO) SetImageId(v int32)`

SetImageId sets ImageId field to given value.

### HasImageId

`func (o *LocationsRequestDTO) HasImageId() bool`

HasImageId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


