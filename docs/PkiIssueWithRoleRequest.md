# PkiIssueWithRoleRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AltNames** | Pointer to **string** | The requested Subject Alternative Names, if any, in a comma-delimited list. If email protection is enabled for the role, this may contain email addresses. | [optional] 
**CommonName** | Pointer to **string** | The requested common name; if you want more than one, specify the alternative names in the alt_names map. If email protection is enabled in the role, this may be an email address. | [optional] 
**ExcludeCnFromSans** | Pointer to **bool** | If true, the Common Name will not be included in DNS or Email Subject Alternate Names. Defaults to false (CN is included). | [optional] [default to false]
**Format** | Pointer to **string** | Format for returned data. Can be \&quot;pem\&quot;, \&quot;der\&quot;, or \&quot;pem_bundle\&quot;. If \&quot;pem_bundle\&quot;, any private key and issuing cert will be appended to the certificate pem. If \&quot;der\&quot;, the value will be base64 encoded. Defaults to \&quot;pem\&quot;. | [optional] [default to "pem"]
**IpSans** | Pointer to **[]string** | The requested IP SANs, if any, in a comma-delimited list | [optional] 
**IssuerRef** | Pointer to **string** | Reference to a existing issuer; either \&quot;default\&quot; for the configured default issuer, an identifier or the name assigned to the issuer. | [optional] [default to "default"]
**NotAfter** | Pointer to **string** | Set the not after field of the certificate with specified date value. The value format should be given in UTC format YYYY-MM-ddTHH:MM:SSZ | [optional] 
**OtherSans** | Pointer to **[]string** | Requested other SANs, in an array with the format &lt;oid&gt;;UTF8:&lt;utf8 string value&gt; for each entry. | [optional] 
**PrivateKeyFormat** | Pointer to **string** | Format for the returned private key. Generally the default will be controlled by the \&quot;format\&quot; parameter as either base64-encoded DER or PEM-encoded DER. However, this can be set to \&quot;pkcs8\&quot; to have the returned private key contain base64-encoded pkcs8 or PEM-encoded pkcs8 instead. Defaults to \&quot;der\&quot;. | [optional] [default to "der"]
**RemoveRootsFromChain** | Pointer to **bool** | Whether or not to remove self-signed CA certificates in the output of the ca_chain field. | [optional] [default to false]
**SerialNumber** | Pointer to **string** | The Subject&#x27;s requested serial number, if any. See RFC 4519 Section 2.31 &#x27;serialNumber&#x27; for a description of this field. If you want more than one, specify alternative names in the alt_names map using OID 2.5.4.5. This has no impact on the final certificate&#x27;s Serial Number field. | [optional] 
**Ttl** | Pointer to **int32** | The requested Time To Live for the certificate; sets the expiration date. If not specified the role default, backend default, or system default TTL is used, in that order. Cannot be larger than the role max TTL. | [optional] 
**UriSans** | Pointer to **[]string** | The requested URI SANs, if any, in a comma-delimited list. | [optional] 
**UserIds** | Pointer to **[]string** | The requested user_ids value to place in the subject, if any, in a comma-delimited list. Restricted by allowed_user_ids. Any values are added with OID 0.9.2342.19200300.100.1.1. | [optional] 



## Methods


### NewPkiIssueWithRoleRequest

`func NewPkiIssueWithRoleRequest() *PkiIssueWithRoleRequest`

NewPkiIssueWithRoleRequest instantiates a new PkiIssueWithRoleRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPkiIssueWithRoleRequestWithDefaults

`func NewPkiIssueWithRoleRequestWithDefaults() *PkiIssueWithRoleRequest`

NewPkiIssueWithRoleRequestWithDefaults instantiates a new PkiIssueWithRoleRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetAltNames

`func (o *PkiIssueWithRoleRequest) GetAltNames() string`

GetAltNames returns the AltNames field if non-nil, zero value otherwise.

### GetAltNamesOk

`func (o *PkiIssueWithRoleRequest) GetAltNamesOk() (*string, bool)`

GetAltNamesOk returns a tuple with the AltNames field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAltNames

`func (o *PkiIssueWithRoleRequest) SetAltNames(v string)`

SetAltNames sets AltNames field to given value.


### HasAltNames

`func (o *PkiIssueWithRoleRequest) HasAltNames() bool`

HasAltNames returns a boolean if a field has been set.




### GetCommonName

