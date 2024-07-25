# ComponentDataV3ResponseDTO

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ktypeno** | Pointer to **int32** | KType number | [optional] 
**System** | Pointer to [**SystemDTO**](SystemDTO.md) |  | [optional] 
**SubSystem** | Pointer to **string** | Subsystem | [optional] 
**ComponentName** | Pointer to [**ComponentNameDTO**](ComponentNameDTO.md) |  | [optional] 
**IdImageECU** | Pointer to **int32** | ID ECU Image | [optional] 
**PinFrom** | Pointer to **string** | Pin From | [optional] 
**PinTo** | Pointer to [**TranslationDTO**](TranslationDTO.md) |  | [optional] 
**ValueFrom** | Pointer to [**ValueDTO**](ValueDTO.md) |  | [optional] 
**ValueTo** | Pointer to [**ValueDTO**](ValueDTO.md) |  | [optional] 
**PinMeasurementFunction** | Pointer to [**TranslationDTO**](TranslationDTO.md) |  | [optional] 
**PinMeasurementType** | Pointer to [**TranslationDTO**](TranslationDTO.md) |  | [optional] 
**VehicleState** | Pointer to [**TranslationDTO**](TranslationDTO.md) |  | [optional] 
**MeasurementCondition** | Pointer to [**TranslationDTO**](TranslationDTO.md) |  | [optional] 
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
**DivisionXUnit** | Pointer to [**TranslationDTO**](TranslationDTO.md) |  | [optional] 
**DivisionYValue** | Pointer to **float64** | Division Y Value | [optional] 
**DivisionYUnit** | Pointer to [**TranslationDTO**](TranslationDTO.md) |  | [optional] 
**OffsetYAxis** | Pointer to **int32** | Offset Y Axis | [optional] 
**PinScopeCouplingType** | Pointer to **string** | Pin Scope Coupling Type | [optional] 
**ScopeSettingsFunctionType** | Pointer to [**TranslationDTO**](TranslationDTO.md) |  | [optional] 
**ComponentPinFrom** | Pointer to **string** | Component Pin From | [optional] 
**ComponentPinTo** | Pointer to **string** | Component Pin To | [optional] 
**CableIdentifierFrom** | Pointer to **string** | Cable Identifier From | [optional] 
**CableIdentifierTo** | Pointer to **string** | Cable Identifier To | [optional] 
**YearFrom** | Pointer to **string** | Year From | [optional] 
**YearTo** | Pointer to **string** | Year To | [optional] 
**EngineCode** | Pointer to **string** | Engine Code | [optional] 

## Methods

### NewComponentDataV3ResponseDTO

`func NewComponentDataV3ResponseDTO() *ComponentDataV3ResponseDTO`

NewComponentDataV3ResponseDTO instantiates a new ComponentDataV3ResponseDTO object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComponentDataV3ResponseDTOWithDefaults

`func NewComponentDataV3ResponseDTOWithDefaults() *ComponentDataV3ResponseDTO`

NewComponentDataV3ResponseDTOWithDefaults instantiates a new ComponentDataV3ResponseDTO object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKtypeno

`func (o *ComponentDataV3ResponseDTO) GetKtypeno() int32`

GetKtypeno returns the Ktypeno field if non-nil, zero value otherwise.

### GetKtypenoOk

`func (o *ComponentDataV3ResponseDTO) GetKtypenoOk() (*int32, bool)`

GetKtypenoOk returns a tuple with the Ktypeno field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKtypeno

`func (o *ComponentDataV3ResponseDTO) SetKtypeno(v int32)`

SetKtypeno sets Ktypeno field to given value.

### HasKtypeno

`func (o *ComponentDataV3ResponseDTO) HasKtypeno() bool`

HasKtypeno returns a boolean if a field has been set.

### GetSystem

`func (o *ComponentDataV3ResponseDTO) GetSystem() SystemDTO`

GetSystem returns the System field if non-nil, zero value otherwise.

### GetSystemOk

`func (o *ComponentDataV3ResponseDTO) GetSystemOk() (*SystemDTO, bool)`

GetSystemOk returns a tuple with the System field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSystem

`func (o *ComponentDataV3ResponseDTO) SetSystem(v SystemDTO)`

SetSystem sets System field to given value.

### HasSystem

`func (o *ComponentDataV3ResponseDTO) HasSystem() bool`

HasSystem returns a boolean if a field has been set.

