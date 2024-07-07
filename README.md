### Hi, I'm Divyanshi!

<!--
**Div2346/Div2346** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


 # 💫 About Me:
🔭 An aspiring Machine Learning Engineer, learning new stuff everyday<br>🎓 Studying B.Tech. Computer Science and Engineering - Data Science, ML and AI at Lovely Professional University<br>🌱 I’m currently learning Big Data while undergoing my summer training<br>💬 Ask me about ... Data Analytics, Machine Learning, Deep Learning, Quantum Computing<br>📫 Reach out to me at: dvnsh2312@gmail.com<br>⚡ Fun fact: ... I love Rajma Rice!
# Hi, I'm Divyanshi!

<div style="display: flex; align-items: center;">
  <span style="font-size: 24px; margin-right: 10px;">Hi, I'm Divyanshi!</span>
  <svg id="fractalTree" width="100" height="100" viewBox="0 0 100 100"></svg>
</div>

<script>
  const svg = document.getElementById('fractalTree');
  const namespace = "http://www.w3.org/2000/svg";

  function createFractalTree(x1, y1, angle, depth) {
    if (depth === 0) return;
    
    const x2 = x1 + Math.cos(angle) * depth * 10.0;
    const y2 = y1 + Math.sin(angle) * depth * 10.0;
    
    const line = document.createElementNS(namespace, 'line');
    line.setAttribute('x1', x1);
    line.setAttribute('y1', y1);
    line.setAttribute('x2', x2);
    line.setAttribute('y2', y2);
    line.setAttribute('stroke', 'black');
    
    svg.appendChild(line);
    
    createFractalTree(x2, y2, angle - 0.52, depth - 1);
    createFractalTree(x2, y2, angle + 0.52, depth - 1);
  }

  function changeTreePattern() {
    while (svg.firstChild) {
      svg.removeChild(svg.firstChild);
    }
    createFractalTree(50, 100, -Math.PI / 2, 7);
  }

  changeTreePattern();
  setInterval(changeTreePattern, 5000);
</script>



# 💻 Tech Stack:
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)  ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)




<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
