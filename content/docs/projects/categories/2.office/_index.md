---
weight: 2
title: 'Офіс'
description: Офісні програми для локалізації
toc: true
authors:
tags:
categories:
series:
date: '2021-12-19'
lastmod: '2021-12-20'
draft: false
---

# Офісні програми

#### редагування тексту, документів, таблиць з даними, нотатки, електронна пошта

 - ### [Mailcow](https://mailcow.email/), [Mailcow on GitHub](https://github.com/mailcow/mailcow-dockerized)
 
  > Потужна система для налаштування Email серверу та управління електронною поштою. Mailcow містить всі необхідні елементи, що забезпечують віправку та отримання пошти - [MTA (mail transfer agent)](https://en.wikipedia.org/wiki/Message_transfer_agent), [SMTP](https://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol), [MDA (mail delivery agent)](https://en.wikipedia.org/wiki/Mail_delivery_agent), [MUA (email clients)](https://wiki.archlinux.org/index.php/Email_client), [POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol), [IMAP](https://en.wikipedia.org/wiki/IMAP) та інші. Як працюють сервери електронної пошти - див. [сюди](https://wiki.archlinux.org/index.php/Mail_server).
  
   Переклад українською відсутній. В документації не описано як робити переклад. По факту необхідно перекласти файл у форматі JSON і за допомогою [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) на GitHUB додати перекладену мову. Доступні файли з перекладеними мовами розміщено [ТУТ](https://github.com/mailcow/mailcow-dockerized/tree/master/data/web/lang).
   
 ---


 - ### [Joplin](https://joplinapp.org/)
 
  > Застосунок для нотаток. Надає дуже широкі можливості для синхронізації (Dropbox, WebDAV, Nextclout etc.), для імпорту/експорту (напр., з Evernote, Mardown). Проект на [GitHub](https://github.com/laurent22/joplin)
  
   Український переклад взагалі відсутній. Перекладають за допомогою [Poedit](https://poedit.net/), ось [інструкці](https://github.com/laurent22/joplin#localisation) як робити локалізацію.
   
 ---
 
 
 - ### [LibreOffice Help](https://help.libreoffice.org)
 
  > Документація, інструкції, допомога при роботі з офісним пакетом LibreOffice

   Переклад робиться [ТУТ](https://translations.documentfoundation.org/uk/libo_help/).
   
 --- 
 
 
  - ### [Framadate](https://framadate.org/)
 
  > Органайзер, планувальник зустрічей, опитування.

   Як робити переклад/локалізацію вказано [ТУТ](https://framagit.org/framasoft/framadate/framadate/-/wikis/translating). Станом на 14.07.2020р. українська мова відсутня взагалі.
   
 --- 
  
 
# CRM системи 
 
### управління проектами, взаємодія з клієнтами, бізнес-процеси, робота з персоналом
 
 - ### [Dolibarr](https://www.dolibarr.org/)
   
   > Наймовірно потужна та гнучка open source система [ERP&CRM](https://crmswitch.com/crm-value/understanding-crm-erp/).
   
   Український переклад майже відсутній (перекладено 5%). Дуже зручно перекладати через платформу [Transifex](https://www.transifex.com/), деталі як перекладати описано в [WiKi](https://wiki.dolibarr.org/index.php/Translator_documentation).
   Потребує локалізації як сама програма, так і ВіКі.
 ---
  
 - ### [SuiteCRM](https://suitecrm.com/), [SuiteCRM on GitHub](https://github.com/salesagility/SuiteCRM) 
   > SuiteCRM є продовженням (розгалуженням) SugarCRM. Розробник останньої припинив підтримку open source версії. SuiteCRM містить всі необхідні інструменти для роботи з клієнтами, організації бізнес-процесів та котролю ресурсів.
   
   Як робити переклад описано за посиланням [https://docs.suitecrm.com/community/contributing-to-docs/contributing-to-translation/](https://docs.suitecrm.com/community/contributing-to-docs/contributing-to-translation/).
 ---
 
 - ### [EsproCRM](https://www.espocrm.com), [EsproCRM on GitHub](https://github.com/espocrm/espocrm)
   > Досить гнучка система CRM. EspoCRM — веб-додаток з відкритим кодом, що допомагає створити стійкі відносини із клієнтами. Включає функції планування задач, аналізу роботи компанії, фіксує всі взаємодії з клієнтами.
   
   Щоб робити локалізацію (переклад) потрібно завантажити код, встановити NodeJS, відредагувати файли локалізації і робити переклад. Деталі [беремо тут](https://github.com/espocrm/espocrm#how-to-make-a-translation).
