## Frequently Asked Questions (FAQ) for Setting Influenza Thresholds

### Q: How should I approach the consistency of these thresholds over time?

**A:** Typically, thresholds are kept consistent week-to-week for ease of monitoring and interpretation. This consistency ensures stability, predictability, and straightforward comparisons of disease activity across different timeframes. Moreover, with influenza seasons exhibiting substantial variations in their timing, fluctuating thresholds could lead to misinterpretations. A constant benchmark aids healthcare professionals and the public in gauging the severity of a season and anticipating future trends, making it crucial to maintain relative stability in thresholds while also periodically revisiting them for updates.

---

### Q: What can I do if I only have 2 years of data?

**A:** When faced with just 2 years of data, the depth for robust trend analysis is understandably limited. In such scenarios, it's prudent to rely on expert consensus. Convene a panel of experts, like epidemiologists and healthcare professionals familiar with influenza in the region. Present any observed patterns from the 2-year span to this panel, then collaboratively establish provisional thresholds, bearing in mind their tentative nature. As more data becomes available in the future, these thresholds should be revisited and refined, potentially with further expert input. Additionally, collaborating with regions having similar characteristics but longer data histories can offer valuable context.

---

### Q: How should I deal with data gaps?

Addressing data gaps depends on their position in the dataset and their nature:

- **Beginning of Data:** 
  - **Historical Data:** Source older records or data from similar regions to fill the early gaps.
  - **Expert Opinion:** Utilize consensus from local experts familiar with early influenza trends.
   
- **Middle of Data:** 
  - **Imputation:** Techniques such as linear interpolation or more sophisticated statistical methods can fill in missing data points based on surrounding data. However, be cautious of imputing large gaps, as it can introduce biases.
  - **External Data:** Check for alternative sources of data or similar populations/regions that might offer a comparative period.

- **End of Data:** 
  - **Forecasting:** Utilize epidemiological models or statistical forecasting based on past trends.
  - **Contemporary Data:** Source real-time or near-real-time data from healthcare facilities or labs for the latest trends.

- **General Approaches for All Gaps:**
  - **Substitute Data Sources:** Sometimes, alternative datasets, like hospital admissions or lab results, can fill in or validate gaps.
  - **Acknowledgment:** In some instances, if gaps can't be filled convincingly, it might be best to acknowledge them transparently, ensuring that interpretations and decisions are made with the known limitations in mind.
 
---


### Q: How many years of data do I need if I have multiple peaks in a year?

**A:** When dealing with multiple peaks within a single year, the complexity of the data increases. It's recommended to have between 5-10 years of data to adequately characterize and understand these peaks in the context of influenza trends. This duration allows for capturing variations and anomalies, ensuring that the thresholds and models developed can accommodate the intricacies introduced by these multiple peaks.

---

### Q: I need advice on dealing with the tropics. Are there solutions or just problems?

**A:** The tropics pose unique challenges for influenza surveillance due to the distinct nature of its transmission dynamics:

- **Multiple Peaks:** Tropical regions sometimes exhibit more than two peaks in a single season. While the Moving Epidemic Method (MEM) and Average Curve Method (ACM) can effectively handle up to two peaks, they may not be suitable for seasons with more than two. For such scenarios:
  - **Percentile Method:** This method can be advantageous as it doesn't rely on predefined seasonality, making it adaptable to the varying peak occurrences in the tropics.
  - **Expert Consensus:** In the absence of a clear analytical solution, gathering expert opinion and reaching a consensus can help set meaningful thresholds tailored to the region's unique challenges.

- **Undefined Seasons:** The lack of a clear influenza season in some tropical regions can be addressed by:
  - **Segment Data:** Divide data into logical chunks (e.g., monthly or quarterly) to enable more manageable analysis and threshold setting.
  - **Leverage Local Knowledge:** Engage with local epidemiologists and health professionals to gain insights into disease circulation and inform threshold decisions.

