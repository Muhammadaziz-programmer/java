# java
// // // let userName = prompt("Ваше имя");
// // // let userLastname = prompt("Ваша фамилия" );
// // // let age = prompt(`Ваш возраст`)
// // // let job = prompt(`Ваша работа`)

// // // alert( ` name:${userName} \n surname: ${userLastname} \n age:${age}  \n job: ${job}`)

// // // let num1 = +prompt('num1');
// // // let num2 = +prompt('num2');

// // // alert(num1+num2)

// // // let num = prompt()

// // // if(num %2 === 0){
// // //     alert("Четное");
// // // }else{
// // //     alert("Нечетное");
// // // }

// // // let userName = prompt()

// // // if(userName == 1){
// // //     alert("Eldos");
// // // }else if(userName==5){
// // //     alert("Eldos");
// // // }else if(userName==9){
// // //     alert("Eldos");
// // // }else if(userName==68){
// // //     alert("Error");
// // // }else
// // // {
// // //     alert("abdulo")
// // // }
// // // let food = "Apple";
// // // let food2 = "Orange";
// // // let food3 = "Watermalon";
// // // let food4 = "Water";
// // // let food5 = "Coke";
// // // let food6 = "Soda";

// // // let userQuestion = prompt("What do u wont");

// // // if(userQuestion==food){
// // //         alert("okay")
// // // }else if(userQuestion==food2){
// // //         alert("okay")
// // // }else if(userQuestion==food3){
// // //         alert("okay")
// // // }else if(userQuestion==food4){
// // //         alert("okay")
// // // }else if(userQuestion==food5){
// // //         alert("okay")
// // // }else if(userQuestion==food6){
// // //         alert("okay")
// // // }else{
// // //         alert("we don't have this food")
// // // }
// // // alert("" ||0|| "eldos");
// // // let undefinedus = "undefined";

// // // if (!undefinedus) {
// // //   alert("no");
// // // } else {
// // //   alert("on est");
// // // }
// // // let first =""
// // // let second="eldos"
// // // let three=""

// // // alert(first||second||three)

// // // let value = propmt("Какое у вас?")

// // // switch(value){
// // //     case"symyk":
// // //     alert("Какое прекрасное имя")
// // //     case "Abdilaziz":
// // //         alert("")
// // // }

// // // let age = prompt("Тебе есть 18 лет? (да/нет)");

// // // switch (age) {
// // //   case "да":
// // //     alert("Проходи");
// // //     break;
// // //   case "нет":
// // //     prompt("Есть разрешения родителей? (да/нет)");
// // //   case "да":
// // //     alert("наслаждайся");
// // //   case "нет":
// // //     alert("иди домой малыш");
// // // }

// // // let askAgeUser = confirm("Вам имеется 18 лет ?");

// // // switch (askAgeUser) {
// // //   case true:
// // //     let askDrink = confirm("Вы будете пить?");
// // //     switch (askDrink) {
// // //       case true:
// // //         let askAboutParents = confirm("Знают ли ваши родители, что вы здесь?");
// // //         switch (askAboutParents) {
// // //           case true:
// // //             alert("Хорошо можете проходить за стойку");
// // //             break;
// // //           case false:
// // //             alert("Тогда уведомите родителей пожалуйста");
// // //         }
// // //         break;
// // //       case false:
// // //         alert("Хорошо мы проследим что бы вы не пили!");
// // //     }
// // //     break;
// // //   case false:
// // //     alert("Пожалуйста покиньте здание");
// // //     break;
// // // }

// // // let allOrderUser = "";
// // // let bill;

// // // let questionForFirstWhile = prompt("Вам первое или второе?");

// // // if (questionForFirstWhile == "Первое") {
// // //   let firstMenu = prompt(
// // //     "1) Суши 320 сом \n 2) Шашлык 150сом \n 3) Шаурма 200сом\n 4) Самса 60сом"
// // //   );
// // //   switch (firstMenu) {
// // //     case "1":
// // //       allOrderUser = "Суши";
// // //       bill = +320;
// // //       break;
// // //     case "2":
// // //       allOrderUser = "Шашлык";
// // //       bill = +150;
// // //       break;
// // //     case "3":
// // //       allOrderUser = "Шаурма";
// // //       bill = +200;
// // //       break;
// // //     case "4":
// // //       allOrderUser = "Самса";
// // //       bill = +60;
// // //       break;
// // //   }
// // //   let countOrder = prompt("На сколько персон");
// // //   alert(`${allOrderUser} \n ${bill * countOrder}`);
// // // }

// // // let userAnswer = +prompt("Сколько вам лет в данный момент");
// // // let bill;
// // // let bill2;

// // // let fullBill;

// // // let fullPassport;

// // // let daysPassport = 500;
// // // let dayTransitPassport = 600;

// // // if ((userAnswer) => 15) {
// // //   let confirmForPassport = confirm(
// // //     "Точно ли вы хотите сделать паспорт в данный момент"
// // //   );
// // //   if (confirmForPassport === true) {
// // //     let userName = prompt("Какое у вас имя");
// // //     let userSurname = prompt("Какое у вас фамилия");
// // //     if (userName) {
// // //       let answerForNation = prompt("Какая у вас национальность");

// // //       let val = 1000000000;
// // //       let userPersonalIIN = Math.floor(Math.random() * val);

// // //       fullPassport = `Имя: ${userName} \n Фамилия: ${userSurname} \n Ваш возраст:  ${userAnswer}`;
// // //       if (answerForNation) {
// // //         fullPassport += `\n национальность: ${answerForNation} \n Ваш персональный номер: ${userPersonalIIN}`;
// // //       } else {
// // //         fullPassport += `\n национальность: - \n Ваш персональный номер: ${userPersonalIIN}`;
// // //       }

// // //       let countDaysForCome = +prompt(
// // //         "За какое кол-во дней вы хотели бы получить паспорт",
// // //         "6"
// // //       );
// // //       bill = daysPassport * (30 - countDaysForCome);

// // //       alert(fullPassport);
// // //     }
// // //   }
// // //   let confirmForTransitPassword = confirm(
// // //     "Хотите ли вы сделать еще загранный паспорт ?"
// // //   );

// // //   if (confirmForTransitPassword === true) {
// // //     alert(`
// // //         ************ Заграничный Паспорт ************
// // //         \n
// // //         ${fullPassport}
// // //         \n
// // //         ************ Эскиз ************`);
// // //     let countDaysForComeTransit = +prompt(
// // //       "За какое кол-во дней вы хотите получить ваш загранный паспотрт",
// // //       "6"
// // //     );

// // //     bill2 = dayTransitPassport * (30 - countDaysForComeTransit);
// // //   } else {
// // //     alert("Всего доброго!");
// // //   }

// // //   fullBill = bill + bill2;

// // //   alert(`${fullBill} сомов`);
// // // }

// // // let product = "";
// // // let bill;

