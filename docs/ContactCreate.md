# ContactCreate

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccountHolder** | Pointer to **NullableString** |  | [optional] 
**AcquisitionCost** | Pointer to **NullableString** |  | [optional] 
**AddressSupplement** | Pointer to **NullableString** |  | [optional] 
**Attention** | Pointer to **NullableString** |  | [optional] 
**BankName** | Pointer to **NullableString** |  | [optional] 
**Bic** | Pointer to **NullableString** |  | [optional] 
**BuyerReference** | Pointer to **NullableString** |  | [optional] 
**Category** | Pointer to **NullableString** |  | [optional] 
**CertificateAuthority** | Pointer to **NullableString** |  | [optional] 
**CertificateNumber** | Pointer to **NullableString** |  | [optional] 
**CertificateParagraph** | Pointer to **NullableString** |  | [optional] 
**CertificateValidUntil** | Pointer to **NullableString** |  | [optional] 
**City** | Pointer to **NullableString** |  | [optional] 
**CompanyName** | Pointer to **NullableString** |  | [optional] 
**ContactPersons** | Pointer to **interface{}** |  | [optional] 
**ContactType** | [**ContactType**](ContactType.md) |  | 
**Country** | Pointer to [**NullableCountryCode**](CountryCode.md) |  | [optional] 
**CreditLimit** | Pointer to **NullableString** |  | [optional] 
**CreditorAccountSkr03** | Pointer to **NullableString** |  | [optional] 
**CreditorAccountSkr04** | Pointer to **NullableString** |  | [optional] 
**Currency** | Pointer to **NullableString** |  | [optional] 
**CustomFields** | Pointer to **interface{}** |  | [optional] 
**CustomerNumber** | Pointer to **NullableString** |  | [optional] 
**DebitorAccountSkr03** | Pointer to **NullableString** |  | [optional] 
**DebitorAccountSkr04** | Pointer to **NullableString** |  | [optional] 
**DefaultDebitorNumber** | Pointer to **NullableString** |  | [optional] 
**DeliveryBlock** | Pointer to **NullableBool** |  | [optional] 
**Department** | Pointer to **NullableString** |  | [optional] 
**DiscountDays** | Pointer to **NullableInt32** |  | [optional] 
**DiscountPercentage** | Pointer to **NullableString** |  | [optional] 
**DonationReceiptEligible** | Pointer to **NullableBool** |  | [optional] 
**Email** | Pointer to **NullableString** |  | [optional] 
**ExternalId** | Pointer to **NullableString** |  | [optional] 
**Fax** | Pointer to **NullableString** |  | [optional] 
**Iban** | Pointer to **NullableString** |  | [optional] 
**Industry** | Pointer to **NullableString** |  | [optional] 
**IsActive** | Pointer to **NullableBool** |  | [optional] 
**IsMember** | Pointer to **NullableBool** |  | [optional] 
**IsNonprofit** | Pointer to **NullableBool** |  | [optional] 
**LastContactDate** | Pointer to **NullableString** |  | [optional] 
**LastPurchaseDate** | Pointer to **NullableString** |  | [optional] 
**LeitwegId** | Pointer to **NullableString** |  | [optional] 
**LifetimeValue** | Pointer to **NullableString** |  | [optional] 
**MandateDate** | Pointer to **NullableString** |  | [optional] 
**MandateReference** | Pointer to **NullableString** |  | [optional] 
**MarketingConsent** | Pointer to **NullableBool** |  | [optional] 
**MarketingConsentAt** | Pointer to **NullableTime** |  | [optional] 
**MarketingConsentSource** | Pointer to **NullableString** |  | [optional] 
**Mobile** | Pointer to **NullableString** |  | [optional] 
**Name** | **string** |  | 
**NextContactDate** | Pointer to **NullableString** |  | [optional] 
**Notes** | Pointer to **NullableString** |  | [optional] 
**OpeningBalance** | Pointer to **NullableString** |  | [optional] 
**OpeningBalanceDate** | Pointer to **NullableString** |  | [optional] 
**OrderReference** | Pointer to **NullableString** |  | [optional] 
**PaymentBlock** | Pointer to **NullableBool** |  | [optional] 
**PaymentGracePeriodDays** | Pointer to **NullableInt32** |  | [optional] 
**PaymentMethods** | Pointer to **[]string** |  | [optional] 
**PaymentTerms** | Pointer to **NullableString** |  | [optional] 
**Phone** | Pointer to **NullableString** |  | [optional] 
**Rating** | Pointer to **NullableInt32** |  | [optional] 
**SalesRepresentative** | Pointer to **NullableString** |  | [optional] 
**SepaBatchBooking** | Pointer to **NullableBool** |  | [optional] 
**SepaSequenceType** | Pointer to [**NullableSepaSequenceType**](SepaSequenceType.md) |  | [optional] 
**SocialMedia** | Pointer to **interface{}** |  | [optional] 
**Source** | Pointer to **NullableString** |  | [optional] 
**State** | Pointer to **NullableString** |  | [optional] 
**Street** | Pointer to **NullableString** |  | [optional] 
**StreetNumber** | Pointer to **NullableString** |  | [optional] 
**SupplierNumber** | Pointer to **NullableString** |  | [optional] 
**Tags** | Pointer to **[]string** |  | [optional] 
**TaxCountry** | Pointer to [**NullableCountryCode**](CountryCode.md) |  | [optional] 
**TaxNumber** | Pointer to **NullableString** |  | [optional] 
**TaxOffice** | Pointer to **NullableString** |  | [optional] 
**TotalInvoices** | Pointer to **NullableInt32** |  | [optional] 
**TotalRevenue** | Pointer to **NullableString** |  | [optional] 
**VatId** | Pointer to **NullableString** |  | [optional] 
**VatIdValidated** | Pointer to **NullableBool** |  | [optional] 
**VatIdValidationDate** | Pointer to **NullableString** |  | [optional] 
**Website** | Pointer to **NullableString** |  | [optional] 
**Zip** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewContactCreate

`func NewContactCreate(contactType ContactType, name string, ) *ContactCreate`

NewContactCreate instantiates a new ContactCreate object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactCreateWithDefaults

`func NewContactCreateWithDefaults() *ContactCreate`

NewContactCreateWithDefaults instantiates a new ContactCreate object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountHolder

`func (o *ContactCreate) GetAccountHolder() string`

GetAccountHolder returns the AccountHolder field if non-nil, zero value otherwise.

### GetAccountHolderOk

`func (o *ContactCreate) GetAccountHolderOk() (*string, bool)`

GetAccountHolderOk returns a tuple with the AccountHolder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountHolder

`func (o *ContactCreate) SetAccountHolder(v string)`

SetAccountHolder sets AccountHolder field to given value.

### HasAccountHolder

`func (o *ContactCreate) HasAccountHolder() bool`

HasAccountHolder returns a boolean if a field has been set.

### SetAccountHolderNil

`func (o *ContactCreate) SetAccountHolderNil(b bool)`

 SetAccountHolderNil sets the value for AccountHolder to be an explicit nil

### UnsetAccountHolder
`func (o *ContactCreate) UnsetAccountHolder()`

UnsetAccountHolder ensures that no value is present for AccountHolder, not even an explicit nil
### GetAcquisitionCost

`func (o *ContactCreate) GetAcquisitionCost() string`

GetAcquisitionCost returns the AcquisitionCost field if non-nil, zero value otherwise.

### GetAcquisitionCostOk

`func (o *ContactCreate) GetAcquisitionCostOk() (*string, bool)`

GetAcquisitionCostOk returns a tuple with the AcquisitionCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcquisitionCost

`func (o *ContactCreate) SetAcquisitionCost(v string)`

SetAcquisitionCost sets AcquisitionCost field to given value.

### HasAcquisitionCost

`func (o *ContactCreate) HasAcquisitionCost() bool`

HasAcquisitionCost returns a boolean if a field has been set.

### SetAcquisitionCostNil

`func (o *ContactCreate) SetAcquisitionCostNil(b bool)`

 SetAcquisitionCostNil sets the value for AcquisitionCost to be an explicit nil

### UnsetAcquisitionCost
`func (o *ContactCreate) UnsetAcquisitionCost()`

UnsetAcquisitionCost ensures that no value is present for AcquisitionCost, not even an explicit nil
### GetAddressSupplement

`func (o *ContactCreate) GetAddressSupplement() string`

GetAddressSupplement returns the AddressSupplement field if non-nil, zero value otherwise.

### GetAddressSupplementOk

`func (o *ContactCreate) GetAddressSupplementOk() (*string, bool)`

GetAddressSupplementOk returns a tuple with the AddressSupplement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressSupplement

`func (o *ContactCreate) SetAddressSupplement(v string)`

SetAddressSupplement sets AddressSupplement field to given value.

### HasAddressSupplement

`func (o *ContactCreate) HasAddressSupplement() bool`

HasAddressSupplement returns a boolean if a field has been set.

### SetAddressSupplementNil

`func (o *ContactCreate) SetAddressSupplementNil(b bool)`

 SetAddressSupplementNil sets the value for AddressSupplement to be an explicit nil

### UnsetAddressSupplement
`func (o *ContactCreate) UnsetAddressSupplement()`

UnsetAddressSupplement ensures that no value is present for AddressSupplement, not even an explicit nil
### GetAttention

`func (o *ContactCreate) GetAttention() string`

GetAttention returns the Attention field if non-nil, zero value otherwise.

### GetAttentionOk

`func (o *ContactCreate) GetAttentionOk() (*string, bool)`

GetAttentionOk returns a tuple with the Attention field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttention

