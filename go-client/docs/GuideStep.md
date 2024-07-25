# GuideStep

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int64** | Id | [optional] 
**Type** | Pointer to **string** | Type | [optional] 
**Order** | Pointer to **int64** | Order | [optional] 
**Title** | Pointer to [**TitleText**](TitleText.md) |  | [optional] 
**Icon** | Pointer to [**Icon**](Icon.md) |  | [optional] 
**Lines** | Pointer to [**[]Line**](Line.md) | Lines | [optional] 
**Images** | Pointer to [**[]OrderedImage**](OrderedImage.md) | Images | [optional] 

## Methods

### NewGuideStep

`func NewGuideStep() *GuideStep`

NewGuideStep instantiates a new GuideStep object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGuideStepWithDefaults

`func NewGuideStepWithDefaults() *GuideStep`

NewGuideStepWithDefaults instantiates a new GuideStep object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GuideStep) GetId() int64`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GuideStep) GetIdOk() (*int64, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GuideStep) SetId(v int64)`

SetId sets Id field to given value.

### HasId

`func (o *GuideStep) HasId() bool`

HasId returns a boolean if a field has been set.

### GetType

`func (o *GuideStep) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *GuideStep) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *GuideStep) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *GuideStep) HasType() bool`

HasType returns a boolean if a field has been set.

### GetOrder

`func (o *GuideStep) GetOrder() int64`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *GuideStep) GetOrderOk() (*int64, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *GuideStep) SetOrder(v int64)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *GuideStep) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetTitle

`func (o *GuideStep) GetTitle() TitleText`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *GuideStep) GetTitleOk() (*TitleText, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *GuideStep) SetTitle(v TitleText)`

SetTitle sets Title field to given value.

### HasTitle

`func (o *GuideStep) HasTitle() bool`

HasTitle returns a boolean if a field has been set.

### GetIcon

`func (o *GuideStep) GetIcon() Icon`

GetIcon returns the Icon field if non-nil, zero value otherwise.

### GetIconOk

`func (o *GuideStep) GetIconOk() (*Icon, bool)`

GetIconOk returns a tuple with the Icon field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIcon

`func (o *GuideStep) SetIcon(v Icon)`

SetIcon sets Icon field to given value.

### HasIcon

`func (o *GuideStep) HasIcon() bool`

HasIcon returns a boolean if a field has been set.

### GetLines

`func (o *GuideStep) GetLines() []Line`

GetLines returns the Lines field if non-nil, zero value otherwise.

### GetLinesOk

`func (o *GuideStep) GetLinesOk() (*[]Line, bool)`

GetLinesOk returns a tuple with the Lines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLines

`func (o *GuideStep) SetLines(v []Line)`

SetLines sets Lines field to given value.

### HasLines

`func (o *GuideStep) HasLines() bool`

HasLines returns a boolean if a field has been set.

### GetImages

`func (o *GuideStep) GetImages() []OrderedImage`

GetImages returns the Images field if non-nil, zero value otherwise.

### GetImagesOk

`func (o *GuideStep) GetImagesOk() (*[]OrderedImage, bool)`

GetImagesOk returns a tuple with the Images field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImages

`func (o *GuideStep) SetImages(v []OrderedImage)`

SetImages sets Images field to given value.

### HasImages

`func (o *GuideStep) HasImages() bool`

HasImages returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


