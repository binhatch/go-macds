# ComponentDataV4ResponseDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ktypeno** | Pointer to **int32** | KType number | [optional] 
**SystemIdent** | Pointer to **string** | System Ident | [optional] 
**SubSystem** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**ComponentName** | Pointer to [**IdTexts**](IdTexts.md) |  | [optional] 
**IdImageECU** | Pointer to **int32** | ID ECU Image | [optional] 
**PinFrom** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**PinTo** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**ValueFrom** | Pointer to [**ValueDTO**](ValueDTO.md) |  | [optional] 
**ValueTo** | Pointer to [**ValueDTO**](ValueDTO.md) |  | [optional] 
**PinMeasurementFunction** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**PinMeasurementType** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**VehicleState** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**MeasurementCondition** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**ImagePinFromX1** | Pointer to **int32** | Image Pin From X1 | [optional] 
**ImagePinFromY1** | Pointer to **int32** | Image Pin From Y1 | [optional] 
**ImagePinFromWidth** | Pointer to **int32** | Image Pin From Width | [optional] 
**ImagePinFromHeight** | Pointer to **int32** | Image Pin From Heught | [optional] 
**ImagePinToX** | Pointer to **int32** | Image Pin To X | [optional] 
**ImagePinToY** | Pointer to **int32** | Image Pin To Y | [optional] 
**ImagePinToWidth** | Pointer to **int32** | Image Pin To Width | [optional] 
**ImagePinToHeight** | Pointer to **int32** | Image Pin To Height | [optional] 
**IdScopeImage** | Pointer to **int32** | Id Scope Imag | [optional] 
**DivisionXValue** | Pointer to **float64** | Division X Value | [optional] 
**DivisionXUnit** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**DivisionYValue** | Pointer to **float64** | Division Y Value | [optional] 
**DivisionYUnit** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**OffsetYAxis** | Pointer to **int32** | Offset Y Axis | [optional] 
**ScopeSettingsFunctionType** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**PinScopeCouplingType** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**ComponentPinFrom** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**ComponentPinTo** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**CableIdentifierFrom** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**CableIdentifierTo** | Pointer to [**Texts**](Texts.md) |  | [optional] 
**YearFrom** | Pointer to **string** | Year From | [optional] 
**YearTo** | Pointer to **string** | Year To | [optional] 
**EngineCode** | Pointer to **string** | Engine Code | [optional] 

## Methods

### NewComponentDataV4ResponseDTO

`func NewComponentDataV4ResponseDTO() *ComponentDataV4ResponseDTO`

NewComponentDataV4ResponseDTO instantiates a new ComponentDataV4ResponseDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComponentDataV4ResponseDTOWithDefaults

`func NewComponentDataV4ResponseDTOWithDefaults() *ComponentDataV4ResponseDTO`

NewComponentDataV4ResponseDTOWithDefaults instantiates a new ComponentDataV4ResponseDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKtypeno

`func (o *ComponentDataV4ResponseDTO) GetKtypeno() int32`

GetKtypeno returns the Ktypeno field if non-nil, zero value otherwise.

### GetKtypenoOk

`func (o *ComponentDataV4ResponseDTO) GetKtypenoOk() (*int32, bool)`

GetKtypenoOk returns a tuple with the Ktypeno field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKtypeno

`func (o *ComponentDataV4ResponseDTO) SetKtypeno(v int32)`

SetKtypeno sets Ktypeno field to given value.

### HasKtypeno

`func (o *ComponentDataV4ResponseDTO) HasKtypeno() bool`

HasKtypeno returns a boolean if a field has been set.

### GetSystemIdent

`func (o *ComponentDataV4ResponseDTO) GetSystemIdent() string`

GetSystemIdent returns the SystemIdent field if non-nil, zero value otherwise.

### GetSystemIdentOk

`func (o *ComponentDataV4ResponseDTO) GetSystemIdentOk() (*string, bool)`

GetSystemIdentOk returns a tuple with the SystemIdent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystemIdent

`func (o *ComponentDataV4ResponseDTO) SetSystemIdent(v string)`

SetSystemIdent sets SystemIdent field to given value.

### HasSystemIdent

`func (o *ComponentDataV4ResponseDTO) HasSystemIdent() bool`

HasSystemIdent returns a boolean if a field has been set.

### GetSubSystem