`func (o *ContactCreate) SetAttention(v string)`

SetAttention sets Attention field to given value.

### HasAttention

`func (o *ContactCreate) HasAttention() bool`

HasAttention returns a boolean if a field has been set.

### SetAttentionNil

`func (o *ContactCreate) SetAttentionNil(b bool)`

 SetAttentionNil sets the value for Attention to be an explicit nil

### UnsetAttention
`func (o *ContactCreate) UnsetAttention()`

UnsetAttention ensures that no value is present for Attention, not even an explicit nil
### GetBankName

`func (o *ContactCreate) GetBankName() string`

GetBankName returns the BankName field if non-nil, zero value otherwise.

### GetBankNameOk

`func (o *ContactCreate) GetBankNameOk() (*string, bool)`

GetBankNameOk returns a tuple with the BankName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankName

`func (o *ContactCreate) SetBankName(v string)`

SetBankName sets BankName field to given value.

### HasBankName

`func (o *ContactCreate) HasBankName() bool`

HasBankName returns a boolean if a field has been set.

### SetBankNameNil

`func (o *ContactCreate) SetBankNameNil(b bool)`

 SetBankNameNil sets the value for BankName to be an explicit nil

### UnsetBankName
`func (o *ContactCreate) UnsetBankName()`

UnsetBankName ensures that no value is present for BankName, not even an explicit nil
### GetBic

`func (o *ContactCreate) GetBic() string`

GetBic returns the Bic field if non-nil, zero value otherwise.

### GetBicOk

`func (o *ContactCreate) GetBicOk() (*string, bool)`

GetBicOk returns a tuple with the Bic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBic

`func (o *ContactCreate) SetBic(v string)`

SetBic sets Bic field to given value.

### HasBic

`func (o *ContactCreate) HasBic() bool`

HasBic returns a boolean if a field has been set.

### SetBicNil

`func (o *ContactCreate) SetBicNil(b bool)`

 SetBicNil sets the value for Bic to be an explicit nil

### UnsetBic
`func (o *ContactCreate) UnsetBic()`

UnsetBic ensures that no value is present for Bic, not even an explicit nil
### GetBuyerReference

`func (o *ContactCreate) GetBuyerReference() string`

GetBuyerReference returns the BuyerReference field if non-nil, zero value otherwise.

### GetBuyerReferenceOk

`func (o *ContactCreate) GetBuyerReferenceOk() (*string, bool)`

GetBuyerReferenceOk returns a tuple with the BuyerReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuyerReference

`func (o *ContactCreate) SetBuyerReference(v string)`

SetBuyerReference sets BuyerReference field to given value.

### HasBuyerReference

`func (o *ContactCreate) HasBuyerReference() bool`

HasBuyerReference returns a boolean if a field has been set.

### SetBuyerReferenceNil

`func (o *ContactCreate) SetBuyerReferenceNil(b bool)`

 SetBuyerReferenceNil sets the value for BuyerReference to be an explicit nil

### UnsetBuyerReference
`func (o *ContactCreate) UnsetBuyerReference()`

UnsetBuyerReference ensures that no value is present for BuyerReference, not even an explicit nil
### GetCategory

`func (o *ContactCreate) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *ContactCreate) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *ContactCreate) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *ContactCreate) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### SetCategoryNil

`func (o *ContactCreate) SetCategoryNil(b bool)`

 SetCategoryNil sets the value for Category to be an explicit nil

### UnsetCategory
`func (o *ContactCreate) UnsetCategory()`

UnsetCategory ensures that no value is present for Category, not even an explicit nil
### GetCertificateAuthority

`func (o *ContactCreate) GetCertificateAuthority() string`

GetCertificateAuthority returns the CertificateAuthority field if non-nil, zero value otherwise.

### GetCertificateAuthorityOk

`func (o *ContactCreate) GetCertificateAuthorityOk() (*string, bool)`

GetCertificateAuthorityOk returns a tuple with the CertificateAuthority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateAuthority

`func (o *ContactCreate) SetCertificateAuthority(v string)`

SetCertificateAuthority sets CertificateAuthority field to given value.

### HasCertificateAuthority

`func (o *ContactCreate) HasCertificateAuthority() bool`

HasCertificateAuthority returns a boolean if a field has been set.

### SetCertificateAuthorityNil

`func (o *ContactCreate) SetCertificateAuthorityNil(b bool)`

 SetCertificateAuthorityNil sets the value for CertificateAuthority to be an explicit nil

### UnsetCertificateAuthority
`func (o *ContactCreate) UnsetCertificateAuthority()`

UnsetCertificateAuthority ensures that no value is present for CertificateAuthority, not even an explicit nil
### GetCertificateNumber

`func (o *ContactCreate) GetCertificateNumber() string`

GetCertificateNumber returns the CertificateNumber field if non-nil, zero value otherwise.

### GetCertificateNumberOk

`func (o *ContactCreate) GetCertificateNumberOk() (*string, bool)`

GetCertificateNumberOk returns a tuple with the CertificateNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateNumber

`func (o *ContactCreate) SetCertificateNumber(v string)`

SetCertificateNumber sets CertificateNumber field to given value.

### HasCertificateNumber

`func (o *ContactCreate) HasCertificateNumber() bool`

HasCertificateNumber returns a boolean if a field has been set.

### SetCertificateNumberNil

`func (o *ContactCreate) SetCertificateNumberNil(b bool)`

 SetCertificateNumberNil sets the value for CertificateNumber to be an explicit nil

### UnsetCertificateNumber
`func (o *ContactCreate) UnsetCertificateNumber()`

UnsetCertificateNumber ensures that no value is present for CertificateNumber, not even an explicit nil
### GetCertificateParagraph

`func (o *ContactCreate) GetCertificateParagraph() string`

GetCertificateParagraph returns the CertificateParagraph field if non-nil, zero value otherwise.

### GetCertificateParagraphOk

`func (o *ContactCreate) GetCertificateParagraphOk() (*string, bool)`

GetCertificateParagraphOk returns a tuple with the CertificateParagraph field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateParagraph

`func (o *ContactCreate) SetCertificateParagraph(v string)`

SetCertificateParagraph sets CertificateParagraph field to given value.

### HasCertificateParagraph

`func (o *ContactCreate) HasCertificateParagraph() bool`

HasCertificateParagraph returns a boolean if a field has been set.

### SetCertificateParagraphNil

`func (o *ContactCreate) SetCertificateParagraphNil(b bool)`

 SetCertificateParagraphNil sets the value for CertificateParagraph to be an explicit nil

### UnsetCertificateParagraph
`func (o *ContactCreate) UnsetCertificateParagraph()`

UnsetCertificateParagraph ensures that no value is present for CertificateParagraph, not even an explicit nil
### GetCertificateValidUntil

`func (o *ContactCreate) GetCertificateValidUntil() string`

GetCertificateValidUntil returns the CertificateValidUntil field if non-nil, zero value otherwise.

### GetCertificateValidUntilOk

`func (o *ContactCreate) GetCertificateValidUntilOk() (*string, bool)`

GetCertificateValidUntilOk returns a tuple with the CertificateValidUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateValidUntil

`func (o *ContactCreate) SetCertificateValidUntil(v string)`

SetCertificateValidUntil sets CertificateValidUntil field to given value.

### HasCertificateValidUntil

`func (o *ContactCreate) HasCertificateValidUntil() bool`

HasCertificateValidUntil returns a boolean if a field has been set.

### SetCertificateValidUntilNil

`func (o *ContactCreate) SetCertificateValidUntilNil(b bool)`

 SetCertificateValidUntilNil sets the value for CertificateValidUntil to be an explicit nil

### UnsetCertificateValidUntil
`func (o *ContactCreate) UnsetCertificateValidUntil()`

UnsetCertificateValidUntil ensures that no value is present for CertificateValidUntil, not even an explicit nil
### GetCity

`func (o *ContactCreate) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *ContactCreate) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *ContactCreate) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *ContactCreate) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *ContactCreate) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *ContactCreate) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetCompanyName

