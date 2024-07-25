# \ComponentMeasurementValuesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CompMeas31pinComponents**](ComponentMeasurementValuesAPI.md#CompMeas31pinComponents) | **Post** /api/v3/pin/components | Pin components V3
[**CompMeas32pinData**](ComponentMeasurementValuesAPI.md#CompMeas32pinData) | **Post** /api/v3/pin/data | Pin data V3
[**CompMeas33pinEcuImage**](ComponentMeasurementValuesAPI.md#CompMeas33pinEcuImage) | **Get** /api/v3/pin/ecu/image | ECU image V3
[**CompMeas41pinComponents**](ComponentMeasurementValuesAPI.md#CompMeas41pinComponents) | **Post** /api/v4/pin/components | Pin components V4
[**CompMeas42pinData**](ComponentMeasurementValuesAPI.md#CompMeas42pinData) | **Post** /api/v4/pin/data | Pin data V4
[**CompMeas43pinEcuImage**](ComponentMeasurementValuesAPI.md#CompMeas43pinEcuImage) | **Get** /api/v4/pin/ecu/image | ECU image V4



## CompMeas31pinComponents

> PinComponentsV3Response CompMeas31pinComponents(ctx).ComponentsV3RequestDTO(componentsV3RequestDTO).Execute()

Pin components V3



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	componentsV3RequestDTO := *openapiclient.NewComponentsV3RequestDTO(int32(123), "Language_example") // ComponentsV3RequestDTO | The request at least requires the specification of kType and language to get a list of PIN components.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ComponentMeasurementValuesAPI.CompMeas31pinComponents(context.Background()).ComponentsV3RequestDTO(componentsV3RequestDTO).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ComponentMeasurementValuesAPI.CompMeas31pinComponents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompMeas31pinComponents`: PinComponentsV3Response
	fmt.Fprintf(os.Stdout, "Response from `ComponentMeasurementValuesAPI.CompMeas31pinComponents`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCompMeas31pinComponentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **componentsV3RequestDTO** | [**ComponentsV3RequestDTO**](ComponentsV3RequestDTO.md) | The request at least requires the specification of kType and language to get a list of PIN components. | 

### Return type

[**PinComponentsV3Response**](PinComponentsV3Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CompMeas32pinData

> PinDataV3Response CompMeas32pinData(ctx).ComponentDataV3RequestDTO(componentDataV3RequestDTO).Execute()

Pin data V3



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	componentDataV3RequestDTO := *openapiclient.NewComponentDataV3RequestDTO(int32(123), "Language_example", "SystemIdent_example", int32(123)) // ComponentDataV3RequestDTO | The request at least requires the specification of kType and language to get a list of PIN data.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ComponentMeasurementValuesAPI.CompMeas32pinData(context.Background()).ComponentDataV3RequestDTO(componentDataV3RequestDTO).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ComponentMeasurementValuesAPI.CompMeas32pinData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompMeas32pinData`: PinDataV3Response
	fmt.Fprintf(os.Stdout, "Response from `ComponentMeasurementValuesAPI.CompMeas32pinData`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCompMeas32pinDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **componentDataV3RequestDTO** | [**ComponentDataV3RequestDTO**](ComponentDataV3RequestDTO.md) | The request at least requires the specification of kType and language to get a list of PIN data. | 

### Return type

[**PinDataV3Response**](PinDataV3Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CompMeas33pinEcuImage

> UrlResponse CompMeas33pinEcuImage(ctx).EcuImageId(ecuImageId).Execute()

ECU image V3



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	ecuImageId := int32(56) // int32 | Id of the ECU Image

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ComponentMeasurementValuesAPI.CompMeas33pinEcuImage(context.Background()).EcuImageId(ecuImageId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ComponentMeasurementValuesAPI.CompMeas33pinEcuImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompMeas33pinEcuImage`: UrlResponse
	fmt.Fprintf(os.Stdout, "Response from `ComponentMeasurementValuesAPI.CompMeas33pinEcuImage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCompMeas33pinEcuImageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ecuImageId** | **int32** | Id of the ECU Image | 

### Return type

[**UrlResponse**](UrlResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CompMeas41pinComponents

> PinComponentsV4Response CompMeas41pinComponents(ctx).ComponentsV4RequestDTO(componentsV4RequestDTO).Execute()

Pin components V4



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	componentsV4RequestDTO := *openapiclient.NewComponentsV4RequestDTO(int32(123), "Language_example") // ComponentsV4RequestDTO | The request at least requires the specification of kType and language to get a list of PIN components.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ComponentMeasurementValuesAPI.CompMeas41pinComponents(context.Background()).ComponentsV4RequestDTO(componentsV4RequestDTO).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ComponentMeasurementValuesAPI.CompMeas41pinComponents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompMeas41pinComponents`: PinComponentsV4Response
	fmt.Fprintf(os.Stdout, "Response from `ComponentMeasurementValuesAPI.CompMeas41pinComponents`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCompMeas41pinComponentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **componentsV4RequestDTO** | [**ComponentsV4RequestDTO**](ComponentsV4RequestDTO.md) | The request at least requires the specification of kType and language to get a list of PIN components. | 

### Return type

[**PinComponentsV4Response**](PinComponentsV4Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CompMeas42pinData

> PinDataV4Response CompMeas42pinData(ctx).ComponentDataV4RequestDTO(componentDataV4RequestDTO).Execute()

Pin data V4



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	componentDataV4RequestDTO := *openapiclient.NewComponentDataV4RequestDTO(int32(123), "Language_example", "SystemIdent_example", int32(123)) // ComponentDataV4RequestDTO | The request at least requires the specification of kType and language to get a list of PIN data.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ComponentMeasurementValuesAPI.CompMeas42pinData(context.Background()).ComponentDataV4RequestDTO(componentDataV4RequestDTO).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ComponentMeasurementValuesAPI.CompMeas42pinData``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompMeas42pinData`: PinDataV4Response
	fmt.Fprintf(os.Stdout, "Response from `ComponentMeasurementValuesAPI.CompMeas42pinData`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCompMeas42pinDataRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **componentDataV4RequestDTO** | [**ComponentDataV4RequestDTO**](ComponentDataV4RequestDTO.md) | The request at least requires the specification of kType and language to get a list of PIN data. | 

### Return type

[**PinDataV4Response**](PinDataV4Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## CompMeas43pinEcuImage

> UrlResponse CompMeas43pinEcuImage(ctx).EcuImageId(ecuImageId).Execute()

ECU image V4



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/GIT_USER_ID/GIT_REPO_ID"
)

func main() {
	ecuImageId := int32(56) // int32 | Id of the ECU Image

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ComponentMeasurementValuesAPI.CompMeas43pinEcuImage(context.Background()).EcuImageId(ecuImageId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ComponentMeasurementValuesAPI.CompMeas43pinEcuImage``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CompMeas43pinEcuImage`: UrlResponse
	fmt.Fprintf(os.Stdout, "Response from `ComponentMeasurementValuesAPI.CompMeas43pinEcuImage`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCompMeas43pinEcuImageRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **ecuImageId** | **int32** | Id of the ECU Image | 

### Return type

[**UrlResponse**](UrlResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

