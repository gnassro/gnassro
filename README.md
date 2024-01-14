<h2> Hi, I'm Nasreddine Elghozi! <img src="https://media.giphy.com/media/mGcNjsfWAjY5AEZNw6/giphy.gif" width="50"></h2>
<p><em>Senior Flutter Developer<img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> 
</em></p>

[![Twitter: gnassro](https://img.shields.io/twitter/follow/gnassro?style=social)](https://twitter.com/gnassro)
[![Linkedin: gnassro](https://img.shields.io/badge/-gnassro?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/gnassro/)](https://www.linkedin.com/in/gnassro/)
[![GitHub gnassro](https://img.shields.io/github/followers/gnassro?label=follow&style=social)](https://github.com/gnassro)

![Gnassro's github stats](https://github-readme-stats-gnassro.vercel.app/api?username=gnassro&layout=compact&show_icons=true&theme=radical&include_all_commits=true&count_private=true&hide_border=true) ![Top Langs](https://github-readme-stats-gnassro.vercel.app/api/top-langs/?username=gnassro&layout=compact&show_icons=true&theme=radical&hide_border=true&langs_count=8&hide=swift,kotlin,Ruby,Objective-C)



### <img src="https://media.giphy.com/media/VgCDAzcKvsR6OM0uWg/giphy.gif" width="50"> A little more about me...  
---
```Dart
enum SkillLevel {
  beginner,
  intermediate,
  advanced,
  expert,
}

mixin AdditionalFunctionality {
  List<String> hobbies();
}

class AboutMe with AdditionalFunctionality {
  final String currentPosition;
  final Map<String, SkillLevel> skills;
  final List<String> hobbies;

  AboutMe({
    required this.currentPosition,
    required this.skills,
    required this.hobbies
  });

  void knowMe() {
    print("Current Position: $currentPosition");
    print("Skills:");
    skills.forEach((skill, level) {
      print("$skill: $level");
    });
    print(hobbies());
  }

  @override
  List<String> hobbies() {
    return hobbies;
  }
}

void main() {
  AboutMe aboutMe = AboutMe(
    currentPosition: "Senior Flutter Developer",
    skills:  {
        "Flutter": SkillLevel.advanced,
        "Dart": SkillLevel.advanced,
        "Ubuntu": SkillLevel.advanced,
        "Shell": SkillLevel.advanced,
        "Networking": SkillLevel.intermediate,
        "Java": SkillLevel.intermediate,
        "PHP": SkillLevel.intermediate
    },
    hobbies: [
        "Football",
        "Chess",
        "Watching The lord of the rings every month"
    ]
  );

  aboutMe.knowMe();
}
```
---
