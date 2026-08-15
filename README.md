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
    string education   = "IFMS (Electrotechnics) & Behring Academy";
    string volunteer   = "Movimento Meninas Olímpicas";
};

class FlightSystem {
private:
    Pilot pilot;

    struct Hardware {
        vector<string> microcontrollers = {"ESP32", "ESP8266", "Arduino", "Raspberry Pi (Learning)"};
        vector<string> eda_tools        = {"KiCad"};
    } hardware;

    struct Aerodynamics {
        vector<string> cad_fea_cfd = {"Fusion 360", "AutoCAD", "Ansys"};
        vector<string> rocketry   = {"OpenRocket"};
    } aero;

    struct SoftwareStack {
        vector<string> languages    = {"C++", "C", "C#", "Python", "JavaScript", "HTML5", "CSS3", "SQL"};
        vector<string> backend      = {"Flask"};
        vector<string> game_engines = {"Unity"};
        vector<string> databases    = {"PostgreSQL", "SQLite"};
        vector<string> devops       = {"Docker", "Git"};
    } software;

    struct Missions {
        string competitive_prog = "OBI Preparation via Neps Academy";
        vector<string> ai       = {"Search Algorithms", "LLMs", "Reasoning Systems"};
    } missions;

public:
    void executeMission() {
        cout << "1. Propulsion: Competitive Programming in C++\n";
        cout << "2. Avionics: Embedded Systems (ESP, Arduino, KiCad)\n";
        cout << "3. Aerodynamics: Flight Mechanics & CFD (Ansys, OpenRocket, Fusion 360, AutoCAD)\n";
        cout << "4. Payload: Full Stack Web, Game Dev & AI Systems (Flask, Unity, PostgreSQL, Docker)\n";
    }
};

} 
