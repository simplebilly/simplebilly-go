# Contact

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
**ContactId** | **string** |  | 
**ContactPersons** | **interface{}** |  | 
**ContactType** | **string** |  | 
**Country** | Pointer to **NullableString** |  | [optional] 
**CreatedAt** | **string** |  | [readonly] 
**CreditLimit** | Pointer to **NullableString** |  | [optional] 
**CreditorAccountSkr03** | Pointer to **NullableString** |  | [optional] 
**CreditorAccountSkr04** | Pointer to **NullableString** |  | [optional] 
**Currency** | Pointer to **NullableString** |  | [optional] 
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
**MarketingConsentAt** | Pointer to **NullableString** |  | [optional] 
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
**SocialMedia** | **interface{}** |  | 
**Source** | Pointer to **NullableString** |  | [optional] 
**State** | Pointer to **NullableString** |  | [optional] 
**Street** | Pointer to **NullableString** |  | [optional] 
**StreetNumber** | Pointer to **NullableString** |  | [optional] 
**SupplierNumber** | Pointer to **NullableString** |  | [optional] 
**Tags** | Pointer to **[]string** |  | [optional] 
**TaxCountry** | Pointer to **NullableString** |  | [optional] 
**TaxNumber** | Pointer to **NullableString** |  | [optional] 
**TaxOffice** | Pointer to **NullableString** |  | [optional] 
**TotalInvoices** | Pointer to **NullableInt32** |  | [optional] 
**TotalRevenue** | Pointer to **NullableString** |  | [optional] 
**UpdatedAt** | Pointer to **NullableString** |  | [optional] [readonly] 
**VatId** | Pointer to **NullableString** |  | [optional] 
**VatIdValidated** | Pointer to **NullableBool** |  | [optional] 
**VatIdValidationDate** | Pointer to **NullableString** |  | [optional] 
**Website** | Pointer to **NullableString** |  | [optional] 
**Zip** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewContact

`func NewContact(contactId string, contactPersons interface{}, contactType string, createdAt string, name string, socialMedia interface{}, ) *Contact`

NewContact instantiates a new Contact object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactWithDefaults

`func NewContactWithDefaults() *Contact`

NewContactWithDefaults instantiates a new Contact object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccountHolder

`func (o *Contact) GetAccountHolder() string`

GetAccountHolder returns the AccountHolder field if non-nil, zero value otherwise.

### GetAccountHolderOk

`func (o *Contact) GetAccountHolderOk() (*string, bool)`

GetAccountHolderOk returns a tuple with the AccountHolder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccountHolder

`func (o *Contact) SetAccountHolder(v string)`

SetAccountHolder sets AccountHolder field to given value.

### HasAccountHolder

`func (o *Contact) HasAccountHolder() bool`

HasAccountHolder returns a boolean if a field has been set.

### SetAccountHolderNil

`func (o *Contact) SetAccountHolderNil(b bool)`

 SetAccountHolderNil sets the value for AccountHolder to be an explicit nil

### UnsetAccountHolder
`func (o *Contact) UnsetAccountHolder()`

UnsetAccountHolder ensures that no value is present for AccountHolder, not even an explicit nil
### GetAcquisitionCost

`func (o *Contact) GetAcquisitionCost() string`

GetAcquisitionCost returns the AcquisitionCost field if non-nil, zero value otherwise.

### GetAcquisitionCostOk

`func (o *Contact) GetAcquisitionCostOk() (*string, bool)`

GetAcquisitionCostOk returns a tuple with the AcquisitionCost field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAcquisitionCost

`func (o *Contact) SetAcquisitionCost(v string)`

SetAcquisitionCost sets AcquisitionCost field to given value.

### HasAcquisitionCost

`func (o *Contact) HasAcquisitionCost() bool`

HasAcquisitionCost returns a boolean if a field has been set.

### SetAcquisitionCostNil

`func (o *Contact) SetAcquisitionCostNil(b bool)`

 SetAcquisitionCostNil sets the value for AcquisitionCost to be an explicit nil

### UnsetAcquisitionCost
`func (o *Contact) UnsetAcquisitionCost()`

UnsetAcquisitionCost ensures that no value is present for AcquisitionCost, not even an explicit nil
### GetAddressSupplement

`func (o *Contact) GetAddressSupplement() string`

GetAddressSupplement returns the AddressSupplement field if non-nil, zero value otherwise.

### GetAddressSupplementOk

`func (o *Contact) GetAddressSupplementOk() (*string, bool)`

GetAddressSupplementOk returns a tuple with the AddressSupplement field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddressSupplement

`func (o *Contact) SetAddressSupplement(v string)`

SetAddressSupplement sets AddressSupplement field to given value.

### HasAddressSupplement

`func (o *Contact) HasAddressSupplement() bool`

HasAddressSupplement returns a boolean if a field has been set.

### SetAddressSupplementNil

`func (o *Contact) SetAddressSupplementNil(b bool)`

 SetAddressSupplementNil sets the value for AddressSupplement to be an explicit nil

### UnsetAddressSupplement
`func (o *Contact) UnsetAddressSupplement()`

UnsetAddressSupplement ensures that no value is present for AddressSupplement, not even an explicit nil
### GetAttention

`func (o *Contact) GetAttention() string`

GetAttention returns the Attention field if non-nil, zero value otherwise.

### GetAttentionOk

`func (o *Contact) GetAttentionOk() (*string, bool)`

GetAttentionOk returns a tuple with the Attention field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAttention

`func (o *Contact) SetAttention(v string)`

SetAttention sets Attention field to given value.

### HasAttention

`func (o *Contact) HasAttention() bool`

HasAttention returns a boolean if a field has been set.

### SetAttentionNil

`func (o *Contact) SetAttentionNil(b bool)`

 SetAttentionNil sets the value for Attention to be an explicit nil

### UnsetAttention
`func (o *Contact) UnsetAttention()`

UnsetAttention ensures that no value is present for Attention, not even an explicit nil
### GetBankName

`func (o *Contact) GetBankName() string`

GetBankName returns the BankName field if non-nil, zero value otherwise.

### GetBankNameOk

`func (o *Contact) GetBankNameOk() (*string, bool)`

GetBankNameOk returns a tuple with the BankName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBankName

`func (o *Contact) SetBankName(v string)`

SetBankName sets BankName field to given value.

### HasBankName

`func (o *Contact) HasBankName() bool`

HasBankName returns a boolean if a field has been set.

### SetBankNameNil

`func (o *Contact) SetBankNameNil(b bool)`

 SetBankNameNil sets the value for BankName to be an explicit nil

### UnsetBankName
`func (o *Contact) UnsetBankName()`

UnsetBankName ensures that no value is present for BankName, not even an explicit nil
### GetBic

`func (o *Contact) GetBic() string`

GetBic returns the Bic field if non-nil, zero value otherwise.

### GetBicOk

`func (o *Contact) GetBicOk() (*string, bool)`

GetBicOk returns a tuple with the Bic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBic

`func (o *Contact) SetBic(v string)`

SetBic sets Bic field to given value.

### HasBic

`func (o *Contact) HasBic() bool`

HasBic returns a boolean if a field has been set.

### SetBicNil

`func (o *Contact) SetBicNil(b bool)`

 SetBicNil sets the value for Bic to be an explicit nil

### UnsetBic
`func (o *Contact) UnsetBic()`

UnsetBic ensures that no value is present for Bic, not even an explicit nil
### GetBuyerReference

`func (o *Contact) GetBuyerReference() string`

GetBuyerReference returns the BuyerReference field if non-nil, zero value otherwise.

### GetBuyerReferenceOk

`func (o *Contact) GetBuyerReferenceOk() (*string, bool)`

GetBuyerReferenceOk returns a tuple with the BuyerReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBuyerReference

`func (o *Contact) SetBuyerReference(v string)`

SetBuyerReference sets BuyerReference field to given value.

### HasBuyerReference

`func (o *Contact) HasBuyerReference() bool`

HasBuyerReference returns a boolean if a field has been set.

### SetBuyerReferenceNil

`func (o *Contact) SetBuyerReferenceNil(b bool)`

 SetBuyerReferenceNil sets the value for BuyerReference to be an explicit nil

### UnsetBuyerReference
`func (o *Contact) UnsetBuyerReference()`

UnsetBuyerReference ensures that no value is present for BuyerReference, not even an explicit nil
### GetCategory

`func (o *Contact) GetCategory() string`

GetCategory returns the Category field if non-nil, zero value otherwise.

### GetCategoryOk

`func (o *Contact) GetCategoryOk() (*string, bool)`

GetCategoryOk returns a tuple with the Category field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCategory

`func (o *Contact) SetCategory(v string)`

SetCategory sets Category field to given value.

### HasCategory

`func (o *Contact) HasCategory() bool`

HasCategory returns a boolean if a field has been set.

### SetCategoryNil

