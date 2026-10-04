<div align="center">

<!-- HEADER BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,12,24&height=180&section=header&text=Hello,%20World!%20I'm%20Palash&fontSize=36&fontColor=ffffff&animation=fadeIn" width="100%"/>

<!-- SUB-HEADER TYPING EFFECT -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=A9B1D6&center=true&vCenter=true&width=620&lines=Autonomous+Robotics+%7C+Physics-Based+Simulation;Deep+Reinforcement+Learning+for+Legged+Locomotion;ROS+2+Jazzy+%E2%80%A2+Gazebo+Harmonic+%E2%80%A2+MuJoCo;Vision+Team+Lead+%40+Robolution+(BIT+Mesra);Breaking+physics+engines+and+fixing+their+friction+cones" alt="Typing SVG" />
</a>

<br/>

<!-- QUICK BADGES / SOCIALS -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/palash-mendhe)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PalashMendhe)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:palashmendhe777@gmail.com)

</div>

---

### 💻 `$ whoami`

```yaml
identity:
  name: "Palash Siddharth Mendhe"
  role: "Pre-final Year B.Tech in AI & ML @ BIT Mesra (2024–2028)"
  leadership: "Vision Team Lead @ Robolution / Pratyunmis (BIT Mesra)"
  location: "Ranchi, Jharkhand, India"
  timezone: "UTC+05:30"

specializations:
  - "Autonomous Mobile Robots (AMR) & Multi-Agent Logistics"
  - "Physics-based Simulation (MuJoCo, Gazebo Harmonic, ODE)"
  - "Deep RL for Legged Locomotion (CPG + Residual Actor-Critic)"
  - "Manipulator Kinematics & Motion Planning (MoveIt 2, Analytical IK)"

loves:
  - "Hunting down ODE pivot stalls and tweaking anisotropic friction vectors"
  - "Residual Deep RL policies dancing on non-linear Hopf oscillators"
  - "Deterministic closed-form IK > numerical solver timeouts"
  - "Full-stack robotics CI/CD with Docker & headless testing"

current_vibe: "Listening to Synthwave & tuning reward weights at 2 AM"
```

<table>
  <thead>
    <tr>
      <th align="left">Project</th>
      <th align="left">Highlights & Tech Stack</th>
      <th align="left">Status / Benchmarks</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        🐕 <b><a href="https://github.com/PalashMendhe/Reinforcement_learning_ws_go1">Hybrid CPG-RL Quadruped Locomotion</a></b><br/>
        <i>(Unitree Go1)</i>
      </td>
      <td>
        • Coupled non-linear <b>Hopf/Kuramoto CPG oscillators</b> with residual <b>Deep RL (SAC, TD3, PPO)</b> in <b>MuJoCo</b> for bio-inspired 12-DoF trotting.<br/>
        • Benchmarked custom PyTorch algorithms from scratch; multi-objective reward shaping (velocity tracking, clearance symmetry, posture).<br/>
        • <b>Tech:</b> <code>PyTorch</code> <code>MuJoCo</code> <code>Gymnasium</code> <code>CPG</code> <code>SAC</code> <code>TD3</code> <code>PPO</code> <code>CI/CD</code>
      </td>
      <td>
        <code>[██████████]</code> <b>Completed</b><br/>
        ⚡ <b>SAC:</b> ≥ 2000 return in 124k steps (~4.5× PPO efficiency)<br/>
        ⏱️ <b>TD3:</b> 11.9 ms/step wall-clock<br/>
        🧪 <b>29 Pytest suites</b> + GitHub Actions CI
      </td>
    </tr>
    <tr>
      <td>
        🪐 <b><a href="https://github.com/PalashMendhe/robotics-ws">Autonomous Mobile Robot & Warehouse Logistics</a></b><br/>
        <i>(AMR + Station Manipulators)</i>
      </td>
      <td>
        • End-to-end fulfillment system coordinating a 4-wheel skid-steer AMR and 6-DOF station arms via asynchronous mission state machine.<br/>
        • Diagnosed ODE 89° pivot stall: aligned directional friction vectors (<code>&lt;fdir1&gt;</code>) & decoupled lateral slip (μ₂ = 0.05).<br/>
        • Rasterized 17 shelf footprints as 100% solid Costmap2D obstacles; monotonic TF broadcaster & +193 mm lift analytical IK.<br/>
        • <b>Tech:</b> <code>ROS 2 Jazzy</code> <code>Gazebo Harmonic</code> <code>Nav2</code> <code>MoveIt 2</code> <code>AMCL</code> <code>ODE</code>
      </td>
      <td>
        <code>[██████████]</code> <b>Never Completes</b><br/>
        🎯 <b>0.02% rotational error</b> with zero drift<br/>
        📦 Pure-physics parcel retention
      </td>
    </tr>
    <tr>
      <td>
        🦾 <b><a href="https://github.com/PalashMendhe/robotic_arm_ws">Working perception based locomotion</a></b><br/>
        <i>(UR5 Industrial Replica)</i>
      </td>
      <td>
        • Built a hardened simulation testbed with centralized kinematics, workspace bounds, and motion limits (<code>robot_params.yaml</code>).<br/>
        • Implemented closed-form analytical IK (<code>compute_ik</code>) for deterministic 11-step Cartesian pick-and-place routines.<br/>
        • Multi-tier safety architecture: pre-flight action server checks, continuous 3D workspace containment, and automatic emergency abort.<br/>
        • <b>Tech:</b> <code>ROS 2</code> <code>MoveIt 2</code> <code>Gazebo Harmonic</code> <code>Python</code> <code>Docker</code> <code>Pytest</code>
      </td>
      <td>
        <code>[█████████░]</code> <b>Active / V2</b><br/>
        🛡️ Continuous 3D safety bounds<br/>
        🐳 Automated Docker + GitHub Actions CI
      </td>
    </tr>
  </tbody>