// // // let questionForFirstWhile = prompt("Вам продукты или технику?");
// // // if (questionForFirstWhile == "Продукты") {
// // //   let fullProduct = prompt(
// // //     "1)cola \n 2)apple  \n 3)orange \n 4)krecers \n5)milk \n6)rolton \n7)coffee \n8)juice \n9)pepsi \n10)fish \n11)meat \n12)cheeze \n13)cake\n14)ramen\n15)stake\n16)tea\n17)salt\n18)soda\n19)bread\n20)butter"
// // //   );
// // //   switch (fullProduct) {
// // //     case "1":
// // //       product = "Cola";
// // //       bill = +120;
// // //       break;
// // //     case "2":
// // //       product = "apple ";
// // //       bill = +150;
// // //       break;
// // //     case "3":
// // //       product = "orange";
// // //       bill = +200;
// // //       break;
// // //     case "4":
// // //       product = "krecers";
// // //       bill = +60;
// // //       break;
// // //     case "5":
// // //       product = "milk";
// // //       bill = +60;
// // //       break;
// // //     case "6":
// // //       product = "rolton ";
// // //       bill = +60;
// // //       break;
// // //     case "7":
// // //       product = "juice";
// // //       bill = +60;
// // //       break;
// // //     case "8":
// // //       product = "pepsi ";
// // //       bill = +60;
// // //       break;
// // //     case "9":
// // //       product = "fish ";
// // //       bill = +60;
// // //       break;
// // //     case "10":
// // //       product = "meat ";
// // //       bill = +60;
// // //       break;
// // //     case "11":
// // //       product = "cheeze ";
// // //       bill = +60;
// // //       break;
// // //     case "12":
// // //       product = "cake ";
// // //       bill = +60;
// // //       break;
// // //     case "13":
// // //       product = "ramen ";
// // //       bill = +60;
// // //       break;
// // //     case "14":
// // //       product = "stake ";
// // //       bill = +60;
// // //       break;
// // //     case "15":
// // //       product = "tea ";
// // //       bill = +60;
// // //       break;
// // //     case "16":
// // //       product = "salt ";
// // //       bill = +60;
// // //       break;
// // //     case "17":
// // //       product = "soda ";
// // //       bill = +60;
// // //       break;
// // //     case "18":
// // //       product = "coffee ";
// // //       bill = +60;
// // //       break;
// // //       case "19":
// // //       product = "bread ";
// // //       bill = +60;
// // //       break;
// // //       case "20":
// // //         product = "butter ";
// // //         bill = +60;
// // //         break;
// // //   }
// // //     let countOrder = prompt("Какое количество");
// // //   alert(`${fullProduct} \n ${bill * countOrder}`);
// // // }

// // // for(let i=0;i<5;i++){
// // //   alert("Hello")
// // // }

// // // while (true) {
// // //   alert("Hi");
// // // }

// // // let allOrderUser = "";
// // // let bill;

// // // let questionForFirstWhile = prompt("Вам первое или второе,третье?");

// // // if (questionForFirstWhile == "Первое") {
// // //   let firstMenu = prompt(
// // //     "1) Суши 320 сом \n 2) Шашлык 150сом \n 3) Шаурма 200сом\n 4) Самса 60сом  \n 5)Пицца 490сом"
// // //   );
// // //   switch (firstMenu) {
// // //     case "1":
// // //       allOrderUser = "Суши";
// // //       bill = +320;
// // //       break;
// // //     case "2":
// // //       allOrderUser = "Шашлык";
// // //       bill = +150;
// // //       break;
// // //     case "3":
// // //       allOrderUser = "Шаурма";
// // //       bill = +200;
// // //       break;
// // //     case "4":
// // //       allOrderUser = "Самса";
// // //       bill = +60;
// // //       break;
// // //     case "5":
// // //       allOrderUser = "Пицца"
// // //       bill = +490;
// // //       break;
// // //   }
// // //   if (questionForFiratWhile == "Второе"){
// // //     let secondMenu = promt (
// // //     "1) Суп 160 сом \n 2)Манты 180 сом \n 3) Лагман 250 сом \n 4)Бифштекс 170 сом \n 5) Гуляш 150 сом"
// // //     );
// // //     switch(secondMenu) {
// // //       case "1":
// // //         allOrderUser = "Суп";
// // //         bill = +160;
// // //         break;
// // //       case "2":
// // //         allOrderUser = "Манты";
// // //         bill = +180;
// // //         break;
// // //       case "3":
// // //         allOrderUser = "Лагман";
// // //         bill = +250;
// // //         break;
// // //       case "4":
// // //         allOrderUser = "Бифштекс";
// // //         bill = +170;
// // //         break;
// // //       case "5":
// // //         allOrderUser = "Гуляш"
// // //         bill = +150;
// // //         break;
// // //     }
// // //   }
// // //   if (questionForFirstWhile == "Третье"){
// // //     let thirdMenu = promt(
// // //       "1)Плов 200 сом \n 2)Стейк 300 сом \n 3)Бургер 180 сом \n 4)Гриль 300 сом \n 5)Пельмени 180 сом"
// // //     );
// // //     switch(thirdMenuMenu) {
// // //       case "1":
// // //         allOrderUser = "Плов";
// // //         bill = +200;
// // //         break;
// // //       case "2":
// // //         allOrderUser = "Стейк";
// // //         bill = +300;
// // //         break;
// // //       case "3":
// // //         allOrderUser = "Бургер";
// // //         bill = +180;
// // //         break;
// // //       case "4":
// // //         allOrderUser = "Гриль";
// // //         bill = +300;
// // //         break;
// // //       case "5":
// // //         allOrderUser = "Пельмени"
// // //         bill = +180;
// // //         break;
// // //     }
// // //   }
// // //   let countOrder = prompt("На сколько персон");
// // //   alert(`${allOrderUser} \n ${bill * countOrder}`);
// // // }

// // // let acceptUser = confirm("Хотите ли вы поситеть наш магазин?");

// // // let bill;

// // // MarketWhile:while (acceptUser) {
// // //     let food =prompt("1)Манты \n 2)Самса \n 3)Ысык нан \n 4)Нан поло");
// // //     if(food==1){
// // //         bill += 130;
// // //     }else if(food ==2){
// // //         bill += 200;
// // //     }else if(food==3){
// // //         bill +=180;
// // //     }else if(food==4){
// // //         bill +=2000;
// // //     }
// // //     break
// // // }

// // // let allPoints = 0;

// // // while (allPoints < 10) {
// // //     let FirstQuestion = prompt("Какой тег используется для создания заголовка в HTML?");
// // //     if (FirstQuestion === "h1") {
// // //         allPoints++;
// // //         alert(`${allPoints} в данный момент у вас столько баллов, и вы ответили правильно`);
// // //     } else {
// // //         alert("Сорри, но ты ответил неверно");
// // //         allPoints--;
// // //         continue;
// // //     }

// // //     let SecondQuestion = prompt("Какой атрибут задает ссылку в теге <a>?");
// // //     if (SecondQuestion === "href") {
// // //         allPoints++;
// // //         alert(`${allPoints} в данный момент у вас столько баллов, и вы ответили правильно`);
// // //     } else {
// // //         alert("Сорри, но ты ответил неверно");
// // //         allPoints -= 2;
// // //         continue;
// // //     }

// // //     let ThirdQuestion = confirm("Вам нравится изучать HTML?");
// // //     if (ThirdQuestion) {
// // //         allPoints++;
// // //         alert(`${allPoints} в данный момент у вас столько баллов, и вы ответили правильно`);
// // //     } else {
// // //         alert("Сорри, но ты ответил неверно");
// // //         allPoints--;
// // //     } break;
// // // }

// // // let a= ' '

// // // for(let i=0;i<5;i++){
// // //     let tr = ' '
// // //     for(let j=0;j<5;j++){
// // //         if(i==j){
// // //             tr+='x'
// // //         }else{
// // //             tr+='1'
// // //         }
// // //     }a+=tr+'\n'
// // // }
// // // console.log(a)

