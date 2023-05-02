# people_detection

1. pip install numpy
2. pip install paddlepaddle-gpu==2.4.2 -f https://www.paddlepaddle.org.cn/whl/linux/mkl/avx/stable.html
3. pip install -r requirements.txt
4. python setup.py install

## CUDA & CUDNN versions matching

### Windows

| Paddle version                  | CUDA | CUDNN | TRT      | INSTALL COMMAND                                                                                                  |
|---------------------------------|------|-------|----------|------------------------------------------------------------------------------------------------------------------|
| paddlepaddle-gpu==2.4.2.post117 | 11.7 | 8.4.1 | 8.4.2.4  | `pip install paddlepaddle-gpu==2.4.2.post117 -f https://www.paddlepaddle.org.cn/whl/windows/mkl/avx/stable.html` |
| paddlepaddle-gpu==2.4.2.post116 | 11.6 | 8.4.0 | 8.4.0.6  | `pip install paddlepaddle-gpu==2.4.2.post116 -f https://www.paddlepaddle.org.cn/whl/windows/mkl/avx/stable.html` |
| paddlepaddle-gpu==2.4.2.post112 | 11.2 | 8.2.1 | 8.2.4.2  | `pip install paddlepaddle-gpu==2.4.2.post112 -f https://www.paddlepaddle.org.cn/whl/windows/mkl/avx/stable.html` |
| paddlepaddle-gpu==2.4.2         | 10.2 | 7.6.5 | 7.0.0.11 | `pip install paddlepaddle-gpu==2.4.2 -i https://pypi.tuna.tsinghua.edu.cn/simple`                                |

### Linux