`func (o *ComponentDataV4ResponseDTO) GetSubSystem() Texts`

GetSubSystem returns the SubSystem field if non-nil, zero value otherwise.

### GetSubSystemOk

`func (o *ComponentDataV4ResponseDTO) GetSubSystemOk() (*Texts, bool)`

GetSubSystemOk returns a tuple with the SubSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubSystem

`func (o *ComponentDataV4ResponseDTO) SetSubSystem(v Texts)`

SetSubSystem sets SubSystem field to given value.

### HasSubSystem

`func (o *ComponentDataV4ResponseDTO) HasSubSystem() bool`

HasSubSystem returns a boolean if a field has been set.

### GetComponentName

`func (o *ComponentDataV4ResponseDTO) GetComponentName() IdTexts`

GetComponentName returns the ComponentName field if non-nil, zero value otherwise.

### GetComponentNameOk

`func (o *ComponentDataV4ResponseDTO) GetComponentNameOk() (*IdTexts, bool)`

GetComponentNameOk returns a tuple with the ComponentName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentName

`func (o *ComponentDataV4ResponseDTO) SetComponentName(v IdTexts)`

SetComponentName sets ComponentName field to given value.

### HasComponentName

`func (o *ComponentDataV4ResponseDTO) HasComponentName() bool`

HasComponentName returns a boolean if a field has been set.

### GetIdImageECU

`func (o *ComponentDataV4ResponseDTO) GetIdImageECU() int32`

GetIdImageECU returns the IdImageECU field if non-nil, zero value otherwise.

### GetIdImageECUOk

`func (o *ComponentDataV4ResponseDTO) GetIdImageECUOk() (*int32, bool)`

GetIdImageECUOk returns a tuple with the IdImageECU field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdImageECU

`func (o *ComponentDataV4ResponseDTO) SetIdImageECU(v int32)`

SetIdImageECU sets IdImageECU field to given value.

### HasIdImageECU

`func (o *ComponentDataV4ResponseDTO) HasIdImageECU() bool`

HasIdImageECU returns a boolean if a field has been set.

### GetPinFrom

`func (o *ComponentDataV4ResponseDTO) GetPinFrom() Texts`

GetPinFrom returns the PinFrom field if non-nil, zero value otherwise.

### GetPinFromOk

`func (o *ComponentDataV4ResponseDTO) GetPinFromOk() (*Texts, bool)`

GetPinFromOk returns a tuple with the PinFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinFrom

`func (o *ComponentDataV4ResponseDTO) SetPinFrom(v Texts)`

SetPinFrom sets PinFrom field to given value.

### HasPinFrom

`func (o *ComponentDataV4ResponseDTO) HasPinFrom() bool`

HasPinFrom returns a boolean if a field has been set.

### GetPinTo

`func (o *ComponentDataV4ResponseDTO) GetPinTo() Texts`

GetPinTo returns the PinTo field if non-nil, zero value otherwise.

### GetPinToOk

`func (o *ComponentDataV4ResponseDTO) GetPinToOk() (*Texts, bool)`

GetPinToOk returns a tuple with the PinTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinTo

`func (o *ComponentDataV4ResponseDTO) SetPinTo(v Texts)`

SetPinTo sets PinTo field to given value.

### HasPinTo

`func (o *ComponentDataV4ResponseDTO) HasPinTo() bool`

HasPinTo returns a boolean if a field has been set.

### GetValueFrom

`func (o *ComponentDataV4ResponseDTO) GetValueFrom() ValueDTO`

GetValueFrom returns the ValueFrom field if non-nil, zero value otherwise.

### GetValueFromOk

`func (o *ComponentDataV4ResponseDTO) GetValueFromOk() (*ValueDTO, bool)`

GetValueFromOk returns a tuple with the ValueFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValueFrom

`func (o *ComponentDataV4ResponseDTO) SetValueFrom(v ValueDTO)`

SetValueFrom sets ValueFrom field to given value.

### HasValueFrom

`func (o *ComponentDataV4ResponseDTO) HasValueFrom() bool`

HasValueFrom returns a boolean if a field has been set.

### GetValueTo

`func (o *ComponentDataV4ResponseDTO) GetValueTo() ValueDTO`

GetValueTo returns the ValueTo field if non-nil, zero value otherwise.

### GetValueToOk

`func (o *ComponentDataV4ResponseDTO) GetValueToOk() (*ValueDTO, bool)`

