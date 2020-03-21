# Coin Change 

Given a value N, if we want to make change for N cents, and we have infinite supply of each of S = { S<sub>1</sub>, S<sub>2</sub>, ..., S<sub>m</sub>} valued coins, how many ways can we make the change? The order of coins doesn’t matter. 

For example, for N = 4 and S = { 1, 2, 3 }, there are four solutions: 
{ 1, 1, 1, 1 }, { 1, 1, 2}, { 2, 2 }, and { 1, 3 }. 
Therefore, output should be 4. 

For N = 10 and S = { 2, 5, 3, 6 }, there are five solutions: 
{ 2, 2, 2, 2, 2 }, {2, 2, 3, 3 }, { 2, 2, 6 }, {2, 3, 5 }, and { 5, 5 }. 
Therefore, the output should be 5. 
