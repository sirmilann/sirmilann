[![Typing SVG](https://readme-typing-svg.demolab.com?font=&weight=100&size=26&pause=1000&width=435&lines=Welcome+To+My+Page!)](https://git.io/typing-svg)
```c++
#include <iostream>
#include <string>

class ReadMe {
public:
    virtual void about() = 0;
};

class sirmilann : public ReadMe {
public:
    sirmilann() {
        std::cout << R"(
       ██╗  ██╗███████╗██╗     ██╗      ██████╗     ██╗    ██╗ ██████╗ ██████╗ ██╗     ██████╗ ██╗
       ██║  ██║██╔════╝██║     ██║     ██╔═══██╗    ██║    ██║██╔═══██╗██╔══██╗██║     ██╔══██╗██║
       ███████║█████╗  ██║     ██║     ██║   ██║    ██║ █╗ ██║██║   ██║██████╔╝██║     ██║  ██║██║
       ██╔══██║██╔══╝  ██║     ██║     ██║   ██║    ██║███╗██║██║   ██║██╔══██╗██║     ██║  ██║╚═╝
       ██║  ██║███████╗███████╗███████╗╚██████╔╝    ╚███╔███╔╝╚██████╔╝██║  ██║███████╗██████╔╝██╗
       ╚═╝  ╚═╝╚══════╝╚══════╝╚══════╝ ╚═════╝      ╚══╝╚══╝  ╚═════╝ ╚═╝  ╚═╝╚══════╝╚═════╝ ╚═╝
        )" << std::endl;
        
        username = "sirmilann";
        language = "English";
        discord = "https://discord.gg/Eww5ucwY4a";
        coding_languages = "C++";
        location = "United Kingdom";
        donateXMR = "44Q5UNcp3LR4SRZm3fymYeDZETwc6aTynLGnkBgLMTw7a3Nkjambq3WGbqFHLA7gc8D1mVJ6ji7tUeKbKVi9KirJQ3n4964";
    }

    void about() override {
        std::cout << "Hi, I'm " << username << ". I'm just a guy who codes." << std::endl;
    }

private:
    std::string username;
    std::string language;
    std::string discord;
    std::string coding_languages;
    std::string location;
    std::string donateXMR;
};

int main() {
    sirmilann me;
    me.about();
    return 0;
}

```
