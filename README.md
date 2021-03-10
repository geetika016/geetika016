```python
from typing import List

class GS():
    first_name: str = "geetika"
    last_name: str = "sharma"
    pronouns: List[str] = ["she","her"]
    work_where: str = "Canadian Food Inspection Agency, Ottawa 🇨🇦"
    work_what: str = "Data Scientist | AI Engineer "
    univ: str = "Carleton University"
    
    
    mentor: List[str] = ["Technovation Canada", "Technolgap"]
    knowledge_base: List[str] = ["Mentoring","Machine Learning",
                                  "Deep Learning(DL)","Full Stack Development",
                                  "End-to-End ML Pipelines in Azure"]
    current_side_project: str = "my Website using Gatsby and GraphQL"
    research_interest: str="Software Engineering and DL"
    hobbies : List[str] = ["Reading","Hiking","Illustrating","F1","⚽️","🏀","⛷"]


    @classmethod
    def helloWorld(cls):
        print(f"Hi there 👋, I'm {cls.first_name.capitalize()} 👩🏻‍💻.")
        print(f"I work as a {cls.work_what} at the {cls.work_where} .")
        print(f"I am also a CS Research Assistant at {cls.univ} working at the intersection of {cls.research_interest}.")
        print(f"🔭 I’m currently building {cls.current_side_project}")
        print(f"🌱 Ask me about: {', '.join(cls.knowledge_base)}")
        print(f"⏳ How I spend my free time : {', '.join(cls.hobbies)}")

GS.helloWorld()


>>> GS.helloWorld()
Hi there 👋, I'm Geetika 👩🏻‍💻.
I work as a Data Scientist | AI Engineer  at the Canadian Food Inspection Agency, Ottawa 🇨🇦 .
I am also a CS Research Assistant at Carleton University working at the intersection of Software Engineering and DL.
🔭 I’m currently building my Website using Gatsby and GraphQL
🌱 Ask me about: Mentoring, Machine Learning, Deep Learning, Full Stack Development, End-to-End ML Pipelines in Azure
⏳ How I spend my free time : Reading, Hiking, Illustrating, F1, ⚽️, 🏀, ⛷

