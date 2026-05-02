# datacenter_pred
End-to-end machine learning pipeline for predicting Heat Exchanger Effectiveness and Oil Power Rejected (W) on an AI edge computing thermal dataset.An AI edge computing unit generates significant heat during operation. This project studies how different cooling configurations affect CPU temperature, heat exchanger efficiency, and power dissipation. The goal is to build ML models that can predict cooling performance (HX Effectiveness and Power Rejected) from operating conditions — so you can tune cooling parameters without running physical experiments every time.
<br>

# dataset_size
<ul>Total recoreds-213</ul>
<ul>columns-33</ul>
<ul>Ambient temps (30/47/50°C)-3</ul>
<ul>Oil flow rates (5/7.5/10 L/min)-3</ul>
<ul>Fan speeds (30/50/70/90%)-4</ul>
<br>

# ML_targets
<br>
Target 1: hx_eff (HX Effectiveness)
Continuous, range 0.37–1.15. Measures how efficiently the heat exchanger transfers heat. Ridge won → R²=0.9830
<br>
Target 2: power_rejected_W (Oil Power Rejected)
Continuous, range 127–1176 W. Total heat dumped by the oil cooling loop. Extra Trees won → R²=0.9795
