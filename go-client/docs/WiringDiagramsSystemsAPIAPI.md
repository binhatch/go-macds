# \WiringDiagramsSystemsAPIAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**PostWiringDiagrams1Systems**](WiringDiagramsSystemsAPIAPI.md#PostWiringDiagrams1Systems) | **Post** /api/v1/wiring-diagrams/systems | Post wiring diagrams systems
[**PostWiringDiagrams2Diagram**](WiringDiagramsSystemsAPIAPI.md#PostWiringDiagrams2Diagram) | **Post** /api/v1/wiring-diagrams/diagram | Post wiring diagrams diagrams



## PostWiringDiagrams1Systems

> []WiringDiagramSystemsResponse PostWiringDiagrams1Systems(ctx).WiringDiagramsRequestDTO(wiringDiagramsRequestDTO).Execute()

Post wiring diagrams systems



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
	wiringDiagramsRequestDTO := *openapiclient.NewWiringDiagramsRequestDTO("Language_example", "KType_example") // WiringDiagramsRequestDTO | The request requires at least kType, language.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WiringDiagramsSystemsAPIAPI.PostWiringDiagrams1Systems(context.Background()).WiringDiagramsRequestDTO(wiringDiagramsRequestDTO).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WiringDiagramsSystemsAPIAPI.PostWiringDiagrams1Systems``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostWiringDiagrams1Systems`: []WiringDiagramSystemsResponse
	fmt.Fprintf(os.Stdout, "Response from `WiringDiagramsSystemsAPIAPI.PostWiringDiagrams1Systems`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostWiringDiagrams1SystemsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **wiringDiagramsRequestDTO** | [**WiringDiagramsRequestDTO**](WiringDiagramsRequestDTO.md) | The request requires at least kType, language. | 

### Return type

[**[]WiringDiagramSystemsResponse**](WiringDiagramSystemsResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## PostWiringDiagrams2Diagram

> SystemAndDiagramResponse PostWiringDiagrams2Diagram(ctx).WiringDiagramsDiagramsRequestDTO(wiringDiagramsDiagramsRequestDTO).Execute()

Post wiring diagrams diagrams



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
	wiringDiagramsDiagramsRequestDTO := *openapiclient.NewWiringDiagramsDiagramsRequestDTO("SystemId_example", "Language_example") // WiringDiagramsDiagramsRequestDTO | The request requires at least systemId, language.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.WiringDiagramsSystemsAPIAPI.PostWiringDiagrams2Diagram(context.Background()).WiringDiagramsDiagramsRequestDTO(wiringDiagramsDiagramsRequestDTO).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `WiringDiagramsSystemsAPIAPI.PostWiringDiagrams2Diagram``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `PostWiringDiagrams2Diagram`: SystemAndDiagramResponse
	fmt.Fprintf(os.Stdout, "Response from `WiringDiagramsSystemsAPIAPI.PostWiringDiagrams2Diagram`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiPostWiringDiagrams2DiagramRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **wiringDiagramsDiagramsRequestDTO** | [**WiringDiagramsDiagramsRequestDTO**](WiringDiagramsDiagramsRequestDTO.md) | The request requires at least systemId, language. | 

### Return type

[**SystemAndDiagramResponse**](SystemAndDiagramResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

