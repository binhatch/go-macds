# ReplacementIntervalPart

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to [**ReplacementNameReference**](ReplacementNameReference.md) |  | [optional] 
**GenArtNos** | Pointer to **[]int32** | a list of GenArt (Generic Article) numbers | [optional] 

## Methods

### NewReplacementIntervalPart

`func NewReplacementIntervalPart() *ReplacementIntervalPart`

NewReplacementIntervalPart instantiates a new ReplacementIntervalPart object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReplacementIntervalPartWithDefaults

`func NewReplacementIntervalPartWithDefaults() *ReplacementIntervalPart`

NewReplacementIntervalPartWithDefaults instantiates a new ReplacementIntervalPart object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ReplacementIntervalPart) GetName() ReplacementNameReference`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ReplacementIntervalPart) GetNameOk() (*ReplacementNameReference, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ReplacementIntervalPart) SetName(v ReplacementNameReference)`

SetName sets Name field to given value.

### HasName

`func (o *ReplacementIntervalPart) HasName() bool`

HasName returns a boolean if a field has been set.

### GetGenArtNos

`func (o *ReplacementIntervalPart) GetGenArtNos() []int32`

GetGenArtNos returns the GenArtNos field if non-nil, zero value otherwise.

### GetGenArtNosOk

`func (o *ReplacementIntervalPart) GetGenArtNosOk() (*[]int32, bool)`

GetGenArtNosOk returns a tuple with the GenArtNos field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGenArtNos

`func (o *ReplacementIntervalPart) SetGenArtNos(v []int32)`

SetGenArtNos sets GenArtNos field to given value.

### HasGenArtNos

`func (o *ReplacementIntervalPart) HasGenArtNos() bool`

HasGenArtNos returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