`func (o *Contact) SetCategoryNil(b bool)`

 SetCategoryNil sets the value for Category to be an explicit nil

### UnsetCategory
`func (o *Contact) UnsetCategory()`

UnsetCategory ensures that no value is present for Category, not even an explicit nil
### GetCertificateAuthority

`func (o *Contact) GetCertificateAuthority() string`

GetCertificateAuthority returns the CertificateAuthority field if non-nil, zero value otherwise.

### GetCertificateAuthorityOk

`func (o *Contact) GetCertificateAuthorityOk() (*string, bool)`

GetCertificateAuthorityOk returns a tuple with the CertificateAuthority field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateAuthority

`func (o *Contact) SetCertificateAuthority(v string)`

SetCertificateAuthority sets CertificateAuthority field to given value.

### HasCertificateAuthority

`func (o *Contact) HasCertificateAuthority() bool`

HasCertificateAuthority returns a boolean if a field has been set.

### SetCertificateAuthorityNil

`func (o *Contact) SetCertificateAuthorityNil(b bool)`

 SetCertificateAuthorityNil sets the value for CertificateAuthority to be an explicit nil

### UnsetCertificateAuthority
`func (o *Contact) UnsetCertificateAuthority()`

UnsetCertificateAuthority ensures that no value is present for CertificateAuthority, not even an explicit nil
### GetCertificateNumber

`func (o *Contact) GetCertificateNumber() string`

GetCertificateNumber returns the CertificateNumber field if non-nil, zero value otherwise.

### GetCertificateNumberOk

`func (o *Contact) GetCertificateNumberOk() (*string, bool)`

GetCertificateNumberOk returns a tuple with the CertificateNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateNumber

`func (o *Contact) SetCertificateNumber(v string)`

SetCertificateNumber sets CertificateNumber field to given value.

### HasCertificateNumber

`func (o *Contact) HasCertificateNumber() bool`

HasCertificateNumber returns a boolean if a field has been set.

### SetCertificateNumberNil

`func (o *Contact) SetCertificateNumberNil(b bool)`

 SetCertificateNumberNil sets the value for CertificateNumber to be an explicit nil

### UnsetCertificateNumber
`func (o *Contact) UnsetCertificateNumber()`

UnsetCertificateNumber ensures that no value is present for CertificateNumber, not even an explicit nil
### GetCertificateParagraph

`func (o *Contact) GetCertificateParagraph() string`

GetCertificateParagraph returns the CertificateParagraph field if non-nil, zero value otherwise.

### GetCertificateParagraphOk

`func (o *Contact) GetCertificateParagraphOk() (*string, bool)`

GetCertificateParagraphOk returns a tuple with the CertificateParagraph field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateParagraph

`func (o *Contact) SetCertificateParagraph(v string)`

SetCertificateParagraph sets CertificateParagraph field to given value.

### HasCertificateParagraph

`func (o *Contact) HasCertificateParagraph() bool`

HasCertificateParagraph returns a boolean if a field has been set.

### SetCertificateParagraphNil

`func (o *Contact) SetCertificateParagraphNil(b bool)`

 SetCertificateParagraphNil sets the value for CertificateParagraph to be an explicit nil

### UnsetCertificateParagraph
`func (o *Contact) UnsetCertificateParagraph()`

UnsetCertificateParagraph ensures that no value is present for CertificateParagraph, not even an explicit nil
### GetCertificateValidUntil

`func (o *Contact) GetCertificateValidUntil() string`

GetCertificateValidUntil returns the CertificateValidUntil field if non-nil, zero value otherwise.

### GetCertificateValidUntilOk

`func (o *Contact) GetCertificateValidUntilOk() (*string, bool)`

GetCertificateValidUntilOk returns a tuple with the CertificateValidUntil field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificateValidUntil

`func (o *Contact) SetCertificateValidUntil(v string)`

SetCertificateValidUntil sets CertificateValidUntil field to given value.

### HasCertificateValidUntil

`func (o *Contact) HasCertificateValidUntil() bool`

HasCertificateValidUntil returns a boolean if a field has been set.

### SetCertificateValidUntilNil

`func (o *Contact) SetCertificateValidUntilNil(b bool)`

 SetCertificateValidUntilNil sets the value for CertificateValidUntil to be an explicit nil

### UnsetCertificateValidUntil
`func (o *Contact) UnsetCertificateValidUntil()`

UnsetCertificateValidUntil ensures that no value is present for CertificateValidUntil, not even an explicit nil
### GetCity

`func (o *Contact) GetCity() string`

GetCity returns the City field if non-nil, zero value otherwise.

### GetCityOk

`func (o *Contact) GetCityOk() (*string, bool)`

GetCityOk returns a tuple with the City field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCity

`func (o *Contact) SetCity(v string)`

SetCity sets City field to given value.

### HasCity

`func (o *Contact) HasCity() bool`

HasCity returns a boolean if a field has been set.

### SetCityNil

`func (o *Contact) SetCityNil(b bool)`

 SetCityNil sets the value for City to be an explicit nil

### UnsetCity
`func (o *Contact) UnsetCity()`

UnsetCity ensures that no value is present for City, not even an explicit nil
### GetCompanyName

`func (o *Contact) GetCompanyName() string`

GetCompanyName returns the CompanyName field if non-nil, zero value otherwise.

### GetCompanyNameOk

`func (o *Contact) GetCompanyNameOk() (*string, bool)`

GetCompanyNameOk returns a tuple with the CompanyName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompanyName

`func (o *Contact) SetCompanyName(v string)`

SetCompanyName sets CompanyName field to given value.

### HasCompanyName

`func (o *Contact) HasCompanyName() bool`

HasCompanyName returns a boolean if a field has been set.

### SetCompanyNameNil

`func (o *Contact) SetCompanyNameNil(b bool)`

 SetCompanyNameNil sets the value for CompanyName to be an explicit nil

### UnsetCompanyName
`func (o *Contact) UnsetCompanyName()`

UnsetCompanyName ensures that no value is present for CompanyName, not even an explicit nil
### GetContactId

`func (o *Contact) GetContactId() string`

GetContactId returns the ContactId field if non-nil, zero value otherwise.

### GetContactIdOk

`func (o *Contact) GetContactIdOk() (*string, bool)`

GetContactIdOk returns a tuple with the ContactId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactId

`func (o *Contact) SetContactId(v string)`

SetContactId sets ContactId field to given value.


### GetContactPersons

`func (o *Contact) GetContactPersons() interface{}`

GetContactPersons returns the ContactPersons field if non-nil, zero value otherwise.

### GetContactPersonsOk

`func (o *Contact) GetContactPersonsOk() (*interface{}, bool)`

GetContactPersonsOk returns a tuple with the ContactPersons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactPersons

`func (o *Contact) SetContactPersons(v interface{})`

SetContactPersons sets ContactPersons field to given value.


### SetContactPersonsNil

`func (o *Contact) SetContactPersonsNil(b bool)`

 SetContactPersonsNil sets the value for ContactPersons to be an explicit nil

### UnsetContactPersons
`func (o *Contact) UnsetContactPersons()`

UnsetContactPersons ensures that no value is present for ContactPersons, not even an explicit nil
### GetContactType

`func (o *Contact) GetContactType() string`

GetContactType returns the ContactType field if non-nil, zero value otherwise.

### GetContactTypeOk

`func (o *Contact) GetContactTypeOk() (*string, bool)`

GetContactTypeOk returns a tuple with the ContactType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContactType

`func (o *Contact) SetContactType(v string)`

SetContactType sets ContactType field to given value.


### GetCountry

`func (o *Contact) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *Contact) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *Contact) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *Contact) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *Contact) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *Contact) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetCreatedAt

`func (o *Contact) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *Contact) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *Contact) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetCreditLimit

`func (o *Contact) GetCreditLimit() string`

GetCreditLimit returns the CreditLimit field if non-nil, zero value otherwise.

### GetCreditLimitOk

`func (o *Contact) GetCreditLimitOk() (*string, bool)`

GetCreditLimitOk returns a tuple with the CreditLimit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditLimit

`func (o *Contact) SetCreditLimit(v string)`

SetCreditLimit sets CreditLimit field to given value.

### HasCreditLimit

`func (o *Contact) HasCreditLimit() bool`

HasCreditLimit returns a boolean if a field has been set.

### SetCreditLimitNil

`func (o *Contact) SetCreditLimitNil(b bool)`

 SetCreditLimitNil sets the value for CreditLimit to be an explicit nil

### UnsetCreditLimit
`func (o *Contact) UnsetCreditLimit()`

UnsetCreditLimit ensures that no value is present for CreditLimit, not even an explicit nil
### GetCreditorAccountSkr03

`func (o *Contact) GetCreditorAccountSkr03() string`

GetCreditorAccountSkr03 returns the CreditorAccountSkr03 field if non-nil, zero value otherwise.

### GetCreditorAccountSkr03Ok

