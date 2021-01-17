# Kirill Ryzhenko

Belarus, Minsk
**Mobile:** +375447550097
**Email:** kirillryzh@gmail.com

## Personal Profile Statement

StackEdit stores your files in your browser, which means all your files are automatically saved locally and are accessible **offline!**

## Skills

- HTML / PUG
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

## Education

I am a 3rd year student of BSUIR

## English

Pre-Intermediate