`func (o *ContactCreate) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *ContactCreate) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *ContactCreate) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.

### HasCompanyName

`func (o *ContactCreate) HasCompanyName() bool`

HasCompanyName returns a boolean if a field has been set.

### SetCompanyNameNil

`func (o *ContactCreate) SetCompanyNameNil(b bool)`

 SetCompanyNameNil sets the value for CompanyName to be an explicit nil

### UnsetCompanyName
`func (o *ContactCreate) UnsetCompanyName()`

UnsetCompanyName ensures that no value is present for CompanyName, not even an explicit nil
### GetContactPersons

`func (o *ContactCreate) GetContactPersons() interface{}`

GetContactPersons returns the ContactPersons field if non-nil, zero value otherwise.

### GetContactPersonsOk

`func (o *ContactCreate) GetContactPersonsOk() (*interface{}, bool)`

GetContactPersonsOk returns a tuple with the ContactPersons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactPersons

`func (o *ContactCreate) SetContactPersons(v interface{})`

SetContactPersons sets ContactPersons field to given value.

### HasContactPersons

`func (o *ContactCreate) HasContactPersons() bool`

HasContactPersons returns a boolean if a field has been set.

### SetContactPersonsNil

`func (o *ContactCreate) SetContactPersonsNil(b bool)`

 SetContactPersonsNil sets the value for ContactPersons to be an explicit nil

### UnsetContactPersons
`func (o *ContactCreate) UnsetContactPersons()`

UnsetContactPersons ensures that no value is present for ContactPersons, not even an explicit nil
### GetContactType

`func (o *ContactCreate) GetContactType() ContactType`

GetContactType returns the ContactType field if non-nil, zero value otherwise.

### GetContactTypeOk

`func (o *ContactCreate) GetContactTypeOk() (*ContactType, bool)`

GetContactTypeOk returns a tuple with the ContactType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactType

`func (o *ContactCreate) SetContactType(v ContactType)`

SetContactType sets ContactType field to given value.


### GetCountry

`func (o *ContactCreate) GetCountry() CountryCode`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *ContactCreate) GetCountryOk() (*CountryCode, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *ContactCreate) SetCountry(v CountryCode)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *ContactCreate) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *ContactCreate) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *ContactCreate) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetCreditLimit

`func (o *ContactCreate) GetCreditLimit() string`

GetCreditLimit returns the CreditLimit field if non-nil, zero value otherwise.

### GetCreditLimitOk

`func (o *ContactCreate) GetCreditLimitOk() (*string, bool)`

GetCreditLimitOk returns a tuple with the CreditLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditLimit

`func (o *ContactCreate) SetCreditLimit(v string)`

SetCreditLimit sets CreditLimit field to given value.

### HasCreditLimit

`func (o *ContactCreate) HasCreditLimit() bool`

HasCreditLimit returns a boolean if a field has been set.

### SetCreditLimitNil

`func (o *ContactCreate) SetCreditLimitNil(b bool)`

 SetCreditLimitNil sets the value for CreditLimit to be an explicit nil

### UnsetCreditLimit
`func (o *ContactCreate) UnsetCreditLimit()`

UnsetCreditLimit ensures that no value is present for CreditLimit, not even an explicit nil
### GetCreditorAccountSkr03

`func (o *ContactCreate) GetCreditorAccountSkr03() string`

GetCreditorAccountSkr03 returns the CreditorAccountSkr03 field if non-nil, zero value otherwise.

### GetCreditorAccountSkr03Ok

`func (o *ContactCreate) GetCreditorAccountSkr03Ok() (*string, bool)`

GetCreditorAccountSkr03Ok returns a tuple with the CreditorAccountSkr03 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditorAccountSkr03

`func (o *ContactCreate) SetCreditorAccountSkr03(v string)`

SetCreditorAccountSkr03 sets CreditorAccountSkr03 field to given value.

### HasCreditorAccountSkr03

`func (o *ContactCreate) HasCreditorAccountSkr03() bool`

HasCreditorAccountSkr03 returns a boolean if a field has been set.

### SetCreditorAccountSkr03Nil

`func (o *ContactCreate) SetCreditorAccountSkr03Nil(b bool)`

 SetCreditorAccountSkr03Nil sets the value for CreditorAccountSkr03 to be an explicit nil

### UnsetCreditorAccountSkr03
`func (o *ContactCreate) UnsetCreditorAccountSkr03()`

UnsetCreditorAccountSkr03 ensures that no value is present for CreditorAccountSkr03, not even an explicit nil
### GetCreditorAccountSkr04

`func (o *ContactCreate) GetCreditorAccountSkr04() string`

GetCreditorAccountSkr04 returns the CreditorAccountSkr04 field if non-nil, zero value otherwise.

### GetCreditorAccountSkr04Ok

`func (o *ContactCreate) GetCreditorAccountSkr04Ok() (*string, bool)`

GetCreditorAccountSkr04Ok returns a tuple with the CreditorAccountSkr04 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditorAccountSkr04

`func (o *ContactCreate) SetCreditorAccountSkr04(v string)`

SetCreditorAccountSkr04 sets CreditorAccountSkr04 field to given value.

### HasCreditorAccountSkr04

`func (o *ContactCreate) HasCreditorAccountSkr04() bool`

HasCreditorAccountSkr04 returns a boolean if a field has been set.

### SetCreditorAccountSkr04Nil

`func (o *ContactCreate) SetCreditorAccountSkr04Nil(b bool)`

 SetCreditorAccountSkr04Nil sets the value for CreditorAccountSkr04 to be an explicit nil

### UnsetCreditorAccountSkr04
`func (o *ContactCreate) UnsetCreditorAccountSkr04()`

UnsetCreditorAccountSkr04 ensures that no value is present for CreditorAccountSkr04, not even an explicit nil
### GetCurrency

`func (o *ContactCreate) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ContactCreate) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ContactCreate) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *ContactCreate) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *ContactCreate) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *ContactCreate) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetCustomFields

`func (o *ContactCreate) GetCustomFields() interface{}`

GetCustomFields returns the CustomFields field if non-nil, zero value otherwise.

### GetCustomFieldsOk

`func (o *ContactCreate) GetCustomFieldsOk() (*interface{}, bool)`

GetCustomFieldsOk returns a tuple with the CustomFields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomFields

`func (o *ContactCreate) SetCustomFields(v interface{})`

SetCustomFields sets CustomFields field to given value.

### HasCustomFields

`func (o *ContactCreate) HasCustomFields() bool`

HasCustomFields returns a boolean if a field has been set.

### SetCustomFieldsNil

`func (o *ContactCreate) SetCustomFieldsNil(b bool)`

 SetCustomFieldsNil sets the value for CustomFields to be an explicit nil

### UnsetCustomFields
`func (o *ContactCreate) UnsetCustomFields()`

UnsetCustomFields ensures that no value is present for CustomFields, not even an explicit nil
### GetCustomerNumber

`func (o *ContactCreate) GetCustomerNumber() string`

GetCustomerNumber returns the CustomerNumber field if non-nil, zero value otherwise.

### GetCustomerNumberOk

`func (o *ContactCreate) GetCustomerNumberOk() (*string, bool)`

GetCustomerNumberOk returns a tuple with the CustomerNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerNumber

`func (o *ContactCreate) SetCustomerNumber(v string)`

SetCustomerNumber sets CustomerNumber field to given value.

### HasCustomerNumber

`func (o *ContactCreate) HasCustomerNumber() bool`

HasCustomerNumber returns a boolean if a field has been set.

### SetCustomerNumberNil

`func (o *ContactCreate) SetCustomerNumberNil(b bool)`

 SetCustomerNumberNil sets the value for CustomerNumber to be an explicit nil

### UnsetCustomerNumber
`func (o *ContactCreate) UnsetCustomerNumber()`

UnsetCustomerNumber ensures that no value is present for CustomerNumber, not even an explicit nil
### GetDebitorAccountSkr03

`func (o *ContactCreate) GetDebitorAccountSkr03() string`

GetDebitorAccountSkr03 returns the DebitorAccountSkr03 field if non-nil, zero value otherwise.

### GetDebitorAccountSkr03Ok

`func (o *ContactCreate) GetDebitorAccountSkr03Ok() (*string, bool)`

GetDebitorAccountSkr03Ok returns a tuple with the DebitorAccountSkr03 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebitorAccountSkr03

`func (o *ContactCreate) SetDebitorAccountSkr03(v string)`

SetDebitorAccountSkr03 sets DebitorAccountSkr03 field to given value.

### HasDebitorAccountSkr03

`func (o *ContactCreate) HasDebitorAccountSkr03() bool`

HasDebitorAccountSkr03 returns a boolean if a field has been set.

### SetDebitorAccountSkr03Nil

`func (o *ContactCreate) SetDebitorAccountSkr03Nil(b bool)`

 SetDebitorAccountSkr03Nil sets the value for DebitorAccountSkr03 to be an explicit nil

### UnsetDebitorAccountSkr03
`func (o *ContactCreate) UnsetDebitorAccountSkr03()`

UnsetDebitorAccountSkr03 ensures that no value is present for DebitorAccountSkr03, not even an explicit nil
### GetDebitorAccountSkr04

`func (o *ContactCreate) GetDebitorAccountSkr04() string`

GetDebitorAccountSkr04 returns the DebitorAccountSkr04 field if non-nil, zero value otherwise.

### GetDebitorAccountSkr04Ok

`func (o *ContactCreate) GetDebitorAccountSkr04Ok() (*string, bool)`

GetDebitorAccountSkr04Ok returns a tuple with the DebitorAccountSkr04 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebitorAccountSkr04

`func (o *ContactCreate) SetDebitorAccountSkr04(v string)`

SetDebitorAccountSkr04 sets DebitorAccountSkr04 field to given value.

### HasDebitorAccountSkr04

`func (o *ContactCreate) HasDebitorAccountSkr04() bool`

HasDebitorAccountSkr04 returns a boolean if a field has been set.

### SetDebitorAccountSkr04Nil

`func (o *ContactCreate) SetDebitorAccountSkr04Nil(b bool)`

 SetDebitorAccountSkr04Nil sets the value for DebitorAccountSkr04 to be an explicit nil

### UnsetDebitorAccountSkr04
`func (o *ContactCreate) UnsetDebitorAccountSkr04()`

UnsetDebitorAccountSkr04 ensures that no value is present for DebitorAccountSkr04, not even an explicit nil
### GetDefaultDebitorNumber

`func (o *ContactCreate) GetDefaultDebitorNumber() string`

GetDefaultDebitorNumber returns the DefaultDebitorNumber field if non-nil, zero value otherwise.

### GetDefaultDebitorNumberOk

`func (o *ContactCreate) GetDefaultDebitorNumberOk() (*string, bool)`

GetDefaultDebitorNumberOk returns a tuple with the DefaultDebitorNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultDebitorNumber

`func (o *ContactCreate) SetDefaultDebitorNumber(v string)`

SetDefaultDebitorNumber sets DefaultDebitorNumber field to given value.

### HasDefaultDebitorNumber

`func (o *ContactCreate) HasDefaultDebitorNumber() bool`

HasDefaultDebitorNumber returns a boolean if a field has been set.