In conclusion, while tropical regions introduce complexities in influenza surveillance, a combination of analytical techniques and expert collaboration can help navigate these challenges.

---

### Q: How many years of historical data are needed for percentiles?

**A:** Determining the ideal amount of historical data for calculating percentiles is intricate and hinges on several factors:

- **Variability of the Disease:** For disease with high year-to-year variability, more years of data will provide a more robust percentile estimate.

- **Data Quality:** If the historical data is of high quality and consistency, fewer years might suffice. Conversely, data with inconsistencies or gaps might necessitate a longer historical dataset to derive reliable percentiles.

- **Purpose of Analysis:** For short-term or preliminary insights, a smaller dataset could be acceptable. However, for comprehensive epidemiological studies or public health interventions, a longer dataset is advisable.

In general, a minimum of 3-5 years of consistent, high-quality data is often recommended to calculate meaningful percentiles for influenza trends. Yet, the more years you can incorporate, the more reliable and representative your percentiles will be.


---
### Q: How often should thresholds be reviewed and potentially recalibrated?

**A:** Regular review of thresholds is crucial to maintain their relevance and accuracy. Ideally, thresholds should be revisited **annually**. This annual review allows for the integration of data from the most recent influenza season, helping to ensure that the thresholds are up-to-date and reflective of any new epidemiological trends. Additionally, as data quality or surveillance methodologies evolve, an annual recalibration ensures that the thresholds remain robust and fit-for-purpose. Keeping thresholds current is vital for effective public health response and preparedness.

---

### Q: Are there specific tools or software recommended for threshold setting?

**A:** Absolutely, there are specialized tools and software developed for threshold setting in influenza surveillance:

- **For the Moving Epidemic Method (MEM):**
  - While you can calculate thresholds manually following the MEM algorithm, there's a dedicated **[MEM package for R](https://cran.r-project.org/web/packages/mem/index.html)** available for those familiar with the R programming language. This package offers increased flexibility, allowing users to choose various options such as type of confidence interval for threshold calculation, type of confidence interval for determining length, start, and percentages, as well as the number of bootstrap iterations. The package also aids in generating different types of graphs.
  - For those who may not be familiar with R, there's a user-friendly **[web-based application](http://memapp.iecscyl.com:8080/)** that can be utilized.

- **For the Average Curve Method (ACM):**
  - Just as with the MEM, you can manually calculate thresholds following the ACM steps. However, for ease and convenience, there's a **[web-based application](https://worldhealthorg.shinyapps.io/averagecurves/)** available. This tool is designed for users without the requirement of R knowledge.
 
  
These tools greatly streamline the threshold setting process, making it more accessible to both experts and those new to the field.


---

### Q: Can we apply the same threshold settings across different diseases or conditions?

**A:** Each disease or condition has unique epidemiology, and it's generally not advisable to directly apply the same thresholds across them. However, the methodology or approach might be similar, but specific values or parameters should be tailored to each disease's characteristics.

---

### Q: How do we handle unexpected outliers or anomalies in the data when setting thresholds?

**A:** Outliers or anomalies can significantly influence threshold calculations, potentially leading to misleading results. Here's a suggested approach:

1. **Identification:** Before setting thresholds, always visualize and statistically analyze your data to identify any apparent outliers or anomalies.
 
2. **Verification:** Once identified, verify these anomalies. Are they genuine reflections of disease activity or perhaps results of data errors, changes in reporting, or other non-epidemiological factors?

3. **Decision on Inclusion/Exclusion:** Based on the verification:
   - If an outlier is genuine, it should be included in the analysis as it reflects true disease variability.
   - If it's a result of an error or non-epidemiological factor, consider excluding it to ensure robust threshold setting.

4. **Sensitivity Analysis:** After making decisions on outliers, it's prudent to conduct a sensitivity analysis. This can help understand the impact of those outliers on your threshold calculations.

5. **Documentation:** Always document the decisions made regarding outliers and anomalies, providing justifications. This ensures transparency and reproducibility of your threshold-setting process.

