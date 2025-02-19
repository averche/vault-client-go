# MountsTuneConfigurationParametersRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AllowedManagedKeys** | Pointer to **[]string** |  | [optional] 
**AllowedResponseHeaders** | Pointer to **[]string** | A list of headers to whitelist and allow a plugin to set on responses. | [optional] 
**AuditNonHmacRequestKeys** | Pointer to **[]string** | The list of keys in the request data object that will not be HMAC&#x27;ed by audit devices. | [optional] 
**AuditNonHmacResponseKeys** | Pointer to **[]string** | The list of keys in the response data object that will not be HMAC&#x27;ed by audit devices. | [optional] 
**DefaultLeaseTtl** | Pointer to **string** | The default lease TTL for this mount. | [optional] 
**Description** | Pointer to **string** | User-friendly description for this credential backend. | [optional] 
**ListingVisibility** | Pointer to **string** | Determines the visibility of the mount in the UI-specific listing endpoint. Accepted value are &#x27;unauth&#x27; and &#x27;hidden&#x27;, with the empty default (&#x27;&#x27;) behaving like &#x27;hidden&#x27;. | [optional] 
**MaxLeaseTtl** | Pointer to **string** | The max lease TTL for this mount. | [optional] 
**Options** | Pointer to **map[string]interface{}** | The options to pass into the backend. Should be a json object with string keys and values. | [optional] 
**PassthroughRequestHeaders** | Pointer to **[]string** | A list of headers to whitelist and pass from the request to the plugin. | [optional] 
**PluginVersion** | Pointer to **string** | The semantic version of the plugin to use. | [optional] 
**TokenType** | Pointer to **string** | The type of token to issue (service or batch). | [optional] 
**UserLockoutConfig** | Pointer to **map[string]interface{}** | The user lockout configuration to pass into the backend. Should be a json object with string keys and values. | [optional] 



## Methods


### NewMountsTuneConfigurationParametersRequest

`func NewMountsTuneConfigurationParametersRequest() *MountsTuneConfigurationParametersRequest`

NewMountsTuneConfigurationParametersRequest instantiates a new MountsTuneConfigurationParametersRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMountsTuneConfigurationParametersRequestWithDefaults

`func NewMountsTuneConfigurationParametersRequestWithDefaults() *MountsTuneConfigurationParametersRequest`

NewMountsTuneConfigurationParametersRequestWithDefaults instantiates a new MountsTuneConfigurationParametersRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetAllowedManagedKeys

`func (o *MountsTuneConfigurationParametersRequest) GetAllowedManagedKeys() []string`

GetAllowedManagedKeys returns the AllowedManagedKeys field if non-nil, zero value otherwise.

### GetAllowedManagedKeysOk

`func (o *MountsTuneConfigurationParametersRequest) GetAllowedManagedKeysOk() (*[]string, bool)`

GetAllowedManagedKeysOk returns a tuple with the AllowedManagedKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedManagedKeys

`func (o *MountsTuneConfigurationParametersRequest) SetAllowedManagedKeys(v []string)`

SetAllowedManagedKeys sets AllowedManagedKeys field to given value.


### HasAllowedManagedKeys

`func (o *MountsTuneConfigurationParametersRequest) HasAllowedManagedKeys() bool`

HasAllowedManagedKeys returns a boolean if a field has been set.




### GetAllowedResponseHeaders

`func (o *MountsTuneConfigurationParametersRequest) GetAllowedResponseHeaders() []string`

GetAllowedResponseHeaders returns the AllowedResponseHeaders field if non-nil, zero value otherwise.

### GetAllowedResponseHeadersOk

`func (o *MountsTuneConfigurationParametersRequest) GetAllowedResponseHeadersOk() (*[]string, bool)`

GetAllowedResponseHeadersOk returns a tuple with the AllowedResponseHeaders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAllowedResponseHeaders

`func (o *MountsTuneConfigurationParametersRequest) SetAllowedResponseHeaders(v []string)`

SetAllowedResponseHeaders sets AllowedResponseHeaders field to given value.


### HasAllowedResponseHeaders

`func (o *MountsTuneConfigurationParametersRequest) HasAllowedResponseHeaders() bool`

HasAllowedResponseHeaders returns a boolean if a field has been set.




### GetAuditNonHmacRequestKeys

