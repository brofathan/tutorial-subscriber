# Reflection

Nama: Emir Mohamad Fathan <br>
NPM: 2206081982 <br>

1. What is amqp?

AMQP merupakan Advanced Message Queuing Protocol. Protokol ini mengatur komponen software yang berbeda untuk berkomunikasi secara terdistribusi. Khususnya dalam sistem antrean pesan (Queuing). AMQP mengatur format dalam pertukaran pesan antara sistem yang berbeda, hal ini akan memudahkan aplikasi yang berbeda dalam berkomunikasi.

2. What it means? guest:guest@localhost:5672 , what is the first quest, and what is 
the second guest, and what is localhost:5672 is for? 

- guest:guest merupakan username dan password default dalam autentikasi AMQP broker seperti RabbitMQ.
- localhost:5672 merupakan hostname dan port. "localhost" merupakan nama local machine dalam AMQP broker, sedangkan "5672" adalah default port untuk komunikasi AMQP.

<br>
<hr>
<br>

- Screen of RabbitMQ with slow subscriber
![image](https://github.com/brofathan/tutorial-publisher/assets/45114836/12431f18-2020-4394-8793-a1aebe0ec765)
(Terdapat 15 message queue karena saya menjalankan publisher sepertinya sebanyak 3 kali, publisher mengirimkan 5 data tiap dijalankan.)
