# Bitcoin Optech's Compatibility Website Project Plan

Given the purpose of the website as outlined in the [README](../README.md), we need to provide screens for visitors to:

## View compatibility information for a specific Bitcoin service (exchange, wallet, block explorer, etc)

![Service Detail Page](images/Service-Detail-Page.png)

This is the "service detail page" which shows all compatibility information related to a particular wallet/exchange/explorer/etc all in one place.

## View a summary/matrix of compatibility information for a given type of service (exchanges, wallets, explorers) listing all services

![Service List Page](images/Service-List-Page.png)

This is the "service list page" which shows all of the services within a particular type. For example all wallets compared to one another.

There will be Service List Pages for Exchanges, Wallets, Explorers. In the future Libraries could be included as well.

This mockup shows what it might look like if RBF tab was selected.

The "Overview" tab would have a matrix like the one shown for RBF but would just have columns for RBF|CPFP|Bech32 and some sort of score/color coding as to the summary of how well that Bitcoin feature is supported in that wallet.