### GetSubSystem

`func (o *ComponentDataV3ResponseDTO) GetSubSystem() string`

GetSubSystem returns the SubSystem field if non-nil, zero value otherwise.

### GetSubSystemOk

`func (o *ComponentDataV3ResponseDTO) GetSubSystemOk() (*string, bool)`

GetSubSystemOk returns a tuple with the SubSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubSystem

`func (o *ComponentDataV3ResponseDTO) SetSubSystem(v string)`

SetSubSystem sets SubSystem field to given value.

### HasSubSystem

`func (o *ComponentDataV3ResponseDTO) HasSubSystem() bool`

HasSubSystem returns a boolean if a field has been set.

### GetComponentName

`func (o *ComponentDataV3ResponseDTO) GetComponentName() ComponentNameDTO`

GetComponentName returns the ComponentName field if non-nil, zero value otherwise.

### GetComponentNameOk

`func (o *ComponentDataV3ResponseDTO) GetComponentNameOk() (*ComponentNameDTO, bool)`

GetComponentNameOk returns a tuple with the ComponentName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentName

`func (o *ComponentDataV3ResponseDTO) SetComponentName(v ComponentNameDTO)`

SetComponentName sets ComponentName field to given value.

### HasComponentName

`func (o *ComponentDataV3ResponseDTO) HasComponentName() bool`

HasComponentName returns a boolean if a field has been set.

### GetIdImageECU

`func (o *ComponentDataV3ResponseDTO) GetIdImageECU() int32`

GetIdImageECU returns the IdImageECU field if non-nil, zero value otherwise.

### GetIdImageECUOk

`func (o *ComponentDataV3ResponseDTO) GetIdImageECUOk() (*int32, bool)`

GetIdImageECUOk returns a tuple with the IdImageECU field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdImageECU

`func (o *ComponentDataV3ResponseDTO) SetIdImageECU(v int32)`

SetIdImageECU sets IdImageECU field to given value.

### HasIdImageECU

`func (o *ComponentDataV3ResponseDTO) HasIdImageECU() bool`

HasIdImageECU returns a boolean if a field has been set.

### GetPinFrom

`func (o *ComponentDataV3ResponseDTO) GetPinFrom() string`

GetPinFrom returns the PinFrom field if non-nil, zero value otherwise.

### GetPinFromOk

`func (o *ComponentDataV3ResponseDTO) GetPinFromOk() (*string, bool)`

GetPinFromOk returns a tuple with the PinFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinFrom

`func (o *ComponentDataV3ResponseDTO) SetPinFrom(v string)`

SetPinFrom sets PinFrom field to given value.

### HasPinFrom

`func (o *ComponentDataV3ResponseDTO) HasPinFrom() bool`

HasPinFrom returns a boolean if a field has been set.

### GetPinTo

`func (o *ComponentDataV3ResponseDTO) GetPinTo() TranslationDTO`

GetPinTo returns the PinTo field if non-nil, zero value otherwise.

### GetPinToOk

`func (o *ComponentDataV3ResponseDTO) GetPinToOk() (*TranslationDTO, bool)`

GetPinToOk returns a tuple with the PinTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinTo

`func (o *ComponentDataV3ResponseDTO) SetPinTo(v TranslationDTO)`

SetPinTo sets PinTo field to given value.

### HasPinTo

`func (o *ComponentDataV3ResponseDTO) HasPinTo() bool`

HasPinTo returns a boolean if a field has been set.

### GetValueFrom

`func (o *ComponentDataV3ResponseDTO) GetValueFrom() ValueDTO`

GetValueFrom returns the ValueFrom field if non-nil, zero value otherwise.

### GetValueFromOk

`func (o *ComponentDataV3ResponseDTO) GetValueFromOk() (*ValueDTO, bool)`

GetValueFromOk returns a tuple with the ValueFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValueFrom

`func (o *ComponentDataV3ResponseDTO) SetValueFrom(v ValueDTO)`

SetValueFrom sets ValueFrom field to given value.

### HasValueFrom

`func (o *ComponentDataV3ResponseDTO) HasValueFrom() bool`

HasValueFrom returns a boolean if a field has been set.

### GetValueTo

`func (o *ComponentDataV3ResponseDTO) GetValueTo() ValueDTO`

GetValueTo returns the ValueTo field if non-nil, zero value otherwise.

### GetValueToOk

