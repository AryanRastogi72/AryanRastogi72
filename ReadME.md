<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:2C5364,100:2E9EF7&height=200&section=header&text=Aryan%20Rastogi&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=Electrical%20%26%20Computer%20Engineering%20%7C%20Hardware%20to%20Full-Stack%20to%20Applied%20ML&descAlignY=62&descSize=16"/>

<a href="https://www.linkedin.com/in/aryan-rastogi-742109382/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" height="36"/></a>
<a href="https://github.com/AryanRastogi72"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" height="36"/></a>
<a href="mailto:ar323@snu.edu.in"><img src="https://img.shields.io/badge/College%20Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" height="36"/></a>
<a href="mailto:rastogiaryan2005@gmail.com"><img src="https://img.shields.io/badge/Personal%20Email-4285F4?style=for-the-badge&logo=gmail&logoColor=white" height="36"/></a>

</div>

<br/>

> I'm an Electrical and Computer Engineering student at Shiv Nadar University who works across the stack in the literal sense — from FPGA-level digital design up through backend systems and applied machine learning. I like understanding what's actually happening beneath the abstraction layer, whether that's a clock cycle inside an FPGA, a database transaction, or a REST API call.
>
> I haven't committed to a single specialization yet, and that's intentional — every project below reflects a different thing I set out to learn at the time, spanning hardware, full-stack web development, and AI systems.

<br/>

## 🧩 Technical Skills

<table width="100%">
<tr><td width="160"><b>Languages</b></td><td>

<img src="https://skillicons.dev/icons?i=python,cpp,c,java,js,kotlin,matlab&theme=dark"/>

</td></tr>
<tr><td><b>Frameworks & Libraries</b></td><td>

<img src="https://skillicons.dev/icons?i=react,nodejs,express,spring,flask,tailwind&theme=dark"/> &nbsp; `LangGraph`

</td></tr>
<tr><td><b>Databases</b></td><td>

<img src="https://skillicons.dev/icons?i=mysql,mongodb,sqlite&theme=dark"/>

</td></tr>
<tr><td><b>Hardware & Digital Design</b></td><td>

`Xilinx Vivado` &nbsp; `FPGA (Artix-7)`

</td></tr>
<tr><td><b>Tools</b></td><td>

<img src="https://skillicons.dev/icons?i=git&theme=dark"/>

</td></tr>
<tr><td><b>AI / ML — currently building with</b></td><td>

<img src="https://skillicons.dev/icons?i=fastapi,docker,pytorch,sklearn&theme=dark"/> &nbsp; `Streamlit`

</td></tr>
</table>

<br/>

## 💼 Experience & Education

<table width="100%">
<tr>
<td width="28%" valign="top"><b>Jun 2026 – Aug 2026</b><br/><sub>Bengaluru</sub></td>
<td width="72%" valign="top">

**Summer Intern — L&T Technology Services (LTTS)**

Engineered an end-to-end stock prediction system evaluating 12 model variants (Random Forest, XGBoost, LSTM) across regression and classification tasks, trained on 15 years of daily NSE market data (3,698 records, 2011–2026). Deployed via a FastAPI backend, Streamlit interface, and Docker containerization.

- Achieved an **R² of 0.975** and **RMSE of 57.11** for 1-day-ahead price forecasting with a hyperparameter-tuned LSTM network — against a test-period price range of ₹2,529–₹4,375.
- Built a 3-class trend classifier (Up/Down/Flat, ±0.5% threshold) with a tuned XGBoost model reaching **37.30% accuracy**, outperforming the 31.69% majority-class baseline in a historically hard prediction setting.
- Built a real-time inference pipeline pulling 6 months of live Yahoo Finance data, computing technical indicators (MACD, RSI, Bollinger Bands), and returning predictions via REST API in milliseconds using pre-serialized `.joblib`/`.pt` model weights.

</td>
</tr>
<tr><td colspan="2"><br/></td></tr>
<tr>
<td width="28%" valign="top"><b>Expected May 2027</b><br/><sub>Greater Noida</sub></td>
<td width="72%" valign="top">

**B.Tech, Electrical and Computer Engineering**
Shiv Nadar University

</td>
</tr>
</table>

<br/>

## 🚀 Featured Projects

<details open>
<summary><b>🎓 SARMS — University ERP System</b></summary>
<br/>

A full-stack university ERP with three role-based portals — Student, Faculty, and Admin — covering authentication, academic records, and semester progression. Replaces fragmented, manual academic administration (grading, SGPA computation, semester promotion) with a single role-aware system.

