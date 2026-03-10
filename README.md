<h1 align="center">📐 IoT Tiling & Paint Estimator</h1>

<p align="center">
Smart Room Measurement & Material Estimation using IoT, 3D Visualization, and Web Technologies
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
The <b>IoT Tiling & Paint Estimator</b> is a smart web-based application designed to calculate
tile requirements and paint quantity for a room using either manual measurements
or real-time distance data streamed from an IoT device.
</p>

<p>
The system integrates <b>IoT distance measurement, Bluetooth communication,
3D room visualization, and cost estimation</b> to provide accurate material planning
for interior construction tasks.
</p>

<p>
Users can visualize their room in <b>interactive 3D</b>, select tile dimensions,
choose tile patterns, and instantly receive a detailed estimate of
tiles required, paint required, and total material cost.
</p>

<hr>

<h2>🎯 Key Features</h2>

<ul>
<li>📏 Real-time distance measurement using <b>Bluetooth (BLE)</b></li>
<li>🧱 Automatic tile requirement calculation</li>
<li>🎨 Paint quantity estimation based on wall area</li>
<li>📊 Interactive <b>3D room visualization</b> using Three.js</li>
<li>📱 Fully responsive UI for desktop and mobile</li>
<li>🌗 Light / Dark theme toggle</li>
<li>🧮 Automatic cost calculation for tiles and paint</li>
<li>🧠 Tile wastage calculation based on tile patterns</li>
<li>🔊 Voice feedback using Web Speech API</li>
<li>📡 Mock BLE mode for testing without hardware</li>
</ul>

<hr>

<h2>🛠 Technologies Used</h2>

<p>
<b>Frontend:</b><br>
HTML5<br>
CSS3<br>
JavaScript<br>

<b>Libraries:</b><br>
Three.js (3D visualization)<br>
Web Bluetooth API<br>
Web Speech API<br>

<b>IoT Integration:</b><br>
ESP32 BLE Distance Streaming Device
</p>

<hr>

<h2>📐 Calculations Performed</h2>

<ul>
<li>Floor Area Calculation</li>
<li>Wall Surface Area Calculation</li>
<li>Tile Quantity Estimation</li>
<li>Tile Wastage Adjustment</li>
<li>Paint Quantity Estimation</li>
<li>Total Material Cost Estimation</li>
</ul>

<hr>

<h2>🧱 Tile Pattern Wastage</h2>

<table border="1" cellpadding="6">
<tr>
<th>Tile Pattern</th>
<th>Wastage Percentage</th>
</tr>

<tr>
<td>Straight Lay</td>
<td>5%</td>
</tr>

<tr>
<td>Diagonal</td>
<td>10%</td>
</tr>

<tr>
<td>Herringbone</td>
<td>15%</td>
</tr>

<tr>
<td>Brick Pattern</td>
<td>8%</td>
</tr>

</table>

<hr>

<h2>📊 Outputs Generated</h2>

The estimator provides the following results:

<ul>
<li>Number of tiles required</li>
<li>Total tile cost</li>
<li>Paint required (litres)</li>
<li>Total paint cost</li>
<li>Floor area</li>
<li>Wall surface area</li>
<li>Total material cost</li>
</ul>

<hr>

<h2>▶️ How to Run the Project</h2>

<ol>

<li>Download or clone the repository</li>

<li>Ensure all files are in the same folder</li>

<li>Open the HTML file in a browser</li>

</ol>

<pre>
index.html
</pre>

<p>
For Bluetooth functionality:
</p>

<ul>
<li>Use a browser that supports <b>Web Bluetooth (Chrome / Edge)</b></li>
<li>Enable Bluetooth on your computer</li>
<li>Connect to the device named <b>"Distance Streamer"</b></li>
</ul>

<p>
If no IoT device is available, the system automatically switches to
<b>mock mode</b> to simulate live distance data.
</p>

<hr>

<h2>📦 Project Structure</h2>

<pre>
IoT-Tiling-Paint-Estimator
│
├── index.html
├── README.md
</pre>

<hr>

<h2>🛍 Suggested Suppliers (India)</h2>

<b>Tile Brands</b>

<ul>
<li>Kajaria Ceramics</li>
<li>Somany Ceramics</li>
<li>Asian Granito (AGL)</li>
</ul>

<b>Paint Brands</b>

<ul>
<li>Asian Paints</li>
<li>Berger Paints</li>
<li>Nerolac Paints</li>
</ul>

<hr>

<h2>🚀 Future Enhancements</h2>

<ul>
<li>Integration with real-time construction cost APIs</li>
<li>Export estimation reports as PDF</li>
<li>AI-based interior design suggestions</li>
<li>Augmented Reality room preview</li>
<li>Mobile app integration</li>
</ul>

<hr>

<p align="center">
⭐ If you find this project useful, consider giving it a star on GitHub!
</p>
