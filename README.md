# Engeto_projekt_2
Druhý projekt Engeto Python akademie - Hra Bulls and Cows

Jedná se o program, který simuluje tradiční hru Bulls and Cows. Program vygeneruje náhodné 4 místné číslo za určitých podmínek ( nezačíná nulou a všechny číslice jsou unikátní) a hráč se poté snaží, v co nejmenším počtu pokusů, číslo uhodnout.

Vstup uživatele je ošetřen základními podmínkami (musí mít přesně 4 znaky, musí se jednat o čísla). Program poté porovnává vstup uživatele a vygenerované číslo. Pokud se číslice ze vstupu nachází ve vygenerovaném čísle, ale na jiném indexu, program počítá uživateli hodnotu Cows. Pokud se číslice nachází i na stejném indexu, přičítá se hodnota Bulls. Podle těchto indicií pak uživatel hádá generované číslo. Cílem je tedy trefit 4x Bulls, tím hra končí.
Program navíc počítá uživatelovy pokusy a dobu, za jakou mu trvalo číslo uhodnout.
