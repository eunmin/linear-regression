# linear-regression

* Install dependencies
```
brew install protobuf
brew install snappy

curl https://storage.googleapis.com/tensorflow/libtensorflow/libtensorflow-cpu-darwin-x86_64-1.0.0.tar.gz > libtensorflow.tar.gz
tar zxf libtensorflow.tar.gz -C /usr/local
mv /usr/local/lib/libtensorflow.so /usr/local/lib/libtensorflow.dylib
install_name_tool -id libtensorflow.dylib /usr/local/lib/libtensorflow.dylib
rm libtensorflow.tar.gz
```
