# PlatformInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Author** | **string** |  | 
**Changelog** | [**[]ChangelogEntry**](ChangelogEntry.md) |  | 
**ConfigFieldNames** | **[]string** |  | 
**ConfigFields** | [**[]ConfigFieldInfo**](ConfigFieldInfo.md) |  | 
**DisplayName** | **string** |  | 
**Platform** | **string** |  | 
**Pricing** | [**PluginPricing**](PluginPricing.md) |  | 
**SupportedEntities** | **[]string** |  | 
**SupportsExport** | **bool** |  | 
**SupportsImport** | **bool** |  | 
**SupportsOauth** | **bool** |  | 
**Version** | **string** |  | 

## Methods

### NewPlatformInfo

`func NewPlatformInfo(author string, changelog []ChangelogEntry, configFieldNames []string, configFields []ConfigFieldInfo, displayName string, platform string, pricing PluginPricing, supportedEntities []string, supportsExport bool, supportsImport bool, supportsOauth bool, version string, ) *PlatformInfo`

NewPlatformInfo instantiates a new PlatformInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPlatformInfoWithDefaults

`func NewPlatformInfoWithDefaults() *PlatformInfo`

NewPlatformInfoWithDefaults instantiates a new PlatformInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAuthor

`func (o *PlatformInfo) GetAuthor() string`

GetAuthor returns the Author field if non-nil, zero value otherwise.

### GetAuthorOk

`func (o *PlatformInfo) GetAuthorOk() (*string, bool)`

GetAuthorOk returns a tuple with the Author field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuthor

`func (o *PlatformInfo) SetAuthor(v string)`

SetAuthor sets Author field to given value.


### GetChangelog

`func (o *PlatformInfo) GetChangelog() []ChangelogEntry`

GetChangelog returns the Changelog field if non-nil, zero value otherwise.

### GetChangelogOk

`func (o *PlatformInfo) GetChangelogOk() (*[]ChangelogEntry, bool)`

GetChangelogOk returns a tuple with the Changelog field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChangelog

`func (o *PlatformInfo) SetChangelog(v []ChangelogEntry)`

SetChangelog sets Changelog field to given value.


### GetConfigFieldNames

`func (o *PlatformInfo) GetConfigFieldNames() []string`

GetConfigFieldNames returns the ConfigFieldNames field if non-nil, zero value otherwise.

### GetConfigFieldNamesOk

`func (o *PlatformInfo) GetConfigFieldNamesOk() (*[]string, bool)`

GetConfigFieldNamesOk returns a tuple with the ConfigFieldNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigFieldNames

`func (o *PlatformInfo) SetConfigFieldNames(v []string)`

SetConfigFieldNames sets ConfigFieldNames field to given value.


### GetConfigFields

`func (o *PlatformInfo) GetConfigFields() []ConfigFieldInfo`

GetConfigFields returns the ConfigFields field if non-nil, zero value otherwise.

### GetConfigFieldsOk

`func (o *PlatformInfo) GetConfigFieldsOk() (*[]ConfigFieldInfo, bool)`

GetConfigFieldsOk returns a tuple with the ConfigFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetConfigFields

`func (o *PlatformInfo) SetConfigFields(v []ConfigFieldInfo)`

SetConfigFields sets ConfigFields field to given value.


### GetDisplayName

`func (o *PlatformInfo) GetDisplayName() string`

GetDisplayName returns the DisplayName field if non-nil, zero value otherwise.

### GetDisplayNameOk

`func (o *PlatformInfo) GetDisplayNameOk() (*string, bool)`

GetDisplayNameOk returns a tuple with the DisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDisplayName

`func (o *PlatformInfo) SetDisplayName(v string)`

SetDisplayName sets DisplayName field to given value.


### GetPlatform

`func (o *PlatformInfo) GetPlatform() string`

GetPlatform returns the Platform field if non-nil, zero value otherwise.

### GetPlatformOk

`func (o *PlatformInfo) GetPlatformOk() (*string, bool)`

GetPlatformOk returns a tuple with the Platform field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlatform

`func (o *PlatformInfo) SetPlatform(v string)`

SetPlatform sets Platform field to given value.


### GetPricing

`func (o *PlatformInfo) GetPricing() PluginPricing`

GetPricing returns the Pricing field if non-nil, zero value otherwise.

### GetPricingOk

`func (o *PlatformInfo) GetPricingOk() (*PluginPricing, bool)`

GetPricingOk returns a tuple with the Pricing field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPricing

`func (o *PlatformInfo) SetPricing(v PluginPricing)`

SetPricing sets Pricing field to given value.


### GetSupportedEntities

`func (o *PlatformInfo) GetSupportedEntities() []string`

GetSupportedEntities returns the SupportedEntities field if non-nil, zero value otherwise.

### GetSupportedEntitiesOk

`func (o *PlatformInfo) GetSupportedEntitiesOk() (*[]string, bool)`

GetSupportedEntitiesOk returns a tuple with the SupportedEntities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportedEntities

`func (o *PlatformInfo) SetSupportedEntities(v []string)`

SetSupportedEntities sets SupportedEntities field to given value.


### GetSupportsExport

`func (o *PlatformInfo) GetSupportsExport() bool`

GetSupportsExport returns the SupportsExport field if non-nil, zero value otherwise.

### GetSupportsExportOk

`func (o *PlatformInfo) GetSupportsExportOk() (*bool, bool)`

GetSupportsExportOk returns a tuple with the SupportsExport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsExport

`func (o *PlatformInfo) SetSupportsExport(v bool)`

SetSupportsExport sets SupportsExport field to given value.


### GetSupportsImport

`func (o *PlatformInfo) GetSupportsImport() bool`

GetSupportsImport returns the SupportsImport field if non-nil, zero value otherwise.

### GetSupportsImportOk

`func (o *PlatformInfo) GetSupportsImportOk() (*bool, bool)`

GetSupportsImportOk returns a tuple with the SupportsImport field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsImport

`func (o *PlatformInfo) SetSupportsImport(v bool)`

SetSupportsImport sets SupportsImport field to given value.


### GetSupportsOauth

`func (o *PlatformInfo) GetSupportsOauth() bool`

GetSupportsOauth returns the SupportsOauth field if non-nil, zero value otherwise.

### GetSupportsOauthOk

`func (o *PlatformInfo) GetSupportsOauthOk() (*bool, bool)`

GetSupportsOauthOk returns a tuple with the SupportsOauth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupportsOauth

`func (o *PlatformInfo) SetSupportsOauth(v bool)`

SetSupportsOauth sets SupportsOauth field to given value.


### GetVersion

`func (o *PlatformInfo) GetVersion() string`

GetVersion returns the Version field if non-nil, zero value otherwise.

### GetVersionOk

`func (o *PlatformInfo) GetVersionOk() (*string, bool)`

GetVersionOk returns a tuple with the Version field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVersion

`func (o *PlatformInfo) SetVersion(v string)`

SetVersion sets Version field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


