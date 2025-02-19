# TransitDecryptRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AssociatedData** | Pointer to **string** | When using an AEAD cipher mode, such as AES-GCM, this parameter allows passing associated data (AD/AAD) into the encryption function; this data must be passed on subsequent decryption requests but can be transited in plaintext. On successful decryption, both the ciphertext and the associated data are attested not to have been tampered with. | [optional] 
**BatchInput** | Pointer to **[]map[string]interface{}** | Specifies a list of items to be decrypted in a single batch. When this parameter is set, if the parameters &#x27;ciphertext&#x27;, &#x27;context&#x27; and &#x27;nonce&#x27; are also set, they will be ignored. Any batch output will preserve the order of the batch input. | [optional] 
**Ciphertext** | Pointer to **string** | The ciphertext to decrypt, provided as returned by encrypt. | [optional] 
**Context** | Pointer to **string** | Base64 encoded context for key derivation. Required if key derivation is enabled. | [optional] 
**Nonce** | Pointer to **string** | Base64 encoded nonce value used during encryption. Must be provided if convergent encryption is enabled for this key and the key was generated with Vault 0.6.1. Not required for keys created in 0.6.2+. | [optional] 
**PartialFailureResponseCode** | Pointer to **int32** | Ordinarily, if a batch item fails to decrypt due to a bad input, but other batch items succeed, the HTTP response code is 400 (Bad Request). Some applications may want to treat partial failures differently. Providing the parameter returns the given response code integer instead of a 400 in this case. If all values fail HTTP 400 is still returned. | [optional] 



## Methods


### NewTransitDecryptRequest

`func NewTransitDecryptRequest() *TransitDecryptRequest`

NewTransitDecryptRequest instantiates a new TransitDecryptRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTransitDecryptRequestWithDefaults

`func NewTransitDecryptRequestWithDefaults() *TransitDecryptRequest`

NewTransitDecryptRequestWithDefaults instantiates a new TransitDecryptRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set


### GetAssociatedData

`func (o *TransitDecryptRequest) GetAssociatedData() string`

GetAssociatedData returns the AssociatedData field if non-nil, zero value otherwise.

### GetAssociatedDataOk

`func (o *TransitDecryptRequest) GetAssociatedDataOk() (*string, bool)`

GetAssociatedDataOk returns a tuple with the AssociatedData field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssociatedData

`func (o *TransitDecryptRequest) SetAssociatedData(v string)`

SetAssociatedData sets AssociatedData field to given value.


### HasAssociatedData

`func (o *TransitDecryptRequest) HasAssociatedData() bool`

HasAssociatedData returns a boolean if a field has been set.




### GetBatchInput

`func (o *TransitDecryptRequest) GetBatchInput() []map[string]interface{}`

GetBatchInput returns the BatchInput field if non-nil, zero value otherwise.

### GetBatchInputOk

`func (o *TransitDecryptRequest) GetBatchInputOk() (*[]map[string]interface{}, bool)`

GetBatchInputOk returns a tuple with the BatchInput field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBatchInput

`func (o *TransitDecryptRequest) SetBatchInput(v []map[string]interface{})`

SetBatchInput sets BatchInput field to given value.


### HasBatchInput

`func (o *TransitDecryptRequest) HasBatchInput() bool`

HasBatchInput returns a boolean if a field has been set.




### GetCiphertext

`func (o *TransitDecryptRequest) GetCiphertext() string`

GetCiphertext returns the Ciphertext field if non-nil, zero value otherwise.

### GetCiphertextOk

`func (o *TransitDecryptRequest) GetCiphertextOk() (*string, bool)`

GetCiphertextOk returns a tuple with the Ciphertext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCiphertext

`func (o *TransitDecryptRequest) SetCiphertext(v string)`

SetCiphertext sets Ciphertext field to given value.


### HasCiphertext

`func (o *TransitDecryptRequest) HasCiphertext() bool`

HasCiphertext returns a boolean if a field has been set.




### GetContext

`func (o *TransitDecryptRequest) GetContext() string`

GetContext returns the Context field if non-nil, zero value otherwise.

### GetContextOk

`func (o *TransitDecryptRequest) GetContextOk() (*string, bool)`

GetContextOk returns a tuple with the Context field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContext

`func (o *TransitDecryptRequest) SetContext(v string)`

SetContext sets Context field to given value.


### HasContext

`func (o *TransitDecryptRequest) HasContext() bool`

HasContext returns a boolean if a field has been set.




### GetNonce

`func (o *TransitDecryptRequest) GetNonce() string`

GetNonce returns the Nonce field if non-nil, zero value otherwise.

### GetNonceOk

`func (o *TransitDecryptRequest) GetNonceOk() (*string, bool)`

GetNonceOk returns a tuple with the Nonce field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNonce

`func (o *TransitDecryptRequest) SetNonce(v string)`

SetNonce sets Nonce field to given value.


### HasNonce

`func (o *TransitDecryptRequest) HasNonce() bool`

HasNonce returns a boolean if a field has been set.




### GetPartialFailureResponseCode

`func (o *TransitDecryptRequest) GetPartialFailureResponseCode() int32`

GetPartialFailureResponseCode returns the PartialFailureResponseCode field if non-nil, zero value otherwise.

### GetPartialFailureResponseCodeOk

`func (o *TransitDecryptRequest) GetPartialFailureResponseCodeOk() (*int32, bool)`

GetPartialFailureResponseCodeOk returns a tuple with the PartialFailureResponseCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPartialFailureResponseCode

`func (o *TransitDecryptRequest) SetPartialFailureResponseCode(v int32)`

SetPartialFailureResponseCode sets PartialFailureResponseCode field to given value.


### HasPartialFailureResponseCode

`func (o *TransitDecryptRequest) HasPartialFailureResponseCode() bool`

HasPartialFailureResponseCode returns a boolean if a field has been set.









[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


