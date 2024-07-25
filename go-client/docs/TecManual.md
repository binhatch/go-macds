# TecManual

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ManualId** | Pointer to **int32** | Manual Id | [optional] 
**ManualMainTitle** | Pointer to **string** | Manual Main Title | [optional] 
**ManualSubTitle** | Pointer to **string** | Manual Sub Title | [optional] 
**QualifierCollectionId** | Pointer to **int32** | Qualifier Collection Id | [optional] 
**QualifierCollectionText** | Pointer to **string** | Qualifier Collection Text | [optional] 
**ContentSections** | Pointer to [**[]ContentSection**](ContentSection.md) | List of Content Sections | [optional] 
**Images** | Pointer to [**[]ManualImage**](ManualImage.md) | List of Images | [optional] 

## Methods

### NewTecManual

`func NewTecManual() *TecManual`

NewTecManual instantiates a new TecManual object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTecManualWithDefaults

`func NewTecManualWithDefaults() *TecManual`

NewTecManualWithDefaults instantiates a new TecManual object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetManualId

`func (o *TecManual) GetManualId() int32`

GetManualId returns the ManualId field if non-nil, zero value otherwise.

### GetManualIdOk

`func (o *TecManual) GetManualIdOk() (*int32, bool)`

GetManualIdOk returns a tuple with the ManualId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManualId

`func (o *TecManual) SetManualId(v int32)`

SetManualId sets ManualId field to given value.

### HasManualId

`func (o *TecManual) HasManualId() bool`

HasManualId returns a boolean if a field has been set.

### GetManualMainTitle

`func (o *TecManual) GetManualMainTitle() string`

GetManualMainTitle returns the ManualMainTitle field if non-nil, zero value otherwise.

### GetManualMainTitleOk

`func (o *TecManual) GetManualMainTitleOk() (*string, bool)`

GetManualMainTitleOk returns a tuple with the ManualMainTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManualMainTitle

`func (o *TecManual) SetManualMainTitle(v string)`

SetManualMainTitle sets ManualMainTitle field to given value.

### HasManualMainTitle

`func (o *TecManual) HasManualMainTitle() bool`

HasManualMainTitle returns a boolean if a field has been set.

### GetManualSubTitle

`func (o *TecManual) GetManualSubTitle() string`

GetManualSubTitle returns the ManualSubTitle field if non-nil, zero value otherwise.

### GetManualSubTitleOk

`func (o *TecManual) GetManualSubTitleOk() (*string, bool)`

GetManualSubTitleOk returns a tuple with the ManualSubTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManualSubTitle

`func (o *TecManual) SetManualSubTitle(v string)`

SetManualSubTitle sets ManualSubTitle field to given value.

### HasManualSubTitle

`func (o *TecManual) HasManualSubTitle() bool`

HasManualSubTitle returns a boolean if a field has been set.

### GetQualifierCollectionId

`func (o *TecManual) GetQualifierCollectionId() int32`

GetQualifierCollectionId returns the QualifierCollectionId field if non-nil, zero value otherwise.

### GetQualifierCollectionIdOk

`func (o *TecManual) GetQualifierCollectionIdOk() (*int32, bool)`

GetQualifierCollectionIdOk returns a tuple with the QualifierCollectionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQualifierCollectionId

`func (o *TecManual) SetQualifierCollectionId(v int32)`

SetQualifierCollectionId sets QualifierCollectionId field to given value.

### HasQualifierCollectionId

`func (o *TecManual) HasQualifierCollectionId() bool`

HasQualifierCollectionId returns a boolean if a field has been set.

### GetQualifierCollectionText

`func (o *TecManual) GetQualifierCollectionText() string`

GetQualifierCollectionText returns the QualifierCollectionText field if non-nil, zero value otherwise.

### GetQualifierCollectionTextOk

`func (o *TecManual) GetQualifierCollectionTextOk() (*string, bool)`

GetQualifierCollectionTextOk returns a tuple with the QualifierCollectionText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQualifierCollectionText

`func (o *TecManual) SetQualifierCollectionText(v string)`

SetQualifierCollectionText sets QualifierCollectionText field to given value.

### HasQualifierCollectionText

`func (o *TecManual) HasQualifierCollectionText() bool`

HasQualifierCollectionText returns a boolean if a field has been set.

### GetContentSections

`func (o *TecManual) GetContentSections() []ContentSection`

GetContentSections returns the ContentSections field if non-nil, zero value otherwise.

### GetContentSectionsOk

`func (o *TecManual) GetContentSectionsOk() (*[]ContentSection, bool)`

GetContentSectionsOk returns a tuple with the ContentSections field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentSections

`func (o *TecManual) SetContentSections(v []ContentSection)`

SetContentSections sets ContentSections field to given value.

### HasContentSections

`func (o *TecManual) HasContentSections() bool`

HasContentSections returns a boolean if a field has been set.

### GetImages

`func (o *TecManual) GetImages() []ManualImage`

GetImages returns the Images field if non-nil, zero value otherwise.

### GetImagesOk

`func (o *TecManual) GetImagesOk() (*[]ManualImage, bool)`

GetImagesOk returns a tuple with the Images field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImages

`func (o *TecManual) SetImages(v []ManualImage)`

SetImages sets Images field to given value.

### HasImages

`func (o *TecManual) HasImages() bool`

HasImages returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


