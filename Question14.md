1) 

![image](https://github.com/user-attachments/assets/80e46c0d-c87e-4e6a-a8de-4195ded8cc72)

2) ~/.ssh/authorized_keys

3) 

![image](https://github.com/user-attachments/assets/5ed2cc0c-ab6c-4a3e-9967-0ad5ddd32aa4)


4) 
commande pour se connecter avec la clé: 

![image](https://github.com/user-attachments/assets/f55518c0-8e68-4362-b0bf-869a94675ec3)


commande pour obtenir le fingerprint a comparer :
ssh-keygen -lf /etc/ssh/ssh_host_ed25519_key.pub

et on compare ce fingerprint a celui que l'on a eu lors de la première connexion
