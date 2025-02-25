# Financial Numeracy and Inventory Efficiency: Examining Business Performance Through an Econometric Lens
Date: 3/12/2024


# Abstarct
This study explores the impact of financial numeracy on the efficiency and size of inventory holdings in businesses, focusing on how improved financial literacy influences inventory management practices. Using a cross-sectional dataset of 1,487 businesses, I estimate a regression model to assess the relationship between financial numeracy and inventory size while controlling for sector, business age, owner gender, previous business ownership, and additional business ownership.
The econometric model employs the natural logarithm of baseline inventory size as the dependent variable, allowing for a percentage-based interpretation of changes in inventory levels. The results reveal that financial numeracy has a significant negative effect on inventory size, indicating that higher levels of financial literacy among business owners lead to more efficient inventory management. Specifically, a one-unit increase in financial numeracy corresponds to a 64.7% increase in inventory size, reflecting better turnover rates and reduced holding costs. Sectoral variations further underscore the role of industry context, with the service sector demonstrating leaner inventory practices compared to goods and mixed sectors.
These findings highlight the importance of financial literacy as a key driver of operational efficiency in businesses. By improving their financial numeracy, business owners can optimize inventory levels, minimize costs, and enhance overall performance. The results have practical implications for policymakers and training organizations, emphasizing the need for targeted financial literacy programs to support business growth and efficiency.


**Keywords**: Financial Numeracy, Financial Literacy, Inventory Management, Business Efficiency, Operational Efficiency, Small and Medium Enterprises (SMEs), Sectoral Variations, Financial Decision-Making, Economic Order Quantity (EOQ)
Just-in-Time (JIT) Inventory, Serial Correlation


# Introduction

The efficient management of inventory is a critical factor in business success, as it directly affects operational costs, cash flow, and profitability. This study examines the impact of financial numeracy on the efficiency and size of inventory holdings in businesses. Financial numeracy, a subset of financial literacy, refers to the ability to understand and apply quantitative information in decision-making. My research aims to determine whether business owners with higher financial numeracy are better equipped to optimize inventory levels, reduce excess holdings, and improve turnover rates.

To build on this analysis, I extend the research question by incorporating additional business characteristics, such as sectoral variations, business age, owner gender, prior business ownership experience, and ownership of other businesses. These factors are expected to influence how financial numeracy affects inventory management, offering a more detailed understanding of the relationship between financial skills and operational efficiency.

## Scope of the Model

To address the research question, I developed an econometric model that examines the logarithm of baseline inventory size (ln(inventory_baseline)) as the dependent variable. This transformation allows for a percentage-based interpretation of changes in inventory size, making the findings more applicable to real-world scenarios. The independent variables in the model include:

    Financial Numeracy: A measure of the owner's financial literacy and skills.
    Sector: A categorical variable distinguishing between goods, services, and mixed-sector businesses.
    Business Age: The number of years the business has been in operation.
    Gender: A binary variable indicating the gender of the business owner.
    Previous Business Ownership: A binary variable capturing prior entrepreneurial experience.
    Other Business Ownership: A binary variable indicating whether the owner manages additional businesses.

## Hypotheses and Theories to Be Tested
This study is grounded in several key theories:

Human Capital Theory – Financial numeracy, as a form of human capital, equips business owners to make informed decisions about inventory management, leading to greater efficiency.
Inventory Management Theory – Concepts such as Economic Order Quantity (EOQ) and Just-in-Time (JIT) inventory control depend on financial literacy to minimize holding and ordering costs.
Behavioral Economics and Decision-Making – Financially literate individuals are better positioned to navigate bounded rationality and effectively manage inventory risks.


## Importance of the Study
This study addresses a critical gap in the literature by examining the role of financial numeracy in inventory management an area often overlooked despite its importance for business performance. Efficient inventory management is particularly crucial for small and medium-sized enterprises (SMEs), which operate under tighter resource constraints and are more vulnerable to inefficiencies. By analyzing the impact of financial numeracy, this research provides valuable insights that can benefit policymakers, training organizations, and business owners.

The findings have practical implications, highlighting the need for targeted financial literacy programs that can help business owners optimize inventory levels, reduce costs, and improve overall efficiency. On a larger scale, enhancing inventory management practices can strengthen supply chain resilience and contribute to economic growth. As a result, this study is highly relevant to both business practitioners and policymakers seeking to improve operational efficiency and long-term business sustainability.


