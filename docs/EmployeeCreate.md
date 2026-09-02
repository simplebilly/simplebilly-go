# EmployeeCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Address** | Pointer to **NullableString** |  | [optional] 
**BackupEmployeeId** | Pointer to **NullableString** | References another employee who covers when this employee is absent. | [optional] 
**Bic** | Pointer to **NullableString** |  | [optional] 
**City** | Pointer to **NullableString** |  | [optional] 
**Country** | Pointer to [**NullableCountryCode**](CountryCode.md) |  | [optional] 
**DateOfBirth** | Pointer to **NullableString** |  | [optional] 
**DepartmentId** | Pointer to **string** | References the department entity. | [optional] 
**Email** | Pointer to **string** |  | [optional] 
**FirstName** | Pointer to **string** |  | [optional] 
**Gender** | Pointer to [**NullableGender**](Gender.md) | Gender for pay-transparency reporting: \&quot;male\&quot;, \&quot;female\&quot; or \&quot;diverse\&quot;. | [optional] 
**HireDate** | Pointer to **NullableString** |  | [optional] 
**HourlyCost** | Pointer to **NullableString** | Hourly cost rate in EUR for labor-cost reporting; when unset the rate is derived from &#x60;monthly_salary / (weekly_hours * 4.33)&#x60;. | [optional] 
**Iban** | Pointer to **NullableString** |  | [optional] 
**JobTitle** | Pointer to **string** |  | [optional] 
**LastLogin** | Pointer to **NullableTime** |  | [optional] 
**LastName** | Pointer to **string** |  | [optional] 
**LastUpdated** | Pointer to **NullableTime** |  | [optional] 
**MonthlySalary** | Pointer to **NullableString** | Gross monthly salary in EUR for pay-transparency reporting. | [optional] 
**Phone** | Pointer to **NullableString** |  | [optional] 
**State** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to [**EmployeeStatus**](EmployeeStatus.md) |  | [optional] 
**UserId** | Pointer to **NullableString** | References the user entity. | [optional] 
**WeeklyHours** | Pointer to **NullableString** | Contractual weekly working hours for pay-transparency normalization. | [optional] 
**Zip** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewEmployeeCreate

`func NewEmployeeCreate() *EmployeeCreate`

NewEmployeeCreate instantiates a new EmployeeCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEmployeeCreateWithDefaults

`func NewEmployeeCreateWithDefaults() *EmployeeCreate`

NewEmployeeCreateWithDefaults instantiates a new EmployeeCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAddress

`func (o *EmployeeCreate) GetAddress() string`

GetAddress returns the Address field if non-nil, zero value otherwise.

### GetAddressOk

`func (o *EmployeeCreate) GetAddressOk() (*string, bool)`

GetAddressOk returns a tuple with the Address field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddress

`func (o *EmployeeCreate) SetAddress(v string)`

SetAddress sets Address field to given value.

### HasAddress

`func (o *EmployeeCreate) HasAddress() bool`

HasAddress returns a boolean if a field has been set.

### SetAddressNil

`func (o *EmployeeCreate) SetAddressNil(b bool)`

 SetAddressNil sets the value for Address to be an explicit nil

### UnsetAddress
`func (o *EmployeeCreate) UnsetAddress()`

UnsetAddress ensures that no value is present for Address, not even an explicit nil
### GetBackupEmployeeId

`func (o *EmployeeCreate) GetBackupEmployeeId() string`

GetBackupEmployeeId returns the BackupEmployeeId field if non-nil, zero value otherwise.

### GetBackupEmployeeIdOk

`func (o *EmployeeCreate) GetBackupEmployeeIdOk() (*string, bool)`

GetBackupEmployeeIdOk returns a tuple with the BackupEmployeeId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBackupEmployeeId

`func (o *EmployeeCreate) SetBackupEmployeeId(v string)`

SetBackupEmployeeId sets BackupEmployeeId field to given value.

