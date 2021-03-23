# ParkingLot

Parcarea are un numar predefinit de locuri X.
Administratorul poate adauga sau sterge oricate masini din gestiune cu conditia sa aiba numere de inmatriculare diferite.
Nu se poate sterge din sistem o masina cu statusul “ocupat”, pana ce aceasta iese din parcare.
Senzorul optic citeste numerele la intrare si iesire schimband statusurle.
La intrare, sistemul va citi numarul de inmatriculare si va marca masina ca “ocupat” daca capacitatea parcarii permite, altfel va printa un mesaj de eroare.
De asemena va printa un mesaj de eroare daca o masina marcata “liber” incearca sa iasa sau una marcata “ocupat” incearca sa intre.
Administratorul are nevoie si de numarul cu care se depaseste capacitatea, egal cu maximul de masini care incearca sa intre si nu au loc, intre o intrare si o iesire de succes.

