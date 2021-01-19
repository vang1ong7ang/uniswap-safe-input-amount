# uniswap safe input amount

uniswap safe input amount is showed [here](safe.ipynb) to anti front running.

essentially the safe input amount is `0.30135474%` of *amount of input token in the pool* because of the *transaction fee* is `0.3%`.

thus, the `0.3%` *transaction fee* in uniswap provide benefits not only for the liquidity providers but also for the traders.

according to the expression show [here](safe.ipynb) the safe input amout is about *transaction fee* ✕ *amount of input token in the pool* when *transaction fee* is less than `1%`
