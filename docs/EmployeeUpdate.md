# EmployeeUpdate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **NullableString** |  | [optional] 
**BackupEmployeeId** | Pointer to **NullableString** | References another employee who covers when this employee is absent. | [optional] 
**Bic** | Pointer to **NullableString** |  | [optional] 
**City** | Pointer to **NullableString** |  | [optional] 
**Country** | Pointer to [**NullableCountryCode**](CountryCode.md) |  | [optional] 
**DateOfBirth** | Pointer to **NullableString** |  | [optional] 
**DepartmentId** | Pointer to **NullableString** | References the department entity. | [optional] 
**Email** | Pointer to **NullableString** |  | [optional] 
**FirstName** | Pointer to **NullableString** |  | [optional] 
**Gender** | Pointer to [**NullableGender**](Gender.md) | Gender for pay-transparency reporting: \&quot;male\&quot;, \&quot;female\&quot; or \&quot;diverse\&quot;. | [optional] 
**HireDate** | Pointer to **NullableString** |  | [optional] 
**HourlyCost** | Pointer to **NullableString** | Hourly cost rate in EUR for labor-cost reporting; when unset the rate is derived from &#x60;monthly_salary / (weekly_hours * 4.33)&#x60;. | [optional] 
**Iban** | Pointer to **NullableString** |  | [optional] 
**JobTitle** | Pointer to **NullableString** |  | [optional] 
**LastLogin** | Pointer to **NullableTime** |  | [optional] 
**LastName** | Pointer to **NullableString** |  | [optional] 
**LastUpdated** | Pointer to **NullableTime** |  | [optional] 
**MonthlySalary** | Pointer to **NullableString** | Gross monthly salary in EUR for pay-transparency reporting. | [optional] 
**Phone** | Pointer to **NullableString** |  | [optional] 
**State** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to [**NullableEmployeeStatus**](EmployeeStatus.md) |  | [optional] 
**UserId** | Pointer to **NullableString** | References the user entity. | [optional] 
**WeeklyHours** | Pointer to **NullableString** | Contractual weekly working hours for pay-transparency normalization. | [optional] 
**Zip** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewEmployeeUpdate

`func NewEmployeeUpdate() *EmployeeUpdate`

NewEmployeeUpdate instantiates a new EmployeeUpdate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmployeeUpdateWithDefaults

`func NewEmployeeUpdateWithDefaults() *EmployeeUpdate`

NewEmployeeUpdateWithDefaults instantiates a new EmployeeUpdate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *EmployeeUpdate) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *EmployeeUpdate) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *EmployeeUpdate) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *EmployeeUpdate) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *EmployeeUpdate) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *EmployeeUpdate) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetBackupEmployeeId

`func (o *EmployeeUpdate) GetBackupEmployeeId() string`

GetBackupEmployeeId returns the BackupEmployeeId field if non-nil, zero value otherwise.

### GetBackupEmployeeIdOk

`func (o *EmployeeUpdate) GetBackupEmployeeIdOk() (*string, bool)`

GetBackupEmployeeIdOk returns a tuple with the BackupEmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackupEmployeeId

`func (o *EmployeeUpdate) SetBackupEmployeeId(v string)`

SetBackupEmployeeId sets BackupEmployeeId field to given value.

### HasBackupEmployeeId

`func (o *EmployeeUpdate) HasBackupEmployeeId() bool`

HasBackupEmployeeId returns a boolean if a field has been set.

### SetBackupEmployeeIdNil

`func (o *EmployeeUpdate) SetBackupEmployeeIdNil(b bool)`

 SetBackupEmployeeIdNil sets the value for BackupEmployeeId to be an explicit nil

### UnsetBackupEmployeeId
`func (o *EmployeeUpdate) UnsetBackupEmployeeId()`

UnsetBackupEmployeeId ensures that no value is present for BackupEmployeeId, not even an explicit nil
### GetBic