**Contribution:** Built collaboratively with 3 teammates — worked across the stack alongside the team on both frontend and backend, rather than owning a single isolated module.

![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**[→ View Repository](https://github.com/top-of-the-code/SARMS)**

</details>

<details>
<summary><b>🔬 FSM-Based RFFT Spectrum Analyzer</b></summary>
<br/>

A real-time N=16 FFT spectrum analyzer implemented entirely in Verilog on a Xilinx Artix-7 FPGA, with a live VGA bar-graph display at 640×480 @ 60Hz. Demonstrates real-time frequency-domain signal analysis on bare FPGA hardware — an FSM-driven datapath computing an FFT using Q1.15 fixed-point arithmetic, without relying on a soft processor or vendor DSP IP core.

**Contribution:** Built collaboratively with 3 teammates on the FSM datapath design, fixed-point arithmetic implementation, and VGA output logic; synthesized and deployed on a Digilent Nexys 4.

![Verilog](https://img.shields.io/badge/Verilog-1E1E1E?style=flat-square) ![Vivado](https://img.shields.io/badge/Xilinx_Vivado-E31937?style=flat-square) ![FPGA](https://img.shields.io/badge/FPGA_(Artix--7)-8A2BE2?style=flat-square)

**[→ View Repository](https://github.com/aniket-s007/FSM_based_RFFT)**

</details>

<details>
<summary><b>🏦 RANS Bank — Online Banking Management System</b></summary>
<br/>

A full-featured banking platform with distinct role-based access for Customers, Staff, and Admins, covering account management, loans, and fund transfers. Handles loan lifecycles and EMI schedules through MySQL stored procedures, with row-level locking to prevent race conditions during concurrent fund transfers.

**Contribution:** Built collaboratively with 3 teammates across the application and database layers.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white) ![Jinja2](https://img.shields.io/badge/Jinja2-B41717?style=flat-square&logo=jinja&logoColor=white)

**[→ View Repository](https://github.com/RaghavGarg3594/Online_Banking_Management_System)**

</details>

<details>
<summary><b>✈️ Multi-Agent AI Travel Planner</b></summary>
<br/>

A multi-agent AI system that coordinates real-time flight and hotel data across 5+ API endpoints and generates dynamic itinerary and pricing recommendations. Automates the manual, multi-source research process of trip planning by using a Map-Reduce agent workflow to gather and reconcile data from the Amadeus and OpenAI APIs in parallel.

**Contribution:** Solo project — designed and built end-to-end, including the agent workflow, API integrations, and data layer.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square) ![Amadeus](https://img.shields.io/badge/Amadeus_API-00205B?style=flat-square) ![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**[→ View Repository](https://github.com/AryanRastogi72/Multi_Agent_AI_Travel_Planner)**

</details>

<br/>

## 🎯 Current Focus

Wrapping up my LTTS internship and continuing to build across both hardware (FPGA/digital design) and software (full-stack, applied ML) rather than narrowing early. Open to internship and collaboration opportunities in embedded systems, full-stack development, or applied ML.

<br/>

## 📊 GitHub Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AryanRastogi72/AryanRastogi72/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AryanRastogi72/AryanRastogi72/output/github-contribution-grid-snake.svg">
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/AryanRastogi72/AryanRastogi72/output/github-contribution-grid-snake.svg" width="100%"/>
</picture>

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api?username=AryanRastogi72&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=2E9EF7&icon_color=2E9EF7&count_private=true&cache_seconds=1800" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AryanRastogi72&layout=compact&theme=radical&hide_border=true&bg_color=0D1117&title_color=2E9EF7&cache_seconds=1800" height="165" />

<img src="https://streak-stats.demolab.com/?user=AryanRastogi72&theme=radical&hide_border=true&background=0D1117&stroke=2E9EF7&ring=2E9EF7&fire=2E9EF7" />

</div>

<br/>

<div align="center">

**Let's connect**

<a href="https://www.linkedin.com/in/aryan-rastogi-742109382/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" height="36"/></a>
<a href="https://github.com/AryanRastogi72"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" height="36"/></a>
<a href="mailto:ar323@snu.edu.in"><img src="https://img.shields.io/badge/College%20Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" height="36"/></a>
<a href="mailto:rastogiaryan2005@gmail.com"><img src="https://img.shields.io/badge/Personal%20Email-4285F4?style=for-the-badge&logo=gmail&logoColor=white" height="36"/></a>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2E9EF7,50:2C5364,100:0F2027&height=90&section=footer"/>

</div>
