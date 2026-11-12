<div align="center">

# Hi there, I'm Khagesh Ranjan 👋

### **AI & Deep Learning Engineer | Systems & Full-Stack AI Builder**
**Rajiv Gandhi Institute of Petroleum Technology (RGIPT)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Khagesh%20Ranjan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/khagesh-ranjan-986721324/)
[![GitHub](https://img.shields.io/badge/GitHub-khageshranjan23--pixel-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/khageshranjan23-pixel)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:khageshranjan23@gmail.com)
[![Portfolio](https://img.shields.io/badge/Status-Actively%20Seeking%20Opportunities-success?style=for-the-badge)](#-get-in-touch)

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=620&lines=Deep+Learning+%26+Self-Supervised+Learning;First-Principles+NumPy+%26+PyTorch+Implementations;Autonomous+Multi-Modal+AI+Systems+%26+WebRTC;Production-Grade+FastAPI+%2B+Next.js+Applications" alt="Typing SVG" />
</p>

---

</div>

## 📌 Executive Summary

I am an **AI Engineer and Machine Learning Researcher** focused on bridging mathematical deep learning theory with robust, production-grade systems engineering. My work spans:
- **First-Principles Deep Learning**: Re-implementing fundamental algorithms (optimizers, analytical backpropagation, and ICML self-supervised representations) from scratch without relying on off-the-shelf black boxes.
- **Production AI Systems**: Architecting end-to-end multi-modal platforms integrating streaming WebRTC audio/video (LiveKit), LLM orchestration (Gemini API with structured outputs & tool-use), and low-latency backends (FastAPI, Cloudflare Workers).
- **Applied Machine Learning & Hackathons**: Building high-impact geospatial and risk-intelligence solutions (Smart India Hackathon 2026, UIDAI Aadhaar anomaly detection).

**Actively looking for AI / Machine Learning Engineer, Deep Learning Research Engineer, or Full-Stack AI roles.**

---

## 🚀 Featured Flagship Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🔬 Barlow Twins SSL on CIFAR-10</h3>
      <p align="center">
        <a href="https://github.com/khageshranjan23-pixel/dl070-barlow-twins-cifar10-24cs2021">
          <img src="https://img.shields.io/badge/Repo-Barlow--Twins--CIFAR10-blue?style=for-the-badge&logo=github" />
        </a>
      </p>
      <p><b>Empirical reproduction and ablation of ICML 2021 Barlow Twins SSL on consumer hardware.</b></p>
      <ul>
        <li><b>Key Result:</b> Achieved <b>74.84% linear probe test accuracy</b> and <b>72.41% 20-NN cosine accuracy</b> under a 50-epoch budget on an RTX 5050 GPU (537 MB peak VRAM).</li>
        <li><b>Scientific Finding:</b> Ablating the redundancy reduction term (&lambda; = 0) caused a catastrophic <b>17.72% drop</b> in linear probe accuracy, proving full rank alone does not ensure semantically separable embeddings.</li>
        <li><b>Stack:</b> <code>PyTorch</code>, <code>Torchvision</code>, <code>ResNet-18</code>, <code>SVD / Rank Analysis</code></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🤖 HireNeuron Verity</h3>
      <p align="center">
        <a href="https://github.com/khageshranjan23-pixel/hireneuron-verity">
          <img src="https://img.shields.io/badge/Repo-HireNeuron--Verity-purple?style=for-the-badge&logo=github" />
        </a>
      </p>
      <p><b>Autonomous AI technical recruitment platform with dual-camera integrity & real-time evaluation.</b></p>
      <ul>
        <li><b>Architecture:</b> Next.js recruiter dashboard, FastAPI transactional engine, LiveKit WebRTC dual-camera proctoring, Deepgram streaming STT/TTS adapter.</li>
        <li><b>AI Reasoning:</b> Gemini structured outputs for multi-turn technical follow-ups, citation-backed evaluation, and signed tamper-evident event chains.</li>
        <li><b>Stack:</b> <code>FastAPI</code>, <code>Next.js</code>, <code>TypeScript</code>, <code>LiveKit (WebRTC)</code>, <code>Gemini API</code>, <code>Deepgram</code></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">⚡ Deep Learning Optimizer Visualizer</h3>
      <p align="center">
        <a href="https://github.com/khageshranjan23-pixel/Deep-Learning-Optimizer-Visualizer">
          <img src="https://img.shields.io/badge/Repo-Optimizer--Visualizer-orange?style=for-the-badge&logo=github" />
        </a>
      </p>
      <p><b>7 Deep learning optimizers engineered from first principles in pure NumPy (0% autograd / PyTorch).</b></p>
      <ul>
        <li><b>From-Scratch Core:</b> SGD, Momentum, NAG, AdaGrad, RMSProp, Adam, and AdamW implemented with manual analytical backpropagation for a 3-layer MLP.</li>
        <li><b>Interactive Simulation:</b> 2D loss surfaces with condition numbers &kappa; &in; [10, 1000], synchronized contour maps, and live training benchmarks.</li>
        <li><b>Stack:</b> <code>Python</code>, <code>NumPy</code>, <code>Plotly</code>, <code>Streamlit</code>, <code>Pytest</code></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🌊 OceanEmbed (SIH 2026)</h3>
      <p align="center">
        <a href="https://github.com/khageshranjan23-pixel/oceanembed-sih2026">
          <img src="https://img.shields.io/badge/Repo-OceanEmbed--SIH2026-teal?style=for-the-badge&logo=github" />
        </a>
      </p>
      <p><b>Satellite-to-subsurface ocean temperature reconstruction (Smart India Hackathon 2026 - PS 26066).</b></p>
      <ul>
        <li><b>System:</b> React/Vite web application with Cloudflare Workers API serving precomputed spatio-temporal snapshots and regional regime metrics.</li>
        <li><b>Autonomous Queries:</b> Gemini function calling pipeline for natural language exploration of oceanographic profiles and inversion cases.</li>
        <li><b>Stack:</b> <code>Cloudflare Workers</code>, <code>React</code>, <code>Gemini Function Calling</code>, <code>Vite</code></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🛡️ UIDAI Risk Intelligence System</h3>
      <p align="center">
        <a href="https://github.com/khageshranjan23-pixel/UIDAI-PROJECT">
          <img src="https://img.shields.io/badge/Repo-UIDAI--Risk--Intelligence-red?style=for-the-badge&logo=github" />
        </a>
      </p>
      <p><b>AI-powered risk intelligence engine for detecting anomalous patterns in Aadhaar biometric & demographic updates.</b></p>
      <ul>
        <li><b>Multi-Tiered Detection:</b> Isolation Forest (unsupervised behavioral anomalies) + LSTM (temporal trend anomalies per pincode) + spatial clustering.</li>
        <li><b>Explainability:</b> Decision-maker risk heatmaps and composite scoring (< 0.30 normal, > 0.47 high-risk audit flags).</li>
        <li><b>Stack:</b> <code>Python</code>, <code>Scikit-Learn</code>, <code>TensorFlow / LSTM</code>, <code>Streamlit</code>, <code>Pandas</code></li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🛣️ RoadSense AI</h3>
      <p align="center">
        <a href="https://github.com/khageshranjan23-pixel/roadsense-ai">
          <img src="https://img.shields.io/badge/Repo-RoadSense--AI-green?style=for-the-badge&logo=github" />
        </a>
      </p>
      <p><b>Intelligent road condition monitoring and infrastructure defect detection platform.</b></p>
      <ul>
        <li><b>System:</b> Edge-first computer vision inference pipeline for automated pothole and crack detection, geotagging, and civic severity scoring.</li>
        <li><b>Dashboard:</b> Full-stack monorepo featuring real-time maps, asset tracking, and maintenance dispatch telemetry.</li>
        <li><b>Stack:</b> <code>TypeScript</code>, <code>Next.js</code>, <code>Computer Vision</code>, <code>Turborepo</code></li>
      </ul>
    </td>
  </tr>
</table>

---

## 🛠️ Technical Arsenal

<div align="center">

### **Deep Learning, Machine Learning & AI Research**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=NumPy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=SciPy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=Pandas&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=OpenCV&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=Plotly&logoColor=white)

### **Systems, Backend & Full-Stack Engineering**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=FastAPI&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=Next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=TypeScript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=Streamlit&logoColor=white)

### **AI Cloud, Streaming & Infrastructure**
![LiveKit WebRTC](https://img.shields.io/badge/LiveKit_WebRTC-0070F3?style=flat-square&logo=webrtc&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini_API-4285F4?style=flat-square&logo=google&logoColor=white)
![Deepgram](https://img.shields.io/badge/Deepgram_STT/TTS-13EF93?style=flat-square&logo=soundcharts&logoColor=black)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=Cloudflare&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=Linux&logoColor=black)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=SQLite&logoColor=white)

</div>

---

## 📊 GitHub Analytics & Activity

<div align="center">

<p align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=khageshranjan23-pixel&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" alt="Khagesh's GitHub Stats" />
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=khageshranjan23-pixel&layout=compact&theme=tokyonight&hide_border=true" width="48%" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=khageshranjan23-pixel&theme=tokyonight&hide_border=true" width="97%" alt="GitHub Streak" />
</p>

</div>

---

## 🏆 Key Milestones & Research Highlights

- 🏅 **Smart India Hackathon (SIH 2026):** Selected for Problem Statement 26066 — Subsurface ocean temperature reconstruction from satellite altimetry with OceanEmbed.
- 🔬 **Self-Supervised Learning Research:** Empirical study demonstrating the mathematical necessity of off-diagonal cross-correlation decorrelation in Barlow Twins on consumer GPUs.
- 💻 **Mathematical Backpropagation from Scratch:** Derived and coded full analytical forward/backward graph for neural networks and 7 adaptive optimizers without autograd engines.
- 🎯 **UIDAI Anomaly Detection:** Formulated dual-stream temporal (LSTM) and unsupervised behavioral (Isolation Forest) scoring for high-scale Aadhaar update audits.

---

## 📬 Get In Touch

I am open to discussions on **AI Engineering, Deep Learning Research, ML Infrastructure, and Full-Stack AI roles**.

- **Email:** [khageshranjan23@gmail.com](mailto:khageshranjan23@gmail.com)
- **GitHub:** [@khageshranjan23-pixel](https://github.com/khageshranjan23-pixel)
- **LinkedIn:** [Khagesh Ranjan](https://www.linkedin.com/in/khagesh-ranjan-986721324/)
- **Location:** India 🇮🇳 (Open to Remote, Hybrid, & Relocation)

<div align="center">
  <sub>Built with precision and passion by Khagesh Ranjan. Star ⭐ my repositories if you find my work inspiring!</sub>
</div>
