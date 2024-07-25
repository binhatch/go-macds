# IdentResponseDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Kba** | Pointer to **string** | KBA | [optional] 
**Probability** | Pointer to **float64** | Probability | [optional] 
**Ktype** | Pointer to **int32** | KType | [optional] 
**AdditionalInfo** | Pointer to [**IdentAdditionalInfoDTO**](IdentAdditionalInfoDTO.md) |  | [optional] 

## Methods

### NewIdentResponseDTO

`func NewIdentResponseDTO() *IdentResponseDTO`

NewIdentResponseDTO instantiates a new IdentResponseDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewIdentResponseDTOWithDefaults

`func NewIdentResponseDTOWithDefaults() *IdentResponseDTO`

NewIdentResponseDTOWithDefaults instantiates a new IdentResponseDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKba

`func (o *IdentResponseDTO) GetKba() string`

GetKba returns the Kba field if non-nil, zero value otherwise.

### GetKbaOk

`func (o *IdentResponseDTO) GetKbaOk() (*string, bool)`

GetKbaOk returns a tuple with the Kba field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKba

`func (o *IdentResponseDTO) SetKba(v string)`

SetKba sets Kba field to given value.

### HasKba

`func (o *IdentResponseDTO) HasKba() bool`

HasKba returns a boolean if a field has been set.

### GetProbability

`func (o *IdentResponseDTO) GetProbability() float64`

GetProbability returns the Probability field if non-nil, zero value otherwise.

### GetProbabilityOk

`func (o *IdentResponseDTO) GetProbabilityOk() (*float64, bool)`

GetProbabilityOk returns a tuple with the Probability field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProbability

`func (o *IdentResponseDTO) SetProbability(v float64)`

SetProbability sets Probability field to given value.

### HasProbability

`func (o *IdentResponseDTO) HasProbability() bool`

HasProbability returns a boolean if a field has been set.

### GetKtype

`func (o *IdentResponseDTO) GetKtype() int32`

GetKtype returns the Ktype field if non-nil, zero value otherwise.

### GetKtypeOk

`func (o *IdentResponseDTO) GetKtypeOk() (*int32, bool)`

GetKtypeOk returns a tuple with the Ktype field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKtype

`func (o *IdentResponseDTO) SetKtype(v int32)`

SetKtype sets Ktype field to given value.

### HasKtype

`func (o *IdentResponseDTO) HasKtype() bool`

HasKtype returns a boolean if a field has been set.

### GetAdditionalInfo

`func (o *IdentResponseDTO) GetAdditionalInfo() IdentAdditionalInfoDTO`

GetAdditionalInfo returns the AdditionalInfo field if non-nil, zero value otherwise.

### GetAdditionalInfoOk

`func (o *IdentResponseDTO) GetAdditionalInfoOk() (*IdentAdditionalInfoDTO, bool)`

GetAdditionalInfoOk returns a tuple with the AdditionalInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAdditionalInfo

`func (o *IdentResponseDTO) SetAdditionalInfo(v IdentAdditionalInfoDTO)`

SetAdditionalInfo sets AdditionalInfo field to given value.

### HasAdditionalInfo

`func (o *IdentResponseDTO) HasAdditionalInfo() bool`

HasAdditionalInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