GetValueToOk returns a tuple with the ValueTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValueTo

`func (o *ComponentDataV4ResponseDTO) SetValueTo(v ValueDTO)`

SetValueTo sets ValueTo field to given value.

### HasValueTo

`func (o *ComponentDataV4ResponseDTO) HasValueTo() bool`

HasValueTo returns a boolean if a field has been set.

### GetPinMeasurementFunction

`func (o *ComponentDataV4ResponseDTO) GetPinMeasurementFunction() Texts`

GetPinMeasurementFunction returns the PinMeasurementFunction field if non-nil, zero value otherwise.

### GetPinMeasurementFunctionOk

`func (o *ComponentDataV4ResponseDTO) GetPinMeasurementFunctionOk() (*Texts, bool)`

GetPinMeasurementFunctionOk returns a tuple with the PinMeasurementFunction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinMeasurementFunction

`func (o *ComponentDataV4ResponseDTO) SetPinMeasurementFunction(v Texts)`

SetPinMeasurementFunction sets PinMeasurementFunction field to given value.

### HasPinMeasurementFunction

`func (o *ComponentDataV4ResponseDTO) HasPinMeasurementFunction() bool`

HasPinMeasurementFunction returns a boolean if a field has been set.

### GetPinMeasurementType

`func (o *ComponentDataV4ResponseDTO) GetPinMeasurementType() Texts`

GetPinMeasurementType returns the PinMeasurementType field if non-nil, zero value otherwise.

### GetPinMeasurementTypeOk

`func (o *ComponentDataV4ResponseDTO) GetPinMeasurementTypeOk() (*Texts, bool)`

GetPinMeasurementTypeOk returns a tuple with the PinMeasurementType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinMeasurementType

`func (o *ComponentDataV4ResponseDTO) SetPinMeasurementType(v Texts)`

SetPinMeasurementType sets PinMeasurementType field to given value.

### HasPinMeasurementType

`func (o *ComponentDataV4ResponseDTO) HasPinMeasurementType() bool`

HasPinMeasurementType returns a boolean if a field has been set.

### GetVehicleState

`func (o *ComponentDataV4ResponseDTO) GetVehicleState() Texts`

GetVehicleState returns the VehicleState field if non-nil, zero value otherwise.

### GetVehicleStateOk

`func (o *ComponentDataV4ResponseDTO) GetVehicleStateOk() (*Texts, bool)`

GetVehicleStateOk returns a tuple with the VehicleState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVehicleState

`func (o *ComponentDataV4ResponseDTO) SetVehicleState(v Texts)`

SetVehicleState sets VehicleState field to given value.

### HasVehicleState

`func (o *ComponentDataV4ResponseDTO) HasVehicleState() bool`

HasVehicleState returns a boolean if a field has been set.

### GetMeasurementCondition

`func (o *ComponentDataV4ResponseDTO) GetMeasurementCondition() Texts`

GetMeasurementCondition returns the MeasurementCondition field if non-nil, zero value otherwise.

### GetMeasurementConditionOk

`func (o *ComponentDataV4ResponseDTO) GetMeasurementConditionOk() (*Texts, bool)`

GetMeasurementConditionOk returns a tuple with the MeasurementCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeasurementCondition

`func (o *ComponentDataV4ResponseDTO) SetMeasurementCondition(v Texts)`

SetMeasurementCondition sets MeasurementCondition field to given value.

### HasMeasurementCondition

`func (o *ComponentDataV4ResponseDTO) HasMeasurementCondition() bool`

HasMeasurementCondition returns a boolean if a field has been set.

### GetImagePinFromX1

`func (o *ComponentDataV4ResponseDTO) GetImagePinFromX1() int32`

GetImagePinFromX1 returns the ImagePinFromX1 field if non-nil, zero value otherwise.

### GetImagePinFromX1Ok

`func (o *ComponentDataV4ResponseDTO) GetImagePinFromX1Ok() (*int32, bool)`

GetImagePinFromX1Ok returns a tuple with the ImagePinFromX1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePinFromX1

`func (o *ComponentDataV4ResponseDTO) SetImagePinFromX1(v int32)`

SetImagePinFromX1 sets ImagePinFromX1 field to given value.

### HasImagePinFromX1

`func (o *ComponentDataV4ResponseDTO) HasImagePinFromX1() bool`