### SetDefaultDebitorNumberNil

`func (o *ContactCreate) SetDefaultDebitorNumberNil(b bool)`

 SetDefaultDebitorNumberNil sets the value for DefaultDebitorNumber to be an explicit nil

### UnsetDefaultDebitorNumber
`func (o *ContactCreate) UnsetDefaultDebitorNumber()`

UnsetDefaultDebitorNumber ensures that no value is present for DefaultDebitorNumber, not even an explicit nil
### GetDeliveryBlock

`func (o *ContactCreate) GetDeliveryBlock() bool`

GetDeliveryBlock returns the DeliveryBlock field if non-nil, zero value otherwise.

### GetDeliveryBlockOk

`func (o *ContactCreate) GetDeliveryBlockOk() (*bool, bool)`

GetDeliveryBlockOk returns a tuple with the DeliveryBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryBlock

`func (o *ContactCreate) SetDeliveryBlock(v bool)`

SetDeliveryBlock sets DeliveryBlock field to given value.

### HasDeliveryBlock

`func (o *ContactCreate) HasDeliveryBlock() bool`

HasDeliveryBlock returns a boolean if a field has been set.

### SetDeliveryBlockNil

`func (o *ContactCreate) SetDeliveryBlockNil(b bool)`

 SetDeliveryBlockNil sets the value for DeliveryBlock to be an explicit nil

### UnsetDeliveryBlock
`func (o *ContactCreate) UnsetDeliveryBlock()`

UnsetDeliveryBlock ensures that no value is present for DeliveryBlock, not even an explicit nil
### GetDepartment

`func (o *ContactCreate) GetDepartment() string`

GetDepartment returns the Department field if non-nil, zero value otherwise.

### GetDepartmentOk

`func (o *ContactCreate) GetDepartmentOk() (*string, bool)`

GetDepartmentOk returns a tuple with the Department field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartment

`func (o *ContactCreate) SetDepartment(v string)`

SetDepartment sets Department field to given value.

### HasDepartment

`func (o *ContactCreate) HasDepartment() bool`

HasDepartment returns a boolean if a field has been set.

### SetDepartmentNil

`func (o *ContactCreate) SetDepartmentNil(b bool)`

 SetDepartmentNil sets the value for Department to be an explicit nil

### UnsetDepartment
`func (o *ContactCreate) UnsetDepartment()`

UnsetDepartment ensures that no value is present for Department, not even an explicit nil
### GetDiscountDays

`func (o *ContactCreate) GetDiscountDays() int32`

GetDiscountDays returns the DiscountDays field if non-nil, zero value otherwise.

### GetDiscountDaysOk

`func (o *ContactCreate) GetDiscountDaysOk() (*int32, bool)`

GetDiscountDaysOk returns a tuple with the DiscountDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountDays

`func (o *ContactCreate) SetDiscountDays(v int32)`

SetDiscountDays sets DiscountDays field to given value.

### HasDiscountDays

`func (o *ContactCreate) HasDiscountDays() bool`

HasDiscountDays returns a boolean if a field has been set.

### SetDiscountDaysNil

`func (o *ContactCreate) SetDiscountDaysNil(b bool)`

 SetDiscountDaysNil sets the value for DiscountDays to be an explicit nil

### UnsetDiscountDays
`func (o *ContactCreate) UnsetDiscountDays()`

UnsetDiscountDays ensures that no value is present for DiscountDays, not even an explicit nil
### GetDiscountPercentage

`func (o *ContactCreate) GetDiscountPercentage() string`

GetDiscountPercentage returns the DiscountPercentage field if non-nil, zero value otherwise.

### GetDiscountPercentageOk

`func (o *ContactCreate) GetDiscountPercentageOk() (*string, bool)`

GetDiscountPercentageOk returns a tuple with the DiscountPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountPercentage

`func (o *ContactCreate) SetDiscountPercentage(v string)`

SetDiscountPercentage sets DiscountPercentage field to given value.

### HasDiscountPercentage

`func (o *ContactCreate) HasDiscountPercentage() bool`

HasDiscountPercentage returns a boolean if a field has been set.

### SetDiscountPercentageNil

`func (o *ContactCreate) SetDiscountPercentageNil(b bool)`

 SetDiscountPercentageNil sets the value for DiscountPercentage to be an explicit nil

### UnsetDiscountPercentage
`func (o *ContactCreate) UnsetDiscountPercentage()`

UnsetDiscountPercentage ensures that no value is present for DiscountPercentage, not even an explicit nil
### GetDonationReceiptEligible

`func (o *ContactCreate) GetDonationReceiptEligible() bool`

GetDonationReceiptEligible returns the DonationReceiptEligible field if non-nil, zero value otherwise.

### GetDonationReceiptEligibleOk

`func (o *ContactCreate) GetDonationReceiptEligibleOk() (*bool, bool)`

GetDonationReceiptEligibleOk returns a tuple with the DonationReceiptEligible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDonationReceiptEligible

`func (o *ContactCreate) SetDonationReceiptEligible(v bool)`

SetDonationReceiptEligible sets DonationReceiptEligible field to given value.

### HasDonationReceiptEligible

`func (o *ContactCreate) HasDonationReceiptEligible() bool`

HasDonationReceiptEligible returns a boolean if a field has been set.

### SetDonationReceiptEligibleNil

`func (o *ContactCreate) SetDonationReceiptEligibleNil(b bool)`

 SetDonationReceiptEligibleNil sets the value for DonationReceiptEligible to be an explicit nil

### UnsetDonationReceiptEligible
`func (o *ContactCreate) UnsetDonationReceiptEligible()`

UnsetDonationReceiptEligible ensures that no value is present for DonationReceiptEligible, not even an explicit nil
### GetEmail

`func (o *ContactCreate) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *ContactCreate) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *ContactCreate) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *ContactCreate) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *ContactCreate) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *ContactCreate) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetExternalId

`func (o *ContactCreate) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *ContactCreate) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *ContactCreate) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.

### HasExternalId

`func (o *ContactCreate) HasExternalId() bool`

HasExternalId returns a boolean if a field has been set.

### SetExternalIdNil

`func (o *ContactCreate) SetExternalIdNil(b bool)`

 SetExternalIdNil sets the value for ExternalId to be an explicit nil

### UnsetExternalId
`func (o *ContactCreate) UnsetExternalId()`

UnsetExternalId ensures that no value is present for ExternalId, not even an explicit nil
### GetFax

`func (o *ContactCreate) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *ContactCreate) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *ContactCreate) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *ContactCreate) HasFax() bool`

HasFax returns a boolean if a field has been set.

### SetFaxNil

`func (o *ContactCreate) SetFaxNil(b bool)`

 SetFaxNil sets the value for Fax to be an explicit nil

### UnsetFax
`func (o *ContactCreate) UnsetFax()`

UnsetFax ensures that no value is present for Fax, not even an explicit nil
### GetIban

`func (o *ContactCreate) GetIban() string`

GetIban returns the Iban field if non-nil, zero value otherwise.

### GetIbanOk

`func (o *ContactCreate) GetIbanOk() (*string, bool)`

GetIbanOk returns a tuple with the Iban field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIban

`func (o *ContactCreate) SetIban(v string)`

SetIban sets Iban field to given value.

### HasIban

`func (o *ContactCreate) HasIban() bool`

HasIban returns a boolean if a field has been set.

### SetIbanNil

`func (o *ContactCreate) SetIbanNil(b bool)`

 SetIbanNil sets the value for Iban to be an explicit nil

### UnsetIban
`func (o *ContactCreate) UnsetIban()`

UnsetIban ensures that no value is present for Iban, not even an explicit nil
### GetIndustry

`func (o *ContactCreate) GetIndustry() string`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *ContactCreate) GetIndustryOk() (*string, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *ContactCreate) SetIndustry(v string)`

SetIndustry sets Industry field to given value.

### HasIndustry

`func (o *ContactCreate) HasIndustry() bool`

HasIndustry returns a boolean if a field has been set.

### SetIndustryNil

`func (o *ContactCreate) SetIndustryNil(b bool)`

 SetIndustryNil sets the value for Industry to be an explicit nil

### UnsetIndustry
`func (o *ContactCreate) UnsetIndustry()`

UnsetIndustry ensures that no value is present for Industry, not even an explicit nil
### GetIsActive

`func (o *ContactCreate) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *ContactCreate) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *ContactCreate) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *ContactCreate) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### SetIsActiveNil

`func (o *ContactCreate) SetIsActiveNil(b bool)`

 SetIsActiveNil sets the value for IsActive to be an explicit nil

### UnsetIsActive
`func (o *ContactCreate) UnsetIsActive()`

UnsetIsActive ensures that no value is present for IsActive, not even an explicit nil
### GetIsMember

`func (o *ContactCreate) GetIsMember() bool`

GetIsMember returns the IsMember field if non-nil, zero value otherwise.

### GetIsMemberOk

`func (o *ContactCreate) GetIsMemberOk() (*bool, bool)`

GetIsMemberOk returns a tuple with the IsMember field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsMember

`func (o *ContactCreate) SetIsMember(v bool)`

SetIsMember sets IsMember field to given value.

### HasIsMember

`func (o *ContactCreate) HasIsMember() bool`

HasIsMember returns a boolean if a field has been set.

### SetIsMemberNil

`func (o *ContactCreate) SetIsMemberNil(b bool)`

 SetIsMemberNil sets the value for IsMember to be an explicit nil

### UnsetIsMember
`func (o *ContactCreate) UnsetIsMember()`

UnsetIsMember ensures that no value is present for IsMember, not even an explicit nil
### GetIsNonprofit

