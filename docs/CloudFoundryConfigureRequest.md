# CloudFoundryConfigureRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CfApiAddr** | Pointer to **string** | CF’s API address. | [optional] 
**CfApiMutualTlsCertificate** | Pointer to **string** | The PEM-format certificates that are presented for mutual TLS with the CloudFoundry API. If not set, mutual TLS is not used | [optional] 
**CfApiMutualTlsKey** | Pointer to **string** | The PEM-format private key that are used for mutual TLS with the CloudFoundry API. If not set, mutual TLS is not used | [optional] 
**CfApiTrustedCertificates** | Pointer to **[]string** | The PEM-format CA certificates that are acceptable for the CF API to present. | [optional] 
**CfClientId** | Pointer to **string** | The client id for CF’s API. | [optional] 
**CfClientSecret** | Pointer to **string** | The client secret for CF’s API. | [optional] 
**CfPassword** | Pointer to **string** | The password for CF’s API. | [optional] 
**CfUsername** | Pointer to **string** | The username for CF’s API. | [optional] 
**IdentityCaCertificates** | Pointer to **[]string** | The PEM-format CA certificates that are required to have issued the instance certificates presented for logging in. | [optional] 
**LoginMaxSecondsNotAfter** | Pointer to **int32** | Duration in seconds for the maximum acceptable length in the future a \&quot;signing_time\&quot; can be. Useful for clock drift. Set low to reduce the opportunity for replay attacks. | [optional] [default to 60]
**LoginMaxSecondsNotBefore** | Pointer to **int32** | Duration in seconds for the maximum acceptable age of a \&quot;signing_time\&quot;. Useful for clock drift. Set low to reduce the opportunity for replay attacks. | [optional] [default to 300]
**PcfApiAddr** | Pointer to **string** | Deprecated. Please use \&quot;cf_api_addr\&quot;. | [optional] 
**PcfApiTrustedCertificates** | Pointer to **[]string** | Deprecated. Please use \&quot;cf_api_trusted_certificates\&quot;. | [optional] 
**PcfPassword** | Pointer to **string** | Deprecated. Please use \&quot;cf_password\&quot;. | [optional] 
**PcfUsername** | Pointer to **string** | Deprecated. Please use \&quot;cf_username\&quot;. | [optional] 



## Methods


### NewCloudFoundryConfigureRequest

`func NewCloudFoundryConfigureRequest() *CloudFoundryConfigureRequest`

NewCloudFoundryConfigureRequest instantiates a new CloudFoundryConfigureRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCloudFoundryConfigureRequestWithDefaults

`func NewCloudFoundryConfigureRequestWithDefaults() *CloudFoundryConfigureRequest`

NewCloudFoundryConfigureRequestWithDefaults instantiates a new CloudFoundryConfigureRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetCfApiAddr

`func (o *CloudFoundryConfigureRequest) GetCfApiAddr() string`

GetCfApiAddr returns the CfApiAddr field if non-nil, zero value otherwise.

### GetCfApiAddrOk

`func (o *CloudFoundryConfigureRequest) GetCfApiAddrOk() (*string, bool)`

GetCfApiAddrOk returns a tuple with the CfApiAddr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCfApiAddr

`func (o *CloudFoundryConfigureRequest) SetCfApiAddr(v string)`

SetCfApiAddr sets CfApiAddr field to given value.


### HasCfApiAddr

`func (o *CloudFoundryConfigureRequest) HasCfApiAddr() bool`

HasCfApiAddr returns a boolean if a field has been set.




### GetCfApiMutualTlsCertificate

`func (o *CloudFoundryConfigureRequest) GetCfApiMutualTlsCertificate() string`

GetCfApiMutualTlsCertificate returns the CfApiMutualTlsCertificate field if non-nil, zero value otherwise.

### GetCfApiMutualTlsCertificateOk

`func (o *CloudFoundryConfigureRequest) GetCfApiMutualTlsCertificateOk() (*string, bool)`

GetCfApiMutualTlsCertificateOk returns a tuple with the CfApiMutualTlsCertificate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCfApiMutualTlsCertificate

`func (o *CloudFoundryConfigureRequest) SetCfApiMutualTlsCertificate(v string)`

SetCfApiMutualTlsCertificate sets CfApiMutualTlsCertificate field to given value.


### HasCfApiMutualTlsCertificate

`func (o *CloudFoundryConfigureRequest) HasCfApiMutualTlsCertificate() bool`

HasCfApiMutualTlsCertificate returns a boolean if a field has been set.




### GetCfApiMutualTlsKey

`func (o *CloudFoundryConfigureRequest) GetCfApiMutualTlsKey() string`

GetCfApiMutualTlsKey returns the CfApiMutualTlsKey field if non-nil, zero value otherwise.

### GetCfApiMutualTlsKeyOk

`func (o *CloudFoundryConfigureRequest) GetCfApiMutualTlsKeyOk() (*string, bool)`

GetCfApiMutualTlsKeyOk returns a tuple with the CfApiMutualTlsKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCfApiMutualTlsKey

`func (o *CloudFoundryConfigureRequest) SetCfApiMutualTlsKey(v string)`

SetCfApiMutualTlsKey sets CfApiMutualTlsKey field to given value.


### HasCfApiMutualTlsKey

`func (o *CloudFoundryConfigureRequest) HasCfApiMutualTlsKey() bool`

HasCfApiMutualTlsKey returns a boolean if a field has been set.




### GetCfApiTrustedCertificates

`func (o *CloudFoundryConfigureRequest) GetCfApiTrustedCertificates() []string`

GetCfApiTrustedCertificates returns the CfApiTrustedCertificates field if non-nil, zero value otherwise.

### GetCfApiTrustedCertificatesOk

`func (o *CloudFoundryConfigureRequest) GetCfApiTrustedCertificatesOk() (*[]string, bool)`

GetCfApiTrustedCertificatesOk returns a tuple with the CfApiTrustedCertificates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCfApiTrustedCertificates

`func (o *CloudFoundryConfigureRequest) SetCfApiTrustedCertificates(v []string)`

SetCfApiTrustedCertificates sets CfApiTrustedCertificates field to given value.


### HasCfApiTrustedCertificates

`func (o *CloudFoundryConfigureRequest) HasCfApiTrustedCertificates() bool`

HasCfApiTrustedCertificates returns a boolean if a field has been set.




### GetCfClientId

`func (o *CloudFoundryConfigureRequest) GetCfClientId() string`

GetCfClientId returns the CfClientId field if non-nil, zero value otherwise.

### GetCfClientIdOk

`func (o *CloudFoundryConfigureRequest) GetCfClientIdOk() (*string, bool)`

GetCfClientIdOk returns a tuple with the CfClientId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCfClientId

`func (o *CloudFoundryConfigureRequest) SetCfClientId(v string)`

SetCfClientId sets CfClientId field to given value.


### HasCfClientId

`func (o *CloudFoundryConfigureRequest) HasCfClientId() bool`

HasCfClientId returns a boolean if a field has been set.




### GetCfClientSecret

`func (o *CloudFoundryConfigureRequest) GetCfClientSecret() string`

GetCfClientSecret returns the CfClientSecret field if non-nil, zero value otherwise.

### GetCfClientSecretOk

`func (o *CloudFoundryConfigureRequest) GetCfClientSecretOk() (*string, bool)`

GetCfClientSecretOk returns a tuple with the CfClientSecret field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCfClientSecret

`func (o *CloudFoundryConfigureRequest) SetCfClientSecret(v string)`

SetCfClientSecret sets CfClientSecret field to given value.


### HasCfClientSecret

`func (o *CloudFoundryConfigureRequest) HasCfClientSecret() bool`

HasCfClientSecret returns a boolean if a field has been set.




### GetCfPassword

`func (o *CloudFoundryConfigureRequest) GetCfPassword() string`

GetCfPassword returns the CfPassword field if non-nil, zero value otherwise.

### GetCfPasswordOk

`func (o *CloudFoundryConfigureRequest) GetCfPasswordOk() (*string, bool)`

GetCfPasswordOk returns a tuple with the CfPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCfPassword

`func (o *CloudFoundryConfigureRequest) SetCfPassword(v string)`

SetCfPassword sets CfPassword field to given value.


### HasCfPassword

`func (o *CloudFoundryConfigureRequest) HasCfPassword() bool`

HasCfPassword returns a boolean if a field has been set.




### GetCfUsername

`func (o *CloudFoundryConfigureRequest) GetCfUsername() string`

GetCfUsername returns the CfUsername field if non-nil, zero value otherwise.

### GetCfUsernameOk

`func (o *CloudFoundryConfigureRequest) GetCfUsernameOk() (*string, bool)`

GetCfUsernameOk returns a tuple with the CfUsername field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCfUsername

`func (o *CloudFoundryConfigureRequest) SetCfUsername(v string)`

SetCfUsername sets CfUsername field to given value.


### HasCfUsername

`func (o *CloudFoundryConfigureRequest) HasCfUsername() bool`

HasCfUsername returns a boolean if a field has been set.




### GetIdentityCaCertificates

`func (o *CloudFoundryConfigureRequest) GetIdentityCaCertificates() []string`

GetIdentityCaCertificates returns the IdentityCaCertificates field if non-nil, zero value otherwise.

### GetIdentityCaCertificatesOk

`func (o *CloudFoundryConfigureRequest) GetIdentityCaCertificatesOk() (*[]string, bool)`

GetIdentityCaCertificatesOk returns a tuple with the IdentityCaCertificates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentityCaCertificates

`func (o *CloudFoundryConfigureRequest) SetIdentityCaCertificates(v []string)`

SetIdentityCaCertificates sets IdentityCaCertificates field to given value.


### HasIdentityCaCertificates

`func (o *CloudFoundryConfigureRequest) HasIdentityCaCertificates() bool`

HasIdentityCaCertificates returns a boolean if a field has been set.




### GetLoginMaxSecondsNotAfter

`func (o *CloudFoundryConfigureRequest) GetLoginMaxSecondsNotAfter() int32`