### HasBackupEmployeeId

`func (o *EmployeeCreate) HasBackupEmployeeId() bool`

HasBackupEmployeeId returns a boolean if a field has been set.

### SetBackupEmployeeIdNil

`func (o *EmployeeCreate) SetBackupEmployeeIdNil(b bool)`

 SetBackupEmployeeIdNil sets the value for BackupEmployeeId to be an explicit nil

### UnsetBackupEmployeeId
`func (o *EmployeeCreate) UnsetBackupEmployeeId()`

UnsetBackupEmployeeId ensures that no value is present for BackupEmployeeId, not even an explicit nil
### GetBic

`func (o *EmployeeCreate) GetBic() string`

GetBic returns the Bic field if non-nil, zero value otherwise.

### GetBicOk

`func (o *EmployeeCreate) GetBicOk() (*string, bool)`

GetBicOk returns a tuple with the Bic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBic

`func (o *EmployeeCreate) SetBic(v string)`

SetBic sets Bic field to given value.

### HasBic

`func (o *EmployeeCreate) HasBic() bool`

HasBic returns a boolean if a field has been set.

### SetBicNil

`func (o *EmployeeCreate) SetBicNil(b bool)`

 SetBicNil sets the value for Bic to be an explicit nil

### UnsetBic
`func (o *EmployeeCreate) UnsetBic()`

UnsetBic ensures that no value is present for Bic, not even an explicit nil
### GetCity

`func (o *EmployeeCreate) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *EmployeeCreate) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *EmployeeCreate) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *EmployeeCreate) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *EmployeeCreate) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *EmployeeCreate) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetCountry

`func (o *EmployeeCreate) GetCountry() CountryCode`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *EmployeeCreate) GetCountryOk() (*CountryCode, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *EmployeeCreate) SetCountry(v CountryCode)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *EmployeeCreate) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *EmployeeCreate) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *EmployeeCreate) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetDateOfBirth

`func (o *EmployeeCreate) GetDateOfBirth() string`

GetDateOfBirth returns the DateOfBirth field if non-nil, zero value otherwise.

### GetDateOfBirthOk

`func (o *EmployeeCreate) GetDateOfBirthOk() (*string, bool)`

GetDateOfBirthOk returns a tuple with the DateOfBirth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDateOfBirth

`func (o *EmployeeCreate) SetDateOfBirth(v string)`

SetDateOfBirth sets DateOfBirth field to given value.

### HasDateOfBirth

`func (o *EmployeeCreate) HasDateOfBirth() bool`

HasDateOfBirth returns a boolean if a field has been set.

### SetDateOfBirthNil

`func (o *EmployeeCreate) SetDateOfBirthNil(b bool)`

 SetDateOfBirthNil sets the value for DateOfBirth to be an explicit nil

### UnsetDateOfBirth
`func (o *EmployeeCreate) UnsetDateOfBirth()`

UnsetDateOfBirth ensures that no value is present for DateOfBirth, not even an explicit nil
### GetDepartmentId

`func (o *EmployeeCreate) GetDepartmentId() string`

GetDepartmentId returns the DepartmentId field if non-nil, zero value otherwise.

### GetDepartmentIdOk

`func (o *EmployeeCreate) GetDepartmentIdOk() (*string, bool)`

GetDepartmentIdOk returns a tuple with the DepartmentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartmentId

`func (o *EmployeeCreate) SetDepartmentId(v string)`

SetDepartmentId sets DepartmentId field to given value.

### HasDepartmentId

`func (o *EmployeeCreate) HasDepartmentId() bool`

HasDepartmentId returns a boolean if a field has been set.

### GetEmail

`func (o *EmployeeCreate) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *EmployeeCreate) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *EmployeeCreate) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *EmployeeCreate) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### GetFirstName

`func (o *EmployeeCreate) GetFirstName() string`