`func (o *ContactCreate) GetIsNonprofit() bool`

GetIsNonprofit returns the IsNonprofit field if non-nil, zero value otherwise.

### GetIsNonprofitOk

`func (o *ContactCreate) GetIsNonprofitOk() (*bool, bool)`

GetIsNonprofitOk returns a tuple with the IsNonprofit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsNonprofit

`func (o *ContactCreate) SetIsNonprofit(v bool)`

SetIsNonprofit sets IsNonprofit field to given value.

### HasIsNonprofit

`func (o *ContactCreate) HasIsNonprofit() bool`

HasIsNonprofit returns a boolean if a field has been set.

### SetIsNonprofitNil

`func (o *ContactCreate) SetIsNonprofitNil(b bool)`

 SetIsNonprofitNil sets the value for IsNonprofit to be an explicit nil

### UnsetIsNonprofit
`func (o *ContactCreate) UnsetIsNonprofit()`

UnsetIsNonprofit ensures that no value is present for IsNonprofit, not even an explicit nil
### GetLastContactDate

`func (o *ContactCreate) GetLastContactDate() string`

GetLastContactDate returns the LastContactDate field if non-nil, zero value otherwise.

### GetLastContactDateOk

`func (o *ContactCreate) GetLastContactDateOk() (*string, bool)`

GetLastContactDateOk returns a tuple with the LastContactDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastContactDate

`func (o *ContactCreate) SetLastContactDate(v string)`

SetLastContactDate sets LastContactDate field to given value.

### HasLastContactDate

`func (o *ContactCreate) HasLastContactDate() bool`

HasLastContactDate returns a boolean if a field has been set.

### SetLastContactDateNil

`func (o *ContactCreate) SetLastContactDateNil(b bool)`

 SetLastContactDateNil sets the value for LastContactDate to be an explicit nil

### UnsetLastContactDate
`func (o *ContactCreate) UnsetLastContactDate()`

UnsetLastContactDate ensures that no value is present for LastContactDate, not even an explicit nil
### GetLastPurchaseDate

`func (o *ContactCreate) GetLastPurchaseDate() string`

GetLastPurchaseDate returns the LastPurchaseDate field if non-nil, zero value otherwise.

### GetLastPurchaseDateOk

`func (o *ContactCreate) GetLastPurchaseDateOk() (*string, bool)`

GetLastPurchaseDateOk returns a tuple with the LastPurchaseDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPurchaseDate

`func (o *ContactCreate) SetLastPurchaseDate(v string)`

SetLastPurchaseDate sets LastPurchaseDate field to given value.

### HasLastPurchaseDate

`func (o *ContactCreate) HasLastPurchaseDate() bool`

HasLastPurchaseDate returns a boolean if a field has been set.

### SetLastPurchaseDateNil

`func (o *ContactCreate) SetLastPurchaseDateNil(b bool)`

 SetLastPurchaseDateNil sets the value for LastPurchaseDate to be an explicit nil

### UnsetLastPurchaseDate
`func (o *ContactCreate) UnsetLastPurchaseDate()`

UnsetLastPurchaseDate ensures that no value is present for LastPurchaseDate, not even an explicit nil
### GetLeitwegId

`func (o *ContactCreate) GetLeitwegId() string`

GetLeitwegId returns the LeitwegId field if non-nil, zero value otherwise.

### GetLeitwegIdOk

`func (o *ContactCreate) GetLeitwegIdOk() (*string, bool)`

GetLeitwegIdOk returns a tuple with the LeitwegId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeitwegId

`func (o *ContactCreate) SetLeitwegId(v string)`

SetLeitwegId sets LeitwegId field to given value.

### HasLeitwegId

`func (o *ContactCreate) HasLeitwegId() bool`

HasLeitwegId returns a boolean if a field has been set.

### SetLeitwegIdNil

`func (o *ContactCreate) SetLeitwegIdNil(b bool)`

 SetLeitwegIdNil sets the value for LeitwegId to be an explicit nil

### UnsetLeitwegId
`func (o *ContactCreate) UnsetLeitwegId()`

UnsetLeitwegId ensures that no value is present for LeitwegId, not even an explicit nil
### GetLifetimeValue

`func (o *ContactCreate) GetLifetimeValue() string`

GetLifetimeValue returns the LifetimeValue field if non-nil, zero value otherwise.

### GetLifetimeValueOk

`func (o *ContactCreate) GetLifetimeValueOk() (*string, bool)`

GetLifetimeValueOk returns a tuple with the LifetimeValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLifetimeValue

`func (o *ContactCreate) SetLifetimeValue(v string)`

SetLifetimeValue sets LifetimeValue field to given value.

### HasLifetimeValue

`func (o *ContactCreate) HasLifetimeValue() bool`

HasLifetimeValue returns a boolean if a field has been set.

### SetLifetimeValueNil

`func (o *ContactCreate) SetLifetimeValueNil(b bool)`

 SetLifetimeValueNil sets the value for LifetimeValue to be an explicit nil

### UnsetLifetimeValue
`func (o *ContactCreate) UnsetLifetimeValue()`

UnsetLifetimeValue ensures that no value is present for LifetimeValue, not even an explicit nil
### GetMandateDate

`func (o *ContactCreate) GetMandateDate() string`

GetMandateDate returns the MandateDate field if non-nil, zero value otherwise.

### GetMandateDateOk

`func (o *ContactCreate) GetMandateDateOk() (*string, bool)`

GetMandateDateOk returns a tuple with the MandateDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMandateDate

`func (o *ContactCreate) SetMandateDate(v string)`

SetMandateDate sets MandateDate field to given value.

### HasMandateDate

`func (o *ContactCreate) HasMandateDate() bool`

HasMandateDate returns a boolean if a field has been set.

### SetMandateDateNil

`func (o *ContactCreate) SetMandateDateNil(b bool)`

 SetMandateDateNil sets the value for MandateDate to be an explicit nil

### UnsetMandateDate
`func (o *ContactCreate) UnsetMandateDate()`

UnsetMandateDate ensures that no value is present for MandateDate, not even an explicit nil
### GetMandateReference

`func (o *ContactCreate) GetMandateReference() string`

GetMandateReference returns the MandateReference field if non-nil, zero value otherwise.

### GetMandateReferenceOk

`func (o *ContactCreate) GetMandateReferenceOk() (*string, bool)`

GetMandateReferenceOk returns a tuple with the MandateReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMandateReference

`func (o *ContactCreate) SetMandateReference(v string)`

SetMandateReference sets MandateReference field to given value.

### HasMandateReference

`func (o *ContactCreate) HasMandateReference() bool`

HasMandateReference returns a boolean if a field has been set.

### SetMandateReferenceNil

`func (o *ContactCreate) SetMandateReferenceNil(b bool)`

 SetMandateReferenceNil sets the value for MandateReference to be an explicit nil

### UnsetMandateReference
`func (o *ContactCreate) UnsetMandateReference()`

UnsetMandateReference ensures that no value is present for MandateReference, not even an explicit nil
### GetMarketingConsent

`func (o *ContactCreate) GetMarketingConsent() bool`

GetMarketingConsent returns the MarketingConsent field if non-nil, zero value otherwise.

### GetMarketingConsentOk

`func (o *ContactCreate) GetMarketingConsentOk() (*bool, bool)`

GetMarketingConsentOk returns a tuple with the MarketingConsent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarketingConsent

`func (o *ContactCreate) SetMarketingConsent(v bool)`

SetMarketingConsent sets MarketingConsent field to given value.

### HasMarketingConsent

`func (o *ContactCreate) HasMarketingConsent() bool`

HasMarketingConsent returns a boolean if a field has been set.

### SetMarketingConsentNil

`func (o *ContactCreate) SetMarketingConsentNil(b bool)`

 SetMarketingConsentNil sets the value for MarketingConsent to be an explicit nil

### UnsetMarketingConsent
`func (o *ContactCreate) UnsetMarketingConsent()`

UnsetMarketingConsent ensures that no value is present for MarketingConsent, not even an explicit nil
### GetMarketingConsentAt

`func (o *ContactCreate) GetMarketingConsentAt() time.Time`

GetMarketingConsentAt returns the MarketingConsentAt field if non-nil, zero value otherwise.

### GetMarketingConsentAtOk

`func (o *ContactCreate) GetMarketingConsentAtOk() (*time.Time, bool)`

GetMarketingConsentAtOk returns a tuple with the MarketingConsentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarketingConsentAt

`func (o *ContactCreate) SetMarketingConsentAt(v time.Time)`

SetMarketingConsentAt sets MarketingConsentAt field to given value.

### HasMarketingConsentAt

`func (o *ContactCreate) HasMarketingConsentAt() bool`

HasMarketingConsentAt returns a boolean if a field has been set.

### SetMarketingConsentAtNil

`func (o *ContactCreate) SetMarketingConsentAtNil(b bool)`

 SetMarketingConsentAtNil sets the value for MarketingConsentAt to be an explicit nil

### UnsetMarketingConsentAt
`func (o *ContactCreate) UnsetMarketingConsentAt()`

UnsetMarketingConsentAt ensures that no value is present for MarketingConsentAt, not even an explicit nil
### GetMarketingConsentSource

`func (o *ContactCreate) GetMarketingConsentSource() string`

GetMarketingConsentSource returns the MarketingConsentSource field if non-nil, zero value otherwise.

### GetMarketingConsentSourceOk

`func (o *ContactCreate) GetMarketingConsentSourceOk() (*string, bool)`

GetMarketingConsentSourceOk returns a tuple with the MarketingConsentSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarketingConsentSource

`func (o *ContactCreate) SetMarketingConsentSource(v string)`

