Instruction for a basic development setup:

    virtualenv -p python3 .virtualenv
    source virtualenv/bin/activate
    pip3 install -r requirements.txt

# Tips

Rename all files in a folder from ki_34668_16p.20180402143731.csv to 34668.csv:

    sudo apt-get install rename
    rename 's/.201804*\d+//' *
    rename 's/^(.*?)\_//' *
    rename 's/_16p//' *
