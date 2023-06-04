```C++
class MyProfile {
    auto FullName() {
        return "Allen White";
    }

    auto Gender() {
        return "Male";
    }

    auto Age() {
        return 16;
    }

    auto Skills() {
        std::vector<std::string> skills {
            "C/C++", "C#", "WinForms",
            "WPF", "MySQL", "AHK"
        };
        
        return skills;
    }

    auto Socials() {
        std::vector<std::string> socials {
            "Discord: 0xLUXX#8884",
            "Telegram: @luxxbyaw",
            "VK: @a.aw10"
        };
        
        return socials;
    }
};
```
