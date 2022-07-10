## Slippage Checks

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-05-sturdy.md#h-01-hard-coded-slippage-may-freeze-user-funds-during-market-turbulence

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-05-sturdy.md#m-06-yield-can-be-unfairly-divided-because-of-mevjust-in-time-stablecoin-deposits

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-07-spartan.md#h-07-missing-slippage-checks

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-09-yaxis.md#m-06---controller-is-vulnerable-to-sandwich-attack

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-09-yaxis.md#m-12-harvest-can-be-frontrun

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-10-mochi.md#m-02-regerralfeepool-is-vulnerable-to-mev-searcher

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-badgerzaps.md#m-05-no-slippage-control-on-deposit-of-ibbtcvaultzapsol

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-badgerzaps.md#m-01-improper-implementation-of-slippage-check

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-malt.md#m-27-slippage-checks-when-adding-liquidity-are-too-strict

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-vader.md#h-01-minting-and-burning-synths-exposes-users-to-unlimited-slippage

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-vader.md#h-29-vaderpoolv2mintfungible-exposes-users-to-unlimited-slippage

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-vader.md#h-31-unused-slippage-params

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-12-vader.md#m-01-vaderpoolv2mintfungible-exposes-users-to-unlimited-slippage

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-01-notional.md#m-02-snotesol_mintfromassets-lack-of-slippage-control

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-01-sandclock.md#h-03-vaults-with-non-ust-underlying-asset-vulnerable-to-flash-loan-attack-on-curve-pool

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-01-trader-joe.md#m-09-createpair-expects-zero-slippage

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-02-hubble.md#m-14-liquidation-is-vulnerable-to-sandwich-attacks

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-02-redacted-cartel.md#m-05-wrong-slippage-check

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-04-backd.md#m-11-position-owner-should-set-allowed-slippage

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-04-backd.md#m-04-cvxcrvrewardslocker-implements-a-swap-without-a-slippage-check-that-can-result-in-a-loss-of-funds-through-me

## Msg.value validation

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-03-lifinance.md#m-07-erc20-bridging-functions-do-not-revert-on-non-zero-msgvalue

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-05-cally.md#m-03-users-may-accidentally-overpay-in-buyoption-and-the-excess-will-be-paid-to-the-vault-creator

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-05-sturdy.md#m-01-possible-lost-msgvalue

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-nested.md#m-03-nestedfactory-ensure-zero-msgvalue-if-transferring-from-user-and-inputtoken-is-not-eth-

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-03-lifinance.md#m-09-should-prevent-users-from-sending-more-native-tokens-in-the-startbridgetokensviacbridge-function

## Swap Path

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-05-sturdy.md#m-02-uniswap_fee-is-hardcoded-which-will-lead-to-significant-losses-compared-to-optimal-routing

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-04-jpegd.md#m-08-_swapuniswapv2-may-use-an-improper-path-which-can-cause-a-loss-of-the-majority-of-the-rewardtokens

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-12-mellow.md#m-06-uniswapv3s-path-issue-for-swapexactoutput 

## Unbounded Loop

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-05-sturdy.md#m-03-processyield-and-distributeyield-may-run-out-of-gas-and-revert-due-to-long-list-of-extra-rewardsyields

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-05-nftx.md#m-05-unbounded-iteration-in-nftxeligiblitymanagerdistribute-over-_feereceivers

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-05-visorfinance.md#h-04-unbounded-loop-in-_removenft-could-lead-to-a-griefingdos-attack

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-bootfinance.md#h-08-unable-to-claim-vesting-due-to-unbounded-timelock-loop

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-11-vader.md#m-01-unbounded-loop-in-twaporacleupdate-can-result-in-oracle-being-locked

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2021-12-yetifinance.md#m-04-out-of-gas

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-01-insure.md#m-08-unbounded-iteration-over-all-indexes-2

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-02-hubble.md#m-16-usdc-blacklisted-accounts-can-dos-the-withdrawal-system

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-02-hubble.md#m-04-settlefunding-will-exceed-block-gas-with-more-markets-and-activity

https://github.com/code-423n4/code423n4.com/blob/main/_data/reports/2022-02-hubble.md#h-02-denial-of-service

## ERC20 zero transfer

2022-02-aave-lens.md#m-09-collect-modules-can-fail-on-zero-amount-transfers-if-treasury-fee-is-set-to-zero

2022-02-concur.md#m-29-convexstakingwrapper-deposits-and-withdraws-will-frequently-be-disabled-if-a-token-that-doesnt-allow-zero-value-transfers-will-be-added-as-a-reward-one

2022-05-sturdy.md#m-04-convexcurvelpvaults-_transferyield-can-become-stuck-with-zero-reward-transfer 

2022-02-hubble.md#m-10-blocking-of-the-vusd-withdrawals-is-possible-if-the-reserve-token-doesnt-support-zero-value-transfers
