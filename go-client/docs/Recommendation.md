# Recommendation

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Identifier | [optional] 
**Language** | Pointer to **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | [optional] 
**Text** | Pointer to **string** | Translation text | [optional] 
**Dashboard** | Pointer to **string** | The dashboard related text | [optional] 
**Driver** | Pointer to **string** | The driver related text | [optional] 

## Methods

### NewRecommendation

`func NewRecommendation() *Recommendation`

NewRecommendation instantiates a new Recommendation object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRecommendationWithDefaults

`func NewRecommendationWithDefaults() *Recommendation`

NewRecommendationWithDefaults instantiates a new Recommendation object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *Recommendation) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Recommendation) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Recommendation) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Recommendation) HasId() bool`

HasId returns a boolean if a field has been set.

### GetLanguage

`func (o *Recommendation) GetLanguage() string`

GetLanguage returns the Language field if non-nil, zero value otherwise.

### GetLanguageOk

`func (o *Recommendation) GetLanguageOk() (*string, bool)`

GetLanguageOk returns a tuple with the Language field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLanguage

`func (o *Recommendation) SetLanguage(v string)`

SetLanguage sets Language field to given value.

### HasLanguage

`func (o *Recommendation) HasLanguage() bool`

HasLanguage returns a boolean if a field has been set.

### GetText

`func (o *Recommendation) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *Recommendation) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *Recommendation) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *Recommendation) HasText() bool`

HasText returns a boolean if a field has been set.

### GetDashboard

`func (o *Recommendation) GetDashboard() string`

GetDashboard returns the Dashboard field if non-nil, zero value otherwise.

### GetDashboardOk

`func (o *Recommendation) GetDashboardOk() (*string, bool)`

GetDashboardOk returns a tuple with the Dashboard field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDashboard

`func (o *Recommendation) SetDashboard(v string)`

SetDashboard sets Dashboard field to given value.

### HasDashboard

`func (o *Recommendation) HasDashboard() bool`

HasDashboard returns a boolean if a field has been set.

### GetDriver

`func (o *Recommendation) GetDriver() string`

GetDriver returns the Driver field if non-nil, zero value otherwise.

### GetDriverOk

`func (o *Recommendation) GetDriverOk() (*string, bool)`

GetDriverOk returns a tuple with the Driver field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDriver

`func (o *Recommendation) SetDriver(v string)`

SetDriver sets Driver field to given value.

### HasDriver

`func (o *Recommendation) HasDriver() bool`

HasDriver returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


