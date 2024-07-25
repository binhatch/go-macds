# RepairTimesJobLink

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**JobLink** | Pointer to [**RepairTimesJobLinkDetails**](RepairTimesJobLinkDetails.md) |  | [optional] 
**PreliminaryLinks** | Pointer to [**[]RepairTimesJobLinkOther**](RepairTimesJobLinkOther.md) | works which are required to be done before the main work | [optional] 
**SubsequentLinks** | Pointer to [**[]RepairTimesJobLinkOther**](RepairTimesJobLinkOther.md) | works which need to be done after the main work | [optional] 
**NotIncludedLinks** | Pointer to [**[]RepairTimesJobLinkOther**](RepairTimesJobLinkOther.md) | Tasks that are not covered. | [optional] 

## Methods

### NewRepairTimesJobLink

`func NewRepairTimesJobLink() *RepairTimesJobLink`

NewRepairTimesJobLink instantiates a new RepairTimesJobLink object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRepairTimesJobLinkWithDefaults

`func NewRepairTimesJobLinkWithDefaults() *RepairTimesJobLink`

NewRepairTimesJobLinkWithDefaults instantiates a new RepairTimesJobLink object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetJobLink

`func (o *RepairTimesJobLink) GetJobLink() RepairTimesJobLinkDetails`

GetJobLink returns the JobLink field if non-nil, zero value otherwise.

### GetJobLinkOk

`func (o *RepairTimesJobLink) GetJobLinkOk() (*RepairTimesJobLinkDetails, bool)`

GetJobLinkOk returns a tuple with the JobLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobLink

`func (o *RepairTimesJobLink) SetJobLink(v RepairTimesJobLinkDetails)`

SetJobLink sets JobLink field to given value.

### HasJobLink

`func (o *RepairTimesJobLink) HasJobLink() bool`

HasJobLink returns a boolean if a field has been set.

### GetPreliminaryLinks

`func (o *RepairTimesJobLink) GetPreliminaryLinks() []RepairTimesJobLinkOther`

GetPreliminaryLinks returns the PreliminaryLinks field if non-nil, zero value otherwise.

### GetPreliminaryLinksOk

`func (o *RepairTimesJobLink) GetPreliminaryLinksOk() (*[]RepairTimesJobLinkOther, bool)`

GetPreliminaryLinksOk returns a tuple with the PreliminaryLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPreliminaryLinks

`func (o *RepairTimesJobLink) SetPreliminaryLinks(v []RepairTimesJobLinkOther)`

SetPreliminaryLinks sets PreliminaryLinks field to given value.

### HasPreliminaryLinks

`func (o *RepairTimesJobLink) HasPreliminaryLinks() bool`

HasPreliminaryLinks returns a boolean if a field has been set.

### GetSubsequentLinks

`func (o *RepairTimesJobLink) GetSubsequentLinks() []RepairTimesJobLinkOther`

GetSubsequentLinks returns the SubsequentLinks field if non-nil, zero value otherwise.

### GetSubsequentLinksOk

`func (o *RepairTimesJobLink) GetSubsequentLinksOk() (*[]RepairTimesJobLinkOther, bool)`

GetSubsequentLinksOk returns a tuple with the SubsequentLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubsequentLinks

`func (o *RepairTimesJobLink) SetSubsequentLinks(v []RepairTimesJobLinkOther)`

SetSubsequentLinks sets SubsequentLinks field to given value.

### HasSubsequentLinks

`func (o *RepairTimesJobLink) HasSubsequentLinks() bool`

HasSubsequentLinks returns a boolean if a field has been set.

### GetNotIncludedLinks

`func (o *RepairTimesJobLink) GetNotIncludedLinks() []RepairTimesJobLinkOther`

GetNotIncludedLinks returns the NotIncludedLinks field if non-nil, zero value otherwise.

### GetNotIncludedLinksOk

`func (o *RepairTimesJobLink) GetNotIncludedLinksOk() (*[]RepairTimesJobLinkOther, bool)`

GetNotIncludedLinksOk returns a tuple with the NotIncludedLinks field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotIncludedLinks

`func (o *RepairTimesJobLink) SetNotIncludedLinks(v []RepairTimesJobLinkOther)`

SetNotIncludedLinks sets NotIncludedLinks field to given value.

### HasNotIncludedLinks

`func (o *RepairTimesJobLink) HasNotIncludedLinks() bool`

HasNotIncludedLinks returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


