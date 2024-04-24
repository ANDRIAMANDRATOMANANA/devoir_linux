# devoir_linux
    ÉTAPE D’ INSTALLATION DE MYSQL
    
    Etape 1:Télechargement du source sur github 
    mysql 8.3.0.tar.gz
    Etape 2:Décompression et désarchivage du fichier source
    $tar -zxvf mysql 8.3.0.tar.gz
    Etape 3:Installation
    $cd mysql 8.3.0
    $mysql 8.3.0/
    $mysql 8.3.0/ ./configure
    Error:./configure:no such file or directory
    $mysql 8.3.0/ ls
    $mysql 8.3.0/ more README
    Installation des dépendance nécessaire
    openssl version 
    cmake
    $mysql 8.3.0/mkdir axen
    $mysql 8.3.0/cd axen
    $mysql 8.3.0/build/sudo cmake ..
    Error:dépendance necessaire:flex, bison, zlib
    installation de ces dépendance
    $mysql 8.3.0/build/sudo cmake ..
    $mysql 8.3.0/build/ make
    $mysql 8.3.0/build/make install
                        EXPORTATION
    $echo ‘export PATH=$PATH /usr /local/bin’ >>.bashrc
    
    
    
  
      
    ÉTAPE D’INSTALLATION APACHE 
    Etape 1:Télechargement du source sur github 
    Code source:httpd-2-4-59.tar.gz
    Etape 2:Décompression et désarchivage du fichier source
    $gunzip httpd-2-4-59.tar.gz
    $tar -xvf httpd-2-4-59.tar
    Etape 3:Installation
    $cd  httpd-2-4-59
    $httpd-2-4-59/./configure
    Error :no such files or directory
    $httpd-2-4-59/ls
    $httpd-2-4-59/more README 
    $httpd-2-4-59/./buildconf
    Error:APR not found
    Installation des dépendances 
    apr version
    apr-util version
    $httpd-2-4-59/./configure
    Error:APR could not found
    $httpd-2-4-59/ ./configure  --with-apr=/usr/local/apr/bin
    $httpd-2-4-59/ sudo make 
    $httpd-2-4-59/sudo make install
                                      Exportation 
    $httpd-2-4-59/ echo ‘export PATH=$PATH /usr/local/bin’ >>.bashrc
    
    
    
  
    ÉTAPE D’INSTALLATION DE PHP 
    Etape 1:Télechargement du code source sur github 
    Code source:php-8.2.18.tar.gz
    Etape 2:Décompression et désarchivage du fichier source
    $gunzip php-8.2.18.tar.gz
    $tar -xvf php-8.2.18.tar
    Etape 3:Installation
    $cd   php-8.2.18
    $  php-8.2.18/./configure
    Error:no such files or directory
    $php-8.2.18/ls
    $php-8.2.18/more README .md
    $php-8.2.18/more INSTALL
    installation des dépendances necessaires
    $httpd-2-4-59/sudo apt install -y pkg -config build -essential autoconf bison re2c
    $php-8.2.18/./buildconf
     $php-8.2.18/./configure  
    $php-8.2.18// sudo make 
    $php-8.2.18/sudo make install
                                     Exportation                 
    ~$echo ‘export PATH=$PATH /usr/local/bin’ >>.bashrc
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    

