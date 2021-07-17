# Nazar Danchin
Email: <hokkilax@mail.ru>  
Discord: Unno#1948  
## Objective  
To get a position of IT Specialist, Front-end Developer.
## Technical Skills 
Languages: Javascript (HTML/CSS)  
Version Control System (GIT)     
Internet (all popular browsers)  
## Sample code
```
let user = prompt('Кто там?', '');
let isAdmin;
let isModerator;
if (user == 'Админ' || user == 'Модератор') {

    let password = prompt('Введите пароль', '');

    if (password == 'Я главный') {  
        alert('Здравствуйте, админ!')
    } else if (password == 'Я модератор') {
        alert('Здравствуйте, модератор!');
    } else if (password == '' || password == null) {
        alert('Отменено');
    } else {
        alert('Неверный пароль');
    }

} else if (user == '' || user == null) {
    alert('Отменено');
} else {
    alert('Я вас не знаю');
}
```  