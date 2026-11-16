jeffersonnatividad@AirdiJefferson ~ % cd 
jeffersonnatividad@AirdiJefferson ~ % mkdir wa
mkdir: wa: File exists
jeffersonnatividad@AirdiJefferson ~ % cd wa
jeffersonnatividad@AirdiJefferson wa % mkdir test-comandi
jeffersonnatividad@AirdiJefferson wa % cd test-comandi
jeffersonnatividad@AirdiJefferson test-comandi % touch ciao.txt
jeffersonnatividad@AirdiJefferson test-comandi % vim ciao.txt
jeffersonnatividad@AirdiJefferson test-comandi % cat ciao.txt

Ciao, questo è il mio primo file creato con Vim da solo.
jeffersonnatividad@AirdiJefferson test-comandi % mkdir musica immagini testi
jeffersonnatividad@AirdiJefferson test-comandi % mv ciao.txt testi/
jeffersonnatividad@AirdiJefferson test-comandi % ls testi
ciao.txt
jeffersonnatividad@AirdiJefferson test-comandi % touch brani.txt
jeffersonnatividad@AirdiJefferson test-comandi % cp brani.txt musica/
jeffersonnatividad@AirdiJefferson test-comandi % cd musica
jeffersonnatividad@AirdiJefferson musica % ls
brani.txt
jeffersonnatividad@AirdiJefferson musica % rm ../brani.txt
jeffersonnatividad@AirdiJefferson musica % cd ..
jeffersonnatividad@AirdiJefferson test-comandi % mkdir logs
jeffersonnatividad@AirdiJefferson test-comandi % cd logs
jeffersonnatividad@AirdiJefferson logs % mkdir browser server
jeffersonnatividad@AirdiJefferson logs % touch logs.txt
jeffersonnatividad@AirdiJefferson logs % cp logs.txt browser && cp logs.txt server
jeffersonnatividad@AirdiJefferson logs % cp logs.txt browser
jeffersonnatividad@AirdiJefferson logs % cp logs.txt server
jeffersonnatividad@AirdiJefferson logs % ls browser
logs.txt
jeffersonnatividad@AirdiJefferson logs % ls server
logs.txt
jeffersonnatividad@AirdiJefferson logs % cd ..
jeffersonnatividad@AirdiJefferson test-comandi % pwd
/Users/jeffersonnatividad/wa/test-comandi
jeffersonnatividad@AirdiJefferson test-comandi % rm -r logs
jeffersonnatividad@AirdiJefferson test-comandi % ls
immagini	musica		testi
jeffersonnatividad@AirdiJefferson test-comandi % 