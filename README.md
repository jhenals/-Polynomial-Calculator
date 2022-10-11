# -Polynomial-Calculator
This simple project uses the GUI interface of Java to give the user an easy-to-use application capable of solving elementary operations for polynomial equations.

This is a university project written in Italian for my Object-Oriented-Programming Course (AA 2020-2021)

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
