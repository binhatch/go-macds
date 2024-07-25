# \DTCAPIAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Dtcs**](DTCAPIAPI.md#Dtcs) | **Post** /api/v4/dtcs | DTC API



## Dtcs

> Response Dtcs(ctx).DtcRequestDto(dtcRequestDto).Execute()

DTC API



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
	dtcRequestDto := *openapiclient.NewDtcRequestDto("Vin_example", "Language_example", []openapiclient.DtcsDto{*openapiclient.NewDtcsDto("Code_example")}) // DtcRequestDto | The request requires at least the VIN, a list of DTCs and the language.

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DTCAPIAPI.Dtcs(context.Background()).DtcRequestDto(dtcRequestDto).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DTCAPIAPI.Dtcs``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Dtcs`: Response
	fmt.Fprintf(os.Stdout, "Response from `DTCAPIAPI.Dtcs`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiDtcsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **dtcRequestDto** | [**DtcRequestDto**](DtcRequestDto.md) | The request requires at least the VIN, a list of DTCs and the language. | 

### Return type

[**Response**](Response.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

