# OssReport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Dependencies** | [**[]OssDependency**](OssDependency.md) |  | 
**TotalCount** | **int32** |  | 

## Methods

### NewOssReport

`func NewOssReport(dependencies []OssDependency, totalCount int32, ) *OssReport`

NewOssReport instantiates a new OssReport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOssReportWithDefaults

`func NewOssReportWithDefaults() *OssReport`

NewOssReportWithDefaults instantiates a new OssReport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDependencies

`func (o *OssReport) GetDependencies() []OssDependency`

GetDependencies returns the Dependencies field if non-nil, zero value otherwise.

### GetDependenciesOk

`func (o *OssReport) GetDependenciesOk() (*[]OssDependency, bool)`

GetDependenciesOk returns a tuple with the Dependencies field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDependencies

`func (o *OssReport) SetDependencies(v []OssDependency)`

SetDependencies sets Dependencies field to given value.


### GetTotalCount

`func (o *OssReport) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *OssReport) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *OssReport) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


