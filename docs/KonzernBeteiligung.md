# KonzernBeteiligung

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CompanyName** | **string** |  | 
**ControlBasis** | **[]string** | Erfüllte Kontroll-Indikatoren (§ 290 Abs. 2 HGB) als deutsche Bezeichnungen. | 
**Controlled** | **bool** |  | 
**OwnershipPct** | **string** |  | 

## Methods

### NewKonzernBeteiligung

`func NewKonzernBeteiligung(companyName string, controlBasis []string, controlled bool, ownershipPct string, ) *KonzernBeteiligung`

NewKonzernBeteiligung instantiates a new KonzernBeteiligung object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewKonzernBeteiligungWithDefaults

`func NewKonzernBeteiligungWithDefaults() *KonzernBeteiligung`

NewKonzernBeteiligungWithDefaults instantiates a new KonzernBeteiligung object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCompanyName

`func (o *KonzernBeteiligung) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *KonzernBeteiligung) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *KonzernBeteiligung) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.


### GetControlBasis

`func (o *KonzernBeteiligung) GetControlBasis() []string`

GetControlBasis returns the ControlBasis field if non-nil, zero value otherwise.

### GetControlBasisOk

`func (o *KonzernBeteiligung) GetControlBasisOk() (*[]string, bool)`

GetControlBasisOk returns a tuple with the ControlBasis field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlBasis

`func (o *KonzernBeteiligung) SetControlBasis(v []string)`

SetControlBasis sets ControlBasis field to given value.


### GetControlled

`func (o *KonzernBeteiligung) GetControlled() bool`

GetControlled returns the Controlled field if non-nil, zero value otherwise.

### GetControlledOk

`func (o *KonzernBeteiligung) GetControlledOk() (*bool, bool)`

GetControlledOk returns a tuple with the Controlled field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetControlled

`func (o *KonzernBeteiligung) SetControlled(v bool)`

SetControlled sets Controlled field to given value.


### GetOwnershipPct

`func (o *KonzernBeteiligung) GetOwnershipPct() string`

GetOwnershipPct returns the OwnershipPct field if non-nil, zero value otherwise.

### GetOwnershipPctOk

`func (o *KonzernBeteiligung) GetOwnershipPctOk() (*string, bool)`

GetOwnershipPctOk returns a tuple with the OwnershipPct field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnershipPct

`func (o *KonzernBeteiligung) SetOwnershipPct(v string)`

SetOwnershipPct sets OwnershipPct field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