HasImagePinFromX1 returns a boolean if a field has been set.

### GetImagePinFromY1

`func (o *ComponentDataV4ResponseDTO) GetImagePinFromY1() int32`

GetImagePinFromY1 returns the ImagePinFromY1 field if non-nil, zero value otherwise.

### GetImagePinFromY1Ok

`func (o *ComponentDataV4ResponseDTO) GetImagePinFromY1Ok() (*int32, bool)`

GetImagePinFromY1Ok returns a tuple with the ImagePinFromY1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePinFromY1

`func (o *ComponentDataV4ResponseDTO) SetImagePinFromY1(v int32)`

SetImagePinFromY1 sets ImagePinFromY1 field to given value.

### HasImagePinFromY1

`func (o *ComponentDataV4ResponseDTO) HasImagePinFromY1() bool`

HasImagePinFromY1 returns a boolean if a field has been set.

### GetImagePinFromWidth

`func (o *ComponentDataV4ResponseDTO) GetImagePinFromWidth() int32`

GetImagePinFromWidth returns the ImagePinFromWidth field if non-nil, zero value otherwise.

### GetImagePinFromWidthOk

`func (o *ComponentDataV4ResponseDTO) GetImagePinFromWidthOk() (*int32, bool)`

GetImagePinFromWidthOk returns a tuple with the ImagePinFromWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePinFromWidth

`func (o *ComponentDataV4ResponseDTO) SetImagePinFromWidth(v int32)`

SetImagePinFromWidth sets ImagePinFromWidth field to given value.

### HasImagePinFromWidth

`func (o *ComponentDataV4ResponseDTO) HasImagePinFromWidth() bool`

HasImagePinFromWidth returns a boolean if a field has been set.

### GetImagePinFromHeight

`func (o *ComponentDataV4ResponseDTO) GetImagePinFromHeight() int32`

GetImagePinFromHeight returns the ImagePinFromHeight field if non-nil, zero value otherwise.

### GetImagePinFromHeightOk

`func (o *ComponentDataV4ResponseDTO) GetImagePinFromHeightOk() (*int32, bool)`

GetImagePinFromHeightOk returns a tuple with the ImagePinFromHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePinFromHeight

`func (o *ComponentDataV4ResponseDTO) SetImagePinFromHeight(v int32)`

SetImagePinFromHeight sets ImagePinFromHeight field to given value.

### HasImagePinFromHeight

`func (o *ComponentDataV4ResponseDTO) HasImagePinFromHeight() bool`

HasImagePinFromHeight returns a boolean if a field has been set.

### GetImagePinToX

`func (o *ComponentDataV4ResponseDTO) GetImagePinToX() int32`

GetImagePinToX returns the ImagePinToX field if non-nil, zero value otherwise.

### GetImagePinToXOk

`func (o *ComponentDataV4ResponseDTO) GetImagePinToXOk() (*int32, bool)`

GetImagePinToXOk returns a tuple with the ImagePinToX field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePinToX

`func (o *ComponentDataV4ResponseDTO) SetImagePinToX(v int32)`

SetImagePinToX sets ImagePinToX field to given value.

### HasImagePinToX

`func (o *ComponentDataV4ResponseDTO) HasImagePinToX() bool`

HasImagePinToX returns a boolean if a field has been set.

### GetImagePinToY

`func (o *ComponentDataV4ResponseDTO) GetImagePinToY() int32`

GetImagePinToY returns the ImagePinToY field if non-nil, zero value otherwise.

### GetImagePinToYOk

`func (o *ComponentDataV4ResponseDTO) GetImagePinToYOk() (*int32, bool)`

GetImagePinToYOk returns a tuple with the ImagePinToY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePinToY

`func (o *ComponentDataV4ResponseDTO) SetImagePinToY(v int32)`

SetImagePinToY sets ImagePinToY field to given value.

### HasImagePinToY

`func (o *ComponentDataV4ResponseDTO) HasImagePinToY() bool`

HasImagePinToY returns a boolean if a field has been set.

### GetImagePinToWidth

`func (o *ComponentDataV4ResponseDTO) GetImagePinToWidth() int32`

GetImagePinToWidth returns the ImagePinToWidth field if non-nil, zero value otherwise.

### GetImagePinToWidthOk