`func (o *ComponentDataV3ResponseDTO) GetValueToOk() (*ValueDTO, bool)`

GetValueToOk returns a tuple with the ValueTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValueTo

`func (o *ComponentDataV3ResponseDTO) SetValueTo(v ValueDTO)`

SetValueTo sets ValueTo field to given value.

### HasValueTo

`func (o *ComponentDataV3ResponseDTO) HasValueTo() bool`

HasValueTo returns a boolean if a field has been set.

### GetPinMeasurementFunction

`func (o *ComponentDataV3ResponseDTO) GetPinMeasurementFunction() TranslationDTO`

GetPinMeasurementFunction returns the PinMeasurementFunction field if non-nil, zero value otherwise.

### GetPinMeasurementFunctionOk

`func (o *ComponentDataV3ResponseDTO) GetPinMeasurementFunctionOk() (*TranslationDTO, bool)`

GetPinMeasurementFunctionOk returns a tuple with the PinMeasurementFunction field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinMeasurementFunction

`func (o *ComponentDataV3ResponseDTO) SetPinMeasurementFunction(v TranslationDTO)`

SetPinMeasurementFunction sets PinMeasurementFunction field to given value.

### HasPinMeasurementFunction

`func (o *ComponentDataV3ResponseDTO) HasPinMeasurementFunction() bool`

HasPinMeasurementFunction returns a boolean if a field has been set.

### GetPinMeasurementType

`func (o *ComponentDataV3ResponseDTO) GetPinMeasurementType() TranslationDTO`

GetPinMeasurementType returns the PinMeasurementType field if non-nil, zero value otherwise.

### GetPinMeasurementTypeOk

`func (o *ComponentDataV3ResponseDTO) GetPinMeasurementTypeOk() (*TranslationDTO, bool)`

GetPinMeasurementTypeOk returns a tuple with the PinMeasurementType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinMeasurementType

`func (o *ComponentDataV3ResponseDTO) SetPinMeasurementType(v TranslationDTO)`

SetPinMeasurementType sets PinMeasurementType field to given value.

### HasPinMeasurementType

`func (o *ComponentDataV3ResponseDTO) HasPinMeasurementType() bool`

HasPinMeasurementType returns a boolean if a field has been set.

### GetVehicleState

`func (o *ComponentDataV3ResponseDTO) GetVehicleState() TranslationDTO`

GetVehicleState returns the VehicleState field if non-nil, zero value otherwise.

### GetVehicleStateOk

`func (o *ComponentDataV3ResponseDTO) GetVehicleStateOk() (*TranslationDTO, bool)`

GetVehicleStateOk returns a tuple with the VehicleState field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVehicleState

`func (o *ComponentDataV3ResponseDTO) SetVehicleState(v TranslationDTO)`

SetVehicleState sets VehicleState field to given value.

### HasVehicleState

`func (o *ComponentDataV3ResponseDTO) HasVehicleState() bool`

HasVehicleState returns a boolean if a field has been set.

### GetMeasurementCondition

`func (o *ComponentDataV3ResponseDTO) GetMeasurementCondition() TranslationDTO`

GetMeasurementCondition returns the MeasurementCondition field if non-nil, zero value otherwise.

### GetMeasurementConditionOk

`func (o *ComponentDataV3ResponseDTO) GetMeasurementConditionOk() (*TranslationDTO, bool)`

GetMeasurementConditionOk returns a tuple with the MeasurementCondition field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeasurementCondition

`func (o *ComponentDataV3ResponseDTO) SetMeasurementCondition(v TranslationDTO)`

SetMeasurementCondition sets MeasurementCondition field to given value.

### HasMeasurementCondition

`func (o *ComponentDataV3ResponseDTO) HasMeasurementCondition() bool`

HasMeasurementCondition returns a boolean if a field has been set.

### GetImagePinFromX1

`func (o *ComponentDataV3ResponseDTO) GetImagePinFromX1() int32`

GetImagePinFromX1 returns the ImagePinFromX1 field if non-nil, zero value otherwise.

### GetImagePinFromX1Ok

`func (o *ComponentDataV3ResponseDTO) GetImagePinFromX1Ok() (*int32, bool)`

GetImagePinFromX1Ok returns a tuple with the ImagePinFromX1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePinFromX1

`func (o *ComponentDataV3ResponseDTO) SetImagePinFromX1(v int32)`

SetImagePinFromX1 sets ImagePinFromX1 field to given value.

