# Buy Now, Pay Later Project 13
- Student name: Hoang Long Le; Student ID: 1189672
- Student name: Elmer Chen; Student ID: 1356250
- Student name: Anhphi Nguyen; Student ID: 1356159
- Student name:  Ashwin Prakash; Student ID: 1350294
- Student name:  Chengming Liew; Student ID: 1266882

** Research goal:** Ranking merchants and picking which merchants to go onboard

Before running any files, ensure you have downloaded the following external datasets and placed the `SA2_ERP.csv` and `SA2_Income.csv` files under the data/external_data directory:
1. SA2 population data (`SA2_ERP.csv`): https://explore.data.abs.gov.au/vis?fs[0]=People%2C1%7CPopulation%23POPULATION%23%7CEstimated%20Resident%20Population%23ERP%23&pg=10&fc=People&df[ds]=PEOPLE_TOPICS&df[id]=ERP_COMP_SA_ASGS2021&df[ag]=ABS&df[vs]=1.0.0&pd=2022%2C&dq=10.SA2..A&vw=tb&lb=bt
2. SA2 income data (`SA2_Income.csv`): https://digital.atlas.gov.au/datasets/digitalatlas::abs-income-including-government-allowances-by-2021-sa2-nov-2023/explore?filters=eyJpbmNvbWVfMTgyMDIwIjpbMC4xLDIyNDRdLCJpbmNvbWVfMzYyMDIwIjpbMTM2MTEsMzc4NTg4XSwiaW5jb21lXzQxMjAyMCI6WzAuMzE4LDMuMTQzXX0%3D&showTable=true

To run the pipeline, please visit the `notebooks` directory and run the files in order:
1. 1.0_merge.ipynb 
2. 1.1_external_data.ipynb 
3. 2_outlier_analysis.ipynb 
4. 3.0_tags_cleaning.ipynb 
5. 3.1_grouped.ipynb 
6. 4.1_revenue_model.ipynb 
7. 4.2_customer_count_model.ipynb
8. 4.3_new_unique_customer_model.ipynb
9. 5_ranking.ipynb

There are two optional notebooks that we tried to implement more on but did not have the time to do so. These are:
1. 6.0_(extra)num_transactions_model.ipynb
2. 6.1_(extra)visualisation.ipynb