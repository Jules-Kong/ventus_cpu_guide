# ventus_cpu_guide

#### 下载
ventus cpu的只需要
* llvm-ventus : git clone -b dev_cpu https://github.com/THU-DSP-LAB/llvm-project.git
* ocl-icd : git clone https://github.com/OCL-dev/ocl-icd.git   
* pocl : git clone -b dev_cpu https://github.com/THU-DSP-LAB/pocl.git   

### 构建和使用
借鉴ventus教程 https://github.com/THU-DSP-LAB/llvm-project ；    
注意，export POCL_DEVICES="basic" 即可；   

### 测试套教程
* cts   
  https://github.com/Jules-Kong/OpenCL-CTS-guide     
* gpu-rodinia   
  https://github.com/Jules-Kong/gpu-rodinia     
