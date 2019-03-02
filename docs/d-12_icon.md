# CSS 图标

## 如何使用

我们一般将图标放置在 `<i>` 和 `<span>` 元素中。下列都是一些常见的图标库。

## Font Awesome Icons

- 使用方式：

    将 `<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ" crossorigin="anonymous">` 添加进 `<head>` 元素中。

- 示例：

    ```html
    <!DOCTYPE html>
    <html>
    <head>
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ" crossorigin="anonymous">
    </head>
    <body>

    <i class="fas fa-cloud"></i>
    <i class="fas fa-heart"></i>
    <i class="fas fa-car"></i>
    <i class="fas fa-file"></i>
    <i class="fas fa-bars"></i>

    </body>
    </html>
    ```

## Bootstrap Icons

- 使用方式：

    将 `<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">` 添加进 `<head>` 元素中。

- 示例：

    ```html
    <!DOCTYPE html>
    <html>
    <head>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    </head>
    <body>

    <i class="glyphicon glyphicon-cloud"></i>
    <i class="glyphicon glyphicon-remove"></i>
    <i class="glyphicon glyphicon-user"></i>
    <i class="glyphicon glyphicon-envelope"></i>
    <i class="glyphicon glyphicon-thumbs-up"></i>

    </body>
    </html>
    ```

## Google Icons

- 使用方式：

    将 `<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">` 添加进 `<head>` 元素中。

- 示例：

    ```html
    <!DOCTYPE html>
    <html>
    <head>
    <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
    </head>
    <body>

    <i class="material-icons">cloud</i>
    <i class="material-icons">favorite</i>
    <i class="material-icons">attachment</i>
    <i class="material-icons">computer</i>
    <i class="material-icons">traffic</i>

    </body>
    </html>
    ```