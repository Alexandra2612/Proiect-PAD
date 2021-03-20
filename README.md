# Proiect-PAD
Food Delivery

Acest proiect urmareste crearea unei aplicatii de livrare a mancarii.Cu ajutorul acesteia clientii,restaurantele,precum si cei ce se ocupa cu livrarea mancarii pot interactiona intr-un mod simplu si eficient.



Administratorul este cel ce va creea lista de restaurante disponibile in aplicatie.Pentru fiecare restaurant acesta va adauga meniurile corespunzatoare,ingredientele din care sunt facute produsele,imagini sugestive,precum si potentiale toping-uri.Fiecare produs si toping este insotit de un pret si un gramaj.Lista de restaurante si meniurile vor fi memorate intr-o baza de date(SQL).Administratorul are rol de server,astfel ca toate informatiile de la cele doua tipuri de clienti ii sunt transmise lui,iar el le trimite mai departe celui caruia ii este destinata informatia.



Clientul se poate inregistra si conecta in aplicatie,pentru conectare trimitand o cerere serverului.Acesta va adauga clientul intr-o lista de utilizatori stocata in baza de date.Dupa autentificare,clientul poate adauga intr-o lista toate produsele pe care doreste sa le comande,lista care va fi trimisa mai apoi serverului.Trimiterea catre server a comenzii presupune si adaugarea unei metode de plata si chiar introducerea detaliilor despre contul din care se va efectua tranzactia in cazul in care clientul a ales modalitatea de plata cu cardul.De la server clientul va primi un mesaj de preluare a comenzii,precum si un timp maxim de livrare in momentul preluarii acesteia de catre persoana ce va aduce comanda.Pe langa mesaj,clientul va putea vizualiza si detalii precum numele,prenumele si numarul de telefon al celui ce ii livreaza comanda.La final clientul va trimite o cerere de deconectare catre administrator,in urma careia va primi un mesaj corespunzator.



Persoana ce livreaza comenzi se poate de asemenea inregistra si conecta,reprezentand si aceasta un tip de client in aplicatie.Pentru ambele tipuri de clienti inregistarea se face printr-un username si o parola,username-ul fiind reprezentat de nume si prenume.Totodata dupa conectare acestia isi vor adauga numarul de telefon pentru a putea comunica in caz de nevoie.Toate datele vor fi trimise server-ului ce le va stoca in baza de date si le va trimite cumparatorului si celui ce va face livrarea in momentul preluarii comenzii.Parolele sunt singurele informatii ce nu vor fi transmise,iar acestea vor fi criptate pentru securitatea conturilor utilizatorilor.Pentru a prelua o comanda tipul de utilizator ce are acesta optiune va putea vizualiza o lista primita de la server cu comenzi si va putea sa selecteze o anumita comanda pe care in cazul in care va apasa pe butonul de accept o va avea atribuita lui.Atribuirea se face prin trimiterea unui mesaj de accept pentru o anumita comanda catre server care va scoate din lista de comenzi disponibile comanda respectiva.Dupa livrare acest tip de client va apasa pe butonul de comanda livrata si astfel va putea reveni la lista de comenzi disponibile pentru preluare.La final acesta se poate deconecta la fel ca si cumparatorii.
