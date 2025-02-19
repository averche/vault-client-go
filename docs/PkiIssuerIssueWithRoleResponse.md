# PkiIssuerIssueWithRoleResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CaChain** | Pointer to **[]string** | Certificate Chain | [optional] 
**Certificate** | Pointer to **string** | Certificate | [optional] 
**Expiration** | Pointer to **string** | Time of expiration | [optional] 
**IssuingCa** | Pointer to **string** | Issuing Certificate Authority | [optional] 
**PrivateKey** | Pointer to **string** | Private key | [optional] 
**PrivateKeyType** | Pointer to **string** | Private key type | [optional] 
**SerialNumber** | Pointer to **string** | Serial Number | [optional] 



## Methods


### NewPkiIssuerIssueWithRoleResponse

`func NewPkiIssuerIssueWithRoleResponse() *PkiIssuerIssueWithRoleResponse`

NewPkiIssuerIssueWithRoleResponse instantiates a new PkiIssuerIssueWithRoleResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPkiIssuerIssueWithRoleResponseWithDefaults

`func NewPkiIssuerIssueWithRoleResponseWithDefaults() *PkiIssuerIssueWithRoleResponse`

NewPkiIssuerIssueWithRoleResponseWithDefaults instantiates a new PkiIssuerIssueWithRoleResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetCaChain

`func (o *PkiIssuerIssueWithRoleResponse) GetCaChain() []string`

GetCaChain returns the CaChain field if non-nil, zero value otherwise.

### GetCaChainOk

`func (o *PkiIssuerIssueWithRoleResponse) GetCaChainOk() (*[]string, bool)`

GetCaChainOk returns a tuple with the CaChain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCaChain

`func (o *PkiIssuerIssueWithRoleResponse) SetCaChain(v []string)`

SetCaChain sets CaChain field to given value.


### HasCaChain

`func (o *PkiIssuerIssueWithRoleResponse) HasCaChain() bool`

HasCaChain returns a boolean if a field has been set.




### GetCertificate

`func (o *PkiIssuerIssueWithRoleResponse) GetCertificate() string`

GetCertificate returns the Certificate field if non-nil, zero value otherwise.

### GetCertificateOk

`func (o *PkiIssuerIssueWithRoleResponse) GetCertificateOk() (*string, bool)`

GetCertificateOk returns a tuple with the Certificate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificate

`func (o *PkiIssuerIssueWithRoleResponse) SetCertificate(v string)`

SetCertificate sets Certificate field to given value.


### HasCertificate

`func (o *PkiIssuerIssueWithRoleResponse) HasCertificate() bool`

HasCertificate returns a boolean if a field has been set.




### GetExpiration

`func (o *PkiIssuerIssueWithRoleResponse) GetExpiration() string`

GetExpiration returns the Expiration field if non-nil, zero value otherwise.

### GetExpirationOk

`func (o *PkiIssuerIssueWithRoleResponse) GetExpirationOk() (*string, bool)`

GetExpirationOk returns a tuple with the Expiration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiration

`func (o *PkiIssuerIssueWithRoleResponse) SetExpiration(v string)`

SetExpiration sets Expiration field to given value.


### HasExpiration

`func (o *PkiIssuerIssueWithRoleResponse) HasExpiration() bool`

HasExpiration returns a boolean if a field has been set.




### GetIssuingCa

`func (o *PkiIssuerIssueWithRoleResponse) GetIssuingCa() string`

GetIssuingCa returns the IssuingCa field if non-nil, zero value otherwise.

### GetIssuingCaOk

`func (o *PkiIssuerIssueWithRoleResponse) GetIssuingCaOk() (*string, bool)`

GetIssuingCaOk returns a tuple with the IssuingCa field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuingCa

`func (o *PkiIssuerIssueWithRoleResponse) SetIssuingCa(v string)`

SetIssuingCa sets IssuingCa field to given value.


### HasIssuingCa

`func (o *PkiIssuerIssueWithRoleResponse) HasIssuingCa() bool`

HasIssuingCa returns a boolean if a field has been set.




### GetPrivateKey

`func (o *PkiIssuerIssueWithRoleResponse) GetPrivateKey() string`

GetPrivateKey returns the PrivateKey field if non-nil, zero value otherwise.

### GetPrivateKeyOk

`func (o *PkiIssuerIssueWithRoleResponse) GetPrivateKeyOk() (*string, bool)`

GetPrivateKeyOk returns a tuple with the PrivateKey field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivateKey

`func (o *PkiIssuerIssueWithRoleResponse) SetPrivateKey(v string)`

SetPrivateKey sets PrivateKey field to given value.


### HasPrivateKey

`func (o *PkiIssuerIssueWithRoleResponse) HasPrivateKey() bool`

HasPrivateKey returns a boolean if a field has been set.




### GetPrivateKeyType

`func (o *PkiIssuerIssueWithRoleResponse) GetPrivateKeyType() string`

GetPrivateKeyType returns the PrivateKeyType field if non-nil, zero value otherwise.

### GetPrivateKeyTypeOk

`func (o *PkiIssuerIssueWithRoleResponse) GetPrivateKeyTypeOk() (*string, bool)`

GetPrivateKeyTypeOk returns a tuple with the PrivateKeyType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivateKeyType

`func (o *PkiIssuerIssueWithRoleResponse) SetPrivateKeyType(v string)`

SetPrivateKeyType sets PrivateKeyType field to given value.


### HasPrivateKeyType

`func (o *PkiIssuerIssueWithRoleResponse) HasPrivateKeyType() bool`

HasPrivateKeyType returns a boolean if a field has been set.




### GetSerialNumber

`func (o *PkiIssuerIssueWithRoleResponse) GetSerialNumber() string`

GetSerialNumber returns the SerialNumber field if non-nil, zero value otherwise.

### GetSerialNumberOk

`func (o *PkiIssuerIssueWithRoleResponse) GetSerialNumberOk() (*string, bool)`

GetSerialNumberOk returns a tuple with the SerialNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNumber

`func (o *PkiIssuerIssueWithRoleResponse) SetSerialNumber(v string)`

SetSerialNumber sets SerialNumber field to given value.


### HasSerialNumber

`func (o *PkiIssuerIssueWithRoleResponse) HasSerialNumber() bool`

HasSerialNumber returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


