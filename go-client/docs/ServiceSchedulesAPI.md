# \ServiceSchedulesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ServiceSchedules1main**](ServiceSchedulesAPI.md#ServiceSchedules1main) | **Post** /api/v1/service-schedules | Post service schedules
[**ServiceSchedules2inspections**](ServiceSchedulesAPI.md#ServiceSchedules2inspections) | **Post** /api/v1/service-schedules/inspections | Post service schedules inspections



## ServiceSchedules1main

> []ServiceType ServiceSchedules1main(ctx).ServiceSchedulesRequestDTO(serviceSchedulesRequestDTO).Execute()

Post service schedules



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
	serviceSchedulesRequestDTO := *openapiclient.NewServiceSchedulesRequestDTO("Language_example", "KType_example") // ServiceSchedulesRequestDTO | The request requires at least kType, regionCode, language.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ServiceSchedulesAPI.ServiceSchedules1main(context.Background()).ServiceSchedulesRequestDTO(serviceSchedulesRequestDTO).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ServiceSchedulesAPI.ServiceSchedules1main``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ServiceSchedules1main`: []ServiceType
	fmt.Fprintf(os.Stdout, "Response from `ServiceSchedulesAPI.ServiceSchedules1main`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiServiceSchedules1mainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **serviceSchedulesRequestDTO** | [**ServiceSchedulesRequestDTO**](ServiceSchedulesRequestDTO.md) | The request requires at least kType, regionCode, language. | 

### Return type

[**[]ServiceType**](ServiceType.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ServiceSchedules2inspections

> []SchemaCategory ServiceSchedules2inspections(ctx).InspectionsRequestDTO(inspectionsRequestDTO).Execute()

Post service schedules inspections



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
	inspectionsRequestDTO := *openapiclient.NewInspectionsRequestDTO("Language_example", []int32{int32(123)}, "KType_example") // InspectionsRequestDTO | For the request, it is required to specify the kType, language, regionCode as well as the desired serviceIds.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ServiceSchedulesAPI.ServiceSchedules2inspections(context.Background()).InspectionsRequestDTO(inspectionsRequestDTO).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ServiceSchedulesAPI.ServiceSchedules2inspections``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ServiceSchedules2inspections`: []SchemaCategory
	fmt.Fprintf(os.Stdout, "Response from `ServiceSchedulesAPI.ServiceSchedules2inspections`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiServiceSchedules2inspectionsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **inspectionsRequestDTO** | [**InspectionsRequestDTO**](InspectionsRequestDTO.md) | For the request, it is required to specify the kType, language, regionCode as well as the desired serviceIds. | 

### Return type

[**[]SchemaCategory**](SchemaCategory.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