`func (o *ComponentDataV4ResponseDTO) GetImagePinToWidthOk() (*int32, bool)`

GetImagePinToWidthOk returns a tuple with the ImagePinToWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePinToWidth

`func (o *ComponentDataV4ResponseDTO) SetImagePinToWidth(v int32)`

SetImagePinToWidth sets ImagePinToWidth field to given value.

### HasImagePinToWidth

`func (o *ComponentDataV4ResponseDTO) HasImagePinToWidth() bool`

HasImagePinToWidth returns a boolean if a field has been set.

### GetImagePinToHeight

`func (o *ComponentDataV4ResponseDTO) GetImagePinToHeight() int32`

GetImagePinToHeight returns the ImagePinToHeight field if non-nil, zero value otherwise.

### GetImagePinToHeightOk

`func (o *ComponentDataV4ResponseDTO) GetImagePinToHeightOk() (*int32, bool)`

GetImagePinToHeightOk returns a tuple with the ImagePinToHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePinToHeight

`func (o *ComponentDataV4ResponseDTO) SetImagePinToHeight(v int32)`

SetImagePinToHeight sets ImagePinToHeight field to given value.

### HasImagePinToHeight

`func (o *ComponentDataV4ResponseDTO) HasImagePinToHeight() bool`

HasImagePinToHeight returns a boolean if a field has been set.

### GetIdScopeImage

`func (o *ComponentDataV4ResponseDTO) GetIdScopeImage() int32`

GetIdScopeImage returns the IdScopeImage field if non-nil, zero value otherwise.

### GetIdScopeImageOk

`func (o *ComponentDataV4ResponseDTO) GetIdScopeImageOk() (*int32, bool)`

GetIdScopeImageOk returns a tuple with the IdScopeImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdScopeImage

`func (o *ComponentDataV4ResponseDTO) SetIdScopeImage(v int32)`

SetIdScopeImage sets IdScopeImage field to given value.

### HasIdScopeImage

`func (o *ComponentDataV4ResponseDTO) HasIdScopeImage() bool`

HasIdScopeImage returns a boolean if a field has been set.

### GetDivisionXValue

`func (o *ComponentDataV4ResponseDTO) GetDivisionXValue() float64`

GetDivisionXValue returns the DivisionXValue field if non-nil, zero value otherwise.

### GetDivisionXValueOk

`func (o *ComponentDataV4ResponseDTO) GetDivisionXValueOk() (*float64, bool)`

GetDivisionXValueOk returns a tuple with the DivisionXValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDivisionXValue

`func (o *ComponentDataV4ResponseDTO) SetDivisionXValue(v float64)`

SetDivisionXValue sets DivisionXValue field to given value.

### HasDivisionXValue

`func (o *ComponentDataV4ResponseDTO) HasDivisionXValue() bool`

HasDivisionXValue returns a boolean if a field has been set.

### GetDivisionXUnit

`func (o *ComponentDataV4ResponseDTO) GetDivisionXUnit() Texts`

GetDivisionXUnit returns the DivisionXUnit field if non-nil, zero value otherwise.

### GetDivisionXUnitOk

`func (o *ComponentDataV4ResponseDTO) GetDivisionXUnitOk() (*Texts, bool)`

GetDivisionXUnitOk returns a tuple with the DivisionXUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDivisionXUnit

`func (o *ComponentDataV4ResponseDTO) SetDivisionXUnit(v Texts)`

SetDivisionXUnit sets DivisionXUnit field to given value.

### HasDivisionXUnit

`func (o *ComponentDataV4ResponseDTO) HasDivisionXUnit() bool`

HasDivisionXUnit returns a boolean if a field has been set.

### GetDivisionYValue

`func (o *ComponentDataV4ResponseDTO) GetDivisionYValue() float64`

GetDivisionYValue returns the DivisionYValue field if non-nil, zero value otherwise.

### GetDivisionYValueOk

`func (o *ComponentDataV4ResponseDTO) GetDivisionYValueOk() (*float64, bool)`

GetDivisionYValueOk returns a tuple with the DivisionYValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDivisionYValue

`func (o *ComponentDataV4ResponseDTO) SetDivisionYValue(v float64)`

SetDivisionYValue sets DivisionYValue field to given value.

### HasDivisionYValue

`func (o *ComponentDataV4ResponseDTO) HasDivisionYValue() bool`