`func (o *Contact) GetCreditorAccountSkr03Ok() (*string, bool)`

GetCreditorAccountSkr03Ok returns a tuple with the CreditorAccountSkr03 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditorAccountSkr03

`func (o *Contact) SetCreditorAccountSkr03(v string)`

SetCreditorAccountSkr03 sets CreditorAccountSkr03 field to given value.

### HasCreditorAccountSkr03

`func (o *Contact) HasCreditorAccountSkr03() bool`

HasCreditorAccountSkr03 returns a boolean if a field has been set.

### SetCreditorAccountSkr03Nil

`func (o *Contact) SetCreditorAccountSkr03Nil(b bool)`

 SetCreditorAccountSkr03Nil sets the value for CreditorAccountSkr03 to be an explicit nil

### UnsetCreditorAccountSkr03
`func (o *Contact) UnsetCreditorAccountSkr03()`

UnsetCreditorAccountSkr03 ensures that no value is present for CreditorAccountSkr03, not even an explicit nil
### GetCreditorAccountSkr04

`func (o *Contact) GetCreditorAccountSkr04() string`

GetCreditorAccountSkr04 returns the CreditorAccountSkr04 field if non-nil, zero value otherwise.

### GetCreditorAccountSkr04Ok

`func (o *Contact) GetCreditorAccountSkr04Ok() (*string, bool)`

GetCreditorAccountSkr04Ok returns a tuple with the CreditorAccountSkr04 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreditorAccountSkr04

`func (o *Contact) SetCreditorAccountSkr04(v string)`

SetCreditorAccountSkr04 sets CreditorAccountSkr04 field to given value.

### HasCreditorAccountSkr04

`func (o *Contact) HasCreditorAccountSkr04() bool`

HasCreditorAccountSkr04 returns a boolean if a field has been set.

### SetCreditorAccountSkr04Nil

`func (o *Contact) SetCreditorAccountSkr04Nil(b bool)`

 SetCreditorAccountSkr04Nil sets the value for CreditorAccountSkr04 to be an explicit nil

### UnsetCreditorAccountSkr04
`func (o *Contact) UnsetCreditorAccountSkr04()`

UnsetCreditorAccountSkr04 ensures that no value is present for CreditorAccountSkr04, not even an explicit nil
### GetCurrency

`func (o *Contact) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *Contact) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *Contact) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *Contact) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *Contact) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *Contact) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil
### GetCustomerNumber

`func (o *Contact) GetCustomerNumber() string`

GetCustomerNumber returns the CustomerNumber field if non-nil, zero value otherwise.

### GetCustomerNumberOk

`func (o *Contact) GetCustomerNumberOk() (*string, bool)`

GetCustomerNumberOk returns a tuple with the CustomerNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCustomerNumber

`func (o *Contact) SetCustomerNumber(v string)`

SetCustomerNumber sets CustomerNumber field to given value.

### HasCustomerNumber

`func (o *Contact) HasCustomerNumber() bool`

HasCustomerNumber returns a boolean if a field has been set.

### SetCustomerNumberNil

`func (o *Contact) SetCustomerNumberNil(b bool)`

 SetCustomerNumberNil sets the value for CustomerNumber to be an explicit nil

### UnsetCustomerNumber
`func (o *Contact) UnsetCustomerNumber()`

UnsetCustomerNumber ensures that no value is present for CustomerNumber, not even an explicit nil
### GetDebitorAccountSkr03

`func (o *Contact) GetDebitorAccountSkr03() string`

GetDebitorAccountSkr03 returns the DebitorAccountSkr03 field if non-nil, zero value otherwise.

### GetDebitorAccountSkr03Ok

`func (o *Contact) GetDebitorAccountSkr03Ok() (*string, bool)`

GetDebitorAccountSkr03Ok returns a tuple with the DebitorAccountSkr03 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebitorAccountSkr03

`func (o *Contact) SetDebitorAccountSkr03(v string)`

SetDebitorAccountSkr03 sets DebitorAccountSkr03 field to given value.

### HasDebitorAccountSkr03

`func (o *Contact) HasDebitorAccountSkr03() bool`

HasDebitorAccountSkr03 returns a boolean if a field has been set.

### SetDebitorAccountSkr03Nil

`func (o *Contact) SetDebitorAccountSkr03Nil(b bool)`

 SetDebitorAccountSkr03Nil sets the value for DebitorAccountSkr03 to be an explicit nil

### UnsetDebitorAccountSkr03
`func (o *Contact) UnsetDebitorAccountSkr03()`

UnsetDebitorAccountSkr03 ensures that no value is present for DebitorAccountSkr03, not even an explicit nil
### GetDebitorAccountSkr04

`func (o *Contact) GetDebitorAccountSkr04() string`

GetDebitorAccountSkr04 returns the DebitorAccountSkr04 field if non-nil, zero value otherwise.

### GetDebitorAccountSkr04Ok

`func (o *Contact) GetDebitorAccountSkr04Ok() (*string, bool)`

GetDebitorAccountSkr04Ok returns a tuple with the DebitorAccountSkr04 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDebitorAccountSkr04

`func (o *Contact) SetDebitorAccountSkr04(v string)`

SetDebitorAccountSkr04 sets DebitorAccountSkr04 field to given value.

### HasDebitorAccountSkr04

`func (o *Contact) HasDebitorAccountSkr04() bool`

HasDebitorAccountSkr04 returns a boolean if a field has been set.

### SetDebitorAccountSkr04Nil

`func (o *Contact) SetDebitorAccountSkr04Nil(b bool)`

 SetDebitorAccountSkr04Nil sets the value for DebitorAccountSkr04 to be an explicit nil

### UnsetDebitorAccountSkr04
`func (o *Contact) UnsetDebitorAccountSkr04()`

UnsetDebitorAccountSkr04 ensures that no value is present for DebitorAccountSkr04, not even an explicit nil
### GetDefaultDebitorNumber

`func (o *Contact) GetDefaultDebitorNumber() string`

GetDefaultDebitorNumber returns the DefaultDebitorNumber field if non-nil, zero value otherwise.

### GetDefaultDebitorNumberOk

`func (o *Contact) GetDefaultDebitorNumberOk() (*string, bool)`

GetDefaultDebitorNumberOk returns a tuple with the DefaultDebitorNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultDebitorNumber

`func (o *Contact) SetDefaultDebitorNumber(v string)`

SetDefaultDebitorNumber sets DefaultDebitorNumber field to given value.

### HasDefaultDebitorNumber

`func (o *Contact) HasDefaultDebitorNumber() bool`

HasDefaultDebitorNumber returns a boolean if a field has been set.

### SetDefaultDebitorNumberNil

`func (o *Contact) SetDefaultDebitorNumberNil(b bool)`

 SetDefaultDebitorNumberNil sets the value for DefaultDebitorNumber to be an explicit nil

### UnsetDefaultDebitorNumber
`func (o *Contact) UnsetDefaultDebitorNumber()`

UnsetDefaultDebitorNumber ensures that no value is present for DefaultDebitorNumber, not even an explicit nil
### GetDeliveryBlock

`func (o *Contact) GetDeliveryBlock() bool`

GetDeliveryBlock returns the DeliveryBlock field if non-nil, zero value otherwise.

### GetDeliveryBlockOk

`func (o *Contact) GetDeliveryBlockOk() (*bool, bool)`

GetDeliveryBlockOk returns a tuple with the DeliveryBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveryBlock

`func (o *Contact) SetDeliveryBlock(v bool)`

SetDeliveryBlock sets DeliveryBlock field to given value.

### HasDeliveryBlock

`func (o *Contact) HasDeliveryBlock() bool`

HasDeliveryBlock returns a boolean if a field has been set.

### SetDeliveryBlockNil

`func (o *Contact) SetDeliveryBlockNil(b bool)`

 SetDeliveryBlockNil sets the value for DeliveryBlock to be an explicit nil

### UnsetDeliveryBlock
`func (o *Contact) UnsetDeliveryBlock()`

UnsetDeliveryBlock ensures that no value is present for DeliveryBlock, not even an explicit nil
### GetDepartment

`func (o *Contact) GetDepartment() string`

GetDepartment returns the Department field if non-nil, zero value otherwise.

### GetDepartmentOk

`func (o *Contact) GetDepartmentOk() (*string, bool)`

GetDepartmentOk returns a tuple with the Department field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDepartment

`func (o *Contact) SetDepartment(v string)`

SetDepartment sets Department field to given value.

### HasDepartment

`func (o *Contact) HasDepartment() bool`

HasDepartment returns a boolean if a field has been set.

### SetDepartmentNil

`func (o *Contact) SetDepartmentNil(b bool)`

 SetDepartmentNil sets the value for Department to be an explicit nil

### UnsetDepartment
`func (o *Contact) UnsetDepartment()`

UnsetDepartment ensures that no value is present for Department, not even an explicit nil
### GetDiscountDays

`func (o *Contact) GetDiscountDays() int32`

GetDiscountDays returns the DiscountDays field if non-nil, zero value otherwise.

### GetDiscountDaysOk

`func (o *Contact) GetDiscountDaysOk() (*int32, bool)`

GetDiscountDaysOk returns a tuple with the DiscountDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountDays

`func (o *Contact) SetDiscountDays(v int32)`

SetDiscountDays sets DiscountDays field to given value.

### HasDiscountDays

`func (o *Contact) HasDiscountDays() bool`

HasDiscountDays returns a boolean if a field has been set.

### SetDiscountDaysNil

`func (o *Contact) SetDiscountDaysNil(b bool)`

 SetDiscountDaysNil sets the value for DiscountDays to be an explicit nil

### UnsetDiscountDays
`func (o *Contact) UnsetDiscountDays()`

UnsetDiscountDays ensures that no value is present for DiscountDays, not even an explicit nil
### GetDiscountPercentage

`func (o *Contact) GetDiscountPercentage() string`

GetDiscountPercentage returns the DiscountPercentage field if non-nil, zero value otherwise.

### GetDiscountPercentageOk

`func (o *Contact) GetDiscountPercentageOk() (*string, bool)`

GetDiscountPercentageOk returns a tuple with the DiscountPercentage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDiscountPercentage

`func (o *Contact) SetDiscountPercentage(v string)`

SetDiscountPercentage sets DiscountPercentage field to given value.

### HasDiscountPercentage

`func (o *Contact) HasDiscountPercentage() bool`

HasDiscountPercentage returns a boolean if a field has been set.

### SetDiscountPercentageNil

`func (o *Contact) SetDiscountPercentageNil(b bool)`

 SetDiscountPercentageNil sets the value for DiscountPercentage to be an explicit nil

### UnsetDiscountPercentage
`func (o *Contact) UnsetDiscountPercentage()`

UnsetDiscountPercentage ensures that no value is present for DiscountPercentage, not even an explicit nil
### GetDonationReceiptEligible

`func (o *Contact) GetDonationReceiptEligible() bool`

GetDonationReceiptEligible returns the DonationReceiptEligible field if non-nil, zero value otherwise.

### GetDonationReceiptEligibleOk

`func (o *Contact) GetDonationReceiptEligibleOk() (*bool, bool)`

GetDonationReceiptEligibleOk returns a tuple with the DonationReceiptEligible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDonationReceiptEligible

`func (o *Contact) SetDonationReceiptEligible(v bool)`

SetDonationReceiptEligible sets DonationReceiptEligible field to given value.

### HasDonationReceiptEligible

`func (o *Contact) HasDonationReceiptEligible() bool`

HasDonationReceiptEligible returns a boolean if a field has been set.

### SetDonationReceiptEligibleNil

`func (o *Contact) SetDonationReceiptEligibleNil(b bool)`

 SetDonationReceiptEligibleNil sets the value for DonationReceiptEligible to be an explicit nil

### UnsetDonationReceiptEligible
`func (o *Contact) UnsetDonationReceiptEligible()`

UnsetDonationReceiptEligible ensures that no value is present for DonationReceiptEligible, not even an explicit nil
### GetEmail

`func (o *Contact) GetEmail() string`

GetEmail returns the Email field if non-nil, zero value otherwise.

### GetEmailOk

`func (o *Contact) GetEmailOk() (*string, bool)`

GetEmailOk returns a tuple with the Email field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEmail

`func (o *Contact) SetEmail(v string)`

SetEmail sets Email field to given value.

### HasEmail

`func (o *Contact) HasEmail() bool`

HasEmail returns a boolean if a field has been set.

### SetEmailNil

`func (o *Contact) SetEmailNil(b bool)`

 SetEmailNil sets the value for Email to be an explicit nil

### UnsetEmail
`func (o *Contact) UnsetEmail()`

UnsetEmail ensures that no value is present for Email, not even an explicit nil
### GetExternalId

`func (o *Contact) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *Contact) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *Contact) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.

