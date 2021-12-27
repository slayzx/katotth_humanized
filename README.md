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
* div_num - системний номер об’єкта АТУ
* div_type - тип об’єкта АТУ
* div_name - назва об’єкта АТУ
* div_full_name - повна назва об’єкта АТУ (div_type + div_name)
### JSON файл має наступну структуру:
```json
{
	"id" : 27034,
	"region" : 65,
	"region_name" : "Херсонська область",
	"distr" : 8,
	"distr_name" : "Скадовський район",
	"hrom" : 3,
	"hrom_name" : "Голопристанська територіальна громада",
	"municip" : 10,
	"municip_name" : null,
	"distr_city" : null,
	"div_num" : 68268,
	"div_type" : "село",
	"div_name" : "Малі Копані",
	"div_full_name" : "село Малі Копані"
},
{
	"id" : 31749,
	"region" : 80,
	"region_name" : "Київ",
	"distr" : null,
	"distr_name" : null,
	"hrom" : null,
	"hrom_name" : null,
	"municip" : null,
	"municip_name" : "Київ",
	"distr_city" : 9,
	"div_num" : 80793,
	"div_type" : "район у місті",
	"div_name" : "Солом’янський",
	"div_full_name" : "Солом’янський район у місті Київ"
}
```
### XLS файл виглядає так:
![xls_preview](https://user-images.githubusercontent.com/64207210/131174091-9b1bea02-ee8f-4b9b-be2d-a35336295dd8.jpg)