### HasImagePinFromX1

`func (o *ComponentDataV3ResponseDTO) HasImagePinFromX1() bool`

HasImagePinFromX1 returns a boolean if a field has been set.

### GetImagePinFromY1

`func (o *ComponentDataV3ResponseDTO) GetImagePinFromY1() int32`

GetImagePinFromY1 returns the ImagePinFromY1 field if non-nil, zero value otherwise.

### GetImagePinFromY1Ok

`func (o *ComponentDataV3ResponseDTO) GetImagePinFromY1Ok() (*int32, bool)`

GetImagePinFromY1Ok returns a tuple with the ImagePinFromY1 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePinFromY1

`func (o *ComponentDataV3ResponseDTO) SetImagePinFromY1(v int32)`

SetImagePinFromY1 sets ImagePinFromY1 field to given value.

### HasImagePinFromY1

`func (o *ComponentDataV3ResponseDTO) HasImagePinFromY1() bool`

HasImagePinFromY1 returns a boolean if a field has been set.

### GetImagePinFromWidth

`func (o *ComponentDataV3ResponseDTO) GetImagePinFromWidth() int32`

GetImagePinFromWidth returns the ImagePinFromWidth field if non-nil, zero value otherwise.

### GetImagePinFromWidthOk

`func (o *ComponentDataV3ResponseDTO) GetImagePinFromWidthOk() (*int32, bool)`

GetImagePinFromWidthOk returns a tuple with the ImagePinFromWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePinFromWidth

`func (o *ComponentDataV3ResponseDTO) SetImagePinFromWidth(v int32)`

SetImagePinFromWidth sets ImagePinFromWidth field to given value.

### HasImagePinFromWidth

`func (o *ComponentDataV3ResponseDTO) HasImagePinFromWidth() bool`

HasImagePinFromWidth returns a boolean if a field has been set.

### GetImagePinFromHeight

`func (o *ComponentDataV3ResponseDTO) GetImagePinFromHeight() int32`

GetImagePinFromHeight returns the ImagePinFromHeight field if non-nil, zero value otherwise.

### GetImagePinFromHeightOk

`func (o *ComponentDataV3ResponseDTO) GetImagePinFromHeightOk() (*int32, bool)`

GetImagePinFromHeightOk returns a tuple with the ImagePinFromHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePinFromHeight

`func (o *ComponentDataV3ResponseDTO) SetImagePinFromHeight(v int32)`

SetImagePinFromHeight sets ImagePinFromHeight field to given value.

### HasImagePinFromHeight

`func (o *ComponentDataV3ResponseDTO) HasImagePinFromHeight() bool`

HasImagePinFromHeight returns a boolean if a field has been set.

### GetImagePinToX

`func (o *ComponentDataV3ResponseDTO) GetImagePinToX() int32`

GetImagePinToX returns the ImagePinToX field if non-nil, zero value otherwise.

### GetImagePinToXOk

`func (o *ComponentDataV3ResponseDTO) GetImagePinToXOk() (*int32, bool)`

GetImagePinToXOk returns a tuple with the ImagePinToX field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePinToX

`func (o *ComponentDataV3ResponseDTO) SetImagePinToX(v int32)`

SetImagePinToX sets ImagePinToX field to given value.

### HasImagePinToX

`func (o *ComponentDataV3ResponseDTO) HasImagePinToX() bool`

HasImagePinToX returns a boolean if a field has been set.

### GetImagePinToY

`func (o *ComponentDataV3ResponseDTO) GetImagePinToY() int32`

GetImagePinToY returns the ImagePinToY field if non-nil, zero value otherwise.

### GetImagePinToYOk

`func (o *ComponentDataV3ResponseDTO) GetImagePinToYOk() (*int32, bool)`

GetImagePinToYOk returns a tuple with the ImagePinToY field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePinToY

`func (o *ComponentDataV3ResponseDTO) SetImagePinToY(v int32)`

SetImagePinToY sets ImagePinToY field to given value.

### HasImagePinToY

`func (o *ComponentDataV3ResponseDTO) HasImagePinToY() bool`

HasImagePinToY returns a boolean if a field has been set.

### GetImagePinToWidth

`func (o *ComponentDataV3ResponseDTO) GetImagePinToWidth() int32`

GetImagePinToWidth returns the ImagePinToWidth field if non-nil, zero value otherwise.

