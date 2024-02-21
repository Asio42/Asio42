### Hi there 👋

<!--
**Asio42/Asio42** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
# -*- coding: utf-8 -*-
# Created on Thu Feb  23 19:58:13 2023

class ITStudent():
    def __init__(self):
      self.name = "Evandro Rhari"
      self.spokenLanguages = ["pt_BR", "en"]
      self.code = ["Cpp", "Python", "HTML", "CSS"]
      self.school = "CEFET/RJ"
      
    def learn(self, *learning):
      for subject in learning:
        self.code.append(subject)
      
    def greet(self):
      print("Welcome to my profile. Make yourself at home, and oh please excuse the mess.") 
      

eRhari = ITStudent()
eRhari.greet()
eRhari.learn("PHP", "JavaScript")
