# Example of using Sandpiper-SaaS as a frontend in SiliconCompiler

This repository has a simple [example](./adder), that shows how to use Sandpiper-SaaS as a front end to convert TL-Verilog to SystemVerilog/Verilog in any flow supported by SiliconCompiler (or your own flow)

- Note: The front-end support is not available in the main SiliconCompiler Repo, and is maintained as a fork [here](https://github.com/shariethernet/siliconcompiler)
- You can either install siliconcompiler following the instructions in the document or you can run the Docker image that I have provided [here](https://github.com/shariethernet/siliconcompiler/tree/main/siliconcompiler_docker) using the following steps

```
git clone  https://github.com/shariethernet/siliconcompiler
cd siliconcompiler/siliconcompiler_docker
chmod +x run-docker.sh
./run-docker.sh
```