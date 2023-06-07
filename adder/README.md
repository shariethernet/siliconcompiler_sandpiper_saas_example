# Using TL-V as a frontend in SiliconCompiler

You can see the [adder.tlv](./adder.tlv) which is the example TL-Verilog file and a sample  constraints file [adder.sdc](./adder.sdc) 

You can invoke siliconcompiler in two ways:
- Python
    You can use the siliconcompiler library and write a python script as seen in [adder.py](./adder.py) to configure your flow in any way supported by siliconcompiler
- CLI
    You can also write one line commands to run siliconcompiler as seen in [run.sh](./run.sh)

The provided scripts are only an example of using the TL-Verilog front-end in Siliconcompiler. To create/develop you own flows or to know more about using SiliconCompiler refer the [docs](https://docs.siliconcompiler.com/en/stable/)
