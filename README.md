# MediTicketTracker-MTT-
A tool to track the used and unused vouchers

How does it work?
1.You copy all your codes in the codes.txt file.
2.Go to dist/MTT.exe and execute it.
3.It will ask for the location of the codes.txt file.
  Right click on codes.txt and copy the location. 
  Paste the location into the window with the prompt and add \codes.txt after your copied location.
4.Now it should work and give you all the codes with eiter used or unused back. 


TODO: 
Damit dieses Tool mal bei uns am Server laufen kann muss einiges geändert werden
.) Verwendung des Remote Web-Drivers anstelle des Chrome-Drivers da auf unserem Server wahrscheinlich kein Chrome oben ist
    https://selenium-python.readthedocs.io/installation.html#downloading-selenium-server
.) Pocketbase Integration
  .] Die Codes sollten nicht mehr aus einem .txt File eingelesen werden, sondern mithilfe der API aus der Datenbank geladen werden
  .] Anstelle die Ergebnisse ob die Codes verbraucht wurden in ein TXT File zu schreiben,
     sollte der Status der Codes in der Datenbank aktualisiert werden

.) Beim deployment auf dem Server soll dann so eingestellt werden, dass das Programm jeden Tag einmal läuft und somit alle Codes abfrägt.
  