`func (o *EmployeeUpdate) GetBic() string`

GetBic returns the Bic field if non-nil, zero value otherwise.

### GetBicOk

`func (o *EmployeeUpdate) GetBicOk() (*string, bool)`

GetBicOk returns a tuple with the Bic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBic

`func (o *EmployeeUpdate) SetBic(v string)`

SetBic sets Bic field to given value.

### HasBic

`func (o *EmployeeUpdate) HasBic() bool`

HasBic returns a boolean if a field has been set.

### SetBicNil

`func (o *EmployeeUpdate) SetBicNil(b bool)`

 SetBicNil sets the value for Bic to be an explicit nil

### UnsetBic
`func (o *EmployeeUpdate) UnsetBic()`

UnsetBic ensures that no value is present for Bic, not even an explicit nil
### GetCity

`func (o *EmployeeUpdate) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *EmployeeUpdate) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *EmployeeUpdate) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *EmployeeUpdate) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *EmployeeUpdate) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *EmployeeUpdate) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetCountry

`func (o *EmployeeUpdate) GetCountry() CountryCode`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *EmployeeUpdate) GetCountryOk() (*CountryCode, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *EmployeeUpdate) SetCountry(v CountryCode)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *EmployeeUpdate) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *EmployeeUpdate) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *EmployeeUpdate) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetDateOfBirth

`func (o *EmployeeUpdate) GetDateOfBirth() string`

GetDateOfBirth returns the DateOfBirth field if non-nil, zero value otherwise.

### GetDateOfBirthOk

`func (o *EmployeeUpdate) GetDateOfBirthOk() (*string, bool)`

GetDateOfBirthOk returns a tuple with the DateOfBirth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateOfBirth

`func (o *EmployeeUpdate) SetDateOfBirth(v string)`

SetDateOfBirth sets DateOfBirth field to given value.

### HasDateOfBirth

`func (o *EmployeeUpdate) HasDateOfBirth() bool`

HasDateOfBirth returns a boolean if a field has been set.

### SetDateOfBirthNil

`func (o *EmployeeUpdate) SetDateOfBirthNil(b bool)`

 SetDateOfBirthNil sets the value for DateOfBirth to be an explicit nil

### UnsetDateOfBirth
`func (o *EmployeeUpdate) UnsetDateOfBirth()`

UnsetDateOfBirth ensures that no value is present for DateOfBirth, not even an explicit nil
### GetDepartmentId

`func (o *EmployeeUpdate) GetDepartmentId() string`

GetDepartmentId returns the DepartmentId field if non-nil, zero value otherwise.

### GetDepartmentIdOk

`func (o *EmployeeUpdate) GetDepartmentIdOk() (*string, bool)`

GetDepartmentIdOk returns a tuple with the DepartmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartmentId

`func (o *EmployeeUpdate) SetDepartmentId(v string)`

SetDepartmentId sets DepartmentId field to given value.

### HasDepartmentId

`func (o *EmployeeUpdate) HasDepartmentId() bool`

HasDepartmentId returns a boolean if a field has been set.

### SetDepartmentIdNil

`func (o *EmployeeUpdate) SetDepartmentIdNil(b bool)`

 SetDepartmentIdNil sets the value for DepartmentId to be an explicit nil

### UnsetDepartmentId
`func (o *EmployeeUpdate) UnsetDepartmentId()`

UnsetDepartmentId ensures that no value is present for DepartmentId, not even an explicit nil
### GetEmail

`func (o *EmployeeUpdate) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *EmployeeUpdate) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *EmployeeUpdate) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *EmployeeUpdate) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *EmployeeUpdate) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *EmployeeUpdate) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetFirstName

`func (o *EmployeeUpdate) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *EmployeeUpdate) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *EmployeeUpdate) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *EmployeeUpdate) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### SetFirstNameNil

`func (o *EmployeeUpdate) SetFirstNameNil(b bool)`

 SetFirstNameNil sets the value for FirstName to be an explicit nil

### UnsetFirstName
`func (o *EmployeeUpdate) UnsetFirstName()`

UnsetFirstName ensures that no value is present for FirstName, not even an explicit nil
### GetGender

`func (o *EmployeeUpdate) GetGender() Gender`

GetGender returns the Gender field if non-nil, zero value otherwise.

### GetGenderOk

`func (o *EmployeeUpdate) GetGenderOk() (*Gender, bool)`

GetGenderOk returns a tuple with the Gender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGender

`func (o *EmployeeUpdate) SetGender(v Gender)`

SetGender sets Gender field to given value.

### HasGender

`func (o *EmployeeUpdate) HasGender() bool`

HasGender returns a boolean if a field has been set.

### SetGenderNil

`func (o *EmployeeUpdate) SetGenderNil(b bool)`

 SetGenderNil sets the value for Gender to be an explicit nil

### UnsetGender
`func (o *EmployeeUpdate) UnsetGender()`

UnsetGender ensures that no value is present for Gender, not even an explicit nil
### GetHireDate

`func (o *EmployeeUpdate) GetHireDate() string`

GetHireDate returns the HireDate field if non-nil, zero value otherwise.

### GetHireDateOk

`func (o *EmployeeUpdate) GetHireDateOk() (*string, bool)`

GetHireDateOk returns a tuple with the HireDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHireDate

`func (o *EmployeeUpdate) SetHireDate(v string)`

SetHireDate sets HireDate field to given value.

### HasHireDate

`func (o *EmployeeUpdate) HasHireDate() bool`

HasHireDate returns a boolean if a field has been set.

### SetHireDateNil

`func (o *EmployeeUpdate) SetHireDateNil(b bool)`

 SetHireDateNil sets the value for HireDate to be an explicit nil

### UnsetHireDate
`func (o *EmployeeUpdate) UnsetHireDate()`

UnsetHireDate ensures that no value is present for HireDate, not even an explicit nil
### GetHourlyCost

`func (o *EmployeeUpdate) GetHourlyCost() string`

GetHourlyCost returns the HourlyCost field if non-nil, zero value otherwise.

### GetHourlyCostOk

`func (o *EmployeeUpdate) GetHourlyCostOk() (*string, bool)`

GetHourlyCostOk returns a tuple with the HourlyCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHourlyCost

`func (o *EmployeeUpdate) SetHourlyCost(v string)`

SetHourlyCost sets HourlyCost field to given value.

### HasHourlyCost

`func (o *EmployeeUpdate) HasHourlyCost() bool`

HasHourlyCost returns a boolean if a field has been set.

### SetHourlyCostNil

`func (o *EmployeeUpdate) SetHourlyCostNil(b bool)`

 SetHourlyCostNil sets the value for HourlyCost to be an explicit nil

### UnsetHourlyCost
`func (o *EmployeeUpdate) UnsetHourlyCost()`

UnsetHourlyCost ensures that no value is present for HourlyCost, not even an explicit nil
### GetIban

`func (o *EmployeeUpdate) GetIban() string`

GetIban returns the Iban field if non-nil, zero value otherwise.

### GetIbanOk

`func (o *EmployeeUpdate) GetIbanOk() (*string, bool)`

GetIbanOk returns a tuple with the Iban field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIban

`func (o *EmployeeUpdate) SetIban(v string)`

SetIban sets Iban field to given value.

### HasIban

`func (o *EmployeeUpdate) HasIban() bool`

HasIban returns a boolean if a field has been set.

### SetIbanNil

`func (o *EmployeeUpdate) SetIbanNil(b bool)`

 SetIbanNil sets the value for Iban to be an explicit nil

### UnsetIban
`func (o *EmployeeUpdate) UnsetIban()`

UnsetIban ensures that no value is present for Iban, not even an explicit nil
### GetJobTitle

`func (o *EmployeeUpdate) GetJobTitle() string`

GetJobTitle returns the JobTitle field if non-nil, zero value otherwise.

### GetJobTitleOk

`func (o *EmployeeUpdate) GetJobTitleOk() (*string, bool)`

GetJobTitleOk returns a tuple with the JobTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobTitle

`func (o *EmployeeUpdate) SetJobTitle(v string)`

SetJobTitle sets JobTitle field to given value.

### HasJobTitle

`func (o *EmployeeUpdate) HasJobTitle() bool`

HasJobTitle returns a boolean if a field has been set.

### SetJobTitleNil

`func (o *EmployeeUpdate) SetJobTitleNil(b bool)`

 SetJobTitleNil sets the value for JobTitle to be an explicit nil

### UnsetJobTitle
`func (o *EmployeeUpdate) UnsetJobTitle()`

UnsetJobTitle ensures that no value is present for JobTitle, not even an explicit nil
### GetLastLogin

`func (o *EmployeeUpdate) GetLastLogin() time.Time`

GetLastLogin returns the LastLogin field if non-nil, zero value otherwise.

### GetLastLoginOk

`func (o *EmployeeUpdate) GetLastLoginOk() (*time.Time, bool)`

GetLastLoginOk returns a tuple with the LastLogin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastLogin

`func (o *EmployeeUpdate) SetLastLogin(v time.Time)`

SetLastLogin sets LastLogin field to given value.

### HasLastLogin

`func (o *EmployeeUpdate) HasLastLogin() bool`

HasLastLogin returns a boolean if a field has been set.

### SetLastLoginNil

`func (o *EmployeeUpdate) SetLastLoginNil(b bool)`

 SetLastLoginNil sets the value for LastLogin to be an explicit nil

### UnsetLastLogin
`func (o *EmployeeUpdate) UnsetLastLogin()`

UnsetLastLogin ensures that no value is present for LastLogin, not even an explicit nil
### GetLastName

`func (o *EmployeeUpdate) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *EmployeeUpdate) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *EmployeeUpdate) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *EmployeeUpdate) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### SetLastNameNil

