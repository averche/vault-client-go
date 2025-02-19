# MfaConfigurePingIdMethodRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MethodName** | Pointer to **string** | The unique name identifier for this MFA method. | [optional] 
**SettingsFileBase64** | Pointer to **string** | The settings file provided by Ping, Base64-encoded. This must be a settings file suitable for third-party clients, not the PingID SDK or PingFederate. | [optional] 
**UsernameFormat** | Pointer to **string** | A template string for mapping Identity names to MFA method names. Values to subtitute should be placed in {{}}. For example, \&quot;{{alias.name}}@example.com\&quot;. Currently-supported mappings: alias.name: The name returned by the mount configured via the mount_accessor parameter If blank, the Alias&#x27;s name field will be used as-is. | [optional] 



## Methods


### NewMfaConfigurePingIdMethodRequest

`func NewMfaConfigurePingIdMethodRequest() *MfaConfigurePingIdMethodRequest`

NewMfaConfigurePingIdMethodRequest instantiates a new MfaConfigurePingIdMethodRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMfaConfigurePingIdMethodRequestWithDefaults

`func NewMfaConfigurePingIdMethodRequestWithDefaults() *MfaConfigurePingIdMethodRequest`

NewMfaConfigurePingIdMethodRequestWithDefaults instantiates a new MfaConfigurePingIdMethodRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetMethodName

`func (o *MfaConfigurePingIdMethodRequest) GetMethodName() string`

GetMethodName returns the MethodName field if non-nil, zero value otherwise.

### GetMethodNameOk

`func (o *MfaConfigurePingIdMethodRequest) GetMethodNameOk() (*string, bool)`

GetMethodNameOk returns a tuple with the MethodName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMethodName

`func (o *MfaConfigurePingIdMethodRequest) SetMethodName(v string)`

SetMethodName sets MethodName field to given value.


### HasMethodName

`func (o *MfaConfigurePingIdMethodRequest) HasMethodName() bool`

HasMethodName returns a boolean if a field has been set.




### GetSettingsFileBase64

`func (o *MfaConfigurePingIdMethodRequest) GetSettingsFileBase64() string`

GetSettingsFileBase64 returns the SettingsFileBase64 field if non-nil, zero value otherwise.

### GetSettingsFileBase64Ok

`func (o *MfaConfigurePingIdMethodRequest) GetSettingsFileBase64Ok() (*string, bool)`

GetSettingsFileBase64Ok returns a tuple with the SettingsFileBase64 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSettingsFileBase64

`func (o *MfaConfigurePingIdMethodRequest) SetSettingsFileBase64(v string)`

SetSettingsFileBase64 sets SettingsFileBase64 field to given value.


### HasSettingsFileBase64

`func (o *MfaConfigurePingIdMethodRequest) HasSettingsFileBase64() bool`

HasSettingsFileBase64 returns a boolean if a field has been set.




### GetUsernameFormat

`func (o *MfaConfigurePingIdMethodRequest) GetUsernameFormat() string`

GetUsernameFormat returns the UsernameFormat field if non-nil, zero value otherwise.

### GetUsernameFormatOk

`func (o *MfaConfigurePingIdMethodRequest) GetUsernameFormatOk() (*string, bool)`

GetUsernameFormatOk returns a tuple with the UsernameFormat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsernameFormat

`func (o *MfaConfigurePingIdMethodRequest) SetUsernameFormat(v string)`

SetUsernameFormat sets UsernameFormat field to given value.


### HasUsernameFormat

`func (o *MfaConfigurePingIdMethodRequest) HasUsernameFormat() bool`

HasUsernameFormat returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


