# GdprExport

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ActivityLog** | [**[]GdprActivity**](GdprActivity.md) |  | 
**ApiKeys** | [**[]GdprApiKey**](GdprApiKey.md) | Key identifiers and names only — never a usable credential. | 
**Billing** | [**[]GdprBillingInfo**](GdprBillingInfo.md) |  | 
**ExportedAt** | **time.Time** |  | 
**GeneratedByAi** | **bool** | Honesty field: this document is a plain data dump, never AI-generated. | 
**Notifications** | [**[]GdprNotification**](GdprNotification.md) |  | 
**RefreshTokens** | [**[]GdprRefreshToken**](GdprRefreshToken.md) | Session records: metadata only, never the token hash. | 
**Tenants** | [**[]GdprTenant**](GdprTenant.md) |  | 
**UsageEvents** | [**[]GdprUsageEvent**](GdprUsageEvent.md) |  | 
**User** | [**GdprUser**](GdprUser.md) |  | 

## Methods

### NewGdprExport

`func NewGdprExport(activityLog []GdprActivity, apiKeys []GdprApiKey, billing []GdprBillingInfo, exportedAt time.Time, generatedByAi bool, notifications []GdprNotification, refreshTokens []GdprRefreshToken, tenants []GdprTenant, usageEvents []GdprUsageEvent, user GdprUser, ) *GdprExport`

NewGdprExport instantiates a new GdprExport object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGdprExportWithDefaults

`func NewGdprExportWithDefaults() *GdprExport`

NewGdprExportWithDefaults instantiates a new GdprExport object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActivityLog

`func (o *GdprExport) GetActivityLog() []GdprActivity`

GetActivityLog returns the ActivityLog field if non-nil, zero value otherwise.

### GetActivityLogOk

`func (o *GdprExport) GetActivityLogOk() (*[]GdprActivity, bool)`

GetActivityLogOk returns a tuple with the ActivityLog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityLog

`func (o *GdprExport) SetActivityLog(v []GdprActivity)`

SetActivityLog sets ActivityLog field to given value.


### GetApiKeys

`func (o *GdprExport) GetApiKeys() []GdprApiKey`

GetApiKeys returns the ApiKeys field if non-nil, zero value otherwise.

### GetApiKeysOk

`func (o *GdprExport) GetApiKeysOk() (*[]GdprApiKey, bool)`

GetApiKeysOk returns a tuple with the ApiKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiKeys

`func (o *GdprExport) SetApiKeys(v []GdprApiKey)`

SetApiKeys sets ApiKeys field to given value.


### GetBilling

`func (o *GdprExport) GetBilling() []GdprBillingInfo`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *GdprExport) GetBillingOk() (*[]GdprBillingInfo, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *GdprExport) SetBilling(v []GdprBillingInfo)`

SetBilling sets Billing field to given value.


### GetExportedAt

`func (o *GdprExport) GetExportedAt() time.Time`

GetExportedAt returns the ExportedAt field if non-nil, zero value otherwise.

### GetExportedAtOk

`func (o *GdprExport) GetExportedAtOk() (*time.Time, bool)`

GetExportedAtOk returns a tuple with the ExportedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExportedAt

`func (o *GdprExport) SetExportedAt(v time.Time)`

SetExportedAt sets ExportedAt field to given value.


### GetGeneratedByAi

`func (o *GdprExport) GetGeneratedByAi() bool`

GetGeneratedByAi returns the GeneratedByAi field if non-nil, zero value otherwise.

### GetGeneratedByAiOk

`func (o *GdprExport) GetGeneratedByAiOk() (*bool, bool)`

GetGeneratedByAiOk returns a tuple with the GeneratedByAi field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedByAi

`func (o *GdprExport) SetGeneratedByAi(v bool)`

SetGeneratedByAi sets GeneratedByAi field to given value.


### GetNotifications

`func (o *GdprExport) GetNotifications() []GdprNotification`

GetNotifications returns the Notifications field if non-nil, zero value otherwise.

### GetNotificationsOk

`func (o *GdprExport) GetNotificationsOk() (*[]GdprNotification, bool)`

GetNotificationsOk returns a tuple with the Notifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifications

`func (o *GdprExport) SetNotifications(v []GdprNotification)`

SetNotifications sets Notifications field to given value.


### GetRefreshTokens

`func (o *GdprExport) GetRefreshTokens() []GdprRefreshToken`

GetRefreshTokens returns the RefreshTokens field if non-nil, zero value otherwise.

### GetRefreshTokensOk

`func (o *GdprExport) GetRefreshTokensOk() (*[]GdprRefreshToken, bool)`

GetRefreshTokensOk returns a tuple with the RefreshTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefreshTokens

`func (o *GdprExport) SetRefreshTokens(v []GdprRefreshToken)`

SetRefreshTokens sets RefreshTokens field to given value.


### GetTenants

`func (o *GdprExport) GetTenants() []GdprTenant`

GetTenants returns the Tenants field if non-nil, zero value otherwise.

### GetTenantsOk

`func (o *GdprExport) GetTenantsOk() (*[]GdprTenant, bool)`

GetTenantsOk returns a tuple with the Tenants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenants

`func (o *GdprExport) SetTenants(v []GdprTenant)`

SetTenants sets Tenants field to given value.


### GetUsageEvents

`func (o *GdprExport) GetUsageEvents() []GdprUsageEvent`

GetUsageEvents returns the UsageEvents field if non-nil, zero value otherwise.

### GetUsageEventsOk

`func (o *GdprExport) GetUsageEventsOk() (*[]GdprUsageEvent, bool)`

GetUsageEventsOk returns a tuple with the UsageEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageEvents

`func (o *GdprExport) SetUsageEvents(v []GdprUsageEvent)`

SetUsageEvents sets UsageEvents field to given value.


### GetUser

`func (o *GdprExport) GetUser() GdprUser`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *GdprExport) GetUserOk() (*GdprUser, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *GdprExport) SetUser(v GdprUser)`

SetUser sets User field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


