## Visualizing Predicitive Factors for Death in Long Term Care Facilities in COVID19

I chose to use Ontario's public data on COVID19 outbreaks in long term care facilities to see if facility factors predicted death outcome. My data is from various public ontario records that can be found [with the rest of my code](https://github.com/raywoo32/BioHacks2021). 

I used linear model and found 5 predictors of mortality through a step-wise regression model. My results were significant, with R-squared of 0.13 and a p-value < 0.005. While this may not seem like a lot of predictive power, I would argue that 13% is worth investigating given that the context is predicted mortality in a pandemic. My significant variables are: 

1. Number of Beds/Residents
2. Number of Non-compliance issues found in targeted inspections
3. Number of Councils for Resident Advocacy (resident and family councils) 
5. Non-Profit Status
6. For-Profit Status

### Interpreting the results 

### Methodology

My methods were mainly data cleaning and web-scraping to integrate different data sources. I did the following

1. Webscrape government website to get data on complicance in inspections 
2. Webscrape government website to get data on profit status
3. Integrate and clean data (only 29 out of 514 long term care homes were excluded due to missing data) 
4. Create linear model 


[Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/raywoo32/biohacks2021.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
