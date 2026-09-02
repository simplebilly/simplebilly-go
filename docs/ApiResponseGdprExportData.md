# ApiResponseGdprExportData

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

### NewApiResponseGdprExportData

`func NewApiResponseGdprExportData(activityLog []GdprActivity, apiKeys []GdprApiKey, billing []GdprBillingInfo, exportedAt time.Time, generatedByAi bool, notifications []GdprNotification, refreshTokens []GdprRefreshToken, tenants []GdprTenant, usageEvents []GdprUsageEvent, user GdprUser, ) *ApiResponseGdprExportData`

NewApiResponseGdprExportData instantiates a new ApiResponseGdprExportData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewApiResponseGdprExportDataWithDefaults

`func NewApiResponseGdprExportDataWithDefaults() *ApiResponseGdprExportData`

NewApiResponseGdprExportDataWithDefaults instantiates a new ApiResponseGdprExportData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetActivityLog

`func (o *ApiResponseGdprExportData) GetActivityLog() []GdprActivity`

GetActivityLog returns the ActivityLog field if non-nil, zero value otherwise.

### GetActivityLogOk

`func (o *ApiResponseGdprExportData) GetActivityLogOk() (*[]GdprActivity, bool)`

GetActivityLogOk returns a tuple with the ActivityLog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActivityLog

`func (o *ApiResponseGdprExportData) SetActivityLog(v []GdprActivity)`

SetActivityLog sets ActivityLog field to given value.


### GetApiKeys

`func (o *ApiResponseGdprExportData) GetApiKeys() []GdprApiKey`

GetApiKeys returns the ApiKeys field if non-nil, zero value otherwise.

### GetApiKeysOk

`func (o *ApiResponseGdprExportData) GetApiKeysOk() (*[]GdprApiKey, bool)`

GetApiKeysOk returns a tuple with the ApiKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetApiKeys

`func (o *ApiResponseGdprExportData) SetApiKeys(v []GdprApiKey)`

SetApiKeys sets ApiKeys field to given value.


### GetBilling

`func (o *ApiResponseGdprExportData) GetBilling() []GdprBillingInfo`

GetBilling returns the Billing field if non-nil, zero value otherwise.

### GetBillingOk

`func (o *ApiResponseGdprExportData) GetBillingOk() (*[]GdprBillingInfo, bool)`

GetBillingOk returns a tuple with the Billing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBilling

`func (o *ApiResponseGdprExportData) SetBilling(v []GdprBillingInfo)`

SetBilling sets Billing field to given value.


### GetExportedAt

`func (o *ApiResponseGdprExportData) GetExportedAt() time.Time`

GetExportedAt returns the ExportedAt field if non-nil, zero value otherwise.

### GetExportedAtOk

`func (o *ApiResponseGdprExportData) GetExportedAtOk() (*time.Time, bool)`

GetExportedAtOk returns a tuple with the ExportedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExportedAt

`func (o *ApiResponseGdprExportData) SetExportedAt(v time.Time)`

SetExportedAt sets ExportedAt field to given value.


### GetGeneratedByAi

`func (o *ApiResponseGdprExportData) GetGeneratedByAi() bool`

GetGeneratedByAi returns the GeneratedByAi field if non-nil, zero value otherwise.

### GetGeneratedByAiOk

`func (o *ApiResponseGdprExportData) GetGeneratedByAiOk() (*bool, bool)`

GetGeneratedByAiOk returns a tuple with the GeneratedByAi field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGeneratedByAi

`func (o *ApiResponseGdprExportData) SetGeneratedByAi(v bool)`

SetGeneratedByAi sets GeneratedByAi field to given value.


### GetNotifications

`func (o *ApiResponseGdprExportData) GetNotifications() []GdprNotification`

GetNotifications returns the Notifications field if non-nil, zero value otherwise.

### GetNotificationsOk

`func (o *ApiResponseGdprExportData) GetNotificationsOk() (*[]GdprNotification, bool)`

GetNotificationsOk returns a tuple with the Notifications field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotifications

`func (o *ApiResponseGdprExportData) SetNotifications(v []GdprNotification)`

SetNotifications sets Notifications field to given value.


### GetRefreshTokens

`func (o *ApiResponseGdprExportData) GetRefreshTokens() []GdprRefreshToken`

GetRefreshTokens returns the RefreshTokens field if non-nil, zero value otherwise.

### GetRefreshTokensOk

`func (o *ApiResponseGdprExportData) GetRefreshTokensOk() (*[]GdprRefreshToken, bool)`

GetRefreshTokensOk returns a tuple with the RefreshTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRefreshTokens

`func (o *ApiResponseGdprExportData) SetRefreshTokens(v []GdprRefreshToken)`

SetRefreshTokens sets RefreshTokens field to given value.


### GetTenants

`func (o *ApiResponseGdprExportData) GetTenants() []GdprTenant`

GetTenants returns the Tenants field if non-nil, zero value otherwise.

### GetTenantsOk

`func (o *ApiResponseGdprExportData) GetTenantsOk() (*[]GdprTenant, bool)`

GetTenantsOk returns a tuple with the Tenants field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenants

`func (o *ApiResponseGdprExportData) SetTenants(v []GdprTenant)`

SetTenants sets Tenants field to given value.


### GetUsageEvents

`func (o *ApiResponseGdprExportData) GetUsageEvents() []GdprUsageEvent`

GetUsageEvents returns the UsageEvents field if non-nil, zero value otherwise.

### GetUsageEventsOk

`func (o *ApiResponseGdprExportData) GetUsageEventsOk() (*[]GdprUsageEvent, bool)`

GetUsageEventsOk returns a tuple with the UsageEvents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsageEvents

`func (o *ApiResponseGdprExportData) SetUsageEvents(v []GdprUsageEvent)`

SetUsageEvents sets UsageEvents field to given value.


### GetUser

`func (o *ApiResponseGdprExportData) GetUser() GdprUser`

GetUser returns the User field if non-nil, zero value otherwise.

### GetUserOk

`func (o *ApiResponseGdprExportData) GetUserOk() (*GdprUser, bool)`

GetUserOk returns a tuple with the User field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUser

`func (o *ApiResponseGdprExportData) SetUser(v GdprUser)`

SetUser sets User field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


