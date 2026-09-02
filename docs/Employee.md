# Employee

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **NullableString** |  | [optional] 
**BackupEmployeeId** | Pointer to **NullableString** | References another employee who covers when this employee is absent. | [optional] 
**Bic** | Pointer to **NullableString** |  | [optional] 
**City** | Pointer to **NullableString** |  | [optional] 
**Country** | Pointer to [**NullableCountryCode**](CountryCode.md) |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**DateOfBirth** | Pointer to **NullableString** |  | [optional] 
**DeletedAt** | Pointer to **NullableTime** |  | [optional] 
**DepartmentId** | Pointer to **string** | References the department entity. | [optional] 
**Email** | Pointer to **string** |  | [optional] 
**FirstName** | Pointer to **string** |  | [optional] 
**Gender** | Pointer to [**NullableGender**](Gender.md) | Gender for pay-transparency reporting: \&quot;male\&quot;, \&quot;female\&quot; or \&quot;diverse\&quot;. | [optional] 
**HireDate** | Pointer to **NullableString** |  | [optional] 
**HourlyCost** | Pointer to **NullableString** | Hourly cost rate in EUR for labor-cost reporting; when unset the rate is derived from &#x60;monthly_salary / (weekly_hours * 4.33)&#x60;. | [optional] 
**Iban** | Pointer to **NullableString** |  | [optional] 
**Id** | Pointer to **string** |  | [optional] 
**JobTitle** | Pointer to **string** |  | [optional] 
**LastLogin** | Pointer to **NullableTime** |  | [optional] 
**LastName** | Pointer to **string** |  | [optional] 
**LastUpdated** | Pointer to **NullableTime** |  | [optional] 
**MonthlySalary** | Pointer to **NullableString** | Gross monthly salary in EUR for pay-transparency reporting. | [optional] 
**Phone** | Pointer to **NullableString** |  | [optional] 
**State** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to [**EmployeeStatus**](EmployeeStatus.md) |  | [optional] 
**TenantId** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to **NullableTime** |  | [optional] 
**UserId** | Pointer to **NullableString** | References the user entity. | [optional] 
**WeeklyHours** | Pointer to **NullableString** | Contractual weekly working hours for pay-transparency normalization. | [optional] 
**Zip** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewEmployee

`func NewEmployee() *Employee`

NewEmployee instantiates a new Employee object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmployeeWithDefaults

`func NewEmployeeWithDefaults() *Employee`

NewEmployeeWithDefaults instantiates a new Employee object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *Employee) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *Employee) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *Employee) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *Employee) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *Employee) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *Employee) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetBackupEmployeeId

`func (o *Employee) GetBackupEmployeeId() string`

GetBackupEmployeeId returns the BackupEmployeeId field if non-nil, zero value otherwise.

### GetBackupEmployeeIdOk

`func (o *Employee) GetBackupEmployeeIdOk() (*string, bool)`

GetBackupEmployeeIdOk returns a tuple with the BackupEmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackupEmployeeId

`func (o *Employee) SetBackupEmployeeId(v string)`

SetBackupEmployeeId sets BackupEmployeeId field to given value.

### HasBackupEmployeeId

`func (o *Employee) HasBackupEmployeeId() bool`

HasBackupEmployeeId returns a boolean if a field has been set.

### SetBackupEmployeeIdNil

`func (o *Employee) SetBackupEmployeeIdNil(b bool)`

 SetBackupEmployeeIdNil sets the value for BackupEmployeeId to be an explicit nil

### UnsetBackupEmployeeId
`func (o *Employee) UnsetBackupEmployeeId()`

UnsetBackupEmployeeId ensures that no value is present for BackupEmployeeId, not even an explicit nil
### GetBic

`func (o *Employee) GetBic() string`

GetBic returns the Bic field if non-nil, zero value otherwise.

### GetBicOk

`func (o *Employee) GetBicOk() (*string, bool)`

GetBicOk returns a tuple with the Bic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBic

`func (o *Employee) SetBic(v string)`

SetBic sets Bic field to given value.

### HasBic

`func (o *Employee) HasBic() bool`

HasBic returns a boolean if a field has been set.

### SetBicNil

`func (o *Employee) SetBicNil(b bool)`

 SetBicNil sets the value for Bic to be an explicit nil

### UnsetBic
`func (o *Employee) UnsetBic()`