### HasExternalId

`func (o *Contact) HasExternalId() bool`

HasExternalId returns a boolean if a field has been set.

### SetExternalIdNil

`func (o *Contact) SetExternalIdNil(b bool)`

 SetExternalIdNil sets the value for ExternalId to be an explicit nil

### UnsetExternalId
`func (o *Contact) UnsetExternalId()`

UnsetExternalId ensures that no value is present for ExternalId, not even an explicit nil
### GetFax

`func (o *Contact) GetFax() string`

GetFax returns the Fax field if non-nil, zero value otherwise.

### GetFaxOk

`func (o *Contact) GetFaxOk() (*string, bool)`

GetFaxOk returns a tuple with the Fax field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFax

`func (o *Contact) SetFax(v string)`

SetFax sets Fax field to given value.

### HasFax

`func (o *Contact) HasFax() bool`

HasFax returns a boolean if a field has been set.

### SetFaxNil

`func (o *Contact) SetFaxNil(b bool)`

 SetFaxNil sets the value for Fax to be an explicit nil

### UnsetFax
`func (o *Contact) UnsetFax()`

UnsetFax ensures that no value is present for Fax, not even an explicit nil
### GetIban

`func (o *Contact) GetIban() string`

GetIban returns the Iban field if non-nil, zero value otherwise.

### GetIbanOk

`func (o *Contact) GetIbanOk() (*string, bool)`

GetIbanOk returns a tuple with the Iban field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIban

`func (o *Contact) SetIban(v string)`

SetIban sets Iban field to given value.

### HasIban

`func (o *Contact) HasIban() bool`

HasIban returns a boolean if a field has been set.

### SetIbanNil

`func (o *Contact) SetIbanNil(b bool)`

 SetIbanNil sets the value for Iban to be an explicit nil

### UnsetIban
`func (o *Contact) UnsetIban()`

UnsetIban ensures that no value is present for Iban, not even an explicit nil
### GetIndustry

`func (o *Contact) GetIndustry() string`

GetIndustry returns the Industry field if non-nil, zero value otherwise.

### GetIndustryOk

`func (o *Contact) GetIndustryOk() (*string, bool)`

GetIndustryOk returns a tuple with the Industry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndustry

`func (o *Contact) SetIndustry(v string)`

SetIndustry sets Industry field to given value.

### HasIndustry

`func (o *Contact) HasIndustry() bool`

HasIndustry returns a boolean if a field has been set.

### SetIndustryNil

`func (o *Contact) SetIndustryNil(b bool)`

 SetIndustryNil sets the value for Industry to be an explicit nil

### UnsetIndustry
`func (o *Contact) UnsetIndustry()`

UnsetIndustry ensures that no value is present for Industry, not even an explicit nil
### GetIsActive

