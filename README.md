<img src="./headerPic.png" alt="name banner" />

## Language, Tools, Skills 🛠

<div align="center">
<img src="https://img.shields.io/badge/Java-Programming-orange?style=flat&logo=java" />
<img src="https://img.shields.io/badge/C%23-Developer-blue?style=flat&logo=c-sharp" />
<img src="https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white" />
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
<img src="https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white" />
<img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" />
<img src="https://img.shields.io/badge/bitbucket-%230047B3.svg?style=for-the-badge&logo=bitbucket&logoColor=white" />
<img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" />
<img src="https://img.shields.io/badge/mysql-%2300000f.svg?style=for-the-badge&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="html" />
<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="css" />
<img src="https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-407AFC?style=for-the-badge&logo=icloud&logoColor=white" alt="sql" />
<img src="https://img.shields.io/badge/postgresql-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="postgresql" />
<img src="https://img.shields.io/badge/sqlite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" />
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="github" />
<img src="https://img.shields.io/badge/vs%20code-007ACC?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" alt="vs code" />
<img src="https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=for-the-badge&logo=windows-terminal&logoColor=white" alt="terminal" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
<img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="bootstrap" />
<img src="https://img.shields.io/badge/jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="jira" />
<img src="https://img.shields.io/badge/confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=white" alt="confluence" />
</div>

---

<p align="left">

    class Person:

    def__init__(self, given_name, family_name, birth_date, birth_place, employer):

    self.given_name = given_name
            self.family_name = family_name
            self.birth_date = birth_date
            self.location = birth_place
            self.employer = employer
            self.age = self._get_age()
            self.curr_location = self._get_current_location()

    def _get_age(self):
            b_date = datetime.strptime(self.birth_date, '%m/%d/%Y')
            my_age = ((datetime.today() - b_date).days/365)
            return int(my_age)

    def _get_current_location(self):
            resp_ip = requests.get('https://api64.ipify.org?format=json').json()["ip"]
            resp_local_data = requests.get(f'https://ipapi.co/{resp_ip}/json/').json()
            city, region, country = tuple([resp_local_data.get(key) for key in ["city",
                                                                                "region",
                                                                                "country"]])

    return f"{city}, {region}, {country}"
    its_me = Person("Ryan", "Muir", "09/06/1988", "St. Louis, MO", "Lumeris")

</p>

---

### GitHub Stats 📈

<div align="center">
  <table width="100%">
    <tbody>
      <tr>
        <td width="50%" style="border: none !important;">
        <div align="center" width="100%">
          <a href="https://github.com/ramuir">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ramuir&hide=ruby&layout=compact&hide_border=true&langs_count=6" alt="Ryans's Language Stats" vertical-align="middle"/>
          </a>
        </div>
        </td>
        <td width="50%" style="border: none !important;">
        <div align="center" width="100%">
          <a href="https://github.com/ramuir">
            <img src="https://github-readme-stats.vercel.app/api?username=ramuir&show_icons=true&hide=stars&hide_border=true" alt="Ryan's GitHub Stats" vertical-align="middle"/>
          </a>
        </div>
        </td>
      </tr>
    </tbody>
  <table>
<div>

---

<div align='center'>

![](https://komarev.com/ghpvc/?username=ramuir&label=Profile+Views)

</div>
