+++
title = 'Maple'
date = 2023-10-25T02:14:11+03:00
draft = true
+++

## Проект беспилотного летательного аппарата самолетного типа "Клён"

### Цель

Рассчитать, построить и проверить БПЛА самолетного типа для наработки знаний и
навыков проведения расчетов и проектирования

### Техническое задание

Характеристики, которые необходимо соблюсти:

* Назначение ЛА: разведывательный (приоритет - время полета)
* Размах крыла: 2м
* Силовая установка: Электрическая

### Расчет

Так как в приоритетах стоит увеличение времени полета и задан размах крыла,
будем отталкиваться не от веса конструкции или полезной нагрузки, а от
подъемной силы, создаваемой крылом, а так же лобового сопротивления.

По этим параметрам можно будет выйти на мощность и вес двигателя и других
частей конструкции.

#### Этапы расчета

1. Определение параметров крыла
    1. Удлинение крыла
    2. Ширина
    3. Профиль
    4. Сужение
    5. Крутка
    6. V-образность
    7. Законцовки
2. Расчет подъемной силы крыла
3. Расчет лобового сопротивления
4. Расчет веса оборудования
   1. Двигатель
   2. Регулятор
   3. Батарея
   4. Сервомашинки
   5. Приемник сигнала управления
   6. Стабилизатор / автопилот
   7. GPS приемник
   8. Камера
   9. Передатчик видео
5. Расчет строительного веса

Уравнение подъемной силы:
$$
\begin{equation}
L=\frac{1}{2} \cdot \rho \cdot S \cdot V^2 \cdot C_y
\end{equation}
$$

### Проектирование

### Постройка опытного образца