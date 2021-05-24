>#  ⚡ ELEKTRA⚡
**An ML powered Electricity Outage prediction tool**

[CHECK LIVE](https://elecktra.uc.r.appspot.com)

### Check out the [YouTube video](https://www.youtube.com/watch?v=NODY3Kwz8FU&feature=youtu.be)

<img src="https://i.ibb.co/yk5gRVB/ew1.png" alt="ew1" border="0"> <img src="https://i.ibb.co/92CbKnQ/resp.png" alt="resp" border="0">

[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
![Maintenance](https://img.shields.io/maintenance/yes/2021)

[![Issues](https://img.shields.io/github/issues/khannakshat7/Elektra)](https://github.com/khannakshat7/Elektra/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/khannakshat7/Elektra)](https://github.com/khannakshat7/Elektra)
[![Pull Requests](https://img.shields.io/github/issues-pr-closed/khannakshat7/Elektra)](https://github.com/khannakshat7/Elektra)

[![Forks](https://img.shields.io/github/forks/khannakshat7/Elektra?style=social)](https://github.com/khannakshat7/Elektra) 
[![Stars](https://img.shields.io/github/stars/khannakshat7/Elektra?style=social)](https://github.com/khannakshat7/Elektra) 
[![Watchers](https://img.shields.io/github/watchers/khannakshat7/Elektra?style=social)](https://github.com/khannakshat7/Elektra)

# Features
- Real-time monitoring with map
- Admin / User Dashboard
- Analysis of different areas in a city
- Analysis of previous data of a city
- Announcements by Electricity Board
- Public Feedback


# Tech Stack Used
- HTML5
- CSS3
- Bootstrap4
- JavaScript
- JQuery
- Django
- Sqlite
- Google Maps API
- Google Cloud Platform

# Contribution Guideline 💻:

You may go through these guidelines and contribute accordingly:

- Make sure you do not copy codes from external sources because that work will not be considered. **Plagiarism is strictly not allowed.** 
- You can only work on issues that you have been assigned to you.
- If you want to contribute for an existing code, we prefer that you create an issue before making a PR and link your PR to that issue.
- If you have modified/added code work, make sure that it is working fine before submitting.
- Strictly use camel case in your functions and classes.
- Do not update the [README.md](README.md).

# How to fork and run Elektra on your local machine 💻:

1. Download and install Python
2. Download and install Git.
3. Fork the Repository.
4. Clone the repository to your local machine 
```bash
git clone https://github.com/<your-github-username>/Elektra.git
```

5. Change directory to Elektra
```bash
cd Elektra
```

6. Install virtualenv
```bash
pip3 install virtualenv
```

7. Create a virtual environment
```bash
virtualenv env -p python
```  
8. Activate the environment
  * For linux 
  ```bash
  source env/bin/activate
  ```

  * For windows (Windows PowerShell)
  ```powershell
  env\Scripts\activate
  ```

9. Install the requirements:
```bash
pip install -r requirements.txt
```

10. Go to [Elektra/settings.py](Elecktra/settings.py "link") and change the username and password of databases as per your own local mysql database. Here is a reference below to where you can find the code:
  ![Screenshot (129)](https://user-images.githubusercontent.com/71708571/110449895-aa212900-80e8-11eb-9469-84da185b9c13.png)
  
  <p>After changing the username and password, create a database named `Elektra` and then continue on to following the steps given below.<p>

11. Make migrations
```bash
python manage.py makemigrations
```

12. Migrate the changes to the database
```bash 
python manage.py migrate
```

13. Create admin 
```bash
python manage.py createsuperuser
```

14. Run the server
```bash
python manage.py runserver
```

15. Open any web browser and then paste the server address to see the webpage working on your local machine

<p>Happy Coding 😁</p>


### Deployment ✔️Google Cloud Platform

# Maintainers 👦👧

<table>
  <tbody><tr>
    <td align="center"><a href="https://github.com/khannakshat7"><img alt="" src="https://avatars.githubusercontent.com/khannakshat7" width="100px;"><br><sub><b>
Akshat Khanna </b></sub></a><br><a href="https://github.com/khannakshat7/Elektra/commits?author=khannakshat7" title="Code">💻 🖋</a></td></a></td>
    <td align="center"><a href="https://github.com/CodesbyUnnati"><img alt="" src="https://avatars.githubusercontent.com/CodesbyUnnati" width="100px;"><br><sub><b>Unnati Mishra</b></sub></a><br><a href="https://github.com/khannakshat7/Elektra/commits?author=CodesbyUnnati" title="Code">💻 🖋</a></td> </a></td>
  </tr>
</tbody></table>

# Contributors:
## Credit goes to these people:✨
<table>
	<tr>
		<td>
			<a href="https://github.com/khannakshat7/Elektra/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=khannakshat7/Elektra" />
</a>
		</td>
	</tr>
</table>

# Code of Conduct
You can find our Code of Conduct [here](https://github.com/khannakshat7/Elektra/blob/master/CODE_OF_CONDUCT.md).

# License

This project follows the [MIT License](https://choosealicense.com/licenses/mit/).

[![forthebadge](https://forthebadge.com/images/badges/built-by-developers.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/open-source.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/uses-git.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