UnsetBic ensures that no value is present for Bic, not even an explicit nil
### GetCity

`func (o *Employee) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *Employee) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *Employee) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *Employee) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *Employee) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *Employee) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetCountry

`func (o *Employee) GetCountry() CountryCode`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *Employee) GetCountryOk() (*CountryCode, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *Employee) SetCountry(v CountryCode)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *Employee) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *Employee) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *Employee) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetCreatedAt

`func (o *Employee) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Employee) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Employee) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *Employee) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetDateOfBirth

`func (o *Employee) GetDateOfBirth() string`

GetDateOfBirth returns the DateOfBirth field if non-nil, zero value otherwise.

### GetDateOfBirthOk

`func (o *Employee) GetDateOfBirthOk() (*string, bool)`

GetDateOfBirthOk returns a tuple with the DateOfBirth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateOfBirth

`func (o *Employee) SetDateOfBirth(v string)`

SetDateOfBirth sets DateOfBirth field to given value.

### HasDateOfBirth

`func (o *Employee) HasDateOfBirth() bool`

HasDateOfBirth returns a boolean if a field has been set.

### SetDateOfBirthNil

`func (o *Employee) SetDateOfBirthNil(b bool)`

 SetDateOfBirthNil sets the value for DateOfBirth to be an explicit nil

### UnsetDateOfBirth
`func (o *Employee) UnsetDateOfBirth()`

UnsetDateOfBirth ensures that no value is present for DateOfBirth, not even an explicit nil
### GetDeletedAt

`func (o *Employee) GetDeletedAt() time.Time`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *Employee) GetDeletedAtOk() (*time.Time, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *Employee) SetDeletedAt(v time.Time)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *Employee) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### SetDeletedAtNil

`func (o *Employee) SetDeletedAtNil(b bool)`

 SetDeletedAtNil sets the value for DeletedAt to be an explicit nil

### UnsetDeletedAt
`func (o *Employee) UnsetDeletedAt()`

UnsetDeletedAt ensures that no value is present for DeletedAt, not even an explicit nil
### GetDepartmentId

`func (o *Employee) GetDepartmentId() string`

GetDepartmentId returns the DepartmentId field if non-nil, zero value otherwise.

### GetDepartmentIdOk

`func (o *Employee) GetDepartmentIdOk() (*string, bool)`

GetDepartmentIdOk returns a tuple with the DepartmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartmentId

`func (o *Employee) SetDepartmentId(v string)`

SetDepartmentId sets DepartmentId field to given value.

### HasDepartmentId

`func (o *Employee) HasDepartmentId() bool`

HasDepartmentId returns a boolean if a field has been set.

### GetEmail

`func (o *Employee) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *Employee) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *Employee) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *Employee) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetFirstName

`func (o *Employee) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *Employee) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *Employee) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *Employee) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetGender

`func (o *Employee) GetGender() Gender`

GetGender returns the Gender field if non-nil, zero value otherwise.

### GetGenderOk

`func (o *Employee) GetGenderOk() (*Gender, bool)`

GetGenderOk returns a tuple with the Gender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGender

`func (o *Employee) SetGender(v Gender)`

SetGender sets Gender field to given value.

### HasGender

`func (o *Employee) HasGender() bool`

HasGender returns a boolean if a field has been set.

### SetGenderNil

`func (o *Employee) SetGenderNil(b bool)`

 SetGenderNil sets the value for Gender to be an explicit nil

### UnsetGender
`func (o *Employee) UnsetGender()`

UnsetGender ensures that no value is present for Gender, not even an explicit nil
### GetHireDate

`func (o *Employee) GetHireDate() string`

GetHireDate returns the HireDate field if non-nil, zero value otherwise.

### GetHireDateOk

`func (o *Employee) GetHireDateOk() (*string, bool)`

GetHireDateOk returns a tuple with the HireDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHireDate

`func (o *Employee) SetHireDate(v string)`

SetHireDate sets HireDate field to given value.

### HasHireDate

`func (o *Employee) HasHireDate() bool`

HasHireDate returns a boolean if a field has been set.

### SetHireDateNil

`func (o *Employee) SetHireDateNil(b bool)`

 SetHireDateNil sets the value for HireDate to be an explicit nil

### UnsetHireDate
`func (o *Employee) UnsetHireDate()`

