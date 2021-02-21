# Larisa Gonchar
### __Personal information:__
>Education:

- Systems Engineer, Belarusian State University of Informatics and Radioelectronics (2018 - Present)
- JavaScript, The Rolling Scopes School (2020 - Present)

>Location:

Minsk, Belarus
>Spoken languages:

- Russian (native) 
- English (A2+)

>Contacts:
- Phone: +375293130275 (A1)
- Email: Chayka_Lory@mail.ru
- Telegram: @croft_queen
- Github: @croftik

>Other:

A person, who're always ready to work hard and learn a lot of new information. 
I really want to make this world much easier, that's why I want to develop my skills in Front-end and begin to do adaptive and responsive sites and applications.

### __Skills:__

- C++
- HTML/CSS
- Markdown
- Python
- C++
- SQLite
- Microsoft Word
- Microsoft PowerPoint
- Figma
- JavaScript
- Code examples:
```
void readFileAccounts(Account *arr_of_accounts, int &number_of_accounts) {
	ifstream fin(FILE_OF_ACCOUNTS, ios::in);
	if (!fin.is_open()) {
		makeFirstAdmin(arr_of_accounts, number_of_accounts);
		writeFileAccounts(arr_of_accounts, number_of_accounts);
	} else {
		int i = 0;
		while (!fin.eof()) {
			if (i < SIZE_ARR_OF_ACCOUNTS) {
				fin >> arr_of_accounts[i].login
					>> arr_of_accounts[i].password
					>> arr_of_accounts[i].role;
				i++;
			} else {
				cout << "\nНедостаточно памяти для чтения всех данных!"; break;
			}
		}
		number_of_accounts = i;
	}
    fin.close();
}
```


### __Work experience:__

- Calculator - takes mathematical operations such as: addition, subtraction, multiplication, division, square root and exponentiation. It can do both: positive and negative numbers. Also, it works correctly with fractions.
- Momentum - shows the time and user's name, his goal and quote of the current day. The background image changes depending on the time of the day.
- Shelter - an adaptive multi-page website, that contains animated slider, burger menu, popup and pagination.
- Virtual Keyboard - besides basic functionality has keys for changing language, switching sound and speech recognition.
- Codewars
