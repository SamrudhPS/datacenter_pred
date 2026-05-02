# datacenter_pred
End-to-end machine learning pipeline for predicting Heat Exchanger Effectiveness and Oil Power Rejected (W) on an AI edge computing thermal dataset.
Stacking Ensemble achieves R² = 0.9953 on HX Effectiveness and R² = 0.9778 on Oil Power Rejected.
<br>
# dataset size
<ul>Total recoreds-213</ul>
<ul>columns-33</ul>
<ul>Ambient temps (30/47/50°C)-3</ul>
<ul>Oil flow rates (5/7.5/10 L/min)-3</ul>
<ul>Fan speeds (30/50/70/90%)-4</ul>
<br>
# ML targets
Target 1: hx_eff (HX Effectiveness)
Continuous, range 0.37–1.15. Measures how efficiently the heat exchanger transfers heat. Ridge won → R²=0.9830
<br>
Target 2: power_rejected_W (Oil Power Rejected)
Continuous, range 127–1176 W. Total heat dumped by the oil cooling loop. Extra Trees won → R²=0.9795
