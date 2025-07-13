# 🚀 Welcome to Thuriya Ye Naing's Cosmic C++ Citadel! 👾🌌

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=FF00FF¢er=true&vCenter=true&width=435&lines=C%2B%2B+Galaxy+Explorer+%F0%9F%94%A5;From+Myanmar+%F0%9F%87%B2%F0%9F%87%B2+to+the+Universe+%F0%9F%8C%9E;Forging+Code+Legends;Roll%2C+Code%2C+Conquer" alt="Typing SVG" />
</div>

## 🌠 About Me

I’m Thuriya Ye Naing, a C++ code wizard from Myanmar 🇲🇲, launching epic digital voyages! My GitHub realm, https://github.com/theYE-8266-viren-Nai/, is a treasure trove of C++ magic, starting with the legendary **C++ School Management System** featuring a dice-rolling saga in `diceRolling.cpp`. Beyond C++, I’m a full-stack voyager exploring React, Laravel, and even WebAssembly!

- 🔭 Currently crafting **C++ epics and WebAssembly experiments**
- 🌱 Diving into **AI code optimization and Three.js 3D realms**
- 👯 Seeking cosmic collaborators for **open-source quests**
- 🤔 Pondering **quantum C++ and intergalactic UI design**
- 💬 Chat with me about **C++, React, Laravel, or UI/UX magic**
- 📫 Reach me at: **thuriyayenaing@gmail.com**
- ⚡ Fun fact: **I debug with a virtual dice roll—odds favor the code! 🎲**

## 🎲 Dice-Rolling C++ Adventure

My flagship project, the **C++ School Management System**[](https://github.com/theYE-8266-viren-Nai/cpp-school-management-system), turns classrooms into dice-rolling arenas! Compile and roll the digital dice to decide fates—pure coding chaos!

### How to Join the Fun
1. Clone the repo: `git clone https://github.com/theYE-8266-viren-Nai/cpp-school-management-system.git`
2. Compile: `g++ -o schoolDice diceRolling.cpp`
3. Run: `./schoolDice` and let the dice decide!

## 🌐 My GitHub Universe
Explore my repositories at https://github.com/theYE-8266-viren-Nai/:
- **cpp-school-management-system**: The dice-rolling C++ saga!
- **viren140290.github.io**: A portal to my web dev adventures.
- And more to come—stay tuned for cosmic updates!

## 💻 Tech Arsenal

### 🎯 C++ Powerhouse
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)

### 🌠 Experimental Frontiers
![WebAssembly](https://img.shields.io/badge/WebAssembly-%23654FF0.svg?style=for-the-badge&logo=webassembly&logoColor=white)
![Emscripten](https://img.shields.io/badge/Emscripten-%23000000.svg?style=for-the-badge&logo=emscripten&logoColor=white)

### 🚀 Full-Stack Odyssey
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)

### 🛠️ Tools of the Trade
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

## 🎨 Interactive ASCII Dice Art (Roll It!)

```cpp
#include <iostream>
#include <cstdlib>
#include <ctime>

void drawDiceFace(int roll) {
    std::cout << "-------\n";
    if (roll == 1) std::cout << "|   *   |\n|   *   |\n|   *   |\n";
    else if (roll == 2) std::cout << "| *    |\n|      |\n|    * |\n";
    else if (roll == 3) std::cout << "| *    |\n|   *   |\n|    * |\n";
    else if (roll == 4) std::cout << "| *   * |\n|       |\n| *   * |\n";
    else if (roll == 5) std::cout << "| *   * |\n|   *   |\n| *   * |\n";
    else if (roll == 6) std::cout << "| *   * |\n| *   * |\n| *   * |\n";
    std::cout << "-------\n";
}

int main() {
    srand(time(0));
    int roll = rand() % 6 + 1;
    std::cout << "Rolling the cosmic dice... You got: " << roll << "!\n";
    drawDiceFace(roll);
    return 0;
}
