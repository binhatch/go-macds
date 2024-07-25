# \KTypeAPIAPI

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Ktype1makes**](KTypeAPIAPI.md#Ktype1makes) | **Get** /api/v2/makes | Makes
[**Ktype2models**](KTypeAPIAPI.md#Ktype2models) | **Get** /api/v2/models | Models
[**Ktype3types**](KTypeAPIAPI.md#Ktype3types) | **Get** /api/v2/types | Types



## Ktype1makes

> []MakeV2 Ktype1makes(ctx).Execute()

Makes



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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KTypeAPIAPI.Ktype1makes(context.Background()).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KTypeAPIAPI.Ktype1makes``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Ktype1makes`: []MakeV2
	fmt.Fprintf(os.Stdout, "Response from `KTypeAPIAPI.Ktype1makes`: %v\n", resp)
}
```

### Path Parameters

This endpoint does not need any parameter.

### Other Parameters

Other parameters are passed through a pointer to a apiKtype1makesRequest struct via the builder pattern


### Return type

[**[]MakeV2**](MakeV2.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Ktype2models

> []ModelSeriesV2DTO Ktype2models(ctx).MakeId(makeId).Execute()

Models



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
	makeId := "makeId_example" // string | Id of the make

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KTypeAPIAPI.Ktype2models(context.Background()).MakeId(makeId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KTypeAPIAPI.Ktype2models``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Ktype2models`: []ModelSeriesV2DTO
	fmt.Fprintf(os.Stdout, "Response from `KTypeAPIAPI.Ktype2models`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiKtype2modelsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **makeId** | **string** | Id of the make | 

### Return type

[**[]ModelSeriesV2DTO**](ModelSeriesV2DTO.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## Ktype3types

> []TypeV2Dto Ktype3types(ctx).ModelId(modelId).Execute()

Types



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
	modelId := "modelId_example" // string | Id of the model

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.KTypeAPIAPI.Ktype3types(context.Background()).ModelId(modelId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `KTypeAPIAPI.Ktype3types``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Ktype3types`: []TypeV2Dto
	fmt.Fprintf(os.Stdout, "Response from `KTypeAPIAPI.Ktype3types`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiKtype3typesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **modelId** | **string** | Id of the model | 

### Return type

[**[]TypeV2Dto**](TypeV2Dto.md)

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: */*

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

