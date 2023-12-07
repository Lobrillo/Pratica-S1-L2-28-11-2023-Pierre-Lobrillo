# Pratica-S1-L2-28-11-2023-Pierre-Lobrillo
Scrivere per i seguenti IP: IP Network, IP Gateway ‘convenzionale’, IP Broadcast, quali e quanti ottetti per gli host, quanti e quali per la network. ● 1.1.1.1/8 ● 128.1.6.5/12 ● 200.1.2.3/24 ● 192.192.1.1/22 ● 126.5.4.3/9 ● 200.1.9.8/24 ● 172.16.0.4/16

● 1.1.1.1/8
IP in Bin 00000001.00000001.00000001.00000001
Subnet mask In decimale 8.
Subnet mask in binario 1111111.00000000.00000000.0000000
Utilizzando operatore logico AND, 5 AND 7 = 00000001.00000000.00000000.00000000 che rappresanta IP Network in bin; quindi 1.0.0.0 in dec.
Quindi l'ultimo indirizzo de la network 00000001.11111111.11111111.11111111 che rappresenta l'IP Broadcast in bin; quindi 1.255.255.255 in dec.
Il primo indirizzo seguente quella della network sarà 0000001.00000000.00000000.00000001 che rappresenta l'IP Gateway in bin e quindi 1.0.0.1 in dec.
ABBIAMO QUINDI PER ● 1.1.1.1/8
IP Network: 1.0.0.0/8
IP Broadcast: 1.255.255.255/8
IP Gateway: 1.0.O.1/8
Otteti Host=3 ; Otteti rete=1.


● 128.1.6.5/12
il processo è approssivamente lo stesso dal processo precedente solo che qui possiam spieghare la conversione di 120 in base bin
128/2=64 con resto è 0*, 64/2=32 con resto 0*, 32/2=16 R=0*, 16/2=8 R=0, 8/2=4 R=0*, 4/2=2 R=0*, 2/2=0* R=0*; ci fa 7 Resto Nullo con 0000000 ci 
manca 1 un numero binario per completare a 8 numeri aggiungeremo quindi 1 a sinistra per completare visto che i zeri non possono stare a sinistra e gli uno a destra. quindi 128 in bin risulta essere 100000000 bin.
Abbiamo quindi:
IP Network: 128.0.0.1/12
IP Broadcast: 128.15.255.255/12
IP Gateway: 128.0.O.1/12
Otteti Host=2 ; Otteti rete=2.


● 200.1.2.3/24
IP Network: 128.0.0.1/12
IP Broadcast: 128.15.255.255/12
IP Gateway: 128.0.O.1/12
Otteti Host=2 ; Otteti rete=2.


● 192.192.1.1/22
Per questo caso C'è l'importanza di notificare che le rete partono 4 in 4 perché abbiamo l'ottetto interessante=252 e 256-252=4 sara importante per l'ssegnazione dell'IP Broadcast.
IP Network: 192.192.0.0/22
IP Broadcast: 192.192.3.255/22
IP Gateway: 192.192.0.1/22
Otteti Host=2 ; Otteti rete=3.


● 126.5.4.3/9
Per questo caso C'è l'importanza di notificare che le rete partono 128 in 128 perché abbiamo l'ottetto interessante=128 e 256-128=128 sara importante per l'ssegnazione dell'IP Broadcast.
IP Network: 126.0.0.0/9
IP Broadcast: 126.127.255.255/9
IP Gateway: 126.0.0.1/9
Otteti Host=3 ; Otteti rete=1.


● 200.1.9.8/24
IP Network: 200.1.9.0/24
IP Broadcast: 200.1.9.255/24
IP Gateway: 200.1.9.1/24
Otteti Host=1 ; Otteti rete=3.


● 172.16.0.4/16
IP Network: 172.160.0.0/16
IP Broadcast: 172.160.255.255/16
IP Gateway: 172.16.0.1/16
Otteti Host=2 ; Otteti rete=2.
