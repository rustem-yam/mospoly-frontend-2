# БЭМ

## Тело человека

тело\_\_голова.голова
тело\_\_рука.рука
тело\_\_торс.торс

### голова

#### голова\_\_уши

голова\_\_уши--размер_длинные  
голова\_\_уши--размер_узкие  
голова\_\_уши--размер_маленькие  

#### голова\_\_нос

голова\_\_нос--цвет_бежевый  
голова\_\_нос--цвет_красный  
голова\_\_нос--цвет_коричевый  

#### голова\_\_волосы

голова\_\_волосы--до-пола  
голова\_\_волосы--карэ  
голова\_\_волосы--короткие  

### рука

#### рука\_\_рана

рука\_\_рана--порез  
рука\_\_рана--синяк  
рука\_\_рана--садина  

#### рука\_\_кисть

рука\_\_кисть--охват_большой  
рука\_\_кисть--охват_средний  
рука\_\_кисть--охват_маленький  

#### рука\_\_вена

рука\_\_вена--видимость_отчётливо  
рука\_\_вена--видимость_плохо  
рука\_\_вена--видимость_спрятано  

### торс

#### торс\_\_позвоночник

торс\_\_позвоночник--деформация_первая-степень  
торс\_\_позвоночник--деформация_вторая-степень  
торс\_\_позвоночник--деформация_третья-степень  

#### торс\_\_пресс

торс\_\_пресс--рельефный  
торс\_\_пресс--отрафированный  
торс\_\_пресс--не-видно  

#### торс\_\_сердце

торс\_\_сердце--большое  
торс\_\_сердце--ледяное  
торс\_\_сердце--десктрокардия  

## Нотация Emmet блоков старого макета

### Header

(header.header>(a.header__logo.header+nav.header__nav>ul.nav__list>(li.nav__item*5>a.item__link)+li.nav__item>a.btn))+(section.hero>h1.hero__title+h2.hero__text+a.btn.btn--modal+img.hero__img+a.hero__btn>img.btn--arrow)

![alt text](https://github.com/rustem-yam/mospoly-frontend-2/blob/emmet/header.jpg?raw=true)

### Форма

form.footer__form>label+input.form__input+button.form__submit

![alt text](https://github.com/rustem-yam/mospoly-frontend-2/blob/emmet/form.jpg?raw=true)

### Карточка

li.card>(.card__text>p.card__subtitle+h2.card__title+p.card__paragraph)+img.card__img

![alt text](https://github.com/rustem-yam/mospoly-frontend-2/blob/emmet/card.jpg?raw=true)

### Секция "Ready to get started"

section.download>.download__grid>h2.download__title.title+a.btn.btn--p_large+a.btn.btn--transparent

![alt text](https://github.com/rustem-yam/mospoly-frontend-2/blob/emmet/ready-to-get-started.jpg?raw=true)
