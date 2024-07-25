# \TechnicalDataAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**TechnicalData1main**](TechnicalDataAPI.md#TechnicalData1main) | **Get** /api/v1/techdata | Get technical data



## TechnicalData1main

> []VehicleTechData TechnicalData1main(ctx).Language(language).KType(kType).EngineCode(engineCode).EngineKw(engineKw).RegionCode(regionCode).HgsManufId(hgsManufId).HgsModelId(hgsModelId).ProductionYear(productionYear).Preview(preview).Execute()

Get technical data



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
	language := "language_example" // string | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl
	kType := "kType_example" // string | KType (optional)
	engineCode := "engineCode_example" // string | Engine Code (optional)
	engineKw := "engineKw_example" // string | Engine kW (optional)
	regionCode := "regionCode_example" // string | Region Code (optional)
	hgsManufId := "hgsManufId_example" // string | HGS Manufacturer Id (optional)
	hgsModelId := "hgsModelId_example" // string | HGS Model Id (optional)
	productionYear := "productionYear_example" // string | Production Year (optional)
	preview := "preview_example" // string | Preview (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.TechnicalDataAPI.TechnicalData1main(context.Background()).Language(language).KType(kType).EngineCode(engineCode).EngineKw(engineKw).RegionCode(regionCode).HgsManufId(hgsManufId).HgsModelId(hgsModelId).ProductionYear(productionYear).Preview(preview).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `TechnicalDataAPI.TechnicalData1main``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `TechnicalData1main`: []VehicleTechData
	fmt.Fprintf(os.Stdout, "Response from `TechnicalDataAPI.TechnicalData1main`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiTechnicalData1mainRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **language** | **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | 
 **kType** | **string** | KType | 
 **engineCode** | **string** | Engine Code | 
 **engineKw** | **string** | Engine kW | 
 **regionCode** | **string** | Region Code | 
 **hgsManufId** | **string** | HGS Manufacturer Id | 
 **hgsModelId** | **string** | HGS Model Id | 
 **productionYear** | **string** | Production Year | 
 **preview** | **string** | Preview | 

### Return type

[**[]VehicleTechData**](VehicleTechData.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

