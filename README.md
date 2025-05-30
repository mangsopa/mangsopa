## Hi!👋 My Name is Sofa

A young person who likes doing things behind the scenes and learning new things. create and share projects about web and mobile technology! 

```php

<?php

namespace AshSofa;

class About extends Me
{
    function __about()
    {
        $itsMe = Me::where('name', 'Mangsopa')
                   ->where('country', 'Indonesia')
                   ->orderBy('name', 'asc')
                   ->orderBy('country', 'desc')
                   ->get();

        return view('welcome', compact('itsMe'));
    }

    function getDailyKnowledge()
    {
        $Knowledge = [
            Laravel::class,
            CodeIgniter::class,
            JavaScript::class
        ];
    }

    function getFutureGoal()
    {
        echo "To contribute to open source.";
    }
}
```

<h2 align="center">⚡ Stats ⚡</h2>
<br>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=mangsopa&locale=en&mode=daily&theme=graywhite&hide_border=true&border_radius=5&date_format=M%20j%5B,%20Y%5D" height="130" alt="streak graph"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=mangsopa&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=graywhite&hide_border=false" height="130" alt="languages graph"  />
</div>
<br>

<h2 align="center"> 🌟 My Skills </h2>
<div align="center">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="60" alt="javascript logo" title="javascript" />
      <img width="17" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="60" alt="react logo" title="React Native"  />
      <img width="17" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original-wordmark.svg" height="60" alt="tailwindcss logo" title="tailwinds"  />
      <img width="17" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" height="60" alt="php logo" title="php" />
      <img width="17" />
      <img src="https://cdn.worldvectorlogo.com/logos/laravel-2.svg" height="60" alt="laravel logo" title="laravel"  />
      <img width="17" />
      <img src="https://cdn.worldvectorlogo.com/logos/codeigniter.svg" height="60" alt="code igniter logo" title="code igniter"  />
      <img width="17" />
     <img src="https://cdn.worldvectorlogo.com/logos/express-109.svg" height="60" alt="express js logo" title="express js"  />
      <img width="17" />
   
</div>

<!-- ## Reach me on

<div align="center">
  <a href="https://www.instagram.com/faaa_fs" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="33" alt="instagram logo"  />
  </a>
    <a href="https://discord.com/channels/@owesofa" target="_blank">
  <img src="https://img.shields.io/static/v1?message=Discord&logo=discord&label=&color=7289DA&logoColor=white&labelColor=&style=for-the-badge" height="33" alt="discord logo"  />
  </a>

  <a href="https://mail.google.com/mail/u/0/?view=cm&tf=1&fs=1&to=whoamiii336@gmail.com" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="33" alt="gmail logo"  />
  </a>
  <a href="https://www.linkedin.com/in/ahmadsofa/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="33" alt="linkedin logo"  />
  </a>
  <a href="https://www.hackerrank.com/profile/sofa_ramadhan168" target="_blank">
    <img src="https://img.shields.io/static/v1?message=HackerRank&logo=hackerrank&label=&color=2EC866&logoColor=white&labelColor=&style=for-the-badge" height="33" alt="hackerrank logo"  />
  </a>
  <a href="https://www.facebook.com/sofarafs" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Facebook&logo=facebook&label=&color=1877F2&logoColor=white&labelColor=&style=for-the-badge" height="33" alt="facebook logo"  />
  </a>
</div>

<!-- ## 📊 GitHub Stats & Streak
 <p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mangsopa&theme=radical" alt="GitHub Streak" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=mangsopa&layout=compact&theme=radical" alt="Top Languages" />
</p>


