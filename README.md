<div align="center">

# Igor Braga Palhano
### **Telecommunications Engineer & Embedded / Edge AI Developer**
*Edge Machine Learning • Wireless Systems & RF Protocols • Embedded Firmware*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/igor-palhano-81102622a/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:igor.palhano@alu.ufc.br)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)](https://www.kaggle.com/igorbragapalhano)
[![Codewars](https://img.shields.io/badge/Codewars-B1361E?style=for-the-badge&logo=Codewars&logoColor=white)](https://www.codewars.com/users/BPalhano)
[![Location](https://img.shields.io/badge/Location-Fortaleza%2C%20Brazil-2ea44f?style=for-the-badge&logo=google-maps&logoColor=white)](https://maps.google.com)

</div>

---

### 👨‍💻 About Me

- 🎓 **Telecommunications Engineer** graduate & researcher at **Universidade Federal do Ceará (UFC)**, with academic experience at **ENSICAEN (France)** and research at **GTEL (Wireless Telecommunications Research Group)**.
- 🏎️ **Edge AI & Autonomous Systems**: Deep learning applied to real-time embedded systems, pioneering hybrid Vision Transformers (**MicroViT**) accelerated with **NVIDIA TensorRT INT8** and **ONNX Runtime**.
- 📡 **Wireless & RF Protocol Engineering**: Extensive work with wireless channel modeling (3GPP standards), cellular positioning algorithms, and low-level RF reconnaissance (802.11 monitor mode, Bluetooth/BLE packet inspection).
- ⚙️ **Embedded Firmware**: Hands-on development of bare-metal and RTOS-based firmware (**ESP-IDF**, **FreeRTOS**, C/C++) with direct hardware peripheral control (I2S, DMA, GPIO).

---

### 🚀 Highlighted Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🏎️ <a href="https://github.com/BPalhano/nxpcup">NXP Cup Autonomous Driving</a></h3>
      <p><strong>Edge AI Perception & High-Speed Continuous Steering</strong></p>
      <ul>
        <li>Hybrid Vision Transformer (<strong>MicroViT</strong>, 359k params) built for 1:10 autonomous racing, <strong>-77.4% smaller than NVIDIA DAVE-2</strong>.</li>
        <li>Compiles to <strong>sub-2.2ms latency (&gt;430 FPS)</strong> on edge devices via <strong>NVIDIA TensorRT INT8 PTQ</strong> and <strong>ONNX Runtime</strong>.</li>
        <li>Autonomous kinematic labeling with 3D Inverse Perspective Mapping (IPM) and <strong>Stanley + Pure Pursuit</strong> controllers.</li>
        <li>Production inference microservice using <strong>FastAPI</strong>, <strong>Docker</strong>, <strong>MLflow</strong>, and <strong>Evidently AI</strong> data-drift auditing.</li>
      </ul>
      <p><em>Stack: PyTorch, TensorRT INT8, ONNX, FastAPI, Docker, OpenCV, Python</em></p>
    </td>
    <td width="50%" valign="top">
      <h3>📡 <a href="https://github.com/BPalhano/wireless_prober">Wireless Prober (RF Listener)</a></h3>
      <p><strong>Linux RF Reconnaissance & Wireless Protocol Inspector</strong></p>
      <ul>
        <li>Automated reconnaissance tool auditing <strong>802.11 Wi-Fi</strong>, <strong>Bluetooth Classic</strong>, and <strong>Bluetooth Low Energy (BLE)</strong>.</li>
        <li>Captures client probe requests, authentication, and association frames in <strong>Monitor Mode</strong> via low-level <code>tshark</code> filters.</li>
        <li>Extracts active AP parameters, associated stations, and RSSI metrics interfacing with native Linux networking (<code>iw</code>, <code>bluez</code>).</li>
        <li>Asynchronous BLE advertisement discovery and peripheral inspection via <code>bleak</code>.</li>
      </ul>
      <p><em>Stack: Python, Linux Networking (iw, bluez), TShark, BLE, Wi-Fi 802.11</em></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/BPalhano/ESP32-projects">ESP32 Firmware & Audio DSP</a></h3>
      <p><strong>Low-Level Microcontroller Architecture & Peripheral Drivers</strong></p>
      <ul>
        <li>Direct peripheral control configuring the <strong>I2S (Inter-IC Sound)</strong> interface for dual-channel audio streaming.</li>
        <li>Configured <strong>DMA (Direct Memory Access)</strong> ring buffers for deterministic zero-copy sample transfer.</li>
        <li>Built on <strong>FreeRTOS</strong> preemptive multitasking for precise cycle scheduling on <strong>ESP32</strong> silicon.</li>
        <li>Modular build automation and menu configuration using Espressif's <strong>ESP-IDF</strong> and CMake.</li>
      </ul>
      <p><em>Stack: C, ESP-IDF, FreeRTOS, I2S Driver, DMA, CMake, ESP32</em></p>
    </td>
    <td width="50%" valign="top">
      <h3>🌐 <a href="https://github.com/BPalhano/Pallas">Pallas Telecommunications Library</a></h3>
      <p><strong>Wireless Channel Simulation & Radio Positioning Framework</strong></p>
      <ul>
        <li>Modular Python library for physical layer mobile network simulations and link evaluations.</li>
        <li>Standardized propagation channel models including <strong>3GPP Urban Macro (UMa)</strong> path loss and multipath fading.</li>
        <li>Implements spatial multi-antenna arrays and RF-based <strong>user positioning algorithms</strong> (ToA, TDoA, AoA).</li>
        <li>Optimized numerical computations utilizing vectorized NumPy/SciPy operations for extensive simulation grids.</li>
      </ul>
      <p><em>Stack: Python, NumPy, SciPy, 3GPP Channel Models, RF Positioning</em></p>
    </td>
  </tr>
</table>

---

### 🛠️ Technical Arsenal

<div align="center">

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Languages** | `C` • `C++` • `Python` • `Bash` • `MATLAB` • `Julia` • `SQL` |
| **Edge AI & Vision** | NVIDIA TensorRT (INT8 PTQ) • ONNX Runtime • PyTorch • OpenCV • Vision Transformers • MLflow |
| **Telecom & Wireless** | 3GPP Channel Modeling • RF Positioning/Planning • 802.11 Wi-Fi • BLE • TShark / Wireshark • DSP |
| **Embedded & Systems** | ESP-IDF • FreeRTOS • I2S / DMA • Linux (Debian/Arch) • POSIX • CMake • Docker |
| **Tooling & Quality** | Git • GitHub Actions (CI/CD) • Pytest • Evidently AI (Drift) • Neovim / Emacs • LaTeX |

<br/>

<a href="https://github.com/BPalhano">
  <img src="https://skillicons.dev/icons?i=c,cpp,python,pytorch,linux,docker,bash,git,matlab" alt="Skills" />
</a>

</div>

---
<!--
### 📊 GitHub Activity

<div align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=BPalhano&show_icons=true&theme=tokyonight&count_private=true&hide_border=true" alt="Igor's GitHub Stats" />
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BPalhano&layout=compact&theme=tokyonight&count_private=true&hide_border=true&langs_count=8" alt="Top Languages" />
</div>

---
-->
<div align="center">
  <sub>Open for challenging opportunities in Edge AI, Embedded Systems, and Telecommunications Engineering.</sub>
</div>