// // // let allOrderUser = "";
// // // let bill;

// // // let questionForFirstWhile = prompt("Вам первое?");

// // // if (questionForFirstWhile == "Первое") {
// // // let firstMenu = prompt(
// // //     "1) Суши 320 сом \n 2) Шашлык 150сом \n 3) Шаурма 200сом\n 4) Самса 60сом  \n 5)Пицца 490сом"
// // // );
// // // switch (firstMenu) {
// // //     case "1":
// // //     allOrderUser = "Суши";
// // //     bill = +320;
// // //     break;
// // //     case "2":
// // //     allOrderUser = "Шашлык";
// // //     bill = +150;
// // //     break;
// // //     case "3":
// // //         allOrderUser = "Шаурма";
// // //         bill = +200;
// // //         break;
// // //     case "4":
// // //         allOrderUser = "Самса";
// // //         bill = +60;
// // //         break;
// // //     case "5":
// // //         allOrderUser = "Пицца"
// // //         bill = +490;
// // //     break;
// // //     } let countOrder = prompt("Какое количество");
// // //     alert(`${allOrderUser} \n ${bill * countOrder}`);
// // // }

// // // for (let i = 0; i <5; i++) {
// // //     let line = '';
// // //     for (let j = 0; j < 5; j++) {
// // //         if ((i === 0 || i === 5 - 1) && (j === 0 || j === 5 - 1)) {
// // //             line += 'x';
// // //         } else if (i === 1 && (j === 1 || j === 3)) {
// // //             line += 'x';
// // //         } else if (i === 3 && (j === 1 || j === 3)) {
// // //             line += 'x';
// // //         } else if (i === 2 && (j === 2)) {
// // //             line += 'x';
// // //         } else {
// // //             line += '1';
// // //         }
// // //     }
// // //     console.log(line);
// // // }

// // // function days(day,week,month) {
// // //     let day;
// // //     let week = "";
// // //     let month = "November"
// // // }

// // // function runnersRace() {
// // //     let distance = parseFloat(prompt("Введите дистанцию:"));
// // //     let runnersCount = parseInt(prompt("Введите количество участников:"));

// // //     let runners = {};

// // //     for (let i = 0; i < runnersCount; i++) {
// // //         let name = prompt(`Введите имя участника ${i + 1}:`);
// // //         let speed = parseFloat(prompt(`Введите скорость участника ${name} (в км/ч):`));
// // //         let time = distance / speed;
// // //         runners({ name, speed, time });
// // //     }

// // //     let result = "Результаты гонки:\n";
// // //     let title = "Место | Имя       | Время (ч)    | Скорость (км/ч)";
// // //     result += title + "\n";

// // //     runners.sort((a, b) => a.time - b.time);

// // //     runners.forEach((runner, index) => {
// // //         result += `${index + 1}     | ${runner.name.padEnd(10)} | ${runner.time.toFixed(2).padStart(10)}  | ${runner.speed.toFixed(2)}\n`;
// // //     });

// // //     let winner = runners[0];

// // //     result += `\n Победитель: ${winner.name} с временем ${winner.time.toFixed(2)} часов (скорость: ${winner.speed.toFixed(2)} км/ч)`;

// // //     alert(result);
// // // }

// // // runnersRace();

// // // let calc;

// // // let firstNumber = prompt("Первое число?");
// // // let secondNumber = prompt("Второе число?")

// // // function ShowOldYear(name,year) {

// // //     if (year) {
// // //         let calc = firstNumber
// // //     }

// // // }

// // // let CustemerToBook = prompt(
// // //   `Хотите вы 1)забронировать или же вы просто \n 2)посмотреть или \n 3)заказать`
// // // );

// // // let localFood;
// // // let localCheck;

// // // function btoc(paramsToOrder) {
// // //   if (paramsToOrder == 1) {
// // //     let menuForCu = prompt(
// // //       `1)Горячие \n 2) Супы \n 3) Фаст Фуд \n 4) Мясное \n 5) Японская кухня \n 6) Десерты \n 7) Напитки \n 8) Кофе \n\n !! Если пришли с водкой поделитесь с повором !! `
// // //     );

// // //     while (true) {
// // //       if (!menuForCu) {
// // //         break;
// // //       }

// // //       if (menuForCu == 1) {
// // //         let hotFood;
// // //         while (true) {
// // //           hotFood = prompt(
// // //             `\n Горячие блюда \n 1) Бифштекс - 200 сом \n 2) Логман - 220 сом \n 3) Плов - 180 сом \n \n 0) Выход`
// // //           );

// // //           if (hotFood == "1") {
// // //             localFood = "Бифштекс";
// // //             localCheck = 200;
// // //           } else if (hotFood == "2") {
// // //             localFood = "Логман";
// // //             localCheck = 220;
// // //           } else if (hotFood == "3") {
// // //             localFood = "Плов";
// // //             localCheck = 180;
// // //           } else if (hotFood == "0") {
// // //             break;
// // //           } else {
// // //             alert("Некорректный выбор. Попробуйте снова.");
// // //             continue;
// // //           }
// // //           alert(`${localFood} и цена ${localCheck} сом`);
// // //           let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// // //           if (continueOrder != "1") {
// // //             break;
// // //           } else {
// // //             menuForCu = prompt(
// // //               `1)Горячие \n 2) Супы \n 3) Фаст Фуд \n 4) Мясное \n 5) Японская кухня \n 6) Десерты \n 7) Напитки \n 8) Кофе \n\n !! Если пришли с водкой поделитесь с повором !! `
// // //             );
// // //           }
// // //         }
// // //       } else if (menuForCu == 2) {
// // //         let soup = prompt(`\n 1) Чечевичный суп \n 2) Мастава \n 3) Борщ\n \n 0) Выход`);
// // //         if (soup == "1") {
// // //           localFood = "Чечевичный суп";
// // //           localCheck = 150;
// // //         } else if (soup == "2") {
// // //           localFood = "Мастава";
// // //           localCheck = 160;
// // //         } else if (soup == "3") {
// // //           localFood = "Борщ";
// // //           localCheck = 140;
// // //         }  else if (soup == "0") {
// // //           break;
// // //         } else {
// // //           alert("Некорректный выбор. Попробуйте снова.");
// // //           continue;
// // //         }
// // //         alert(`${localFood} и цена ${localCheck} сом`);
// // //       } else if (menuForCu == 3) {
// // //         let fastFood = prompt("\n Фаст Фуд \n 1) Бургеры \n 2) Шарму \n 3) Пицца\n \n 0) Выход");
// // //         if (fastFood == "1") {
// // //           localFood = "Бургеры";
// // //           localCheck = 250;
// // //         } else if (fastFood == "2") {
// // //           localFood = "Шарма";
// // //           localCheck = 200;
// // //         } else if (fastFood == "3") {
// // //           localFood = "Пицца";
// // //           localCheck = 300;
// // //         } else if (fastFood == "0") {
// // //           break;
// // //         } else {
// // //           alert("Некорректный выбор. Попробуйте снова.");
// // //           continue;
// // //         }
// // //         alert(`${localFood} и цена ${localCheck} сом`);
// // //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// // //         if (continueOrder = 2) {
// // //           break;
// // //         } else {
// // //           menuForCu = prompt(
// // //             `1)Горячие \n 2) Супы \n 3) Фаст Фуд \n 4) Мясное \n 5) Японская кухня \n 6) Десерты \n 7) Напитки \n 8) Кофе \n\n !! Если пришли с водкой поделитесь с повором !! `
// // //           );
// // //         }