</table>
### 🤖 Robotics, Autonomy & AI Stack

#### ⚙️ Middleware, Simulation & Physics Engines
<p align="left">
  <img src="https://img.shields.io/badge/ROS_2-Jazzy%20%7C%20Lyrical-22314E?style=for-the-badge&logo=ros&logoColor=white" />
  <img src="https://img.shields.io/badge/Gazebo-Harmonic-F26522?style=for-the-badge&logo=gazebo&logoColor=white" />
  <img src="https://img.shields.io/badge/MuJoCo-Physics_Engine-4834d4?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ODE-Open_Dynamics_Engine-grey?style=for-the-badge" />
  <img src="https://img.shields.io/badge/RViz2-Visualization-34495E?style=for-the-badge&logo=ros&logoColor=white" />
  <img src="https://img.shields.io/badge/Fusion_360-CAD%2FModeling-E05A47?style=for-the-badge&logo=autodesk&logoColor=white" />
</p>

#### 🧭 Autonomy, Motion Planning & State Estimation
<p align="left">
  <img src="https://img.shields.io/badge/Nav2-Autonomous_Navigation-007ACC?style=for-the-badge&logo=ros&logoColor=white" />
  <img src="https://img.shields.io/badge/MoveIt_2-Motion_Planning-4B6584?style=for-the-badge&logo=ros&logoColor=white" />
  <img src="https://img.shields.io/badge/AMCL-Adaptive_Monte_Carlo-16a085?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Costmap_2D-Obstacle_Layering-27ae60?style=for-the-badge" />
  <img src="https://img.shields.io/badge/EKF_%2F_UKF-robot__localization-8e44ad?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Kinematics-Analytical_IK_%7C_KDL-d35400?style=for-the-badge" />
</p>

#### 🧠 Deep Reinforcement Learning & Machine Learning
<p align="left">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Gymnasium-Farama_Foundation-1E293B?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Algorithms-SAC_%7C_TD3_%7C_PPO-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/CPG-Hopf_%2F_Kuramoto_Oscillators-teal?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Control-Continuous_Control_%7C_GAE-008080?style=for-the-badge" />
</p>

#### 💻 Languages & DevOps
<div align="center">
  <img src="https://skillicons.dev/icons?i=cpp,python,c,matlab,bash,linux,ubuntu,docker,git,githubactions,cmake&theme=dark" />
</div>

### Activity & Contribution
### 📊 Activity & Contributions

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=PalashMendhe&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=70A5FD&icon_color=BF9EEE&text_color=A9B1D6" alt="Palash's GitHub Stats" height="165" />
  <img src="https://streak-stats.demolab.com?user=PalashMendhe&theme=tokyonight&hide_border=true&background=0D1117" alt="GitHub Streak" height="165" />
</div>

<br/>

<div align="center">
  <img src="https://raw.githubusercontent.com/PalashMendhe/PalashMendhe/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" width="100%" />
</div>