# Literature Review

### Financial Literacy and Business Performance
Culebro-Martínez et al. (2024) examined the components of financial literacy—knowledge, behaviour, and attitude—among micro, small, and medium-sized entrepreneurs in Mexico. Their findings suggest that while financial knowledge and attitude did not significantly impact company performance, positive financial behaviour played a crucial role in business success. This highlights the importance of applying financial management skills in real-world business operations to enhance performance.

### Financial Literacy and Financial Well-being
Lusardi and Messy (2023) explored the role of financial literacy in improving financial well-being. Their study found that higher financial literacy levels contribute to better financial decision-making, increased use of financial instruments, and improved financial resilience. These factors collectively enhance business success by enabling entrepreneurs to manage risks more effectively and make informed investment choices.

### Financial Literacy in SMEs
Molina-García et al. (2022) conducted a bibliometric analysis and systematic literature review on financial literacy in small and medium-sized enterprises (SMEs). Their research highlights that financial literacy has a positive impact on business performance, access to finance, innovation, and risk management. The study underscores the multifaceted role of financial literacy in shaping the strategic and operational decisions of SMEs, reinforcing its significance for long-term business sustainability.

These studies collectively emphasize the importance of financial literacy in business success, supporting the premise that financial numeracy can significantly influence inventory management efficiency.


# Model Specification 

Ln_inventory_baseline = β0 + β1⋅financial_numeracy_baseline + β2⋅sector + β3⋅agebiz + β4⋅gender + β5⋅previous_business_owner + β6⋅other_biz + ϵ

The above model aims to analyze the effect of financial numeracy on the efficiency and size of inventory holdings in businesses. The model's dependent variable is the natural logarithm of the number of days of baseline inventory needed to sustain the business operation, and the independent variables include financial numeracy, sector, business age, gender, prior business ownership, and the ownership of additional businesses.

## Dependent Variable

### Log of days of inventory available at baseline (ln_inventory_baseline) 
Represents the natural logarithm of the number of days a business's inventory can sustain operations at its current sales levels. The logarithmic transformation allows interpretation of the coefficients in percentage terms and captures relationships between predictors and inventory size. It also reduces heteroscedasticity.

## Independent Variables

### Financial Numeracy Baseline (financial_numeracy_baseline)
Measures the financial literacy and skills of the business owner. Higher financial numeracy is expected to improve inventory efficiency, leading to optimized inventory size. The expected sign is negative indicating that higher financial numeracy is expected to improve inventory efficiency, resulting in shorter inventory durations. 

### Sector
Categorical variable indicating the business type. Different sectors have varying inventory requirements due to product perishability, demand variability, or production cycles. The expected sign for service businesses is likely negative as they typically require minimal or no inventory, resulting in significantly fewer inventory days.

### Business Age
Represents the number of years the business has been in operation. Older businesses likely have more experience and better inventory management practices. The expected sign is negative as older businesses may streamline inventory management, resulting in fewer days of inventory being held.

### Gender
Binary indicator of the owner's gender (male = 1, female = 0). Gender may influence inventory practices due to differing access to resources. An expected sign is positive for male owners as gender may influence inventory practices due to greater access to resources for males as evidenced in the study. 

### Previous Business Owner
Binary indicator of whether the owner has prior business experience (1 = yes, 0 = no). Prior experience may lead to better inventory management practices. A negative expected sign reflects greater efficiency due to experience.

### Ownership of Other Businesses (other_biz):
Binary indicator of whether the owner operates additional businesses (1 = yes, 0 = no). Spreading resources across multiple businesses may limit the size of a single business' inventory. The sign is expected to be negative due to the allocation of resources among businesses, resulting in fewer inventory days for each business.

### Inclusion of Relevant Variables
Financial numeracy is the primary independent variable of interest, as it directly measures the financial skills and literacy of the business owner and is hypothesized to significantly influence inventory efficiency. Control variables such as sector, business age, gender, previous ownership, and ownership of other businesses are included to account for alternative factors that could impact inventory size and efficiency. However, some potentially relevant variables, such as market competition or broader economic conditions, are not included due to data limitations, and factors like owner education or managerial style might also play a role but are not captured in the model.

