# Polynomial-Calculator 
## Overview
This simple project uses the GUI interface of Java to give the user an easy-to-use application capable of solving elementary operations for polynomial equations.

## To Read
This is a university project written in Italian for my Object-Oriented-Programming Course (AA 2020-2021). This project aims to apply our knowledge of the GUI interface of Java. The package _polinomi_ was already provided by our professor while our task is to write a java file for the GUI aplication (_PolinomiGUI.java_)

## Screenshot
![Polynomial Equation Calc](https://user-images.githubusercontent.com/77573528/196042978-336e6e53-8611-4c9f-a781-8b4dd9b1a12f.png)


## How to use
* Users will type the polynomial in the text box. 
* Clicking the _Inserisci_ button will insert the polynomial expression in the Check box (yellow part)
   ![image](https://user-images.githubusercontent.com/77573528/196044194-8b0c28b2-1f4b-48dd-9077-f08e9954b470.png)

* User can manipulate all the inserted polynomials using the command button which will display the following operation: Sum, Product, Derivative and Evaluation of the polynomial for a given value of the variable x. 
   ![image](https://user-images.githubusercontent.com/77573528/196043689-537da939-6c77-41e2-bb13-5a29877d1cee.png)

* Choosing 1 polynomial in the checkbox makes Derivative and Value menu valid. 
   ![image](https://user-images.githubusercontent.com/77573528/196044219-ef41e93c-e05a-4c29-9452-fa3a95b751a8.png)
 
* When the user choose 2 polynomials in the checkbox, the Sum and Product menu become valid. 
   ![image](https://user-images.githubusercontent.com/77573528/196044244-a4521d6d-5cf7-46fa-9b9b-a59ec554e481.png)

* When the user choose _Valore_ , the program will ask the user for the desired value of x in which the polynomial will be solved. 
   ![value](https://user-images.githubusercontent.com/77573528/196044327-388b7cdc-a8c8-4795-89af-e6da6b5263cd.png)

* For more info, click the _Help_ button

## Description (in Italian)
Polinomi
- Partendo dalle classi/interfacce sviluppate a lezione, si desidera completare l’applicazione dei 
polinomi mediante una GUI che consenta (almeno) le seguenti operazioni:
* inserimento di un polinomio-stringa, nel formato es. -3x^5+2x^3+4, seguito dall’uso di una 
regex di validazione (condizione sufficiente)
* memorizzazione della stringa polinomio, supposta corretta, in un oggetto Check Box il cui 
contenuto può variare dinamicamente
* salvataggio/ripristino su/da file testo, della collezione di polinomi correnti nel Check Box, 
mediante impostazione di un JFileChooser per selezionare il file etc.
* selezione di un polinomio, mediante spunta dal check box, e scelta di un’operazione da 
eseguire su di esso come valutazione del polinomio su un assegnato valore della x (da 
leggere sempre in modo grafico es. mediante un JOptionPane input dialog) o calcolo del 
polinomio derivata prima con memorizzazione del polinomio risultato nella lista del Check 
Box dei polinomi
* selezione, mediante spunta, di due polinomi, e scelta di un’operazione aritmetica binaria 
da applicare ai due polinomi, con memorizzazione del polinomio risultato nel Check Box
* rimozione di un polinomio dal Check Box.

   Tutti i comandi dovrebbero essere evocati mediante una struttura a menù che includa, almeno, 
   il menù File, il menù comandi etc. o, in alternativa, mediante un pop-up menù da attivare col 
   click destro del mouse sul componente grafico


