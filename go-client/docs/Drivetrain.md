# Drivetrain

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**EngineCode** | Pointer to **string** | Engine Code | [optional] 
**EngineCodeAlias** | Pointer to **string** | Engine Code Alias | [optional] 
**EngineHp** | Pointer to **int32** | Engine Horse Power | [optional] 
**EngineKw** | Pointer to **int32** | Engine kW | [optional] 
**PropulsionType** | Pointer to **int32** | Propulsion Type as integer value:&lt;table&gt;&lt;tbody&gt;&lt;tr&gt;&lt;td&gt;0&lt;/td&gt;&lt;td&gt;None&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;1&lt;/td&gt;&lt;td&gt;Benzin&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;2&lt;/td&gt;&lt;td&gt;Diesel&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;40&lt;/td&gt;&lt;td&gt;Elektromotor&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;41&lt;/td&gt;&lt;td&gt;Hybrid_Benzin_Elektromotor&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;42&lt;/td&gt;&lt;td&gt;Hybrid_Diesel_Elektromotor&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;46&lt;/td&gt;&lt;td&gt;Benzin_Gas&lt;/td&gt;&lt;/tr&gt;&lt;tr&gt;&lt;td&gt;50&lt;/td&gt;&lt;td&gt;FuelCell&lt;/td&gt;&lt;/tr&gt;&lt;/tbody&gt;&lt;/table&gt; | [optional] 
**PropulsionTypeName** | Pointer to **string** | Propulsion Type Name | [optional] 
**Cylinders** | Pointer to **int32** | Cylinders | [optional] 

## Methods

### NewDrivetrain

`func NewDrivetrain() *Drivetrain`

NewDrivetrain instantiates a new Drivetrain object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDrivetrainWithDefaults

`func NewDrivetrainWithDefaults() *Drivetrain`

NewDrivetrainWithDefaults instantiates a new Drivetrain object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEngineCode

`func (o *Drivetrain) GetEngineCode() string`

GetEngineCode returns the EngineCode field if non-nil, zero value otherwise.

### GetEngineCodeOk

`func (o *Drivetrain) GetEngineCodeOk() (*string, bool)`

GetEngineCodeOk returns a tuple with the EngineCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCode

`func (o *Drivetrain) SetEngineCode(v string)`

SetEngineCode sets EngineCode field to given value.

### HasEngineCode

`func (o *Drivetrain) HasEngineCode() bool`

HasEngineCode returns a boolean if a field has been set.

### GetEngineCodeAlias

`func (o *Drivetrain) GetEngineCodeAlias() string`

GetEngineCodeAlias returns the EngineCodeAlias field if non-nil, zero value otherwise.

### GetEngineCodeAliasOk

`func (o *Drivetrain) GetEngineCodeAliasOk() (*string, bool)`

GetEngineCodeAliasOk returns a tuple with the EngineCodeAlias field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineCodeAlias

`func (o *Drivetrain) SetEngineCodeAlias(v string)`

SetEngineCodeAlias sets EngineCodeAlias field to given value.

### HasEngineCodeAlias

`func (o *Drivetrain) HasEngineCodeAlias() bool`

HasEngineCodeAlias returns a boolean if a field has been set.

### GetEngineHp

`func (o *Drivetrain) GetEngineHp() int32`

GetEngineHp returns the EngineHp field if non-nil, zero value otherwise.

### GetEngineHpOk

`func (o *Drivetrain) GetEngineHpOk() (*int32, bool)`

GetEngineHpOk returns a tuple with the EngineHp field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineHp

`func (o *Drivetrain) SetEngineHp(v int32)`

SetEngineHp sets EngineHp field to given value.

### HasEngineHp

`func (o *Drivetrain) HasEngineHp() bool`

HasEngineHp returns a boolean if a field has been set.

### GetEngineKw

`func (o *Drivetrain) GetEngineKw() int32`

GetEngineKw returns the EngineKw field if non-nil, zero value otherwise.

### GetEngineKwOk

`func (o *Drivetrain) GetEngineKwOk() (*int32, bool)`

GetEngineKwOk returns a tuple with the EngineKw field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEngineKw

`func (o *Drivetrain) SetEngineKw(v int32)`

SetEngineKw sets EngineKw field to given value.

### HasEngineKw

`func (o *Drivetrain) HasEngineKw() bool`

HasEngineKw returns a boolean if a field has been set.

### GetPropulsionType

`func (o *Drivetrain) GetPropulsionType() int32`

GetPropulsionType returns the PropulsionType field if non-nil, zero value otherwise.

### GetPropulsionTypeOk

`func (o *Drivetrain) GetPropulsionTypeOk() (*int32, bool)`

GetPropulsionTypeOk returns a tuple with the PropulsionType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPropulsionType

`func (o *Drivetrain) SetPropulsionType(v int32)`

SetPropulsionType sets PropulsionType field to given value.

### HasPropulsionType

`func (o *Drivetrain) HasPropulsionType() bool`

HasPropulsionType returns a boolean if a field has been set.

### GetPropulsionTypeName

`func (o *Drivetrain) GetPropulsionTypeName() string`

GetPropulsionTypeName returns the PropulsionTypeName field if non-nil, zero value otherwise.

### GetPropulsionTypeNameOk

`func (o *Drivetrain) GetPropulsionTypeNameOk() (*string, bool)`

GetPropulsionTypeNameOk returns a tuple with the PropulsionTypeName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPropulsionTypeName

`func (o *Drivetrain) SetPropulsionTypeName(v string)`

SetPropulsionTypeName sets PropulsionTypeName field to given value.

### HasPropulsionTypeName

`func (o *Drivetrain) HasPropulsionTypeName() bool`

HasPropulsionTypeName returns a boolean if a field has been set.

### GetCylinders

`func (o *Drivetrain) GetCylinders() int32`

GetCylinders returns the Cylinders field if non-nil, zero value otherwise.

### GetCylindersOk

`func (o *Drivetrain) GetCylindersOk() (*int32, bool)`

GetCylindersOk returns a tuple with the Cylinders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCylinders

`func (o *Drivetrain) SetCylinders(v int32)`

SetCylinders sets Cylinders field to given value.

### HasCylinders

`func (o *Drivetrain) HasCylinders() bool`

HasCylinders returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


