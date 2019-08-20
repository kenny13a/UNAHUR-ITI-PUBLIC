#!/bin/bash
function inst_xampp(){
echo "Descargar XAMPP??? 142mb"
select yn in "Si" "No"; do
    case $yn in
        Si ) wget https://www.apachefriends.org/xampp-files/7.2.6/xampp-linux-x64-7.2.6-0-installer.run; break;;
        No ) break;;
    esac
done

sudo chmod +x xampp-linux-x64-7.2.6-0-installer.run

sudo ./xampp-linux-x64-7.2.6-0-installer.run

# sudo cp "com.ubuntu.pkexec.xampp.policy" /usr/share/polkit-1/actions

echo "Instalación finalizada."
echo "IMPORTANTE: Para utilizar el programa abra una terminal y escriba:"
echo "$(tput setaf 3)      sudo /opt/lampp/manager-linux-x64.run $(tput sgr 0)"
echo ""

}

sudo apt-get autoremove
    if [ "$?" = "0" ]; then
	echo "$(tput setaf 2) Puede continuar $(tput sgr 0)"
else
    echo "$(tput setaf 1) ERROR reinicie la pc $(tput sgr 0)"
fi

echo "Estructuras de persistencia"


echo "Instalar  xampp???"
select yn in "Si" "No"; do
    case $yn in
        Si ) inst_xampp; break;;
        No ) break;;
    esac
done



echo "TERMINADO"
echo "autor: santiago.maydana@unahur.edu.ar"

