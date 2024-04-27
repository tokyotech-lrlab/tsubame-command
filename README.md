# Commandline Tools for using Tsubame

### job-script

- Setup
  ```
  echo "export PATH="/gs/bs/tga-t2glrlab-1/tsubame-command:$PATH" >> ~/.bashrc
  source ~/.bashrc
  ```
- Usage
  ```
  head -n 8 $(which job-script)
  ```
- Example
  ```
  job-script -N example_job -l gpu_1=1 -t 1:00:00 -c python main.py
  ```
