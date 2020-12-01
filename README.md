Instruction for a basic development setup:

    virtualenv -p python3 .virtualenv
    source virtualenv/bin/activate
    pip3 install -r requirements.txt

Rename a file from ki_34668_16p.20180402143731.csv to 34668.csv:

    rename 's/.2018*\d+//' *
    rename 's/^(.*?)\_//' *
    rename 's/_16p//' *
