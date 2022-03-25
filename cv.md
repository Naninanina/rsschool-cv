![610478039](https://user-images.githubusercontent.com/57724541/160100611-9d4fd009-b95f-4052-aa9b-1be65d8acee1.jpeg) 
# Nina Morozova
**Junior Frontend developer**
***
**Contact information:**
* **Phone:** +7(952)380-64-60
* **E-mail:** nina05022002@mail.ru
* **Telegram:** @nanimoro
* **Skype:** nina-ananasik
* **Discord:** @Ninanina#1410
***
**About myself:**

I am 20 years old. I am a student at the St. Petersburg Electrotechnical University "LETI" at the Faculty of Computer Technologies and Informatics. I strive to learn and discover new things. That is why I am a student of RS school.

At the same time, I try to finish what I started. Evidence of this is the completed music and art schools.
> Fight and seek, find and never give up!
***
**Skills and Profiency:**
* HTML, CSS
* C++ Basics
* Git, GitHub
***
**Code example:**
```
//функция замены подстроки на другую подстроку
string replaceSubString(string arrstr[], int numStr, string subStr, string replaceSubStr)
{
	string newString = arrstr[numStr];
	int i = 0;
	int z = 0;

	do
	{
		i = newString.find(replaceSubStr, i); //индекс, с которого начнется вставка заданной подстроки; функция find ищет индекс первого символа подстроки, перед которой мы будем вставлять заданную подстроку

		if (i != -1)
		{
			newString.replace(i, replaceSubStr.size(), subStr);      //вставка подстроки перед другой заданной подстрокой
			z = subStr.size() - replaceSubStr.size();
			i += abs(z); 
		}

	} while (i != -1);

	return newString;
}
```
***
**Learning project:**

A website that I created to practice html and css.

* [Website](https://naninanina.github.io/Painting-1920-1930/)
* [GitGub repository](https://github.com/Naninanina/Painting-1920-1930)
***
**Education:**

* Second year of the Magical Electrotechnical (alias ETU "LETI")
	+ Informatics and computer engineering
***
**Languages:**

* Russian — native speaker
* English — A2