`func (o *MountsTuneConfigurationParametersRequest) GetAuditNonHmacRequestKeys() []string`

GetAuditNonHmacRequestKeys returns the AuditNonHmacRequestKeys field if non-nil, zero value otherwise.

### GetAuditNonHmacRequestKeysOk

`func (o *MountsTuneConfigurationParametersRequest) GetAuditNonHmacRequestKeysOk() (*[]string, bool)`

GetAuditNonHmacRequestKeysOk returns a tuple with the AuditNonHmacRequestKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuditNonHmacRequestKeys

`func (o *MountsTuneConfigurationParametersRequest) SetAuditNonHmacRequestKeys(v []string)`

SetAuditNonHmacRequestKeys sets AuditNonHmacRequestKeys field to given value.


### HasAuditNonHmacRequestKeys

`func (o *MountsTuneConfigurationParametersRequest) HasAuditNonHmacRequestKeys() bool`

HasAuditNonHmacRequestKeys returns a boolean if a field has been set.




### GetAuditNonHmacResponseKeys

`func (o *MountsTuneConfigurationParametersRequest) GetAuditNonHmacResponseKeys() []string`

GetAuditNonHmacResponseKeys returns the AuditNonHmacResponseKeys field if non-nil, zero value otherwise.

### GetAuditNonHmacResponseKeysOk

`func (o *MountsTuneConfigurationParametersRequest) GetAuditNonHmacResponseKeysOk() (*[]string, bool)`

GetAuditNonHmacResponseKeysOk returns a tuple with the AuditNonHmacResponseKeys field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAuditNonHmacResponseKeys

`func (o *MountsTuneConfigurationParametersRequest) SetAuditNonHmacResponseKeys(v []string)`

SetAuditNonHmacResponseKeys sets AuditNonHmacResponseKeys field to given value.


### HasAuditNonHmacResponseKeys

`func (o *MountsTuneConfigurationParametersRequest) HasAuditNonHmacResponseKeys() bool`

HasAuditNonHmacResponseKeys returns a boolean if a field has been set.




### GetDefaultLeaseTtl

`func (o *MountsTuneConfigurationParametersRequest) GetDefaultLeaseTtl() string`

GetDefaultLeaseTtl returns the DefaultLeaseTtl field if non-nil, zero value otherwise.

### GetDefaultLeaseTtlOk

`func (o *MountsTuneConfigurationParametersRequest) GetDefaultLeaseTtlOk() (*string, bool)`

GetDefaultLeaseTtlOk returns a tuple with the DefaultLeaseTtl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefaultLeaseTtl

`func (o *MountsTuneConfigurationParametersRequest) SetDefaultLeaseTtl(v string)`

SetDefaultLeaseTtl sets DefaultLeaseTtl field to given value.


### HasDefaultLeaseTtl

`func (o *MountsTuneConfigurationParametersRequest) HasDefaultLeaseTtl() bool`

HasDefaultLeaseTtl returns a boolean if a field has been set.




### GetDescription

`func (o *MountsTuneConfigurationParametersRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *MountsTuneConfigurationParametersRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *MountsTuneConfigurationParametersRequest) SetDescription(v string)`

SetDescription sets Description field to given value.


### HasDescription

`func (o *MountsTuneConfigurationParametersRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.




### GetListingVisibility

`func (o *MountsTuneConfigurationParametersRequest) GetListingVisibility() string`

GetListingVisibility returns the ListingVisibility field if non-nil, zero value otherwise.

### GetListingVisibilityOk

`func (o *MountsTuneConfigurationParametersRequest) GetListingVisibilityOk() (*string, bool)`

GetListingVisibilityOk returns a tuple with the ListingVisibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetListingVisibility

`func (o *MountsTuneConfigurationParametersRequest) SetListingVisibility(v string)`

SetListingVisibility sets ListingVisibility field to given value.


### HasListingVisibility

`func (o *MountsTuneConfigurationParametersRequest) HasListingVisibility() bool`

HasListingVisibility returns a boolean if a field has been set.




### GetMaxLeaseTtl

`func (o *MountsTuneConfigurationParametersRequest) GetMaxLeaseTtl() string`

GetMaxLeaseTtl returns the MaxLeaseTtl field if non-nil, zero value otherwise.

### GetMaxLeaseTtlOk

`func (o *MountsTuneConfigurationParametersRequest) GetMaxLeaseTtlOk() (*string, bool)`

GetMaxLeaseTtlOk returns a tuple with the MaxLeaseTtl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMaxLeaseTtl

`func (o *MountsTuneConfigurationParametersRequest) SetMaxLeaseTtl(v string)`

SetMaxLeaseTtl sets MaxLeaseTtl field to given value.


### HasMaxLeaseTtl

`func (o *MountsTuneConfigurationParametersRequest) HasMaxLeaseTtl() bool`

HasMaxLeaseTtl returns a boolean if a field has been set.




### GetOptions

`func (o *MountsTuneConfigurationParametersRequest) GetOptions() map[string]interface{}`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *MountsTuneConfigurationParametersRequest) GetOptionsOk() (*map[string]interface{}, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *MountsTuneConfigurationParametersRequest) SetOptions(v map[string]interface{})`

