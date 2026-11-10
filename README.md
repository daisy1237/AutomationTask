# Task 2: demoblaze
- An automation task for Automatify internship program, developed in UiPath Studio 

## Procesare fișier Excel – PO
Robotul va primi PO-ul sub formă de fișier Excel.
Pentru fiecare rând din Excel, robotul trebuie să:
Identifice produsul corect după:
- Category
- Brand
- Price în intervalul Min–Max
Adauge produsul în coș de Qty ori (cantitatea din Excel)

## Finalizare comandă
După ce toate produsele au fost adăugate în coș, robotul finalizează comanda (Place Order).

## E-mail Automation
La final, robotul trimite un email de confirmare că achiziția a fost realizată cu succes, incluzând un screenshot.
 
## Observații
Se reutilizeaza automatizarea anterioară (Login + Cart handling + Add to Cart logic) din Task1

