﻿**Гаврюшин Иван Андреевич**
 
 **ИВБО-10-17**
 
 **Техническое задание**

**N.N.00013-01 ТЗ 013-КЕ**

#### СОДЕРЖАНИЕ ####

[1. ВВЕДЕНИЕ](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md/#1-введение)  
	[1.1. Наименование программы](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md/#11-наименование-программы)  
	[1.2. Краткая характеристика области применения программы](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md/#12-краткая-характеристика-области-применения-программы)  
[2. ОСНОВАНИЕ ДЛЯ РАЗРАБОТКИ](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md/#2-основание-для-разработки)  
	[2.1. Основание для проведения разработки](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md/#21-основание-для-проведения-разработки)  
	[2.2. Наименование и условное обозначение темы разработки](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md/#22-наименование-и-условное-обозначение-темы-разработки)  
[3. НАЗНАЧЕНИЕ РАЗРАБОТКИ](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md/#3-назначение-разработки)  
	[3.1. Функциональное назначение программы](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md/#31-функциональное-назначение-программы)  
	[3.2. Эксплуатационное назначение программы](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md/#32-эксплуатационное-назначение-программы)  
[4. ТРЕБОВАНИЯ К ПРОГРАММЕ](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md/#4-требования-к-программе)  
	[4.1. Требования к функциональным характеристикам](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md/#41-требования-к-функциональным-характеристикам)  
		[4.1.1. Требования к составу выполняемых функций](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md/#411-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D1%81%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D1%83-%D0%B2%D1%8B%D0%BF%D0%BE%D0%BB%D0%BD%D1%8F%D0%B5%D0%BC%D1%8B%D1%85-%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%B9)  
		[4.1.2. Требования к организации входных и выходных данных](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#412-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D0%BE%D1%80%D0%B3%D0%B0%D0%BD%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8-%D0%B2%D1%85%D0%BE%D0%B4%D0%BD%D1%8B%D1%85-%D0%B8-%D0%B2%D1%8B%D1%85%D0%BE%D0%B4%D0%BD%D1%8B%D1%85-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85)  
		[4.1.3. Требования к временным характеристикам](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#413-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D0%B2%D1%80%D0%B5%D0%BC%D0%B5%D0%BD%D0%BD%D1%8B%D0%BC-%D1%85%D0%B0%D1%80%D0%B0%D0%BA%D1%82%D0%B5%D1%80%D0%B8%D1%81%D1%82%D0%B8%D0%BA%D0%B0%D0%BC)  
	[4.2. Требования к надежности](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#42-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D0%BD%D0%B0%D0%B4%D0%B5%D0%B6%D0%BD%D0%BE%D1%81%D1%82%D0%B8)  
		[4.2.1. Требования к обеспечению надежного (устойчивого) функционирования программы](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#421-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D0%BE%D0%B1%D0%B5%D1%81%D0%BF%D0%B5%D1%87%D0%B5%D0%BD%D0%B8%D1%8E-%D0%BD%D0%B0%D0%B4%D0%B5%D0%B6%D0%BD%D0%BE%D0%B3%D0%BE-%D1%83%D1%81%D1%82%D0%BE%D0%B9%D1%87%D0%B8%D0%B2%D0%BE%D0%B3%D0%BE-%D1%84%D1%83%D0%BD%D0%BA%D1%86%D0%B8%D0%BE%D0%BD%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B)  
		[4.2.2. Контроль входной и выходной информации](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#422-%D0%BA%D0%BE%D0%BD%D1%82%D1%80%D0%BE%D0%BB%D1%8C-%D0%B2%D1%85%D0%BE%D0%B4%D0%BD%D0%BE%D0%B9-%D0%B8-%D0%B2%D1%8B%D1%85%D0%BE%D0%B4%D0%BD%D0%BE%D0%B9-%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D0%B8)  
		[4.2.3. Время восстановления после отказа](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#423-%D0%B2%D1%80%D0%B5%D0%BC%D1%8F-%D0%B2%D0%BE%D1%81%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F-%D0%BF%D0%BE%D1%81%D0%BB%D0%B5-%D0%BE%D1%82%D0%BA%D0%B0%D0%B7%D0%B0)  
	[4.3. Условия эксплуатации](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#43-%D1%83%D1%81%D0%BB%D0%BE%D0%B2%D0%B8%D1%8F-%D1%8D%D0%BA%D1%81%D0%BF%D0%BB%D1%83%D0%B0%D1%82%D0%B0%D1%86%D0%B8%D0%B8)  
		[4.3.1. Климатические условия эксплуатации](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#431-%D0%BA%D0%BB%D0%B8%D0%BC%D0%B0%D1%82%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5-%D1%83%D1%81%D0%BB%D0%BE%D0%B2%D0%B8%D1%8F-%D1%8D%D0%BA%D1%81%D0%BF%D0%BB%D1%83%D0%B0%D1%82%D0%B0%D1%86%D0%B8%D0%B8)  
		[4.3.2. Требования к видам обслуживания](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#432-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D0%B2%D0%B8%D0%B4%D0%B0%D0%BC-%D0%BE%D0%B1%D1%81%D0%BB%D1%83%D0%B6%D0%B8%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)  
		[4.3.3. Требования к численности и квалификации персонала](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#433-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D1%87%D0%B8%D1%81%D0%BB%D0%B5%D0%BD%D0%BD%D0%BE%D1%81%D1%82%D0%B8-%D0%B8-%D0%BA%D0%B2%D0%B0%D0%BB%D0%B8%D1%84%D0%B8%D0%BA%D0%B0%D1%86%D0%B8%D0%B8-%D0%BF%D0%B5%D1%80%D1%81%D0%BE%D0%BD%D0%B0%D0%BB%D0%B0)  
	[4.4. Требования к составу и параметрам технических средств](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#44-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D1%81%D0%BE%D1%81%D1%82%D0%B0%D0%B2%D1%83-%D0%B8-%D0%BF%D0%B0%D1%80%D0%B0%D0%BC%D0%B5%D1%82%D1%80%D0%B0%D0%BC-%D1%82%D0%B5%D1%85%D0%BD%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D1%85-%D1%81%D1%80%D0%B5%D0%B4%D1%81%D1%82%D0%B2)  
	[4.5. Требования к информационной и программной совместимости](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#45-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D0%BE%D0%B9-%D0%B8-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B9-%D1%81%D0%BE%D0%B2%D0%BC%D0%B5%D1%81%D1%82%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8)  
		[4.5.1. Требования к информационным структурам и методам решения](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#451-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D0%BE%D0%BD%D0%BD%D1%8B%D0%BC-%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D1%83%D1%80%D0%B0%D0%BC-%D0%B8-%D0%BC%D0%B5%D1%82%D0%BE%D0%B4%D0%B0%D0%BC-%D1%80%D0%B5%D1%88%D0%B5%D0%BD%D0%B8%D1%8F)  
		[4.5.2. Требования к исходным кодам и языкам программирования](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#452-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D0%B8%D1%81%D1%85%D0%BE%D0%B4%D0%BD%D1%8B%D0%BC-%D0%BA%D0%BE%D0%B4%D0%B0%D0%BC-%D0%B8-%D1%8F%D0%B7%D1%8B%D0%BA%D0%B0%D0%BC-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)  
		[4.5.3. Требования к программным средствам, используемым программой](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#453-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D1%8B%D0%BC-%D1%81%D1%80%D0%B5%D0%B4%D1%81%D1%82%D0%B2%D0%B0%D0%BC-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D1%83%D0%B5%D0%BC%D1%8B%D0%BC-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BE%D0%B9)  
		[4.5.4. Требования к защите информации и программ](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#454-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D0%B7%D0%B0%D1%89%D0%B8%D1%82%D0%B5-%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D0%B8-%D0%B8-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC)  
	[4.6. Требования к маркировке и упаковке](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#46-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D0%BC%D0%B0%D1%80%D0%BA%D0%B8%D1%80%D0%BE%D0%B2%D0%BA%D0%B5-%D0%B8-%D1%83%D0%BF%D0%B0%D0%BA%D0%BE%D0%B2%D0%BA%D0%B5)  
	[4.7. Требования к транспортированию и хранению](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#47-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D1%82%D1%80%D0%B0%D0%BD%D1%81%D0%BF%D0%BE%D1%80%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8E-%D0%B8-%D1%85%D1%80%D0%B0%D0%BD%D0%B5%D0%BD%D0%B8%D1%8E)  
	[4.8. Специальные требования](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#48-%D1%81%D0%BF%D0%B5%D1%86%D0%B8%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F)  
[5. ТРЕБОВАНИЯ К ПРОГРАММНОЙ ДОКУМЕНТАЦИИ](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#5-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B9-%D0%B4%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D0%B8)  
	[5.1. Предварительный состав программной документации](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#51-%D0%BF%D1%80%D0%B5%D0%B4%D0%B2%D0%B0%D1%80%D0%B8%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D1%8B%D0%B9-%D1%81%D0%BE%D1%81%D1%82%D0%B0%D0%B2-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B9-%D0%B4%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D0%B8)  
	[5.2. Специальные требования к программной документации](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#52-%D1%81%D0%BF%D0%B5%D1%86%D0%B8%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B9-%D0%B4%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D0%B8)  
[6. ТЕХНИКО-ЭКОНОМИЧЕСКИЕ ПОКАЗАТЕЛИ](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#6-%D1%82%D0%B5%D1%85%D0%BD%D0%B8%D0%BA%D0%BE-%D1%8D%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5-%D0%BF%D0%BE%D0%BA%D0%B0%D0%B7%D0%B0%D1%82%D0%B5%D0%BB%D0%B8)  
	[6.1. Ориентировочная экономическая эффективность](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#61-%D0%BE%D1%80%D0%B8%D0%B5%D0%BD%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%BE%D1%87%D0%BD%D0%B0%D1%8F-%D1%8D%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F-%D1%8D%D1%84%D1%84%D0%B5%D0%BA%D1%82%D0%B8%D0%B2%D0%BD%D0%BE%D1%81%D1%82%D1%8C)  
	[6.2. Предполагаемая годовая потребность](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#62-%D0%BF%D1%80%D0%B5%D0%B4%D0%BF%D0%BE%D0%BB%D0%B0%D0%B3%D0%B0%D0%B5%D0%BC%D0%B0%D1%8F-%D0%B3%D0%BE%D0%B4%D0%BE%D0%B2%D0%B0%D1%8F-%D0%BF%D0%BE%D1%82%D1%80%D0%B5%D0%B1%D0%BD%D0%BE%D1%81%D1%82%D1%8C)  
	[6.3. Экономические преимущества разработки](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#63-%D1%8D%D0%BA%D0%BE%D0%BD%D0%BE%D0%BC%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B5-%D0%BF%D1%80%D0%B5%D0%B8%D0%BC%D1%83%D1%89%D0%B5%D1%81%D1%82%D0%B2%D0%B0-%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B8)  
[7. СТАДИИ И ЭТАПЫ РАЗРАБОТКИ](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#7-%D1%81%D1%82%D0%B0%D0%B4%D0%B8%D0%B8-%D0%B8-%D1%8D%D1%82%D0%B0%D0%BF%D1%8B-%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B8)  
	[7.1. Стадии разработки](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#71-%D1%81%D1%82%D0%B0%D0%B4%D0%B8%D0%B8-%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B8)  
	[7.2. Этапы разработки](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#72-%D1%8D%D1%82%D0%B0%D0%BF%D1%8B-%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B8)  
	[7.3. Содержание работ по этапам](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#73-%D1%81%D0%BE%D0%B4%D0%B5%D1%80%D0%B6%D0%B0%D0%BD%D0%B8%D0%B5-%D1%80%D0%B0%D0%B1%D0%BE%D1%82-%D0%BF%D0%BE-%D1%8D%D1%82%D0%B0%D0%BF%D0%B0%D0%BC)  
[8. ПОРЯДОК КОНТРОЛЯ И ПРИЕМКИ](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#8-%D0%BF%D0%BE%D1%80%D1%8F%D0%B4%D0%BE%D0%BA-%D0%BA%D0%BE%D0%BD%D1%82%D1%80%D0%BE%D0%BB%D1%8F-%D0%B8-%D0%BF%D1%80%D0%B8%D0%B5%D0%BC%D0%BA%D0%B8)  
	[8.1. Виды испытаний](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#81-%D0%B2%D0%B8%D0%B4%D1%8B-%D0%B8%D1%81%D0%BF%D1%8B%D1%82%D0%B0%D0%BD%D0%B8%D0%B9)  
	[8.2. Общие требования к приемке работы](https://github.com/addzt/ucheba/blob/FINDSTR/tzfindstr.md#82-%D0%BE%D0%B1%D1%89%D0%B8%D0%B5-%D1%82%D1%80%D0%B5%D0%B1%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-%D0%BA-%D0%BF%D1%80%D0%B8%D0%B5%D0%BC%D0%BA%D0%B5-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B)  

### 1. ВВЕДЕНИЕ

#### 1.1. Наименование программы

Наименование – «Утилита FINDSTR командной строки CMD»

#### 1.2. Краткая характеристика области применения программы

Команда FINDSTR используется поиска шаблонов текста в файлах.

### 2. ОСНОВАНИЕ ДЛЯ РАЗРАБОТКИ

#### 2.1. Основание для проведения разработки

Основанием для проведения разработки является лабораторный практикум по дисциплине «Технология разработки ПО АСОИУ», утвержденный Сувальским А.А., в дальнейшем именуемым Заказчиком. Дата утверждения – 03.09.2020.

#### 2.2. Наименование и условное обозначение темы разработки

Наименование темы разработки – «Разработка утилиты FINDSTR.
Условное обозначение темы разработки – «N.N.00013».

### 3. НАЗНАЧЕНИЕ РАЗРАБОТКИ

#### 3.1. Функциональное назначение программы

Функциональным назначением утилиты FINDSTR является поиск текстовой строки в одном или нескольких файлах с использованием регулярных выражений. По сравнению с командой FIND данная команда позволяет выполнять значительно более гибкий поиск в соответствии с правилами, задаваемыми в качестве параметров командной строки.



#### 3.2. Эксплуатационное назначение программы

Утилита FINDSTR должна эксплуатироваться в интерпретаторе командной строки CMD или в пакетном файле.

### 4. ТРЕБОВАНИЯ К ПРОГРАММЕ

#### 4.1. Требования к функциональным характеристикам

#### 4.1.1. Требования к составу выполняемых функций

Утилита FINDSTR должна обеспечивать возможность выполнения перечисленных ниже функций:

1. выполнять точный поиск текста в любом текстовом файле или файлах формата ASCII;
1. предоставлять возможность поиска с использованием регулярных выражений;
1. предоставлять использование как литеральных символов, так и мета-символов.

#### 4.1.2. Требования к организации входных и выходных данных

Синтаксис утилиты FINDSTR:
FINDSTR [/B] [/E] [/L] [/R] [/S] [/I] [/X] [/V] [/N] [/M] [/O] [/P] [/F:файл] [/C:строка] [/G:файл] [/D:список\_папок] [/A:цвета] [/OFF[LINE]] строки [[диск:][путь]имя\_файла[ ...]]

Параметры утилиты FINDSTR:

|/b|Соответствует шаблону текста, если он находится в начале строки.|
| :- | :- |
|/e|Соответствует шаблону текста, если он находится в конце строки.|
|/l|Обрабатывает строки поиска буквально.|
|/r|Обрабатывает строки поиска в виде регулярных выражений. Это параметр по умолчанию.|
|/s|Выполняет поиск в текущем каталоге и во всех подкаталогах.|
|/i|Игнорирует регистр символов при поиске строки.|
|/x|Выводит строки, которые точно соответствуют друг другу.|
|/v|Выводит только те строки, которые не содержат совпадений.|
|/n|Выводит номер строки каждой соответствующей строки.|
|/m|Печатает только имя файла, если файл содержит совпадение.|
|/o|Выводит смещение символов перед каждой совпадающей строкой.|
|/p|Пропускает файлы с непечатаемыми символами.|
|"/OFF" [строка]|Не пропускает файлы с установленным атрибутом offline.|
|\<file>|Возвращает список файлов из указанного файла.|
|/c:\<string>|Использует указанный текст в качестве литеральной строки поиска.|
|/g\<file>|Возвращает строки поиска из указанного файла.|
|/d\<dirlist>|Выполняет поиск в указанном списке каталогов. Каждый каталог должен быть отделен точкой с запятой (например,;) dir1;dir2;dir3 .|
|/\<colorattribute>|Задает атрибуты цвета с двумя шестнадцатеричными цифрами. Введите дополнительные color /? сведения.|
|\<strings>|Задает текст для поиска в файле *filename*. Обязательный элемент.|
|[\<drive>:][\<path>][\<filename>]|Указывает расположение и файл или файлы для поиска. Требуется по крайней мере одно имя файла.|
|/?|Отображает справку в командной строке.|

#### 4.1.3. Требования к временным характеристикам

Требования к временным характеристикам программы не предъявляются.

#### 4.2. Требования к надежности

#### 4.2.1. Требования к обеспечению надежного (устойчивого) функционирования программы

Надежное (устойчивое) функционирование программы должно быть обеспечено выполнением совокупности организационно-технических мероприятий:

1. организацией бесперебойного питания технических средств;
1. выполнением рекомендаций Министерства труда и социального развития РФ, изложенных в Постановлении от 23 июля 1998 г. «Об утверждении межотраслевых типовых норм времени на работы по сервисному обслуживанию ПЭВМ и оргтехники и сопровождению программных средств»;
1. выполнением требований ГОСТ 51188-98. Защита информации. Испытания программных средств на наличие компьютерных вирусов;
1. необходимым уровнем квалификации сотрудников профильных подразделений.

#### 4.2.2. Контроль входной и выходной информации

Предусмотреть блокировку некорректных действий пользователя при работе с системой – вывод сообщения об ошибке с вводом.

#### 4.2.3. Время восстановления после отказа

Время восстановления после отказа должно не превышать 20 мин.

#### 4.3. Условия эксплуатации

#### 4.3.1. Климатические условия эксплуатации

Программа должна работать в закрытых помещениях, при нормальных климатических условиях.
Температура окружающего воздуха должна быть в диапазоне 20-30 градусов, относительная влажность на уровне 40-60%.

#### 4.3.2. Требования к видам обслуживания

Проводится периодическое тестирование программы, раз в полгода.

#### 4.3.3. Требования к численности и квалификации персонала

Минимальное количество персонала, требуемого для работы программы, должно составлять не менее двух штатных единиц – системный администратор и конечный пользователь программы – оператор.
Системный администратор должен иметь минимум среднее техническое образование. В перечень задач, выполняемых системным администратором, должны входить:

1. задача поддержания работоспособности технических средств;
1. задача установки (инсталляции) и поддержания работоспособности системного программного средства - операционной системы;
1. задача установки (инсталляции) программы.

Конечный пользователь программы (оператор) должен обладать практическими навыками работы с графическим пользовательским интерфейсом операционной системы.

#### 4.4. Требования к составу и параметрам технических средств

B состав технических средств должен входить IBM-совместимый персональный компьютер (ПЭВМ), включающий в себя:

1. процессор Pentium – 4 с тактовой частотой не менее 300 МГц;
1. оперативную память объемом не менее 128 Мб;
1. жесткий диск объемом 1.5 Гб и выше.
1. система должна работать под управлением семейства операционных систем Win 32 (Windows 95, Windows 98, Windows 2000, Windows NT и т. п.).

#### 4.5. Требования к информационной и программной совместимости

#### 4.5.1. Требования к информационным структурам и методам решения

Требования к информационным структурам на входе и выходе, а также к методам решения не предъявляются.

#### 4.5.2. Требования к исходным кодам и языкам программирования

Исходные коды программы должны быть реализованы в пакетном файле или непосредственно в интерпретаторе командной строки CMD.

#### 4.5.3. Требования к программным средствам, используемым программой

Должна использоваться командная строка, встроенная в операционную систему Windows.

#### 4.5.4. Требования к защите информации и программ

Требования к защите информации и программ не предъявляются.

#### 4.6. Требования к маркировке и упаковке

Требования к маркировке и упаковке не предъявляются.

#### 4.7. Требования к транспортированию и хранению

Требования к транспортированию и хранению не предъявляются.

#### 4.8. Специальные требования

Специальные требования к программе не предъявляются.

### 5. ТРЕБОВАНИЯ К ПРОГРАММНОЙ ДОКУМЕНТАЦИИ

#### 5.1. Предварительный состав программной документации

Состав программной документации должен включать в себя:

- техническое задание;
- спецификация;
- текст программы;
- описание программы;
- программу и методики испытаний;
- пояснительную записку;
- ведомость эксплуатационных документов;
- формуляр;
- описание применения;
- руководство системного программиста;
- руководство программиста;
- руководство оператора.

#### 5.2. Специальные требования к программной документации

Специальные требования к программной документации не предъявляются.

### 6. ТЕХНИКО-ЭКОНОМИЧЕСКИЕ ПОКАЗАТЕЛИ

#### 6.1. Ориентировочная экономическая эффективность

Ориентировочная экономическая эффективность не рассчитывается.

#### 6.2. Предполагаемая годовая потребность

Предполагаемая годовая потребность не рассчитывается.

#### 6.3. Экономические преимущества разработки

Экономические преимущества разработки не рассчитываются.

### 7. СТАДИИ И ЭТАПЫ РАЗРАБОТКИ

#### 7.1. Стадии разработки

Разработка должна быть проведена в три стадии:

1. разработка технического задания;
1. рабочее проектирование;
1. внедрение.

#### 7.2. Этапы разработки

На стадии разработки технического задания должен быть выполнен этап разработки, согласования и утверждения между Заказчиком и Исполнителем настоящего технического задания.
На стадии рабочего проектирования должны быть выполнены следующие этапы работ:

1. разработка программы;
1. разработка программной документации;
1. испытания программы.

На стадии внедрения должен быть выполнен этап разработки – подготовка и передача программы.

#### 7.3. Содержание работ по этапам

На этапе разработки технического задания должны быть выполнены следующие виды работ:

1. постановка задачи;
1. определение и уточнение требований к техническим средствам;
1. определение требований к программе;
1. определение стадий, этапов и сроков разработки программы и документации на неё;
1. выбор языков программирования;
1. согласование и утверждение технического задания.

На этапе разработки программы должна быть выполнена работа по программированию и отладке программы.
На этапе разработки программной документации должна быть выполнена разработка программных документов в соответствии с требованиями ГОСТ 19. 101-77 и требованием п. «Предварительный состав программной документации» настоящего технического задания.
На этапе испытаний программы должны быть выполнены следующие виды работ:

1. разработка, согласование и утверждение программы и методики испытаний;
1. проведение приемо-сдаточных испытаний;
1. корректировка программы и программной документации по результатам испытаний.

На этапе подготовки и передачи программы должна быть выполнена работа по подготовке и передаче программы и программной документации в эксплуатацию на объектах Заказчика.

### 8. ПОРЯДОК КОНТРОЛЯ И ПРИЕМКИ

#### 8.1. Виды испытаний

Приемо-сдаточные испытания программы должны проводиться согласно разработанной Исполнителем и согласованной Заказчиком «Программы и методики испытаний».
Ход проведения приемо-сдаточных испытаний документируется Заказчиком и Исполнителем в Протоколе проведения испытаний.

#### 8.2. Общие требования к приемке работы

После проведения испытаний в полном объеме, на основании «Протокола испытаний» утверждают «Свидетельство о приемке» и производят запись в программном документе «Формуляр»

