# Jeremia195410002/Responsi

berikut link image php:7.4-apache yang digunakan : 

                          https://hub.docker.com/_/php
                           
                           
Petunjuk : 
1. git clone pada terminal anda : 

                           git clone https://github.com/Jeremia195410002/responsi.git
                           
2. pull image dari dockerhub ke terminal anda : 

                            docker pull masjeje/cloud


3. masuk kedalam direktori file yang diambil dari github : 

                            cd Jeremia195410002


4. setelah masuk kedalam direktori Jeremia195410002/ jalankan perintah berikut :

                            docker-compose up -d


5. setelah selesai buka web browser anda lalu masuk ke localhost : 

                            localhost --> masuk ke menu web
                            
                            localhost:8080 --> masuk database
 
 6. untuk membuat web bisa melakukan CRUD lakukan setting pada database, Log in ke database : 
 
                            Username : root
                            password : example
                            Database : (kosongkan, jangan di isi)
                            
                            
    lalu create database dengan nama : dj                    
    
    buat tabel dengan nama : tj
    
    lalu buat colom : 
    
                    id  | int | length (kosongkan) |  options (koosngkan) | NULL (kosongkan)  | AI (conteng, ini primary key) | sisanya kosongkan
                    
                    nama  | varchar | lenght (25) | options (default) | sisanya kosongkan
                    
                    nim | int | length (9)  | sisanya kosongkan
                    
                    Default values (conteng), Comment (conteng)
                    
                    lalu save.
                    
7. buka lagi localhost, lalu masuk ke menu CRUD. sekarang telah bisa melakukan proses CRUD pada web ini.


    
                        
