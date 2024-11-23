<h1 align="center">Hi 👋, I'm Muhammad Ahmed</h1>

<p align="center">
  <img src="https://camo.githubusercontent.com/cd878ec5a6b9314e5d2862b8f5f6e934ef657572f93e650c569aa3499937eebd/68747470733a2f2f6d656469612e67697068792e636f6d2f6d656469612f4650626e53687131683149533546517950442f67697068792e676966" alt="GIF" width="400"/>
</p>

<h2 align="center">
  <span>
    <p align="center">
      <span id="animated-text"></span>
    </p>
  </span>
</h2>

<p align="center">I'm a passionate backend developer from Pakistan.</p>

---

### **About Me**
<p align="center">
  🔭 I’m currently working on **Laravel, WordPress, and Shopify**  
  🌱 I’m currently learning **Vue.js and Shopify API integrations**  
  👯 I’m looking to collaborate on **Open-Source Laravel projects**  
  💬 Ask me about **Laravel, RESTful APIs, and Backend Development**  
  📫 How to reach me: [ahmeddeveloper@gmail.com](mailto:ahmeddeveloper@gmail.com)  
  ⚡ Fun fact: I love exploring new technologies and connecting with like-minded people  
</p>

---

### **Languages and Tools**
<p align="center">
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white" alt="Laravel"/>
  <img src="https://img.shields.io/badge/WordPress-21759B?style=flat&logo=wordpress&logoColor=white" alt="WordPress"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white" alt="MySQL"/>
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vue.js&logoColor=white" alt="Vue.js"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white" alt="PHP"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white" alt="Postman"/>
  <img src="https://img.shields.io/badge/Bootstrap-563D7C?style=flat&logo=bootstrap&logoColor=white" alt="Bootstrap"/>
</p>

---

### **Connect with Me**
<p align="center">
  <a href="https://www.linkedin.com/in/mahmed1011/?originalSubdomain=pk" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://www.instagram.com/ahmi_rajpoot1011/" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white" alt="Instagram"/>
  </a>
  <a href="https://www.facebook.com/profile.php?id=100022122034419" target="_blank">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=flat&logo=facebook&logoColor=white" alt="Facebook"/>
  </a>
  <a href="https://github.com/mahmed1011" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://api.whatsapp.com/send?phone=923136756624" target="_blank">
    <img src="https://img.shields.io/badge/WhatsApp-25D366?style=flat&logo=whatsapp&logoColor=white" alt="WhatsApp"/>
  </a>
</p>

---

### **GitHub Contributions**
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mahmed1011&theme=radical" alt="GitHub Streak"/>
  <img src="https://activity-graph.herokuapp.com/graph?username=mahmed1011&theme=radical" alt="GitHub Activity Graph"/>
</p>

---

<script>
const texts = [
  "I'm a Web Designer.",
  "I'm a Laravel Developer.",
  "I'm a WordPress Developer.",
  "I'm a Shopify Developer.",
  "I'm a Freelancer."
];
let index = 0;
const textElement = document.getElementById("animated-text");

function typeWriter() {
  let text = texts[index];
  let typeIndex = 0;

  const typing = setInterval(() => {
    if (typeIndex < text.length) {
      textElement.innerHTML += text[typeIndex];
      typeIndex++;
    } else {
      clearInterval(typing);
      setTimeout(() => deleteText(text), 1500);
    }
  }, 100);
}

function deleteText(text) {
  let deleteIndex = text.length;

  const deleting = setInterval(() => {
    if (deleteIndex > 0) {
      textElement.innerHTML = text.substring(0, deleteIndex - 1);
      deleteIndex--;
    } else {
      clearInterval(deleting);
      index = (index + 1) % texts.length;
      setTimeout(typeWriter, 500);
    }
  }, 50);
}

setTimeout(typeWriter, 1000);
</script>
