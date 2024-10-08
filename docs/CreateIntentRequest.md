# CreateIntentRequest

## Properties
Name | Type | Description                                                                 | Notes
------------ | ------------- |-----------------------------------------------------------------------------| -------------
**clientId** | **String** | Unique client identifier.                                                   | [optional] 
**userId** | **String** | The user ID associated with the payment.                                    | 
**productId** | **String** | The ID of the product being purchased.                                      | 
**productType** | **String** | Type of the product.                                                        | 
**resume** | [**ResumeDto**](ResumeDto.md) |                                                                             | [optional] 
**products** | [**ProductDto**](ProductDto.md) | A list of products associated with the payment.                             | 
**currency** | **String** | Currency code for the payment. Must respect the ISO 4217 and be upper case. | 
**company** | **String** | Company making the payment request.                                         | 
**microsite** | **String** | The microsite making the payment request.                                   | 
**country** | **String** | Must be a valid ISO 3166-1 alpha-2 code.                                    | 
**amount** | **BigDecimal** | The amount to be charged.                                                   | 

<a name="ProductTypeEnum"></a>
## Enum: ProductTypeEnum

* `BOOKING` (value: `"BOOKING"`)
* `SUBSCRIPTION` (value: `"SUBSCRIPTION"`)
* `GIFT` (value: `"GIFT"`)
* `EVENT` (value: `"EVENT"`)
* `SERVICE` (value: `"SERVICE"`)
* `ACCOMMODATION` (value: `"ACCOMMODATION"`)
* `FLIGHT` (value: `"FLIGHT"`)
* `PACKAGE` (value: `"PACKAGE"`)
* `INSURANCE` (value: `"INSURANCE"`)
* `CRUISE` (value: `"CRUISE"`)
* `ACTIVITY` (value: `"ACTIVITY"`)
* `TRANSFER` (value: `"TRANSFER"`)

