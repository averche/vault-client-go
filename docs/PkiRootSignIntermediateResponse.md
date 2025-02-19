# PkiRootSignIntermediateResponse


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**CaChain** | Pointer to **[]string** | CA Chain | [optional] 
**Certificate** | Pointer to **string** | Certificate | [optional] 
**Expiration** | Pointer to **int64** | Expiration Time | [optional] 
**IssuingCa** | Pointer to **string** | Issuing CA | [optional] 
**SerialNumber** | Pointer to **string** | Serial Number | [optional] 



## Methods


### NewPkiRootSignIntermediateResponse

`func NewPkiRootSignIntermediateResponse() *PkiRootSignIntermediateResponse`

NewPkiRootSignIntermediateResponse instantiates a new PkiRootSignIntermediateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPkiRootSignIntermediateResponseWithDefaults

`func NewPkiRootSignIntermediateResponseWithDefaults() *PkiRootSignIntermediateResponse`

NewPkiRootSignIntermediateResponseWithDefaults instantiates a new PkiRootSignIntermediateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetCaChain

`func (o *PkiRootSignIntermediateResponse) GetCaChain() []string`

GetCaChain returns the CaChain field if non-nil, zero value otherwise.

### GetCaChainOk

`func (o *PkiRootSignIntermediateResponse) GetCaChainOk() (*[]string, bool)`

GetCaChainOk returns a tuple with the CaChain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCaChain

`func (o *PkiRootSignIntermediateResponse) SetCaChain(v []string)`

SetCaChain sets CaChain field to given value.


### HasCaChain

`func (o *PkiRootSignIntermediateResponse) HasCaChain() bool`

HasCaChain returns a boolean if a field has been set.




### GetCertificate

`func (o *PkiRootSignIntermediateResponse) GetCertificate() string`

GetCertificate returns the Certificate field if non-nil, zero value otherwise.

### GetCertificateOk

`func (o *PkiRootSignIntermediateResponse) GetCertificateOk() (*string, bool)`

GetCertificateOk returns a tuple with the Certificate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificate

`func (o *PkiRootSignIntermediateResponse) SetCertificate(v string)`

SetCertificate sets Certificate field to given value.


### HasCertificate

`func (o *PkiRootSignIntermediateResponse) HasCertificate() bool`

HasCertificate returns a boolean if a field has been set.




### GetExpiration

`func (o *PkiRootSignIntermediateResponse) GetExpiration() int64`

GetExpiration returns the Expiration field if non-nil, zero value otherwise.

### GetExpirationOk

`func (o *PkiRootSignIntermediateResponse) GetExpirationOk() (*int64, bool)`

GetExpirationOk returns a tuple with the Expiration field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiration

`func (o *PkiRootSignIntermediateResponse) SetExpiration(v int64)`

SetExpiration sets Expiration field to given value.


### HasExpiration

`func (o *PkiRootSignIntermediateResponse) HasExpiration() bool`

HasExpiration returns a boolean if a field has been set.




### GetIssuingCa

`func (o *PkiRootSignIntermediateResponse) GetIssuingCa() string`

GetIssuingCa returns the IssuingCa field if non-nil, zero value otherwise.

### GetIssuingCaOk

`func (o *PkiRootSignIntermediateResponse) GetIssuingCaOk() (*string, bool)`

GetIssuingCaOk returns a tuple with the IssuingCa field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuingCa

`func (o *PkiRootSignIntermediateResponse) SetIssuingCa(v string)`

SetIssuingCa sets IssuingCa field to given value.


### HasIssuingCa

`func (o *PkiRootSignIntermediateResponse) HasIssuingCa() bool`

HasIssuingCa returns a boolean if a field has been set.




### GetSerialNumber

`func (o *PkiRootSignIntermediateResponse) GetSerialNumber() string`

GetSerialNumber returns the SerialNumber field if non-nil, zero value otherwise.

### GetSerialNumberOk

`func (o *PkiRootSignIntermediateResponse) GetSerialNumberOk() (*string, bool)`

GetSerialNumberOk returns a tuple with the SerialNumber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSerialNumber

`func (o *PkiRootSignIntermediateResponse) SetSerialNumber(v string)`

SetSerialNumber sets SerialNumber field to given value.


### HasSerialNumber

`func (o *PkiRootSignIntermediateResponse) HasSerialNumber() bool`

HasSerialNumber returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


