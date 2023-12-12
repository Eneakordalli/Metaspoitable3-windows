Installing metaspoitable3 on WINDOWS (ENG)

1. First, vagrant must be downloaded at the url: https://developer.hashicorp.com/vagrant/downloads
2. AMD64 or I686 must be downloaded based on the processor.
3. Proceed with the installation of vagrant by clicking ok each step. In the end, it will ask to be restarted and it must be done.
4. By opening cmd from the desktop, we must create the right folder:
     - mkdir metasploitable3-workspace
     - cd metasploitable3-workspace
5. Then entering the created folder we must open powershell (shift + right mouse):
     - Invoke-WebRequest -Uri "https://raw.githubusercontent.com/rapid7/metasploitable3/master/Vagrantfile" -OutFile "Vagrantfile"
     - vagrant up
6. Virtualbox will bring up some popups regarding the configuration of the interface and you must click ok or allow.
7. We have to wait until ubuntu and windows server are installed and start automatically


Instalimi i metaspoitable3 ne WINDOWS (AL)

1. Si fillim duhet te shkarkohet vagrant tek url: https://developer.hashicorp.com/vagrant/downloads
2. Ne baze te procesorit duhet shkarkuar AMD64 ose I686.
3. Procedojme me instalimin e vagrant duke klikuar ok cdo hap. Ne fund do kerkoje te behet restart dhe duhet bere me patjeter.
4. Duke hapur cmd nga desktop duhet te krijojme folderin e duhur :
    - mkdir metasploitable3-workspace
    - cd metasploitable3-workspace
5. Pastaj duke hyre te folderi i krijuar duhet te hapim powershell (shift + right mouse):
    - Invoke-WebRequest -Uri "https://raw.githubusercontent.com/rapid7/metasploitable3/master/Vagrantfile" -OutFile "Vagrantfile"
    - vagrant up
6. Virtualbox do te nxjeri disa popup ne lidhje me konfigurumin e interfare dhe duhet klikuar ok ose allow. 
7. Duhet te presim sa te instalohet ubuntu dhe windows server dhe te startohet automatikisht 
