# CustomerGroupUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **NullableString** |  | [optional] 
**MemberIds** | Pointer to **[]string** | Contact ids that are members of this group. | [optional] 
**MembershipFilter** | Pointer to **NullableString** | Rule description for membership, e.g. \&quot;orders &gt; 5 last 12 months\&quot;. | [optional] 
**Name** | Pointer to **NullableString** | Unique group name, e.g. \&quot;VIP\&quot;, \&quot;Wholesale\&quot;, \&quot;Newsletter\&quot;. | [optional] 

## Methods

### NewCustomerGroupUpdate

`func NewCustomerGroupUpdate() *CustomerGroupUpdate`

NewCustomerGroupUpdate instantiates a new CustomerGroupUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerGroupUpdateWithDefaults

`func NewCustomerGroupUpdateWithDefaults() *CustomerGroupUpdate`

NewCustomerGroupUpdateWithDefaults instantiates a new CustomerGroupUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *CustomerGroupUpdate) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CustomerGroupUpdate) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CustomerGroupUpdate) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CustomerGroupUpdate) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CustomerGroupUpdate) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CustomerGroupUpdate) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetMemberIds

`func (o *CustomerGroupUpdate) GetMemberIds() []string`

GetMemberIds returns the MemberIds field if non-nil, zero value otherwise.

### GetMemberIdsOk

`func (o *CustomerGroupUpdate) GetMemberIdsOk() (*[]string, bool)`

GetMemberIdsOk returns a tuple with the MemberIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemberIds

`func (o *CustomerGroupUpdate) SetMemberIds(v []string)`

SetMemberIds sets MemberIds field to given value.

### HasMemberIds

`func (o *CustomerGroupUpdate) HasMemberIds() bool`

HasMemberIds returns a boolean if a field has been set.

### SetMemberIdsNil

`func (o *CustomerGroupUpdate) SetMemberIdsNil(b bool)`

 SetMemberIdsNil sets the value for MemberIds to be an explicit nil

### UnsetMemberIds
`func (o *CustomerGroupUpdate) UnsetMemberIds()`

UnsetMemberIds ensures that no value is present for MemberIds, not even an explicit nil
### GetMembershipFilter

`func (o *CustomerGroupUpdate) GetMembershipFilter() string`

GetMembershipFilter returns the MembershipFilter field if non-nil, zero value otherwise.

### GetMembershipFilterOk

`func (o *CustomerGroupUpdate) GetMembershipFilterOk() (*string, bool)`

GetMembershipFilterOk returns a tuple with the MembershipFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMembershipFilter

`func (o *CustomerGroupUpdate) SetMembershipFilter(v string)`

SetMembershipFilter sets MembershipFilter field to given value.

### HasMembershipFilter

`func (o *CustomerGroupUpdate) HasMembershipFilter() bool`

HasMembershipFilter returns a boolean if a field has been set.

### SetMembershipFilterNil

`func (o *CustomerGroupUpdate) SetMembershipFilterNil(b bool)`

 SetMembershipFilterNil sets the value for MembershipFilter to be an explicit nil

### UnsetMembershipFilter
`func (o *CustomerGroupUpdate) UnsetMembershipFilter()`

UnsetMembershipFilter ensures that no value is present for MembershipFilter, not even an explicit nil
### GetName

`func (o *CustomerGroupUpdate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CustomerGroupUpdate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CustomerGroupUpdate) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CustomerGroupUpdate) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *CustomerGroupUpdate) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *CustomerGroupUpdate) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


