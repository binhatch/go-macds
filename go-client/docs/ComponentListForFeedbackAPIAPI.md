# \ComponentListForFeedbackAPIAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Feedbackpredictioncomponents**](ComponentListForFeedbackAPIAPI.md#Feedbackpredictioncomponents) | **Get** /api/feedback/prediction/components | FEEDBACK PREDICTION COMPONENTS API



## Feedbackpredictioncomponents

> []DtcFeedbackPredictionComponent Feedbackpredictioncomponents(ctx).Language(language).Execute()

FEEDBACK PREDICTION COMPONENTS API



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ComponentListForFeedbackAPIAPI.Feedbackpredictioncomponents(context.Background()).Language(language).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ComponentListForFeedbackAPIAPI.Feedbackpredictioncomponents``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Feedbackpredictioncomponents`: []DtcFeedbackPredictionComponent
	fmt.Fprintf(os.Stdout, "Response from `ComponentListForFeedbackAPIAPI.Feedbackpredictioncomponents`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiFeedbackpredictioncomponentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **language** | **string** | Two characters defining the language code; allowed values: de, en, nl, zh, it, hu, hr, fr, fi, es, el, tr, da, sv, sk, cs, ru, ro, pt, pl | 

### Return type

[**[]DtcFeedbackPredictionComponent**](DtcFeedbackPredictionComponent.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

