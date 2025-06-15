<h1>🔦 Microwave-Motion-Detector-Based-Automatic-Light</h1>

<p>This project is an automatic light control system using a microwave motion detector. When motion is detected, the system automatically turns on a connected light and keeps it ON for a defined period. It is a touchless, energy-saving solution for smart lighting applications.</p>

<h2>⚙️ How It Works</h2>
<ul>
  <li>The microwave motion detector module continuously scans for movement.</li>
  <li>When motion is detected, the opto-isolated TRIAC driver (MOC3020) triggers the BT136 TRIAC to turn on the AC light.</li>
  <li>The light remains ON as long as motion is detected.</li>
  <li>After a short delay, the light turns OFF automatically if no movement is detected.</li>
</ul>

<h2>🔌 Circuit Description</h2>
<p>The circuit is divided into three sections:</p>

<h3>1. Power Supply Section</h3>
<ul>
  <li>AC voltage is rectified using a bridge rectifier (1N4007 diodes).</li>
  <li>A 5V Zener diode ensures a regulated 5V output for the motion detector module.</li>
</ul>

<h3>2. Motion Detection & Control Section</h3>
<ul>
  <li>The microwave motion sensor detects motion and sends a signal.</li>
  <li>An indicator LED (LED1) turns ON when motion is detected.</li>
  <li>A 100Ω resistor (R8) limits current to the optocoupler.</li>
</ul>

<h3>3. Light Switching Section</h3>
<ul>
  <li>The MOC3020 optocoupler isolates the low-power control circuit from the high-power AC load.</li>
  <li>The BT136 TRIAC is triggered to switch the AC light ON.</li>
  <li>A snubber network (capacitor + resistor) ensures stable operation of the TRIAC.</li>
</ul>

<h2>📋 Components Used</h2>
<table>
  <tr><th>Component</th><th>Description</th></tr>
  <tr><td>Microwave Motion Detector</td><td>Detects movement</td></tr>
  <tr><td>MOC3020</td><td>Optocoupler for isolation</td></tr>
  <tr><td>BT136</td><td>TRIAC for AC load switching</td></tr>
  <tr><td>1N4007 Diodes</td><td>Bridge rectifier</td></tr>
  <tr><td>Zener Diode (5V)</td><td>Voltage regulation</td></tr>
  <tr><td>LED & Resistors</td><td>Indicator and current limiting</td></tr>
  <tr><td>Capacitors</td><td>Filtering and snubber network</td></tr>
</table>

<h2>🧠 Working Principle</h2>
<ul>
  <li><strong>Motion Detected</strong> → Sensor triggers the circuit.</li>
  <li><strong>Optocoupler Activates</strong> → MOC3020 isolates and triggers the TRIAC.</li>
  <li><strong>Light Turns ON</strong> → The TRIAC allows AC power to the bulb.</li>
  <li><strong>No Motion</strong> → Light turns OFF after a delay.</li>
</ul>

<h2>💡 Applications</h2>
<ul>
  <li>Automatic Room Lighting</li>
  <li>Corridor & Staircase Lighting</li>
  <li>Smart Home Automation</li>
  <li>Security Lighting</li>
</ul>


📬 Author: Jitendra Sharma 📧 Email: jitendrasharma7409@gmail.com 🔗 Follow for more: https://github.com/jitendrasharma-eng?tab=repositories | www.youtube.com/@ECodeLab-mv4jm | linkedin.com/in/jitendra-sharma-484072248 [https://www.linkedin.com/in/jitendra-sharma-484072248?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BdRzhEpUKQSqQh6%2Fm6UayRw%3D%3D]
