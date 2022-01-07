# Кодифікатор адміністративно-територіальних одиниць та територій територіальних громад
У репозиторії представлені файли (JSON, CSV, XLS) які містять дані з [кодифікатора](https://www.minregion.gov.ua/napryamki-diyalnosti/rozvytok-mistsevoho-samovryaduvannya/administratyvno/kodyfikator-administratyvno-terytorialnyh-odynycz-ta-terytorij-terytorialnyh-gromad/) адміністративно-територіальних одиниць та територій територіальних громад (Катоттг) за `16.12.2021`. 
#### Розтлумачення скорочених назв "стовпців":
* region - номер області
* reg_name - назва області
* distr - номер району
* distr_name - назва району
* hrom - номер територіальної громади
* hrom_name - назва територіальної громади
* municip - номер адмін. одиниці (об’єкта АТУ) в громаді
* municip_name - назва міста з районним поділом
* distr_city - назва району у місті з районним поділом
* katotth - номер КАТОТТГ
* div_type - тип об’єкта АТУ
* div_name - назва об’єкта АТУ
* div_full_name - повна назва об’єкта АТУ (div_type + div_name)
### JSON файл має наступну структуру:
```json
{
	"id" : 17375,
	"region" : 48,
	"region_name" : "Миколаївська область",
	"distr" : 6,
	"distr_name" : "Миколаївський район",
	"hrom" : 5,
	"hrom_name" : "Воскресенська територіальна громада",
	"municip" : 8,
	"municip_name" : null,
	"distr_city" : null,
	"katotth" : "UA48060050080014262",
	"div_type" : "селище",
	"div_name" : "Горохівка",
	"div_full_name" : "селище Горохівка"
},
{
	"id" : 17376,
	"region" : 48,
	"region_name" : "Миколаївська область",
	"distr" : 6,
	"distr_name" : "Миколаївський район",
	"hrom" : 5,
	"hrom_name" : "Воскресенська територіальна громада",
	"municip" : 9,
	"municip_name" : null,
	"distr_city" : null,
	"katotth" : "UA48060050090034168",
	"div_type" : "селище",
	"div_name" : "Грейгове",
	"div_full_name" : "селище Грейгове"
}
```
### XLS файл виглядає так:
![xls_preview](https://user-images.githubusercontent.com/64207210/131174091-9b1bea02-ee8f-4b9b-be2d-a35336295dd8.jpg)
