[Trolley Python SDK](../README.md) > [balances_gateway](../classes/balances_gateway.md)



# Class: BalancesGateway

## Index

### Methods

* [find](balancesgateway.md#find)



---


## Methods

___

<a id="find"></a>

###  find

► **find**(kind: *"paypal"⎮"trolley"*): `Balance`



*Defined in [balances_gateway.py:49](https://github.com/trolley/python-sdk/tree/master/trolley/balances_gateway.py#L49)*



Fetch the account balance for the given account type

    balances = client.balances.find("trolley")


**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| kind | "paypal"⎮"trolley"   |  The account type to get the balances for |





**Returns:**  `Balances`





___
