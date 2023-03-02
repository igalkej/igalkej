## Hi there 👋

### IGAL KEJSEFMAN (He/Him)
Economist specialized in data modeling and project management, with programming skills, experience in machine learning and
algorithms. I apply my analytical abilities and domain knowledge to help organizations make data-driven decisions. With a curious
personality and leadership skills, I am seeking challenging opportunities in the field of Data Science.


![](https://github.com/igalkej/igalkej/blob/main/aboutme2023tr1.png#gh-light-mode-only)
![](https://github.com/igalkej/igalkej/blob/main/aboutme2023tr1_dark.png#gh-dark-mode-only)
sorce: check out my code 👇


```python 
from matplotlib import pyplot as plt
from matplotlib_venn import venn3, venn3_circles, venn3_unweighted
import numpy as np

plt.style.use('seaborn')
params = {'figure.figsize': (20, 20),
              'axes.labelsize': 20,
              'axes.titlesize': 30,
              'xtick.labelsize': 20,
              'ytick.labelsize': 20}
plt.rcParams.update(params)

v = venn3_unweighted(subsets=(1, 1, 1, 1, 1, 1, 1),
             set_labels=("", "", ""),
             subset_areas=(5,3,1,1,1,1,1))

v.get_label_by_id('100').set_text("Economics & \n Reaserch")
v.get_label_by_id('010').set_text("Proyect \n Manager")
v.get_label_by_id('001').set_text("Data \n Scientist")
v.get_label_by_id('101').set_text("")
v.get_label_by_id('011').set_text("")
v.get_label_by_id('110').set_text("")
v.get_label_by_id('111').set_text("Me")

about =  "Buenos Aires, Argentina (UTC-3)\nigalkej@gmail.com\n(+54)911-3262-5462"
data_sc = "Data science:\n\nProfessional experience:\nData Scientist (DIC 2020 - NOV 2022)\nCenter for Production Studies (CEPXXI)Ministry of Economy"



for text in v.subset_labels:
    text.set_fontsize(14)

plt.annotate(about, xy=v.get_label_by_id('111').get_position() - np.array([0, 0.0]), xytext=(-50,400),
             ha='left', textcoords='offset points', bbox=dict(boxstyle='round,pad=0.5', fc='gray', alpha=0.1),
             arrowprops=dict(arrowstyle='->', connectionstyle='arc3,rad=0.5',color='gray'))
plt.annotate('PhD in Social Science', xy=v.get_label_by_id('100').get_position() - np.array([0, 0.05]), xytext=(-300,0),
             ha='center', textcoords='offset points', bbox=dict(boxstyle='round,pad=0.5', fc='gray', alpha=0.1),
             arrowprops=dict(arrowstyle='->', connectionstyle='arc3,rad=0.5',color='gray'))
plt.annotate('leading teams', xy=v.get_label_by_id('010').get_position() - np.array([0, 0.05]), xytext=(300,0),
             ha='center', textcoords='offset points', bbox=dict(boxstyle='round,pad=0.5', fc='gray', alpha=0.1),
             arrowprops=dict(arrowstyle='->', connectionstyle='arc3,rad=0.5',color='gray'))
plt.annotate(data_sc, xy=v.get_label_by_id('001').get_position() - np.array([0, 0.05]), xytext=(-70,-70),
             ha='center', textcoords='offset points', bbox=dict(boxstyle='round,pad=0.5', fc='gray', alpha=0.1),
             arrowprops=dict(arrowstyle='->', connectionstyle='arc3,rad=0.5',color='gray'))
plt.show()
```
Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me:
igalkej[a]gmail.com
https://www.linkedin.com/in/igal-kejsefman-88791a1a0/
https://conicet-ar.academia.edu/IgalKejsefman

