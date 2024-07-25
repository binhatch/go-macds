# \VehicleAPIAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetVehicles**](VehicleAPIAPI.md#GetVehicles) | **Get** /api/v1/vehicles | Vehicles



## GetVehicles

> []VehicleReferenceX GetVehicles(ctx).KType(kType).ModelId(modelId).Execute()

Vehicles



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
	kType := "kType_example" // string | KType
	modelId := "modelId_example" // string | Model Id (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VehicleAPIAPI.GetVehicles(context.Background()).KType(kType).ModelId(modelId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VehicleAPIAPI.GetVehicles``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetVehicles`: []VehicleReferenceX
	fmt.Fprintf(os.Stdout, "Response from `VehicleAPIAPI.GetVehicles`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiGetVehiclesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **kType** | **string** | KType | 
 **modelId** | **string** | Model Id | 

### Return type

[**[]VehicleReferenceX**](VehicleReferenceX.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