By meticulously handling outliers, you can ensure that the thresholds are representative of genuine disease activity and not unduly influenced by anomalous data points.


---

### Q: How should we adjust thresholds in light of significant public health interventions (like vaccinations)?

**A:** Public health interventions, especially widespread measures like vaccinations, can have a profound impact on disease transmission and incidence. When such interventions are introduced, they can shift the epidemiological landscape, necessitating an adjustment in thresholds. Here's a structured approach to this adjustment:

1. **Data Monitoring:** Post-intervention, closely monitor disease incidence and trends. Significant interventions might alter the baseline level of disease activity or change the seasonality patterns.

2. **Comparison with Historical Data:** Compare post-intervention data with historical trends. Recognize any deviations that may be attributed to the interventions.

3. **Modeling Interventions:** Use epidemiological models to simulate the expected impact of the intervention. This can help in predicting changes and adjusting thresholds accordingly.

4. **Temporary Adjustment:** Initially, make temporary adjustments to the thresholds, understanding that the full impact of interventions (especially vaccinations) might take time to manifest completely.

5. **Continuous Review:** As more post-intervention data becomes available, continuously review and recalibrate the thresholds. This iterative process ensures that the thresholds remain relevant and reflective of the current epidemiological context.

6. **Stakeholder Engagement:** Engage with healthcare providers, public health professionals, and the community. Their insights and on-the-ground observations can be invaluable in understanding the real-world effects of interventions and making informed adjustments.

7. **Documentation:** Always document the changes made, the rationale behind them, and the data supporting those decisions. This ensures transparency, allows for feedback, and provides a basis for future evaluations.

Remember, the goal is to ensure that thresholds remain a meaningful tool for public health decision-making, even as interventions shift the disease dynamics.

---

### Q: How do external factors, like weather patterns or public events, impact threshold settings?

**A:** External factors can play a significant role in the transmission and incidence of diseases, and therefore, they may influence the setting and interpretation of thresholds. Here's how some of these factors impact:

1. **Weather Patterns:** Climate and weather, including temperature, humidity, and precipitation, can affect the transmission dynamics of certain diseases. For instance, influenza transmission might be higher during colder, dryer months. In such cases, thresholds may need to be adjusted seasonally to account for these predictable changes.

2. **Public Events:** Large gatherings, festivals, or public events can lead to spikes in disease incidence due to increased human-to-human contact. If such events are regular and predictable (e.g., annual festivals), it might be worth considering separate thresholds or at least contextualizing data during these periods.

3. **Migration Patterns:** Movement of populations, whether due to seasonal work, migration, or tourism, can introduce new cases into an area or change local disease dynamics. This can lead to transient changes in disease incidence, influencing threshold settings.

4. **Behavioral Changes:** Public awareness campaigns, school holidays, or cultural practices can influence behavior and, subsequently, disease transmission. For example, hand hygiene campaigns might temporarily reduce disease incidence.

5. **Infrastructure and Environmental Changes:** Factors like urbanization, construction projects, or deforestation can influence disease vectors and transmission patterns. They might necessitate longer-term adjustments in thresholds.

6. **Interconnectedness:** In today's globalized world, an outbreak in one region can quickly influence another due to travel and trade. Being aware of global disease trends can help in understanding sudden changes in local thresholds.

When setting or reviewing thresholds, it's essential to be aware of these external factors and consider how they might impact the data. Analyzing disease trends in the context of these factors will provide a more accurate and actionable understanding of the current situation.


---
### Q: Should thresholds be adjusted for population size or density?

**A:** Yes, population size and density can significantly influence the transmission dynamics of diseases and, therefore, the setting of thresholds. Here's a breakdown of why and how:

1. **Population Size:** The absolute number of cases in a large population might be higher than in a smaller population, even if the rate of transmission or the proportion of affected individuals is the same. Therefore, when considering thresholds, it's often more informative to look at incidence rates (e.g., cases per 100,000 individuals) rather than absolute numbers. This provides a standardized measure that is comparable across regions with different population sizes.