### GetImagePinToWidthOk

`func (o *ComponentDataV3ResponseDTO) GetImagePinToWidthOk() (*int32, bool)`

GetImagePinToWidthOk returns a tuple with the ImagePinToWidth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePinToWidth

`func (o *ComponentDataV3ResponseDTO) SetImagePinToWidth(v int32)`

SetImagePinToWidth sets ImagePinToWidth field to given value.

### HasImagePinToWidth

`func (o *ComponentDataV3ResponseDTO) HasImagePinToWidth() bool`

HasImagePinToWidth returns a boolean if a field has been set.

### GetImagePinToHeight

`func (o *ComponentDataV3ResponseDTO) GetImagePinToHeight() int32`

GetImagePinToHeight returns the ImagePinToHeight field if non-nil, zero value otherwise.

### GetImagePinToHeightOk

`func (o *ComponentDataV3ResponseDTO) GetImagePinToHeightOk() (*int32, bool)`

GetImagePinToHeightOk returns a tuple with the ImagePinToHeight field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImagePinToHeight

`func (o *ComponentDataV3ResponseDTO) SetImagePinToHeight(v int32)`

SetImagePinToHeight sets ImagePinToHeight field to given value.

### HasImagePinToHeight

`func (o *ComponentDataV3ResponseDTO) HasImagePinToHeight() bool`

HasImagePinToHeight returns a boolean if a field has been set.

### GetIdScopeImage

`func (o *ComponentDataV3ResponseDTO) GetIdScopeImage() int32`

GetIdScopeImage returns the IdScopeImage field if non-nil, zero value otherwise.

### GetIdScopeImageOk

`func (o *ComponentDataV3ResponseDTO) GetIdScopeImageOk() (*int32, bool)`

GetIdScopeImageOk returns a tuple with the IdScopeImage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdScopeImage

`func (o *ComponentDataV3ResponseDTO) SetIdScopeImage(v int32)`

SetIdScopeImage sets IdScopeImage field to given value.

### HasIdScopeImage

`func (o *ComponentDataV3ResponseDTO) HasIdScopeImage() bool`

HasIdScopeImage returns a boolean if a field has been set.

### GetDivisionXValue

`func (o *ComponentDataV3ResponseDTO) GetDivisionXValue() float64`

GetDivisionXValue returns the DivisionXValue field if non-nil, zero value otherwise.

### GetDivisionXValueOk

`func (o *ComponentDataV3ResponseDTO) GetDivisionXValueOk() (*float64, bool)`

GetDivisionXValueOk returns a tuple with the DivisionXValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDivisionXValue

`func (o *ComponentDataV3ResponseDTO) SetDivisionXValue(v float64)`

SetDivisionXValue sets DivisionXValue field to given value.

### HasDivisionXValue

`func (o *ComponentDataV3ResponseDTO) HasDivisionXValue() bool`

HasDivisionXValue returns a boolean if a field has been set.

### GetDivisionXUnit

`func (o *ComponentDataV3ResponseDTO) GetDivisionXUnit() TranslationDTO`

GetDivisionXUnit returns the DivisionXUnit field if non-nil, zero value otherwise.

### GetDivisionXUnitOk

`func (o *ComponentDataV3ResponseDTO) GetDivisionXUnitOk() (*TranslationDTO, bool)`

GetDivisionXUnitOk returns a tuple with the DivisionXUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDivisionXUnit

`func (o *ComponentDataV3ResponseDTO) SetDivisionXUnit(v TranslationDTO)`

SetDivisionXUnit sets DivisionXUnit field to given value.

### HasDivisionXUnit

`func (o *ComponentDataV3ResponseDTO) HasDivisionXUnit() bool`

HasDivisionXUnit returns a boolean if a field has been set.

### GetDivisionYValue

`func (o *ComponentDataV3ResponseDTO) GetDivisionYValue() float64`

GetDivisionYValue returns the DivisionYValue field if non-nil, zero value otherwise.

### GetDivisionYValueOk

`func (o *ComponentDataV3ResponseDTO) GetDivisionYValueOk() (*float64, bool)`

GetDivisionYValueOk returns a tuple with the DivisionYValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDivisionYValue

`func (o *ComponentDataV3ResponseDTO) SetDivisionYValue(v float64)`

SetDivisionYValue sets DivisionYValue field to given value.

### HasDivisionYValue