// // //       } else if (menuForCu == 4) {
// // //         let meet = prompt(
// // //           "\n Мясное \n 1) Стейк \n 2) Шашлык \n 3) Мясное рагу\n \n 0) Выход"
// // //         );
// // //         if (meet == "1") {
// // //           localFood = "Стейк";
// // //           localCheck = 350;
// // //         } else if (meet == "2") {
// // //           localFood = "Шашлык";
// // //           localCheck = 300;
// // //         } else if (meet == "3") {
// // //           localFood = "Мясное рагу";
// // //           localCheck = 250;
// // //         } else if (meet == "0") {
// // //           break;
// // //         } else {
// // //           alert("Некорректный выбор. Попробуйте снова.");
// // //           continue;
// // //         }
// // //         alert(`${localFood} и цена ${localCheck} сом`);
// // //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// // //         if (continueOrder = 2) {
// // //           break;
// // //         } else {
// // //           menuForCu = prompt(
// // //             `1)Горячие \n 2) Супы \n 3) Фаст Фуд \n 4) Мясное \n 5) Японская кухня \n 6) Десерты \n 7) Напитки \n 8) Кофе \n\n !! Если пришли с водкой поделитесь с повором !! `
// // //           );
// // //         }
// // //       }else if(menuForCu==5){
// // //         let japanmenu = promt(
// // //           "\nЯпонская кухня\n 1) Ролы\n2)Суши \n 3)Рамен\n \n 0) Выход"
// // //         );
// // //         if(japanmenu=="1"){
// // //           localFood="Ролы";
// // //           localCheck = 350;
// // //         }else if(japanmenu=="2"){
// // //           localFood = "Суши";
// // //           localCheck = 300;
// // //         }else if(japanmenu=="3"){
// // //           localFood = "Рамен";
// // //           localCheck = 250;
// // //         }else if(japanmenu=="0"){
// // //           break;
// // //         }else {
// // //           alert("Некорректный выбор. Попробуйте снова.");
// // //           continue;
// // //         }
// // //         alert(`${localFood} и цена ${localCheck} сом`);
// // //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// // //         if (continueOrder = 2) {
// // //           break;
// // //         } else {
// // //           menuForCu = prompt(
// // //             `1)Горячие \n 2) Супы \n 3) Фаст Фуд \n 4) Мясное \n 5) Японская кухня \n 6) Десерты \n 7) Напитки \n 8) Кофе \n\n !! Если пришли с водкой поделитесь с повором !! `
// // //           );
// // //         }
// // //       } else {
// // //         alert("Некорректный выбор. Попробуйте снова.");
// // //         continue;
// // //       }

// // //       let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// // //       if (continueOrder = 2) {
// // //         break;
// // //       } else {
// // //         menuForCu = prompt(
// // //           `1)Горячие \n 2) Супы \n 3) Фаст Фуд \n 4) Мясное \n 5) Японская кухня \n 6) Десерты \n 7) Напитки \n 8) Кофе \n\n !! Если пришли с водкой поделитесь с повором !! `
// // //         );
// // //       }
// // //     }
// // //   } else {
// // //     alert("Вы выбрали посмотреть, но не выбрали дополнительных опций.");
// // //   }
// // // }

// // // btoc(CustemerToBook);

// // // let CustemerToBook = prompt(
// // //   ` Хотите вы 1) забронировать, 2) просто посмотреть или 3) заказать с доставкой?`
// // // );

// // // let localFood = "";
// // // let localCheck = 0;

// // // function showMenu() {
// // //   loopMenu: while (true) {
// // //     let menuForCu = prompt(
// // //       ` \n Меню: \n 1) Горячие \n 2) Супы \n 3) Фаст Фуд \n 4) Мясное \n 5) Японская кухня \n 6) Десерты \n 7) Напитки \n 8) Кофе \n \n 0) Выход`
// // //     );

// // //     if (menuForCu == "0") break loopMenu;

