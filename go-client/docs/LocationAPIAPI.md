# \LocationAPIAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Location1component**](LocationAPIAPI.md#Location1component) | **Post** /api/v2/location/components | Component locations
[**Location2fusebox**](LocationAPIAPI.md#Location2fusebox) | **Post** /api/v1/location/fusebox | Fuse and Fuse Box Locations



## Location1component

> LocationsVehicleResponse Location1component(ctx).LocationsRequestDTO(locationsRequestDTO).Execute()

Component locations



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
	locationsRequestDTO := *openapiclient.NewLocationsRequestDTO(int32(123), "Language_example") // LocationsRequestDTO | The request at least requires the specification of kType and language to get a list of location components.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LocationAPIAPI.Location1component(context.Background()).LocationsRequestDTO(locationsRequestDTO).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LocationAPIAPI.Location1component``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Location1component`: LocationsVehicleResponse
	fmt.Fprintf(os.Stdout, "Response from `LocationAPIAPI.Location1component`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLocation1componentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **locationsRequestDTO** | [**LocationsRequestDTO**](LocationsRequestDTO.md) | The request at least requires the specification of kType and language to get a list of location components. | 

### Return type

[**LocationsVehicleResponse**](LocationsVehicleResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Location2fusebox

> FuseBoxLocationsResponse Location2fusebox(ctx).FuseBoxLocationsRequestDTO(fuseBoxLocationsRequestDTO).Execute()

Fuse and Fuse Box Locations



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
	fuseBoxLocationsRequestDTO := *openapiclient.NewFuseBoxLocationsRequestDTO(int32(123), "Language_example") // FuseBoxLocationsRequestDTO | The request requires the specification of kType and language to get the fusebox location.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.LocationAPIAPI.Location2fusebox(context.Background()).FuseBoxLocationsRequestDTO(fuseBoxLocationsRequestDTO).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `LocationAPIAPI.Location2fusebox``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Location2fusebox`: FuseBoxLocationsResponse
	fmt.Fprintf(os.Stdout, "Response from `LocationAPIAPI.Location2fusebox`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiLocation2fuseboxRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **fuseBoxLocationsRequestDTO** | [**FuseBoxLocationsRequestDTO**](FuseBoxLocationsRequestDTO.md) | The request requires the specification of kType and language to get the fusebox location. | 

### Return type

[**FuseBoxLocationsResponse**](FuseBoxLocationsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