`func (o *ComponentDataV3ResponseDTO) HasDivisionYValue() bool`

HasDivisionYValue returns a boolean if a field has been set.

### GetDivisionYUnit

`func (o *ComponentDataV3ResponseDTO) GetDivisionYUnit() TranslationDTO`

GetDivisionYUnit returns the DivisionYUnit field if non-nil, zero value otherwise.

### GetDivisionYUnitOk

`func (o *ComponentDataV3ResponseDTO) GetDivisionYUnitOk() (*TranslationDTO, bool)`

GetDivisionYUnitOk returns a tuple with the DivisionYUnit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDivisionYUnit

`func (o *ComponentDataV3ResponseDTO) SetDivisionYUnit(v TranslationDTO)`

SetDivisionYUnit sets DivisionYUnit field to given value.

### HasDivisionYUnit

`func (o *ComponentDataV3ResponseDTO) HasDivisionYUnit() bool`

HasDivisionYUnit returns a boolean if a field has been set.

### GetOffsetYAxis

`func (o *ComponentDataV3ResponseDTO) GetOffsetYAxis() int32`

GetOffsetYAxis returns the OffsetYAxis field if non-nil, zero value otherwise.

### GetOffsetYAxisOk

`func (o *ComponentDataV3ResponseDTO) GetOffsetYAxisOk() (*int32, bool)`

GetOffsetYAxisOk returns a tuple with the OffsetYAxis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffsetYAxis

`func (o *ComponentDataV3ResponseDTO) SetOffsetYAxis(v int32)`

SetOffsetYAxis sets OffsetYAxis field to given value.

### HasOffsetYAxis

`func (o *ComponentDataV3ResponseDTO) HasOffsetYAxis() bool`

HasOffsetYAxis returns a boolean if a field has been set.

### GetPinScopeCouplingType

`func (o *ComponentDataV3ResponseDTO) GetPinScopeCouplingType() string`

GetPinScopeCouplingType returns the PinScopeCouplingType field if non-nil, zero value otherwise.

### GetPinScopeCouplingTypeOk

`func (o *ComponentDataV3ResponseDTO) GetPinScopeCouplingTypeOk() (*string, bool)`

GetPinScopeCouplingTypeOk returns a tuple with the PinScopeCouplingType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinScopeCouplingType

`func (o *ComponentDataV3ResponseDTO) SetPinScopeCouplingType(v string)`

SetPinScopeCouplingType sets PinScopeCouplingType field to given value.

### HasPinScopeCouplingType

`func (o *ComponentDataV3ResponseDTO) HasPinScopeCouplingType() bool`

HasPinScopeCouplingType returns a boolean if a field has been set.

### GetScopeSettingsFunctionType

`func (o *ComponentDataV3ResponseDTO) GetScopeSettingsFunctionType() TranslationDTO`

GetScopeSettingsFunctionType returns the ScopeSettingsFunctionType field if non-nil, zero value otherwise.

### GetScopeSettingsFunctionTypeOk

`func (o *ComponentDataV3ResponseDTO) GetScopeSettingsFunctionTypeOk() (*TranslationDTO, bool)`

GetScopeSettingsFunctionTypeOk returns a tuple with the ScopeSettingsFunctionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScopeSettingsFunctionType

`func (o *ComponentDataV3ResponseDTO) SetScopeSettingsFunctionType(v TranslationDTO)`

SetScopeSettingsFunctionType sets ScopeSettingsFunctionType field to given value.

### HasScopeSettingsFunctionType

`func (o *ComponentDataV3ResponseDTO) HasScopeSettingsFunctionType() bool`

HasScopeSettingsFunctionType returns a boolean if a field has been set.

### GetComponentPinFrom

`func (o *ComponentDataV3ResponseDTO) GetComponentPinFrom() string`

GetComponentPinFrom returns the ComponentPinFrom field if non-nil, zero value otherwise.

### GetComponentPinFromOk

`func (o *ComponentDataV3ResponseDTO) GetComponentPinFromOk() (*string, bool)`

GetComponentPinFromOk returns a tuple with the ComponentPinFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentPinFrom

`func (o *ComponentDataV3ResponseDTO) SetComponentPinFrom(v string)`

SetComponentPinFrom sets ComponentPinFrom field to given value.

### HasComponentPinFrom

`func (o *ComponentDataV3ResponseDTO) HasComponentPinFrom() bool`

HasComponentPinFrom returns a boolean if a field has been set.