GetLoginMaxSecondsNotAfter returns the LoginMaxSecondsNotAfter field if non-nil, zero value otherwise.

### GetLoginMaxSecondsNotAfterOk

`func (o *CloudFoundryConfigureRequest) GetLoginMaxSecondsNotAfterOk() (*int32, bool)`

GetLoginMaxSecondsNotAfterOk returns a tuple with the LoginMaxSecondsNotAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoginMaxSecondsNotAfter

`func (o *CloudFoundryConfigureRequest) SetLoginMaxSecondsNotAfter(v int32)`

SetLoginMaxSecondsNotAfter sets LoginMaxSecondsNotAfter field to given value.


### HasLoginMaxSecondsNotAfter

`func (o *CloudFoundryConfigureRequest) HasLoginMaxSecondsNotAfter() bool`

HasLoginMaxSecondsNotAfter returns a boolean if a field has been set.




### GetLoginMaxSecondsNotBefore

`func (o *CloudFoundryConfigureRequest) GetLoginMaxSecondsNotBefore() int32`

GetLoginMaxSecondsNotBefore returns the LoginMaxSecondsNotBefore field if non-nil, zero value otherwise.

### GetLoginMaxSecondsNotBeforeOk

`func (o *CloudFoundryConfigureRequest) GetLoginMaxSecondsNotBeforeOk() (*int32, bool)`

GetLoginMaxSecondsNotBeforeOk returns a tuple with the LoginMaxSecondsNotBefore field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLoginMaxSecondsNotBefore

`func (o *CloudFoundryConfigureRequest) SetLoginMaxSecondsNotBefore(v int32)`

SetLoginMaxSecondsNotBefore sets LoginMaxSecondsNotBefore field to given value.


### HasLoginMaxSecondsNotBefore

`func (o *CloudFoundryConfigureRequest) HasLoginMaxSecondsNotBefore() bool`

HasLoginMaxSecondsNotBefore returns a boolean if a field has been set.




### GetPcfApiAddr

`func (o *CloudFoundryConfigureRequest) GetPcfApiAddr() string`

GetPcfApiAddr returns the PcfApiAddr field if non-nil, zero value otherwise.

### GetPcfApiAddrOk

`func (o *CloudFoundryConfigureRequest) GetPcfApiAddrOk() (*string, bool)`

GetPcfApiAddrOk returns a tuple with the PcfApiAddr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPcfApiAddr

`func (o *CloudFoundryConfigureRequest) SetPcfApiAddr(v string)`

SetPcfApiAddr sets PcfApiAddr field to given value.


### HasPcfApiAddr

`func (o *CloudFoundryConfigureRequest) HasPcfApiAddr() bool`

HasPcfApiAddr returns a boolean if a field has been set.




### GetPcfApiTrustedCertificates

`func (o *CloudFoundryConfigureRequest) GetPcfApiTrustedCertificates() []string`

GetPcfApiTrustedCertificates returns the PcfApiTrustedCertificates field if non-nil, zero value otherwise.

### GetPcfApiTrustedCertificatesOk

`func (o *CloudFoundryConfigureRequest) GetPcfApiTrustedCertificatesOk() (*[]string, bool)`

GetPcfApiTrustedCertificatesOk returns a tuple with the PcfApiTrustedCertificates field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPcfApiTrustedCertificates

`func (o *CloudFoundryConfigureRequest) SetPcfApiTrustedCertificates(v []string)`

SetPcfApiTrustedCertificates sets PcfApiTrustedCertificates field to given value.


### HasPcfApiTrustedCertificates

`func (o *CloudFoundryConfigureRequest) HasPcfApiTrustedCertificates() bool`

HasPcfApiTrustedCertificates returns a boolean if a field has been set.




### GetPcfPassword

`func (o *CloudFoundryConfigureRequest) GetPcfPassword() string`

GetPcfPassword returns the PcfPassword field if non-nil, zero value otherwise.

### GetPcfPasswordOk

`func (o *CloudFoundryConfigureRequest) GetPcfPasswordOk() (*string, bool)`

GetPcfPasswordOk returns a tuple with the PcfPassword field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPcfPassword

`func (o *CloudFoundryConfigureRequest) SetPcfPassword(v string)`

SetPcfPassword sets PcfPassword field to given value.


### HasPcfPassword

`func (o *CloudFoundryConfigureRequest) HasPcfPassword() bool`

HasPcfPassword returns a boolean if a field has been set.




### GetPcfUsername

`func (o *CloudFoundryConfigureRequest) GetPcfUsername() string`

GetPcfUsername returns the PcfUsername field if non-nil, zero value otherwise.

### GetPcfUsernameOk

`func (o *CloudFoundryConfigureRequest) GetPcfUsernameOk() (*string, bool)`

GetPcfUsernameOk returns a tuple with the PcfUsername field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPcfUsername

`func (o *CloudFoundryConfigureRequest) SetPcfUsername(v string)`

SetPcfUsername sets PcfUsername field to given value.


### HasPcfUsername

`func (o *CloudFoundryConfigureRequest) HasPcfUsername() bool`

HasPcfUsername returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


