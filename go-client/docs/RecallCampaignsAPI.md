# \RecallCampaignsAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**RecallCampaigns1tree**](RecallCampaignsAPI.md#RecallCampaigns1tree) | **Get** /api/v1/recall-campaigns/tree | Get recall campaigns tree



## RecallCampaigns1tree

> []RecallGroup RecallCampaigns1tree(ctx).KType(kType).Language(language).Country(country).IncludeOutdatedInfos(includeOutdatedInfos).Execute()

Get recall campaigns tree



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
	includeOutdatedInfos := "includeOutdatedInfos_example" // string | Include Outdated Info (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.RecallCampaignsAPI.RecallCampaigns1tree(context.Background()).KType(kType).Language(language).Country(country).IncludeOutdatedInfos(includeOutdatedInfos).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `RecallCampaignsAPI.RecallCampaigns1tree``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RecallCampaigns1tree`: []RecallGroup
	fmt.Fprintf(os.Stdout, "Response from `RecallCampaignsAPI.RecallCampaigns1tree`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiRecallCampaigns1treeRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **kType** | **string** | KType | 
 **language** | **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | 
 **country** | **string** | Two characters defining the ISO country code | 
 **includeOutdatedInfos** | **string** | Include Outdated Info | 

### Return type

[**[]RecallGroup**](RecallGroup.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

