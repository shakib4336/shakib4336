<!-- Gradient color header -->
<h1 align="center">
  <span style="background: linear-gradient(90deg, #00DBDE 0%, #FC00FF 100%);
               -webkit-background-clip: text;
               -webkit-text-fill-color: transparent;
               font-weight: 900;">
    Hi 👋, I'm Md Nazmus Shakib Mun
  </span>
</h1>

<!-- Animated typing effect -->
<p align="center" style="font-size: 20px; font-weight: 600; margin-top: -10px; margin-bottom: 40px;">
  <b><i>
    <span id="typed-text"></span><span class="cursor">|</span>
  </i></b>
</p>

<!-- Side by side images with shadow and rounded corners -->
<table width="100%" style="margin-bottom: 30px;">
  <tr>
    <td align="left" width="50%">
      <img 
        src="https://media.licdn.com/dms/image/v2/D4D12AQHGG4J6b6OmyQ/article-cover_image-shrink_720_1280/article-cover_image-shrink_720_1280/0/1709674937953?e=2147483647&v=beta&t=tgAv-o8rHSfUFWzGQT2nCOfZkc2Hdluh-9xTR3Opu-w" 
        alt="Left Image" 
        width="380" 
        style="border-radius: 20px; box-shadow: 0px 10px 30px rgba(252, 0, 255, 0.4);" 
      />
    </td>
    <td align="right" width="50%">
      <img 
        src="https://miro.medium.com/v2/resize:fit:1400/1*qLTMkJzldptJh5W9JGQWVw.gif" 
        alt="Right Image" 
        width="380" 
        style="border-radius: 20px; box-shadow: 0px 10px 30px rgba(0, 219, 222, 0.4);" 
      />
    </td>
  </tr>
</table>

<!-- Profile views badge -->
<p align="center"> 
  <img src="https://komarev.com/ghpvc/?username=shakib4336&label=Profile%20views&color=7D5FFF&style=for-the-badge" alt="shakib4336" /> 
</p>

<!-- Project and contact -->
<p align="center" style="font-size: 18px; font-weight: 500; margin-bottom: 25px;">
  🔭 Currently working on <strong>Computer Science and Engineering</strong><br>
  <a href="https://github.com/shakib4336/Darmatory/blob/main/project.c" target="_blank" style="color: #7D5FFF; font-weight: 700; text-decoration: none;">
    Darmatory Project
  </a><br>
  📫 Reach me at <b>nazmusshakib195@gmail.com</b>
</p>

<!-- Social badges -->
<p align="center" style="margin-bottom: 40px;">
  <a href="https://fb.com/nazmussakib.moon.1" target="_blank" style="margin-right: 15px;">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook"/>
  </a>
  <a href="https://instagram.com/nazmus_shakib2108" target="_blank" style="margin-right: 15px;">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/>
  </a>
</p>

<!-- Languages and Tools -->
<p align="center" style="margin-bottom: 40px;">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C" style="margin-right:8px;"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" style="margin-right:8px;"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" style="margin-right:8px;"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" style="margin-right:8px;"/>
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" style="margin-right:8px;"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" style="margin-right:8px;"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" style="margin-right:8px;"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" style="margin-right:8px;"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" style="margin-right:8px;"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" style="margin-right:8px;"/>
</p>

<!-- GitHub stats -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=shakib4336&show_icons=true&theme=radical" alt="GitHub Stats" style="margin-right: 25px;"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shakib4336&layout=compact&theme=radical" alt="Top Languages" />
</p>

<p align="center" style="margin-top: 40px;">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=shakib4336&theme=radical" alt="GitHub Streak" />
</p>

<!-- Typing animation script -->
<script>
  const typedTextSpan = document.getElementById('typed-text');
  const textArray = ['Developer', 'DevOps Enthusiast', 'Coder', 'Tech Lover'];
  const typingDelay = 150;
  const erasingDelay = 100;
  const newTextDelay = 2000; // Delay between current and next text
  let textArrayIndex = 0;
  let charIndex = 0;

  function type() {
    if (charIndex < textArray[textArrayIndex].length) {
      typedTextSpan.textContent += textArray[textArrayIndex].charAt(charIndex);
      charIndex++;
      setTimeout(type, typingDelay);
    } else {
      setTimeout(erase, newTextDelay);
    }
  }

  function erase() {
    if (charIndex > 0) {
      typedTextSpan.textContent = textArray[textArrayIndex].substring(0, charIndex - 1);
      charIndex--;
      setTimeout(erase, erasingDelay);
    } else {
      textArrayIndex++;
      if (textArrayIndex >= textArray.length) textArrayIndex = 0;
      setTimeout(type, typingDelay + 1100);
    }
  }

  document.addEventListener('DOMContentLoaded', function () {
    if(textArray.length) setTimeout(type, newTextDelay + 250);
  });
</script>
