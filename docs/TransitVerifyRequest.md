# TransitVerifyRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Algorithm** | Pointer to **string** | Deprecated: use \&quot;hash_algorithm\&quot; instead. | [optional] [default to "sha2-256"]
**BatchInput** | Pointer to **[]map[string]interface{}** | Specifies a list of items for processing. When this parameter is set, any supplied &#x27;input&#x27;, &#x27;hmac&#x27; or &#x27;signature&#x27; parameters will be ignored. Responses are returned in the &#x27;batch_results&#x27; array component of the &#x27;data&#x27; element of the response. Any batch output will preserve the order of the batch input | [optional] 
**Context** | Pointer to **string** | Base64 encoded context for key derivation. Required if key derivation is enabled; currently only available with ed25519 keys. | [optional] 
**HashAlgorithm** | Pointer to **string** | Hash algorithm to use (POST body parameter). Valid values are: * sha1 * sha2-224 * sha2-256 * sha2-384 * sha2-512 * sha3-224 * sha3-256 * sha3-384 * sha3-512 * none Defaults to \&quot;sha2-256\&quot;. Not valid for all key types. See note about none on signing path. | [optional] [default to "sha2-256"]
**Hmac** | Pointer to **string** | The HMAC, including vault header/key version | [optional] 
**Input** | Pointer to **string** | The base64-encoded input data to verify | [optional] 
**MarshalingAlgorithm** | Pointer to **string** | The method by which to unmarshal the signature when verifying. The default is &#x27;asn1&#x27; which is used by openssl and X.509; can also be set to &#x27;jws&#x27; which is used for JWT signatures in which case the signature is also expected to be url-safe base64 encoding instead of standard base64 encoding. Currently only valid for ECDSA P-256 key types\&quot;. | [optional] [default to "asn1"]
**Prehashed** | Pointer to **bool** | Set to &#x27;true&#x27; when the input is already hashed. If the key type is &#x27;rsa-2048&#x27;, &#x27;rsa-3072&#x27; or &#x27;rsa-4096&#x27;, then the algorithm used to hash the input should be indicated by the &#x27;algorithm&#x27; parameter. | [optional] 
**SaltLength** | Pointer to **string** | The salt length used to sign. Currently only applies to the RSA PSS signature scheme. Options are &#x27;auto&#x27; (the default used by Golang, causing the salt to be as large as possible when signing), &#x27;hash&#x27; (causes the salt length to equal the length of the hash used in the signature), or an integer between the minimum and the maximum permissible salt lengths for the given RSA key size. Defaults to &#x27;auto&#x27;. | [optional] [default to "auto"]
**Signature** | Pointer to **string** | The signature, including vault header/key version | [optional] 
**SignatureAlgorithm** | Pointer to **string** | The signature algorithm to use for signature verification. Currently only applies to RSA key types. Options are &#x27;pss&#x27; or &#x27;pkcs1v15&#x27;. Defaults to &#x27;pss&#x27; | [optional] 
**Urlalgorithm** | Pointer to **string** | Hash algorithm to use (POST URL parameter) | [optional] 



## Methods


### NewTransitVerifyRequest

`func NewTransitVerifyRequest() *TransitVerifyRequest`

NewTransitVerifyRequest instantiates a new TransitVerifyRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTransitVerifyRequestWithDefaults

`func NewTransitVerifyRequestWithDefaults() *TransitVerifyRequest`

NewTransitVerifyRequestWithDefaults instantiates a new TransitVerifyRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetAlgorithm

`func (o *TransitVerifyRequest) GetAlgorithm() string`

GetAlgorithm returns the Algorithm field if non-nil, zero value otherwise.

### GetAlgorithmOk

`func (o *TransitVerifyRequest) GetAlgorithmOk() (*string, bool)`

GetAlgorithmOk returns a tuple with the Algorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlgorithm

`func (o *TransitVerifyRequest) SetAlgorithm(v string)`

SetAlgorithm sets Algorithm field to given value.


### HasAlgorithm

`func (o *TransitVerifyRequest) HasAlgorithm() bool`

HasAlgorithm returns a boolean if a field has been set.




### GetBatchInput

`func (o *TransitVerifyRequest) GetBatchInput() []map[string]interface{}`

GetBatchInput returns the BatchInput field if non-nil, zero value otherwise.

### GetBatchInputOk

`func (o *TransitVerifyRequest) GetBatchInputOk() (*[]map[string]interface{}, bool)`

GetBatchInputOk returns a tuple with the BatchInput field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchInput

`func (o *TransitVerifyRequest) SetBatchInput(v []map[string]interface{})`

SetBatchInput sets BatchInput field to given value.


### HasBatchInput

`func (o *TransitVerifyRequest) HasBatchInput() bool`

HasBatchInput returns a boolean if a field has been set.




### GetContext

