![logo](assets/img/logo48.png) Using
==========

/* This page is subject to change at any time. */

Basic info
----------

### Check balance

Check the balance of the main account.

Command

	?

Example

	?

Return

	You have 50 points, 368.988352 XRP, 1 USD, 0 CNY, 3.3501 CNY

### Check balance for all accounts

One can host multiple accounts. To check the balance of all accounts of more than one account is linked, use this Command.

Command

	?

Example

	??

Return

	主帐户:
	368.988352 XRP, 1 USD, 0 CNY, 3.3501 CNY
	帐户1:
	148.276276 XRP, 0 BTC, 78.88 CNY, 0.0081202 USD, 9 CNY
	帐户2:
	账户未激活.

### List all accounts to show ripple public addresses

Command

	list

Example

	list

Return

	您的Ripple账户地址是: r4tanZ23Dg43p8n7BxoKbQyfD4uG2Aj3LL

	全部账户信息:
	主帐户:
	r4tanZ23Dg43p8n7BxoKbQyfD4uG2Aj3LL
	帐户1:
	r9ABKNjoXHy8uvUAchxjhp3W6kvETaABQA
	帐户2:
	rGtrVow9K8r3r1T3LD5kyztfBogqXGWXKT

### Show gateways

Command

	gateways

Example
	
	gateways

Return. Each line means the maximum amount of this currency you can hold.

	USD: 100/sundaywork
	CNY: 303/sundaywork
	CNY: 100/ripplecn

### Set trust to gateway

Command

	trust [currency] [amount] [gateway]

Example
	
	trust cny 300 rfnfenhqw2Ud2S3n4GRrheQR7wQbTLd7MG

Return

	about to set trust 303 CNY...
	呼叫签名...
	request submitted
	Transaction succeeded.

Payment
----------

### Send payment to someone
	
Command

	pay [target] [amount] [currency]

Example
	
	pay someone@gmail.com 1 USD

Return

	todo