`func (o *Contact) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *Contact) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *Contact) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *Contact) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### SetIsActiveNil

`func (o *Contact) SetIsActiveNil(b bool)`

 SetIsActiveNil sets the value for IsActive to be an explicit nil

### UnsetIsActive
`func (o *Contact) UnsetIsActive()`

UnsetIsActive ensures that no value is present for IsActive, not even an explicit nil
### GetIsMember

`func (o *Contact) GetIsMember() bool`

GetIsMember returns the IsMember field if non-nil, zero value otherwise.

### GetIsMemberOk

`func (o *Contact) GetIsMemberOk() (*bool, bool)`

GetIsMemberOk returns a tuple with the IsMember field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsMember

`func (o *Contact) SetIsMember(v bool)`

SetIsMember sets IsMember field to given value.

### HasIsMember

`func (o *Contact) HasIsMember() bool`

HasIsMember returns a boolean if a field has been set.

### SetIsMemberNil

`func (o *Contact) SetIsMemberNil(b bool)`

 SetIsMemberNil sets the value for IsMember to be an explicit nil

### UnsetIsMember
`func (o *Contact) UnsetIsMember()`

UnsetIsMember ensures that no value is present for IsMember, not even an explicit nil
### GetIsNonprofit

`func (o *Contact) GetIsNonprofit() bool`

GetIsNonprofit returns the IsNonprofit field if non-nil, zero value otherwise.

### GetIsNonprofitOk

`func (o *Contact) GetIsNonprofitOk() (*bool, bool)`

GetIsNonprofitOk returns a tuple with the IsNonprofit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsNonprofit

`func (o *Contact) SetIsNonprofit(v bool)`

SetIsNonprofit sets IsNonprofit field to given value.

### HasIsNonprofit

`func (o *Contact) HasIsNonprofit() bool`

HasIsNonprofit returns a boolean if a field has been set.

### SetIsNonprofitNil

`func (o *Contact) SetIsNonprofitNil(b bool)`

 SetIsNonprofitNil sets the value for IsNonprofit to be an explicit nil

### UnsetIsNonprofit
`func (o *Contact) UnsetIsNonprofit()`

UnsetIsNonprofit ensures that no value is present for IsNonprofit, not even an explicit nil
### GetLastContactDate

`func (o *Contact) GetLastContactDate() string`

GetLastContactDate returns the LastContactDate field if non-nil, zero value otherwise.

### GetLastContactDateOk

`func (o *Contact) GetLastContactDateOk() (*string, bool)`

GetLastContactDateOk returns a tuple with the LastContactDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastContactDate

`func (o *Contact) SetLastContactDate(v string)`

SetLastContactDate sets LastContactDate field to given value.

### HasLastContactDate

`func (o *Contact) HasLastContactDate() bool`

HasLastContactDate returns a boolean if a field has been set.

### SetLastContactDateNil

`func (o *Contact) SetLastContactDateNil(b bool)`

 SetLastContactDateNil sets the value for LastContactDate to be an explicit nil

### UnsetLastContactDate
`func (o *Contact) UnsetLastContactDate()`

UnsetLastContactDate ensures that no value is present for LastContactDate, not even an explicit nil
### GetLastPurchaseDate

`func (o *Contact) GetLastPurchaseDate() string`

GetLastPurchaseDate returns the LastPurchaseDate field if non-nil, zero value otherwise.

### GetLastPurchaseDateOk

`func (o *Contact) GetLastPurchaseDateOk() (*string, bool)`

GetLastPurchaseDateOk returns a tuple with the LastPurchaseDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastPurchaseDate

`func (o *Contact) SetLastPurchaseDate(v string)`

SetLastPurchaseDate sets LastPurchaseDate field to given value.

### HasLastPurchaseDate

`func (o *Contact) HasLastPurchaseDate() bool`

HasLastPurchaseDate returns a boolean if a field has been set.

### SetLastPurchaseDateNil

`func (o *Contact) SetLastPurchaseDateNil(b bool)`

 SetLastPurchaseDateNil sets the value for LastPurchaseDate to be an explicit nil

### UnsetLastPurchaseDate
`func (o *Contact) UnsetLastPurchaseDate()`

UnsetLastPurchaseDate ensures that no value is present for LastPurchaseDate, not even an explicit nil
### GetLeitwegId

`func (o *Contact) GetLeitwegId() string`

GetLeitwegId returns the LeitwegId field if non-nil, zero value otherwise.

### GetLeitwegIdOk

`func (o *Contact) GetLeitwegIdOk() (*string, bool)`

GetLeitwegIdOk returns a tuple with the LeitwegId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLeitwegId

`func (o *Contact) SetLeitwegId(v string)`

SetLeitwegId sets LeitwegId field to given value.

### HasLeitwegId

`func (o *Contact) HasLeitwegId() bool`

HasLeitwegId returns a boolean if a field has been set.

### SetLeitwegIdNil

`func (o *Contact) SetLeitwegIdNil(b bool)`

 SetLeitwegIdNil sets the value for LeitwegId to be an explicit nil

### UnsetLeitwegId
`func (o *Contact) UnsetLeitwegId()`

UnsetLeitwegId ensures that no value is present for LeitwegId, not even an explicit nil
### GetLifetimeValue

`func (o *Contact) GetLifetimeValue() string`

GetLifetimeValue returns the LifetimeValue field if non-nil, zero value otherwise.

### GetLifetimeValueOk

`func (o *Contact) GetLifetimeValueOk() (*string, bool)`

GetLifetimeValueOk returns a tuple with the LifetimeValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLifetimeValue

`func (o *Contact) SetLifetimeValue(v string)`

SetLifetimeValue sets LifetimeValue field to given value.

### HasLifetimeValue

`func (o *Contact) HasLifetimeValue() bool`

HasLifetimeValue returns a boolean if a field has been set.

### SetLifetimeValueNil

`func (o *Contact) SetLifetimeValueNil(b bool)`

 SetLifetimeValueNil sets the value for LifetimeValue to be an explicit nil

### UnsetLifetimeValue
`func (o *Contact) UnsetLifetimeValue()`

UnsetLifetimeValue ensures that no value is present for LifetimeValue, not even an explicit nil
### GetMandateDate

`func (o *Contact) GetMandateDate() string`

GetMandateDate returns the MandateDate field if non-nil, zero value otherwise.

### GetMandateDateOk

`func (o *Contact) GetMandateDateOk() (*string, bool)`

GetMandateDateOk returns a tuple with the MandateDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMandateDate

`func (o *Contact) SetMandateDate(v string)`

SetMandateDate sets MandateDate field to given value.

### HasMandateDate

`func (o *Contact) HasMandateDate() bool`

HasMandateDate returns a boolean if a field has been set.

### SetMandateDateNil

`func (o *Contact) SetMandateDateNil(b bool)`

 SetMandateDateNil sets the value for MandateDate to be an explicit nil

### UnsetMandateDate
`func (o *Contact) UnsetMandateDate()`

UnsetMandateDate ensures that no value is present for MandateDate, not even an explicit nil
### GetMandateReference

`func (o *Contact) GetMandateReference() string`

GetMandateReference returns the MandateReference field if non-nil, zero value otherwise.

### GetMandateReferenceOk

`func (o *Contact) GetMandateReferenceOk() (*string, bool)`

GetMandateReferenceOk returns a tuple with the MandateReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMandateReference

`func (o *Contact) SetMandateReference(v string)`

SetMandateReference sets MandateReference field to given value.

### HasMandateReference

`func (o *Contact) HasMandateReference() bool`

HasMandateReference returns a boolean if a field has been set.

### SetMandateReferenceNil

`func (o *Contact) SetMandateReferenceNil(b bool)`

 SetMandateReferenceNil sets the value for MandateReference to be an explicit nil

### UnsetMandateReference
`func (o *Contact) UnsetMandateReference()`

UnsetMandateReference ensures that no value is present for MandateReference, not even an explicit nil
### GetMarketingConsent

`func (o *Contact) GetMarketingConsent() bool`

GetMarketingConsent returns the MarketingConsent field if non-nil, zero value otherwise.

### GetMarketingConsentOk

`func (o *Contact) GetMarketingConsentOk() (*bool, bool)`

GetMarketingConsentOk returns a tuple with the MarketingConsent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarketingConsent

`func (o *Contact) SetMarketingConsent(v bool)`

SetMarketingConsent sets MarketingConsent field to given value.

### HasMarketingConsent

`func (o *Contact) HasMarketingConsent() bool`

HasMarketingConsent returns a boolean if a field has been set.

### SetMarketingConsentNil

`func (o *Contact) SetMarketingConsentNil(b bool)`

 SetMarketingConsentNil sets the value for MarketingConsent to be an explicit nil

### UnsetMarketingConsent
`func (o *Contact) UnsetMarketingConsent()`

UnsetMarketingConsent ensures that no value is present for MarketingConsent, not even an explicit nil
### GetMarketingConsentAt

`func (o *Contact) GetMarketingConsentAt() string`

GetMarketingConsentAt returns the MarketingConsentAt field if non-nil, zero value otherwise.

### GetMarketingConsentAtOk

`func (o *Contact) GetMarketingConsentAtOk() (*string, bool)`

GetMarketingConsentAtOk returns a tuple with the MarketingConsentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarketingConsentAt

`func (o *Contact) SetMarketingConsentAt(v string)`

SetMarketingConsentAt sets MarketingConsentAt field to given value.

### HasMarketingConsentAt

`func (o *Contact) HasMarketingConsentAt() bool`

HasMarketingConsentAt returns a boolean if a field has been set.

### SetMarketingConsentAtNil

`func (o *Contact) SetMarketingConsentAtNil(b bool)`

 SetMarketingConsentAtNil sets the value for MarketingConsentAt to be an explicit nil

### UnsetMarketingConsentAt
`func (o *Contact) UnsetMarketingConsentAt()`

UnsetMarketingConsentAt ensures that no value is present for MarketingConsentAt, not even an explicit nil
### GetMarketingConsentSource

`func (o *Contact) GetMarketingConsentSource() string`

GetMarketingConsentSource returns the MarketingConsentSource field if non-nil, zero value otherwise.

### GetMarketingConsentSourceOk

`func (o *Contact) GetMarketingConsentSourceOk() (*string, bool)`

GetMarketingConsentSourceOk returns a tuple with the MarketingConsentSource field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarketingConsentSource

`func (o *Contact) SetMarketingConsentSource(v string)`

SetMarketingConsentSource sets MarketingConsentSource field to given value.

### HasMarketingConsentSource

`func (o *Contact) HasMarketingConsentSource() bool`

HasMarketingConsentSource returns a boolean if a field has been set.

### SetMarketingConsentSourceNil

`func (o *Contact) SetMarketingConsentSourceNil(b bool)`

 SetMarketingConsentSourceNil sets the value for MarketingConsentSource to be an explicit nil

### UnsetMarketingConsentSource
`func (o *Contact) UnsetMarketingConsentSource()`

UnsetMarketingConsentSource ensures that no value is present for MarketingConsentSource, not even an explicit nil
### GetMobile

`func (o *Contact) GetMobile() string`

GetMobile returns the Mobile field if non-nil, zero value otherwise.

### GetMobileOk

`func (o *Contact) GetMobileOk() (*string, bool)`

GetMobileOk returns a tuple with the Mobile field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMobile

`func (o *Contact) SetMobile(v string)`

SetMobile sets Mobile field to given value.

### HasMobile

`func (o *Contact) HasMobile() bool`

HasMobile returns a boolean if a field has been set.

### SetMobileNil

`func (o *Contact) SetMobileNil(b bool)`

 SetMobileNil sets the value for Mobile to be an explicit nil

### UnsetMobile
`func (o *Contact) UnsetMobile()`

UnsetMobile ensures that no value is present for Mobile, not even an explicit nil
### GetName

`func (o *Contact) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *Contact) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *Contact) SetName(v string)`

SetName sets Name field to given value.


### GetNextContactDate

`func (o *Contact) GetNextContactDate() string`

GetNextContactDate returns the NextContactDate field if non-nil, zero value otherwise.

### GetNextContactDateOk

`func (o *Contact) GetNextContactDateOk() (*string, bool)`

GetNextContactDateOk returns a tuple with the NextContactDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNextContactDate

`func (o *Contact) SetNextContactDate(v string)`

SetNextContactDate sets NextContactDate field to given value.

### HasNextContactDate

`func (o *Contact) HasNextContactDate() bool`

HasNextContactDate returns a boolean if a field has been set.

### SetNextContactDateNil

`func (o *Contact) SetNextContactDateNil(b bool)`

 SetNextContactDateNil sets the value for NextContactDate to be an explicit nil

### UnsetNextContactDate
`func (o *Contact) UnsetNextContactDate()`

UnsetNextContactDate ensures that no value is present for NextContactDate, not even an explicit nil
### GetNotes

`func (o *Contact) GetNotes() string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *Contact) GetNotesOk() (*string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *Contact) SetNotes(v string)`

SetNotes sets Notes field to given value.

### HasNotes

`func (o *Contact) HasNotes() bool`

HasNotes returns a boolean if a field has been set.

### SetNotesNil

`func (o *Contact) SetNotesNil(b bool)`

 SetNotesNil sets the value for Notes to be an explicit nil

### UnsetNotes
`func (o *Contact) UnsetNotes()`

UnsetNotes ensures that no value is present for Notes, not even an explicit nil
### GetOpeningBalance

`func (o *Contact) GetOpeningBalance() string`

GetOpeningBalance returns the OpeningBalance field if non-nil, zero value otherwise.

### GetOpeningBalanceOk

`func (o *Contact) GetOpeningBalanceOk() (*string, bool)`

GetOpeningBalanceOk returns a tuple with the OpeningBalance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpeningBalance

`func (o *Contact) SetOpeningBalance(v string)`

SetOpeningBalance sets OpeningBalance field to given value.

### HasOpeningBalance

`func (o *Contact) HasOpeningBalance() bool`

HasOpeningBalance returns a boolean if a field has been set.

### SetOpeningBalanceNil

`func (o *Contact) SetOpeningBalanceNil(b bool)`

 SetOpeningBalanceNil sets the value for OpeningBalance to be an explicit nil

### UnsetOpeningBalance
`func (o *Contact) UnsetOpeningBalance()`

UnsetOpeningBalance ensures that no value is present for OpeningBalance, not even an explicit nil
### GetOpeningBalanceDate

`func (o *Contact) GetOpeningBalanceDate() string`

GetOpeningBalanceDate returns the OpeningBalanceDate field if non-nil, zero value otherwise.

### GetOpeningBalanceDateOk

`func (o *Contact) GetOpeningBalanceDateOk() (*string, bool)`

GetOpeningBalanceDateOk returns a tuple with the OpeningBalanceDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOpeningBalanceDate

`func (o *Contact) SetOpeningBalanceDate(v string)`

SetOpeningBalanceDate sets OpeningBalanceDate field to given value.

### HasOpeningBalanceDate

`func (o *Contact) HasOpeningBalanceDate() bool`

HasOpeningBalanceDate returns a boolean if a field has been set.

### SetOpeningBalanceDateNil

`func (o *Contact) SetOpeningBalanceDateNil(b bool)`

 SetOpeningBalanceDateNil sets the value for OpeningBalanceDate to be an explicit nil

### UnsetOpeningBalanceDate
`func (o *Contact) UnsetOpeningBalanceDate()`

UnsetOpeningBalanceDate ensures that no value is present for OpeningBalanceDate, not even an explicit nil
### GetOrderReference

`func (o *Contact) GetOrderReference() string`

GetOrderReference returns the OrderReference field if non-nil, zero value otherwise.

### GetOrderReferenceOk

`func (o *Contact) GetOrderReferenceOk() (*string, bool)`

GetOrderReferenceOk returns a tuple with the OrderReference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrderReference

`func (o *Contact) SetOrderReference(v string)`

SetOrderReference sets OrderReference field to given value.

### HasOrderReference

`func (o *Contact) HasOrderReference() bool`

HasOrderReference returns a boolean if a field has been set.

### SetOrderReferenceNil

`func (o *Contact) SetOrderReferenceNil(b bool)`

 SetOrderReferenceNil sets the value for OrderReference to be an explicit nil

### UnsetOrderReference
`func (o *Contact) UnsetOrderReference()`

UnsetOrderReference ensures that no value is present for OrderReference, not even an explicit nil
### GetPaymentBlock

`func (o *Contact) GetPaymentBlock() bool`

GetPaymentBlock returns the PaymentBlock field if non-nil, zero value otherwise.

### GetPaymentBlockOk

`func (o *Contact) GetPaymentBlockOk() (*bool, bool)`

GetPaymentBlockOk returns a tuple with the PaymentBlock field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentBlock

`func (o *Contact) SetPaymentBlock(v bool)`

SetPaymentBlock sets PaymentBlock field to given value.

### HasPaymentBlock

`func (o *Contact) HasPaymentBlock() bool`

HasPaymentBlock returns a boolean if a field has been set.

### SetPaymentBlockNil

`func (o *Contact) SetPaymentBlockNil(b bool)`

 SetPaymentBlockNil sets the value for PaymentBlock to be an explicit nil

### UnsetPaymentBlock
`func (o *Contact) UnsetPaymentBlock()`

UnsetPaymentBlock ensures that no value is present for PaymentBlock, not even an explicit nil
### GetPaymentGracePeriodDays

`func (o *Contact) GetPaymentGracePeriodDays() int32`

GetPaymentGracePeriodDays returns the PaymentGracePeriodDays field if non-nil, zero value otherwise.

### GetPaymentGracePeriodDaysOk

`func (o *Contact) GetPaymentGracePeriodDaysOk() (*int32, bool)`

GetPaymentGracePeriodDaysOk returns a tuple with the PaymentGracePeriodDays field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentGracePeriodDays

`func (o *Contact) SetPaymentGracePeriodDays(v int32)`

SetPaymentGracePeriodDays sets PaymentGracePeriodDays field to given value.

### HasPaymentGracePeriodDays

`func (o *Contact) HasPaymentGracePeriodDays() bool`

HasPaymentGracePeriodDays returns a boolean if a field has been set.

### SetPaymentGracePeriodDaysNil

`func (o *Contact) SetPaymentGracePeriodDaysNil(b bool)`

 SetPaymentGracePeriodDaysNil sets the value for PaymentGracePeriodDays to be an explicit nil

### UnsetPaymentGracePeriodDays
`func (o *Contact) UnsetPaymentGracePeriodDays()`

UnsetPaymentGracePeriodDays ensures that no value is present for PaymentGracePeriodDays, not even an explicit nil
### GetPaymentMethods

`func (o *Contact) GetPaymentMethods() []string`

GetPaymentMethods returns the PaymentMethods field if non-nil, zero value otherwise.

### GetPaymentMethodsOk

`func (o *Contact) GetPaymentMethodsOk() (*[]string, bool)`

GetPaymentMethodsOk returns a tuple with the PaymentMethods field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentMethods

`func (o *Contact) SetPaymentMethods(v []string)`

SetPaymentMethods sets PaymentMethods field to given value.

### HasPaymentMethods

`func (o *Contact) HasPaymentMethods() bool`

HasPaymentMethods returns a boolean if a field has been set.

### SetPaymentMethodsNil

`func (o *Contact) SetPaymentMethodsNil(b bool)`

 SetPaymentMethodsNil sets the value for PaymentMethods to be an explicit nil

### UnsetPaymentMethods
`func (o *Contact) UnsetPaymentMethods()`

UnsetPaymentMethods ensures that no value is present for PaymentMethods, not even an explicit nil
### GetPaymentTerms

`func (o *Contact) GetPaymentTerms() string`

GetPaymentTerms returns the PaymentTerms field if non-nil, zero value otherwise.

### GetPaymentTermsOk

`func (o *Contact) GetPaymentTermsOk() (*string, bool)`

GetPaymentTermsOk returns a tuple with the PaymentTerms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaymentTerms

`func (o *Contact) SetPaymentTerms(v string)`

SetPaymentTerms sets PaymentTerms field to given value.

### HasPaymentTerms

`func (o *Contact) HasPaymentTerms() bool`

HasPaymentTerms returns a boolean if a field has been set.

### SetPaymentTermsNil

`func (o *Contact) SetPaymentTermsNil(b bool)`

 SetPaymentTermsNil sets the value for PaymentTerms to be an explicit nil

### UnsetPaymentTerms
`func (o *Contact) UnsetPaymentTerms()`

UnsetPaymentTerms ensures that no value is present for PaymentTerms, not even an explicit nil
### GetPhone

`func (o *Contact) GetPhone() string`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *Contact) GetPhoneOk() (*string, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *Contact) SetPhone(v string)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *Contact) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### SetPhoneNil

`func (o *Contact) SetPhoneNil(b bool)`

 SetPhoneNil sets the value for Phone to be an explicit nil

### UnsetPhone
`func (o *Contact) UnsetPhone()`

UnsetPhone ensures that no value is present for Phone, not even an explicit nil
### GetRating

`func (o *Contact) GetRating() int32`

GetRating returns the Rating field if non-nil, zero value otherwise.

### GetRatingOk

`func (o *Contact) GetRatingOk() (*int32, bool)`

GetRatingOk returns a tuple with the Rating field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRating

`func (o *Contact) SetRating(v int32)`

SetRating sets Rating field to given value.

### HasRating

`func (o *Contact) HasRating() bool`

HasRating returns a boolean if a field has been set.

### SetRatingNil

`func (o *Contact) SetRatingNil(b bool)`

 SetRatingNil sets the value for Rating to be an explicit nil

### UnsetRating
`func (o *Contact) UnsetRating()`

UnsetRating ensures that no value is present for Rating, not even an explicit nil
### GetSalesRepresentative

`func (o *Contact) GetSalesRepresentative() string`

GetSalesRepresentative returns the SalesRepresentative field if non-nil, zero value otherwise.

### GetSalesRepresentativeOk

`func (o *Contact) GetSalesRepresentativeOk() (*string, bool)`

GetSalesRepresentativeOk returns a tuple with the SalesRepresentative field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSalesRepresentative

`func (o *Contact) SetSalesRepresentative(v string)`

SetSalesRepresentative sets SalesRepresentative field to given value.

### HasSalesRepresentative

`func (o *Contact) HasSalesRepresentative() bool`

HasSalesRepresentative returns a boolean if a field has been set.

### SetSalesRepresentativeNil

`func (o *Contact) SetSalesRepresentativeNil(b bool)`

 SetSalesRepresentativeNil sets the value for SalesRepresentative to be an explicit nil

### UnsetSalesRepresentative
`func (o *Contact) UnsetSalesRepresentative()`

UnsetSalesRepresentative ensures that no value is present for SalesRepresentative, not even an explicit nil
### GetSocialMedia

`func (o *Contact) GetSocialMedia() interface{}`

GetSocialMedia returns the SocialMedia field if non-nil, zero value otherwise.

### GetSocialMediaOk

`func (o *Contact) GetSocialMediaOk() (*interface{}, bool)`

GetSocialMediaOk returns a tuple with the SocialMedia field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSocialMedia

`func (o *Contact) SetSocialMedia(v interface{})`

SetSocialMedia sets SocialMedia field to given value.


### SetSocialMediaNil

`func (o *Contact) SetSocialMediaNil(b bool)`

 SetSocialMediaNil sets the value for SocialMedia to be an explicit nil

### UnsetSocialMedia
`func (o *Contact) UnsetSocialMedia()`

UnsetSocialMedia ensures that no value is present for SocialMedia, not even an explicit nil
### GetSource

`func (o *Contact) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *Contact) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *Contact) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *Contact) HasSource() bool`

HasSource returns a boolean if a field has been set.

### SetSourceNil

`func (o *Contact) SetSourceNil(b bool)`

 SetSourceNil sets the value for Source to be an explicit nil

### UnsetSource
`func (o *Contact) UnsetSource()`

UnsetSource ensures that no value is present for Source, not even an explicit nil
### GetState

`func (o *Contact) GetState() string`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *Contact) GetStateOk() (*string, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *Contact) SetState(v string)`

