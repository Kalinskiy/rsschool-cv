# Aleksandr Kalinskyi, 26 y.o <br/> *(Front-end developer)*

## Location: Kiev, Ukraine

## Contacts:
- [Telegramm](http://t.me/kalinskiyqq)
- kalinskiy.sasha@gmail.com
- +38 050 810 80 19


## Education

- Luhansk Taras Shevchenko National University 2016-2019 *(Software Engineering)*
- IT - INCUBATOR (Minsk) 03.2020 - 09.2020 *(React/Redux development)*
- English courses New-Tone 2014-2015 (B2)

## Stack
- React
- Redux
- Js
- HTML
- Material UI
- CSS/SCSS/SASS
- Formik
- Hooks
- Typescript
- Thunk

## Code example 
```
export const getPacksAllTC = (pageCount = 9, page = 0, name?: string): ThunkActionType => async (dispatch:any) => {
    dispatch(changePreloaderTrigger(true))
    try {

        const data = await packsAPI.getPacksAll(pageCount, page, name)
        dispatch(savePack(data.cardPacks))
        dispatch(setTotalPacks(data.cardPacksTotalCount))
        dispatch(getPackPage(data.page))
        dispatch(setIsMyPacks(false))
        dispatch(setIsMyCards(false))

    } catch (error) {
        console.log(error)
    }
    dispatch(changePreloaderTrigger(false))
}
```
## About
I am Ukrainian front-end and React developer focused on clean and qualitative code.
I am passionate about building excellent software and interested to learn new things.