// // //     if (menuForCu == "1") {
// // //       loopHot: while (true) {
// // //         let hotChoice = prompt(
// // //           ` \n Горячие блюда: \n 1) Бифштекс - 200 сом \n 2) Логман - 220 сом \n 3) Плов - 180 сом \n \n 0) Вернуться назад`
// // //         );
// // //         if (hotChoice == "1") {
// // //           localFood += "Бифштекс\n";
// // //           localCheck += 200;
// // //         } else if (hotChoice == "2") {
// // //           localFood += "Логман\n";
// // //           localCheck += 220;
// // //         } else if (hotChoice == "3") {
// // //           localFood += "Плов\n";
// // //           localCheck += 180;
// // //         } else if (hotChoice == "0") break loopHot;
// // //         else alert("Некорректный выбор. Попробуйте снова.");
// // //         alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// // //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// // //         if (continueOrder == 2) {
// // //           break;
// // //         } else {
// // //           menuForCu = prompt(
// // //             `1)Горячие \n 2) Супы \n 3) Фаст Фуд \n 4) Мясное \n 5) Японская кухня \n 6) Десерты \n 7) Напитки \n 8) Кофе \n\n !! Если пришли с водкой поделитесь с повором !! `
// // //           );
// // //         }
// // //       }
// // //     } else if (menuForCu == "2") {
// // //       loopSoup: while (true) {
// // //         let soupChoice = prompt(
// // //           ` \n Супы: \n 1) Борщ - 150 сом \n 2) Щи - 140 сом \n 3) Солянка - 200 сом \n \n 0) Вернуться назад`
// // //         );
// // //         if (soupChoice == "1") {
// // //           localFood += "Борщ\n";
// // //           localCheck += 150;
// // //         } else if (soupChoice == "2") {
// // //           localFood += "Щи\n";
// // //           localCheck += 140;
// // //         } else if (soupChoice == "3") {
// // //           localFood += "Солянка\n";
// // //           localCheck += 200;
// // //         } else if (soupChoice == "0") break loopSoup;
// // //         else alert("Некорректный выбор. Попробуйте снова.");
// // //         alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// // //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// // //         if (continueOrder == 2) {
// // //           break;
// // //         } else {
// // //           menuForCu = prompt(
// // //             `1)Горячие \n 2) Супы \n 3) Фаст Фуд \n 4) Мясное \n 5) Японская кухня \n 6) Десерты \n 7) Напитки \n 8) Кофе \n\n !! Если пришли с водкой поделитесь с повором !! `
// // //           );
// // //         }
// // //       }
// // //     } else if (menuForCu == "3") {
// // //       loopFastFood: while (true) {
// // //         let fastChoice = prompt(
// // //           `  \n Фаст Фуд: \n 1) Бургер - 150 сом \n 2) Шаурма - 180 сом \n 3) Пицца - 250 сом \n \n 0) Вернуться назад`
// // //         );
// // //         if (fastChoice == "1") {
// // //           localFood += "Бургер\n";
// // //           localCheck += 150;
// // //         } else if (fastChoice == "2") {
// // //           localFood += "Шаурма\n";
// // //           localCheck += 180;
// // //         } else if (fastChoice == "3") {
// // //           localFood += "Пицца\n";
// // //           localCheck += 250;
// // //         } else if (fastChoice == "0") break loopFastFood;
// // //         else alert("Некорректный выбор. Попробуйте снова.");
// // //         alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// // //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// // //         if (continueOrder == 2) {
// // //           break;
// // //         } else {
// // //           menuForCu = prompt(
// // //             `1)Горячие \n 2) Супы \n 3) Фаст Фуд \n 4) Мясное \n 5) Японская кухня \n 6) Десерты \n 7) Напитки \n 8) Кофе \n\n !! Если пришли с водкой поделитесь с повором !! `
// // //           );
// // //         }
// // //       }
// // //     } else if (menuForCu == "4") {
// // //       loopMeat: while (true) {
// // //         let meatChoice = prompt(
// // //           ` \n Мясное: \n 1) Стейк - 400 сом \n 2) Шашлык - 350 сом \n 3) Рагу - 300 сом \n \n 0) Вернуться назад`
// // //         );
// // //         if (meatChoice == "1") {
// // //           localFood += "Стейк\n";
// // //           localCheck += 400;
// // //         } else if (meatChoice == "2") {
// // //           localFood += "Шашлык\n";
// // //           localCheck += 350;
// // //         } else if (meatChoice == "3") {
// // //           localFood += "Рагу\n";
// // //           localCheck += 300;
// // //         } else if (meatChoice == "0") break loopMeat;
// // //         else alert("Некорректный выбор. Попробуйте снова.");
// // //         alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// // //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// // //         if (continueOrder == 2) {
// // //           break;
// // //         } else {
// // //           menuForCu = prompt(
// // //             `1)Горячие \n 2) Супы \n 3) Фаст Фуд \n 4) Мясное \n 5) Японская кухня \n 6) Десерты \n 7) Напитки \n 8) Кофе \n\n !! Если пришли с водкой поделитесь с повором !! `
// // //           );
// // //         }
// // //       }
// // //     } else if (menuForCu == "5") {
// // //       loopJapanese: while (true) {
// // //         let japaneseChoice = prompt(
// // //           ` \n Японская кухня: \n 1) Суши - 300 сом \n 2) Роллы - 250 сом \n 3) Мисо суп - 200 сом \n \n 0) Вернуться назад`
// // //         );
// // //         if (japaneseChoice == "1") {
// // //           localFood += "Суши\n";
// // //           localCheck += 300;
// // //         } else if (japaneseChoice == "2") {
// // //           localFood += "Роллы\n";
// // //           localCheck += 250;
// // //         } else if (japaneseChoice == "3") {
// // //           localFood += "Мисо суп\n";
// // //           localCheck += 200;
// // //         } else if (japaneseChoice == "0") break loopJapanese;
// // //         else alert("Некорректный выбор. Попробуйте снова.");
// // //         alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// // //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// // //         if (continueOrder == 2) {
// // //           break;
// // //         } else {
// // //           menuForCu = prompt(
// // //             `1)Горячие \n 2) Супы \n 3) Фаст Фуд \n 4) Мясное \n 5) Японская кухня \n 6) Десерты \n 7) Напитки \n 8) Кофе \n\n !! Если пришли с водкой поделитесь с повором !! `
// // //           );
// // //         }
// // //       }
// // //     } else if (menuForCu == "6") {
// // //       loopDessert: while (true) {
// // //         let dessertChoice = prompt(
// // //           ` \n Десерты: \n 1) Торт - 200 сом \n 2) Мороженое - 150 сом \n 3) Чизкейк - 250 сом \n \n 0) Вернуться назад`
// // //         );
// // //         if (dessertChoice == "1") {
// // //           localFood += "Торт\n";
// // //           localCheck += 200;
// // //         } else if (dessertChoice == "2") {
// // //           localFood += "Мороженое\n";
// // //           localCheck += 150;
// // //         } else if (dessertChoice == "3") {
// // //           localFood += "Чизкейк\n";
// // //           localCheck += 250;
// // //         } else if (dessertChoice == "0") break loopDessert;
// // //         else alert("Некорректный выбор. Попробуйте снова.");
// // //         alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// // //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// // //         if (continueOrder == 2) {
// // //           break;
// // //         } else {
// // //           menuForCu = prompt(
// // //             `1)Горячие \n 2) Супы \n 3) Фаст Фуд \n 4) Мясное \n 5) Японская кухня \n 6) Десерты \n 7) Напитки \n 8) Кофе \n\n !! Если пришли с водкой поделитесь с повором !! `
// // //           );
// // //         }
// // //       }
// // //     } else if (menuForCu == "7") {
// // //       loopDrinks: while (true) {
// // //         let drinkChoice = prompt(
// // //           ` \n Напитки: \n 1) Сок - 100 сом \n 2) Кола - 120 сом \n 3) Минеральная вода - 80 сом \n \n 0) Вернуться назад`
// // //         );
// // //         if (drinkChoice == "1") {
// // //           localFood += "Сок\n";
// // //           localCheck += 100;
// // //         } else if (drinkChoice == "2") {
// // //           localFood += "Кола\n";
// // //           localCheck += 120;
// // //         } else if (drinkChoice == "3") {
// // //           localFood += "Минеральная вода\n";
// // //           localCheck += 80;
// // //         } else if (drinkChoice == "0") break loopDrinks;
// // //         else alert("Некорректный выбор. Попробуйте снова.");
// // //         alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// // //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// // //         if (continueOrder == 2) {
// // //           break;
// // //         } else {
// // //           menuForCu = prompt(
// // //             `1)Горячие \n 2) Супы \n 3) Фаст Фуд \n 4) Мясное \n 5) Японская кухня \n 6) Десерты \n 7) Напитки \n 8) Кофе \n\n !! Если пришли с водкой поделитесь с повором !! `
// // //           );
// // //         }
// // //       }
// // //     } else if (menuForCu == "8") {
// // //       loopCoffee: while (true) {
// // //         let coffeeChoice = prompt(
// // //           ` \n Кофе: \n 1) Эспрессо - 120 сом \n 2) Капучино - 150 сом \n 3) Латте - 170 сом \n \n 0) Вернуться назад`
// // //         );
// // //         if (coffeeChoice == "1") {
// // //           localFood += "Эспрессо\n";
// // //           localCheck += 120;
// // //         } else if (coffeeChoice == "2") {
// // //           localFood += "Капучино\n";
// // //           localCheck += 150;
// // //         } else if (coffeeChoice == "3") {
// // //           localFood += "Латте\n";
// // //           localCheck += 170;
// // //         } else if (coffeeChoice == "0") break loopCoffee;
// // //         else alert("Некорректный выбор. Попробуйте снова.");
// // //         alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// // //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// // //         if  (continueOrder == 2) {
// // //           break;
// // //         } else {
// // //           menuForCu = prompt(
// // //             `1)Горячие \n 2) Супы \n 3) Фаст Фуд \n 4) Мясное \n 5) Японская кухня \n 6) Десерты \n 7) Напитки \n 8) Кофе \n\n !! Если пришли с водкой поделитесь с повором !! `
// // //           );
// // //         }
// // //       }
// // //     } else {
// // //       alert("Некорректный выбор. Попробуйте снова.");
// // //     }
// // //   }
// // // }

// // // function delivery() {
// // //   let address = prompt("Введите ваш адрес для доставки:");
// // //   if (address == "Кара-Суу" || address == "мкр тюлейкен 23 ") {
// // //     alert("К сожалению, доставка в ваш район невозможна.");
// // //   } else {
// // //     alert(
// // //       `Ваш заказ будет доставлен по адресу: ${address}. \nИтоговая сумма: ${localCheck} сом`
// // //     );
// // //   }
// // // }