HasDivisionYValue returns a boolean if a field has been set.

### GetDivisionYUnit

`func (o *ComponentDataV4ResponseDTO) GetDivisionYUnit() Texts`

GetDivisionYUnit returns the DivisionYUnit field if non-nil, zero value otherwise.

### GetDivisionYUnitOk

`func (o *ComponentDataV4ResponseDTO) GetDivisionYUnitOk() (*Texts, bool)`

GetDivisionYUnitOk returns a tuple with the DivisionYUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDivisionYUnit

`func (o *ComponentDataV4ResponseDTO) SetDivisionYUnit(v Texts)`

SetDivisionYUnit sets DivisionYUnit field to given value.

### HasDivisionYUnit

`func (o *ComponentDataV4ResponseDTO) HasDivisionYUnit() bool`

HasDivisionYUnit returns a boolean if a field has been set.

### GetOffsetYAxis

`func (o *ComponentDataV4ResponseDTO) GetOffsetYAxis() int32`

GetOffsetYAxis returns the OffsetYAxis field if non-nil, zero value otherwise.

### GetOffsetYAxisOk

`func (o *ComponentDataV4ResponseDTO) GetOffsetYAxisOk() (*int32, bool)`

GetOffsetYAxisOk returns a tuple with the OffsetYAxis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffsetYAxis

`func (o *ComponentDataV4ResponseDTO) SetOffsetYAxis(v int32)`

SetOffsetYAxis sets OffsetYAxis field to given value.

### HasOffsetYAxis

`func (o *ComponentDataV4ResponseDTO) HasOffsetYAxis() bool`

HasOffsetYAxis returns a boolean if a field has been set.

### GetScopeSettingsFunctionType

`func (o *ComponentDataV4ResponseDTO) GetScopeSettingsFunctionType() Texts`

GetScopeSettingsFunctionType returns the ScopeSettingsFunctionType field if non-nil, zero value otherwise.

### GetScopeSettingsFunctionTypeOk

`func (o *ComponentDataV4ResponseDTO) GetScopeSettingsFunctionTypeOk() (*Texts, bool)`

GetScopeSettingsFunctionTypeOk returns a tuple with the ScopeSettingsFunctionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopeSettingsFunctionType

`func (o *ComponentDataV4ResponseDTO) SetScopeSettingsFunctionType(v Texts)`

SetScopeSettingsFunctionType sets ScopeSettingsFunctionType field to given value.

### HasScopeSettingsFunctionType

`func (o *ComponentDataV4ResponseDTO) HasScopeSettingsFunctionType() bool`

HasScopeSettingsFunctionType returns a boolean if a field has been set.

### GetPinScopeCouplingType

`func (o *ComponentDataV4ResponseDTO) GetPinScopeCouplingType() Texts`

GetPinScopeCouplingType returns the PinScopeCouplingType field if non-nil, zero value otherwise.

### GetPinScopeCouplingTypeOk

`func (o *ComponentDataV4ResponseDTO) GetPinScopeCouplingTypeOk() (*Texts, bool)`

GetPinScopeCouplingTypeOk returns a tuple with the PinScopeCouplingType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinScopeCouplingType

`func (o *ComponentDataV4ResponseDTO) SetPinScopeCouplingType(v Texts)`

SetPinScopeCouplingType sets PinScopeCouplingType field to given value.

### HasPinScopeCouplingType

`func (o *ComponentDataV4ResponseDTO) HasPinScopeCouplingType() bool`

HasPinScopeCouplingType returns a boolean if a field has been set.

### GetComponentPinFrom

`func (o *ComponentDataV4ResponseDTO) GetComponentPinFrom() Texts`

GetComponentPinFrom returns the ComponentPinFrom field if non-nil, zero value otherwise.

### GetComponentPinFromOk

`func (o *ComponentDataV4ResponseDTO) GetComponentPinFromOk() (*Texts, bool)`

GetComponentPinFromOk returns a tuple with the ComponentPinFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentPinFrom

`func (o *ComponentDataV4ResponseDTO) SetComponentPinFrom(v Texts)`

SetComponentPinFrom sets ComponentPinFrom field to given value.

### HasComponentPinFrom

`func (o *ComponentDataV4ResponseDTO) HasComponentPinFrom() bool`

HasComponentPinFrom returns a boolean if a field has been set.

### GetComponentPinTo