SetState sets State field to given value.

### HasState

`func (o *Contact) HasState() bool`

HasState returns a boolean if a field has been set.

### SetStateNil

`func (o *Contact) SetStateNil(b bool)`

 SetStateNil sets the value for State to be an explicit nil

### UnsetState
`func (o *Contact) UnsetState()`

UnsetState ensures that no value is present for State, not even an explicit nil
### GetStreet

`func (o *Contact) GetStreet() string`

GetStreet returns the Street field if non-nil, zero value otherwise.

### GetStreetOk

`func (o *Contact) GetStreetOk() (*string, bool)`

GetStreetOk returns a tuple with the Street field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStreet

`func (o *Contact) SetStreet(v string)`

SetStreet sets Street field to given value.

### HasStreet

`func (o *Contact) HasStreet() bool`

HasStreet returns a boolean if a field has been set.

### SetStreetNil

`func (o *Contact) SetStreetNil(b bool)`

 SetStreetNil sets the value for Street to be an explicit nil

### UnsetStreet
`func (o *Contact) UnsetStreet()`

UnsetStreet ensures that no value is present for Street, not even an explicit nil
### GetStreetNumber

`func (o *Contact) GetStreetNumber() string`

GetStreetNumber returns the StreetNumber field if non-nil, zero value otherwise.