SetMarketingConsentSource sets MarketingConsentSource field to given value.

### HasMarketingConsentSource

`func (o *ContactCreate) HasMarketingConsentSource() bool`

HasMarketingConsentSource returns a boolean if a field has been set.

### SetMarketingConsentSourceNil

`func (o *ContactCreate) SetMarketingConsentSourceNil(b bool)`

 SetMarketingConsentSourceNil sets the value for MarketingConsentSource to be an explicit nil

### UnsetMarketingConsentSource
`func (o *ContactCreate) UnsetMarketingConsentSource()`

UnsetMarketingConsentSource ensures that no value is present for MarketingConsentSource, not even an explicit nil
### GetMobile

`func (o *ContactCreate) GetMobile() string`

GetMobile returns the Mobile field if non-nil, zero value otherwise.

### GetMobileOk

`func (o *ContactCreate) GetMobileOk() (*string, bool)`

GetMobileOk returns a tuple with the Mobile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobile

`func (o *ContactCreate) SetMobile(v string)`

SetMobile sets Mobile field to given value.

### HasMobile

`func (o *ContactCreate) HasMobile() bool`

HasMobile returns a boolean if a field has been set.

### SetMobileNil

`func (o *ContactCreate) SetMobileNil(b bool)`

 SetMobileNil sets the value for Mobile to be an explicit nil

### UnsetMobile
`func (o *ContactCreate) UnsetMobile()`

UnsetMobile ensures that no value is present for Mobile, not even an explicit nil
### GetName

`func (o *ContactCreate) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ContactCreate) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ContactCreate) SetName(v string)`

SetName sets Name field to given value.


### GetNextContactDate

`func (o *ContactCreate) GetNextContactDate() string`

GetNextContactDate returns the NextContactDate field if non-nil, zero value otherwise.

### GetNextContactDateOk

`func (o *ContactCreate) GetNextContactDateOk() (*string, bool)`

GetNextContactDateOk returns a tuple with the NextContactDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextContactDate

`func (o *ContactCreate) SetNextContactDate(v string)`

SetNextContactDate sets NextContactDate field to given value.

### HasNextContactDate

`func (o *ContactCreate) HasNextContactDate() bool`

HasNextContactDate returns a boolean if a field has been set.

### SetNextContactDateNil

`func (o *ContactCreate) SetNextContactDateNil(b bool)`

 SetNextContactDateNil sets the value for NextContactDate to be an explicit nil

### UnsetNextContactDate
`func (o *ContactCreate) UnsetNextContactDate()`

UnsetNextContactDate ensures that no value is present for NextContactDate, not even an explicit nil
### GetNotes

`func (o *ContactCreate) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ContactCreate) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ContactCreate) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *ContactCreate) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *ContactCreate) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *ContactCreate) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetOpeningBalance

`func (o *ContactCreate) GetOpeningBalance() string`

GetOpeningBalance returns the OpeningBalance field if non-nil, zero value otherwise.

### GetOpeningBalanceOk

`func (o *ContactCreate) GetOpeningBalanceOk() (*string, bool)`

GetOpeningBalanceOk returns a tuple with the OpeningBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpeningBalance

`func (o *ContactCreate) SetOpeningBalance(v string)`

SetOpeningBalance sets OpeningBalance field to given value.

### HasOpeningBalance

`func (o *ContactCreate) HasOpeningBalance() bool`

HasOpeningBalance returns a boolean if a field has been set.

### SetOpeningBalanceNil

`func (o *ContactCreate) SetOpeningBalanceNil(b bool)`

 SetOpeningBalanceNil sets the value for OpeningBalance to be an explicit nil

### UnsetOpeningBalance
`func (o *ContactCreate) UnsetOpeningBalance()`

UnsetOpeningBalance ensures that no value is present for OpeningBalance, not even an explicit nil
### GetOpeningBalanceDate

`func (o *ContactCreate) GetOpeningBalanceDate() string`

GetOpeningBalanceDate returns the OpeningBalanceDate field if non-nil, zero value otherwise.

### GetOpeningBalanceDateOk

`func (o *ContactCreate) GetOpeningBalanceDateOk() (*string, bool)`

GetOpeningBalanceDateOk returns a tuple with the OpeningBalanceDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpeningBalanceDate

`func (o *ContactCreate) SetOpeningBalanceDate(v string)`

SetOpeningBalanceDate sets OpeningBalanceDate field to given value.

### HasOpeningBalanceDate

`func (o *ContactCreate) HasOpeningBalanceDate() bool`

HasOpeningBalanceDate returns a boolean if a field has been set.

### SetOpeningBalanceDateNil

`func (o *ContactCreate) SetOpeningBalanceDateNil(b bool)`

 SetOpeningBalanceDateNil sets the value for OpeningBalanceDate to be an explicit nil

### UnsetOpeningBalanceDate
`func (o *ContactCreate) UnsetOpeningBalanceDate()`

UnsetOpeningBalanceDate ensures that no value is present for OpeningBalanceDate, not even an explicit nil
### GetOrderReference

`func (o *ContactCreate) GetOrderReference() string`

GetOrderReference returns the OrderReference field if non-nil, zero value otherwise.

### GetOrderReferenceOk

`func (o *ContactCreate) GetOrderReferenceOk() (*string, bool)`

GetOrderReferenceOk returns a tuple with the OrderReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderReference

`func (o *ContactCreate) SetOrderReference(v string)`

SetOrderReference sets OrderReference field to given value.

### HasOrderReference

`func (o *ContactCreate) HasOrderReference() bool`

HasOrderReference returns a boolean if a field has been set.

### SetOrderReferenceNil

`func (o *ContactCreate) SetOrderReferenceNil(b bool)`

 SetOrderReferenceNil sets the value for OrderReference to be an explicit nil

### UnsetOrderReference
`func (o *ContactCreate) UnsetOrderReference()`

UnsetOrderReference ensures that no value is present for OrderReference, not even an explicit nil
### GetPaymentBlock

`func (o *ContactCreate) GetPaymentBlock() bool`

GetPaymentBlock returns the PaymentBlock field if non-nil, zero value otherwise.

### GetPaymentBlockOk

`func (o *ContactCreate) GetPaymentBlockOk() (*bool, bool)`

GetPaymentBlockOk returns a tuple with the PaymentBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentBlock

`func (o *ContactCreate) SetPaymentBlock(v bool)`

SetPaymentBlock sets PaymentBlock field to given value.

### HasPaymentBlock

`func (o *ContactCreate) HasPaymentBlock() bool`

HasPaymentBlock returns a boolean if a field has been set.

### SetPaymentBlockNil

`func (o *ContactCreate) SetPaymentBlockNil(b bool)`

 SetPaymentBlockNil sets the value for PaymentBlock to be an explicit nil

### UnsetPaymentBlock
`func (o *ContactCreate) UnsetPaymentBlock()`

UnsetPaymentBlock ensures that no value is present for PaymentBlock, not even an explicit nil
### GetPaymentGracePeriodDays

`func (o *ContactCreate) GetPaymentGracePeriodDays() int32`

GetPaymentGracePeriodDays returns the PaymentGracePeriodDays field if non-nil, zero value otherwise.

### GetPaymentGracePeriodDaysOk

`func (o *ContactCreate) GetPaymentGracePeriodDaysOk() (*int32, bool)`

GetPaymentGracePeriodDaysOk returns a tuple with the PaymentGracePeriodDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentGracePeriodDays

`func (o *ContactCreate) SetPaymentGracePeriodDays(v int32)`

SetPaymentGracePeriodDays sets PaymentGracePeriodDays field to given value.

### HasPaymentGracePeriodDays

`func (o *ContactCreate) HasPaymentGracePeriodDays() bool`

HasPaymentGracePeriodDays returns a boolean if a field has been set.

### SetPaymentGracePeriodDaysNil

`func (o *ContactCreate) SetPaymentGracePeriodDaysNil(b bool)`

 SetPaymentGracePeriodDaysNil sets the value for PaymentGracePeriodDays to be an explicit nil

### UnsetPaymentGracePeriodDays
`func (o *ContactCreate) UnsetPaymentGracePeriodDays()`

UnsetPaymentGracePeriodDays ensures that no value is present for PaymentGracePeriodDays, not even an explicit nil
### GetPaymentMethods

`func (o *ContactCreate) GetPaymentMethods() []string`

GetPaymentMethods returns the PaymentMethods field if non-nil, zero value otherwise.

### GetPaymentMethodsOk

`func (o *ContactCreate) GetPaymentMethodsOk() (*[]string, bool)`

GetPaymentMethodsOk returns a tuple with the PaymentMethods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentMethods

`func (o *ContactCreate) SetPaymentMethods(v []string)`

SetPaymentMethods sets PaymentMethods field to given value.

### HasPaymentMethods

`func (o *ContactCreate) HasPaymentMethods() bool`

HasPaymentMethods returns a boolean if a field has been set.

### SetPaymentMethodsNil

`func (o *ContactCreate) SetPaymentMethodsNil(b bool)`

 SetPaymentMethodsNil sets the value for PaymentMethods to be an explicit nil

### UnsetPaymentMethods
`func (o *ContactCreate) UnsetPaymentMethods()`

UnsetPaymentMethods ensures that no value is present for PaymentMethods, not even an explicit nil
### GetPaymentTerms

`func (o *ContactCreate) GetPaymentTerms() string`

GetPaymentTerms returns the PaymentTerms field if non-nil, zero value otherwise.

### GetPaymentTermsOk

`func (o *ContactCreate) GetPaymentTermsOk() (*string, bool)`

GetPaymentTermsOk returns a tuple with the PaymentTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentTerms

`func (o *ContactCreate) SetPaymentTerms(v string)`

SetPaymentTerms sets PaymentTerms field to given value.

### HasPaymentTerms

`func (o *ContactCreate) HasPaymentTerms() bool`

HasPaymentTerms returns a boolean if a field has been set.

### SetPaymentTermsNil

`func (o *ContactCreate) SetPaymentTermsNil(b bool)`

 SetPaymentTermsNil sets the value for PaymentTerms to be an explicit nil

### UnsetPaymentTerms
`func (o *ContactCreate) UnsetPaymentTerms()`

UnsetPaymentTerms ensures that no value is present for PaymentTerms, not even an explicit nil
### GetPhone

`func (o *ContactCreate) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *ContactCreate) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *ContactCreate) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *ContactCreate) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *ContactCreate) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *ContactCreate) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetRating

`func (o *ContactCreate) GetRating() int32`

GetRating returns the Rating field if non-nil, zero value otherwise.

### GetRatingOk

`func (o *ContactCreate) GetRatingOk() (*int32, bool)`

GetRatingOk returns a tuple with the Rating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRating

`func (o *ContactCreate) SetRating(v int32)`

SetRating sets Rating field to given value.

### HasRating

`func (o *ContactCreate) HasRating() bool`

HasRating returns a boolean if a field has been set.

### SetRatingNil

`func (o *ContactCreate) SetRatingNil(b bool)`

 SetRatingNil sets the value for Rating to be an explicit nil

### UnsetRating
`func (o *ContactCreate) UnsetRating()`

UnsetRating ensures that no value is present for Rating, not even an explicit nil
### GetSalesRepresentative

`func (o *ContactCreate) GetSalesRepresentative() string`

GetSalesRepresentative returns the SalesRepresentative field if non-nil, zero value otherwise.

### GetSalesRepresentativeOk

`func (o *ContactCreate) GetSalesRepresentativeOk() (*string, bool)`

GetSalesRepresentativeOk returns a tuple with the SalesRepresentative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesRepresentative

`func (o *ContactCreate) SetSalesRepresentative(v string)`

SetSalesRepresentative sets SalesRepresentative field to given value.

### HasSalesRepresentative

`func (o *ContactCreate) HasSalesRepresentative() bool`

HasSalesRepresentative returns a boolean if a field has been set.

### SetSalesRepresentativeNil

`func (o *ContactCreate) SetSalesRepresentativeNil(b bool)`

 SetSalesRepresentativeNil sets the value for SalesRepresentative to be an explicit nil

### UnsetSalesRepresentative
`func (o *ContactCreate) UnsetSalesRepresentative()`

UnsetSalesRepresentative ensures that no value is present for SalesRepresentative, not even an explicit nil
### GetSepaBatchBooking

`func (o *ContactCreate) GetSepaBatchBooking() bool`

GetSepaBatchBooking returns the SepaBatchBooking field if non-nil, zero value otherwise.

### GetSepaBatchBookingOk

`func (o *ContactCreate) GetSepaBatchBookingOk() (*bool, bool)`

GetSepaBatchBookingOk returns a tuple with the SepaBatchBooking field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSepaBatchBooking

`func (o *ContactCreate) SetSepaBatchBooking(v bool)`

SetSepaBatchBooking sets SepaBatchBooking field to given value.

### HasSepaBatchBooking

`func (o *ContactCreate) HasSepaBatchBooking() bool`

HasSepaBatchBooking returns a boolean if a field has been set.

### SetSepaBatchBookingNil

`func (o *ContactCreate) SetSepaBatchBookingNil(b bool)`

 SetSepaBatchBookingNil sets the value for SepaBatchBooking to be an explicit nil

### UnsetSepaBatchBooking
`func (o *ContactCreate) UnsetSepaBatchBooking()`

UnsetSepaBatchBooking ensures that no value is present for SepaBatchBooking, not even an explicit nil
### GetSepaSequenceType

`func (o *ContactCreate) GetSepaSequenceType() SepaSequenceType`

GetSepaSequenceType returns the SepaSequenceType field if non-nil, zero value otherwise.

### GetSepaSequenceTypeOk

`func (o *ContactCreate) GetSepaSequenceTypeOk() (*SepaSequenceType, bool)`

GetSepaSequenceTypeOk returns a tuple with the SepaSequenceType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSepaSequenceType

`func (o *ContactCreate) SetSepaSequenceType(v SepaSequenceType)`

SetSepaSequenceType sets SepaSequenceType field to given value.

### HasSepaSequenceType

`func (o *ContactCreate) HasSepaSequenceType() bool`

HasSepaSequenceType returns a boolean if a field has been set.

### SetSepaSequenceTypeNil

`func (o *ContactCreate) SetSepaSequenceTypeNil(b bool)`

 SetSepaSequenceTypeNil sets the value for SepaSequenceType to be an explicit nil

### UnsetSepaSequenceType
`func (o *ContactCreate) UnsetSepaSequenceType()`

UnsetSepaSequenceType ensures that no value is present for SepaSequenceType, not even an explicit nil
### GetSocialMedia

`func (o *ContactCreate) GetSocialMedia() interface{}`

GetSocialMedia returns the SocialMedia field if non-nil, zero value otherwise.

### GetSocialMediaOk

`func (o *ContactCreate) GetSocialMediaOk() (*interface{}, bool)`

GetSocialMediaOk returns a tuple with the SocialMedia field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSocialMedia

`func (o *ContactCreate) SetSocialMedia(v interface{})`

SetSocialMedia sets SocialMedia field to given value.

### HasSocialMedia

`func (o *ContactCreate) HasSocialMedia() bool`

HasSocialMedia returns a boolean if a field has been set.

### SetSocialMediaNil

`func (o *ContactCreate) SetSocialMediaNil(b bool)`

 SetSocialMediaNil sets the value for SocialMedia to be an explicit nil

### UnsetSocialMedia
`func (o *ContactCreate) UnsetSocialMedia()`

UnsetSocialMedia ensures that no value is present for SocialMedia, not even an explicit nil
### GetSource

`func (o *ContactCreate) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ContactCreate) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ContactCreate) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *ContactCreate) HasSource() bool`

HasSource returns a boolean if a field has been set.

### SetSourceNil

`func (o *ContactCreate) SetSourceNil(b bool)`

 SetSourceNil sets the value for Source to be an explicit nil

### UnsetSource
`func (o *ContactCreate) UnsetSource()`

UnsetSource ensures that no value is present for Source, not even an explicit nil
### GetState

`func (o *ContactCreate) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *ContactCreate) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *ContactCreate) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *ContactCreate) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *ContactCreate) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *ContactCreate) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetStreet

`func (o *ContactCreate) GetStreet() string`

GetStreet returns the Street field if non-nil, zero value otherwise.

### GetStreetOk

`func (o *ContactCreate) GetStreetOk() (*string, bool)`

GetStreetOk returns a tuple with the Street field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStreet

`func (o *ContactCreate) SetStreet(v string)`

SetStreet sets Street field to given value.

### HasStreet

`func (o *ContactCreate) HasStreet() bool`

HasStreet returns a boolean if a field has been set.

### SetStreetNil

`func (o *ContactCreate) SetStreetNil(b bool)`

 SetStreetNil sets the value for Street to be an explicit nil

### UnsetStreet
`func (o *ContactCreate) UnsetStreet()`

UnsetStreet ensures that no value is present for Street, not even an explicit nil
### GetStreetNumber

`func (o *ContactCreate) GetStreetNumber() string`

GetStreetNumber returns the StreetNumber field if non-nil, zero value otherwise.

### GetStreetNumberOk

`func (o *ContactCreate) GetStreetNumberOk() (*string, bool)`

GetStreetNumberOk returns a tuple with the StreetNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStreetNumber

`func (o *ContactCreate) SetStreetNumber(v string)`

SetStreetNumber sets StreetNumber field to given value.

### HasStreetNumber

`func (o *ContactCreate) HasStreetNumber() bool`

HasStreetNumber returns a boolean if a field has been set.

### SetStreetNumberNil

`func (o *ContactCreate) SetStreetNumberNil(b bool)`

 SetStreetNumberNil sets the value for StreetNumber to be an explicit nil

### UnsetStreetNumber
`func (o *ContactCreate) UnsetStreetNumber()`

UnsetStreetNumber ensures that no value is present for StreetNumber, not even an explicit nil
### GetSupplierNumber

`func (o *ContactCreate) GetSupplierNumber() string`

GetSupplierNumber returns the SupplierNumber field if non-nil, zero value otherwise.

### GetSupplierNumberOk

`func (o *ContactCreate) GetSupplierNumberOk() (*string, bool)`

GetSupplierNumberOk returns a tuple with the SupplierNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierNumber

`func (o *ContactCreate) SetSupplierNumber(v string)`

SetSupplierNumber sets SupplierNumber field to given value.

### HasSupplierNumber

`func (o *ContactCreate) HasSupplierNumber() bool`

HasSupplierNumber returns a boolean if a field has been set.

### SetSupplierNumberNil

`func (o *ContactCreate) SetSupplierNumberNil(b bool)`

 SetSupplierNumberNil sets the value for SupplierNumber to be an explicit nil

### UnsetSupplierNumber
`func (o *ContactCreate) UnsetSupplierNumber()`

UnsetSupplierNumber ensures that no value is present for SupplierNumber, not even an explicit nil
### GetTags

`func (o *ContactCreate) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *ContactCreate) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *ContactCreate) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *ContactCreate) HasTags() bool`

HasTags returns a boolean if a field has been set.

### SetTagsNil

`func (o *ContactCreate) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *ContactCreate) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil
### GetTaxCountry