2. **Population Density:** Areas with higher population density might experience more rapid disease spread due to closer human-to-human contact. Diseases that spread via respiratory droplets, for instance, might see quicker transmission in densely populated urban areas compared to rural areas. In such cases, thresholds might need to be set differently for regions based on their population density.

3. **Heterogeneity in Population Density:** In many regions, population density isn't uniform. Urban centers might be very densely populated, while surrounding areas are sparser. In such cases, a single threshold might not be adequate, and separate thresholds might need to be established for different parts of the region.

4. **Mobility Patterns:** Areas with high population density often have a higher volume of people moving in and out, due to work, tourism, or other reasons. This increased mobility can also influence disease transmission dynamics. While this is more about mobility than density per se, the two often go hand in hand.

5. **Healthcare Infrastructure:** Densely populated areas often have more healthcare facilities, but they might also experience a higher strain on these facilities during outbreaks. Understanding the balance between population density and healthcare capacity can also inform threshold settings.

In summary, when setting or adjusting thresholds, it's crucial to consider both the size and density of the population. These factors can influence not just the raw numbers but also the speed and pattern of disease spread.


---

### Q: How do we manage thresholds for new or emerging diseases with limited historical data?

**A:** Setting thresholds for new or emerging diseases with scarce historical data presents a unique challenge. Here's a structured approach to address this:

1. **Expert Consensus:** Initially, rely on expert consensus. Assemble a team of epidemiologists, clinicians, and other relevant experts to provide insights based on the limited data available and their knowledge of similar diseases.

2. **Use of Proxies:** If the emerging disease is similar to known diseases, historical data from those diseases can serve as a proxy, though this should be approached with caution.

3. **Real-Time Data Analysis:** As the disease progresses, continuously collect and analyze real-time data. The initial phases of the outbreak can provide valuable insights for setting preliminary thresholds.

4. **Dynamic Adjustments:** Recognize that the initial thresholds might need frequent adjustments as more data becomes available. Be prepared for an iterative process.

5. **International Collaboration:** Share data and insights with international partners. Pooling data from multiple sources can provide a broader perspective and compensate for limited local data.

6. **Modeling and Simulation:** Utilize computational models to simulate disease spread and test various thresholds. While models are only as good as the data fed into them, they can provide hypothetical scenarios that aid in decision-making.

7. **Public Communication:** It's essential to communicate the uncertainty and potential changes in thresholds to the public and stakeholders. Being transparent about the challenges and the iterative nature of the process can help manage expectations.

8. **Regular Review:** As the disease becomes better understood and more data is accumulated, the thresholds should be reviewed regularly and adjusted as needed.

In summary, while limited historical data complicates threshold setting for new diseases, a combination of expert input, real-time analysis, modeling, and international collaboration can guide the process until more robust data is available.


---

### Q: Should public perception or media attention influence threshold adjustments?

**A:** Public perception and media attention play a significant role in shaping the public's response to health events. However, when it comes to the scientific process of setting thresholds, the primary considerations should be evidence-based and rooted in epidemiological data. Here's a structured perspective:

1. **Data-Driven Approach:** Thresholds should fundamentally be based on epidemiological data, scientific research, and expert consensus. Making adjustments based purely on public perception or media attention could compromise the scientific integrity and effectiveness of threshold-based interventions.

2. **Understanding Public Concern:** While the media and public sentiment shouldn't dictate threshold adjustments, it's crucial to understand and acknowledge their concerns. This can provide context, especially in situations where there might be under-reporting or when public perception points to anomalies in the data.

3. **Transparent Communication:** Addressing public and media concerns with transparent, clear, and timely communication can alleviate misconceptions. It's essential to explain the basis for thresholds and any subsequent adjustments to maintain trust.

4. **Educational Outreach:** Use public concern and media attention as an opportunity to educate the public about how thresholds are set and why they are essential. Informative campaigns can dispel myths and provide clarity.