`func (o *ComponentDataV4ResponseDTO) GetComponentPinTo() Texts`

GetComponentPinTo returns the ComponentPinTo field if non-nil, zero value otherwise.

### GetComponentPinToOk

`func (o *ComponentDataV4ResponseDTO) GetComponentPinToOk() (*Texts, bool)`

GetComponentPinToOk returns a tuple with the ComponentPinTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentPinTo

`func (o *ComponentDataV4ResponseDTO) SetComponentPinTo(v Texts)`

SetComponentPinTo sets ComponentPinTo field to given value.

### HasComponentPinTo

`func (o *ComponentDataV4ResponseDTO) HasComponentPinTo() bool`

HasComponentPinTo returns a boolean if a field has been set.

### GetCableIdentifierFrom

`func (o *ComponentDataV4ResponseDTO) GetCableIdentifierFrom() Texts`

GetCableIdentifierFrom returns the CableIdentifierFrom field if non-nil, zero value otherwise.

### GetCableIdentifierFromOk

`func (o *ComponentDataV4ResponseDTO) GetCableIdentifierFromOk() (*Texts, bool)`

GetCableIdentifierFromOk returns a tuple with the CableIdentifierFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCableIdentifierFrom

`func (o *ComponentDataV4ResponseDTO) SetCableIdentifierFrom(v Texts)`

SetCableIdentifierFrom sets CableIdentifierFrom field to given value.

### HasCableIdentifierFrom

`func (o *ComponentDataV4ResponseDTO) HasCableIdentifierFrom() bool`

HasCableIdentifierFrom returns a boolean if a field has been set.

### GetCableIdentifierTo

`func (o *ComponentDataV4ResponseDTO) GetCableIdentifierTo() Texts`

GetCableIdentifierTo returns the CableIdentifierTo field if non-nil, zero value otherwise.

### GetCableIdentifierToOk

`func (o *ComponentDataV4ResponseDTO) GetCableIdentifierToOk() (*Texts, bool)`

GetCableIdentifierToOk returns a tuple with the CableIdentifierTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCableIdentifierTo

`func (o *ComponentDataV4ResponseDTO) SetCableIdentifierTo(v Texts)`

SetCableIdentifierTo sets CableIdentifierTo field to given value.

### HasCableIdentifierTo

`func (o *ComponentDataV4ResponseDTO) HasCableIdentifierTo() bool`

HasCableIdentifierTo returns a boolean if a field has been set.

### GetYearFrom

`func (o *ComponentDataV4ResponseDTO) GetYearFrom() string`

GetYearFrom returns the YearFrom field if non-nil, zero value otherwise.

### GetYearFromOk

`func (o *ComponentDataV4ResponseDTO) GetYearFromOk() (*string, bool)`

GetYearFromOk returns a tuple with the YearFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearFrom

`func (o *ComponentDataV4ResponseDTO) SetYearFrom(v string)`

SetYearFrom sets YearFrom field to given value.

### HasYearFrom

`func (o *ComponentDataV4ResponseDTO) HasYearFrom() bool`

HasYearFrom returns a boolean if a field has been set.

### GetYearTo

`func (o *ComponentDataV4ResponseDTO) GetYearTo() string`

GetYearTo returns the YearTo field if non-nil, zero value otherwise.

### GetYearToOk

`func (o *ComponentDataV4ResponseDTO) GetYearToOk() (*string, bool)`

GetYearToOk returns a tuple with the YearTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearTo

`func (o *ComponentDataV4ResponseDTO) SetYearTo(v string)`

SetYearTo sets YearTo field to given value.

### HasYearTo

`func (o *ComponentDataV4ResponseDTO) HasYearTo() bool`

HasYearTo returns a boolean if a field has been set.

### GetEngineCode

`func (o *ComponentDataV4ResponseDTO) GetEngineCode() string`

GetEngineCode returns the EngineCode field if non-nil, zero value otherwise.

### GetEngineCodeOk

`func (o *ComponentDataV4ResponseDTO) GetEngineCodeOk() (*string, bool)`

GetEngineCodeOk returns a tuple with the EngineCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCode

`func (o *ComponentDataV4ResponseDTO) SetEngineCode(v string)`

SetEngineCode sets EngineCode field to given value.

### HasEngineCode

`func (o *ComponentDataV4ResponseDTO) HasEngineCode() bool`

HasEngineCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


