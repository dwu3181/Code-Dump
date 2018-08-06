with open('mapsmetadata.py', 'r') as fin:
    data = fin.read().splitlines(True)
with open('mapsmetadata.py', 'w') as fout:
        fout.writelines(data[1:])
