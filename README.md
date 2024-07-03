### Hello. (•◡•)/

<p> <img src="https://komarev.com/ghpvc/?username=Fulgur0" /> </p>

```cpp
#include <iostream>
#include <vector>
#include <string>

using namespace std;

class Project
{
 public:
  string project;
  string language;
  string description;
};

class AboutMe
{
 public:
  string nick = "Fulgur";
  int age = 18;
  string gender = "male";
  string about = "full stack developer student that enjoys breaking and fixing things.";
  string location = "Netherlands";
  vector<string> hobbies = { "Programming", "IRC", "Cycling" };
  vector<string> languages = { "C++", "PHP", "C#", "CSS", "HTML", "Python" };
  vector<string> os = { "Windows", "Qubes OS" };
  vector<string> timezone = { "UTC+2" };
  vector<Project> projects;

  void introduce() {
   cout << "Hello, my name is " << this->nick << ". I\'m from " << this->location << " and am " << this->age << " years old." << endl;
   cout << "I\'m a " << this->about << endl;
  }

};

int main() {
 Project p1;
 p1.project = "IRC Client";
 p1.language = "C++";
 p1.description = "An IRC client written in C++ using sockets";
 Project p2;
 p2.project = "Saturn Hosting";
 p2.language = "PHP";
 p2.description = "Saturn Hosting offering cloud hosting https://github.com/Saturn-Hosting";

 AboutMe me;
 me.projects.push_back(p1);
 me.projects.push_back(p2);
 me.introduce();
}
```

![Harlok's WakaTime stats](https://github-readme-stats.vercel.app/api/wakatime?username=Fulgur)
