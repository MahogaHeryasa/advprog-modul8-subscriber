# advprog-modul8-Subscriber

# Mahoga Aribowo Heryasa

# 2206025230

### what is amqp?

AMQP atau *Advanced Message Queuing Protocol* adalah sebuah protokol komunikasi yang digunakan untuk pertukaran pesan antara aplikasi dan sistem yang saling bekerja sama. AMQP dirancang untuk mendukung komunikasi yang andal, efisien, dan aman antara berbagai aplikasi atau sistem yang mungkin menggunakan bahasa atau platform yang berbeda.

Dalam konteks `Subscriber`, AMPQ di implementasikan untuk mengubungkan antrean pesan dengan aplikasi, dengan menggunakan `CrosstownBus` yang memantau pengiriman dan penerimaam pesan dari antrean yang terhubung ke broker AMQP.

### what it means? guest:guest@localhost:5672 , what is the first quest, and what is the second guest, and what is localhost:5672 is for? 

`guest:guest@localhost:5672` adalah bentuk URL dengan format `<username>:<password>@<host>:<port>` yang mengubungkan aplikasi ke server AMQP dengan.

- `guest` pertama adalah *username* pengguna yang digunakan untuk autentikasi di RabbitMQ.
- `guest` kedua adalah *password* pengguna yang digunakan untuk autentikasi di RabbitMQ.
- `localhost:5672` adalah *hostname* dan port dari broker AMQP. *hostname* "localhost" berarti broker AMQP diharapkan berjalan pada mesin yang sama di mana aplikasi berjalan. Sementara, port 5672 adalah port default untuk komunikasi AMQP.