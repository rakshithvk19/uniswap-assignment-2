## ExactSwap.sol
1. In `getAmountIn()` in `UniswapV2Library.sol`, why are we adding 1 to the result of the division? What role does solidity play here?
2. What are the gas cost implications of performing swaps directly through the pair contract versus using the Uniswap router?
3. What are the differences in implementing exact input swaps versus exact output swaps in Uniswap V2?

## ExactSwapUsingRouter.sol
1. What is the purpose of the `swapTokensForExactTokens` function, and how does it differ from `swapExactTokensForTokens`?
2. How does the concept of slippage apply to the swapTokensForExactTokens function in UniswapV2?
3. What are the potential risks of setting amountInMax too high? How might this be exploited?

## MultiHop.sol
1. How does Uniswap V2's pricing mechanism work across multiple hops, and how does it ensure the best possible exchange rate?
2. How does the Uniswap V2 router handle slippage in multi-hop swaps, and what strategies can be employed to minimize its impact?
3. What are the limitations of multi-hop swaps in Uniswap V2, and how do they compare to more advanced DEX aggregators?

## SandwichSwap.sol
1. What role does slippage tolerance play in preventing sandwich attacks, and how can users protect themselves?
2. What on-chain and off-chain solutions are being developed to mitigate the risk of sandwich attacks in decentralized exchanges?
3. How do gas prices and network congestion affect the execution and profitability of sandwich attacks?

## SyncAndSkim.sol
1. What is token rebasing, and how does AMPL token manage its token supply and holder balances?
2. Explain how does UniswapV2's `skim()` work and provide and example of a situation when it might be invoked.
3. Explain how does UniswapV2's `sync()` work and provide and example of a situation when it might be invoked.
4. How might arbitrageurs take advantage of situations where `sync()` or `skim()` haven't been called?
