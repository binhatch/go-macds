# Availability

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ComponentLocation** | Pointer to **bool** | Indicates if dataType component location is available | [optional] 
**FuseBoxLocation** | Pointer to **bool** | Indicates if dataType fuse box location is available | [optional] 
**RepairTimes** | Pointer to **bool** | Indicates if dataType repair times is available (will be true regardless of the particular modelId, if it&#39;s available for the specified kType) | [optional] 
**TechData** | Pointer to **bool** | Indicates if dataType tech data is available | [optional] 
**ServiceSchedules** | Pointer to **bool** | Indicates if dataType service schedules is available | [optional] 
**WiringDiagrams** | Pointer to **bool** | Indicates if dataType wiring diagrams is available | [optional] 
**RecallCampaigns** | Pointer to **bool** | Indicates if dataType recall campaigns is available | [optional] 
**RepairInstructions** | Pointer to **bool** | Indicates if dataType repair instructions is available | [optional] 
**ManufacturerCampaigns** | Pointer to **bool** | Indicates if dataType manufacturer campaigns is available | [optional] 

## Methods

### NewAvailability

`func NewAvailability() *Availability`

NewAvailability instantiates a new Availability object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAvailabilityWithDefaults

`func NewAvailabilityWithDefaults() *Availability`

NewAvailabilityWithDefaults instantiates a new Availability object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetComponentLocation

`func (o *Availability) GetComponentLocation() bool`

GetComponentLocation returns the ComponentLocation field if non-nil, zero value otherwise.

### GetComponentLocationOk

`func (o *Availability) GetComponentLocationOk() (*bool, bool)`

GetComponentLocationOk returns a tuple with the ComponentLocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentLocation

`func (o *Availability) SetComponentLocation(v bool)`

SetComponentLocation sets ComponentLocation field to given value.

### HasComponentLocation

`func (o *Availability) HasComponentLocation() bool`

HasComponentLocation returns a boolean if a field has been set.

### GetFuseBoxLocation

`func (o *Availability) GetFuseBoxLocation() bool`

GetFuseBoxLocation returns the FuseBoxLocation field if non-nil, zero value otherwise.

### GetFuseBoxLocationOk

`func (o *Availability) GetFuseBoxLocationOk() (*bool, bool)`

GetFuseBoxLocationOk returns a tuple with the FuseBoxLocation field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFuseBoxLocation

`func (o *Availability) SetFuseBoxLocation(v bool)`

SetFuseBoxLocation sets FuseBoxLocation field to given value.

### HasFuseBoxLocation

`func (o *Availability) HasFuseBoxLocation() bool`

HasFuseBoxLocation returns a boolean if a field has been set.

### GetRepairTimes

`func (o *Availability) GetRepairTimes() bool`

GetRepairTimes returns the RepairTimes field if non-nil, zero value otherwise.

### GetRepairTimesOk

`func (o *Availability) GetRepairTimesOk() (*bool, bool)`

GetRepairTimesOk returns a tuple with the RepairTimes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepairTimes

`func (o *Availability) SetRepairTimes(v bool)`

SetRepairTimes sets RepairTimes field to given value.

### HasRepairTimes

`func (o *Availability) HasRepairTimes() bool`

HasRepairTimes returns a boolean if a field has been set.

### GetTechData

`func (o *Availability) GetTechData() bool`

GetTechData returns the TechData field if non-nil, zero value otherwise.

### GetTechDataOk

`func (o *Availability) GetTechDataOk() (*bool, bool)`

GetTechDataOk returns a tuple with the TechData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTechData

`func (o *Availability) SetTechData(v bool)`

SetTechData sets TechData field to given value.

### HasTechData

`func (o *Availability) HasTechData() bool`

HasTechData returns a boolean if a field has been set.

### GetServiceSchedules

`func (o *Availability) GetServiceSchedules() bool`

GetServiceSchedules returns the ServiceSchedules field if non-nil, zero value otherwise.

### GetServiceSchedulesOk

`func (o *Availability) GetServiceSchedulesOk() (*bool, bool)`

GetServiceSchedulesOk returns a tuple with the ServiceSchedules field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServiceSchedules

`func (o *Availability) SetServiceSchedules(v bool)`

SetServiceSchedules sets ServiceSchedules field to given value.

### HasServiceSchedules

`func (o *Availability) HasServiceSchedules() bool`

HasServiceSchedules returns a boolean if a field has been set.

### GetWiringDiagrams

`func (o *Availability) GetWiringDiagrams() bool`

GetWiringDiagrams returns the WiringDiagrams field if non-nil, zero value otherwise.

### GetWiringDiagramsOk

`func (o *Availability) GetWiringDiagramsOk() (*bool, bool)`

GetWiringDiagramsOk returns a tuple with the WiringDiagrams field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWiringDiagrams

`func (o *Availability) SetWiringDiagrams(v bool)`

SetWiringDiagrams sets WiringDiagrams field to given value.

### HasWiringDiagrams

`func (o *Availability) HasWiringDiagrams() bool`

HasWiringDiagrams returns a boolean if a field has been set.

### GetRecallCampaigns

`func (o *Availability) GetRecallCampaigns() bool`

GetRecallCampaigns returns the RecallCampaigns field if non-nil, zero value otherwise.

### GetRecallCampaignsOk

`func (o *Availability) GetRecallCampaignsOk() (*bool, bool)`

GetRecallCampaignsOk returns a tuple with the RecallCampaigns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecallCampaigns

`func (o *Availability) SetRecallCampaigns(v bool)`

SetRecallCampaigns sets RecallCampaigns field to given value.

### HasRecallCampaigns

`func (o *Availability) HasRecallCampaigns() bool`

HasRecallCampaigns returns a boolean if a field has been set.

### GetRepairInstructions

`func (o *Availability) GetRepairInstructions() bool`

GetRepairInstructions returns the RepairInstructions field if non-nil, zero value otherwise.

### GetRepairInstructionsOk

`func (o *Availability) GetRepairInstructionsOk() (*bool, bool)`

GetRepairInstructionsOk returns a tuple with the RepairInstructions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRepairInstructions

`func (o *Availability) SetRepairInstructions(v bool)`

SetRepairInstructions sets RepairInstructions field to given value.

### HasRepairInstructions

`func (o *Availability) HasRepairInstructions() bool`

HasRepairInstructions returns a boolean if a field has been set.

### GetManufacturerCampaigns

`func (o *Availability) GetManufacturerCampaigns() bool`

GetManufacturerCampaigns returns the ManufacturerCampaigns field if non-nil, zero value otherwise.

### GetManufacturerCampaignsOk

`func (o *Availability) GetManufacturerCampaignsOk() (*bool, bool)`

GetManufacturerCampaignsOk returns a tuple with the ManufacturerCampaigns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetManufacturerCampaigns

`func (o *Availability) SetManufacturerCampaigns(v bool)`

SetManufacturerCampaigns sets ManufacturerCampaigns field to given value.

### HasManufacturerCampaigns

`func (o *Availability) HasManufacturerCampaigns() bool`

HasManufacturerCampaigns returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