`func (o *EmployeeUpdate) SetLastNameNil(b bool)`

 SetLastNameNil sets the value for LastName to be an explicit nil

### UnsetLastName
`func (o *EmployeeUpdate) UnsetLastName()`

UnsetLastName ensures that no value is present for LastName, not even an explicit nil
### GetLastUpdated

`func (o *EmployeeUpdate) GetLastUpdated() time.Time`

GetLastUpdated returns the LastUpdated field if non-nil, zero value otherwise.

### GetLastUpdatedOk

`func (o *EmployeeUpdate) GetLastUpdatedOk() (*time.Time, bool)`

GetLastUpdatedOk returns a tuple with the LastUpdated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdated

`func (o *EmployeeUpdate) SetLastUpdated(v time.Time)`

SetLastUpdated sets LastUpdated field to given value.

### HasLastUpdated

`func (o *EmployeeUpdate) HasLastUpdated() bool`

HasLastUpdated returns a boolean if a field has been set.

### SetLastUpdatedNil

`func (o *EmployeeUpdate) SetLastUpdatedNil(b bool)`

 SetLastUpdatedNil sets the value for LastUpdated to be an explicit nil

### UnsetLastUpdated
`func (o *EmployeeUpdate) UnsetLastUpdated()`

UnsetLastUpdated ensures that no value is present for LastUpdated, not even an explicit nil
### GetMonthlySalary

`func (o *EmployeeUpdate) GetMonthlySalary() string`

GetMonthlySalary returns the MonthlySalary field if non-nil, zero value otherwise.

### GetMonthlySalaryOk

`func (o *EmployeeUpdate) GetMonthlySalaryOk() (*string, bool)`

GetMonthlySalaryOk returns a tuple with the MonthlySalary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlySalary

`func (o *EmployeeUpdate) SetMonthlySalary(v string)`

SetMonthlySalary sets MonthlySalary field to given value.

