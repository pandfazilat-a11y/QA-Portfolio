# Bug Report 004

## Title

Поле Email принимает некорректный формат

## Environment

Website: Online store
Browser: Google Chrome

## Preconditions

Пользователь находится на странице регистрации

## Steps to reproduce

1. Открыть страницу регистрации
2. Ввести имя
3. Ввести некорректный email, например `test@`
4. Ввести пароль
5. Нажать кнопку "Регистрация"

## Expected Result

Система показывает сообщение об ошибке и не позволяет зарегистрироваться.

## Actual Result

Система принимает некорректный email и позволяет продолжить регистрацию.

## Severity

Medium

## Priority

High
