# Intelligent_Job_Match
Setup & Installation:
1. git clone https://github.com/likhithakodumuri/Intelligent_Job_Match.git
2. virtualenv myenv
3. myenv\scripts\activate
4. cd App
5. pip install -r requirements.txt
6. python -m spacy download en_core_web_sm or manual install tar.gz file
7. After installation is finished create a Database 'cv'
8. change user credentials inside 'App.py'
9. connection = pymysql.connect(host='localhost',user='root',password='',db='cv')
10. Go to "myenv\Lib\site-packages\pyresparser" folder and replace the 'resume_parser.py' with 'resume_parser.py' provided in repository
11. streamlit run App.py

Have these things installed to make your process smooth:
1. Python (3.9.12) https://www.python.org/downloads/release/python-3912/
2. MySQL https://www.mysql.com/downloads/
3. Visual Studio Code (Prefered Code Editor) https://code.visualstudio.com/Download
4. Visual Studio build tools for C++ https://aka.ms/vs/17/release/vs_BuildTools.exe
