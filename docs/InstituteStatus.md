# InstituteStatus

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Checklist** | [**[]InstituteCheckItem**](InstituteCheckItem.md) |  | 
**Deadlines** | [**InstituteDeadlines**](InstituteDeadlines.md) |  | 
**InstituteType** | **string** |  | 
**Kapitalmarktorientiert** | **bool** |  | 

## Methods

### NewInstituteStatus

`func NewInstituteStatus(checklist []InstituteCheckItem, deadlines InstituteDeadlines, instituteType string, kapitalmarktorientiert bool, ) *InstituteStatus`

NewInstituteStatus instantiates a new InstituteStatus object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstituteStatusWithDefaults

`func NewInstituteStatusWithDefaults() *InstituteStatus`

NewInstituteStatusWithDefaults instantiates a new InstituteStatus object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChecklist

`func (o *InstituteStatus) GetChecklist() []InstituteCheckItem`

GetChecklist returns the Checklist field if non-nil, zero value otherwise.

### GetChecklistOk

`func (o *InstituteStatus) GetChecklistOk() (*[]InstituteCheckItem, bool)`

GetChecklistOk returns a tuple with the Checklist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChecklist

`func (o *InstituteStatus) SetChecklist(v []InstituteCheckItem)`

SetChecklist sets Checklist field to given value.


### GetDeadlines

`func (o *InstituteStatus) GetDeadlines() InstituteDeadlines`

GetDeadlines returns the Deadlines field if non-nil, zero value otherwise.

### GetDeadlinesOk

`func (o *InstituteStatus) GetDeadlinesOk() (*InstituteDeadlines, bool)`

GetDeadlinesOk returns a tuple with the Deadlines field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeadlines

`func (o *InstituteStatus) SetDeadlines(v InstituteDeadlines)`

SetDeadlines sets Deadlines field to given value.


### GetInstituteType

`func (o *InstituteStatus) GetInstituteType() string`

GetInstituteType returns the InstituteType field if non-nil, zero value otherwise.

### GetInstituteTypeOk

`func (o *InstituteStatus) GetInstituteTypeOk() (*string, bool)`

GetInstituteTypeOk returns a tuple with the InstituteType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstituteType

`func (o *InstituteStatus) SetInstituteType(v string)`

SetInstituteType sets InstituteType field to given value.


### GetKapitalmarktorientiert

`func (o *InstituteStatus) GetKapitalmarktorientiert() bool`

GetKapitalmarktorientiert returns the Kapitalmarktorientiert field if non-nil, zero value otherwise.

### GetKapitalmarktorientiertOk

`func (o *InstituteStatus) GetKapitalmarktorientiertOk() (*bool, bool)`

GetKapitalmarktorientiertOk returns a tuple with the Kapitalmarktorientiert field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKapitalmarktorientiert

`func (o *InstituteStatus) SetKapitalmarktorientiert(v bool)`

SetKapitalmarktorientiert sets Kapitalmarktorientiert field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


