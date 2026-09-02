# InstituteProfile

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**InstituteType** | Pointer to [**InstituteType**](InstituteType.md) | Institutsart: \&quot;kein\&quot; | \&quot;kreditinstitut\&quot; | \&quot;finanzdienstleistungsinstitut\&quot; | \&quot;finanzunternehmen\&quot; | \&quot;versicherung\&quot;. | [optional] 
**Kapitalmarktorientiert** | Pointer to **bool** | Kapitalmarktorientierung (§ 325 Abs. 4 HGB): Offenlegungsfrist 4 statt 12 Monate. | [optional] 

## Methods

### NewInstituteProfile

`func NewInstituteProfile() *InstituteProfile`

NewInstituteProfile instantiates a new InstituteProfile object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstituteProfileWithDefaults

`func NewInstituteProfileWithDefaults() *InstituteProfile`

NewInstituteProfileWithDefaults instantiates a new InstituteProfile object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetInstituteType

`func (o *InstituteProfile) GetInstituteType() InstituteType`

GetInstituteType returns the InstituteType field if non-nil, zero value otherwise.

### GetInstituteTypeOk

`func (o *InstituteProfile) GetInstituteTypeOk() (*InstituteType, bool)`

GetInstituteTypeOk returns a tuple with the InstituteType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInstituteType

`func (o *InstituteProfile) SetInstituteType(v InstituteType)`

SetInstituteType sets InstituteType field to given value.

### HasInstituteType

`func (o *InstituteProfile) HasInstituteType() bool`

HasInstituteType returns a boolean if a field has been set.

### GetKapitalmarktorientiert

`func (o *InstituteProfile) GetKapitalmarktorientiert() bool`

GetKapitalmarktorientiert returns the Kapitalmarktorientiert field if non-nil, zero value otherwise.

### GetKapitalmarktorientiertOk

`func (o *InstituteProfile) GetKapitalmarktorientiertOk() (*bool, bool)`

GetKapitalmarktorientiertOk returns a tuple with the Kapitalmarktorientiert field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKapitalmarktorientiert

`func (o *InstituteProfile) SetKapitalmarktorientiert(v bool)`

SetKapitalmarktorientiert sets Kapitalmarktorientiert field to given value.

### HasKapitalmarktorientiert

`func (o *InstituteProfile) HasKapitalmarktorientiert() bool`

HasKapitalmarktorientiert returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