### GetStreetNumberOk

`func (o *Contact) GetStreetNumberOk() (*string, bool)`

GetStreetNumberOk returns a tuple with the StreetNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStreetNumber

`func (o *Contact) SetStreetNumber(v string)`

SetStreetNumber sets StreetNumber field to given value.

### HasStreetNumber

`func (o *Contact) HasStreetNumber() bool`

HasStreetNumber returns a boolean if a field has been set.

### SetStreetNumberNil

`func (o *Contact) SetStreetNumberNil(b bool)`

 SetStreetNumberNil sets the value for StreetNumber to be an explicit nil

### UnsetStreetNumber
`func (o *Contact) UnsetStreetNumber()`

UnsetStreetNumber ensures that no value is present for StreetNumber, not even an explicit nil
### GetSupplierNumber

`func (o *Contact) GetSupplierNumber() string`

GetSupplierNumber returns the SupplierNumber field if non-nil, zero value otherwise.

### GetSupplierNumberOk

`func (o *Contact) GetSupplierNumberOk() (*string, bool)`

GetSupplierNumberOk returns a tuple with the SupplierNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSupplierNumber

`func (o *Contact) SetSupplierNumber(v string)`

SetSupplierNumber sets SupplierNumber field to given value.

### HasSupplierNumber

`func (o *Contact) HasSupplierNumber() bool`

HasSupplierNumber returns a boolean if a field has been set.

### SetSupplierNumberNil

`func (o *Contact) SetSupplierNumberNil(b bool)`

 SetSupplierNumberNil sets the value for SupplierNumber to be an explicit nil

### UnsetSupplierNumber
`func (o *Contact) UnsetSupplierNumber()`

UnsetSupplierNumber ensures that no value is present for SupplierNumber, not even an explicit nil
### GetTags

`func (o *Contact) GetTags() []string`

GetTags returns the Tags field if non-nil, zero value otherwise.

### GetTagsOk

`func (o *Contact) GetTagsOk() (*[]string, bool)`

GetTagsOk returns a tuple with the Tags field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTags

`func (o *Contact) SetTags(v []string)`

SetTags sets Tags field to given value.

### HasTags

`func (o *Contact) HasTags() bool`

HasTags returns a boolean if a field has been set.

### SetTagsNil

`func (o *Contact) SetTagsNil(b bool)`

 SetTagsNil sets the value for Tags to be an explicit nil

### UnsetTags
`func (o *Contact) UnsetTags()`

UnsetTags ensures that no value is present for Tags, not even an explicit nil
### GetTaxCountry

`func (o *Contact) GetTaxCountry() string`

GetTaxCountry returns the TaxCountry field if non-nil, zero value otherwise.

### GetTaxCountryOk

`func (o *Contact) GetTaxCountryOk() (*string, bool)`

GetTaxCountryOk returns a tuple with the TaxCountry field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxCountry

`func (o *Contact) SetTaxCountry(v string)`

SetTaxCountry sets TaxCountry field to given value.

### HasTaxCountry

`func (o *Contact) HasTaxCountry() bool`

HasTaxCountry returns a boolean if a field has been set.

### SetTaxCountryNil

`func (o *Contact) SetTaxCountryNil(b bool)`

 SetTaxCountryNil sets the value for TaxCountry to be an explicit nil

