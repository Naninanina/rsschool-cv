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


