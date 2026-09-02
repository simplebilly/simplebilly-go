# CustomerGroup

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Description** | Pointer to **NullableString** |  | [optional] 
**MemberIds** | Pointer to **[]string** | Contact ids that are members of this group. | [optional] 
**MembershipFilter** | Pointer to **NullableString** | Rule description for membership, e.g. \&quot;orders &gt; 5 last 12 months\&quot;. | [optional] 
**Name** | **string** | Unique group name, e.g. \&quot;VIP\&quot;, \&quot;Wholesale\&quot;, \&quot;Newsletter\&quot;. | 

## Methods

### NewCustomerGroup

`func NewCustomerGroup(name string, ) *CustomerGroup`

NewCustomerGroup instantiates a new CustomerGroup object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCustomerGroupWithDefaults

`func NewCustomerGroupWithDefaults() *CustomerGroup`

NewCustomerGroupWithDefaults instantiates a new CustomerGroup object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDescription

`func (o *CustomerGroup) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *CustomerGroup) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *CustomerGroup) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *CustomerGroup) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *CustomerGroup) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *CustomerGroup) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetMemberIds

`func (o *CustomerGroup) GetMemberIds() []string`

GetMemberIds returns the MemberIds field if non-nil, zero value otherwise.

### GetMemberIdsOk

`func (o *CustomerGroup) GetMemberIdsOk() (*[]string, bool)`

GetMemberIdsOk returns a tuple with the MemberIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMemberIds

`func (o *CustomerGroup) SetMemberIds(v []string)`

SetMemberIds sets MemberIds field to given value.

### HasMemberIds

`func (o *CustomerGroup) HasMemberIds() bool`

HasMemberIds returns a boolean if a field has been set.

### GetMembershipFilter

`func (o *CustomerGroup) GetMembershipFilter() string`

GetMembershipFilter returns the MembershipFilter field if non-nil, zero value otherwise.

### GetMembershipFilterOk

`func (o *CustomerGroup) GetMembershipFilterOk() (*string, bool)`

GetMembershipFilterOk returns a tuple with the MembershipFilter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMembershipFilter

`func (o *CustomerGroup) SetMembershipFilter(v string)`

SetMembershipFilter sets MembershipFilter field to given value.

### HasMembershipFilter

`func (o *CustomerGroup) HasMembershipFilter() bool`

HasMembershipFilter returns a boolean if a field has been set.

### SetMembershipFilterNil

`func (o *CustomerGroup) SetMembershipFilterNil(b bool)`

 SetMembershipFilterNil sets the value for MembershipFilter to be an explicit nil

### UnsetMembershipFilter
`func (o *CustomerGroup) UnsetMembershipFilter()`

UnsetMembershipFilter ensures that no value is present for MembershipFilter, not even an explicit nil
### GetName

`func (o *CustomerGroup) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CustomerGroup) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CustomerGroup) SetName(v string)`

SetName sets Name field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


