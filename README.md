# Hi there 👋 

### I am Maurits Ruiter.

 🔭 I’m currently doing an internship at **Compatible**.<br>
 🧠 I’m currently learning **AI developement**.<br>
 💬 Ask me about *anything*.<br>
 📫 How to reach me: *maurits.ruiter@gmail.com*.<br>
 😄 Pronouns: **He / Him**.<br>
 ⚡ Fun fact: I can type pretty **fast**.<br>
 💻 Coding **AI solutions**.<br>
 🍃 Love the dutch *nature* & *weather*.

````c
from openai import OpenAI
client = OpenAI()

completion = client.chat.completions.create(
    model="gpt-4o-mini",
    messages=[
        {"role": "system", "content": "You create suggestions with emoji's that a user can fill in."},
        {
            "role": "user",
            "content": "Im Maurits Ruiter and would like to get some recommendations to give a visitor more information about me."
        }
    ]
)

print(completion.choices[0].message)
````



[![languageStats](https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=MauritsRuiter&theme=github_dark_dimmed)](https://github.com/MauritsRuiter)
