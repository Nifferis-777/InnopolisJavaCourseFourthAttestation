# Промежуточная аттестация №4 "UI-автотесты"
## Задание:
### 1. Напишите автотесты на сервис https://www.saucedemo.com/

### 2. Сценарии:

#### A. Успешная авторизация (standard_user)

#### B. Авторизация заблокированного пользователя (locked_out_user)

#### C. e2e-сценарий (под пользователями standard_user и performance_glitch_user):

#####  1) авторизоваться

#####  2) добавить в коризину товары: Sauce Labs Backpack, Sauce Labs Bolt T-Shirt, Sauce Labs Onesie

#####  3) перейти в корзину

#####  4) проверить отображение 3 товаров

#####  5) нажать Checkout

#####  6) заполнить форму валидными данными

#####  7) нажать Continue 

#####  8) проверить, что сумма заказа = $58.29

#####  9) нажать Finish



### Реализация: 

#### В классе "AuthorizationTests" представлены решения сценариев A и B

#### В классе "EndToEndTests" представлено решение сценария С, где используется параметризация (необходима для выполнения одного и того же сценария под разными профилями пользователей)
