```C++
class MyProfile {
public:
	std::string FullName() {
		return "Allen White";
	}

	std::string Gender() {
		return "Male";
	}

	int Age() {
		return 16;
	}

	std::vector<std::string> Skills() {
		std::vector<std::string> skills { "C/C++", "C#", "A little bit of python" };
		return skills;
	}

	std::vector<std::string> Socials() {
		std::vector<std::string> socials { "Discord: 0xLUXX#8884", "Telegram: @luxbyaw"};
		return socials;
	}
};
```
