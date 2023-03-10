# MedWeb
Med Web веб платформата служи за закажување на здравствени прегледи во државните болници во Македонија.
Секој корисник на Med Web ќе има увид во достапните термини на докторите/специјалистите за прегледи според упат пополнет од доктор (матичен или специјалист) со ИД за одреден оддел.
Доколку сака да закаже преглед, ќе биде потребно да се регистрира на платформата, а по регистрацијата се добива ID за корисник/пациент. При секоја следна најава, ќе се користи e-mail адресата која првично ја има внесено при самата регистрација.
Според дадениот упат, пациентот може да избере термин кај некој од специјалистите кои работат во соодветниот оддел кој е запишан на упатот, како и болницата во која се наоѓа истиот.
За секој корисник/пациент се чува ID, e-mail адреса, телефонски број, име и презиме, ЕМБГ.
За секоја болница се чува назив, ID, град во кој се наоѓа и адреса.
За секој доктор се чува број на лиценца, оддел/болница во која работи, специјалност (дали е матичен или специјалист).

Крајната имплементација претставува Sprig Boot апликација. За да се стартува, потребно е да имате IDE по желба (ние користевме Intellij), JDK, Maven и PostgreSQL Driver. 
По симнување на кодот, отворете го проектот во вашето IDE и почекајте целосно да се вчита (да се симнат и инсталираат соодветните верзии на Dependencies кои се во pom.xml фајлот. Процесот е автоматски). (Напомена: Ова е возможно доколку го користите Intellij IDEА). Потоа стартувајте ја апликацијата на Run. Апликацијата се стартува на localhost порта 9090. Почетната страна се наоѓа на localhost:9090/home и localhost:9090. Понатаму, сѐ е интуитивно за користење, а ако сакате да видите кое копче за што служи без самите да кликате, погледнете ја презентацијата (https://youtu.be/5Teb3R99mMA)каде има детален опис за секое сценарио.
