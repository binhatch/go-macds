# RelayDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Id | [optional] 
**Text** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**ComponentFuseName** | Pointer to **string** | Component Fuese Name | [optional] 
**LocationText** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**LocationImageUrl** | Pointer to **string** | Location Image URL | [optional] 
**FuseBoxImageUrl** | Pointer to **string** | Fuse Box Image URL | [optional] 
**Coordinates** | Pointer to [**CoordinatesDTO**](CoordinatesDTO.md) |  | [optional] 

## Methods

### NewRelayDTO

`func NewRelayDTO() *RelayDTO`

NewRelayDTO instantiates a new RelayDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRelayDTOWithDefaults

`func NewRelayDTOWithDefaults() *RelayDTO`

NewRelayDTOWithDefaults instantiates a new RelayDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *RelayDTO) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RelayDTO) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RelayDTO) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *RelayDTO) HasId() bool`

HasId returns a boolean if a field has been set.

### GetText

`func (o *RelayDTO) GetText() Texts`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *RelayDTO) GetTextOk() (*Texts, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *RelayDTO) SetText(v Texts)`

SetText sets Text field to given value.

### HasText

`func (o *RelayDTO) HasText() bool`

HasText returns a boolean if a field has been set.

### GetComponentFuseName

`func (o *RelayDTO) GetComponentFuseName() string`

GetComponentFuseName returns the ComponentFuseName field if non-nil, zero value otherwise.

### GetComponentFuseNameOk

`func (o *RelayDTO) GetComponentFuseNameOk() (*string, bool)`

GetComponentFuseNameOk returns a tuple with the ComponentFuseName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentFuseName

`func (o *RelayDTO) SetComponentFuseName(v string)`

SetComponentFuseName sets ComponentFuseName field to given value.

### HasComponentFuseName

`func (o *RelayDTO) HasComponentFuseName() bool`

HasComponentFuseName returns a boolean if a field has been set.

### GetLocationText

`func (o *RelayDTO) GetLocationText() Texts`

GetLocationText returns the LocationText field if non-nil, zero value otherwise.

### GetLocationTextOk

`func (o *RelayDTO) GetLocationTextOk() (*Texts, bool)`

GetLocationTextOk returns a tuple with the LocationText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationText

`func (o *RelayDTO) SetLocationText(v Texts)`

SetLocationText sets LocationText field to given value.

### HasLocationText

`func (o *RelayDTO) HasLocationText() bool`

HasLocationText returns a boolean if a field has been set.

### GetLocationImageUrl

`func (o *RelayDTO) GetLocationImageUrl() string`

GetLocationImageUrl returns the LocationImageUrl field if non-nil, zero value otherwise.

### GetLocationImageUrlOk

`func (o *RelayDTO) GetLocationImageUrlOk() (*string, bool)`

GetLocationImageUrlOk returns a tuple with the LocationImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLocationImageUrl

`func (o *RelayDTO) SetLocationImageUrl(v string)`

SetLocationImageUrl sets LocationImageUrl field to given value.

### HasLocationImageUrl

`func (o *RelayDTO) HasLocationImageUrl() bool`

HasLocationImageUrl returns a boolean if a field has been set.

### GetFuseBoxImageUrl

`func (o *RelayDTO) GetFuseBoxImageUrl() string`

GetFuseBoxImageUrl returns the FuseBoxImageUrl field if non-nil, zero value otherwise.

### GetFuseBoxImageUrlOk

`func (o *RelayDTO) GetFuseBoxImageUrlOk() (*string, bool)`

GetFuseBoxImageUrlOk returns a tuple with the FuseBoxImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFuseBoxImageUrl

`func (o *RelayDTO) SetFuseBoxImageUrl(v string)`

SetFuseBoxImageUrl sets FuseBoxImageUrl field to given value.

### HasFuseBoxImageUrl

`func (o *RelayDTO) HasFuseBoxImageUrl() bool`

HasFuseBoxImageUrl returns a boolean if a field has been set.

### GetCoordinates

`func (o *RelayDTO) GetCoordinates() CoordinatesDTO`

GetCoordinates returns the Coordinates field if non-nil, zero value otherwise.

### GetCoordinatesOk

`func (o *RelayDTO) GetCoordinatesOk() (*CoordinatesDTO, bool)`

GetCoordinatesOk returns a tuple with the Coordinates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCoordinates

`func (o *RelayDTO) SetCoordinates(v CoordinatesDTO)`

SetCoordinates sets Coordinates field to given value.

### HasCoordinates

`func (o *RelayDTO) HasCoordinates() bool`

HasCoordinates returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