### HasMonthlySalary

`func (o *EmployeeUpdate) HasMonthlySalary() bool`

HasMonthlySalary returns a boolean if a field has been set.

### SetMonthlySalaryNil

`func (o *EmployeeUpdate) SetMonthlySalaryNil(b bool)`

 SetMonthlySalaryNil sets the value for MonthlySalary to be an explicit nil

### UnsetMonthlySalary
`func (o *EmployeeUpdate) UnsetMonthlySalary()`

UnsetMonthlySalary ensures that no value is present for MonthlySalary, not even an explicit nil
### GetPhone

`func (o *EmployeeUpdate) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *EmployeeUpdate) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *EmployeeUpdate) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *EmployeeUpdate) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *EmployeeUpdate) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *EmployeeUpdate) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetState

`func (o *EmployeeUpdate) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *EmployeeUpdate) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *EmployeeUpdate) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *EmployeeUpdate) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *EmployeeUpdate) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *EmployeeUpdate) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetStatus

`func (o *EmployeeUpdate) GetStatus() EmployeeStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EmployeeUpdate) GetStatusOk() (*EmployeeStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EmployeeUpdate) SetStatus(v EmployeeStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *EmployeeUpdate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### SetStatusNil

`func (o *EmployeeUpdate) SetStatusNil(b bool)`

 SetStatusNil sets the value for Status to be an explicit nil

### UnsetStatus
`func (o *EmployeeUpdate) UnsetStatus()`

UnsetStatus ensures that no value is present for Status, not even an explicit nil
### GetUserId

`func (o *EmployeeUpdate) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *EmployeeUpdate) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *EmployeeUpdate) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *EmployeeUpdate) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### SetUserIdNil

`func (o *EmployeeUpdate) SetUserIdNil(b bool)`

 SetUserIdNil sets the value for UserId to be an explicit nil

### UnsetUserId
`func (o *EmployeeUpdate) UnsetUserId()`

UnsetUserId ensures that no value is present for UserId, not even an explicit nil
### GetWeeklyHours

`func (o *EmployeeUpdate) GetWeeklyHours() string`

GetWeeklyHours returns the WeeklyHours field if non-nil, zero value otherwise.

### GetWeeklyHoursOk

`func (o *EmployeeUpdate) GetWeeklyHoursOk() (*string, bool)`

GetWeeklyHoursOk returns a tuple with the WeeklyHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeeklyHours

`func (o *EmployeeUpdate) SetWeeklyHours(v string)`

SetWeeklyHours sets WeeklyHours field to given value.

### HasWeeklyHours

`func (o *EmployeeUpdate) HasWeeklyHours() bool`

HasWeeklyHours returns a boolean if a field has been set.

### SetWeeklyHoursNil

`func (o *EmployeeUpdate) SetWeeklyHoursNil(b bool)`

 SetWeeklyHoursNil sets the value for WeeklyHours to be an explicit nil

### UnsetWeeklyHours
`func (o *EmployeeUpdate) UnsetWeeklyHours()`

UnsetWeeklyHours ensures that no value is present for WeeklyHours, not even an explicit nil
### GetZip

`func (o *EmployeeUpdate) GetZip() string`

GetZip returns the Zip field if non-nil, zero value otherwise.

### GetZipOk

`func (o *EmployeeUpdate) GetZipOk() (*string, bool)`

GetZipOk returns a tuple with the Zip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZip

`func (o *EmployeeUpdate) SetZip(v string)`

SetZip sets Zip field to given value.

### HasZip

`func (o *EmployeeUpdate) HasZip() bool`

HasZip returns a boolean if a field has been set.

### SetZipNil

`func (o *EmployeeUpdate) SetZipNil(b bool)`

 SetZipNil sets the value for Zip to be an explicit nil

### UnsetZip
`func (o *EmployeeUpdate) UnsetZip()`

UnsetZip ensures that no value is present for Zip, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