// // // if (CustemerToBook == "1") {
// // //   showMenu();
// // // } else if (CustemerToBook == "2") {
// // //   alert("Добро пожаловать! Ознакомьтесь с нашим меню.");
// // // } else if (CustemerToBook == "3") {
// // //   showMenu();
// // //   delivery();
// // // } else {
// // //   alert("Некорректный ввод. Попробуйте снова.");
// // // }

// // let CustemerToBook = prompt(
// //   `Хотите вы 1) забронировать, 2) просто посмотреть или 3) заказать с доставкой?`
// // );

// // let localFood = "";
// // let localCheck = 0;

// // function showMenu() {
// //   loopMenu: while (true) {
// //     let menuForCu = prompt(
// //       `\nМеню: \n1) Горячие \n2) Супы \n3) Фаст Фуд \n4) Мясное \n5) Японская кухня \n6) Десерты \n7) Напитки \n8) Кофе \n\n0) Выход`
// //     );

// //     if (menuForCu == "0") break loopMenu;

// //     // Горячие блюда
// //     if (menuForCu == "1") {
// //       loopHot: while (true) {
// //         let hotChoice = prompt(
// //           `\nГорячие блюда: \n1) Бифштекс - 200 сом \n2) Логман - 220 сом \n3) Плов - 180 сом \n\n0) Вернуться назад`
// //         );
// //         if (hotChoice == "1") {
// //           localFood += "Бифштекс\n";
// //           localCheck += 200;
// //         } else if (hotChoice == "2") {
// //           localFood += "Логман\n";
// //           localCheck += 220;
// //         } else if (hotChoice == "3") {
// //           localFood += "Плов\n";
// //           localCheck += 180;
// //         } else if (hotChoice == "0") break loopHot;
// //         else alert("Некорректный выбор. Попробуйте снова.");
// //         alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// //         if (continueOrder == "2") break loopHot;
// //       }
// //     }
// //     // Супы
// //     else if (menuForCu == "2") {
// //       loopSoup: while (true) {
// //         let soupChoice = prompt(
// //           `\nСупы: \n1) Борщ - 150 сом \n2) Щи - 140 сом \n3) Солянка - 200 сом \n\n0) Вернуться назад`
// //         );
// //         if (soupChoice == "1") {
// //           localFood += "Борщ\n";
// //           localCheck += 150;
// //         } else if (soupChoice == "2") {
// //           localFood += "Щи\n";
// //           localCheck += 140;
// //         } else if (soupChoice == "3") {
// //           localFood += "Солянка\n";
// //           localCheck += 200;
// //         } else if (soupChoice == "0") break loopSoup;
// //         else alert("Некорректный выбор. Попробуйте снова.");
// //         alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// //         if (continueOrder == "2") break loopSoup;
// //       }
// //     }
// //     // Фаст Фуд
// //     else if (menuForCu == "3") {
// //       loopFastFood: while (true) {
// //         let fastChoice = prompt(
// //           `\nФаст Фуд: \n1) Бургер - 150 сом \n2) Шаурма - 180 сом \n3) Пицца - 250 сом \n\n0) Вернуться назад`
// //         );
// //         if (fastChoice == "1") {
// //           localFood += "Бургер\n";
// //           localCheck += 150;
// //         } else if (fastChoice == "2") {
// //           localFood += "Шаурма\n";
// //           localCheck += 180;
// //         } else if (fastChoice == "3") {
// //           localFood += "Пицца\n";
// //           localCheck += 250;
// //         } else if (fastChoice == "0") break loopFastFood;
// //         else alert("Некорректный выбор. Попробуйте снова.");
// //         alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// //         if (continueOrder == "2") break loopFastFood;
// //       }
// //     }
// //     // Мясное
// //     else if (menuForCu == "4") {
// //       loopMeat: while (true) {
// //         let meatChoice = prompt(
// //           `\nМясное: \n1) Стейк - 400 сом \n2) Шашлык - 350 сом \n3) Рагу - 300 сом \n\n0) Вернуться назад`
// //         );
// //         if (meatChoice == "1") {
// //           localFood += "Стейк\n";
// //           localCheck += 400;
// //         } else if (meatChoice == "2") {
// //           localFood += "Шашлык\n";
// //           localCheck += 350;
// //         } else if (meatChoice == "3") {
// //           localFood += "Рагу\n";
// //           localCheck += 300;
// //         } else if (meatChoice == "0") break loopMeat;
// //         else alert("Некорректный выбор. Попробуйте снова.");
// //         alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// //         if (continueOrder == "2") break loopMeat;
// //       }
// //     }
// //     // Японская кухня
// //     else if (menuForCu == "5") {
// //       loopJapanese: while (true) {
// //         let japaneseChoice = prompt(
// //           `\nЯпонская кухня: \n1) Суши - 300 сом \n2) Роллы - 250 сом \n3) Мисо суп - 200 сом \n\n0) Вернуться назад`
// //         );
// //         if (japaneseChoice == "1") {
// //           localFood += "Суши\n";
// //           localCheck += 300;
// //         } else if (japaneseChoice == "2") {
// //           localFood += "Роллы\n";
// //           localCheck += 250;
// //         } else if (japaneseChoice == "3") {
// //           localFood += "Мисо суп\n";
// //           localCheck += 200;
// //         } else if (japaneseChoice == "0") break loopJapanese;
// //         else alert("Некорректный выбор. Попробуйте снова.");
// //         alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// //         if (continueOrder == "2") break loopJapanese;
// //       }
// //     }
// //     // Десерты
// //     else if (menuForCu == "6") {
// //       loopDessert: while (true) {
// //         let dessertChoice = prompt(
// //           `\nДесерты: \n1) Торт - 200 сом \n2) Мороженое - 150 сом \n3) Чизкейк - 250 сом \n\n0) Вернуться назад`
// //         );
// //         if (dessertChoice == "1") {
// //           localFood += "Торт\n";
// //           localCheck += 200;
// //         } else if (dessertChoice == "2") {
// //           localFood += "Мороженое\n";
// //           localCheck += 150;
// //         } else if (dessertChoice == "3") {
// //           localFood += "Чизкейк\n";
// //           localCheck += 250;
// //         } else if (dessertChoice == "0") break loopDessert;
// //         else alert("Некорректный выбор. Попробуйте снова.");
// //         alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// //         if (continueOrder == "2") break loopDessert;
// //       }
// //     }
// //     // Напитки
// //     else if (menuForCu == "7") {
// //       loopDrinks: while (true) {
// //         let drinksChoice = prompt(
// //           `\nНапитки: \n1) Сок - 100 сом \n2) Кола - 120 сом \n3) Минеральная вода - 80 сом \n\n0) Вернуться назад`
// //         );
// //         if (drinksChoice == "1") {
// //           localFood += "Сок\n";
// //           localCheck += 100;
// //         } else if (drinksChoice == "2") {
// //           localFood += "Кола\n";
// //           localCheck += 120;
// //         } else if (drinksChoice == "3") {
// //           localFood += "Минеральная вода\n";
// //           localCheck += 80;
// //         } else if (drinksChoice == "0") break loopDrinks;
// //         else alert("Некорректный выбор. Попробуйте снова.");
// //         alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// //         if (continueOrder == "2") break loopDrinks;
// //       }
// //     }
// //     // Кофе
// //     else if (menuForCu == "8") {
// //       loopCoffee: while (true) {
// //         let coffeeChoice = prompt(
// //           `\nКофе: \n1) Эспрессо - 120 сом \n2) Капучино - 150 сом \n3) Латте - 170 сом \n\n0) Вернуться назад`
// //         );
// //         if (coffeeChoice == "1") {
// //           localFood += "Эспрессо\n";
// //           localCheck += 120;
// //         } else if (coffeeChoice == "2") {
// //           localFood += "Капучино\n";
// //           localCheck += 150;
// //         } else if (coffeeChoice == "3") {
// //           localFood += "Латте\n";
// //           localCheck += 170;
// //         } else if (coffeeChoice == "0") break loopCoffee;
// //         else alert("Некорректный выбор. Попробуйте снова.");
// //         alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// //         let continueOrder = prompt("Хотите продолжить заказ? 1) Да 2) Нет");
// //         if (continueOrder == "2") break loopCoffee;
// //       }
// //     }
// //     else {
// //       alert("Некорректный выбор. Попробуйте снова.");
// //     }
// //   }
// // }

