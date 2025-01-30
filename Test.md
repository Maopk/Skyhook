# 编译命令（需安装ONNX Runtime）
g++ -O3 -march=native docking_system.cpp -lonnxruntime -lpthread -o docking

# 运行测试
./docking
