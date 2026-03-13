# Catalog Valuation and Contract Analysis Project for Music Royalties
An excel sheet that compares contract terms and royalty projections.

## Executive Summary:
---
Using historical royalty data and given contract terms, I estimated a valuation of a music catalog under multiple conditions and calculated the costs of the contract that affect an artist. Using this information, an artist can negotiate contracts with more confidence and secure higher offers. This sheet allows the artist to:  
1. Determine their catalog's growth and worth  
2. Understand payment structure of the contract  
3. Calculate investor's rate of return and actual total received  

### Business Problem:  
An artist wants to get a loan or "advance" from a Record Label or a Securitization Company. Investor's will create a contract that allows for control of the rights to a music catalog. This will allow the investor to collect on any royalties the songs generate. In return, an investor will give a large lump sum to the artist with a predetermined repayment structure.  

<img src="Assets/Music Royalties contract flowchart.png" alt="Music Royalty Contract Flowchart" width="500" height="500">

**Questions**: How can we determine the "fairness" of lump sum amount? Is the investor paying what the catalog is actually valued at? What would the repayment structure look like with different terms?

### Methodology:
1. Import and merge Royalty Statement sheets for the year
2. Create a table using conditional formulas that contain the sum amount earned for each month
3. Forecast earnings using monthly earnings and quarterly averrage earnings
4. Create a table to allow users to input their contract terms
5. Calculate actual payment structure using proposed repayment terms and projected data.

### Skills:
1. Formulas: SUMIF, VLOOKUP, INDEX, MATCH, FORECAST.ETS, FORECAST.LINEAR
2. Concepts: Annuities, Effective Interest Rates, Seasonal Trends

### Results:
This excel sheet provides an artist the full picture of the offer at hand. With the contract terms entered, they can see how long it will take to pay off the advance and how much, in excess, would be paid out to the investor. In addition, by providing a calculation of the interest rate, an artist can compare the advance to a bank loan. This analysis also provides the artist with a rough valuation of their catalog to compare with the advance offer to make the most informed decision.