GetFirstName returns the FirstName field if non-nil, zero value otherwise.

### GetFirstNameOk

`func (o *EmployeeCreate) GetFirstNameOk() (*string, bool)`

GetFirstNameOk returns a tuple with the FirstName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFirstName

`func (o *EmployeeCreate) SetFirstName(v string)`

SetFirstName sets FirstName field to given value.

### HasFirstName

`func (o *EmployeeCreate) HasFirstName() bool`

HasFirstName returns a boolean if a field has been set.

### GetGender

`func (o *EmployeeCreate) GetGender() Gender`

GetGender returns the Gender field if non-nil, zero value otherwise.

### GetGenderOk

`func (o *EmployeeCreate) GetGenderOk() (*Gender, bool)`

GetGenderOk returns a tuple with the Gender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGender

`func (o *EmployeeCreate) SetGender(v Gender)`

SetGender sets Gender field to given value.

### HasGender

`func (o *EmployeeCreate) HasGender() bool`

HasGender returns a boolean if a field has been set.

### SetGenderNil

`func (o *EmployeeCreate) SetGenderNil(b bool)`

 SetGenderNil sets the value for Gender to be an explicit nil

### UnsetGender
`func (o *EmployeeCreate) UnsetGender()`

UnsetGender ensures that no value is present for Gender, not even an explicit nil
### GetHireDate

`func (o *EmployeeCreate) GetHireDate() string`

GetHireDate returns the HireDate field if non-nil, zero value otherwise.

### GetHireDateOk

`func (o *EmployeeCreate) GetHireDateOk() (*string, bool)`

GetHireDateOk returns a tuple with the HireDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHireDate

`func (o *EmployeeCreate) SetHireDate(v string)`

SetHireDate sets HireDate field to given value.

### HasHireDate

`func (o *EmployeeCreate) HasHireDate() bool`

HasHireDate returns a boolean if a field has been set.

### SetHireDateNil

`func (o *EmployeeCreate) SetHireDateNil(b bool)`

 SetHireDateNil sets the value for HireDate to be an explicit nil

### UnsetHireDate
`func (o *EmployeeCreate) UnsetHireDate()`

UnsetHireDate ensures that no value is present for HireDate, not even an explicit nil
### GetHourlyCost

`func (o *EmployeeCreate) GetHourlyCost() string`

GetHourlyCost returns the HourlyCost field if non-nil, zero value otherwise.

### GetHourlyCostOk

`func (o *EmployeeCreate) GetHourlyCostOk() (*string, bool)`

GetHourlyCostOk returns a tuple with the HourlyCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHourlyCost

`func (o *EmployeeCreate) SetHourlyCost(v string)`

SetHourlyCost sets HourlyCost field to given value.

### HasHourlyCost

`func (o *EmployeeCreate) HasHourlyCost() bool`

HasHourlyCost returns a boolean if a field has been set.

### SetHourlyCostNil

`func (o *EmployeeCreate) SetHourlyCostNil(b bool)`

 SetHourlyCostNil sets the value for HourlyCost to be an explicit nil

### UnsetHourlyCost
`func (o *EmployeeCreate) UnsetHourlyCost()`

UnsetHourlyCost ensures that no value is present for HourlyCost, not even an explicit nil
### GetIban

`func (o *EmployeeCreate) GetIban() string`

GetIban returns the Iban field if non-nil, zero value otherwise.

### GetIbanOk

`func (o *EmployeeCreate) GetIbanOk() (*string, bool)`

GetIbanOk returns a tuple with the Iban field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIban

`func (o *EmployeeCreate) SetIban(v string)`

SetIban sets Iban field to given value.

### HasIban

`func (o *EmployeeCreate) HasIban() bool`

HasIban returns a boolean if a field has been set.

### SetIbanNil

`func (o *EmployeeCreate) SetIbanNil(b bool)`

 SetIbanNil sets the value for Iban to be an explicit nil

