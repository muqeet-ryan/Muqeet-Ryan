<!--
  QUICK MAP (top to bottom): header > skills > projects > certs > leetcode > contact > end cursor
  LAYOUT RULES: every block is 800px wide, every table uses cellpadding 10, one <br/> between sections.
  COLORS: green 00ff41 = prompt/accent, blue 58a6ff = path, 161b22 = badge background (matches terminal).
  PLACEHOLDERS (Ctrl+H, replace all): GH_USERNAME, REPO_NAME, PROJECT_NAME, DESCRIPTION, TECH,
    CERTIFICATION_NAME, ISSUING_ORGANIZATION, YEAR, LC_USERNAME, LINKEDIN_USERNAME, YOUR_PORTFOLIO_URL
  WHY SVG PROMPTS: GitHub strips colors from text, so only images can be green. Everything else is real text.
  NOTE: column widths below add up to 800 so tables line up with the SVG prompts. Keep that total.
-->

<!-- HEADER: animated terminal window -->
<img src="./assets/newHeader.svg" alt="github@portfolio:~$ whoami → github" width="800"/>

<br/>

<!-- SKILLS: label column 130 + badges column 670 = 800. To add a skill, copy one img line. -->
<img src="./assets/prompt-skills.svg" alt="github@portfolio:~$ ls ~/skills" width="800"/>

<table width="800" cellpadding="10" cellspacing="0">
<tr>
<td width="130" valign="middle"><code>languages</code></td>
<td width="670" valign="middle">
<img src="https://img.shields.io/badge/C%23-161b22?style=flat-square&logo=dotnet&logoColor=512BD4" alt="C#"/>
<img src="https://img.shields.io/badge/JavaScript-161b22?style=flat-square&logo=javascript&logoColor=F7DF1E" alt="JavaScript"/>
</td>
</tr>
<tr>
<td valign="middle"><code>frontend</code></td>
<td valign="middle">
<img src="https://img.shields.io/badge/React.js-161b22?style=flat-square&logo=react&logoColor=61DAFB" alt="React.js"/>
<img src="https://img.shields.io/badge/Tailwind_CSS-161b22?style=flat-square&logo=tailwindcss&logoColor=06B6D4" alt="Tailwind CSS"/>
</td>
</tr>
<tr>
<td valign="middle"><code>backend</code></td>
<td valign="middle">
<img src="https://img.shields.io/badge/ASP.NET_Core-161b22?style=flat-square&logo=dotnet&logoColor=512BD4" alt="ASP.NET Core"/>
<img src="https://img.shields.io/badge/Express.js-161b22?style=flat-square&logo=express&logoColor=white" alt="Express.js"/>
<img src="https://img.shields.io/badge/SQL_Server-161b22?style=flat-square&logo=microsoftsqlserver&logoColor=CC2927" alt="SQL Server"/>
<img src="https://img.shields.io/badge/MongoDB-161b22?style=flat-square&logo=mongodb&logoColor=47A248" alt="MongoDB"/>
</td>
</tr>
<tr>
<td valign="middle"><code>testing</code></td>
<td valign="middle">
<img src="https://img.shields.io/badge/Playwright-161b22?style=flat-square&logo=playwright&logoColor=2EAD33" alt="Playwright"/>
<img src="https://img.shields.io/badge/xUnit-161b22?style=flat-square&logo=dotnet&logoColor=512BD4" alt="xUnit"/>
<img src="https://img.shields.io/badge/Postman-161b22?style=flat-square&logo=postman&logoColor=FF6C37" alt="Postman"/>
<img src="https://img.shields.io/badge/k6-161b22?style=flat-square&logo=k6&logoColor=7D64FF" alt="k6"/>
</td>
</tr>
<tr>
<td valign="middle"><code>devOps & deployment</code></td>
<td valign="middle">
<img src="https://img.shields.io/badge/Git-161b22?style=flat-square&logo=git&logoColor=F05032" alt="Git"/>
<img src="https://img.shields.io/badge/GitHub-161b22?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
<img src="https://img.shields.io/badge/Linux-161b22?style=flat-square&logo=linux&logoColor=FCC624" alt="Linux"/>
<img src="https://img.shields.io/badge/Docker-161b22?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker"/>
<img src="https://img.shields.io/badge/GitHub_Actions_CI%2FCD-161b22?style=flat-square&logo=githubactions&logoColor=2088FF" alt="GitHub Actions CI/CD"/>
<img src="https://img.shields.io/badge/Azure-161b22?style=flat-square&logo=microsoftazure&logoColor=0078D4" alt="Azure"/>
</td>
</tr>
</table>

<br/>

<!-- PROJECTS: columns # 60 + project 200 + description 340 + tech 200 = 800. Copy a tr block to add a row. -->

