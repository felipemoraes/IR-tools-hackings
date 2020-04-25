# IR-tools-hackings
IR tools hackings



# 1) Instalar pyndri no MacOS com Anaconda

- Adiciona no arquivo setup.py a seguinte linha depois de `undef_macros=['NDEBUG']`

`extra_compile_args = ["-std=c++11"]`