// // function delivery() {
// //   let address = prompt("Введите ваш адрес для доставки:");
// //   if (address == "Кара-Суу" || address == "мкр тюлейкен 23") {
// //     alert("К сожалению, доставка в ваш район невозможна.");
// //   } else {
// //     alert(
// //       `Ваш заказ будет доставлен по адресу: ${address}. \nИтоговая сумма: ${localCheck} сом`
// //     );
// //   }
// // }

// // if (CustemerToBook == "1") {
// //   showMenu();
// //   alert(`Ваш заказ: \n${localFood}Итоговая сумма: ${localCheck} сом`);
// // } else if (CustemerToBook == "2") {
// //   alert("Добро пожаловать! Ознакомьтесь с нашим меню.");
// // } else if (CustemerToBook == "3") {
// //   showMenu();
// //   delivery();
// // } else {
// //   alert("Некорректный ввод. Попробуйте снова.");
// // }

// // let localCheck = 0;
// // let localProduct;

// // function storeMenu() {
// //   loopMenu: while (true) {
// //     let menuForCu = prompt(
// //       "1)drinks \n 2)Food \n 3) Desert \n 4)Korzina \n \n 0)Exit"
// //     );
// //     if (menuForCu == "0") break loopMenu;

// //     if(menuForCu == "1"){
// //       loopDrinks:while(true){
// //       let drink = prompt("Drinks:\n\n1)Cola\n 2)Fanta \n 3)Sprite");

// //       if(drink == "1"){
// //         localProduct = "Cola";
// //         localCheck  = +100;
// //       }else if(drink=="2"){
// //         localProduct = "Fanta";
// //         localCheck = +80;
// //       }else if(drink=="3"){
// //         localProduct = "Sprite";
// //         localCheck = +120;
// //         break loopDrinks;
// //       }else{
// //         alert("Error")
// //       }
// //       alert(`Сумма покупок: ${localCheck}som\nПокупки:${localProduct}`)
// //     }
// //     }
// //   }
// // }

// // storeMenu()

// // Функция - это подпрограмма, которую можно вызвать из внешнего кода или внутреннего кода (в случае рекурсии).
// // По отношению функции и кода.
// // Как и сама программа, функция состоит из последовательности инструкций, называемой телом функции.
// // Значения могут быть переданы в функцию, и функция может вернуть значение.
// // синтаксис function declaration:
// // function имя (параметры){
// //  тело функции

// // }
// // имя(аргумент)
// // пример:
// // showMessage('Ulanbek')
// // !!! function declaration можно вызвать до ее объявление
// // function showMessage(params){
// //  alert(`hello ${params}`)
// // }
// // showMessage('Nazarbek')

// // Параметр - Это переменный который находится внутри круглых скобок в функции.
// // Аргумент - Это значение которое передается параменрам функции при ее вызове.

// // !!! return возвращать

// // Локальные и Глобальные переменные

// // Локальные переменные - Это переменные которые были созданы внутри определенной функции, и они видны только для этой функции.
// // пример:

// // function total(){
// //  let total = 0
// //  // let total является локальным переменным
// // }

// // Глобальные переменный - Это переменные которые находится снаружи всех функции, и они выдны для любой функции.

// // пример:

// //  let total = 0
// //  // let total является глобальным переменным
// // function total(){
// // }

// /// Функция : function expression => Выражение

// // Выражение - комбинация значений или свойств в переменных, функциях или внутри других операций.
// // Который может быть интерпретирован по правилам определенного языка.

// // function expression - Это функция которая находится внутри другого выражения.
// // синтаксис:
// // let название для переменной = function имя"Необъязательно"(){

// // }
// // название для переменной()

// // пример:
// // let getFullName = function(name, surname){
// //  alert(`${name} ${surname}`)
// // }
// // getFullName('Nazarbek', 'Alimjanov')

// // arrow function
// // let message = (params) => {
// //  alert(`hello ${params}`)
// // }
// // message('Nazarbek')

// /// Функция : function callback

// // callback - Это функция которая передается как аргумент другой функций.

// // пример:
// // function showMessage(callback){
// //  callback()
// // }

// // function showName(){
// //  alert('Ulanbek')
// // }

// // showMessage(showName)

// // function ourReversed( callback){
// //  callback('hello')
// // }
// // ourReversed((text)=>{return text})
// let film1 = "Taxi";
// let film2 = "Форсаж";

// let cost = 150;

// let product1 = "Поп-корн";
// let product2 = "Чипсы";
// let product3 = "Кола";
// let product4 = "Сникерс";
// let product5 = "Мороженое";

// let prodCost1 = 80;
// let prodCost2 = 100;
// let prodCost3 = 50;
// let prodCost4 = 60;
// let prodCost5 = 90;

// let card = "";
// let bill = 0;

// function homePage() {
//   while (true) {
//     let home = +prompt(`1) Кино\n2) Магазин\n3) История\n4) Выход!`);
//     if (home === 1) {
//       kinoPage();
//     } else if (home === 2) {
//       magazinPage();
//     } else if (home === 3) {
//       alert(`Вы купили: ${card} \nНа сумму: ${bill}`);
//     } else if (home === 4) {
//       alert("Выход!");
//       break;
//     } else {
//       alert("Ошибка! Попробуйте снова.");
//     }
//   }
// }

// function kinoPage() {
//   while (true) {
//     let films = +prompt(`1) ${film1}\n2) ${film2}`);
//     if (films === 1) {
//       card += film1 + " \n";
//       bill += cost;
//       break;
//     } else if (films === 2) {
//       card += film2 + " \n";
//       bill += cost;
//       break;
//     } else {
//       alert("Ошибка! Попробуйте снова.");
//     }
//   }
// }

// function magazinPage() {
//   while (true) {
//     let products = +prompt(`1) ${product1} - ${prodCost1}$\n2) ${product2} - ${prodCost2}$\n3) ${product3} - ${prodCost3}$\n4) ${product4} - ${prodCost4}$\n5) ${product5} - ${prodCost5}$ `);
//     if (products === 1) {
//       card += product1 + " \n";
//       bill += prodCost1;
//       break;
//     } else if (products === 2) {
//       card += product2 + " \n";
//       bill += prodCost2;
//       break;
//     } else if (products === 3) {
//       card += product3 + " \n";
//       bill += prodCost3;
//       break;
//     } else if (products === 4) {
//       card += product4 + " \n";
//       bill += prodCost4;
//       break;
//     } else if (products === 5) {
//       card += product5 + " \n";
//       bill += prodCost5;
//       break;
//     } else {
//       alert("Ошибка! Попробуйте снова.");
//     }
//   }
// }

