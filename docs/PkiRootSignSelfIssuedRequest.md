# PkiRootSignSelfIssuedRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Certificate** | Pointer to **string** | PEM-format self-issued certificate to be signed. | [optional] 
**IssuerRef** | Pointer to **string** | Reference to a existing issuer; either \&quot;default\&quot; for the configured default issuer, an identifier or the name assigned to the issuer. | [optional] [default to "default"]
**RequireMatchingCertificateAlgorithms** | Pointer to **bool** | If true, require the public key algorithm of the signer to match that of the self issued certificate. | [optional] [default to false]



## Methods


### NewPkiRootSignSelfIssuedRequest

`func NewPkiRootSignSelfIssuedRequest() *PkiRootSignSelfIssuedRequest`

NewPkiRootSignSelfIssuedRequest instantiates a new PkiRootSignSelfIssuedRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPkiRootSignSelfIssuedRequestWithDefaults

`func NewPkiRootSignSelfIssuedRequestWithDefaults() *PkiRootSignSelfIssuedRequest`

NewPkiRootSignSelfIssuedRequestWithDefaults instantiates a new PkiRootSignSelfIssuedRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetCertificate

`func (o *PkiRootSignSelfIssuedRequest) GetCertificate() string`

GetCertificate returns the Certificate field if non-nil, zero value otherwise.

### GetCertificateOk

`func (o *PkiRootSignSelfIssuedRequest) GetCertificateOk() (*string, bool)`

GetCertificateOk returns a tuple with the Certificate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCertificate

`func (o *PkiRootSignSelfIssuedRequest) SetCertificate(v string)`

SetCertificate sets Certificate field to given value.


### HasCertificate

`func (o *PkiRootSignSelfIssuedRequest) HasCertificate() bool`

HasCertificate returns a boolean if a field has been set.




### GetIssuerRef

`func (o *PkiRootSignSelfIssuedRequest) GetIssuerRef() string`

GetIssuerRef returns the IssuerRef field if non-nil, zero value otherwise.

### GetIssuerRefOk

`func (o *PkiRootSignSelfIssuedRequest) GetIssuerRefOk() (*string, bool)`

GetIssuerRefOk returns a tuple with the IssuerRef field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIssuerRef

`func (o *PkiRootSignSelfIssuedRequest) SetIssuerRef(v string)`

SetIssuerRef sets IssuerRef field to given value.


### HasIssuerRef

`func (o *PkiRootSignSelfIssuedRequest) HasIssuerRef() bool`

HasIssuerRef returns a boolean if a field has been set.




### GetRequireMatchingCertificateAlgorithms

`func (o *PkiRootSignSelfIssuedRequest) GetRequireMatchingCertificateAlgorithms() bool`

GetRequireMatchingCertificateAlgorithms returns the RequireMatchingCertificateAlgorithms field if non-nil, zero value otherwise.

### GetRequireMatchingCertificateAlgorithmsOk

`func (o *PkiRootSignSelfIssuedRequest) GetRequireMatchingCertificateAlgorithmsOk() (*bool, bool)`

GetRequireMatchingCertificateAlgorithmsOk returns a tuple with the RequireMatchingCertificateAlgorithms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequireMatchingCertificateAlgorithms

`func (o *PkiRootSignSelfIssuedRequest) SetRequireMatchingCertificateAlgorithms(v bool)`

SetRequireMatchingCertificateAlgorithms sets RequireMatchingCertificateAlgorithms field to given value.


### HasRequireMatchingCertificateAlgorithms

`func (o *PkiRootSignSelfIssuedRequest) HasRequireMatchingCertificateAlgorithms() bool`

HasRequireMatchingCertificateAlgorithms returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


