# Understanding Climate Models: Urban Modelling with RegCM and WRF
iSci 3A12 Climate Change Public Summary, Fall 2023 <br>
**By: Abigail H., Edmund P., Flora S., Samiksha B.**

The World Climate Research Programme consistently publishes the Coupled Model Intercomparison Report (CMIP) as a way to provide general, publicly available information on climate change (Nie et al., 2020). The CMIP looks at different models on a regional and global level, however, what is not readily explained is the reasoning behind their comparison.

In the contemporary age of climate change, new generations of high-resolution climate models have become fundamental for informing decision-making mitigation strategies. These models offer information that can better assist weather and pattern prediction of Earth’s dynamic climate system, categorised on a regional and global level. While global climate models (GCMs) primarily focus on major long-term effects and simulate large-scale general processes, certain models can lack the intricacies required to predict on the local scale. As such, regional climate models (RCMs) come into play. RCMs employ downscaling, which is the process of extrapolating the outputs of GCMs, to simulate higher-resolution outputs for smaller, limited regional scales of interest (Xue et al., 2014) (Figure 1). Despite extensive research affirming the accuracy of these models, the public may raise concerns about the CMIP and why there is a need for numerous models. Each model is created for specific needs, using specific computational and geospatial parameters. Some models are meant to provide detailed atmospheric results, while others are for land processes. To illustrate this, it is important to look at model comparisons in detail.

<img src="gcm-to-rcm.png" alt="Statistical Downscaling of GCMs into RCMs" width="1000" style="border: 1px solid darkgrey">

*Figure 1: Dynamical downscaling of global climate models (GCM) using the higher resolution and lower domain of regional climate models (RCMs). Configurations of RCMs include an inner domain and a buffer zone, with time-dependent lateral boundary conditions (LBC) (Adapted on ArcGIS Pro from Giorgi, 2019).*

The two RCMs this paper focuses on are the Weather Research and Forecasting models (WRF) and the International Centre for Theoretical Physics (ICTP) regional climate model (RegCM). In its simplest terms, WRF models produce atmospheric forecasting by generating simulations based on actual or idealised conditions (National Centre for Atmospheric Research, 2023). These models can also consider the physical features of land surfaces by assessing the heat exchange system of cities, hot spots throughout the day and wind movement (Chen, Yang and Zhu, 2014). Similarly, RegCM is another model that takes into consideration land-surface processes and is widely used in downscaling GCM climate change projections (Gao and Giorgi, 2017).

Downscaling into RCMs has applications in understanding and interpreting climate, including the predictions of factors such as precipitation, temperature, and wind (Kong et al., 2019). However, one important aspect is modelling urban areas. Rapidly developing regions and increased anthropogenic activity can be concerning, since this adds in many complex factors to represent climate (Karlický et al., 2020). For example, an application with both CMIP6 models was applied to China, specifically its urban landscape. It was found that WRF had more intricacy in modelling specific factors, however, it is clear that the models are made for strengths in differing areas (Table 1). 

*Table 1: Comparison between the Weather Research and Forecasting models (WRF) and the International Centre for Theoretical Physics (ICTP) regional climate model (RegCM) for modelling general outputs related to temperature, precipitation, and urban regions. Comparisons between both models are based on comparitive studies done in China and other urban agglomerations.*
|   | Temperature  | Precipitation  | Urban Modelling  |
|---|---|---|---|
| Comparison (RegCM and WRF) | For large-scale modelling over long time periods, WRF is a more accurate model. For daily variation and extreme temperature events, RegCM performs with more validity (Kong et al., 2020; Gao, 2020). | WRF is consistently more accurate at estimating precipitation.  RegCM may be able to better predict extreme precipitation events (Liang et al., 2019; Gao, 2020). | WRF has overall better accuracy in modelling urban schemes. Specific adjustments such as the Building Energy Model contribute to its validity. Both WRF and RegCM have made advancements to represent anthropogenic activity (Karlický et al., 2018).  |  

Applications of WRF and RegCM, specifically with urban areas, have impacts on how we view climate modelling as a whole. It is clear that there are many models represented in the CMIP6 because of its applications to different factors that impact climate, where specific ones outperform in certain areas. Urban residents may pay particular attention to the evolution of RCMs since proposals of new legislation and planning developments heavily relies on their improvement. 

