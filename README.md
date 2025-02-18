# MySQL
Folosind ce am învățat despre MySQL, am creat câteva tabele într-o bază de date și am efectuat câteva operații CRUD în XAMPP folosind PHPMyAdmin.
## Tabeluri SQL
Tool-ul folosit: dbdesigner.net<br/>

![Screenshot 2025-02-17 115506](https://github.com/user-attachments/assets/469dd6a3-76ca-4eac-99c1-cf2b81b11a98)
## Operații CRUD
### Create (INSERT)
  1. Add a new product in "products" table
  
  ![Screenshot 2025-02-17 123901](https://github.com/user-attachments/assets/7c059b28-9e88-44f0-b1e8-076db005e72d)<br/>
  ![Screenshot 2025-02-17 123952](https://github.com/user-attachments/assets/cd5b2b6c-e171-4cd9-a1ef-24b5ab7aaaad)<br/>
  
  2. Add a new address for user with CustomerID of 3 in "address" table

  ![Screenshot 2025-02-17 124640](https://github.com/user-attachments/assets/73bd799b-e31a-4dae-af41-7e7cd6a2517b)<br/>
  ![Screenshot 2025-02-17 124731](https://github.com/user-attachments/assets/e7ab8e17-61cd-47e0-b4da-af275ab25f74)<br/>

### Read (SELECT)
  1. Select everything from "product" table

  ![Screenshot 2025-02-17 125025](https://github.com/user-attachments/assets/d5fb24e3-3e3b-4ce7-a44c-fde6bbce64ea)<br/>
  ![Screenshot 2025-02-17 125127](https://github.com/user-attachments/assets/dc2bdbc1-0e5a-4d70-ab1d-1dcab28a4a4c)<br/>

  2. Select every product costing between 100 lei and 500 lei

  ![Screenshot 2025-02-17 125433](https://github.com/user-attachments/assets/896d7b61-4956-4ea6-ac05-3997691892cc)<br/>
  ![Screenshot 2025-02-17 125500](https://github.com/user-attachments/assets/6f378695-93c8-4f6c-b222-8f575d45ac42)<br/>

  3. Select every customer and sort their surnames in alphabetical order

  ![Screenshot 2025-02-18 103544](https://github.com/user-attachments/assets/4f2e0c77-8219-4066-a599-8ed9d7233c4e)<br/>
  ![Screenshot 2025-02-18 103641](https://github.com/user-attachments/assets/971d6570-2465-41ee-b966-dc7d0d3abca5)<br/>

  4. Select the first 4 addresses

  ![Screenshot 2025-02-18 103917](https://github.com/user-attachments/assets/183bef3f-0df7-409b-b889-14a618800adc)<br/>
  ![Screenshot 2025-02-18 103953](https://github.com/user-attachments/assets/320ffd4c-41ee-4da5-9371-915ab1b13867)<br/>

### Update (UPDATE)
  1. Modify a single price tag from the "products" table

  ![Screenshot 2025-02-18 104251](https://github.com/user-attachments/assets/1b92daf9-db3a-4199-8ea7-2c60b36063d4)<br/>
  ![Screenshot 2025-02-18 104419](https://github.com/user-attachments/assets/2581d50e-4ab4-4e36-9a22-c94fb70106d9)<br/>

  2. Modify the customer's address with CustomerID of 1 to "Iasi"

  ![Screenshot 2025-02-18 104741](https://github.com/user-attachments/assets/a9434719-fc97-4b75-8b7f-31fb139a52c7)<br/>
  ![Screenshot 2025-02-18 104804](https://github.com/user-attachments/assets/b585a2a7-d473-4671-bc1d-4e51c19e0757)<br/>

### Delete (DELETE)
  1. Delete the address with an AddressID of 3

  ![Screenshot 2025-02-18 104947](https://github.com/user-attachments/assets/14b5b2ca-886c-4604-8d54-d11c1fd9dc9a)<br/>
  ![Screenshot 2025-02-18 105048](https://github.com/user-attachments/assets/121fbc09-5447-4185-820d-31ff8fb2dd08)<br/>

  2. Delete all products with a price tag lower than 500 lei

  ![Screenshot 2025-02-18 105155](https://github.com/user-attachments/assets/c9ec273f-5172-49b1-a622-8e213a82a183)<br/>
  ![Screenshot 2025-02-18 105223](https://github.com/user-attachments/assets/b8847476-4334-4b29-ad59-b0aea2627782)<br/>

### Join (JOIN)
  1. Use JOIN to show the name, surname, address & city of each client who has an address (clients without an address will not be shown).

  ![Screenshot 2025-02-18 112005](https://github.com/user-attachments/assets/74891c53-53d8-421c-9d89-70e3a624500f)<br/>
  ![Screenshot 2025-02-18 112039](https://github.com/user-attachments/assets/583195fe-00af-4596-ba0a-361bd60959f9)<br/>

  2. Use JOIN to show only product names of items having at least 2 units ordered.

  ![Screenshot 2025-02-18 112452](https://github.com/user-attachments/assets/ad2ce0ab-4463-4e01-89c1-70c101c3bdfd)<br/>
  ![Screenshot 2025-02-18 112519](https://github.com/user-attachments/assets/5758f005-6ac4-4ee2-8b8e-da2ff79951bc)<br/>
