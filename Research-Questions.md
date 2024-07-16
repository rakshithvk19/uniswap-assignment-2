## ExactSwap.sol
1. In `getAmountIn()` in `UniswapV2Library.sol`, why are we adding 1 to the result of the division? What role does solidity play here?
2. What are the gas cost implications of performing swaps directly through the pair contract versus using the Uniswap router?
3. What are the differences in implementing exact input swaps versus exact output swaps in Uniswap V2?

## ExactSwapUsingRouter.sol
1. What is the purpose of the `swapTokensForExactTokens` function, and how does it differ from `swapExactTokensForTokens`?
2. How does the concept of slippage apply to the swapTokensForExactTokens function in UniswapV2?
3. What are the potential risks of setting amountInMax too high? How might this be exploited?