`func (o *PkiIssueWithRoleRequest) GetCommonName() string`

GetCommonName returns the CommonName field if non-nil, zero value otherwise.

### GetCommonNameOk

`func (o *PkiIssueWithRoleRequest) GetCommonNameOk() (*string, bool)`

GetCommonNameOk returns a tuple with the CommonName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCommonName

`func (o *PkiIssueWithRoleRequest) SetCommonName(v string)`

SetCommonName sets CommonName field to given value.


### HasCommonName

`func (o *PkiIssueWithRoleRequest) HasCommonName() bool`

HasCommonName returns a boolean if a field has been set.




### GetExcludeCnFromSans

`func (o *PkiIssueWithRoleRequest) GetExcludeCnFromSans() bool`

GetExcludeCnFromSans returns the ExcludeCnFromSans field if non-nil, zero value otherwise.

### GetExcludeCnFromSansOk

`func (o *PkiIssueWithRoleRequest) GetExcludeCnFromSansOk() (*bool, bool)`

GetExcludeCnFromSansOk returns a tuple with the ExcludeCnFromSans field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExcludeCnFromSans

`func (o *PkiIssueWithRoleRequest) SetExcludeCnFromSans(v bool)`

SetExcludeCnFromSans sets ExcludeCnFromSans field to given value.


### HasExcludeCnFromSans

`func (o *PkiIssueWithRoleRequest) HasExcludeCnFromSans() bool`

HasExcludeCnFromSans returns a boolean if a field has been set.




### GetFormat

`func (o *PkiIssueWithRoleRequest) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *PkiIssueWithRoleRequest) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *PkiIssueWithRoleRequest) SetFormat(v string)`

SetFormat sets Format field to given value.


### HasFormat

`func (o *PkiIssueWithRoleRequest) HasFormat() bool`

HasFormat returns a boolean if a field has been set.




### GetIpSans

`func (o *PkiIssueWithRoleRequest) GetIpSans() []string`

GetIpSans returns the IpSans field if non-nil, zero value otherwise.

### GetIpSansOk

`func (o *PkiIssueWithRoleRequest) GetIpSansOk() (*[]string, bool)`

GetIpSansOk returns a tuple with the IpSans field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIpSans

`func (o *PkiIssueWithRoleRequest) SetIpSans(v []string)`

SetIpSans sets IpSans field to given value.


### HasIpSans

`func (o *PkiIssueWithRoleRequest) HasIpSans() bool`

HasIpSans returns a boolean if a field has been set.




### GetIssuerRef

`func (o *PkiIssueWithRoleRequest) GetIssuerRef() string`

GetIssuerRef returns the IssuerRef field if non-nil, zero value otherwise.

### GetIssuerRefOk

`func (o *PkiIssueWithRoleRequest) GetIssuerRefOk() (*string, bool)`

GetIssuerRefOk returns a tuple with the IssuerRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuerRef

`func (o *PkiIssueWithRoleRequest) SetIssuerRef(v string)`

SetIssuerRef sets IssuerRef field to given value.


### HasIssuerRef

`func (o *PkiIssueWithRoleRequest) HasIssuerRef() bool`

HasIssuerRef returns a boolean if a field has been set.




### GetNotAfter

`func (o *PkiIssueWithRoleRequest) GetNotAfter() string`

GetNotAfter returns the NotAfter field if non-nil, zero value otherwise.

### GetNotAfterOk

`func (o *PkiIssueWithRoleRequest) GetNotAfterOk() (*string, bool)`

GetNotAfterOk returns a tuple with the NotAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotAfter

`func (o *PkiIssueWithRoleRequest) SetNotAfter(v string)`

SetNotAfter sets NotAfter field to given value.


### HasNotAfter

`func (o *PkiIssueWithRoleRequest) HasNotAfter() bool`

HasNotAfter returns a boolean if a field has been set.




### GetOtherSans

`func (o *PkiIssueWithRoleRequest) GetOtherSans() []string`

GetOtherSans returns the OtherSans field if non-nil, zero value otherwise.

### GetOtherSansOk

`func (o *PkiIssueWithRoleRequest) GetOtherSansOk() (*[]string, bool)`

GetOtherSansOk returns a tuple with the OtherSans field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherSans

`func (o *PkiIssueWithRoleRequest) SetOtherSans(v []string)`

SetOtherSans sets OtherSans field to given value.


### HasOtherSans

`func (o *PkiIssueWithRoleRequest) HasOtherSans() bool`

