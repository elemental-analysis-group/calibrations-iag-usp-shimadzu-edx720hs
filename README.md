Instruction for a basic development setup:

    virtualenv -p python3 .virtualenv
    source virtualenv/bin/activate
    pip3 install -r requirements.txt

### Tips

Rename all files in a folder from ki_34668_16p.20180402143731.csv to 34668.csv:

    sudo apt-get install rename
    rename 's/.201804*\d+//' *
    rename 's/^(.*?)\_//' *
    rename 's/_16p//' *


### problema winqxas

A partir do Nb (Z=41), o WinQxas passou a apresentar a linha L3M5 no TXT, junto com a linha K.
Não há distinção entre uma e outra, o que pode trazer problema quando marca-se as duas.
A linha L vem primeiro. NESTA PLANILHA USAMOS SOMENTE A LINA L3M5 PARA TODOS OS ELEMENTOS

No winqxas, quando possível use duas ROIs, exemplo: 31512




