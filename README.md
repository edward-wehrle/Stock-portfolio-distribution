This project's goal was to select a portfolio of stocks and use statistical analysis to choose the optimal weights of the 
individual stocks in the portfolio.
The main metric used to evaluate performance was the Sharpe ratio, represented by this formula

{E(r) - rf} / st dev

E(r) is the expected return of the chosen portfolio, rf is the risk free rate available in the market, and st dev
is the standard deviation of the chosen portfolio. The Sharpe ratio is the amount of excess returns expected per unit of risk. We 
seek to maximize the expected returns and minimize the risk of the portfolio so as to maximize the Sharpe ratio. 


**Correlation Matrix**
The bulk of the file containing all the important calculations. First, a 10 X 10 symmetrical correlation matrix of the stocks was created
using the data analysis tool on Excel. Then a theoretical portfolio that organized returns and variance
was setup to make calculations straightforward. Using solver on Excel, the theoretical portfolio
can be adjusted to solve for the minimum possible variance, or to choose an ideal expected return and
minimize variance at that level.

The returns and standard deviations of a number of portfolios were plotted to form the expected frontier. This is the selection
of the best theoretical portfolios, which maximize returns at a given level of risk. The point on the expected frontier
that lies on the tangent line between the risk free rate and the frontier itself is the ideal portfolio makeup, where the
Sharpe ratio is maximized.

Next, using a theoretical risk free rate of 2.65%, solver was used to find a theoretical maximum Sharpe ratio of 1.17.
The expected return of the ideal portfolio makeup was 24.87% with a standard deviation of 18.92%. By combining specific weights
of the portfolio and risk free rate, any expected return can be chosen and the corresponding best portfolio will be clear.
For example, an E(r) of 10% is comprised of 33% weight in the risky portfolio and a 67% weight in the riskless asset,
which leads to a st dev of 6.26%.

