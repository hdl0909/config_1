![image](https://github.com/user-attachments/assets/ef4fd90f-cda1-4042-886b-506d27d6272a)
```
pip install matplotlib
pip show matplotlib
```
![image](https://github.com/user-attachments/assets/ac2e3708-040c-4620-a450-a0c2609ef51f)
![image](https://github.com/user-attachments/assets/50d4938f-c139-4c7f-b8b0-f1c3cd19270c)
![image](https://github.com/user-attachments/assets/d7f8d742-db10-42a5-82bb-a1a98cb2da93)
![image](https://github.com/user-attachments/assets/efe3b5d4-ceb1-4859-adbc-e1a900c02adc)
```
npm info express
git clone https://github.com/expressjs/express.git
```
![image](https://github.com/user-attachments/assets/11740eec-0033-467a-81af-6904d2745e51)
![image](https://github.com/user-attachments/assets/6abf8d9c-83d4-47a5-9f3c-6884947c7db4)
![image](https://github.com/user-attachments/assets/ea2cf881-c2f4-449c-860d-a10ccbfa82de)
**Команда:**
```
echo 'digraph G {
  node [shape=box];
  matplotlib -> numpy;
  matplotlib -> pillow;
  matplotlib -> cycler;
}' > matplotlib.dot

echo 'digraph G {
  node [shape=box];
  express -> accepts;
  express -> array_flatten;
  express -> content_type;
}' > express.dot

dot -Tpng matplotlib.dot -o matplotlib.png
dot -Tpng express.dot -o express.png

fim matplotlib.png
fim express.png
```
![image](https://github.com/user-attachments/assets/a17bda2e-b798-4198-9e99-b995468397c2)
![image](https://github.com/user-attachments/assets/2a1dae6b-5b38-4eff-add1-41b08ac05fc0)
![image](https://github.com/user-attachments/assets/b8fb4e46-c73c-45f4-a063-308544de036e)
**КОД:**
```
include "globals.mzn";
array[1..6] of var 0..9: tickets;
constraint all_different(tickets);
constraint sum(tickets[1..3]) = sum(tickets[4..6]);
var int: sum_three_digits = sum(tickets[1..3]);
solve minimize sum_three_digits;

output ["Ticket: ", show(tickets)];
output [" Sum of first three digits: ", show(sum_three_digits)];
```
![image](https://github.com/user-attachments/assets/aaf34259-26a6-477d-b67d-a8381d526e3a)

