<!-- badges: start -->
[![](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
<!-- badges: end -->

<h1> Data Underlying the Study on Improving the Solar Sludge Pasteurization Technology </h1>

<b>Contributors</b>  
- Deniz Cinar
</a> *author, maintainer*  
- Jakub Tkaczuk <a href="https://orcid.org/0000-0001-7997-9423">
<img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0001-7997-9423
</a> *supervisor, developer*  
- Elizabeth Tilley <a href="https://orcid.org/0000-0002-2095-9724">
<img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png" width="16" height="16" /> 0000-0002-2095-9724
</a> *supervisor*  

<br>
<p align="middle"> 
<img src="img/ETH_GHE_logo_negative.svg" width=600>
<br><br>
It compliments the openly-accessible master’s thesis, available on the<br \>  
<a href="">ETH Research Collection</a>.
</p>

# Background

This repository compliments the study on the development and field evaluation of a low-cost, solar-powered sludge pasteurization system designed for decentralized sanitation contexts in Sub-Saharan Africa. The system was implemented at Rurri Primary School in Nakuru, Kenya, and tested under peak summer irradiance conditions. Through iterative design, three main versions of the solar water heater were developed, with the final version incorporating all adaptations emerging as the most effective configuration. It reliably achieved Escherichia coli inactivation in all treated samples while maintaining a treatment flow rate of approximately 3 L/h. The data validates the performance of the last pasteurizer's version.

The final system design remains financially viable, with a potential cost as low as $405 USD in installations where gravity flow is available and certain components, such as the heat exchanger, are excluded. While the final version performed well under optimal conditions, residual heat loss through the cold sludge inlet and overnight temperature decline were identified as areas for future improvement.

Temperature and irradiance data were continuously recorded and are available in `data/raw_data` directory, allowing for performance evaluation and time–temperature analysis against literature-based inactivation thresholds.

This work demonstrates the feasibility of decentralized solar-driven sludge treatment and offers a scalable, adaptable solution for improving sanitation in off-grid environments. Further work is needed to optimize thermal retention, validate system performance under variable climatic conditions, and explore automated flow control for enhanced consistency.

![](img/other_figures/swh.jpg)

# Data & system overview

The data in `data/raw_data` directory, together with the metadata in `data/metadata/metadata.csv` are the temperature and solar irradiance measurements collected from the points in the system presented on the figure below.

![](img/other_figures/swh_PandID_with_sensors.png)

# License

The complete design and user manual are licensed under [Creative Commons Attribution 4.0 International](https://github.com/Global-Health-Engineering/glass-crusher-design/blob/main/LICENSE.md).