HasOtherSans returns a boolean if a field has been set.




### GetPrivateKeyFormat

`func (o *PkiIssueWithRoleRequest) GetPrivateKeyFormat() string`

GetPrivateKeyFormat returns the PrivateKeyFormat field if non-nil, zero value otherwise.

### GetPrivateKeyFormatOk

`func (o *PkiIssueWithRoleRequest) GetPrivateKeyFormatOk() (*string, bool)`

GetPrivateKeyFormatOk returns a tuple with the PrivateKeyFormat field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrivateKeyFormat

`func (o *PkiIssueWithRoleRequest) SetPrivateKeyFormat(v string)`

SetPrivateKeyFormat sets PrivateKeyFormat field to given value.


### HasPrivateKeyFormat

`func (o *PkiIssueWithRoleRequest) HasPrivateKeyFormat() bool`

HasPrivateKeyFormat returns a boolean if a field has been set.




### GetRemoveRootsFromChain

`func (o *PkiIssueWithRoleRequest) GetRemoveRootsFromChain() bool`

GetRemoveRootsFromChain returns the RemoveRootsFromChain field if non-nil, zero value otherwise.

### GetRemoveRootsFromChainOk

`func (o *PkiIssueWithRoleRequest) GetRemoveRootsFromChainOk() (*bool, bool)`

GetRemoveRootsFromChainOk returns a tuple with the RemoveRootsFromChain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRemoveRootsFromChain

`func (o *PkiIssueWithRoleRequest) SetRemoveRootsFromChain(v bool)`

SetRemoveRootsFromChain sets RemoveRootsFromChain field to given value.


### HasRemoveRootsFromChain

`func (o *PkiIssueWithRoleRequest) HasRemoveRootsFromChain() bool`

HasRemoveRootsFromChain returns a boolean if a field has been set.




### GetSerialNumber

`func (o *PkiIssueWithRoleRequest) GetSerialNumber() string`

GetSerialNumber returns the SerialNumber field if non-nil, zero value otherwise.

### GetSerialNumberOk

`func (o *PkiIssueWithRoleRequest) GetSerialNumberOk() (*string, bool)`

GetSerialNumberOk returns a tuple with the SerialNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNumber

`func (o *PkiIssueWithRoleRequest) SetSerialNumber(v string)`

SetSerialNumber sets SerialNumber field to given value.


### HasSerialNumber

`func (o *PkiIssueWithRoleRequest) HasSerialNumber() bool`

HasSerialNumber returns a boolean if a field has been set.




### GetTtl

`func (o *PkiIssueWithRoleRequest) GetTtl() int32`

GetTtl returns the Ttl field if non-nil, zero value otherwise.

### GetTtlOk

`func (o *PkiIssueWithRoleRequest) GetTtlOk() (*int32, bool)`

GetTtlOk returns a tuple with the Ttl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTtl

`func (o *PkiIssueWithRoleRequest) SetTtl(v int32)`

SetTtl sets Ttl field to given value.


### HasTtl

`func (o *PkiIssueWithRoleRequest) HasTtl() bool`

HasTtl returns a boolean if a field has been set.




### GetUriSans

`func (o *PkiIssueWithRoleRequest) GetUriSans() []string`

GetUriSans returns the UriSans field if non-nil, zero value otherwise.

### GetUriSansOk

`func (o *PkiIssueWithRoleRequest) GetUriSansOk() (*[]string, bool)`

GetUriSansOk returns a tuple with the UriSans field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUriSans

`func (o *PkiIssueWithRoleRequest) SetUriSans(v []string)`

SetUriSans sets UriSans field to given value.


### HasUriSans

`func (o *PkiIssueWithRoleRequest) HasUriSans() bool`

HasUriSans returns a boolean if a field has been set.




### GetUserIds

`func (o *PkiIssueWithRoleRequest) GetUserIds() []string`

GetUserIds returns the UserIds field if non-nil, zero value otherwise.

### GetUserIdsOk

`func (o *PkiIssueWithRoleRequest) GetUserIdsOk() (*[]string, bool)`

GetUserIdsOk returns a tuple with the UserIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUserIds

`func (o *PkiIssueWithRoleRequest) SetUserIds(v []string)`

SetUserIds sets UserIds field to given value.


### HasUserIds

`func (o *PkiIssueWithRoleRequest) HasUserIds() bool`

HasUserIds returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