## Assumptions in the Model

### Linearity
The relationship between predictors and the dependent variable is assumed to be linear. This ensures the coefficients represent the average change in the dependent variable for a one-unit change in each predictor, holding others constant.

### Independence
Observations are assumed to be independent, meaning one business's inventory decisions do not directly influence another's.

### Homoscedasticity
The residuals are assumed to have constant variance across all levels of the predictors. Heteroscedasticity leads to inefficient estimates and unreliable standard errors, potentially invalidating hypothesis tests.

### No Multicollinearity
Predictors should not be highly correlated, as multicollinearity inflates standard errors and destabilizes coefficient estimates. This makes it hard to assess the independent effect of each variable.

### Normality of Residuals
Residuals are assumed to follow a normal distribution, ensuring valid p-values and confidence intervals for hypothesis testing. Non-normal residuals, often caused by outliers or misspecification, can distort results. 

## Data Description:

### Data Sources
The data was sourced from surveys conducted during a randomized controlled trial targeting micro and small business owners in developing economies. Surveys were administered in person, and responses were recorded electronically to minimize data entry errors.

### Data Refinements
Log Transformation: Days of inventory available at Baseline were log-transformed to address skewness and ensure a linear relationship with predictors.
Handling Missing Values: Missing data for financial numeracy or inventory size were excluded from the analysis to maintain consistency across observations.
Categorization: The sector variable was refined into categories of retail and services to improve interpretability.

### Potential Biases and Weaknesses
Self-Reporting Bias: Variables such as financial numeracy and inventory are based on self-reported data, which may be affected by inaccuracies due to recall errors or intentional misreporting. This can introduce measurement errors that may weaken the reliability of the findings.

Selection Bias: The dataset may disproportionately represent business owners who voluntarily participated in financial training programs, as these individuals might already exhibit higher motivation or skills. This selection bias could limit the generalizability of results to a broader population of business owners.

Unobserved Confounders: Key factors such as the owner's educational background, managerial style, or prevailing market conditions are not included in the dataset. These omitted variables could bias the estimated effects of financial numeracy on inventory size if they are correlated with both the dependent and independent variables.

## Descriptive Statistics 

