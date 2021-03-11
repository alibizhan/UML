## Online Shopping
### 1. top level use cases
Web Customer actor uses some web site to make purchases online. Top level use cases are View Items, Make Purchase and Client Register. View Items use case could be used by customer as top level use case if customer only wants to find and see some products. This use case could also be used as a part of Make Purchase use case. Client Register use case allows customer to register on the web site, for example to get some coupons or be invited to private sales. Note, that Checkout use case is included use case not available by itself - checkout is part of making purchase.

Except for the Web Customer actor there are several other actors which will be described below with detailed use cases.

### 2. View Items use case
View Items use case is extended by several optional use cases - customer may search for items, browse catalog, view items recommended for him/her, add items to shopping cart or wish list. All these use cases are extending use cases because they provide some optional functions allowing customer to find item.

Customer Authentication use case is included in View Recommended Items and Add to Wish List because both require the customer to be authenticated. At the same time, item could be added to the shopping cart without user authentication.

### 3. Checkout use case
Checkout use case includes several required uses cases. Web customer should be authenticated. It could be done through user login page, user authentication cookie ("Remember me") or Single Sign-On (SSO). Web site authentication service is used in all these use cases, while SSO also requires participation of external identity provider.

Checkout use case also includes Payment use case which could be done either by using credit card and external credit payment service or with PayPal.

[For more details](https://www.uml-diagrams.org/examples/online-shopping-use-case-diagram-example.html?context=uc-examples)
