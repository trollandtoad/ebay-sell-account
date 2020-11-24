# # Deposit

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**amount** | [**\eBay\Sell\Account\Model\Amount**](Amount.md) |  | [optional]
**due_in** | [**\eBay\Sell\Account\Model\TimeDuration**](TimeDuration.md) |  | [optional]
**payment_methods** | [**\eBay\Sell\Account\Model\PaymentMethod[]**](PaymentMethod.md) | For deposits (which are applicable to only motor listings), the paymentMethodType must be set to 'PAYPAL' and you must also populate the fields in the recipientAccountReference object. Required if your motor vehicles listing requires a deposit. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
