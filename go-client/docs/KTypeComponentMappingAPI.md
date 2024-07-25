# \KTypeComponentMappingAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ComponentMapping**](KTypeComponentMappingAPI.md#ComponentMapping) | **Get** /api/v1/ktype/component/mapping | KType Component Mapping



## ComponentMapping

> KtypeComponentMappingResponse ComponentMapping(ctx).KType(kType).SystemIdent(systemIdent).ComponentId(componentId).Execute()

KType Component Mapping



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
	systemIdent := "systemIdent_example" // string | System Identification
	componentId := "componentId_example" // string | Component Id

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KTypeComponentMappingAPI.ComponentMapping(context.Background()).KType(kType).SystemIdent(systemIdent).ComponentId(componentId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KTypeComponentMappingAPI.ComponentMapping``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ComponentMapping`: KtypeComponentMappingResponse
	fmt.Fprintf(os.Stdout, "Response from `KTypeComponentMappingAPI.ComponentMapping`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiComponentMappingRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **kType** | **string** | KType | 
 **systemIdent** | **string** | System Identification | 
 **componentId** | **string** | Component Id | 

### Return type

[**KtypeComponentMappingResponse**](KtypeComponentMappingResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