# References

Chen, F., Yang, X. and Zhu, W., 2014. WRF simulations of urban heat island under hot-weather synoptic conditions: The case study of &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Hangzhou City, China. Atmospheric Research, 138, pp.364–377.  ht<span>tps://</span>doi.org/10.1016/j.atmosres.2013.12.005.

Gao, X. and Giorgi, F., 2017. Use of the RegCM System over East Asia: Review and Perspectives. Engineering, 3(5), pp.766–772. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ht<span>tps://</span>doi.org/10.1016/J.ENG.2017.05.019.

Giorgi, F., 2019. Thirty Years of Regional Climate Modeling: Where Are We and Where Are We Going next? Journal of Geophysical Research: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Atmospheres, 124(11), pp.5696–5723. ht<span>tps://</span>doi.org/10.1029/2018JD030094.

Jiang, R., Sun, L., Sun, C. and Liang, X.-Z., 2021. CWRF downscaling and understanding of China precipitation projections. Climate &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dynamics, 57(3–4), pp.1079–1096.  ht<span>tps://</span>doi.org/10.1007/s00382-021-05759-z.

Karlický, J., Huszár, P., Halenka, T., Belda, M., Žák, M., Pišoft, P. and Mikšovský, J., 2018. Multi-model comparison of urban heat island &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;modelling approaches. Atmospheric Chemistry and Physics, 18(14), pp.10655–10674.  ht<span>tps://</span>doi.org/10.5194/acp-18-10655-2018.

Karlický, J., Huszár, P., Nováková, T., Belda, M., Švábik, F., Ďoubalová, J. and Halenka, T., 2020. The “urban meteorology island”: a &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;multi-model ensemble analysis. Atmospheric Chemistry and Physics, 20(23), pp.15061–15077.  ht<span>tps://</span>doi.org/10.5194/acp-20-15061-2020.

Kong, X., Wang, A., Bi, X. and Wang, D., 2019. Assessment of Temperature Extremes in China Using RegCM4 and WRF. Advances in &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Atmospheric Sciences, 36(4), pp.363–377.  ht<span>tps://</span>doi.org/10.1007/s00376-018-8144-0.

Kong, X., Wang, A., Bi, X. and Wei, J., 2020. Daily precipitation characteristics of RegCM4 and WRF in China and their interannual variations. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Climate Research, 82, pp.97–115.  ht<span>tps://</span>doi.org/10.3354/cr01621.

Liang, X.-Z., Sun, C., Zheng, X., Dai, Y., Xu, M., Choi, H.I., Ling, T., Qiao, F., Kong, X., Bi, X., Song, L. and Wang, F., 2019. CWRF performance &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;at downscaling China climate characteristics. Climate Dynamics, 52(3–4), pp.2159–2184.  ht<span>tps://</span>doi.org/10.1007/s00382-018-4257-5.

National Centre for Atmospheric Research, 2023. WEATHER RESEARCH AND FORECASTING MODEL: WRF. Available at: &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ht<span>tps://</span>w<wspan>w.mmm.ucar.edu/models/wrf.

Nie, S., Fu, S., Cao, W. and Jia, X., 2020. Comparison of monthly air and land surface temperature extremes simulated using CMIP5 and &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;CMIP6 versions of the Beijing Climate Center climate model. Theoretical and Applied Climatology, 140(1–2), pp.487–502. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ht<span>tps://</span>doi.org/10.1007/s00704-020-03090-x.

Pachauri, R.K., Mayer, L. and Intergovernmental Panel on Climate Change eds., 2015. Climate change 2014: synthesis report. [online] &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Geneva, Switzerland: Intergovernmental Panel on Climate Change. Available at:  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ht<span>tps://</span>w<wspan>w.ipcc.ch/site/assets/uploads/2018/02/WG1AR5_Chapter13_FINAL.pdf.

Xue, Y., Janjic, Z., Dudhia, J., Vasic, R. and De Sales, F., 2014. A review on regional dynamical downscaling in intraseasonal to seasonal &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;simulation/prediction and major factors that affect downscaling ability. Atmospheric Research, 147–148, pp.68–85.  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ht<span>tps://</span>doi.org/10.1016/j.atmosres.2014.05.001.