### UnsetTaxCountry
`func (o *Contact) UnsetTaxCountry()`

UnsetTaxCountry ensures that no value is present for TaxCountry, not even an explicit nil
### GetTaxNumber

`func (o *Contact) GetTaxNumber() string`

GetTaxNumber returns the TaxNumber field if non-nil, zero value otherwise.

### GetTaxNumberOk

`func (o *Contact) GetTaxNumberOk() (*string, bool)`

GetTaxNumberOk returns a tuple with the TaxNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxNumber

`func (o *Contact) SetTaxNumber(v string)`

SetTaxNumber sets TaxNumber field to given value.

### HasTaxNumber

`func (o *Contact) HasTaxNumber() bool`

HasTaxNumber returns a boolean if a field has been set.

### SetTaxNumberNil

`func (o *Contact) SetTaxNumberNil(b bool)`

 SetTaxNumberNil sets the value for TaxNumber to be an explicit nil

### UnsetTaxNumber
`func (o *Contact) UnsetTaxNumber()`

UnsetTaxNumber ensures that no value is present for TaxNumber, not even an explicit nil
### GetTaxOffice

`func (o *Contact) GetTaxOffice() string`

GetTaxOffice returns the TaxOffice field if non-nil, zero value otherwise.

### GetTaxOfficeOk

`func (o *Contact) GetTaxOfficeOk() (*string, bool)`

GetTaxOfficeOk returns a tuple with the TaxOffice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaxOffice

`func (o *Contact) SetTaxOffice(v string)`

SetTaxOffice sets TaxOffice field to given value.

### HasTaxOffice

`func (o *Contact) HasTaxOffice() bool`

HasTaxOffice returns a boolean if a field has been set.

### SetTaxOfficeNil

`func (o *Contact) SetTaxOfficeNil(b bool)`

 SetTaxOfficeNil sets the value for TaxOffice to be an explicit nil

### UnsetTaxOffice
`func (o *Contact) UnsetTaxOffice()`

UnsetTaxOffice ensures that no value is present for TaxOffice, not even an explicit nil
### GetTotalInvoices

`func (o *Contact) GetTotalInvoices() int32`

GetTotalInvoices returns the TotalInvoices field if non-nil, zero value otherwise.

### GetTotalInvoicesOk

`func (o *Contact) GetTotalInvoicesOk() (*int32, bool)`

GetTotalInvoicesOk returns a tuple with the TotalInvoices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalInvoices

`func (o *Contact) SetTotalInvoices(v int32)`

SetTotalInvoices sets TotalInvoices field to given value.

### HasTotalInvoices

`func (o *Contact) HasTotalInvoices() bool`

HasTotalInvoices returns a boolean if a field has been set.

### SetTotalInvoicesNil

`func (o *Contact) SetTotalInvoicesNil(b bool)`

 SetTotalInvoicesNil sets the value for TotalInvoices to be an explicit nil

### UnsetTotalInvoices
`func (o *Contact) UnsetTotalInvoices()`

UnsetTotalInvoices ensures that no value is present for TotalInvoices, not even an explicit nil
### GetTotalRevenue

`func (o *Contact) GetTotalRevenue() string`

GetTotalRevenue returns the TotalRevenue field if non-nil, zero value otherwise.

### GetTotalRevenueOk

`func (o *Contact) GetTotalRevenueOk() (*string, bool)`

GetTotalRevenueOk returns a tuple with the TotalRevenue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalRevenue

`func (o *Contact) SetTotalRevenue(v string)`

SetTotalRevenue sets TotalRevenue field to given value.

### HasTotalRevenue

`func (o *Contact) HasTotalRevenue() bool`

HasTotalRevenue returns a boolean if a field has been set.

### SetTotalRevenueNil

`func (o *Contact) SetTotalRevenueNil(b bool)`

 SetTotalRevenueNil sets the value for TotalRevenue to be an explicit nil

### UnsetTotalRevenue
`func (o *Contact) UnsetTotalRevenue()`

UnsetTotalRevenue ensures that no value is present for TotalRevenue, not even an explicit nil
### GetUpdatedAt

`func (o *Contact) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *Contact) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *Contact) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *Contact) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### SetUpdatedAtNil

`func (o *Contact) SetUpdatedAtNil(b bool)`

 SetUpdatedAtNil sets the value for UpdatedAt to be an explicit nil

### UnsetUpdatedAt
`func (o *Contact) UnsetUpdatedAt()`

UnsetUpdatedAt ensures that no value is present for UpdatedAt, not even an explicit nil
### GetVatId

`func (o *Contact) GetVatId() string`

GetVatId returns the VatId field if non-nil, zero value otherwise.

### GetVatIdOk

`func (o *Contact) GetVatIdOk() (*string, bool)`

GetVatIdOk returns a tuple with the VatId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatId

`func (o *Contact) SetVatId(v string)`

SetVatId sets VatId field to given value.

### HasVatId

`func (o *Contact) HasVatId() bool`

HasVatId returns a boolean if a field has been set.

### SetVatIdNil

`func (o *Contact) SetVatIdNil(b bool)`

 SetVatIdNil sets the value for VatId to be an explicit nil

### UnsetVatId
`func (o *Contact) UnsetVatId()`

UnsetVatId ensures that no value is present for VatId, not even an explicit nil
### GetVatIdValidated

`func (o *Contact) GetVatIdValidated() bool`

GetVatIdValidated returns the VatIdValidated field if non-nil, zero value otherwise.

### GetVatIdValidatedOk

`func (o *Contact) GetVatIdValidatedOk() (*bool, bool)`

GetVatIdValidatedOk returns a tuple with the VatIdValidated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatIdValidated

`func (o *Contact) SetVatIdValidated(v bool)`

SetVatIdValidated sets VatIdValidated field to given value.

### HasVatIdValidated

`func (o *Contact) HasVatIdValidated() bool`

HasVatIdValidated returns a boolean if a field has been set.

### SetVatIdValidatedNil

`func (o *Contact) SetVatIdValidatedNil(b bool)`

 SetVatIdValidatedNil sets the value for VatIdValidated to be an explicit nil

### UnsetVatIdValidated
`func (o *Contact) UnsetVatIdValidated()`

UnsetVatIdValidated ensures that no value is present for VatIdValidated, not even an explicit nil
### GetVatIdValidationDate

`func (o *Contact) GetVatIdValidationDate() string`

GetVatIdValidationDate returns the VatIdValidationDate field if non-nil, zero value otherwise.

### GetVatIdValidationDateOk

`func (o *Contact) GetVatIdValidationDateOk() (*string, bool)`

GetVatIdValidationDateOk returns a tuple with the VatIdValidationDate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVatIdValidationDate

`func (o *Contact) SetVatIdValidationDate(v string)`

SetVatIdValidationDate sets VatIdValidationDate field to given value.

### HasVatIdValidationDate

`func (o *Contact) HasVatIdValidationDate() bool`

HasVatIdValidationDate returns a boolean if a field has been set.

### SetVatIdValidationDateNil

`func (o *Contact) SetVatIdValidationDateNil(b bool)`

 SetVatIdValidationDateNil sets the value for VatIdValidationDate to be an explicit nil

### UnsetVatIdValidationDate
`func (o *Contact) UnsetVatIdValidationDate()`

UnsetVatIdValidationDate ensures that no value is present for VatIdValidationDate, not even an explicit nil
### GetWebsite

`func (o *Contact) GetWebsite() string`

GetWebsite returns the Website field if non-nil, zero value otherwise.

### GetWebsiteOk

`func (o *Contact) GetWebsiteOk() (*string, bool)`

GetWebsiteOk returns a tuple with the Website field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebsite

`func (o *Contact) SetWebsite(v string)`

SetWebsite sets Website field to given value.

### HasWebsite

`func (o *Contact) HasWebsite() bool`

HasWebsite returns a boolean if a field has been set.

### SetWebsiteNil

`func (o *Contact) SetWebsiteNil(b bool)`

 SetWebsiteNil sets the value for Website to be an explicit nil

### UnsetWebsite
`func (o *Contact) UnsetWebsite()`

UnsetWebsite ensures that no value is present for Website, not even an explicit nil
### GetZip

`func (o *Contact) GetZip() string`

GetZip returns the Zip field if non-nil, zero value otherwise.

### GetZipOk

`func (o *Contact) GetZipOk() (*string, bool)`

GetZipOk returns a tuple with the Zip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetZip

`func (o *Contact) SetZip(v string)`

SetZip sets Zip field to given value.

### HasZip

`func (o *Contact) HasZip() bool`

HasZip returns a boolean if a field has been set.

### SetZipNil

`func (o *Contact) SetZipNil(b bool)`

 SetZipNil sets the value for Zip to be an explicit nil

### UnsetZip
`func (o *Contact) UnsetZip()`

UnsetZip ensures that no value is present for Zip, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