<!-- 
<img src="./assets/prompt-projects.svg" alt="github@portfolio:~$ ls -l ~/projects --pinned" width="800"/>

<table width="800" cellpadding="10" cellspacing="0">
<tr>
<th width="60" align="center"><code>#</code></th>
<th width="200" align="left"><code>project</code></th>
<th width="340" align="left"><code>description</code></th>
<th width="200" align="left"><code>stack</code></th>
</tr>
<tr>
<td align="center" valign="middle">1</td>
<td valign="middle"><b><a href="https://github.com/GH_USERNAME/REPO_NAME">PROJECT_NAME</a></b></td>
<td valign="middle">DESCRIPTION</td>
<td valign="middle"><code>TECH</code> <code>TECH</code></td>
</tr>
<tr>
<td align="center" valign="middle">2</td>
<td valign="middle"><b><a href="https://github.com/GH_USERNAME/REPO_NAME">PROJECT_NAME</a></b></td>
<td valign="middle">DESCRIPTION</td>
<td valign="middle"><code>TECH</code> <code>TECH</code></td>
</tr>
<tr>
<td align="center" valign="middle">3</td>
<td valign="middle"><b><a href="https://github.com/GH_USERNAME/REPO_NAME">PROJECT_NAME</a></b></td>
<td valign="middle">DESCRIPTION</td>
<td valign="middle"><code>TECH</code> <code>TECH</code></td>
</tr>
</table>
 -->
<br/>

<!-- CERTS: columns # 60 + certification 340 + issuer 250 + year 150 = 800. Only list earned ones. -->

<img src="./assets/prompt-certs.svg" alt="github@portfolio:~$ cat ~/certifications.txt" width="800"/>

<table width="800" cellpadding="10" cellspacing="0">
<tr>
<th width="60" align="center"><code>#</code></th>
<th width="340" align="left"><code>certification</code></th>
<th width="250" align="left"><code>issuer</code></th>
<th width="150" align="left"><code>year</code></th>
</tr>
<tr>
<td align="center" valign="middle">1</td>
<td valign="middle">AZ</td>
<td valign="middle">MS</td>
<td valign="middle">202</td>
</tr>
<tr>
<td align="center" valign="middle">2</td>
<td valign="middle">ASP</td>
<td valign="middle">MS</td>
<td valign="middle">202</td>
</tr>
<tr>
<td align="center" valign="middle">3</td>
<td valign="middle">Foundational C# with Microsoft</td>
<td valign="middle">freeCodeCamp</td>
<td valign="middle">2026</td>
</tr>
</table>


<br/>


<!-- LEETCODE: LIVE STATS -->
<img src="./assets/prompt-leetcode.svg" alt="github@portfolio:~$ ./leetcode --stats" width="800"/>

<table width="800" cellpadding="10" cellspacing="0">
  <tr>
    <td valign="middle" width="130"><code>leetcode</code></td>
    <td valign="middle" width="670">
      <a href="https://leetcode.com/u/Muqeet_Ryan/">
        leetcode.com/u/Muqeet_Ryan ↗
      </a>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <a href="https://leetcode.com/u/Muqeet_Ryan/">
        <img
          src="https://leetcard.jacoblin.cool/Muqeet_Ryan?theme=dark&font=Fira%20Code&ext=heatmap&border=0&radius=8"
          alt="Muqeet Ryan LeetCode statistics"
          width="800"
        />
      </a>
    </td>
  </tr>
</table>


<br/>

<!-- CONTACT: three equal cells (267 + 266 + 267 = 800), badges centered so the row is symmetrical. Delete a cell to remove a link. -->
<img src="./assets/prompt-contact.svg" alt="github@portfolio:~$ ./contact.sh" width="800"/>

<table width="800" cellpadding="10" cellspacing="0">
<tr>
<td width="267" align="center" valign="middle"><a href="https://www.linkedin.com/in/muqeet-ryan/"><img src="https://img.shields.io/badge/LinkedIn-161b22?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn"/></a></td>
<td width="266" align="center" valign="middle"><a href="https://ryans-portfolio-gamma.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-161b22?style=for-the-badge&logo=firefoxbrowser&logoColor=00ff41" alt="Portfolio"/></a></td>
<td width="267" align="center" valign="middle"><a href="https://leetcode.com/u/Muqeet_Ryan/"><img src="https://img.shields.io/badge/LeetCode-161b22?style=for-the-badge&logo=leetcode&logoColor=FFA116" alt="LeetCode"/></a></td>
</tr>
</table>

<br/>

<!-- END: final prompt with blinking cursor -->
<img src="./assets/prompt-end.svg" alt="github@portfolio:~$" width="800"/>
