# InstituteDeadlines

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AbschlusspruefungMonths** | Pointer to **NullableInt32** | HGB § 340k/§ 341k: Abschlussprüfung (5 Monate). | [optional] 
**JahresabschlussBafinMonths** | Pointer to **NullableInt32** | KWG § 26: Jahresabschluss an die BaFin (3 Monate, nur KWG-Institute). | [optional] 
**OffenlegungMonths** | **int32** | HGB § 325 Abs. 4: Offenlegung (4 kapitalmarktorientiert / 12 sonst). | 

## Methods

### NewInstituteDeadlines

`func NewInstituteDeadlines(offenlegungMonths int32, ) *InstituteDeadlines`

NewInstituteDeadlines instantiates a new InstituteDeadlines object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewInstituteDeadlinesWithDefaults

`func NewInstituteDeadlinesWithDefaults() *InstituteDeadlines`

NewInstituteDeadlinesWithDefaults instantiates a new InstituteDeadlines object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAbschlusspruefungMonths

`func (o *InstituteDeadlines) GetAbschlusspruefungMonths() int32`

GetAbschlusspruefungMonths returns the AbschlusspruefungMonths field if non-nil, zero value otherwise.

### GetAbschlusspruefungMonthsOk

`func (o *InstituteDeadlines) GetAbschlusspruefungMonthsOk() (*int32, bool)`

GetAbschlusspruefungMonthsOk returns a tuple with the AbschlusspruefungMonths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAbschlusspruefungMonths

`func (o *InstituteDeadlines) SetAbschlusspruefungMonths(v int32)`

SetAbschlusspruefungMonths sets AbschlusspruefungMonths field to given value.

### HasAbschlusspruefungMonths

`func (o *InstituteDeadlines) HasAbschlusspruefungMonths() bool`

HasAbschlusspruefungMonths returns a boolean if a field has been set.

### SetAbschlusspruefungMonthsNil

`func (o *InstituteDeadlines) SetAbschlusspruefungMonthsNil(b bool)`

 SetAbschlusspruefungMonthsNil sets the value for AbschlusspruefungMonths to be an explicit nil

### UnsetAbschlusspruefungMonths
`func (o *InstituteDeadlines) UnsetAbschlusspruefungMonths()`

UnsetAbschlusspruefungMonths ensures that no value is present for AbschlusspruefungMonths, not even an explicit nil
### GetJahresabschlussBafinMonths

`func (o *InstituteDeadlines) GetJahresabschlussBafinMonths() int32`

GetJahresabschlussBafinMonths returns the JahresabschlussBafinMonths field if non-nil, zero value otherwise.

### GetJahresabschlussBafinMonthsOk

`func (o *InstituteDeadlines) GetJahresabschlussBafinMonthsOk() (*int32, bool)`

GetJahresabschlussBafinMonthsOk returns a tuple with the JahresabschlussBafinMonths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetJahresabschlussBafinMonths

`func (o *InstituteDeadlines) SetJahresabschlussBafinMonths(v int32)`

SetJahresabschlussBafinMonths sets JahresabschlussBafinMonths field to given value.

### HasJahresabschlussBafinMonths

`func (o *InstituteDeadlines) HasJahresabschlussBafinMonths() bool`

HasJahresabschlussBafinMonths returns a boolean if a field has been set.

### SetJahresabschlussBafinMonthsNil

`func (o *InstituteDeadlines) SetJahresabschlussBafinMonthsNil(b bool)`

 SetJahresabschlussBafinMonthsNil sets the value for JahresabschlussBafinMonths to be an explicit nil

### UnsetJahresabschlussBafinMonths
`func (o *InstituteDeadlines) UnsetJahresabschlussBafinMonths()`

UnsetJahresabschlussBafinMonths ensures that no value is present for JahresabschlussBafinMonths, not even an explicit nil
### GetOffenlegungMonths

`func (o *InstituteDeadlines) GetOffenlegungMonths() int32`

GetOffenlegungMonths returns the OffenlegungMonths field if non-nil, zero value otherwise.

### GetOffenlegungMonthsOk

`func (o *InstituteDeadlines) GetOffenlegungMonthsOk() (*int32, bool)`

GetOffenlegungMonthsOk returns a tuple with the OffenlegungMonths field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffenlegungMonths

`func (o *InstituteDeadlines) SetOffenlegungMonths(v int32)`

SetOffenlegungMonths sets OffenlegungMonths field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


