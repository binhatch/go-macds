# ComponentDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ShortName** | Pointer to **string** | Short Name | [optional] 
**ComponentId** | Pointer to **int32** | Component Id | [optional] 
**Name** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**ImagePlacementUrl** | Pointer to **string** | Image Placement URL | [optional] 
**ImageUrl** | Pointer to **string** | Image URL | [optional] 
**HintName** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**GenericArticleNos** | Pointer to **[]int32** | Generic Article Numbers | [optional] 
**Xabs** | Pointer to **string** | X Absolute | [optional] 
**Yabs** | Pointer to **string** | Y Absolute | [optional] 

## Methods

### NewComponentDTO

`func NewComponentDTO() *ComponentDTO`

NewComponentDTO instantiates a new ComponentDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComponentDTOWithDefaults

`func NewComponentDTOWithDefaults() *ComponentDTO`

NewComponentDTOWithDefaults instantiates a new ComponentDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetShortName

`func (o *ComponentDTO) GetShortName() string`

GetShortName returns the ShortName field if non-nil, zero value otherwise.

### GetShortNameOk

`func (o *ComponentDTO) GetShortNameOk() (*string, bool)`

GetShortNameOk returns a tuple with the ShortName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetShortName

`func (o *ComponentDTO) SetShortName(v string)`

SetShortName sets ShortName field to given value.

### HasShortName

`func (o *ComponentDTO) HasShortName() bool`

HasShortName returns a boolean if a field has been set.

### GetComponentId

`func (o *ComponentDTO) GetComponentId() int32`

GetComponentId returns the ComponentId field if non-nil, zero value otherwise.

### GetComponentIdOk

`func (o *ComponentDTO) GetComponentIdOk() (*int32, bool)`

GetComponentIdOk returns a tuple with the ComponentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentId

`func (o *ComponentDTO) SetComponentId(v int32)`

SetComponentId sets ComponentId field to given value.

### HasComponentId

`func (o *ComponentDTO) HasComponentId() bool`

HasComponentId returns a boolean if a field has been set.

### GetName

`func (o *ComponentDTO) GetName() Texts`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ComponentDTO) GetNameOk() (*Texts, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ComponentDTO) SetName(v Texts)`

SetName sets Name field to given value.

### HasName

`func (o *ComponentDTO) HasName() bool`

HasName returns a boolean if a field has been set.

### GetImagePlacementUrl

`func (o *ComponentDTO) GetImagePlacementUrl() string`

GetImagePlacementUrl returns the ImagePlacementUrl field if non-nil, zero value otherwise.

### GetImagePlacementUrlOk

`func (o *ComponentDTO) GetImagePlacementUrlOk() (*string, bool)`

GetImagePlacementUrlOk returns a tuple with the ImagePlacementUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePlacementUrl

`func (o *ComponentDTO) SetImagePlacementUrl(v string)`

SetImagePlacementUrl sets ImagePlacementUrl field to given value.

### HasImagePlacementUrl

`func (o *ComponentDTO) HasImagePlacementUrl() bool`

HasImagePlacementUrl returns a boolean if a field has been set.

### GetImageUrl

`func (o *ComponentDTO) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *ComponentDTO) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *ComponentDTO) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *ComponentDTO) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### GetHintName

`func (o *ComponentDTO) GetHintName() Texts`

GetHintName returns the HintName field if non-nil, zero value otherwise.

### GetHintNameOk

`func (o *ComponentDTO) GetHintNameOk() (*Texts, bool)`

GetHintNameOk returns a tuple with the HintName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHintName

`func (o *ComponentDTO) SetHintName(v Texts)`

SetHintName sets HintName field to given value.

### HasHintName

`func (o *ComponentDTO) HasHintName() bool`

HasHintName returns a boolean if a field has been set.

### GetGenericArticleNos

`func (o *ComponentDTO) GetGenericArticleNos() []int32`

GetGenericArticleNos returns the GenericArticleNos field if non-nil, zero value otherwise.

### GetGenericArticleNosOk

`func (o *ComponentDTO) GetGenericArticleNosOk() (*[]int32, bool)`

GetGenericArticleNosOk returns a tuple with the GenericArticleNos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenericArticleNos

`func (o *ComponentDTO) SetGenericArticleNos(v []int32)`

SetGenericArticleNos sets GenericArticleNos field to given value.

### HasGenericArticleNos

`func (o *ComponentDTO) HasGenericArticleNos() bool`

HasGenericArticleNos returns a boolean if a field has been set.

### GetXabs

`func (o *ComponentDTO) GetXabs() string`

GetXabs returns the Xabs field if non-nil, zero value otherwise.

### GetXabsOk

`func (o *ComponentDTO) GetXabsOk() (*string, bool)`

GetXabsOk returns a tuple with the Xabs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetXabs

`func (o *ComponentDTO) SetXabs(v string)`

SetXabs sets Xabs field to given value.

### HasXabs

`func (o *ComponentDTO) HasXabs() bool`

HasXabs returns a boolean if a field has been set.

### GetYabs

`func (o *ComponentDTO) GetYabs() string`

GetYabs returns the Yabs field if non-nil, zero value otherwise.

### GetYabsOk

`func (o *ComponentDTO) GetYabsOk() (*string, bool)`

GetYabsOk returns a tuple with the Yabs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYabs

`func (o *ComponentDTO) SetYabs(v string)`

SetYabs sets Yabs field to given value.

### HasYabs

`func (o *ComponentDTO) HasYabs() bool`

HasYabs returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


