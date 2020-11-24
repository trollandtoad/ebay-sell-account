# # RateTable

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**country_code** | **string** | A two-letter ISO 3166 country code representing the eBay marketplace where an item is listed. For implementation help, refer to <a href='https://developer.ebay.com/api-docs/sell/account/types/ba:CountryCodeEnum'>eBay API documentation</a> | [optional]
**locality** | **string** | The region covered by the shipping rate table, either DOMESTIC or INTERNATIONAL. DOMESTIC indicates that the shipping rate table applies to regions within the country where an item is listed (the source country) while INTERNATIONAL indicates that the shipping rate table applies to regions outside of the country where an item is listed. For implementation help, refer to <a href='https://developer.ebay.com/api-docs/sell/account/types/api:ShippingOptionTypeEnum'>eBay API documentation</a> | [optional]
**name** | **string** | The user-defined name for the shipping rate table. Sellers can access Seller Hub (or My eBay > Account > Site Preferences > Shipping preferences) to create and assign names to their shipping rate tables. | [optional]
**rate_table_id** | **string** | A unique eBay-assigned ID for a seller's shipping rate table. Call getRateTables to retrieve the seller's current rate table IDs. | [optional]

[[Back to Model list]](../../README.md#models) [[Back to API list]](../../README.md#endpoints) [[Back to README]](../../README.md)