UnsetHireDate ensures that no value is present for HireDate, not even an explicit nil
### GetHourlyCost

`func (o *Employee) GetHourlyCost() string`

GetHourlyCost returns the HourlyCost field if non-nil, zero value otherwise.

### GetHourlyCostOk

`func (o *Employee) GetHourlyCostOk() (*string, bool)`

GetHourlyCostOk returns a tuple with the HourlyCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHourlyCost

`func (o *Employee) SetHourlyCost(v string)`

SetHourlyCost sets HourlyCost field to given value.

### HasHourlyCost

`func (o *Employee) HasHourlyCost() bool`

HasHourlyCost returns a boolean if a field has been set.

### SetHourlyCostNil

`func (o *Employee) SetHourlyCostNil(b bool)`

 SetHourlyCostNil sets the value for HourlyCost to be an explicit nil

### UnsetHourlyCost
`func (o *Employee) UnsetHourlyCost()`

UnsetHourlyCost ensures that no value is present for HourlyCost, not even an explicit nil
### GetIban

`func (o *Employee) GetIban() string`

GetIban returns the Iban field if non-nil, zero value otherwise.

### GetIbanOk

`func (o *Employee) GetIbanOk() (*string, bool)`

GetIbanOk returns a tuple with the Iban field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIban

`func (o *Employee) SetIban(v string)`

SetIban sets Iban field to given value.

### HasIban

`func (o *Employee) HasIban() bool`

HasIban returns a boolean if a field has been set.

### SetIbanNil

`func (o *Employee) SetIbanNil(b bool)`

 SetIbanNil sets the value for Iban to be an explicit nil

### UnsetIban
`func (o *Employee) UnsetIban()`

UnsetIban ensures that no value is present for Iban, not even an explicit nil
### GetId

`func (o *Employee) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *Employee) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *Employee) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *Employee) HasId() bool`

HasId returns a boolean if a field has been set.

### GetJobTitle

`func (o *Employee) GetJobTitle() string`

GetJobTitle returns the JobTitle field if non-nil, zero value otherwise.

### GetJobTitleOk

`func (o *Employee) GetJobTitleOk() (*string, bool)`

GetJobTitleOk returns a tuple with the JobTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobTitle

`func (o *Employee) SetJobTitle(v string)`

SetJobTitle sets JobTitle field to given value.

### HasJobTitle

`func (o *Employee) HasJobTitle() bool`

HasJobTitle returns a boolean if a field has been set.

### GetLastLogin

`func (o *Employee) GetLastLogin() time.Time`

GetLastLogin returns the LastLogin field if non-nil, zero value otherwise.

### GetLastLoginOk

`func (o *Employee) GetLastLoginOk() (*time.Time, bool)`

GetLastLoginOk returns a tuple with the LastLogin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastLogin

`func (o *Employee) SetLastLogin(v time.Time)`

SetLastLogin sets LastLogin field to given value.

### HasLastLogin

`func (o *Employee) HasLastLogin() bool`

HasLastLogin returns a boolean if a field has been set.

### SetLastLoginNil

`func (o *Employee) SetLastLoginNil(b bool)`

 SetLastLoginNil sets the value for LastLogin to be an explicit nil

### UnsetLastLogin
`func (o *Employee) UnsetLastLogin()`

UnsetLastLogin ensures that no value is present for LastLogin, not even an explicit nil
### GetLastName

