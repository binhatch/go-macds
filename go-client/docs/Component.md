# Component

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | ID of the component | [optional] 
**Name** | Pointer to **string** | Name of the component | [optional] 
**Language** | Pointer to **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | [optional] 
**Prob** | Pointer to **int32** | Probability that this component is affected, based on historic repair evidence | [optional] 
**RelatedRmi** | Pointer to [**RelatedRmi**](RelatedRmi.md) |  | [optional] 
**GenericArticleNumbers** | Pointer to **[]int32** | The list of generic article numbers | [optional] 

## Methods

### NewComponent

`func NewComponent() *Component`

NewComponent instantiates a new Component object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComponentWithDefaults

`func NewComponentWithDefaults() *Component`

NewComponentWithDefaults instantiates a new Component object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Component) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Component) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Component) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *Component) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *Component) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Component) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Component) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *Component) HasName() bool`

HasName returns a boolean if a field has been set.

### GetLanguage

`func (o *Component) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *Component) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *Component) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *Component) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetProb

`func (o *Component) GetProb() int32`

GetProb returns the Prob field if non-nil, zero value otherwise.

### GetProbOk

`func (o *Component) GetProbOk() (*int32, bool)`

GetProbOk returns a tuple with the Prob field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProb

`func (o *Component) SetProb(v int32)`

SetProb sets Prob field to given value.

### HasProb

`func (o *Component) HasProb() bool`

HasProb returns a boolean if a field has been set.

### GetRelatedRmi

`func (o *Component) GetRelatedRmi() RelatedRmi`

GetRelatedRmi returns the RelatedRmi field if non-nil, zero value otherwise.

### GetRelatedRmiOk

`func (o *Component) GetRelatedRmiOk() (*RelatedRmi, bool)`

GetRelatedRmiOk returns a tuple with the RelatedRmi field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRelatedRmi

`func (o *Component) SetRelatedRmi(v RelatedRmi)`

SetRelatedRmi sets RelatedRmi field to given value.

### HasRelatedRmi

`func (o *Component) HasRelatedRmi() bool`

HasRelatedRmi returns a boolean if a field has been set.

### GetGenericArticleNumbers

`func (o *Component) GetGenericArticleNumbers() []int32`

GetGenericArticleNumbers returns the GenericArticleNumbers field if non-nil, zero value otherwise.

### GetGenericArticleNumbersOk

`func (o *Component) GetGenericArticleNumbersOk() (*[]int32, bool)`

GetGenericArticleNumbersOk returns a tuple with the GenericArticleNumbers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenericArticleNumbers

`func (o *Component) SetGenericArticleNumbers(v []int32)`

SetGenericArticleNumbers sets GenericArticleNumbers field to given value.

### HasGenericArticleNumbers

`func (o *Component) HasGenericArticleNumbers() bool`

HasGenericArticleNumbers returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


