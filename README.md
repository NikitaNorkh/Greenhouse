<style>
  h1, h2, h3 {
    text-align: center;
    color: #2E8B57;
  }
  
  h1 {
    font-size: 36px;
    margin-top: 20px;
  }

  h2 {
    font-size: 28px;
    margin-top: 20px;
  }

  h3 {
    font-size: 22px;
    margin-top: 15px;
  }

  p {
    text-align: center;
    font-size: 16px;
    max-width: 800px;
    margin: auto;
  }

  img {
    display: block;
    margin: 15px auto;
    border-radius: 10px;
    max-width: 90%;
  }

  ul {
    max-width: 800px;
    margin: auto;
    font-size: 16px;
  }

  .highlight {
    background-color: #DEFDE0;
    padding: 5px 10px;
    border-radius: 5px;
    display: inline-block;
  }

  .section {
    margin: 30px 0;
    padding: 15px;
    background: #F0FFF0;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
  }

  code {
    background: #eee;
    padding: 2px 5px;
    border-radius: 3px;
  }
</style>

<h1>🛠️ Smart Greenhouse Automation System 🌿</h1>

<img src="src/assets/scheme.jpg" alt="Scheme" width="700"/>

<div class="section">
  <h2>🔥 Project Description</h2>
  <p>This project is a fully autonomous greenhouse management system, designed and built by me at the age of <span class="highlight">14</span>.</p>
  
  <ul>
    <li>✅ Automated cucumber watering based on DIY soil moisture sensors</li>
    <li>✅ Air temperature monitoring with heater activation</li>
    <li>✅ Automated water tank refill system</li>
    <li>✅ Dual microcontroller setup — <b>Arduino Nano</b> + <b>Arduino Uno</b></li>
  </ul>

  <p>I personally designed, soldered, and coded the entire system from scratch — from circuit diagrams to control logic!</p>
</div>

<div class="section">
  <h2>📸 Project Gallery</h2>

  <h3>📟 Main Controller</h3>
  <img src="src/assets/controller.JPG" alt="Controller" width="500"/>

  <h3>💧 DIY Soil Moisture Sensors</h3>
  <img src="src/assets/sensors.JPG" alt="Sensors" width="500"/>
  <img src="src/assets/sensorsInSoil.JPG" alt="Sensors in Soil" width="500"/>

  <h3>🛢️ Water Tank Setup</h3>
  <img src="src/assets/tank.JPG" alt="Tank" width="500"/>

  <h3>🔌 Internal Wiring and Cable Management</h3>
  <img src="src/assets/mounted_inside.jpg" alt="Mounted Inside" width="500"/>
  <img src="src/assets/mountedCables.jpg" alt="Mounted Cables" width="500"/>

  <h3>🌡️ Status Display</h3>
  <img src="src/assets/display.jpg" alt="Display" width="500"/>

  <h3>🌿 Buckets Watering Setup</h3>
  <img src="src/assets/bucket.jpg" alt="Bucket" width="500"/>
  <img src="src/assets/afterWatering.jpg" alt="After Watering" width="500"/>

  <h3>🔧 Full System Overview</h3>
  <img src="src/assets/fullPicture.JPG" alt="Full Picture" width="700"/>
</div>

<div class="section">
  <h2>🧩 Technical Highlights</h2>
  <ul>
    <li>11 DIY analog soil moisture sensors</li>
    <li>DS18B20 digital temperature sensor</li>
    <li><b>Arduino Uno</b> — system brain (pumps, heater, windows, etc.)</li>
    <li><b>Arduino Nano</b> — dedicated to reading analog sensors</li>
    <li>Serial communication between Arduinos</li>
    <li>Relay modules for pump & heater control</li>
    <li>LCD display for real-time status</li>
    <li>System protection: fuses, power separation</li>
  </ul>
</div>

<div class="section">
  <h2>💡 Why This is Awesome</h2>
  <ul>
    <li>🧠 Developed entirely by me, including circuits & code</li>
    <li>🚀 Completed at age <b>14</b>, proving skills in microcontrollers</li>
    <li>🌱 Solves real-world problems — automating plant care</li>
  </ul>
</div>

<div class="section">
  <h2>📂 Project Structure</h2>
  <pre>
src/assets/ — photos and diagrams
src/arduino_code/ — source code for both Arduino boards
README.md — you're reading it
  </pre>
</div>

<div class="section">
  <h2>🤝 Contact</h2>
  <p>If you're interested in similar projects or need help developing Arduino-based systems — feel free to reach out, I’d love to connect! 🙌</p>
</div>