`func (o *ContactCreate) GetTaxCountry() CountryCode`

GetTaxCountry returns the TaxCountry field if non-nil, zero value otherwise.

### GetTaxCountryOk

`func (o *ContactCreate) GetTaxCountryOk() (*CountryCode, bool)`

GetTaxCountryOk returns a tuple with the TaxCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCountry

`func (o *ContactCreate) SetTaxCountry(v CountryCode)`

SetTaxCountry sets TaxCountry field to given value.

### HasTaxCountry

`func (o *ContactCreate) HasTaxCountry() bool`

HasTaxCountry returns a boolean if a field has been set.

### SetTaxCountryNil

`func (o *ContactCreate) SetTaxCountryNil(b bool)`

 SetTaxCountryNil sets the value for TaxCountry to be an explicit nil

### UnsetTaxCountry
`func (o *ContactCreate) UnsetTaxCountry()`

UnsetTaxCountry ensures that no value is present for TaxCountry, not even an explicit nil
### GetTaxNumber

`func (o *ContactCreate) GetTaxNumber() string`

GetTaxNumber returns the TaxNumber field if non-nil, zero value otherwise.

### GetTaxNumberOk

`func (o *ContactCreate) GetTaxNumberOk() (*string, bool)`

GetTaxNumberOk returns a tuple with the TaxNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxNumber

`func (o *ContactCreate) SetTaxNumber(v string)`

SetTaxNumber sets TaxNumber field to given value.

### HasTaxNumber

`func (o *ContactCreate) HasTaxNumber() bool`

HasTaxNumber returns a boolean if a field has been set.

### SetTaxNumberNil

`func (o *ContactCreate) SetTaxNumberNil(b bool)`

 SetTaxNumberNil sets the value for TaxNumber to be an explicit nil

### UnsetTaxNumber
`func (o *ContactCreate) UnsetTaxNumber()`

UnsetTaxNumber ensures that no value is present for TaxNumber, not even an explicit nil
### GetTaxOffice

`func (o *ContactCreate) GetTaxOffice() string`

GetTaxOffice returns the TaxOffice field if non-nil, zero value otherwise.

### GetTaxOfficeOk

`func (o *ContactCreate) GetTaxOfficeOk() (*string, bool)`

GetTaxOfficeOk returns a tuple with the TaxOffice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxOffice

`func (o *ContactCreate) SetTaxOffice(v string)`

SetTaxOffice sets TaxOffice field to given value.

### HasTaxOffice

`func (o *ContactCreate) HasTaxOffice() bool`

HasTaxOffice returns a boolean if a field has been set.

### SetTaxOfficeNil

`func (o *ContactCreate) SetTaxOfficeNil(b bool)`

 SetTaxOfficeNil sets the value for TaxOffice to be an explicit nil

### UnsetTaxOffice
`func (o *ContactCreate) UnsetTaxOffice()`

UnsetTaxOffice ensures that no value is present for TaxOffice, not even an explicit nil
### GetTotalInvoices

`func (o *ContactCreate) GetTotalInvoices() int32`

GetTotalInvoices returns the TotalInvoices field if non-nil, zero value otherwise.

### GetTotalInvoicesOk

`func (o *ContactCreate) GetTotalInvoicesOk() (*int32, bool)`

GetTotalInvoicesOk returns a tuple with the TotalInvoices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalInvoices

`func (o *ContactCreate) SetTotalInvoices(v int32)`

SetTotalInvoices sets TotalInvoices field to given value.

### HasTotalInvoices

`func (o *ContactCreate) HasTotalInvoices() bool`

HasTotalInvoices returns a boolean if a field has been set.

### SetTotalInvoicesNil

`func (o *ContactCreate) SetTotalInvoicesNil(b bool)`

 SetTotalInvoicesNil sets the value for TotalInvoices to be an explicit nil

### UnsetTotalInvoices
`func (o *ContactCreate) UnsetTotalInvoices()`

UnsetTotalInvoices ensures that no value is present for TotalInvoices, not even an explicit nil
### GetTotalRevenue

`func (o *ContactCreate) GetTotalRevenue() string`

GetTotalRevenue returns the TotalRevenue field if non-nil, zero value otherwise.

### GetTotalRevenueOk

`func (o *ContactCreate) GetTotalRevenueOk() (*string, bool)`

GetTotalRevenueOk returns a tuple with the TotalRevenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalRevenue

`func (o *ContactCreate) SetTotalRevenue(v string)`

SetTotalRevenue sets TotalRevenue field to given value.

### HasTotalRevenue

`func (o *ContactCreate) HasTotalRevenue() bool`

HasTotalRevenue returns a boolean if a field has been set.

### SetTotalRevenueNil

`func (o *ContactCreate) SetTotalRevenueNil(b bool)`

 SetTotalRevenueNil sets the value for TotalRevenue to be an explicit nil

### UnsetTotalRevenue
`func (o *ContactCreate) UnsetTotalRevenue()`

UnsetTotalRevenue ensures that no value is present for TotalRevenue, not even an explicit nil
### GetVatId

`func (o *ContactCreate) GetVatId() string`

GetVatId returns the VatId field if non-nil, zero value otherwise.

### GetVatIdOk

`func (o *ContactCreate) GetVatIdOk() (*string, bool)`

GetVatIdOk returns a tuple with the VatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatId

`func (o *ContactCreate) SetVatId(v string)`

SetVatId sets VatId field to given value.

### HasVatId

`func (o *ContactCreate) HasVatId() bool`

HasVatId returns a boolean if a field has been set.

### SetVatIdNil

`func (o *ContactCreate) SetVatIdNil(b bool)`

 SetVatIdNil sets the value for VatId to be an explicit nil

### UnsetVatId
`func (o *ContactCreate) UnsetVatId()`

UnsetVatId ensures that no value is present for VatId, not even an explicit nil
### GetVatIdValidated

`func (o *ContactCreate) GetVatIdValidated() bool`

GetVatIdValidated returns the VatIdValidated field if non-nil, zero value otherwise.

### GetVatIdValidatedOk

`func (o *ContactCreate) GetVatIdValidatedOk() (*bool, bool)`

GetVatIdValidatedOk returns a tuple with the VatIdValidated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatIdValidated

`func (o *ContactCreate) SetVatIdValidated(v bool)`

SetVatIdValidated sets VatIdValidated field to given value.

### HasVatIdValidated

`func (o *ContactCreate) HasVatIdValidated() bool`

HasVatIdValidated returns a boolean if a field has been set.

### SetVatIdValidatedNil

`func (o *ContactCreate) SetVatIdValidatedNil(b bool)`

 SetVatIdValidatedNil sets the value for VatIdValidated to be an explicit nil

### UnsetVatIdValidated
`func (o *ContactCreate) UnsetVatIdValidated()`

UnsetVatIdValidated ensures that no value is present for VatIdValidated, not even an explicit nil
### GetVatIdValidationDate

`func (o *ContactCreate) GetVatIdValidationDate() string`

GetVatIdValidationDate returns the VatIdValidationDate field if non-nil, zero value otherwise.

### GetVatIdValidationDateOk

`func (o *ContactCreate) GetVatIdValidationDateOk() (*string, bool)`

GetVatIdValidationDateOk returns a tuple with the VatIdValidationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatIdValidationDate

`func (o *ContactCreate) SetVatIdValidationDate(v string)`

SetVatIdValidationDate sets VatIdValidationDate field to given value.

### HasVatIdValidationDate

`func (o *ContactCreate) HasVatIdValidationDate() bool`

HasVatIdValidationDate returns a boolean if a field has been set.

### SetVatIdValidationDateNil

`func (o *ContactCreate) SetVatIdValidationDateNil(b bool)`

 SetVatIdValidationDateNil sets the value for VatIdValidationDate to be an explicit nil

### UnsetVatIdValidationDate
`func (o *ContactCreate) UnsetVatIdValidationDate()`

UnsetVatIdValidationDate ensures that no value is present for VatIdValidationDate, not even an explicit nil
### GetWebsite

`func (o *ContactCreate) GetWebsite() string`

GetWebsite returns the Website field if non-nil, zero value otherwise.

### GetWebsiteOk

`func (o *ContactCreate) GetWebsiteOk() (*string, bool)`

GetWebsiteOk returns a tuple with the Website field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsite

`func (o *ContactCreate) SetWebsite(v string)`

SetWebsite sets Website field to given value.

### HasWebsite

`func (o *ContactCreate) HasWebsite() bool`

HasWebsite returns a boolean if a field has been set.

### SetWebsiteNil

`func (o *ContactCreate) SetWebsiteNil(b bool)`

 SetWebsiteNil sets the value for Website to be an explicit nil

### UnsetWebsite
`func (o *ContactCreate) UnsetWebsite()`

UnsetWebsite ensures that no value is present for Website, not even an explicit nil
### GetZip

`func (o *ContactCreate) GetZip() string`

GetZip returns the Zip field if non-nil, zero value otherwise.

### GetZipOk

`func (o *ContactCreate) GetZipOk() (*string, bool)`

GetZipOk returns a tuple with the Zip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZip

`func (o *ContactCreate) SetZip(v string)`

SetZip sets Zip field to given value.

### HasZip

`func (o *ContactCreate) HasZip() bool`

HasZip returns a boolean if a field has been set.

### SetZipNil

`func (o *ContactCreate) SetZipNil(b bool)`

 SetZipNil sets the value for Zip to be an explicit nil

### UnsetZip
`func (o *ContactCreate) UnsetZip()`

UnsetZip ensures that no value is present for Zip, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


