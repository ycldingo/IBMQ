# Install Qiskit
## macOS
1. Download Anaconda. The detail instruction is indicated in repository *Anaconda-Distribution*.
2. Open a terminal and switch to your working folder by `cd FOLDER_NAME`. To go back: `cd ..`.

3. In order not to pollute the environment, it is suggested to create a new environment, Suppose the new environment is called *IBMQ*:
  - create new environment *IBMQ*:
```javascript
conda create -n IBMQ python=3
```

or

```javascript
conda create --name IBMQ python=3
```
   - go to the environment *IBMQ*: 
```javascript
conda activate IBMQ
```
   - back to the base: 
 ```javascript
conda deactivate
```

4. Install packages in a specific environment: switch to a specific environment and run
```javascript
pip install PACKAGE_NAME
```
Here, install `jupyter notebook`, `matplotlib`, `qiskit`.

5. If you successfully install `jupyter notebook`, by running `jupyter notebook`, you can open it in your browser.


# Verify version
1. Open a terminal and run `jupyter notebook`. 

2. Create a new Python script and run
```python
## Check qiskit version
from qiskit import version
version._get_qiskit_versions()
```