### UnsetIban
`func (o *EmployeeCreate) UnsetIban()`

UnsetIban ensures that no value is present for Iban, not even an explicit nil
### GetJobTitle

`func (o *EmployeeCreate) GetJobTitle() string`

GetJobTitle returns the JobTitle field if non-nil, zero value otherwise.

### GetJobTitleOk

`func (o *EmployeeCreate) GetJobTitleOk() (*string, bool)`

GetJobTitleOk returns a tuple with the JobTitle field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJobTitle

`func (o *EmployeeCreate) SetJobTitle(v string)`

SetJobTitle sets JobTitle field to given value.

### HasJobTitle

`func (o *EmployeeCreate) HasJobTitle() bool`

HasJobTitle returns a boolean if a field has been set.

### GetLastLogin

`func (o *EmployeeCreate) GetLastLogin() time.Time`

GetLastLogin returns the LastLogin field if non-nil, zero value otherwise.

### GetLastLoginOk

`func (o *EmployeeCreate) GetLastLoginOk() (*time.Time, bool)`

GetLastLoginOk returns a tuple with the LastLogin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastLogin

`func (o *EmployeeCreate) SetLastLogin(v time.Time)`

SetLastLogin sets LastLogin field to given value.

### HasLastLogin

`func (o *EmployeeCreate) HasLastLogin() bool`

HasLastLogin returns a boolean if a field has been set.

### SetLastLoginNil

`func (o *EmployeeCreate) SetLastLoginNil(b bool)`

 SetLastLoginNil sets the value for LastLogin to be an explicit nil

### UnsetLastLogin
`func (o *EmployeeCreate) UnsetLastLogin()`

UnsetLastLogin ensures that no value is present for LastLogin, not even an explicit nil
### GetLastName

`func (o *EmployeeCreate) GetLastName() string`

GetLastName returns the LastName field if non-nil, zero value otherwise.

### GetLastNameOk

`func (o *EmployeeCreate) GetLastNameOk() (*string, bool)`

GetLastNameOk returns a tuple with the LastName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastName

`func (o *EmployeeCreate) SetLastName(v string)`

SetLastName sets LastName field to given value.

### HasLastName

`func (o *EmployeeCreate) HasLastName() bool`

HasLastName returns a boolean if a field has been set.

### GetLastUpdated

`func (o *EmployeeCreate) GetLastUpdated() time.Time`

GetLastUpdated returns the LastUpdated field if non-nil, zero value otherwise.

### GetLastUpdatedOk

`func (o *EmployeeCreate) GetLastUpdatedOk() (*time.Time, bool)`

GetLastUpdatedOk returns a tuple with the LastUpdated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastUpdated

`func (o *EmployeeCreate) SetLastUpdated(v time.Time)`

SetLastUpdated sets LastUpdated field to given value.

### HasLastUpdated

`func (o *EmployeeCreate) HasLastUpdated() bool`

HasLastUpdated returns a boolean if a field has been set.

### SetLastUpdatedNil

`func (o *EmployeeCreate) SetLastUpdatedNil(b bool)`

 SetLastUpdatedNil sets the value for LastUpdated to be an explicit nil

### UnsetLastUpdated
`func (o *EmployeeCreate) UnsetLastUpdated()`

UnsetLastUpdated ensures that no value is present for LastUpdated, not even an explicit nil
### GetMonthlySalary

`func (o *EmployeeCreate) GetMonthlySalary() string`

GetMonthlySalary returns the MonthlySalary field if non-nil, zero value otherwise.

### GetMonthlySalaryOk

`func (o *EmployeeCreate) GetMonthlySalaryOk() (*string, bool)`

GetMonthlySalaryOk returns a tuple with the MonthlySalary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMonthlySalary

`func (o *EmployeeCreate) SetMonthlySalary(v string)`

SetMonthlySalary sets MonthlySalary field to given value.

### HasMonthlySalary

