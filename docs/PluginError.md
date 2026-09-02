# PluginError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**BadRequest** | **[]map[string]interface{}** |  | 
**NotFound** | **[]map[string]interface{}** |  | 
**Unauthorized** | **[]map[string]interface{}** |  | 
**InternalError** | **[]map[string]interface{}** |  | 
**DatabaseError** | **[]map[string]interface{}** |  | 
**ValidationError** | **[]map[string]interface{}** |  | 
**NotImplemented** | **string** |  | 

## Methods

### NewPluginError

`func NewPluginError(badRequest []map[string]interface{}, notFound []map[string]interface{}, unauthorized []map[string]interface{}, internalError []map[string]interface{}, databaseError []map[string]interface{}, validationError []map[string]interface{}, notImplemented string, ) *PluginError`

NewPluginError instantiates a new PluginError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPluginErrorWithDefaults

`func NewPluginErrorWithDefaults() *PluginError`

NewPluginErrorWithDefaults instantiates a new PluginError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBadRequest

`func (o *PluginError) GetBadRequest() []map[string]interface{}`

GetBadRequest returns the BadRequest field if non-nil, zero value otherwise.

### GetBadRequestOk

`func (o *PluginError) GetBadRequestOk() (*[]map[string]interface{}, bool)`

GetBadRequestOk returns a tuple with the BadRequest field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBadRequest

`func (o *PluginError) SetBadRequest(v []map[string]interface{})`

SetBadRequest sets BadRequest field to given value.


### GetNotFound

`func (o *PluginError) GetNotFound() []map[string]interface{}`

GetNotFound returns the NotFound field if non-nil, zero value otherwise.

### GetNotFoundOk

`func (o *PluginError) GetNotFoundOk() (*[]map[string]interface{}, bool)`

GetNotFoundOk returns a tuple with the NotFound field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotFound

`func (o *PluginError) SetNotFound(v []map[string]interface{})`

SetNotFound sets NotFound field to given value.


### GetUnauthorized

`func (o *PluginError) GetUnauthorized() []map[string]interface{}`

GetUnauthorized returns the Unauthorized field if non-nil, zero value otherwise.

### GetUnauthorizedOk

`func (o *PluginError) GetUnauthorizedOk() (*[]map[string]interface{}, bool)`

GetUnauthorizedOk returns a tuple with the Unauthorized field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnauthorized

`func (o *PluginError) SetUnauthorized(v []map[string]interface{})`

SetUnauthorized sets Unauthorized field to given value.


### GetInternalError

`func (o *PluginError) GetInternalError() []map[string]interface{}`

GetInternalError returns the InternalError field if non-nil, zero value otherwise.

### GetInternalErrorOk

`func (o *PluginError) GetInternalErrorOk() (*[]map[string]interface{}, bool)`

GetInternalErrorOk returns a tuple with the InternalError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternalError

`func (o *PluginError) SetInternalError(v []map[string]interface{})`

SetInternalError sets InternalError field to given value.


### GetDatabaseError

`func (o *PluginError) GetDatabaseError() []map[string]interface{}`

GetDatabaseError returns the DatabaseError field if non-nil, zero value otherwise.

### GetDatabaseErrorOk

`func (o *PluginError) GetDatabaseErrorOk() (*[]map[string]interface{}, bool)`

GetDatabaseErrorOk returns a tuple with the DatabaseError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDatabaseError

`func (o *PluginError) SetDatabaseError(v []map[string]interface{})`

SetDatabaseError sets DatabaseError field to given value.


### GetValidationError

`func (o *PluginError) GetValidationError() []map[string]interface{}`

GetValidationError returns the ValidationError field if non-nil, zero value otherwise.

### GetValidationErrorOk

`func (o *PluginError) GetValidationErrorOk() (*[]map[string]interface{}, bool)`

GetValidationErrorOk returns a tuple with the ValidationError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidationError

`func (o *PluginError) SetValidationError(v []map[string]interface{})`

SetValidationError sets ValidationError field to given value.


### GetNotImplemented

`func (o *PluginError) GetNotImplemented() string`

GetNotImplemented returns the NotImplemented field if non-nil, zero value otherwise.

### GetNotImplementedOk

`func (o *PluginError) GetNotImplementedOk() (*string, bool)`

GetNotImplementedOk returns a tuple with the NotImplemented field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotImplemented

`func (o *PluginError) SetNotImplemented(v string)`

SetNotImplemented sets NotImplemented field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


