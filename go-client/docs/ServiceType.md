# ServiceType

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Id | [optional] 
**Name** | Pointer to [**ReplacementNameReference**](ReplacementNameReference.md) |  | [optional] 
**Order** | Pointer to **int32** | Order | [optional] 
**Type** | Pointer to **string** | Type | [optional] 
**ImportantGuide** | Pointer to [**ObjectReferenceContainer**](ObjectReferenceContainer.md) |  | [optional] 
**VehicleReference** | Pointer to [**[]VehicleReference**](VehicleReference.md) | List of Vehicle References | [optional] 
**Services** | Pointer to [**[]Service**](Service.md) | List of services | [optional] 
**ExtraServices** | Pointer to [**[]Service**](Service.md) | List of Extra Services | [optional] 

## Methods

### NewServiceType

`func NewServiceType() *ServiceType`

NewServiceType instantiates a new ServiceType object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewServiceTypeWithDefaults

`func NewServiceTypeWithDefaults() *ServiceType`

NewServiceTypeWithDefaults instantiates a new ServiceType object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ServiceType) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ServiceType) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ServiceType) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ServiceType) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ServiceType) GetName() ReplacementNameReference`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ServiceType) GetNameOk() (*ReplacementNameReference, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ServiceType) SetName(v ReplacementNameReference)`

SetName sets Name field to given value.

### HasName

`func (o *ServiceType) HasName() bool`

HasName returns a boolean if a field has been set.

### GetOrder

`func (o *ServiceType) GetOrder() int32`

GetOrder returns the Order field if non-nil, zero value otherwise.

### GetOrderOk

`func (o *ServiceType) GetOrderOk() (*int32, bool)`

GetOrderOk returns a tuple with the Order field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrder

`func (o *ServiceType) SetOrder(v int32)`

SetOrder sets Order field to given value.

### HasOrder

`func (o *ServiceType) HasOrder() bool`

HasOrder returns a boolean if a field has been set.

### GetType

`func (o *ServiceType) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ServiceType) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ServiceType) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *ServiceType) HasType() bool`

HasType returns a boolean if a field has been set.

### GetImportantGuide

`func (o *ServiceType) GetImportantGuide() ObjectReferenceContainer`

GetImportantGuide returns the ImportantGuide field if non-nil, zero value otherwise.

### GetImportantGuideOk

`func (o *ServiceType) GetImportantGuideOk() (*ObjectReferenceContainer, bool)`

GetImportantGuideOk returns a tuple with the ImportantGuide field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImportantGuide

`func (o *ServiceType) SetImportantGuide(v ObjectReferenceContainer)`

SetImportantGuide sets ImportantGuide field to given value.

### HasImportantGuide

`func (o *ServiceType) HasImportantGuide() bool`

HasImportantGuide returns a boolean if a field has been set.

### GetVehicleReference

`func (o *ServiceType) GetVehicleReference() []VehicleReference`

GetVehicleReference returns the VehicleReference field if non-nil, zero value otherwise.

### GetVehicleReferenceOk

`func (o *ServiceType) GetVehicleReferenceOk() (*[]VehicleReference, bool)`

GetVehicleReferenceOk returns a tuple with the VehicleReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVehicleReference

`func (o *ServiceType) SetVehicleReference(v []VehicleReference)`

SetVehicleReference sets VehicleReference field to given value.

### HasVehicleReference

`func (o *ServiceType) HasVehicleReference() bool`

HasVehicleReference returns a boolean if a field has been set.

### GetServices

`func (o *ServiceType) GetServices() []Service`

GetServices returns the Services field if non-nil, zero value otherwise.

### GetServicesOk

`func (o *ServiceType) GetServicesOk() (*[]Service, bool)`

GetServicesOk returns a tuple with the Services field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetServices

`func (o *ServiceType) SetServices(v []Service)`

SetServices sets Services field to given value.

### HasServices

`func (o *ServiceType) HasServices() bool`

HasServices returns a boolean if a field has been set.

### GetExtraServices

`func (o *ServiceType) GetExtraServices() []Service`

GetExtraServices returns the ExtraServices field if non-nil, zero value otherwise.

### GetExtraServicesOk

`func (o *ServiceType) GetExtraServicesOk() (*[]Service, bool)`

GetExtraServicesOk returns a tuple with the ExtraServices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtraServices

`func (o *ServiceType) SetExtraServices(v []Service)`

SetExtraServices sets ExtraServices field to given value.

### HasExtraServices

`func (o *ServiceType) HasExtraServices() bool`

HasExtraServices returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


