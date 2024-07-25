# \ManufacturerCampaignsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**ManufacturerCampaigns1tree**](ManufacturerCampaignsAPI.md#ManufacturerCampaigns1tree) | **Get** /api/v1/manufacturer-campaigns/tree | Get manufacturer campaigns manual tree
[**ManufacturerCampaigns2manual**](ManufacturerCampaignsAPI.md#ManufacturerCampaigns2manual) | **Get** /api/v1/manufacturer-campaigns/manual | Get manufacturer campaigns manual



## ManufacturerCampaigns1tree

> []MainGroup ManufacturerCampaigns1tree(ctx).KType(kType).Language(language).Country(country).Execute()

Get manufacturer campaigns manual tree



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
	language := "language_example" // string | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl
	country := "country_example" // string | Two characters defining the ISO country code

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManufacturerCampaignsAPI.ManufacturerCampaigns1tree(context.Background()).KType(kType).Language(language).Country(country).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManufacturerCampaignsAPI.ManufacturerCampaigns1tree``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ManufacturerCampaigns1tree`: []MainGroup
	fmt.Fprintf(os.Stdout, "Response from `ManufacturerCampaignsAPI.ManufacturerCampaigns1tree`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiManufacturerCampaigns1treeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **kType** | **string** | KType | 
 **language** | **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | 
 **country** | **string** | Two characters defining the ISO country code | 

### Return type

[**[]MainGroup**](MainGroup.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ManufacturerCampaigns2manual

> TecManual ManufacturerCampaigns2manual(ctx).KType(kType).Language(language).Country(country).MainGroup(mainGroup).SubGroup(subGroup).ManualGroup(manualGroup).Manual(manual).Qualifier(qualifier).Execute()

Get manufacturer campaigns manual



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
	language := "language_example" // string | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl
	country := "country_example" // string | Two characters defining the ISO country code
	mainGroup := "mainGroup_example" // string | Main Group
	subGroup := "subGroup_example" // string | Sub Group
	manualGroup := "manualGroup_example" // string | Manual Group
	manual := "manual_example" // string | Manual
	qualifier := "qualifier_example" // string | Qualifier

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ManufacturerCampaignsAPI.ManufacturerCampaigns2manual(context.Background()).KType(kType).Language(language).Country(country).MainGroup(mainGroup).SubGroup(subGroup).ManualGroup(manualGroup).Manual(manual).Qualifier(qualifier).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ManufacturerCampaignsAPI.ManufacturerCampaigns2manual``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ManufacturerCampaigns2manual`: TecManual
	fmt.Fprintf(os.Stdout, "Response from `ManufacturerCampaignsAPI.ManufacturerCampaigns2manual`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiManufacturerCampaigns2manualRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **kType** | **string** | KType | 
 **language** | **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | 
 **country** | **string** | Two characters defining the ISO country code | 
 **mainGroup** | **string** | Main Group | 
 **subGroup** | **string** | Sub Group | 
 **manualGroup** | **string** | Manual Group | 
 **manual** | **string** | Manual | 
 **qualifier** | **string** | Qualifier | 

### Return type

[**TecManual**](TecManual.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

