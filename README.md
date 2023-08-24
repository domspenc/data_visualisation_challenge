<h1>Pymaceuticals Challenge</h1>
<img
        src="https://spectrumnews-web-assets.s3.amazonaws.com/wp-content/uploads/2020/01/22152014/20201214-Pogz-844.jpg"
        alt="Lab Mice"
        width="650"
      />
</br>
<h3><u>Description</u></h3>
<p>
This repository showcases a python pandas analysis of a study done at Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. This study focuses on a group of mice who were identified with squamous cell carcinoma (SCC) tumors, and received treatment using a range of drug regimens. Over the course of 45 days, tumour development was observed and measured. This study's purpose was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.</p>
</br>
<h3><u>Initial Observations</u></h3>
</br>
<p>- The study sample comprised of 248 mice, (249 including duplicates in the data).</p> 
</br>
<p>- The sample group were 49% female, and 51% male.</p> 
</br>
<p>- There were 9 active drugs being tested (including Capomulin), and one placebo.</p> 
</br>
<p>- Other datapoints include the age of each mouse, the weight of each mouse (g), testing timepoints, tumour volume (mm), and number of metastatic sites for each mouse.</p> 
</br>
<p>- All data was split across two separate csv files, which were merged then cleaned to create a more usable, single dataset.</p> 
</br>
<h3><u>Observable Trends</u></h3>
</br> 
<p>- Capomulin, being the drug of interest, had the highest number of mice being tested (230), with Propriva having the fewest mice being tested (148).</p> 
</br>
<p>- Drug effectiveness was analysed by looking at tumour volume (mm3) distribution across four specific drugs (Capomulin, Ramicane, Infubinol and Ceftamin). Of those four, Capomulin and Ramicane proved most effective, having a significantly lower mean tumour volume than the other drugs, and no potential outliers. Ramicane had a similar sample size to Capomulin, with 228 mice being tested.</p> 
</br>
<p>- Looking at one specific mouse stengthens this result, as seen in mouse s185. In the line plot, tumour volume decreases by more than 20mm3 across the study timeframe.</p> 
</br>
<p>- The correlation between average weight (g) and average tumour volume (mm) is 0.84, which is a very strong indication of a direct positive relationship between the two factors.</p> 
</br>
<p>----------------------------------------------------------</p> 
</br>
<p>Thank you for reading!</p> 
<h3>🐁🐁🐁</h3>
</br>
<p>NB: I leaned on numerous sources for troubleshooting and help, including AskBCS (for IQR section), websites including Stack Overflow (particularly for 'isin' and 'duplicated' functions) and Python/Matplotlib/Pandas documentation sites. </p>
</br>
<p>Image by Adobe Stock Images, seen on spectrumnews.org</p>
