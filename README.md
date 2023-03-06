## Hi there 👋

### IGAL KEJSEFMAN (He/Him)
Economist specialized in data modeling and project management, with programming skills, experience in machine learning and
algorithms. I apply my analytical abilities and domain knowledge to help organizations make data-driven decisions. With a curious
personality and leadership skills, I am seeking challenging opportunities in the field of Data Science.


![](https://github.com/igalkej/igalkej/blob/main/aboutme2023.png#gh-light-mode-only)
![](https://github.com/igalkej/igalkej/blob/main/aboutme2023_dark.png#gh-dark-mode-only)
Source: check out my code 👇<br>

🤖 [Read my resume here](https://drive.google.com/file/d/1opqb7EmYYC9HfrJel41Y2a9SfPq1vwUo/view?usp=sharing)<br>

📫 How to reach me:<br>
igalkej[a]gmail.com<br>
[Linkedin](https://www.linkedin.com/in/igal-kejsefman-88791a1a0/)<br>
[Academia.edu](https://conicet-ar.academia.edu/IgalKejsefman)<br>

```python 
from matplotlib import pyplot as plt
from matplotlib_venn import venn3, venn3_circles, venn3_unweighted
import numpy as np

#plt.style.use('dark_background')
plt.style.use('seaborn')
params = {'figure.figsize': (20, 25),
              'axes.labelsize': 20,
              'axes.titlesize': 30,
              'xtick.labelsize': 20,
              'ytick.labelsize': 20}
plt.rcParams.update(params)

v = venn3_unweighted(subsets=(1, 1, 1, 1, 1, 1, 1),
             set_labels=("", "", ""),
             subset_areas=(5,3,1,1,1,1,1))

v.get_label_by_id('100').set_text("Economics & \n Reaserch")
v.get_label_by_id('010').set_text("Project \n Manager")
v.get_label_by_id('001').set_text("Data \n Scientist")
v.get_label_by_id('101').set_text("")
v.get_label_by_id('011').set_text("")
v.get_label_by_id('110').set_text("")
v.get_label_by_id('111').set_text("Me")

about =  "Buenos Aires, Argentina (UTC-3)\n\nigalkej@gmail.com\n\n(+54)911-3262-5462"
data_sc = "Professional experience:\n>Data Scientist (DIC 2020 - NOV 2022)\n Center for Production Studies (CEPXXI), 
        Ministry of Economy\n Provided strategic assistance for data-driven decision making\n by combining domain 
        knowledge, econometrics, and machine\n learning to analyze databases, describe and predict patterns,\n trends,
        and groups.\n\nSkills:\n•Python, R, SQL, MongoDB,SageMaker (AWS), Gis\n•Machine Learning | Automation | Optimization | Debugging |\n  LaTex | Markdown | Github |\n•Reports, indicators, and dashboards for information visualization.\n•Efficient approach to complex problemsolving\n•Handling large volumes of data\n\nCredentials:\n>Master degree in Data Mining & Knowledge Discovery\n (2021-CURRENT)\n University of Buenos Aires\n>Technician in Electronic (1998-2003)\n ORT High School"
e_and_r = "Professional experience:\n
           >Reasercher (APR 2015- CURRENT)\n National Scientific and Technical Research Council (CONICET)\n
           I have written numerous scientific articles in prestigious journals, book chapters, newspaper articles, and 
           a book. My research is interdisciplinary.\n\n
           >University professor (2005-2021)\n UBA, UNGS, UNM, UNLZ\n\n
           Skills:\n
           •Business intelligence\n•Value chain studies\n•Macroeconomic analysis\n
           •Construction of new methodologies and analysis tools\n
           •Critical thinking\n•Learning capacity\n
           •International trade databases\n\n
           Credentials:
           \n>Bachelor's degree in Economics (2010)\n University of Buenos Aires\n>Master's degree in Latin American
           Studies (2017)\n University of Buenos Aires\n>PhD in Social Sciences (2019)\nUniversity of Buenos Aires\n
           >Doctoral scholarchip (2015-2019)\n National Scientific and Technical Research Council (CONICET)\n
           >Postdoc scholarchip (2019-2021)\n National Scientific and Technical Research Council (CONICET)"

pm="Professional experience:\n
    >Team leader (DIC 2020- NOV 2022)\n
    Center for Production Studies (CEPXXI), Ministry of Economy\n
    Led a team of 10 analysts that prepared reports and provided\n information to assist decisions that work in
    the real world.\n\n
    Skills:\n
    Gantt | Trello | Google suite | Slack\n
    •Decision making at critical moments.\n
    •Promotion and stimulation of capacities of team members\n
    •Organizational and planning capacity of the tasks.\n
    •Teamwork, delegation of tasks and excellent interpersonal treatment\n\n
    Internships and volunteering:\n
    >Counselor (2010- 2012)\n University of Buenos Aires\n Preparation of projects and budgets. Strategic negotiation\n
    >President (2012-2013)\n Student union of University of Buenos Aires\n Coordination of multiple work teams,
    management of cultural events"



for text in v.subset_labels:
    text.set_fontsize(14)

plt.annotate(about, xy=v.get_label_by_id('111').get_position() - np.array([0, 0.0]), xytext=(-100,450),
             ha='left', textcoords='offset points', bbox=dict(boxstyle='round,pad=0.5', fc='gray', alpha=0.1),
             arrowprops=dict(arrowstyle='->', connectionstyle='arc3,rad=0.5',color='gray'),fontsize=14)
plt.annotate(e_and_r, xy=v.get_label_by_id('100').get_position() - np.array([0, 0.05]), xytext=(-300,-800), ha='left',              textcoords='offset points', bbox=dict(boxstyle='round,pad=0.5', fc='gray', alpha=0.1),arrowprops=dict                  (arrowstyle='->', connectionstyle='arc3,rad=0.5',color='gray'),fontsize=14)
plt.annotate(pm, xy=v.get_label_by_id('010').get_position() - np.array([0, 0.05]), xytext=(0,-600),
             ha='left', textcoords='offset points', bbox=dict(boxstyle='round,pad=0.5', fc='gray', alpha=0.1),
             arrowprops=dict(arrowstyle='->', connectionstyle='arc3,rad=0.5',color='gray'),fontsize=14)
plt.annotate(data_sc, xy=v.get_label_by_id('001').get_position() - np.array([0, 0.05]), xytext=(-200,-400),
             ha='left', textcoords='offset points', bbox=dict(boxstyle='round,pad=0.5', fc='gray', alpha=0.1),
             arrowprops=dict(arrowstyle='->', connectionstyle='arc3,rad=0.5',color='gray'),fontsize=14)
plt.show()
```



