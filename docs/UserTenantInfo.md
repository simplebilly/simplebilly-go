# UserTenantInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CustomDomain** | Pointer to **NullableString** |  | [optional] 
**Role** | **string** |  | 
**Subdomain** | Pointer to **NullableString** |  | [optional] 
**TenantId** | **string** |  | 
**TenantName** | **string** |  | 

## Methods

### NewUserTenantInfo

`func NewUserTenantInfo(role string, tenantId string, tenantName string, ) *UserTenantInfo`

NewUserTenantInfo instantiates a new UserTenantInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUserTenantInfoWithDefaults

`func NewUserTenantInfoWithDefaults() *UserTenantInfo`

NewUserTenantInfoWithDefaults instantiates a new UserTenantInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCustomDomain

`func (o *UserTenantInfo) GetCustomDomain() string`

GetCustomDomain returns the CustomDomain field if non-nil, zero value otherwise.

### GetCustomDomainOk

`func (o *UserTenantInfo) GetCustomDomainOk() (*string, bool)`

GetCustomDomainOk returns a tuple with the CustomDomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomDomain

`func (o *UserTenantInfo) SetCustomDomain(v string)`

SetCustomDomain sets CustomDomain field to given value.

### HasCustomDomain

`func (o *UserTenantInfo) HasCustomDomain() bool`

HasCustomDomain returns a boolean if a field has been set.

### SetCustomDomainNil

`func (o *UserTenantInfo) SetCustomDomainNil(b bool)`

 SetCustomDomainNil sets the value for CustomDomain to be an explicit nil

### UnsetCustomDomain
`func (o *UserTenantInfo) UnsetCustomDomain()`

UnsetCustomDomain ensures that no value is present for CustomDomain, not even an explicit nil
### GetRole

`func (o *UserTenantInfo) GetRole() string`

GetRole returns the Role field if non-nil, zero value otherwise.

### GetRoleOk

`func (o *UserTenantInfo) GetRoleOk() (*string, bool)`

GetRoleOk returns a tuple with the Role field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRole

`func (o *UserTenantInfo) SetRole(v string)`

SetRole sets Role field to given value.


### GetSubdomain

`func (o *UserTenantInfo) GetSubdomain() string`

GetSubdomain returns the Subdomain field if non-nil, zero value otherwise.

### GetSubdomainOk

`func (o *UserTenantInfo) GetSubdomainOk() (*string, bool)`

GetSubdomainOk returns a tuple with the Subdomain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubdomain

`func (o *UserTenantInfo) SetSubdomain(v string)`

SetSubdomain sets Subdomain field to given value.

### HasSubdomain

`func (o *UserTenantInfo) HasSubdomain() bool`

HasSubdomain returns a boolean if a field has been set.

### SetSubdomainNil

`func (o *UserTenantInfo) SetSubdomainNil(b bool)`

 SetSubdomainNil sets the value for Subdomain to be an explicit nil

### UnsetSubdomain
`func (o *UserTenantInfo) UnsetSubdomain()`

UnsetSubdomain ensures that no value is present for Subdomain, not even an explicit nil
### GetTenantId

`func (o *UserTenantInfo) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *UserTenantInfo) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *UserTenantInfo) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.


### GetTenantName

`func (o *UserTenantInfo) GetTenantName() string`

GetTenantName returns the TenantName field if non-nil, zero value otherwise.

### GetTenantNameOk

`func (o *UserTenantInfo) GetTenantNameOk() (*string, bool)`

GetTenantNameOk returns a tuple with the TenantName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantName

`func (o *UserTenantInfo) SetTenantName(v string)`

SetTenantName sets TenantName field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


