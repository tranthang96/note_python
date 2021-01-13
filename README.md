# note_python
lệnh pip3:
  cài đặt theo đường dẫn 
    pip3 install module -t vị_trí_python_path
   
    VD
    pip3 isntatll serial -t /home/thang/package_python/serial
    như vậy path python cần add là: /home/thang/package_python/serial
  Cache pip3 trong đường dẫn ~/.cache/pip , có thể remove đường dẫn này 
   
   
ADD PYTHONPATH
 C1. thêm module sys add sys.path vào python script
    vd sys.path.append('/home/thang/package_python/serial')
    
 C2: thêm biến PYTHONPATH vào trong file ~/.profile
    VD:
    export PYTHONPATH="/home/thang/package_python/serial:/home/thang/package_python/mysql-connector:$PYTHONPATH"
    
    #export PYTHONPATH=/home/thang/package_python/serial
    #export PYTHONPATH=/home/thang/package_python/mysql-connector
    #export PYTHONPATH=/home/thang/package_python/pyqt5
install mysql-connector

  sudo apt install python3-testresources
  pip3 install 
