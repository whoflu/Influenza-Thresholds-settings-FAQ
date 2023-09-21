## Frequently Asked Questions (FAQ) for Influenza Thresholds Settings

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

**A:** This is a complex issue and depends on [factors/details]. While there isn't a one-size-fits-all answer, general guidelines suggest [your advice here].

---
### Q: How often should thresholds be reviewed and potentially recalibrated?

**A:** It's advisable to review thresholds annually. This allows for the incorporation of the most recent season's data and ensures that the thresholds remain relevant in light of new epidemiological trends or changes in data quality.

---

### Q: Are there specific tools or software recommended for threshold setting?

**A:** Several tools are available, but the right choice depends on the specific data and context. Software packages like R and Python have libraries that can assist with statistical analysis for threshold setting. For a more user-friendly experience, apps dedicated to epidemiological tracking, like FluView, could be explored.

---

### Q: Can we apply the same threshold settings across different diseases or conditions?

**A:** Each disease or condition has unique epidemiology, and it's generally not advisable to directly apply the same thresholds across them. However, the methodology or approach might be similar, but specific values or parameters should be tailored to each disease's characteristics.

---

### Q: How do we handle unexpected outliers or anomalies in the data when setting thresholds?

**A:** It's crucial first to investigate any outliers or anomalies to determine if they are genuine or a result of data errors. If they're genuine, they should be included in the analysis. But if they result from errors, they should be corrected or removed. Robust statistical methods can also be employed to minimize the impact of outliers on threshold settings.

---

### Q: How should we adjust thresholds in light of significant public health interventions (like vaccinations)?

**A:** Significant public health interventions can change the disease landscape. After such interventions, it's essential to monitor data closely and consider a recalibration of thresholds if there's a marked change in disease incidence or patterns.

---

### Q: How do external factors, like weather patterns or public events, impact threshold settings?

**A:** External factors can influence disease transmission and patterns. When setting thresholds, it's beneficial to consider seasonality and any known factors that might lead to unusual spikes in disease activity. Historical data can often provide insights into how such external factors have influenced past outbreaks.

---
### Q: Should thresholds be adjusted for population size or density?

**A:** Yes, population size and density can influence disease transmission. It's essential to normalize or adjust thresholds, especially when comparing different regions or cities with varying population sizes. Using rates (like cases per 100,000 population) can help in this adjustment.

---

### Q: How do we manage thresholds for new or emerging diseases with limited historical data?

**A:** For new or emerging diseases, the lack of historical data poses a challenge. Start by using shorter-term data, being prepared to adjust thresholds frequently as more data becomes available. Collaboration with other regions or countries to pool data can also be beneficial.

---

### Q: Are there differences in setting thresholds for acute versus chronic diseases?

**A:** Yes, acute diseases often have more pronounced fluctuations and seasonality, requiring dynamic thresholds to capture outbreaks. Chronic diseases might have steadier patterns, and thresholds could focus more on long-term trends rather than short-term spikes.

---

### Q: How can we incorporate lab-confirmed cases versus clinically diagnosed cases in thresholds?

**A:** It's advisable to differentiate between lab-confirmed and clinically diagnosed cases. Lab-confirmed cases provide a higher degree of certainty but might be underreported. Clinically diagnosed cases give a broader picture but might include misdiagnoses. Consider having separate thresholds or a weighted approach.

---

### Q: How do global travel patterns influence thresholds, especially for highly communicable diseases?

**A:** Global travel can introduce or amplify outbreaks. For diseases prone to international spread, consider monitoring travel data or alerts from major transit hubs. An unusual spike in cases from a travel origin might warrant a review of your thresholds.

---

### Q: Should public perception or media attention influence threshold adjustments?

**A:** While public perception and media attention are important for public health communication, they should not directly influence the scientific process of threshold setting. However, understanding public perception can help in communication strategies once a threshold is crossed.

---

### Q: How do we balance the need for sensitivity (detecting true outbreaks) versus specificity (avoiding false alarms) in threshold settings?

**A:** The balance depends on the disease's consequences and the cost of false alarms. For severe diseases, higher sensitivity might be favored at the risk of occasional false alarms. Regular reviews and adjustments can help fine-tune this balance over time.


### Q: Some countries, like the US and South Africa, adapt methods such as using percentiles instead of CI in MEM. Adjusting app settings can also help improve thresholds. [More advice/details here.]


**A:** Addressing data gaps is essential for accurate thresholds. Some countries, like the US and South Africa, adapt methods such as using percentiles instead of CI in MEM. Adjusting app settings can also help improve thresholds. [More advice/details here.]

---