5. **Review Process:** While direct adjustments in response to media or public sentiment aren't advisable, these external pressures can be a cue for health authorities to review the thresholds to ensure they are still fit for purpose.

6. **Stakeholder Engagement:** Engaging with key stakeholders, including media, can foster a better understanding of the threshold setting process and ensure that the media's portrayal of health events is accurate.

In summary, while thresholds should remain primarily data-driven, it's vital to address public perception and media attention through communication and education without compromising the scientific basis of the thresholds.

---

### Q: Can existing methods be adapted to context or otherwise?

**A:** Absolutely, existing methods can be modified and adjusted based on the context and specific needs of a region or country. The main aim is to ensure that thresholds are both scientifically sound and relevant to the local epidemiological situation. Here's a breakdown:

1. **Understanding Contextual Needs:** The key to adapting existing methods is understanding the unique epidemiological and healthcare context of a region or country. For instance, regions with multiple peaks in a year, or those with variable disease activity, might need different approaches to threshold setting.

2. **Case Studies:** Countries like the US and South Africa have adapted the MEM (Moving Epidemic Method) to better suit their needs. Instead of using confidence intervals, they've incorporated percentiles, which can offer a more robust approach in certain contexts.

3. **Consider Data Quality:** The type and quality of data available can also influence method adaptations. If data is sparse or has gaps, certain methods might need adjustments or the incorporation of imputation techniques.

4. **Collaborative Efforts:** Collaborating with local experts, epidemiologists, and health officials can provide insights into how best to adapt methods. They can provide on-the-ground perspectives that can guide adjustments.

5. **Continuous Review:** Any adapted method should undergo regular review to ensure it remains effective and relevant. As epidemiological patterns change, or as more data becomes available, further refinements might be necessary.

6. **Educational Resources and Training:** As methods are adapted, it's essential to provide adequate training and resources to health officials and practitioners on how to use and interpret these adapted methods.

In conclusion, while there are established methods for threshold setting, they are not set in stone and can (and should) be adapted to suit specific regional and local contexts, ensuring that they remain effective tools for public health monitoring and response.

---

### Q: What are the pros and cons of excluding COVID-19 pandemic era data in influenza thresholds settings?

**A:** The COVID-19 pandemic had significant impacts on global health systems, public behaviors, and the circulation of other respiratory viruses, including influenza. The pros and cons of excluding this era data from influenza threshold settings are:

**Pros:**
1. **Reduced Noise:** The widespread adoption of preventive measures like mask-wearing, hand hygiene, and social distancing during the COVID-19 pandemic led to unusual reductions in influenza circulation. Excluding this period can reduce noise and outliers in the dataset.
   
2. **Avoid Skewed Thresholds:** The atypical influenza activity during the pandemic could result in thresholds that are either too lenient or too strict if included.

3. **Reflective of Regular Conditions:** Removing the pandemic era can make data more reflective of "regular" or non-pandemic conditions, which may be more helpful for setting accurate thresholds in the future.

4. **Less Confounding:** Many factors during the COVID-19 pandemic, like increased testing for respiratory illnesses or misclassification of cases, could confound influenza data. Exclusion minimizes this impact.

**Cons:**
1. **Loss of Data:** Excluding any period results in a loss of data, which could be valuable, especially for countries or regions with limited historical data.

2. **Unpredictable Future Scenarios:** Pandemics and global health crises are not predictable. Excluding the COVID-19 era might make the thresholds less adaptable to other unforeseen events in the future.

3. **Understanding Co-Circulation:** If both COVID-19 and influenza are circulating simultaneously, understanding their interplay might be crucial. Excluding this data might lead to missed insights about potential synergies or interferences.

4. **Neglecting Behavior Shifts:** The pandemic led to long-term changes in public behavior, like increased remote working or permanent adoption of some preventive measures. Excluding this era might not account for these lasting changes, which could impact influenza trends.

--- 