![image](https://github.com/user-attachments/assets/ecb926be-e6ce-4c11-b076-d29f70d17f88)


The descriptive statistics highlight key characteristics of the variables in the regression model. The log-transformed inventory baseline (`ln_inventory_baseline`) has a mean of 2.36, indicating moderate inventory levels, with a standard deviation of 1.02 and values ranging from 0.00 to 5.48. The financial numeracy baseline (`financial_numeracy_baseline`) shows a high average score of 0.85 with low variability (SD = 0.19) and a range between 0.00 and 1.00, reflecting strong financial literacy among participants. Business age (`agebiz`) has a mean of 119.23 and a high standard deviation of 106.86, with a range from 0.00 to 715.00, indicating substantial diversity in the age of businesses, from newly established to older enterprises. These findings reveal a sample with generally high financial numeracy, moderate inventory levels, and a wide range of business ages.

## Correlation Table

![image](https://github.com/user-attachments/assets/bdcc61e3-5394-4a52-8a7f-1bee759a4327)

The correlation matrix reveals weak relationships among the variables, with all correlation coefficients close to zero. The strongest correlation is between ln_inventory_baseline and financial_numeracy_baseline (0.1134), suggesting a slight positive relationship where higher financial numeracy is associated with a higher inventory baseline. Other variables, such as agebiz (age of business), previous business owner, and whether a person has another business, show negligible correlations with both inventory baseline and each other, indicating minimal linear relationships. These findings suggest that the variables are relatively independent and suitable for regression modelling without concerns of strong linear dependence.


# Results

The adjusted R² is 0.1323, indicating that approximately 13.64% of the variation in the dependent variable is explained by the independent variables in the model, there remains a significant portion of unexplained variance. The F-statistic for the model is 33.38, with a p-value less than 0.01, indicating that the overall model is statistically significant, at least one of the predictors has a meaningful relationship with the dependent variable.
Financial numeracy is highly significant at the 1% level (p<0.01) indicating a strong relationship with inventory levels. Sector (Goods and Services) and Sector (Services) are also significant at a 1% level suggesting that there is a variation in inventory practices across business sectors. The constant term is significant at the 1% level, providing a reliable baseline measure of inventory levels when all predictors are zero. In contrast, variables including establishment age and ownership of other businesses are not statistically significant, suggesting that they do not have a significant impact on inventory levels in this model. Gender is weakly significant at the 10 percent level, showing only marginal effects. These findings highlight that financial numeracy and sector are the most reliable predictors of inventory levels.


![image](https://github.com/user-attachments/assets/360f9530-c635-44cc-9600-1898f991f6f4)

### Serial Correlation
The Durbin-Watson test for serial correlation yielded a statistic of 1.7858, which is close to 2, indicating minimal autocorrelation in the residuals of the regression model. However, the very low p-value (1.629e-05) suggests that the observed autocorrelation, though weak, is statistically significant. This indicates a violation of the regression assumption that residuals are independent. While the degree of serial correlation appears minor, its statistical significance may affect the reliability of standard error estimates and hypothesis tests. 

### Heteroscedasticity
The Breusch-Pagan test for heteroskedasticity revealed a significant result (BP = 22.929, df = 7, p = 0.001754), indicating that the residuals of the regression model do not have constant variance. This suggests the presence of heteroskedasticity, meaning the variability of the residuals changes with the values of the predictors. This violation of the homoscedasticity assumption in Ordinary Least Squares (OLS) regression can lead to inefficient coefficient estimates and biased standard errors, which may affect the validity of hypothesis tests and confidence intervals. To address this, the model may require the application of robust standard errors or transformations of variables to stabilize the variance and improve reliability.

### Multicollinearity
The Variance Inflation Factor (VIF) analysis reveals no significant multicollinearity among the predictors in the regression model as shown in Appendix 3. All predictors, including financial numeracy baseline, sector, age of business, gender, previous business owner, and owner having another business, have VIF values well below the threshold of 5, with the highest Generalized Variance Inflation Factor (GVIF) adjusted being 1.0619 for gender. These results indicate that the predictors are not highly correlated, and the model's regression coefficients are reliable. The absence of multicollinearity ensures that standard errors are not inflated and hypothesis tests remain valid, requiring no corrective actions.

### Alternative Models and Specifications
From the image in Appendix 4, the regression shows the comparison between the initial regression model and the two additional models estimated to compare. The comparison of the three models based on AIC and BIC criteria shows that the initial estimated model performs the best, with the lowest AIC (4068.108) and BIC (4115.848), indicating the best balance between goodness-of-fit and model complexity. Alternative Model 1, which excludes previous business owners and other businesses, has slightly higher AIC (4073.204) and BIC (4110.341), suggesting a marginally poorer fit compared to the initial model. Alternative Model 2, which excludes age of business and gender, has the highest AIC (4109.352) and BIC (4146.554), demonstrating the worst performance among the three models. Overall, the initial model is the preferred choice as it achieves the best predictive accuracy and explanatory power while retaining all relevant predictors.


## Diagnostic Plots

![image](https://github.com/user-attachments/assets/10a44c23-8fbb-4cbf-88c2-cc95bc287341)

The diagnostic plots provide several insights into the regression model's assumptions. The residual vs. Fitted plot suggests potential heteroscedasticity, as the variance of residuals increases with fitted values. This issue is further confirmed by the Scale-Location plot, which displays a non-horizontal trend, indicating that variance is not constant across predicted values.
The Normal Q-Q plot suggests that the residuals are approximately normal, with minor deviations at the tails. However, these deviations are not critical for large sample sizes, where normality assumptions tend to hold due to the Central Limit Theorem. The residual vs. Leverage plot indicates that the model is not significantly influenced by outliers, as no observations exceed Cook’s distance threshold.
Overall, while the model is robust against influential outliers and generally satisfies the normality assumption, the presence of heteroscedasticity suggests that using robust standard errors or variable transformations may be necessary to stabilize the residual variance and improve the reliability of standard errors.

# Discussions

The results reveal that financial numeracy has a positive and significant effect on inventory size, contrary to the initial hypothesis that higher financial literacy would lead to reduced inventory levels. This suggests that financially numerate business owners may strategically maintain larger inventories to optimize opportunities, minimize stockouts, or manage supply chain risks more effectively. Sectoral differences play a crucial role, with businesses in the services sector holding significantly fewer inventory days than those in goods-related industries, reflecting lower inventory needs in service-based operations. Additionally, while gender exhibits a weakly significant effect—indicating that male-owned businesses tend to hold slightly more inventory—other variables such as business age and ownership of additional firms show no significant impact on inventory practices.

Despite the valuable insights gained, the study faces some limitations. The unexpected positive relationship between financial numeracy and inventory levels suggests potential omitted variable bias, as factors like supply chain infrastructure, business size, and market conditions were not included in the model. Additionally, the broad sector classifications may obscure variations within industries, and the binary gender variable does not account for cultural or structural constraints affecting business owners. Furthermore, key business characteristics such as access to credit, which could influence inventory management, were not captured in the dataset. These limitations highlight the need for more detailed sectoral classifications and additional variables in future research to refine the understanding of financial numeracy’s role in inventory management.

## Implications for Future Econometric Research

The findings highlight the importance of addressing unexpected results (i.e. the positive coefficient for financial numeracy) through more refined model specifications and additional data collection. Future econometric research could benefit from exploring gender dynamics in greater depth, particularly by examining how societal and cultural factors influence inventory practices. Additionally, using multi-level models could account for variation across sectors, regions, or industries. By addressing these limitations, future research could provide more actionable insights into the determinants of inventory practices, guiding practitioners in designing targeted interventions for improving business efficiency.


## Conclusion

This study highlights the significant impact of financial numeracy on inventory management efficiency, revealing that higher financial literacy is associated with a 64.7% increase in inventory size. Contrary to the initial hypothesis that greater financial numeracy would reduce inventory holdings, the findings suggest that financially literate business owners may strategically maintain larger inventories to capitalize on market opportunities, prevent stockouts, and mitigate supply chain risks. This challenges the conventional perspective that financial literacy primarily reduces costs, instead emphasizing its role in enabling strategic decision-making regarding inventory levels. Additionally, sectoral differences play a key role, with service-sector businesses maintaining leaner inventory levels than those in goods-related industries, reflecting distinct operational needs. While variables such as business age and previous business ownership show limited effects, gender and ownership of additional businesses exhibit minor yet noteworthy influences on inventory size.

The findings highlight the importance of financial numeracy as a component of human capital, allowing business owners to optimize inventory strategies and manage supply chain uncertainties more effectively. These insights highlight the need for targeted financial literacy training programs, particularly for businesses that rely heavily on inventory, to enhance operational efficiency and resilience. Policymakers and business training organizations should prioritize such interventions to strengthen SMEs' capacity, ultimately improving their profitability and adaptability in dynamic market environments. Future research should explore additional factors affecting inventory efficiencies, such as supply chain infrastructure and access to credit while assessing financial literacy's long-term impact on broader business performance metrics.


# APPENDIX

### Appendix 1: Correlation Matrix Table

![image](https://github.com/user-attachments/assets/36e37de0-5ba7-43ed-abdf-3ee67eee7674)

### Appendix 2: Descriptive Statistics Table

![image](https://github.com/user-attachments/assets/36bf6bee-a192-4534-a971-3bdeeea82716)

### Appendix 4: Regression Table for the 3 different model Comparison

![image](https://github.com/user-attachments/assets/f471ffa5-261c-47f0-ab29-035bd353c5be)

# References

Culebro-Martínez, R., Moreno-García, E., & Hernández-Mejía, S. (2024). Financial Literacy of Entrepreneurs and Companies’ Performance. Journal of Risk and Financial Management, 17(2), Article 2. https://doi.org/10.3390/jrfm17020063 

Lusardi, A., & Messy, F.-A. (2023). The importance of financial literacy and its impact on financial wellbeing. Journal of Financial Literacy and Wellbeing, 1(1), 1–11. https://doi.org/10.1017/flw.2023.8

Molina-García, A., Diéguez-Soto, J., Galache-Laza, M. T., & Campos-Valenzuela, M. (2023). Financial literacy in SMEs: A bibliometric analysis and a systematic literature review of an emerging research field. Review of Managerial Science, 17(3), 787–826. https://doi.org/10.1007/s11846-022-00556-2





