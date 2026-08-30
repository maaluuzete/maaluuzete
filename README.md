<div align="center">

# 🌌 FlightSystem.cpp - Malu Azevedo

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=7AA2F7&width=550&lines=class+FlightSystem+%7B+public%3A+void+launch%28%29%3B+%7D%3B)](https://git.io/typing-svg)

</div>

```cpp
#include <bits/stdc++.h>

using namespace std;

namespace AerospaceAvionics {

class Pilot {
public:
    string name        = "Malu Azevedo";
    string location    = "Mato Grosso do Sul, Brazil 🇧🇷";
    string education   = "IFMS (Electrotechnics), Behring Academy & NES (Novo Ensino Suplementar)";
    
    struct LeadershipRoles {
        string competitive_programming_teacher = "Projeto Sem Parar";
        string club_director                   = "Clube de Física e Matemática";
        string informatics_team                = "NOIC (Núcleo Olímpico de Incentivo ao Conhecimento)";
        string ftc_robotics_team               = "Notorius Tech #37604";
        vector<string> volunteer_work          = {"Movimento Meninas Olímpicas"};
    } leadership;
};

class FlightSystem {
private:
    Pilot pilot;

    struct HardwareAndEmbedded {
        string focus                    = "Embedded Systems & Robotics (FTC)";
        vector<string> microcontrollers = {"ESP32", "ESP8266", "Arduino", "Raspberry Pi (Learning)"};
        vector<string> eda_tools        = {"KiCad"};
    } hardware;

    struct Aerodynamics {
        vector<string> cad_fea_cfd = {"Fusion 360", "AutoCAD", "Ansys"};
        vector<string> rocketry    = {"OpenRocket"};
    } aero;

    struct SoftwareStack {
        vector<string> languages    = {"C++", "C", "C#", "Java", "Python", "JavaScript", "HTML5", "CSS3", "SQL"};
        vector<string> backend      = {"Flask"};
        vector<string> game_engines = {"Unity"};
        vector<string> databases    = {"PostgreSQL", "SQLite"};
        vector<string> devops       = {"Docker", "Git"};
    } software;

    struct Missions {
        string competitive_prog = "OBI Preparation via Neps Academy & NOIC Team";
        string robotics         = "FIRST Tech Challenge (FTC Notorius Tech #37604)";
        vector<string> ai       = {"Search Algorithms", "LLMs", "Reasoning Systems"};
    } missions;

public:
    void executeMission() {
        cout << "1. Propulsion: Competitive Programming (NOIC, OBI, Projeto Sem Parar)\n";
        cout << "2. Avionics & Robotics: Embedded Systems & FTC Team #37604 (Notorius Tech)\n";
        cout << "3. Aerodynamics: Flight Mechanics & CFD (Ansys, OpenRocket, Fusion 360, AutoCAD)\n";
        cout << "4. Leadership & Academics: Physics & Math Club Direction | NES Student\n";
        cout << "5. Payload: Full Stack Web, Game Dev & AI Systems (Flask, Unity, PostgreSQL, Docker)\n";
    }
};

}
