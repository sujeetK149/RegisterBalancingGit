
# MaskedHLS++

Fast Register Balancing at behavioral level for generating minimum latency designs using MaskedHLS

## Installing the dependencies

Install my-project with npm

```bash
  pip install -r requirements.txt
```
    
## How to run

cd to the folder where the script.py file is present.
Run the following command:
```
python ./script.py <options here>
```
The following operations are supported.
```
--topModule : Name of the top topModule (mandatory)
--inputFile : Name of the input file (it is mandatory too and should
              be in the same directory as script.py
--rtlFile : the final verilog code file(default is output.v)
--bitWidth : specify the bitWidth for the rtl code
--checkBalancing : set to 1 to verify the balancing(default is 0)
```

