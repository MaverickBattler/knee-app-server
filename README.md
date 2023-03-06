# Серверная часть приложения KneeApp
Серверная часть приложения KneeApp (можно найти на моем GitHub), которое было разработано как выпускная квалификационная работа бакалавра.

Серверная часть предназначена для сохранения данных пользователя в базе данных, реализации регистрации в приложении, подтверждения электронной почты.

Написано на языке Java с использованием фреймворка Spring Boot.

В базе данных приложения хранятся:
- Личные данные пользователя.
- Роль пользователя (администратор или пользователь).
- Данные о ежедневных тренировках пользователя.
- Данные о еженедельном заполнении анкеты Oxford Knee Score.
- Данные о попытках регистрации пользователей.

Серверная часть приложения предположительно располагается на базе некоторого медицинского учреждения, из базы данных которого берутся данные о пациентах. Зарегистрироваться в приложении могут только пациенты данного медицинского учреждения.