// homePage(); // Запуск программы

// let foods = {};

// function creatNewFood(name, cost, catId) {
//   let size = 0;
//   for(let key in foods){
//     console.log(foods[key]);
//     size++
//   }

//   foods["food" + (size + 1)] = {
//     id: size + 1,
//     name: name,
//     cost: cost,
//     catId: catId,
//   };

// }
// creatNewFood("pizza", 480, 32);
// creatNewFood("burger", 150, 12);
// creatNewFood("shaurma", 210, 24);

// console.log(foods);

// let cars = {};

// function createNewCar(id, category, model, color, v, cost) {
//   let size = 0;
//   for (let key in cars) {
//     // console.log(cars[key]);
//     size++;
//   }

//   cars["car" + (size + 1)] = {
//     id: size + 1,
//     category: category,
//     model: model,
//     color: color,
//     v: v,
//     cost: cost,
//   };
// }
// createNewCar('Toyota', 'Camry', 'Black', 2.5, 12000);
// createNewCar('Mersedes', 'S600', 'Black', 5, 123000);

// console.log(cars);

// function deleteCarById(id) {
//   for (let key in cars) {
//     if (cars[key]["id"] === id) {
//       delete cars[key];
//     }
//   }
// }
// deleteCarById(2);

// function deleteCarByModel(model) {
//   for (let key in cars) {
//     if (cars[key]["model"] === model) {
//       delete cars[key];
//     }
//   }
// }
// deleteCarByModel("w-210");

// function deleteCarByCategory(category) {
//   for (let key in cars) {
//     if (cars[key]["category"] === category) {
//       delete cars[key];
//     }
//   }
// }

// deleteCarByCategory("Tayota");

// let cars = {
//   car1: {
//     id: 1,
//     category: "Tayota",
//     model: "Camry",
//     color: "Black",
//     V: 2.5,
//     cost: "1200$",
//   },
//   car2: {
//     id: 2,
//     category: "Tayota",
//     model: "Corolla",
//     color: "Black",
//     V: 1.8,
//     cost: "1000$",
//   },
//   car3: {
//     id: 3,
//     category: "Mersedes-Benz",
//     model: "w-210",
//     color: "white",
//     V: 3.2,
//     cost: "1200$",
//   },
// };

// function updateCarById(id, category, model, color, V, cost) {
//   for (let carKey in cars) {
//     if (cars[carKey].id === id) {
//       cars[carKey].category = category;
//       cars[carKey].model = model;
//       cars[carKey].color = color;
//       cars[carKey].V = V;
//       cars[carKey].cost = cost;
//       break;
//     }
//   }
// }

// updateCarById(1, "BMW", "X7", "Red", 3.7, "2000$");

//   function updateCar(id, key, value) {
//     for (let key1 in cars) {
//     if (id === cars[key1]['id']) {
//       console.log(cars[key1]);
//       cars[key1][key] = value

//     }
//     }
//   }

// updateCar(3, "model", "w125");

// console.log(cars);

// let users = {
//   user1: {
//     id: 1,
//     name: "Malik",
//     surname: "Alihanov",
//     data: {
//       date: 16,
//       month: 3,
//       year: 2004,
//     },
//   },
// };
// function createNewPerson(name, surname, date, month, year) {
//     let size = 0;
//     for (let key in users) {
//         console.log(users[key]);
//         size++;
//       }
//       users["users" + (size + 1)] = {
//           id: size + 1,
//     name: name,
//     surname: surname,
//     data: {
//         date: date,
//         month: month,
//         year: year,
//       },
//     };
//   }

//   createNewPerson("aziz", "ahmedov", 18, 5, 2001);

//   console.log(users);

// function ReadNewPerson(id) {
//     for (let key in users) {
//         if (users[key]["id"]===id){
//           console.log(users[key]);
//           }
//         }
//       }

//       ReadNewPerson(1);

//   function UpdateUser(id, name, surname, date, month, year) {
//         for (let Key in users) {
//       if (users[Key].id === id) {
//       users[Key].name = name;
//       users[Key].surname = surname;
//       users[Key].data.date = date;
//       users[Key].data.month = month;
//       users[Key].data.year = year;
//     }
//   }
// }

// UpdateUser(1, "aziz", "ahmedov",12,21,2121);
// console.log(users);

// function deleteNewPerson(id) {
//     for (let key in users) {
//         if (users[key]["id"]===id){
//           delete(users[key]);
//           }
//         }
//       }

//       deleteNewPerson(1);

// let foods = {
//   food1: {
//     id: 1,
//     name: "Burger",
//     cost: 120,
//   },
//   food2: {
//     id: 2,
//     name: "Hot-dog",
//     cost: 100,
//   },
// };

// function createNewFood(name, cost) {
//   let size = 0;
//   let exists = false;

//   for (let key in foods) {
//     if (foods[key].name === name) {
//       exists = true;
//     }
//     size++;
//   }

//   if (exists) {
//     console.log("Такое уже есть!!");
//   } else {
//     foods["food" + (size + 1)] = {
//       id: size + 1,
//       name: name,
//       cost: cost,
//     };
//   }
// }

// createNewFood("Shaurma", 180);
// createNewFood("Donner", 100);

// console.log(foods);


// let table = {
//     1: {
//         id: 1,
//     },
//     2: {
//         id: 2,
//     },
//     3: {
//         id: 3,
//     },
//     4: {
//         id: 4,
//     },
// };

// let custemer = {
//     eldos: {
//         id: 1,
//         tableId: 2,
//         food: { 1: 3, 2: 4 },
//     },
//     ariet: {
//         id: 2,
//         tableId: 1,
//         food: { 1: 2, 4: 2 },
//     },
//     // ....
// };

// let food = {
//     hot: {
//         hood1: "Бифштекс",
//         hood2: "Шашлык",
//     },
//     soup: {
//         // ....
//     },
// };

// let price = {
//     hot: {
//         BeefSheks: 240,
//         Lavash: 180,
//     },

// };
// let totalCheck = {

// }

// function calculateAndPrintChecks(customers, prices) {
//     let totalCheck = {};

//     for (let customerName in customers) {
//         let customer = customers[customerName];
//         let customerTotal = 0;

//         for (let foodId in customer.food) {
//             let quantity = customer.food[foodId];
//             let foodPrice = 0;

//             for (let category in prices) {
//                 for (let foodName in prices[category]) {
//                     if (foodId == 1 && foodName == "BeefSheks") foodPrice = prices[category][foodName];
//                     if (foodId == 2 && foodName == "Lavash") foodPrice = prices[category][foodName];
//                     if (foodId == 4 && foodName == "Plov") foodPrice = prices[category][foodName];
//                 }
//             }

//             customerTotal += foodPrice * quantity;
//         }

//         if (customer.tableId === 1) customerTotal -= 1000;
//         else if (customer.tableId === 2) customerTotal -= 500;

//         totalCheck[customerName] = {
//             tableId: customer.tableId,
//             total: customerTotal,
//         };
//     }

//     for (let customerName in totalCheck) {
//         let customerCheck = totalCheck[`customerName`];
//         console.log(
//             `Чек для ${customerName}: Стол #${customerCheck.tableId}, Общая сумма: ${customerCheck.total} сом`
//         );
//     }
// }

// calculateAndPrintChecks(custemer, price);

// advent = ["1", 12, 113, 13, ]
// console.log(advent)