`func (o *EmployeeCreate) HasMonthlySalary() bool`

HasMonthlySalary returns a boolean if a field has been set.

### SetMonthlySalaryNil

`func (o *EmployeeCreate) SetMonthlySalaryNil(b bool)`

 SetMonthlySalaryNil sets the value for MonthlySalary to be an explicit nil

### UnsetMonthlySalary
`func (o *EmployeeCreate) UnsetMonthlySalary()`

UnsetMonthlySalary ensures that no value is present for MonthlySalary, not even an explicit nil
### GetPhone

`func (o *EmployeeCreate) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *EmployeeCreate) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *EmployeeCreate) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *EmployeeCreate) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *EmployeeCreate) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *EmployeeCreate) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetState

`func (o *EmployeeCreate) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *EmployeeCreate) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *EmployeeCreate) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *EmployeeCreate) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *EmployeeCreate) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *EmployeeCreate) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetStatus

`func (o *EmployeeCreate) GetStatus() EmployeeStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *EmployeeCreate) GetStatusOk() (*EmployeeStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *EmployeeCreate) SetStatus(v EmployeeStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *EmployeeCreate) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetUserId

`func (o *EmployeeCreate) GetUserId() string`

GetUserId returns the UserId field if non-nil, zero value otherwise.

### GetUserIdOk

`func (o *EmployeeCreate) GetUserIdOk() (*string, bool)`

GetUserIdOk returns a tuple with the UserId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserId

`func (o *EmployeeCreate) SetUserId(v string)`

SetUserId sets UserId field to given value.

### HasUserId

`func (o *EmployeeCreate) HasUserId() bool`

HasUserId returns a boolean if a field has been set.

### SetUserIdNil

`func (o *EmployeeCreate) SetUserIdNil(b bool)`

 SetUserIdNil sets the value for UserId to be an explicit nil

### UnsetUserId
`func (o *EmployeeCreate) UnsetUserId()`

UnsetUserId ensures that no value is present for UserId, not even an explicit nil
### GetWeeklyHours

`func (o *EmployeeCreate) GetWeeklyHours() string`

GetWeeklyHours returns the WeeklyHours field if non-nil, zero value otherwise.

### GetWeeklyHoursOk

`func (o *EmployeeCreate) GetWeeklyHoursOk() (*string, bool)`

GetWeeklyHoursOk returns a tuple with the WeeklyHours field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWeeklyHours

`func (o *EmployeeCreate) SetWeeklyHours(v string)`

SetWeeklyHours sets WeeklyHours field to given value.

### HasWeeklyHours

`func (o *EmployeeCreate) HasWeeklyHours() bool`

HasWeeklyHours returns a boolean if a field has been set.

### SetWeeklyHoursNil

`func (o *EmployeeCreate) SetWeeklyHoursNil(b bool)`

 SetWeeklyHoursNil sets the value for WeeklyHours to be an explicit nil

### UnsetWeeklyHours
`func (o *EmployeeCreate) UnsetWeeklyHours()`

UnsetWeeklyHours ensures that no value is present for WeeklyHours, not even an explicit nil
### GetZip

`func (o *EmployeeCreate) GetZip() string`

GetZip returns the Zip field if non-nil, zero value otherwise.

### GetZipOk

`func (o *EmployeeCreate) GetZipOk() (*string, bool)`

GetZipOk returns a tuple with the Zip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZip

`func (o *EmployeeCreate) SetZip(v string)`

SetZip sets Zip field to given value.

### HasZip

`func (o *EmployeeCreate) HasZip() bool`

HasZip returns a boolean if a field has been set.

### SetZipNil

`func (o *EmployeeCreate) SetZipNil(b bool)`

 SetZipNil sets the value for Zip to be an explicit nil

### UnsetZip
`func (o *EmployeeCreate) UnsetZip()`

UnsetZip ensures that no value is present for Zip, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


