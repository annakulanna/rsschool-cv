# Кулеш Анна Юрьевна
## Контакты для связи

-----------|:-------: 
E-mail     |   annakulanna@gmail.com
Telegram   |   @KuleshAnya 

## Примеры кода
```
                const convert = (s) => {
                    let set = new Set(s.toLowerCase().split(''))
                    let arr = []
                    let newArr = s.toLowerCase().split('')
                    for (let value of set) {
                      arr.push(value)
                    } 
                    if(arr == ''){
                      return 0
                    } else if (arr.length === 1){
                      return parseInt('1'.repeat(newArr.length))
                    }
                    arr.unshift(...arr.splice(1, 1))
                    return parseInt(newArr.map(value => arr.indexOf(value)).join(''))
                }
```
## Образование 
### Брестский государственный университет им. А.С. Пушкина
* Экономическая кибернетика (2016-2020)
* Математика и компьютерные науки (2020-2022)
## Английский язык - A2
 