`func (o *TransitVerifyRequest) GetContext() string`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *TransitVerifyRequest) GetContextOk() (*string, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *TransitVerifyRequest) SetContext(v string)`

SetContext sets Context field to given value.


### HasContext

`func (o *TransitVerifyRequest) HasContext() bool`

HasContext returns a boolean if a field has been set.




### GetHashAlgorithm

`func (o *TransitVerifyRequest) GetHashAlgorithm() string`

GetHashAlgorithm returns the HashAlgorithm field if non-nil, zero value otherwise.

### GetHashAlgorithmOk

`func (o *TransitVerifyRequest) GetHashAlgorithmOk() (*string, bool)`

GetHashAlgorithmOk returns a tuple with the HashAlgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHashAlgorithm

`func (o *TransitVerifyRequest) SetHashAlgorithm(v string)`

SetHashAlgorithm sets HashAlgorithm field to given value.


### HasHashAlgorithm

`func (o *TransitVerifyRequest) HasHashAlgorithm() bool`

HasHashAlgorithm returns a boolean if a field has been set.




### GetHmac

`func (o *TransitVerifyRequest) GetHmac() string`

GetHmac returns the Hmac field if non-nil, zero value otherwise.

### GetHmacOk

`func (o *TransitVerifyRequest) GetHmacOk() (*string, bool)`

GetHmacOk returns a tuple with the Hmac field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHmac

`func (o *TransitVerifyRequest) SetHmac(v string)`

SetHmac sets Hmac field to given value.


### HasHmac

`func (o *TransitVerifyRequest) HasHmac() bool`

HasHmac returns a boolean if a field has been set.




### GetInput

`func (o *TransitVerifyRequest) GetInput() string`

GetInput returns the Input field if non-nil, zero value otherwise.

### GetInputOk

`func (o *TransitVerifyRequest) GetInputOk() (*string, bool)`

GetInputOk returns a tuple with the Input field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInput

`func (o *TransitVerifyRequest) SetInput(v string)`

SetInput sets Input field to given value.


### HasInput

`func (o *TransitVerifyRequest) HasInput() bool`

HasInput returns a boolean if a field has been set.




### GetMarshalingAlgorithm

`func (o *TransitVerifyRequest) GetMarshalingAlgorithm() string`

GetMarshalingAlgorithm returns the MarshalingAlgorithm field if non-nil, zero value otherwise.

### GetMarshalingAlgorithmOk

`func (o *TransitVerifyRequest) GetMarshalingAlgorithmOk() (*string, bool)`

GetMarshalingAlgorithmOk returns a tuple with the MarshalingAlgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMarshalingAlgorithm

`func (o *TransitVerifyRequest) SetMarshalingAlgorithm(v string)`

SetMarshalingAlgorithm sets MarshalingAlgorithm field to given value.


### HasMarshalingAlgorithm

`func (o *TransitVerifyRequest) HasMarshalingAlgorithm() bool`

HasMarshalingAlgorithm returns a boolean if a field has been set.




### GetPrehashed

`func (o *TransitVerifyRequest) GetPrehashed() bool`

GetPrehashed returns the Prehashed field if non-nil, zero value otherwise.

### GetPrehashedOk

`func (o *TransitVerifyRequest) GetPrehashedOk() (*bool, bool)`

GetPrehashedOk returns a tuple with the Prehashed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrehashed

`func (o *TransitVerifyRequest) SetPrehashed(v bool)`

SetPrehashed sets Prehashed field to given value.


### HasPrehashed

`func (o *TransitVerifyRequest) HasPrehashed() bool`

HasPrehashed returns a boolean if a field has been set.




### GetSaltLength

`func (o *TransitVerifyRequest) GetSaltLength() string`

GetSaltLength returns the SaltLength field if non-nil, zero value otherwise.

### GetSaltLengthOk

`func (o *TransitVerifyRequest) GetSaltLengthOk() (*string, bool)`

GetSaltLengthOk returns a tuple with the SaltLength field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSaltLength

`func (o *TransitVerifyRequest) SetSaltLength(v string)`

SetSaltLength sets SaltLength field to given value.


### HasSaltLength

`func (o *TransitVerifyRequest) HasSaltLength() bool`

HasSaltLength returns a boolean if a field has been set.




### GetSignature

`func (o *TransitVerifyRequest) GetSignature() string`

GetSignature returns the Signature field if non-nil, zero value otherwise.

### GetSignatureOk

`func (o *TransitVerifyRequest) GetSignatureOk() (*string, bool)`

GetSignatureOk returns a tuple with the Signature field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignature

`func (o *TransitVerifyRequest) SetSignature(v string)`

SetSignature sets Signature field to given value.


### HasSignature

`func (o *TransitVerifyRequest) HasSignature() bool`

HasSignature returns a boolean if a field has been set.




### GetSignatureAlgorithm

`func (o *TransitVerifyRequest) GetSignatureAlgorithm() string`

GetSignatureAlgorithm returns the SignatureAlgorithm field if non-nil, zero value otherwise.

### GetSignatureAlgorithmOk

`func (o *TransitVerifyRequest) GetSignatureAlgorithmOk() (*string, bool)`

GetSignatureAlgorithmOk returns a tuple with the SignatureAlgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSignatureAlgorithm

`func (o *TransitVerifyRequest) SetSignatureAlgorithm(v string)`

SetSignatureAlgorithm sets SignatureAlgorithm field to given value.


### HasSignatureAlgorithm

`func (o *TransitVerifyRequest) HasSignatureAlgorithm() bool`

HasSignatureAlgorithm returns a boolean if a field has been set.




### GetUrlalgorithm

`func (o *TransitVerifyRequest) GetUrlalgorithm() string`

GetUrlalgorithm returns the Urlalgorithm field if non-nil, zero value otherwise.

### GetUrlalgorithmOk

`func (o *TransitVerifyRequest) GetUrlalgorithmOk() (*string, bool)`

GetUrlalgorithmOk returns a tuple with the Urlalgorithm field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUrlalgorithm

`func (o *TransitVerifyRequest) SetUrlalgorithm(v string)`

SetUrlalgorithm sets Urlalgorithm field to given value.


### HasUrlalgorithm

`func (o *TransitVerifyRequest) HasUrlalgorithm() bool`

HasUrlalgorithm returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


