# SI_2022_lab2_203041

Maja Panoska 203041

# Цикломатска комплексност
Цикломатската комплексност на овој граф е 9. 
Има вкупно 9 региони. Или според формула: Има вкупно 8 предикатни јазли => 8+1=9 
Предикатни јазли= 1, 3, 5.2, 6, 7, 8, 11, 13.

4.Во графот имаме 20 јазли, а за да ги поминеме сите нив имаме 3 случаи за every statement методот:
4.1 size=0, list=any => ќе се извршат 1, 2 и 18.
4.2 size=5, list=any => ќе се извршат 1, 3, 4, 18.
4.3 size=9, list='0#0#0#00#' => ќе се извршат 1, 3, 5.1, 5.2, 5.3, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17 и 18.

5.Во графот имаме 27 врски кои треба да ги поминеме, ги избираме следниве случаи за every branch методот:
5.1 size=0, list=any => 1-2, 2-18.
5.2 size=5, list=any => 1-3, 3-4, 4-18.
5.3 size=9, list='0#0#0#00#' => 1-3, 3-5.1, 5.1-5.2, 5.2-17, 5.2-6, 17-18, 6-16, 6-7, 16-5.3, 5.3-5.2, 7-8, 7-11, 8-9, 8-10, 9-11, 10-11, 11-12, 11-13, 12-13, 13-14, 13-15, 14-15, 15-5.3. 
