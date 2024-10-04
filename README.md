<img width="650" alt="image" src="https://github.com/user-attachments/assets/2b9021b4-5a1a-4ad8-9872-30db8a0d161f">## Objectives:
1. Create a price weighted DJI index
2. Create an equal weighted DJI index
3. Create a value weighted DJI index
4. Compare performance between the three

Result: Value Weighted Index outperformed the rest! But this is before trading costs as value weighted indexes need to be rebalanced as their market cap changes every second!
<img width="835" alt="image" src="https://github.com/user-attachments/assets/335e8877-ccd7-4b97-96a9-44ad2c62e6cb">


## Method:
- For PWI, sum the price of shares accross the column, and divide the individual prices by the sum accross
- For Equal Weighted Index, the same weight applies accross
- For Value Weighted Index, we first get the market cap for the stocks and sum them accross the columns, then divide by the individual market caps for the weights

Take a look at the market cap distribution! (Huge amounts taken by MSFT and AAPL)

<img width="650" alt="image" src="https://github.com/user-attachments/assets/c3d36ead-2782-4611-a94e-60f32e21b42a">


Take a look at the price weighted distribution!

<img width="913" alt="image" src="https://github.com/user-attachments/assets/1aa38716-ee03-4bed-935e-8a4223dccae7">


## Key Learnings:
- All three Indexes benefit from the Portfolio Diversification Effect!
- Value Index outperformed the others significantly before trading costs
- PWI and EWI have performance close together (before Trading Costs)
- EWI and VWI requires daily rebalancing, with trading costs likely to eat up profits
