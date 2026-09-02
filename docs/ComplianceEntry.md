# ComplianceEntry

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | **string** |  | 
**Module** | **string** |  | 
**Regulations** | **[]string** |  | 

## Methods

### NewComplianceEntry

`func NewComplianceEntry(description string, module string, regulations []string, ) *ComplianceEntry`

NewComplianceEntry instantiates a new ComplianceEntry object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComplianceEntryWithDefaults

`func NewComplianceEntryWithDefaults() *ComplianceEntry`

NewComplianceEntryWithDefaults instantiates a new ComplianceEntry object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *ComplianceEntry) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ComplianceEntry) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ComplianceEntry) SetDescription(v string)`

SetDescription sets Description field to given value.


### GetModule

`func (o *ComplianceEntry) GetModule() string`

GetModule returns the Module field if non-nil, zero value otherwise.

### GetModuleOk

`func (o *ComplianceEntry) GetModuleOk() (*string, bool)`

GetModuleOk returns a tuple with the Module field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModule

`func (o *ComplianceEntry) SetModule(v string)`

SetModule sets Module field to given value.


### GetRegulations

`func (o *ComplianceEntry) GetRegulations() []string`

GetRegulations returns the Regulations field if non-nil, zero value otherwise.

### GetRegulationsOk

`func (o *ComplianceEntry) GetRegulationsOk() (*[]string, bool)`

GetRegulationsOk returns a tuple with the Regulations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRegulations

`func (o *ComplianceEntry) SetRegulations(v []string)`

SetRegulations sets Regulations field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


