# \RepairInstructionsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**RepairInstructions1tree**](RepairInstructionsAPI.md#RepairInstructions1tree) | **Get** /api/v1/repair-instructions/tree | Get repair instructions manuals tree
[**RepairInstructions2manual**](RepairInstructionsAPI.md#RepairInstructions2manual) | **Get** /api/v1/repair-instructions/manual | Get repair instructions manual



## RepairInstructions1tree

> []MainGroup RepairInstructions1tree(ctx).KType(kType).Language(language).Country(country).Execute()

Get repair instructions manuals tree



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
	resp, r, err := apiClient.RepairInstructionsAPI.RepairInstructions1tree(context.Background()).KType(kType).Language(language).Country(country).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RepairInstructionsAPI.RepairInstructions1tree``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RepairInstructions1tree`: []MainGroup
	fmt.Fprintf(os.Stdout, "Response from `RepairInstructionsAPI.RepairInstructions1tree`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRepairInstructions1treeRequest struct via the builder pattern


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


## RepairInstructions2manual

> TecManual RepairInstructions2manual(ctx).KType(kType).Language(language).Country(country).MainGroup(mainGroup).SubGroup(subGroup).ManualGroup(manualGroup).Manual(manual).Qualifier(qualifier).Execute()

Get repair instructions manual



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
	resp, r, err := apiClient.RepairInstructionsAPI.RepairInstructions2manual(context.Background()).KType(kType).Language(language).Country(country).MainGroup(mainGroup).SubGroup(subGroup).ManualGroup(manualGroup).Manual(manual).Qualifier(qualifier).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RepairInstructionsAPI.RepairInstructions2manual``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RepairInstructions2manual`: TecManual
	fmt.Fprintf(os.Stdout, "Response from `RepairInstructionsAPI.RepairInstructions2manual`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRepairInstructions2manualRequest struct via the builder pattern


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