`func (o *Employee) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *Employee) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *Employee) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *Employee) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetLastUpdated

`func (o *Employee) GetLastUpdated() time.Time`

GetLastUpdated returns the LastUpdated field if non-nil, zero value otherwise.

### GetLastUpdatedOk

`func (o *Employee) GetLastUpdatedOk() (*time.Time, bool)`

GetLastUpdatedOk returns a tuple with the LastUpdated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdated

`func (o *Employee) SetLastUpdated(v time.Time)`

SetLastUpdated sets LastUpdated field to given value.

### HasLastUpdated

`func (o *Employee) HasLastUpdated() bool`

HasLastUpdated returns a boolean if a field has been set.

### SetLastUpdatedNil

`func (o *Employee) SetLastUpdatedNil(b bool)`

 SetLastUpdatedNil sets the value for LastUpdated to be an explicit nil

### UnsetLastUpdated
`func (o *Employee) UnsetLastUpdated()`

UnsetLastUpdated ensures that no value is present for LastUpdated, not even an explicit nil
### GetMonthlySalary

`func (o *Employee) GetMonthlySalary() string`

GetMonthlySalary returns the MonthlySalary field if non-nil, zero value otherwise.

### GetMonthlySalaryOk

`func (o *Employee) GetMonthlySalaryOk() (*string, bool)`

GetMonthlySalaryOk returns a tuple with the MonthlySalary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlySalary

`func (o *Employee) SetMonthlySalary(v string)`

SetMonthlySalary sets MonthlySalary field to given value.

### HasMonthlySalary

`func (o *Employee) HasMonthlySalary() bool`

HasMonthlySalary returns a boolean if a field has been set.

### SetMonthlySalaryNil

`func (o *Employee) SetMonthlySalaryNil(b bool)`

 SetMonthlySalaryNil sets the value for MonthlySalary to be an explicit nil

### UnsetMonthlySalary
`func (o *Employee) UnsetMonthlySalary()`

UnsetMonthlySalary ensures that no value is present for MonthlySalary, not even an explicit nil
### GetPhone

`func (o *Employee) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *Employee) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *Employee) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *Employee) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *Employee) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *Employee) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetState

`func (o *Employee) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *Employee) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *Employee) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *Employee) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *Employee) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *Employee) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetStatus

`func (o *Employee) GetStatus() EmployeeStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *Employee) GetStatusOk() (*EmployeeStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *Employee) SetStatus(v EmployeeStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *Employee) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTenantId

`func (o *Employee) GetTenantId() string`

GetTenantId returns the TenantId field if non-nil, zero value otherwise.

### GetTenantIdOk

`func (o *Employee) GetTenantIdOk() (*string, bool)`

GetTenantIdOk returns a tuple with the TenantId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTenantId

`func (o *Employee) SetTenantId(v string)`

SetTenantId sets TenantId field to given value.

### HasTenantId

`func (o *Employee) HasTenantId() bool`

HasTenantId returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *Employee) GetUpdatedAt() time.Time`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Employee) GetUpdatedAtOk() (*time.Time, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Employee) SetUpdatedAt(v time.Time)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Employee) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *Employee) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *Employee) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetUserId

`func (o *Employee) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *Employee) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *Employee) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *Employee) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### SetUserIdNil

`func (o *Employee) SetUserIdNil(b bool)`

 SetUserIdNil sets the value for UserId to be an explicit nil

### UnsetUserId
`func (o *Employee) UnsetUserId()`

UnsetUserId ensures that no value is present for UserId, not even an explicit nil
### GetWeeklyHours

`func (o *Employee) GetWeeklyHours() string`

GetWeeklyHours returns the WeeklyHours field if non-nil, zero value otherwise.

### GetWeeklyHoursOk

`func (o *Employee) GetWeeklyHoursOk() (*string, bool)`

GetWeeklyHoursOk returns a tuple with the WeeklyHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeeklyHours

`func (o *Employee) SetWeeklyHours(v string)`

SetWeeklyHours sets WeeklyHours field to given value.

### HasWeeklyHours

`func (o *Employee) HasWeeklyHours() bool`

HasWeeklyHours returns a boolean if a field has been set.

### SetWeeklyHoursNil

`func (o *Employee) SetWeeklyHoursNil(b bool)`

 SetWeeklyHoursNil sets the value for WeeklyHours to be an explicit nil

### UnsetWeeklyHours
`func (o *Employee) UnsetWeeklyHours()`

UnsetWeeklyHours ensures that no value is present for WeeklyHours, not even an explicit nil
### GetZip

`func (o *Employee) GetZip() string`

GetZip returns the Zip field if non-nil, zero value otherwise.

### GetZipOk

`func (o *Employee) GetZipOk() (*string, bool)`

GetZipOk returns a tuple with the Zip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZip

`func (o *Employee) SetZip(v string)`

SetZip sets Zip field to given value.

### HasZip

`func (o *Employee) HasZip() bool`

HasZip returns a boolean if a field has been set.

### SetZipNil

`func (o *Employee) SetZipNil(b bool)`

 SetZipNil sets the value for Zip to be an explicit nil

### UnsetZip
`func (o *Employee) UnsetZip()`

UnsetZip ensures that no value is present for Zip, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