SetOptions sets Options field to given value.


### HasOptions

`func (o *MountsTuneConfigurationParametersRequest) HasOptions() bool`

HasOptions returns a boolean if a field has been set.




### GetPassthroughRequestHeaders

`func (o *MountsTuneConfigurationParametersRequest) GetPassthroughRequestHeaders() []string`

GetPassthroughRequestHeaders returns the PassthroughRequestHeaders field if non-nil, zero value otherwise.

### GetPassthroughRequestHeadersOk

`func (o *MountsTuneConfigurationParametersRequest) GetPassthroughRequestHeadersOk() (*[]string, bool)`

GetPassthroughRequestHeadersOk returns a tuple with the PassthroughRequestHeaders field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPassthroughRequestHeaders

`func (o *MountsTuneConfigurationParametersRequest) SetPassthroughRequestHeaders(v []string)`

SetPassthroughRequestHeaders sets PassthroughRequestHeaders field to given value.


### HasPassthroughRequestHeaders

`func (o *MountsTuneConfigurationParametersRequest) HasPassthroughRequestHeaders() bool`

HasPassthroughRequestHeaders returns a boolean if a field has been set.




### GetPluginVersion

`func (o *MountsTuneConfigurationParametersRequest) GetPluginVersion() string`

GetPluginVersion returns the PluginVersion field if non-nil, zero value otherwise.

### GetPluginVersionOk

`func (o *MountsTuneConfigurationParametersRequest) GetPluginVersionOk() (*string, bool)`

GetPluginVersionOk returns a tuple with the PluginVersion field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPluginVersion

`func (o *MountsTuneConfigurationParametersRequest) SetPluginVersion(v string)`

SetPluginVersion sets PluginVersion field to given value.


### HasPluginVersion

`func (o *MountsTuneConfigurationParametersRequest) HasPluginVersion() bool`

HasPluginVersion returns a boolean if a field has been set.




### GetTokenType

`func (o *MountsTuneConfigurationParametersRequest) GetTokenType() string`

GetTokenType returns the TokenType field if non-nil, zero value otherwise.

### GetTokenTypeOk

`func (o *MountsTuneConfigurationParametersRequest) GetTokenTypeOk() (*string, bool)`

GetTokenTypeOk returns a tuple with the TokenType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTokenType

`func (o *MountsTuneConfigurationParametersRequest) SetTokenType(v string)`

SetTokenType sets TokenType field to given value.


### HasTokenType

`func (o *MountsTuneConfigurationParametersRequest) HasTokenType() bool`

HasTokenType returns a boolean if a field has been set.




### GetUserLockoutConfig

`func (o *MountsTuneConfigurationParametersRequest) GetUserLockoutConfig() map[string]interface{}`

GetUserLockoutConfig returns the UserLockoutConfig field if non-nil, zero value otherwise.

### GetUserLockoutConfigOk

`func (o *MountsTuneConfigurationParametersRequest) GetUserLockoutConfigOk() (*map[string]interface{}, bool)`

GetUserLockoutConfigOk returns a tuple with the UserLockoutConfig field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserLockoutConfig

`func (o *MountsTuneConfigurationParametersRequest) SetUserLockoutConfig(v map[string]interface{})`

SetUserLockoutConfig sets UserLockoutConfig field to given value.


### HasUserLockoutConfig

`func (o *MountsTuneConfigurationParametersRequest) HasUserLockoutConfig() bool`

HasUserLockoutConfig returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


