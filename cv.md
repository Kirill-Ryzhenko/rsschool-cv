# Kirill Ryzhenko

Belarus, Minsk
**Mobile:** +375447550097
**Email:** kirillryzh@gmail.com

## About me

My name is Kirill Ryzhenko, I am 20 years old, I am a 3rd year student of BSUIR. I am interested in programming and in particular the programming language Javascript.

## Skills

- HTML
- CSS / SASS / SCSS
- BEM methodology
- JS / jQuery
- Webpack
- Git / GitHub

## Code examples

```javascript
$(document).ready(function () {
  $('#submitBtn').click(function () {
    $.ajax({
      url: '/',
      method: 'POST',
      data: { text: $('#cites').val() },
      success: () => {
        console.log('Данные успешно отправлены')
      },
      error: () => {
        console.log('Произошла ошибка')
      },
    })
  })
  $('#default').click(() => {
    $.ajax({
      url: '/default',
      method: 'POST',
      success: (data) => {
        $('#defaultOl').text('')
        $.each(data, function (index, value) {
          $('#defaultOl').append(`<li>${value}</li>`)
        })
        console.log('Показан первоначальный массив')
      },
      error: () => {
        console.log('Произошла ошибка')
      },
    })
  })
  $('#format').click(() => {
    $.ajax({
      url: '/format',
      method: 'POST',
      success: (data) => {
        $('#formatOl').text('')
        $.each(data, function (index, value) {
          $('#formatOl').append(`<li>${value}</li>`)
        })
        console.log('Показан отредактированный массив')
      },
      error: () => {
        console.log('Произошла ошибка')
      },
    })
  })
})
```

## Work experience

Coming soon

## Education

I am a 3rd year student of BSUIR

## English

Pre-Intermediate
