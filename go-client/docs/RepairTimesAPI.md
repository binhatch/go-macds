# \RepairTimesAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**RepairTimes1tree**](RepairTimesAPI.md#RepairTimes1tree) | **Get** /api/v1/repair-times-tree | Get repair times tree
[**RepairTimes2details**](RepairTimesAPI.md#RepairTimes2details) | **Get** /api/v1/repair-times | Get repair times details



## RepairTimes1tree

> RepairTimesTreeResponse RepairTimes1tree(ctx).KType(kType).Language(language).Execute()

Get repair times tree



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RepairTimesAPI.RepairTimes1tree(context.Background()).KType(kType).Language(language).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RepairTimesAPI.RepairTimes1tree``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RepairTimes1tree`: RepairTimesTreeResponse
	fmt.Fprintf(os.Stdout, "Response from `RepairTimesAPI.RepairTimes1tree`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRepairTimes1treeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **kType** | **string** | KType | 
 **language** | **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | 

### Return type

[**RepairTimesTreeResponse**](RepairTimesTreeResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RepairTimes2details

> RepairTimesJobResponse RepairTimes2details(ctx).KType(kType).Language(language).CategoryId(categoryId).SubCategoryId(subCategoryId).GenericArticleNo(genericArticleNo).Execute()

Get repair times details



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
	categoryId := "categoryId_example" // string | The id of the desired category, as describe in the /tree endpoint.  A valid combination of query parameters can be: - categoryId & subCategoryId - categoryId & subCategoryId & genericArticleNo - categoryId & genericArticleNo - genericArticleNo (optional)
	subCategoryId := "subCategoryId_example" // string | The id of the desired sub category, as describe in the /tree endpoint.  A valid combination of query parameters can be: - categoryId & subCategoryId - categoryId & subCategoryId & genericArticleNo - categoryId & genericArticleNo - genericArticleNo (optional)
	genericArticleNo := "genericArticleNo_example" // string | The number of the generic article number (spare part/component) to get specific repair time jobs related to the component.  A valid combination of query parameters can be: - categoryId & subCategoryId - categoryId & subCategoryId & genericArticleNo - categoryId & genericArticleNo - genericArticleNo (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RepairTimesAPI.RepairTimes2details(context.Background()).KType(kType).Language(language).CategoryId(categoryId).SubCategoryId(subCategoryId).GenericArticleNo(genericArticleNo).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RepairTimesAPI.RepairTimes2details``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RepairTimes2details`: RepairTimesJobResponse
	fmt.Fprintf(os.Stdout, "Response from `RepairTimesAPI.RepairTimes2details`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRepairTimes2detailsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **kType** | **string** | KType | 
 **language** | **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | 
 **categoryId** | **string** | The id of the desired category, as describe in the /tree endpoint.  A valid combination of query parameters can be: - categoryId &amp; subCategoryId - categoryId &amp; subCategoryId &amp; genericArticleNo - categoryId &amp; genericArticleNo - genericArticleNo | 
 **subCategoryId** | **string** | The id of the desired sub category, as describe in the /tree endpoint.  A valid combination of query parameters can be: - categoryId &amp; subCategoryId - categoryId &amp; subCategoryId &amp; genericArticleNo - categoryId &amp; genericArticleNo - genericArticleNo | 
 **genericArticleNo** | **string** | The number of the generic article number (spare part/component) to get specific repair time jobs related to the component.  A valid combination of query parameters can be: - categoryId &amp; subCategoryId - categoryId &amp; subCategoryId &amp; genericArticleNo - categoryId &amp; genericArticleNo - genericArticleNo | 

### Return type

[**RepairTimesJobResponse**](RepairTimesJobResponse.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

