# \VISAPIAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Ident**](VISAPIAPI.md#Ident) | **Post** /api/v1/ident | Vehicle identification



## Ident

> IdentResponse Ident(ctx).IdentRequestDTO(identRequestDTO).Execute()

Vehicle identification



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
	identRequestDTO := *openapiclient.NewIdentRequestDTO("Vin_example") // IdentRequestDTO | The request includes at least the VIN.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.VISAPIAPI.Ident(context.Background()).IdentRequestDTO(identRequestDTO).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `VISAPIAPI.Ident``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Ident`: IdentResponse
	fmt.Fprintf(os.Stdout, "Response from `VISAPIAPI.Ident`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiIdentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **identRequestDTO** | [**IdentRequestDTO**](IdentRequestDTO.md) | The request includes at least the VIN. | 

### Return type

[**IdentResponse**](IdentResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