### GetComponentPinTo

`func (o *ComponentDataV3ResponseDTO) GetComponentPinTo() string`

GetComponentPinTo returns the ComponentPinTo field if non-nil, zero value otherwise.

### GetComponentPinToOk

`func (o *ComponentDataV3ResponseDTO) GetComponentPinToOk() (*string, bool)`

GetComponentPinToOk returns a tuple with the ComponentPinTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetComponentPinTo

`func (o *ComponentDataV3ResponseDTO) SetComponentPinTo(v string)`

SetComponentPinTo sets ComponentPinTo field to given value.

### HasComponentPinTo

`func (o *ComponentDataV3ResponseDTO) HasComponentPinTo() bool`

HasComponentPinTo returns a boolean if a field has been set.

### GetCableIdentifierFrom

`func (o *ComponentDataV3ResponseDTO) GetCableIdentifierFrom() string`

GetCableIdentifierFrom returns the CableIdentifierFrom field if non-nil, zero value otherwise.

### GetCableIdentifierFromOk

`func (o *ComponentDataV3ResponseDTO) GetCableIdentifierFromOk() (*string, bool)`

GetCableIdentifierFromOk returns a tuple with the CableIdentifierFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCableIdentifierFrom

`func (o *ComponentDataV3ResponseDTO) SetCableIdentifierFrom(v string)`

SetCableIdentifierFrom sets CableIdentifierFrom field to given value.

### HasCableIdentifierFrom

`func (o *ComponentDataV3ResponseDTO) HasCableIdentifierFrom() bool`

HasCableIdentifierFrom returns a boolean if a field has been set.

### GetCableIdentifierTo

`func (o *ComponentDataV3ResponseDTO) GetCableIdentifierTo() string`

GetCableIdentifierTo returns the CableIdentifierTo field if non-nil, zero value otherwise.

### GetCableIdentifierToOk

`func (o *ComponentDataV3ResponseDTO) GetCableIdentifierToOk() (*string, bool)`

GetCableIdentifierToOk returns a tuple with the CableIdentifierTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCableIdentifierTo

`func (o *ComponentDataV3ResponseDTO) SetCableIdentifierTo(v string)`

SetCableIdentifierTo sets CableIdentifierTo field to given value.

### HasCableIdentifierTo

`func (o *ComponentDataV3ResponseDTO) HasCableIdentifierTo() bool`

HasCableIdentifierTo returns a boolean if a field has been set.

### GetYearFrom

`func (o *ComponentDataV3ResponseDTO) GetYearFrom() string`

GetYearFrom returns the YearFrom field if non-nil, zero value otherwise.

### GetYearFromOk

`func (o *ComponentDataV3ResponseDTO) GetYearFromOk() (*string, bool)`

GetYearFromOk returns a tuple with the YearFrom field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearFrom

`func (o *ComponentDataV3ResponseDTO) SetYearFrom(v string)`

SetYearFrom sets YearFrom field to given value.

### HasYearFrom

`func (o *ComponentDataV3ResponseDTO) HasYearFrom() bool`

HasYearFrom returns a boolean if a field has been set.

### GetYearTo

`func (o *ComponentDataV3ResponseDTO) GetYearTo() string`

GetYearTo returns the YearTo field if non-nil, zero value otherwise.

### GetYearToOk

`func (o *ComponentDataV3ResponseDTO) GetYearToOk() (*string, bool)`

GetYearToOk returns a tuple with the YearTo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetYearTo

`func (o *ComponentDataV3ResponseDTO) SetYearTo(v string)`

SetYearTo sets YearTo field to given value.

### HasYearTo

`func (o *ComponentDataV3ResponseDTO) HasYearTo() bool`

HasYearTo returns a boolean if a field has been set.

### GetEngineCode

`func (o *ComponentDataV3ResponseDTO) GetEngineCode() string`

GetEngineCode returns the EngineCode field if non-nil, zero value otherwise.

### GetEngineCodeOk

`func (o *ComponentDataV3ResponseDTO) GetEngineCodeOk() (*string, bool)`

GetEngineCodeOk returns a tuple with the EngineCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCode

`func (o *ComponentDataV3ResponseDTO) SetEngineCode(v string)`

SetEngineCode sets EngineCode field to given value.

### HasEngineCode

`func (o *ComponentDataV3ResponseDTO) HasEngineCode() bool`

HasEngineCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


